# Welcome to the Cloud Adoption Framework Guidance for Windows Virtual Desktop # 
This Github repository provides guidance and tools for customers and partners who are looking to deploy and manage Azure Windows Virtual Desktop(WVD) in alignment to Cloud Adoption Framework (CAF).

The WVD CAF Solution Factory is designed to take you through all the phases of Cloud Adoption Framework and details out the steps that are needed for a successful Azure Windows Virtual Desktop deployment and management.  

## Artifacts Included
1. WVD CAF Guidance Documentation: Detailed guidance about what one needs to do in each of the Cloud Adoption phases for WVD Deployment starting from Strategy, Plan, Ready, Adopt, Govern and Manage. We have supplied detailed step by step guidance(from our experiences) that will provide the steps necessary to go from zero to a complete WVD deployment and management aligned to the Cloud Adoption Framework methodology. https://github.com/faridabharmal/WVD_CAF_SolutionFactory/blob/master/WVD%20CAF%20Guidance.docx  

2. WVD CAF Project DevOps Project Task List: When you go through the WVD deployment, its a project with more than 100 task - big and small that needs to be done. We have supplied Azure DevOps Project that will provide the steps necessary to go from zero to a complete WVD deployment and management. 

Steps to import the DevOps Project:  
    Sign in to the Azure DevOps Demo Generator site  https://azuredevopsdemogenerator.azurewebsites.net/
    Provide project name, select your Org, and choose the "WVD Project - Task DevOps Template.zip" template from this GitHub Repo 

3. WVD CAF Project Task List.xlsx: Incase if you are not leveraging Azure DevOps for project management, no worries...We have provided all the necessary steps in an excel sheet which can be leveraged as is or imported into your own project management tool of choice.  
https://github.com/faridabharmal/WVD_CAF_SolutionFactory/blob/master/WVD%20CAF%20Project%20Task%20List.xlsx 
 
4. WVD CAF Governance - Security: One common question that we get is what are the security considerations for WVD Deployment. So we have provided guidance about how to leverage the Azure policies to secure your environment. This can act as a good starting point for your security consideration. https://github.com/faridabharmal/WVD_CAF_SolutionFactory/tree/master/WVD%20CAF%20Governance%20-%20Security

## Windows Virtual Desktop (WVD) Overview 
CAF framework outlines key phases typically required/recommended to successfully implement and execute the WVD engagement.

## Azure Cloud Adoption Framework Overview
  
    ## Strategy Phase
    During the strategy phase, we try to understand the business through its motivations and outcomes. The underlying rationale behind the deployment of WVD in Azure is studied here.

    ## Plan Phase
    Planning is the next phase which aids in building the roadmap to transform the strategy goals and business motivation into actionable items in alignment with CAF framework. This phase outlines the IT assets, users involved, their storage needs, resources required for managing and deploying WVD environment and assessment of the environment in detail.

    ## Ready Phase
    This is an important phase where the ground level work is done to ensure that gaps are addressed and support needs are provided before deployment begins. A stage that needs to be set up wherein the landing zone is defined by organizing resources and setting up Network and Domain control. This session also details about building VM image through which we can create multiple session hosts. 
    
    ## Adopt phase
    This is the main phase wherein the actual deployment will take place whether it is in greenfield space or migration from a different setup. It starts with setting up the host pool and customizing it according to the deployment. A standard procedure for execution of greenfield deployment is described herein. Azure enables to migrate existing virtual desktop workloads to Microsoft Azure as part of Windows Virtual Desktop and so, the migration process, its patterns and best practices are described herein.

    ## Governance 
    Governance creates guardrails that keep the company on a safe path throughout the journey. For organizations with existing policies that govern on-premises IT environments, governance should complement those policies. Security and Compliance guidelines are elaborated to keep your systems safe.

    ## Manage
    Unless, we have a plan to manage the operations, the efforts put in planning, readiness and adoption will yield little value. In the end, patch management process is carried out for updating and patching the Session host VMs to avoid any security vulnerabilities and applying any configuration controls as required.


## Contributing
This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, https://cla.microsoft.com

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the <a href="https://opensource.microsoft.com/codeofconduct/">Microsoft Open Source Code of Conduct</a>.

For more information see the <a href="https://opensource.microsoft.com/codeofconduct/faq/" rel="nofollow">Code of Conduct FAQ</a> or
contact <a href="mailto:opencode@microsoft.com">opencode@microsoft.com</a> with any additional questions or comments.

