---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var oauth2PermissionGrants = await graphClient.Users["{id}"].Oauth2PermissionGrants
	.Request()
	.GetAsync();

```