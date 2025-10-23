# Exercise: Execute SDT Step 2 – Library upload

![image1](Images/image1.png)

## Upload of Configuration, Development, Application (Executable), Interface Library

Description:

In this exercise, participants will upload the exported library content from SAP Solution Manager into SAP Cloud ALM. This includes the Configuration, Development, Executable, and Interface Libraries that were previously exported as part of the Selective Data Transfer (SDT). These libraries contain relations, e.g. to Process Hierarchy.

Objective:

Understand how to upload library content into SAP Cloud ALM after SDT export, validate successful import, and verify that library items and relations (e.g., to process nodes) are properly established.

Duration: 10 minutes

Credentials: User: HO00<br>
Password: SDT_to_CALM

Step-by-Step Guide:

- Click on tile "Libraries"
![image2](Images/image2.png)

Note: The Libraries area in SAP Cloud ALM stores all reusable components such as configuration, development, executables, and interfaces.

- Click on "Select View" to select a specific library view
![image3](Images/image3.png)

- Select "A: Configuration View"
![image4](Images/image4.png)

- Click on "Upload"
![image5](Images/image5.png)

- Click on "Browse..."
![image6](Images/image6.png)

Note: Each student should upload their assigned file to ensure data isolation. (HO\_##...) (## = Student Number)

- Select file "HO\_##\_Configuration\_Library.xlsx" (## = Student Number)
![image7](Images/image7.png)

- Click on "Open"
![image8](Images/image8.png)

- Click on "Upload"
![image9](Images/image9.png)

- Click on "Continue"
![image10](Images/image10.png)

- Open filter for “Tags”
![image11](Images/image11.png)

Note: The demo Selective Data Transfer (SDT) files include a dedicated tag HO\_## (## = Student Number) to make it easier to identify and select your assigned content during the exercises. This tag helps ensure that each participant works only with their own dataset, maintaining clear data separation and simplifying filtering in SAP Cloud ALM after upload.

- Select “Selective Data Transfer: HO\_##” (## = Student Number)
![image12](Images/image12.png)

- Click outside the filter to close it
![image13](Images/image13.png)

- Click on “Show More per Row”
![image14](Images/image14.png)

- 14. Check "External Reference Name" hast the value "SAP Solution Manager"
![image15](Images/image15.png)

Note: This confirms that the imported elements are correctly reference to the source system from which they were exported (e.g. SAP Solution Manager).

- Click on tab "Process Hierarchy Nodes"
![image16](Images/image16.png)

Note: During the Selective Data Transfer (SDT) upload, relations between objects (e.g., Libraries and the Process Hierarchy) are automatically created based on the exported references from SAP Solution Manager.

This ensures that documentation in SAP Cloud ALM remain linked to their corresponding configurations, executables, and interfaces, preserving end-to-end traceability after transition.

- Click on “x” (Close)
![image17](Images/image17.png)

- Click on "Select View"
![image18](Images/image18.png)

- Select "B: Development View"
![image19](Images/image19.png)

Note: The Development Library contains custom developments and related entities used across processes. Upload the corresponding file.

- Click on "Upload"
![image20](Images/image20.png)

- Click on "Browse..."
![image21](Images/image21.png)

Note: Each student should upload their assigned file to ensure data isolation. (HO\_##...) (## = Student Number)

- Select file "HO\_##\_Development\_Library.xlsx" ( ## = Student Number)
![image22](Images/image22.png)

- Click on "Open"
![image23](Images/image23.png)

- Click on "Upload"
![image24](Images/image24.png)

- Click on "Continue"
![image25](Images/image25.png)

- Open filter for “Tags”
![image26](Images/image26.png)

- Select “Selective Data Transfer: HO\_##” (## = Student Number)
![image27](Images/image27.png)

- Open filter for “System Group”
![image28](Images/image28.png)

Note: When uploading Libraries via Selective Data Transfer (SDT), the imported items are automatically assigned to the relevant system group defined in the project setup.

This ensures that configurations, executables, and interfaces are correctly linked to the target systems in SAP Cloud ALM, maintaining consistency with the original SAP Solution Manager landscape.

- Select “S4 HANA”
![image29](Images/image29.png)

- Click outside the filter to close it
![image30](Images/image30.png)

- Click on "Select View"
![image31](Images/image31.png)

- Select "C: Application View"
![image32](Images/image32.png)

Note: The Executable Library contains business applications and transactions. These links are essential for process execution context.

- Click on "Upload"
![image33](Images/image33.png)

- Click on "Browse..."
![image34](Images/image34.png)

Note: Each student should upload their assigned file to ensure data isolation. (HO\_##...) ( ## = Student Number)

- Select file "HO\_##\_ Executable\_Library.xlsx" (## = Student Number)
![image35](Images/image35.png)

- Click on "Open"
![image36](Images/image36.png)

- Click on "Upload"
![image37](Images/image37.png)

- Click on "Continue"
![image38](Images/image38.png)

- Open filter for “Tags”
![image39](Images/image39.png)

- Select “Selective Data Transfer: HO\_##” (## = Student Number)
![image40](Images/image40.png)

- Click on "Manage Sales Quotations (F1852)" in the element list
![image41](Images/image41.png)

- Check "System Group"
![image42](Images/image42.png)

Note: When uploading Libraries via Selective Data Transfer (SDT), the imported items are automatically assigned to the relevant system group defined in the project setup.

This ensures that configurations, executables, and interfaces are correctly linked to the target systems in SAP Cloud ALM, maintaining consistency with the original SAP Solution Manager landscape.

- Click on "Change Outbound Delivery" in the element list
![image43](Images/image43.png)

- Collapse the filter area
![image44](Images/image44.png)

- Click on "Create Sales Orders (HO\_##)" (## = Student Number) in the element list
![image45](Images/image45.png)

- Click on tab "Configurations" on the detail view
![image46](Images/image46.png)

Note: During the Selective Data Transfer (SDT) upload, relations between objects (e.g., Libraries and the Process Hierarchy) are automatically created based on the exported references from SAP Solution Manager.

This ensures that processes in SAP Cloud ALM remain linked to their corresponding configurations, executables, and interfaces, preserving end-to-end traceability after migration.

- Click on "Storage Types"
![image47](Images/image47.png)

- Click on “x” (Close) to close the detail view
![image48](Images/image48.png)

- Click on "Select View"
![image49](Images/image49.png)

- Select "D: Interface View"
![image50](Images/image50.png)

Note: The Interface Library includes interfaces and integrations relevant to processes and applications.

- Click on "Upload"
![image51](Images/image51.png)

- Click on "Browse…"
![image52](Images/image52.png)

Note: Each student should upload their assigned file to ensure data isolation. (HO\_##...) ( ## = Student Number)

- Select file "HO\_##\_Interface\_Library.xlsx" ( ## = Student Number)
![image53](Images/image53.png)

- Click on "Open"
![image54](Images/image54.png)

- Click on "Upload"
![image55](Images/image55.png)

- Click on "Continue"
![image56](Images/image56.png)

- Open the filter “Tags”
![image57](Images/image57.png)

- Select “Selective Data Transfer: HO\_##” (## = Student Number)
![image58](Images/image58.png)

- Click on "Confirm Goods Issue" in the element list
![image59](Images/image59.png)

- Click on tab "Applications" in the detail view
![image60](Images/image60.png)

Note: During the Selective Data Transfer (SDT) upload, relations between objects (e.g., Libraries and the Process Hierarchy) are automatically created based on the exported references from SAP Solution Manager.

This ensures that processes in SAP Cloud ALM remain linked to their corresponding configurations, executables, and interfaces, preserving end-to-end traceability after migration.

- Click on "Send Deliveries to Warehouse" in the element list
![image61](Images/image61.png)

- Click on tab "Configurations" in the detail view
![image62](Images/image62.png)

- Click on tab "Interfaces"
![image63](Images/image63.png)

- Click on "Sales to Warehouse" in the element list
![image64](Images/image64.png)

- Click on tab "Interfaces" in the detail view
![image65](Images/image65.png)

- Click on tab "Process Hierarchy Nodes"
![image66](Images/image66.png)

- Click on “x” (Close) to close the detail view
![image67](Images/image67.png)

- Click on “<” (Back)
![image68](Images/image68.png)

- Click on down arrow next to the application name ("Libraries")
![image69](Images/image69.png)

- Select "Implementation"
![image70](Images/image70.png)

Summary:

In this exercise, participants uploaded various libraries (Configuration, Development, Executable, and Interface) from SAP Solution Manager into SAP Cloud ALM. They learned how to:- Access the Libraries area and navigate between different library views.- Upload the predefined SDT export files using SAP’s import templates.- Validate logs and confirm successful import.- Verify cross-references between library objects and process nodes.Key takeaway: Uploading libraries after the Process Hierarchy ensures that all reusable elements and references from SAP Solution Manager are correctly re-established in SAP Cloud ALM, forming the foundation for consistent process documentation and analysis.
