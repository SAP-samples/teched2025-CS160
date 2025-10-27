## Test Case (Test Step) upload to SAP Cloud ALM

## Description:

In this exercise, participants will upload the Test Steps exported from SAP Solution Manager into SAP Cloud ALM based on Selective Data Transfer (SDT) functionality. Test Steps define the detailed actions to be performed within a test and are linked to the corresponding processes or activities. This upload ensures that detailed testing information is retained after migration.

## Objective:

Learn how to upload Test Steps into SAP Cloud ALM, verify the upload results, and confirm that the test steps are correctly linked to their related processes in the system.

Duration:

## Credentials:

User: HO_SDT<br>
Password: SDT_to_CALM

## Step-by-Step Guide:

1. Click on tile "Test Preparation"

![image1](Images/image1.png)

2. Click on “Upload”

![image2](Images/image2.png)

3. Open value list for “Scope”

![image3](Images/image3.png)

4. Select “Demo\_SDT\_Scope”

![image4](Images/image4.png)

5. Click on “Browse...”

![image5](Images/image5.png)

6. Search for the file to be uploaded

![image6](Images/image6.png)

Note: Each student should upload their assigned file to ensure data isolation. (HO\_##...) (## = Student Number)

7. Select file "HO\_##\_Test\_Steps.xlsx” (## = Student Number)

![image7](Images/image7.png)

8. Click on “Open”

![image8](Images/image8.png)

9. Click on "Upload"

![image9](Images/image9.png)

10. Click on "Continue"

![image10](Images/image10.png)

11. Open filter for “Tags”

![image11](Images/image11.png)

Note: The demo Selective Data Transfer (SDT) files include a dedicated tag HO\_## (## = Student Number) to make it easier to identify and select your assigned content during the exercises. This tag helps ensure that each participant works only with their own dataset, maintaining clear data separation and simplifying filtering in SAP Cloud ALM after upload.

12. Select “Selective Data Transfer: HO\_##” (## = Student Number)

![image12](Images/image12.png)

Note: Review the availability of various owner after SDT upload.During the Selective Data Transfer (SDT), information about content owners maintained in SAP Solution Manager can be included in the export.

When imported into SAP Cloud ALM, these ownership details are automatically assigned to the corresponding processes.

18. Click here

![image13](Images/image13.png)

19. Click on “Confirm Goods Issue”

![image14](Images/image14.png)

21. Click on "Relations" drop down

![image15](Images/image15.png)

Note: Validate that the test cases include the expected relations to other elements, e.g. Libraries.

22. Select "Interface”

![image16](Images/image16.png)

23. Click on “<” (Back)

![image17](Images/image17.png)

24. Click on “Create Sales Order”

![image18](Images/image18.png)

25. Click on tab “References”

![image19](Images/image19.png)

26. Click on “Relations” drop down

![image20](Images/image20.png)

27. Select “Solution Activities”

![image21](Images/image21.png)

28. Click on “<” (Back)

![image22](Images/image22.png)

29. Click on “E2E\_OTC\_Sale-from-Stock Direct Sales”

![image23](Images/image23.png)

30. Click on “Relations” drop down

![image24](Images/image24.png)

31. Select “Process Hierarchy Nodes”

![image25](Images/image25.png)

32. Click on “<” (Back)

![image26](Images/image26.png)

33. Click on “PV\_E2E\_O2C\_Sale-from-Stock Internet Sales (simplified)”

![image27](Images/image27.png)

34. Click on “Relations” drop down

![image28](Images/image28.png)

35. Select “Process Hierarchy”

![image29](Images/image29.png)

36. Click on tab “Structure”

![image30](Images/image30.png)

37. Click on "Application"

![image31](Images/image31.png)

Note: In SAP Cloud ALM, each Test Case can be linked to an Application that represents the SAP or non-SAP system where the test is executed.

This linkage helps testers understand the system context of each test and ensures that execution results are tied to the correct technical environment.

38. Close newly opened browser tab

![image32](Images/image32.png)

Note: If required you can log on to S4HANA via User: BAUERA, PW: Solman72

39. Click on "Application" drop down

![image33](Images/image33.png)

41. Check maintained application

![image34](Images/image34.png)

43. Click on “<” (Back)

![image35](Images/image35.png)

44. Click on “<” (Back)

![image36](Images/image36.png)

Summary:

In this exercise, participants uploaded the Test Steps exported from SAP Solution Manager into SAP Cloud ALM. They learned how to:- Perform an SDT upload for Test Steps.- Verify imported Test Steps in the SAP Cloud ALM Test Steps view.- Confirm relationships between Test Steps and their processes.- Use tags to identify uploaded Test Steps in multi-user environments.Key takeaway: Uploading Test Steps ensures that detailed testing instructions and process-specific actions from SAP Solution Manager are accurately migrated to SAP Cloud ALM, maintaining test readiness and traceability.

# Continue to next exercise - [Verify SDT Upload and Completion](../SDT_VERIFY_PHA/SDT_VERIFY_PHA.md)
