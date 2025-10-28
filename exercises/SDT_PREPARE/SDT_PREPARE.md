# Exercise: Prepare SDT upload in SAP Cloud ALM

![image1](Images/image1.png)

## Description: 
In this exercise, participants will prepare the SAP Cloud ALM environment to receive and organize the content exported from SAP Solution Manager via Selective Data Transfer (SDT). They will review project settings, assign responsibilities, configure scopes, and prepare tag management.

## Objective: 
Build awareness of how to configure and align SAP Cloud ALM after an SDT export, ensuring a structured setup for imported content, responsibilities, and system references.

Duration: 5 minutes

## Credentials:

Click link to open [SAP Cloud ALM](https://calm1.test1.eu101.0041.relctestbeta1.customer1.11.test.eu10.alm.cloud.sap/launchpad#Launchpad1.openFLPPage?pageId=BuildPage&spaceId=BuildSpace) and follow the steps below:

User: HO_SDT <br>
Password: SDT_to_CALM

## Step1.by1.Step Guide:

1. Click on launchpad group "Implementation"
    ![image2](Images/image2.png)

    Note: In the Implementation area of the SAP Cloud ALM Launchpad we have defined a specific Transition to SAP Cloud ALM Implementation group with all relevant tiles for the Selective Data Transfer.

1. Click on tile "Projects and Setup"
    ![image3](Images/image3.png)

1. Click on project "Demo\_SDT\_Project"
    ![image4](Images/image4.png)

    Note: A project in SAP Cloud ALM serves as a central container that organizes and consolidates all relevant activities, configurations, and resources related to your transition initiative.

1. Click on tab "General Information"
    ![image5](Images/image5.png)

1. Click on tab "Teams"
    ![image6](Images/image6.png)

    Note: Under Teams you define the roles, responsibilities, and access for each project team member. It ensures that users are properly assigned to project roles (e.g., Project Manager, Application Consultant, Tester) and have the correct authorizations to execute their tasks within Project and Setup.

1. Click on tab "Scopes"
    ![image7](Images/image7.png)

    Note: Within a project in SAP Cloud ALM, scopes are defined to segment and focus on specific areas or phases of the transition. A scope in SAP Cloud ALM enables you to isolate certain data sets, configurations, or processes that need to be transferred from SAP Solution Manager to the new environment.

1. Click on tab "System Groups"
    ![image8](Images/image8.png)

    Note: In SAP Cloud ALM, a system group is a logical grouping of SAP systems that are managed together as a single entity. The selective data transfer facilitates the mapping of logical component groups from SAP Solution Manager to system groups in SAP Cloud ALM, ensuring an accurate and efficient alignment of system structures across platforms.

1. Click on system group "S4 HANA"
    ![image9](Images/image9.png)

1. Click "<" (Back) to return to the launchpad
    ![image10](Images/image10.png)

1. Click on tile "User Management"
    ![image11](Images/image11.png)

    Note: In the User Management app of SAP Cloud ALM, you can manage or display users and their roles, depending on your authorization. Users maintained in the User Management app can be assigned as owners for various entities such as solution processes, documents, or test cases, ensuring clear accountability and traceability across the project.

1. Click on card "Users by Status"
    ![image12](Images/image12.png)

1. Click "<" (Back) to return to the overview page of "User Management"
    ![image13](Images/image13.png)

1. Click on "<" (Back) to return to the launchpad
    ![image14](Images/image14.png)

1. Click on tile "Tag Management"
    ![image15](Images/image15.png)

    Note: Tags in SAP Cloud ALM represent attributes transferred from SAP Solution Manager. They help filter and classify imported content.

1. Click on button "Tag Groups"
    ![image16](Images/image16.png)

    Note: Review existing tag groups that have been created for our demo SDT import process.

1. Click on "<" (Back)
    ![image19](Images/image19.png)

*Summary:*

In this exercise, participants prepared SAP Cloud ALM to manage content imported via Selective Data Transfer (SDT). They learned how to:1. Access and review the imported project structure.1. Verify general project settings and assign responsible users.1. Configure scopes and link the correct system groups (e.g., S/4HANA).1. Review user access and tag management to ensure consistency with attributes transferred from SAP Solution Manager.Key takeaway: Proper preparation of SAP Cloud ALM ensures that imported SDT content is well1.structured, traceable, and ready for ongoing implementation and operations.

# Continue to next exercise 1. [Execute SDT Step 1 – Process Hierarchy Upload](../SDT_STEP1/SDT_STEP1.md)
