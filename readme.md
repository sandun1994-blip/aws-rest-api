* npm install -g serverless
* serverless config credentials --provider aws --key 1234 --secret 5678

key = AKIA4SEHNZOWM7TCLZZY
pw = 8FSI/y53OBaLJg8Cnn3dLMVoT7t6ZFgRcA/Fhf6f

# Profile "default" is already configured in ~/.aws/credentials. Use the overwrite flag ("-o" or "--overwrite") to force the update.

# create serverless templae aws-nodejs
* serverless create -t aws-nodejs
* npm init -y


# Deploy
* serverless deploy
# Add Plugin
* npm i --save-dev serverless-iam-roles-per-function

https://<your user pool domain>/authorize?client_id=<your app client ID>&response_type=<code/token>&scope=<scopes to request>&redirect_uri=<your callback URL>

https://snd-dev.auth.us-east-1.amazoncognito.com/login?response_type=token&client_id=<your_app_client_id>&redirect_uri=<your_callback_url>


https://mynotescd-sand.auth.us-east-1.amazoncognito.com
https://mynotescd-sand.auth.us-east-1.amazoncognito.com/login?response_type=token&client_id=61k2ahukv6pd41kqs43duktbij&redirect_uri=http://localhost:3000