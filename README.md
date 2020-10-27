Automatically Download Microsoft Azure Billing Reports (Enterprise Agreement)
=============================================================================

            

This script uses the REST API to get the Enterprise Agreement billing reports for Azure in CSV format. These monthly reports are normally found in the Azure EA portal.  So the script can be used to automatically download Azure Billing reports for company
 personnel who do not have access to ea.azure.com.


Requirements:


- AccessKey: Get the Accesskey from ea.azure.com under Reports->Download Usage->API Access Key. Create a new Access key if needed. 


- Enrollment number: Get the Azure Billing Enrollment Number from ea.azure.com under Manage->Enrollment Number


 


Example:  .\Get-AzureEA_BillingDetails.ps1 -EnrollmentNo '1234567' -Month '2015-08' -Accesskey 'A23kdsk2kdjmskskskskdjdjdjdks'


 


Reports Downloaded:


-Pricing Report


-Detailed Report


-Summary Report


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
