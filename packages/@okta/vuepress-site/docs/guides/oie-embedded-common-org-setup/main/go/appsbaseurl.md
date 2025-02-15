### Add a trusted origin and enable CORS

For web applications, you have to identify your app's URL as a trusted origin and enable [CORS](/docs/guides/enable-cors/overview/):

1. In the Admin Console, go to **Security** > **API**.
1. On the **API** page, select the **Trusted Origins** tab.
1. Click **Add Origin** and then enter a name for the organization origin.
1. In the **Origin URL** field, specify the base URL of the website that you want to allow cross-origin requests from. If you are using the sample app, specify `http://localhost:8000/`.
1. Under **Type**, select the **CORS** and **Redirect** check boxes.
1. Click **Save**.
