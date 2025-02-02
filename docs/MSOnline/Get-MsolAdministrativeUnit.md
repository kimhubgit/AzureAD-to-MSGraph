# Get-MsolAdministrativeUnit

> /directory/administrativeUnits | /directory/administrativeUnits/{administrativeUnit-id}

## Data

+ AAD Command: [Get-MsolAdministrativeUnit](https://docs.microsoft.com/en-us/powershell/module/MSOnline/Get-MsolAdministrativeUnit)
+ AAD Module: MSOnline
+ Graph Command: [Get-MgDirectoryAdministrativeUnit](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Identity.DirectoryManagement/Get-MgDirectoryAdministrativeUnit)
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|AdministrativeUnit.Read.All, AdministrativeUnit.ReadWrite.All, Directory.Read.All, Directory.ReadWrite.All|
|Delegate|AdministrativeUnit.Read.All, AdministrativeUnit.ReadWrite.All, Directory.AccessAsUser.All, Directory.Read.All, Directory.ReadWrite.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|All|All|System.Management.Automation.SwitchParameter|System.Management.Automation.SwitchParameter||
|TenantId||System.Nullable/System.Guid|||
|ObjectId||System.Guid|||
|MaxResults||System.Int32|||
|UserPrincipalName||System.String|||
|UserObjectId||System.Nullable/System.Guid|||
|SearchString||System.String|||

