# gitlab_provision_webhooks

1. A change is pushed into GitLab.
2. GitLab webhooks calls http://SERVER_NAME:9000/pull, which is provided by HookHand
3. Pull script is executed on the server by HookHand server
4. The server is provisioned!

This requires installation of HookHand

https://github.com/MikeMcQuaid/HookHand






