# Customer On-boarding minimum viable checklist for WSO2

It is important to verify that the deployment is production ready before promoting the deployment. Otherwise the maintenance cost and customer satisfaction will be a big impact on the business. Just like any other process, the verification would be time consuming. WSO2 has come up with a two step approach to find a pragmatic balance between these two ends.

**Minimum Viable Checklist** is a must for all who prefer to have a stable WSO2 deployment. It contains the crucial checkpoints of the deployment.

**Solution Readiness Assessment (SRA)** is the second step of the verification process. WSO2 will perform an assessment on each and every WSO2 solution of its customers. The assessment will be carried out upon on-boarding a new customer to WSO2 based on the life cycle stage of the project and there will be multiple checkpoints as project lifecycle evolves until the go-live. This assessment guarantees that the solution and the deployment is as intended by the WSO2. Solution Readiness Score will be maintained internally for each customer solution based on a scoring scored by completing each checklist item.

This document provides the guideline for Minimum Viable Checklist.

| Minimum Viable Checklist  |
| ------------- |
| 1. Do you have a Business use case document / business architecture you can share - or a simple statement of the business intent for using WSO2? |
| 2. Have we identified right set of products/ features/ extensions ?  |
| 3. Design diagrams <br>L0 - Business Architecture <br>L1 - Solution Architecture <br> L2 - Deployment Architecture |
| 4.1. Expected average/peak loads ? |
| 4.2. Required no of product instances ?  |
| 5. Lower (Pre-Production) Environments <br>  Do you have at least one env that is identical to prod ? <br>  Do you have a dev environment that can be used for verification, without impacting the existing usages ? |
| 6. HA or not - or partial HA ? |
| 7.1. Complete deployment architecture diagram of product deployment |
| 7.2. On-premise, Cloud or Hybrid ? |
| 7.3. High Availability and Scalability |
| 7.4. Security zones |
| 7.5. Availability Zones |
| 8. Do you have WUM updates setup and a proper process to apply updates? |
| 9.1. Configured with supported JDK version ? |
| 9.2. DB Type and Version ? |
| 9.3. Infrastructure of each WSO2 Product Instance and LB |
| 9.3.1. Comply with the recommended CPU allocation  |
| 9.3.2. For optimum performance, our recommendation for JVM memory allocation is [here](https://docs.wso2.com/display/CLUSTER44x/Production+Deployment+Guidelines "here"). Can you share your current or forecasted allocation? If not can you confirm that you've checked out the recommendation? |
| 9.3.3. Comply with the recommended disk allocation  |
| 10. Is the deployment according to a supported deployment pattern ? |
| 11.1. Do we need to use extensions ? |
| 11.2. Do we need to do customizations ? |
| 12. Do you have a test plan for WSO2 components? Is this something you can share with us high level? This is a sample recommendation [docs] |
