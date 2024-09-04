
Welcome to the __Mastering Power Automate__ course labs.

These are hands-on resources to help you learn Power Automate.

## Pre-req

Access to Office 365 (Power Automate, Outlook, SharePoint and OneDrive) using lab credentials.

### Find your lab environment details
- [List of usernames for this course](https://edumscloud-my.sharepoint.com/:x:/g/personal/siddharthdwn_edumscloud_onmicrosoft_com/ETGAI96lJSJJvabhN1Ni6ioBrteRjWJ-TVz3JCqhLJ0MXg?e=uOBXt8)
- Please type your name against the chosen student username. Please use the same username throughout this course to maintain consistency.

### Log in to Office 365 using your lab credentials
- Navigate to [Office 365](https://www.office.com/) in an **incognito** browser window
- Click on **Sign In** and enter your **username** and **password** for the selected student account
- Please **DO NOT** use your Amgen credentials for this course
- Click **Next** when prompted for **Action Required** for additional security:

<img width="448" alt="image" src="https://github.com/user-attachments/assets/c66963ef-364d-4e5c-93db-c97be8fac003">

- Setup Microsoft Authenticator app for your account:

<img width="770" alt="image" src="https://github.com/user-attachments/assets/1d7f8cb3-2fc0-47ae-999e-289001dc3fad">

- Click **Next** and follow the instructions on the screen to set up multi-factor authentication using the **Authenticator** app or your **mobile number**.

<img width="770" alt="image" src="https://github.com/user-attachments/assets/fb765253-e26d-4a27-b925-80ccb2c1bf33">




### Activate your developer license (Optional, as this license is already activated for lab users)
The Microsoft365 license provides a Standard Power Apps and Power Automate license which is good enough for most labs. However, some labs require a Premium connector; the Power Apps Developer Plan gives you access to __Premium__ features of the product for free. The main restriction of the Developer license is that flows and applications created with this license cannot be used in production.
Follow the instruction described here [Sign up for Power Apps Developer Plan - Power Apps | Microsoft Learn](https://learn.microsoft.com/en-us/power-platform/developer/plan) to activate this license.
A dedicated Power Platform environment will be generated as part of this activation, and this is where you will do the exercises.


### Create your own SharePoint site 

All students must login to [SharePoint Online](https://edumscloud.sharepoint.com/) and create a new __Team Site__.
Click on __Home__ > __+ Create Site__ > __Team Site__ > __Standard Team__ > __Use Template__

[Detailed steps to create a team site on SharePoint](https://support.microsoft.com/en-us/office/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d)


### Slides
Please download the slides by clicking [here](https://edumscloud-my.sharepoint.com/:f:/g/personal/siddharthdwn_edumscloud_onmicrosoft_com/Ek93qf0hddVAhs5HgB90czkBxqzJG7Aztzx43ZUPfxwgLQ?e=3ZCqah).


# Day 1

## Basic Cloud Flows

- [Creating a cloud flow using a template](labs/cloudflows/basic/templateflow/README.md)
- [Copy files between Dropbox and SharePoint](labs/cloudflows/basic/copyflow/README.md)
- [Creating a flow from scratch - Overdue Tasks](labs/cloudflows/basic/flowfromscratch/README.md)

## Advanced Cloud Flows
- [Power Automate flow that interacts with Dataverse](labs/cloudflows/advanced/dataverseflow/README.md)
- [Using Expressions in Power Automate](labs/cloudflows/advanced/expressions/README.md)
- [Conditions and switch statements inside Power Automate](labs/cloudflows/advanced/controlflow/README.md)
- [Advanced flow with Flow control, Variables, Expressions and Loops](labs/cloudflows/advanced/advflow/README.md)

# Day 2

## Advanced Cloud Flows - Recap and more features
- [Cloud flow with multiple branches](labs/cloudflows/advanced/branches/README.md)
- [Error handling in Power Automate](labs/cloudflows/advanced/errorhandling/README.md)

## Robotic Process Automation using Desktop Flows
- [Creating a Desktop Flow - Working with a legacy application](labs/rpa/desktopflow/README.md)
- [Calling a Desktop Flow from a Cloud Flow](labs/rpa/integration/README.md)
- [Process Advisor](labs/rpa/processadvisor/README.md)
