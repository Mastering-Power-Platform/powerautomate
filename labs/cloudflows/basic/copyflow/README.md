# Creating a Basic Copy flow using Power Automate Templates

A good way to get started is to use a template that is suited to your organization's scenario. You can choose from a collection of templates to find the one that best matches your scenario. Search all templates or browse by category to find your scenario, and then follow the steps in the template to create a cloud flow from the template.

You can tweak templates by adding, editing, or removing triggers and actions to create your own flows. You can copy paste actions in the same flow or across flows to speed up the your tweaks.

## In this Lab

In this lab, you will create a cloud flow using a Power Automate template that will automatically copy files from OneDrive to SharePoint, Delete the file in OneDrive and send a notification.

* `Learning objectives`- Copy Flow using SaaS Connectors
* `Duration` - 20 minutes
* `Scenario` - A user or application uploads a file to OneDrive or any other cloud storage. This file will automatically be copied into the SharePoint document library.
* `Prerequisites` - Each student must have a OneDrive account using student user accounts and access to SharePoint document library. The OneDrive account must have a folder called Power Automate Demos.
* `Remarks` - The pdf file to be uploaded is available in the resources section of this lab.


## Task 1

Create a cloud flow from a template:
  a. Navigate to __Templates__ and search for __sharepoint onedrive__. Click on the first automated flow.

  <img src="https://github.com/user-attachments/assets/260ee0a4-7906-42b3-88c4-6dc5042f236c" alt="image" width="50%" height="50%">


  b. Ensure all connections are authenticated. If not, please fix your connections. Click __Continue__.

  <img src="https://github.com/user-attachments/assets/001d273a-36cd-43b6-89fa-6c2b6252df50" alt="image" width="50%" height="50%">


  c. Update the values in the trigger. OneDrive Folder Location: __Power Automate Demos__.
    
  <img src="https://github.com/user-attachments/assets/f716e6e4-4380-497e-8448-1a2567e472ee" alt="image" width="50%" height="50%">


  d. Update the __Create File__ action
  
  - Site Address: https://edumscloud.sharepoint.com/sites/PowerAutomateDemos (Link to your SP site)
  - Folder Path: /Shared Documents
  - File Name: File name
  - File Content: Body
 
  <img src="https://github.com/user-attachments/assets/83d6bb9c-edcf-44b0-8b3a-36309bf7cc56" alt="image" width="50%" height="50%">


e. __Save__ the flow

## Task 2

Test the flow by uploading the pdf file (or any other file) to the OneDrive folder __Power Automate_Demos_:
a. Navigate to your SharePoint list, for example, by clicking on the list name on the Quick Launch bar.

  <img src="images/image-4.png" alt="image" width="50%" height="50%">


b. This will automatically trigger the flow.

c. Check the flow status. It should be running:

  <img src="images/image-5.png" alt="image" width="50%" height="50%">


d. Verify if the file was copied by navigating to the shared documents in __Power Automate Demos__ SharePoint Site

  <img src="images/image-6.png" alt="image" width="50%" height="50%">


e. Verify the flow run:

  <img src="images/image-6.png" alt="image" width="50%" height="50%">
