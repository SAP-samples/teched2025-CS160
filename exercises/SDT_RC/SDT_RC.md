## Explore SAP Readiness Check for SAP Cloud ALM

## Description:

In this exercise, participants will explore the SAP Readiness Check for SAP Cloud ALM, navigate through different analysis areas, and understand how the tool provides insights into the current usage of SAP Solution Manager and the availability of capabilities in SAP Cloud ALM.

## Objective:

Build awareness of how the Readiness Check supports transition planning by identifying what is in use in SAP Solution Manager, how it maps to SAP Cloud ALM, and where Selective Data Transfer (SDT) can be applied.

Duration: 15–20 minutes

## Credentials:

User: HO_SDT

Passwort: SDT_to_CALM

## Step-by-Step Guide:

Click link to open [SAP Cloud ALM](https://calm-test-eu10-004-relctestbeta-customer-11.test.eu10.alm.cloud.sap/launchpad#Shell-home) and follow the steps below:

1. Click on "Email or User Name" and

![image1](Images/image1.png)

2. Click on "Password"

![image2](Images/image2.png)

3. Click on "Continue"

![image3](Images/image3.png)

4. Click on "Service"

![image4](Images/image4.png)

5. Click on "SAP Readiness"

![image5](Images/image5.png)

Notes: The “SAP Readiness Check” tile is the entry point for all readiness checks, including the one for SAP Cloud ALM.

6. Click on "DEMO SDT Analyses"

![image6](Images/image6.png)

Notes: The demo system contains simulated data that allows safe exploration of Selective Data Transfer (SDT) analyses.

7. Click on "Usage in SAP Solution Manager"

![image7](Images/image7.png)

Notes: These will show you which areas of SAP Solution Manager are actively used. This helps determine which content is relevant for transition (e.g., process documentation, test cases).

8. Click on "Procecs Manadement"

![image8](Images/image8.png)

9. Click on "Documentation Management"

![image9](Images/image9.png)

10. Click on "Test Suite"

![image10](Images/image10.png)

11. Click on "Test Steps"

![image11](Images/image11.png)

12. Click here

![image12](Images/image12.png)

13. Click on "CAP Cloud AIM canahilities"

![image13](Images/image13.png)

Notes: This view compares your SAP Solution Manager usage with the capabilities currently available in SAP Cloud ALM. It highlights which functions are ready, and where differences exist.

14. Click here

![image14](Images/image14.png)

15. Click here

![image15](Images/image15.png)

16. Click here

![image16](Images/image16.png)

17. Click here

![image17](Images/image17.png)

18. Click here

![image18](Images/image18.png)

19. Click on "Availability of Relevant Capabilities"

![image19](Images/image19.png)

20. Click here

![image20](Images/image20.png)

21. Click here

![image21](Images/image21.png)

22. Click here

![image22](Images/image22.png)

23. Click here

![image23](Images/image23.png)

24. Click on "Change Request Management Insights"

![image24](Images/image24.png)

Notes: Provides insights into ChaRM usage. Since ChaRM has a different handling in SAP Cloud ALM, the “Learn More” links guide you to transition options.

25. Click on "Learn More"

![image25](Images/image25.png)

26. Click here

![image26](Images/image26.png)

27. Click on "Learn More"

![image27](Images/image27.png)

28. Click here

![image28](Images/image28.png)

29. Click on "6 Months"

![image29](Images/image29.png)

Notes: Filter usage data by timeframe (e.g., last 6 months). This helps to focus on active and relevant usage **data** of your Solution Documentation.

30. Click here

![image30](Images/image30.png)

31. Click on "Scope Analysis for Selective Data Transfer"

![image31](Images/image31.png)

Notes: This section shows which solution information is transtion and selctive data transfer relevant (e.g.: scopes, attributes, logical component groups, documentation relations). It supports the SDT principle: migrate only what you need.

32. Click on "DEMO SDT SOLUTION"

![image32](Images/image32.png)

33. Click on "Scopes"

![image33](Images/image33.png)

34. Click on "Custom Attributes"

![image34](Images/image34.png)

Note: Attributes in SAP Solution Manager are transferred via Selective Data Transfer (SDT), they are represented in SAP Cloud ALM as tags. Each attribute value becomes a tag group and tag value on the migrated object. Tags can be used for filtering, searching, and grouping content in SAP Cloud ALM. This allows teams to continue using their classification logic from SAP Solution Manager without reconfiguration.

Note: Furthermore customer-defined attributes in SAP Solution Manager can be used to tag content relevant for Selective Data Transfer. This helps focus the transfer on selected processes or objects, making scoping decisions clear and consistent. Customer attributes give teams a simple way to control what gets migrated to SAP Cloud ALM. As an example in our exercise we have defined a attribute Selective Data Transfer with value HO00.

35. Click on "Business Partner Attributes"

![image35](Images/image35.png)

36. Click on "Maintenance Branch|"

![image36](Images/image36.png)

Note: When migrating content selectively, it is important to know from which branch the data will be taken. The branch context in Readiness Check helps ensure that only the relevant and up-to-date documentation is considered for transfer.

37. Click on "Used Logical Component Groups"

![image37](Images/image37.png)

38. Click on "Used Solution Documentation Relations"

![image38](Images/image38.png)

Note: The Use Solution Documentation Relations matrix helps you understand which types of Soution Documentation entities are used and how they relate to each other in SAP Cloud ALM.

39. Click here

![image39](Images/image39.png)

40. Click here

![image40](Images/image40.png)

41. Click here

![image41](Images/image41.png)

Summary:In this exercise, participants explored the SAP Readiness Check for SAP Cloud ALM using demo data. They learned how to:

- Review the current usage of SAP Solution Manager (Process Management, Documentation, Test Suite, ChaRM).
- Compare this usage against the availability of capabilities in SAP Cloud ALM.
- Understand how the branch information (e.g., maintenance branch) help to identify which version of documentation is considered for transfer.
- Use the Solution Documentation matrix to interpret which Solution Documentation entities and relations are used
Key takeaway:

The Readiness Check provides a transparent view of what can be migrated from SAP Solution Manager to SAP Cloud ALM using SDT, and helps project teams plan their transition based on actual usage, supported capabilities, and roadmap availability.
