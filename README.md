Find and Delete Empty Resource Groups (authenticate using Service Principal)
============================================================================

            

![Image](https://github.com/azureautomation/find-and-delete-empty-resource-groups-(authenticate-using-service-principal)/raw/master/Find-EmptyResourceGroups_connect_with_serviceprincipal.png)


**DESCRIPTION**


This runbook connects to Azure using a child runbook and finds (and optionally deletes) resource groups with no resources. 



You can attach a schedule to this runbook to run it periodically for cleanup purposes.


**DEPENDENCIES**


This runbook requires 'Connect to Azure' child runbook to be imported and published in your automation account:
https://gallery.technet.microsoft.com/scriptcenter/Connect-to-Azure-Using-87ff57a6


**OPTIONAL INPUT PARAMETERS**


 - DeleteEmptyGroups - boolean flag that can be set to TRUE to delete empty groups if found. Defaulted to FALSE.


**OUTPUT: **List of resource group names that have no resources.


**OUTPUT TYPE:** System.String


**AUTHOR: **Stas Kuvshinov (Microsoft)


**LASTEDIT: **2016-06-02


 

 

 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
