# Exercise: Execute SDT Step 4 – Process Elements (Documents, Test Case) upload

![image1](Images/image1.png)

## Documents upload to SAP Cloud ALM

Remark on various option for Documents during SDT:

During Selective Data Transfer (SDT), documents attached to elements in Solution Documentation (such as processes, steps, or test cases) are exported with their metadata included in the SDT export spreadsheet.  For the physical documents the following options exist:

- Option 1 – Keep Documents in SAP Solution Manager:
Only metadata is transferred to SAP Cloud ALM with links back to SAP Solution Manager.

- Option 2 – Move Documents to External Storage: Documents are exported to external storage (e.g., SharePoint) and linked in SAP Cloud ALM.
- Option 3 – Transfer to SAP BTP Document Management System (DMS): Documents will be fully transferred and stored in SAP Cloud ALM’s integrated DMS. (On Roadmap for Q4 2025)
For simplicity reason we use Option 1 for this demo.

Description:

In this exercise, participants will review how documents exported from SAP Solution Manager are uploaded and handled in SAP Cloud ALM as part of the Selective Data Transfer (SDT). They will explore document references, understand the available transfer options, and verify that the document links and metadata are correctly visible in SAP Cloud ALM after import.

Objective:

Understand how document metadata and links are transferred during SDT, review the available transfer options, and validate that the corresponding document references are correctly associated with processes and solution elements in SAP Cloud ALM.

Duration: 10 min.

Credentials:

User: HO00<br>
Password: SDT_to_CALM

Step-by-Step Guide:

1. Click on "Documents"

![image2](Images/image2.png)

Note: The Documents app in SAP Cloud ALM provides a central place to store, view, and manage project-related documentation.

2. Open filter for “Project”

![image3](Images/image3.png)

3. Select “Demo\_SDT\_Project”

![image4](Images/image4.png)

2. Click on "Upload"

![image5](Images/image5.png)

3. Open value list for “Scope”

![image6](Images/image6.png)

4. Select "Demo\_SDT\_Scope"

![image7](Images/image7.png)

5. Click on "Browse…"

![image8](Images/image8.png)

Note: Each student should upload their assigned file to ensure data isolation. (HO\_##...) (## = Student Number)

7. Select file "HO\_##\_Documents.xlsx” (## = Student Number)

![image9](Images/image9.png)

8. Click on “Open”

![image10](Images/image10.png)

9. Click on "Upload"

![image11](Images/image11.png)

10. Click on "Continue"

![image12](Images/image12.png)

11. Open filter for “Tags”

![image13](Images/image13.png)

Note: The demo Selective Data Transfer (SDT) files include a dedicated tag HO\_## (## = Student Number) to make it easier to identify and select your assigned content during the exercises. This tag helps ensure that each participant works only with their own dataset, maintaining clear data separation and simplifying filtering in SAP Cloud ALM after upload.

12. Select “Selective Data Transfer: HO\_##” (## = Student Number)

![image14](Images/image14.png)

13. Click on “E2E\_OTC\_Sale-from-Stock Direct Sales”

![image15](Images/image15.png)

14. Click on tab “Additional Information”

![image16](Images/image16.png)

Note: Check that the metadata (e.g. Title, External Reference) is visible and correctly linked to the document object.

18. Click on tab "References"

![image17](Images/image17.png)

19. Click on "Relations" drop down

![image18](Images/image18.png)

21. Select "Solution Processes"

![image19](Images/image19.png)

22. Click on “E2E\_OST Sales-from-Stock Direct sales” to navigate to the process

![image20](Images/image20.png)

24. Click on the drop down

![image21](Images/image21.png)

25. Click on "Documents"

![image22](Images/image22.png)

26. Click on "E2E OTC Sale-from-Stock Direct Sales" to navigate back to the document

![image23](Images/image23.png)

27. Click on "References"

![image24](Images/image24.png)

Note: This demonstrates that the reference points back to the original SAP Solution Manager location or external storage repository. Depending on the selected transfer option, links may point to SAP Solution Manager orexternal storage.

28. Click on the URL

![image25](Images/image25.png)

29. Close the tab

![image26](Images/image26.png)

30. Close the tab

![image27](Images/image27.png)

31. Click on down arrow next to application name (“Documents”)

![image28](Images/image28.png)

32. Select “Implementation”

![image29](Images/image29.png)

Summary:

In this exercise, participants explored how documents are handled during Selective Data Transfer (SDT) from SAP Solution Manager to SAP Cloud ALM. They learned how to:- Understand and differentiate between the three document transfer options.

- Upload document metadata and verify references in SAP Cloud ALM.- Check the correct linkage between documents and solution processes.Key takeaway: SDT ensures that document references and structures are preserved in SAP Cloud ALM, maintaining traceability while providing flexibility in how document files are managed (linked, stored, or re-uploaded).
