# CSPLicenseInquiry
License inquiry and report script for HaloPSA using Microsoft Graph for Hack Together 2023.

This tool runs as an Azure Runbook and is triggered via webhook from HaloPSA. The script uses a multitenant app registration to look up current user license assignments and attempts to find zombie accounts or accounts that are licensed but deactivated or deleted. This helps to scavenge available licenses during the onboarding process. The report is returned to HaloPSA as an HTML fragment embedded in a private note.

![image](https://user-images.githubusercontent.com/68078971/222438389-9eb9f462-2fc3-4345-8282-c6d91b63b0cd.png)

