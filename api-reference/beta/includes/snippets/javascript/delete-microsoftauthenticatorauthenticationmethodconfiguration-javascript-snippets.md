---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

await client.api('/policies/authenticationMethodsPolicy/authenticationMethodConfigurations/microsoftAuthenticator')
	.version('beta')
	.delete();

```