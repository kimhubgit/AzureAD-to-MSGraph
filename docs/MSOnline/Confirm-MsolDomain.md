# Confirm-MsolDomain

> /domains/{domain-id}/verify

## Data

+ AAD Command: [Confirm-MsolDomain](https://docs.microsoft.com/en-us/powershell/module/MSOnline/Confirm-MsolDomain)
+ AAD Module: MSOnline
+ Graph Command: [Confirm-MgDomain](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Identity.DirectoryManagement/Confirm-MgDomain)
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Domain.ReadWrite.All|
|Delegate|Domain.ReadWrite.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|SigningCertificateUpdateStatus||Microsoft.Online.Administration.SigningCertificateUpdateStatus|||
|ActiveLogOnUri||System.String|||
|NextSigningCertificate||System.String|||
|FederationBrandName||System.String|||
|DefaultInteractiveAuthenticationMethod||System.String|||
|LogOffUri||System.String|||
|MetadataExchangeUri||System.String|||
|TenantId||System.Nullable/System.Guid|||
|PreferredAuthenticationProtocol||System.Nullable/Microsoft.Online.Administration.AuthenticationProtocol|||
|SupportsMfa||System.Nullable/System.Boolean|||
|OpenIdConnectDiscoveryEndpoint||System.String|||
|PassiveLogOnUri||System.String|||
|SigningCertificate||System.String|||
|IssuerUri||System.String|||
|ForceTakeover||Microsoft.Online.Administration.ForceTakeoverOption|||
|PromptLoginBehavior||System.Nullable/Microsoft.Online.Administration.PromptLoginBehavior|||
|DomainName||System.String|||

