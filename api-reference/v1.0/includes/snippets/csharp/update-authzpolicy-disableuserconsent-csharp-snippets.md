---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var authorizationPolicy = new AuthorizationPolicy
{
	DefaultUserRolePermissions = new DefaultUserRolePermissions
	{
		PermissionGrantPoliciesAssigned = new List<String>()
		{
		}
	}
};

await graphClient.Policies.AuthorizationPolicy
	.Request()
	.UpdateAsync(authorizationPolicy);

```