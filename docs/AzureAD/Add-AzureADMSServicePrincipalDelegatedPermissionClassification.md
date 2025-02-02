# Add-AzureADMSServicePrincipalDelegatedPermissionClassification

> /servicePrincipals/{servicePrincipal-id}/delegatedPermissionClassifications

## Data

+ AAD Command: [Add-AzureADMSServicePrincipalDelegatedPermissionClassification](https://docs.microsoft.com/en-us/powershell/module/AzureAD/Add-AzureADMSServicePrincipalDelegatedPermissionClassification)
+ AAD Module: AzureAD
+ Graph Command: [New-MgServicePrincipalDelegatedPermissionClassification](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Applications/New-MgServicePrincipalDelegatedPermissionClassification)
+ Graph Module: Microsoft.Graph.Applications

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application||
|Delegate||

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|ServicePrincipalId|ServicePrincipalId|System.String|System.String||
|PermissionName|PermissionName|System.String|System.String||
|Classification|Classification|System.Nullable/Microsoft.Open.MSGraph.Model.DelegatedPermissionClassification+ClassificationEnum|System.String||
|PermissionId|PermissionId|System.String|System.String||

