---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const keyCredential = {
    keyCredential: {
        type: 'AsymmetricX509Cert',
        usage: 'Verify',
        key: 'MIIDYDCCAki...'
    },
    passwordCredential: null,
    proof: 'eyJ0eXAiOiJ...'
};

await client.api('/servicePrincipals/{id}/addKey')
	.post(keyCredential);

```