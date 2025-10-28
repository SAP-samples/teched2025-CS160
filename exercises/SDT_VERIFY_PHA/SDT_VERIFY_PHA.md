# Exercise: Verify SDT upload and complition

![image1](Images/image1.png)

## Description:

In this exercise, participants will verify the results of the Selective Data Transfer (SDT) by reviewing imported entities and their relationships in the Process Hierarchy Assignment and by using the Solution Process Traceability Report. This verification ensures that all relevant links between processes, libraries, documents and test objects have been successfully maintained in SAP Cloud ALM after SDT.

## Objective:

Learn how to verify SDT results through the Process Hierarchy Assignment and Solution Process Traceability Report, confirming that end-to-end relationships between processes and related artifacts are intact and traceable.

Duration:

## Credentials:

User: HO_SDT<br>
Password: SDT_to_CALM

## Process Hierarchy Assignment Report

## Step-by-Step Guide:

1. Click on tile "Process Hierarchy Assignment Report"

    ![image2](Images/image2.png)

    Note: Open the Process Hierarchy Assignment Report to verify that all SDT-imported processes are visible and correctly structured.

1. Click on "Select View"

    ![image3](Images/image3.png)

1. Select "Process Hierarchy View"

    ![image4](Images/image4.png)

1. Click on "Collapse Entire Tree/Node"

    ![image5](Images/image5.png)

1. Select "Collapse Entire Tree"

    ![image6](Images/image6.png)

    Note: Check that the process is assigned under the correct hierarchy node and matches the original SAP Solution Manager structure.

1. Expand "HO\_##\_Business Processes"

    ![image7](Images/image7.png)

1. Expand "(HO\_##) Corporate Solution"

    ![image8](Images/image8.png)

1. Expand "A. End-to-End Processes"

    ![image9](Images/image9.png)

1. Click on "A.3 E2E\_Order-to-Cash.."

    ![image10](Images/image10.png)

1. Click on tab "Test Preparation"

    ![image11](Images/image11.png)

    Note: Validate that the links between test objects and their processes remain intact after SDT import.

1. Collapse "HO\_##\_Business Processes

    ![image12](Images/image12.png)

1. Expand "HO\_##\_Libraries"

    ![image13](Images/image13.png)

1. Expand "Interface Library"

    ![image14](Images/image14.png)

1. Expand "Global Interfaces"

    ![image15](Images/image15.png)

1. Expand "B. By Function"

    ![image16](Images/image16.png)

1. Click on "08 Sales"

    ![image17](Images/image17.png)

1. Click on "Library" drop down

    ![image18](Images/image18.png)

1. Select "Interface"

    ![image19](Images/image19.png)

    Note: Ensure the process steps are correctly connected to technical systems, confirming full traceability between business and IT artifacts.

1. Collapse "Interface Library"

    ![image20](Images/image20.png)

1. Expand "Executable Library"

    ![image21](Images/image21.png)

1. Expand "S4HANA"

    ![image22](Images/image22.png)

1. Expand "SD"

    ![image23](Images/image23.png)

1. Click on "SD-SLS"

    ![image24](Images/image24.png)

1. Click on "Library" drop down

    ![image25](Images/image25.png)

1. Select "Application"

    ![image26](Images/image26.png)

1. Collapse "Executable Library"

    ![image27](Images/image27.png)

1. Expand "Configuration Library"

    ![image28](Images/image28.png)

1. Expand "B. Authorisation"

    ![image29](Images/image29.png)

1. Click on "S4HANA Fiori Business Roles"

    ![image30](Images/image30.png)

1. Click on "Library" drop down

    ![image31](Images/image31.png)

1. Select "Configuration"

    ![image32](Images/image32.png)

1. Click on down arrow next to application name ("Process Hierarchy Assignment")

    ![image33](Images/image33.png)

1. Select "Implementation"

    ![image34](Images/image34.png)

# Continue to next exercise - [Solution Traceability Report in SAP Cloud ALM](../SDT_VERIFY_STR/SDT_VERIFY_STR.md)
