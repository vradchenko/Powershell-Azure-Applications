# Powershell-Azure-Applications
How Azure PowerShell management modules look in Azure sign-in logs:

| PowerShell cmdlet | Azure Application | Resource |
| ----------- | ----------- | ----------- |
| Connect-ExchangeOnline or Connect-IPPSSession | Microsoft Exchange REST API Based Powershell | Office 365 Exchange Online |
| Connect-AzureAD | Azure Active Directory PowerShell | Windows Azure Active Directory |
| Connect-Az | Microsoft Azure PowerShell | Windows Azure Service Management API |
| Connect-EXOPSSession or Connect-IPPSSession | Microsoft Exchange Online Remote PowerShell | Office 365 Exchange Online |

Watch out for non-admin user sign-ins into these Azure Applications. Can be an indication of data exfiltration from Azure and Azure Active Directory.
