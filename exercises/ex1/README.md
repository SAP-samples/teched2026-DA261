# Exercise 1 - READ-ONLY, GUIDED TOUR: Share SAP-managed Data products from SAP BDC Catalog to SAP Snowflake Horizon Catalog


> [!IMPORTANT]
> This is only a **read-only** exercise, since sharing data products in SAP Business Data Cloud requires ADMIN rights. The purpose is to illustrate the zero-copy data sharing principle, to get easy access to SAP managed and standardized data product economy. There is a product guided tour available below.

This chapter describes the steps how Data Products in SAP Business Data Cloud (SAP BDC) are shared with SAP Snowflake. As a pre-requisite, the [SAP Snowflake](https://help.sap.com/docs/business-data-cloud/administering-sap-business-data-cloud/provisioning-sap-snowflake) must be provisioned. Once active, the SAP Snowflake account is ready for you to share data products from SAP BDC to SAP Snowflake. As part of the provisioning process for a new SAP Snowflake account, the system automatically creates a zero-copy connector called DEFAULT_SAP_BDC_CONNECTOR and enrolls it with SAP BDC in the SAP Snowflake account. The BDC Connect component is a dedicated, integrated environment for advanced data processing within SAP BDC. This process assigns resources, configures identity authentication, and defines key system parameters so that supported external systems are ready for use. In the above scenario with SAP Snowflake, the component is implicit and does not need to be provisioned.


#### Prequisites
- You have an BDC system landscape formation with **SAP SuccessFactors**
- Following Data Products are already installed and available in the SAP Business Data Cloud catalog:

<br/>
| # | Data Package | Data Product |
|---|---|---|
| 1 | SAP SuccessFactors Learning Data Products | LearningEventHistory |
| 2 | SAP SuccessFactors Succession and Career Development Data Products | CareerDevelopmentPlanningData |
| 3 | SAP SuccessFactors Succession and Career Development Data Products | DevelopmentGoals |
| 4 | SAP SuccessFactors Succession and Career Development Data Products | SuccessionManagement |
| 5 | SAP SuccessFactors Succession and Career Development Data Products | SuccessionReadiness |
| 6 | SAP SuccessFactors Performance and Goals Data Products | PerformanceReviews |
| 7 | SAP SuccessFactors Performance and Goals Data Products | PerformanceRatingStandard |
| 8 | SAP SuccessFactors Skills Data Products | WorkforceSkillsData |
| 9 | SAP SuccessFactors Employee Central Data Products | WorkforcePerson |


- You need to have a SAP BDC Admin role for sharing


## Summary

You've now ...

Continue to - [Exercise 2 - Exercise 2 Description](../ex2/README.md)

