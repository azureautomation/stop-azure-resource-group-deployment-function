Stop Azure Resource Group Deployment Function
=============================================

            

 


This script stops an RG deployment . .  


It is the stop script that goes along with this: [https://gallery.technet.microsoft.com/scriptcenter/Azure-Resource-Group-6ee2c700](https://gallery.technet.microsoft.com/scriptcenter/Azure-Resource-Group-6ee2c700) 


 


**Stop-AzureRMDeploy -DP D1**

This will provide an out-gridview pop up to select the deployments that you want to cancel.

You can force the deployments in the Resource Group to stop via the force switch

**Stop-AzureRMDeploy -DP D1* * -Force**



** *** *


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
