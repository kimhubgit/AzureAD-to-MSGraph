# Add-MsolAdministrativeUnitMember

> /directory/administrativeUnits/{administrativeUnit-id}/members/$ref

## Data

+ AAD Command: [Add-MsolAdministrativeUnitMember](https://docs.microsoft.com/en-us/powershell/module/MSOnline/Add-MsolAdministrativeUnitMember)
+ AAD Module: MSOnline
+ Graph Command: [New-MgDirectoryAdministrativeUnitMemberByRef](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Identity.DirectoryManagement/New-MgDirectoryAdministrativeUnitMemberByRef)
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|AdministrativeUnit.ReadWrite.All|
|Delegate|AdministrativeUnit.ReadWrite.All, Directory.AccessAsUser.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|AdministrativeUnitObjectId||System.Guid|||
|TenantId||System.Nullable/System.Guid|||
|AdministrativeUnitMemberObjectId||System.Nullable/System.Guid|||

