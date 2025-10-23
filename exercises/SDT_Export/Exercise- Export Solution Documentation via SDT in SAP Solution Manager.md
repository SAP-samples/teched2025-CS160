# Exercise: Export Solution Documentation via SDT in SAP Solution Manager

![Image1](image1.png)

Description:

In this exercise, participants will practice exporting different Solution Documentation content from SAP Solution Manager via Selective Data Transfer transaction.

Objective:

Gain an understanding of how Selective Data Transfer (SDT) in SAP Solution Manager enables you to choose and export only relevant content—such as processes, libraries, or  test cases—ensuring a focused, lean, and efficient migration into SAP Cloud ALM.

Duration: 10 minutes

System Credentials:

Click link to open SAP Solution Manager 7.2 and follow the steps below:

User: HO00Password: SDT\_to\_CALM

Step-by-Step Guide:

1. Click on launchpad group "Transition to SAP Cloud ALM for Implementation"
![image2](Images/image2.png)

1. Click on tile "Selective Data Transfer"
![image3](Images/image3.png)

Note: The Selective Data Transfer app provides the export functionalities.

1. Open value help for “Object Type”
![image4](Images/image4.png)

Note: Process Hierarchy from solution documentation includes all Folders and Scenarios. Exporting them ensures business process structures are available in SAP Cloud ALM.

1. Select "Process Hierarchy"
![image5](Images/image5.png)

1. Open value list for “Solution”
![image6](Images/image6.png)

1. Select “DEMO\_SDT\_SOLUTION”
![image7](Images/image7.png)

1. Open value list for “Branch”
![image8](Images/image8.png)

1. Select "Maintenance"
![image9](Images/image9.png)

1. Open value list for “Scope”
![image10](Images/image10.png)

Note: Scopes define which subset of content is exported. They allow a controlled, selective migration.

1. Select "Demo SDT Scope"
![image11](Images/image11.png)

1. Click on “OK” button in selection area
![image12](Images/image12.png)

1. Click on "Download" button in ALV toolbar for “Process Hierarchy”
![image13](Images/image13.png)

Note: This triggers the export of the selected content into a file that can later be imported into SAP Cloud ALM.

Repeat similar steps for Configuration Library, Development Library, Executable Library, Interface Library, and Process Step Library

1. Open value list for “Object Type”
![image14](Images/image14.png)

Note: Each library contains reusable objects that must be available in SAP Cloud ALM to preserve references and consistency.

1. Select "Configuration Library"
![image15](Images/image15.png)

1. Click on “OK” button in selection area
![image16](Images/image16.png)

1. Click on “Settings” button in ALV toolbar for “Configuration Library”
![image17](Images/image17.png)

Note: Via settings you can show and hide specific attributes of your Solution Documentation.

1. Area for “Column Selection” is opened
![image18](Images/image18.png)

1. Select "# Responsible" in list of “Hidden Columns”
![image19](Images/image19.png)

Note: All optional attributes have # in the beginning.

1. Select "# Selective Data Transfer" in list of “Hidden Columns”
![image20](Images/image20.png)

Note: For our demo we use a customer attribute “Selective Data Transfer” which is used across our Solution Documentation. The attribute “Responsible” is an SAP Attribute used for better illustration.

1. Click on "Add >" button
![image21](Images/image21.png)

1. Click on “Apply” to confirm the change
![image22](Images/image22.png)

1. Check that s # Responsible and # Selective Data Transfer are added to the result list
![image23](Images/image23.png)

1. Click on "Save as."
![image24](Images/image24.png)

Note: You can save all settings as a custom view for better reuse option.

1. Provide a description for the new view
![image25](Images/image25.png)

1. Check the "Initial View" checkbox
![image26](Images/image26.png)

1. Click on "Save"
![image27](Images/image27.png)

1. Click on “OK” to close the settings area
![image28](Images/image28.png)

1. Click on "Download" button in ALV toolbar for “Configuration Library”
![image29](Images/image29.png)

1. Open value list for “Object Type”
![image30](Images/image30.png)

1. Select "Development Library"
![image31](Images/image31.png)

![image32](Images/image32.png)

1. Click on "OK" button in selection area
1. Click on "Download" button in ALV toolbar for “Development Library”
![image33](Images/image33.png)

1. Open value list for “Object Type”
![image34](Images/image34.png)

1. 35. Select "Executable Library"
![image35](Images/image35.png)

1. Click on "OK" button in selection area
![image36](Images/image36.png)

1. Click on "Download" button in ALV toolbar for “Executable Library”
![image37](Images/image37.png)

1. Open value list of “Object Type”
![image38](Images/image38.png)

1. 40. Select "Interface Library"
![image39](Images/image39.png)

1. Click “OK” button in selection area
![image40](Images/image40.png)

1. Click on "Download" button in ALV toolbar for “Interface Library”
![image41](Images/image41.png)

1. Open value list for “Object Type”
![image42](Images/image42.png)

1. 44. Select "Process Step Library"
![image43](Images/image43.png)

1. Click on "OK" button in selection area
![image44](Images/image44.png)

1. Click on "Download" button in ALV toolbar for “Process Step Library”
![image45](Images/image45.png)

1. Open value list for “Object Type”
![image46](Images/image46.png)

1. 48. Select "Process & Diagrams"
![image47](Images/image47.png)

Note: Exporting Process & Diagrams includes all Business Processes, Diagrams , Variants from your Solution Documentation. The export format is ready to be imported into SAP Cloud ALM.

1. Click on “OK” button in selection area
![image48](Images/image48.png)

1. Click on "Download" button in ALV toolbar for “Process & Diagrams”
![image49](Images/image49.png)

1. Wait until download is done
![image50](Images/image50.png)

1. Click on “OK” button to close the confirmation dialog
![image51](Images/image51.png)

1. Open value list for “Object Type”
![image52](Images/image52.png)

1. 54. Select "Documents"
![image53](Images/image53.png)

Note: During Selective Data Transfer (SDT), documents attached to elements in Solution Documentation (such as processes, steps, or test cases) are exported with their metadata included in the SDT export spreadsheet. For the physical documents the following options exist:

Option 1 – Keep Documents in SAP Solution Manager:

Only metadata is transferred to SAP Cloud ALM with links back to SAP Solution Manager.

Option 2 – Move Documents to External Storage:

Documents are exported to external storage (e.g., SharePoint) and linked in SAP Cloud ALM.

Option 3 – Transfer to SAP BTP Document Management System (DMS):

Documents will be fully transferred and stored in SAP Cloud ALM’s integrated DMS. (On Roadmap for Q4 2025)

For simplicity reason we use Option 1 for this demo.

1. Click on "OK" button in selection area
![image54](Images/image54.png)

1. Click on "Mapping Properties" button in ALV toolbar for “Documents”
![image55](Images/image55.png)

Note: The Mapping Properties allows you to map your SAP Solution Manager document types, statuses and priorities to the relevant SAP Cloud ALM types.

1. Open value list for “Solution Documentation Document Property Value”
![image56](Images/image56.png)

1. 58. Select "(SFT) Single Functional Test (CORP 31)"
![image57](Images/image57.png)

1. Open value list for “SAP Cloud ALM Document Property Value”
![image58](Images/image58.png)

1. Select "Test Document"
![image59](Images/image59.png)

1. Open value list for “Document Property Value”
![image60](Images/image60.png)

1. 62. Select "Priority"
![image61](Images/image61.png)

1. Open value list for “Solution Documentation Document Property Value”
![image62](Images/image62.png)

1. 64. Select "Low"
![image63](Images/image63.png)

1. Click on "Save"
![image64](Images/image64.png)

1. Click on “OK” to confirm saving the mapping properties
![image65](Images/image65.png)

1. Open value list for “Document Property Type”
![image66](Images/image66.png)

1. 68. Select "Status"
![image67](Images/image67.png)

1. Click on “Save”
![image68](Images/image68.png)

1. Click on “OK” to confirm saving the mapping properties
![image69](Images/image69.png)

1. Click on "Save + Close"
![image70](Images/image70.png)

1. Click on “OK” to confirm saving the mapping properties and closing the dialog
![image71](Images/image71.png)

1. Click on “Download” button in ALV toolbar for “Documents
![image72](Images/image72.png)

1. Open value list for “Object Type”
![image73](Images/image73.png)

Note: During Selective Data Transfer (SDT), test steps from SAP Solution Manager Focused Build Test Step Designer can be exported along with their relations e.g. Processes or Process Steps. This ensures that manual test structures and execution steps are preserved and can later be re-used for Test Preparation and Test Execution in SAP Cloud ALM .

1. 75. Select "Test Steps"
![image74](Images/image74.png)

1. Click on "OK" in selection area
![image75](Images/image75.png)

1. Click on "Download" button in ALV toolbar for “Test Steps”
![image76](Images/image76.png)

Summary:

In this exercise, participants practiced exporting different content objects from SAP Solution Manager for Selective Data Transfer (SDT). They learned how to:

- Export process hierarchies, processes & diagrams
- Export library content (configuration, development, executables, interfaces, process steps).
- Include documents and mapping properties with preserved references.
- Export test steps with attributes like priority.
Key takeaway: Exporting from SAP Solution Manager prepares structured content packages that can be seamlessly imported into SAP Cloud ALM, ensuring processes, libraries, and test assets are migrated consistently with their attributes and references.
