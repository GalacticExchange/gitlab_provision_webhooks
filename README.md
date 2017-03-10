Gitlab Provision Webhooks

Provision/update git repository on the server on commit using Gitlab Webhooks

1. A change is pushed into GitLab.
2. GitLab webhook calls http://SERVER_NAME:9000/pull endpoint, which is provided by HookHand. 

   Go to GitLab Webhooks UI to create the webhook

3. Pull script is executed on the server by HookHand server
4. The server is provisioned!

This requires installation of HookHand

https://github.com/MikeMcQuaid/HookHand






