## Perform Scoping in SAP Cloud ALM

## Description:

In SAP Cloud ALM, scopes define which parts of the imported content from Selective Data Transfer (SDT) are included in the transition project.

Scopes help project team:

- Organize imported data by functional area
- Filter and focus on specific processes, applications, or systems relevant to their rollout.
- Control visibility so only scoped content appears in implementation and testing activities.
In this exercise, participants will perform scoping in SAP Cloud ALM to define which processes and solution content are included in the transition project. Scoping helps to focus on the relevant subset of imported content from the Selective Data Transfer (SDT) process and ensures that only the selected scope is used for further configuration and testing activities.

## Objective:

Understand how Scopes in SAP Cloud ALM allow teams to activate and manage the imported SDT content selectively, ensuring efficient, focused, and well-structured project execution.

Duration:

## Credentials:

User: HO_SDT<br>
Password: SDT_to_CALM

## Step-by-Step Guide:

1. Click on tile "Processes"

![image1](Images/image1.png)

Note: The Processes app provides access to all business processes imported from SAP Solution Manager. This is where scoping is initiated.

2. Click on “Edit Scope”

![image2](Images/image2.png)

3. Open filter for “Tags”

![image3](Images/image3.png)

Note: The demo Selective Data Transfer (SDT) files include a dedicated tag “Selective Data Transfer: HO\_## (## = Student Number) to make it easier to identify and select your assigned content during the exercises. This tag helps ensure that each participant works only with their own dataset, maintaining clear data separation and simplifying filtering in SAP Cloud ALM after upload.

4. Select “Selective Data Transfer: HO\_## (## = Student Number)

![image4](Images/image4.png)

5. Select “Selective Data Transfer: HO\_##” (## = Student Number)

![image5](Images/image5.png)

6. Open filter for “Process Owner”

![image6](Images/image6.png)

7. Click here

![image7](Images/image7.png)

Note: During the Selective Data Transfer (SDT), information about content owners maintained in SAP Solution Manager can be included in the export.

When imported into SAP Cloud ALM, these ownership details are automatically assigned to the corresponding processes.

8. Select “Agatha Bauer”

![image8](Images/image8.png)

9. Switch on "Demo\_SDT\_ Scope" for every Solution Process

![image9](Images/image9.png)

Note: Selecting the scope activates processes and their related artifacts (process hierarchy, applications, configurations, and developments).

10. Switch on …

![image10](Images/image10.png)

11. Switch on …

![image11](Images/image11.png)

12. Switch on …

![image12](Images/image12.png)

13. Click on "End Scoping"

![image13](Images/image13.png)

Note: This finalizes the scoping selection. The chosen scope will now be used for implementation and testing activities.

14. Click on "E2E OTC Sale-from-Stock Sales Agent"

![image14](Images/image14.png)

Note: Review the process to ensure all SDT relations from previous uploads are available.

15. Click on tab "Process Hierarchy Nodes"

![image15](Images/image15.png)

16. Click on tab "Solution Process Flow"

![image16](Images/image16.png)

17. Click on the Solution Activity “Create Sales Order”

![image17](Images/image17.png)

18. Click on tab "Applications"

![image18](Images/image18.png)

Note: Validate that the scoped process includes the expected relations to library elements.

19. Click on tab "Configurations"

![image19](Images/image19.png)

20. Click on tab "Developments"

![image20](Images/image20.png)

21. Click on "E2E\_OTC\_Sale-from-Stock Internet Sales (simplified)" drop down

![image21](Images/image21.png)

Note: This shows the list of all upload diagrams from Solution Manager

22. Click on "E2E\_OTC\_Sale-from-Stock Internet Sales"

![image22](Images/image22.png)

23. Click on down arrow next to application name ("Processes")

![image23](Images/image23.png)

24. Select "Implementation"

![image24](Images/image24.png)

Summary:

In this exercise, participants performed scoping in SAP Cloud ALM using the imported SDT content. They learned how to:- Identify and select the relevant SDT content.- Activate specific solution processes.- Validate that process hierarchy, applications, configurations, and developments are correctly linked within the scope.Key takeaway: Performing scoping in SAP Cloud ALM allows project teams to define a clear focus for their implementation, ensuring efficient use of transferred content and consistent project structure.

# Continue to next exercise - [Execute SDT Step 4 – Process Elements Upload (Documents & Test Cases)](../SDT_DOCS/SDT_DOCS.md)
