# chatgpt_via_GCP
POC to test the working of the chat GPT API's and test the google cloud functions in GCP.

steps to deploy the cloud function:
1. Execute the below command by updating the secret key.
gcloud functions deploy get_ingredients --runtime python310 --trigger-http --allow-unauthenticated --set-env-vars OPENAI_API_KEY=<your-secret-key-of-openai-api>
