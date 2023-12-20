# Looker Embed Sample

This example extends the original sample provided in https://github.com/looker/looker_embed_sso_examples/tree/master

This example is meant for **testing purposes only**, and it is **not meant for production purposes** it is always highly recommended to keep your keys stored in secret vaults and follow good engineering practices.

Using this example you are expected to:
- Quickly deploy an iframe from a single Looker dashboard by using only the endpoint value
- Quick test how easy it is to integrate Looker Embedded Analytics to any website


After editing the information, the example can be quickly packed and deployed to cloud run by using the following code:
If you didn't yet, before running the code [install gcloud command](https://cloud.google.com/sdk/docs/install), and then [log in](https://cloud.google.com/sdk/gcloud/reference/auth/login) 

```
    // cd to the folder where the code is
    gcloud run deploy [SERVICE NAME] --source .
```

After answering the prompt questions, gcloud will then containerise the application and push as a new revision of the specified service.

Extra configurations such as unnauthenticated calls and users might be necessary and can be done from the GCP console.

After testing, it is highly recommended that you delete your cloud run instance to not consume resources or impose risks to your project.
