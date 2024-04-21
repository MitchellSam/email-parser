# email-parser

- check gmail to see if there are any emails with a specific label
- download emails, parse them with LLM, and save it to CRM
- Amazon Claude, terraform, lambda, event bridge cron, s3, prostgres serverless, AWS RDS


docker instance of postgres
venv with fastapi and psycopg2
  - use psycopg2 to connect to the db instance (cursor execute)
    - eg psycopg2.createconnection


Create a virtual environment
python3 -m venv venv

venv folder should be created
add it to .gitignore

use the venv
source venv/bin/activate
(can exit using deactivate)

python3 -m pip install fastapi
python3 -m pip install uvicorn
or
python3 -m pip install -r requirements.txt

import boto3
import psycopg2

python3 -m pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib

python3 server.py

https://www.youtube.com/watch?v=ex-4a08wwHE
https://developers.google.com/gmail/api/quickstart/python

https://ei.docs.wso2.com/en/latest/micro-integrator/references/connectors/gmail-connector/configuring-gmail-api/#:~:text=Click%20on%20Authorize%20APIs%20button,with%20configuring%20the%20Gmail%20API.

https://developers.google.com/oauthplayground
https://console.cloud.google.com/apis/credentials?project=gmailconnector-415222
https://console.cloud.google.com/apis/api/gmail.googleapis.com/credentials?project=gmailconnector-415222&pli=1

https://cloud.google.com/sdk/docs/install
https://developers.google.com/gmail/api/auth/web-server#authorizing_with_stored_credentials
https://cloud.google.com/iam/docs/service-accounts-create#python
