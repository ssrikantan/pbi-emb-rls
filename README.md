# Power BI Embedded - Rol Level Security
This sample shows how Row Level Security can be implemented in a Power BI (PBI) Embedded Application. The Power BI Service Subscription is owned by a Company ‘A’, and a PBI Pro User in this Organization builds the Reports and Datasets and publishes them to the Service. Since these reports would be accessed by Users in an external organization (Contoso, in this example), these reports are embedded in an ASP.NET Mvc Application.

The steps to be followed are covered in the blog article [here](https://srikantan67.video.blog/2019/05/18/power-bi-embedded-row-level-security/)
The PBI Desktop Project that was used to create the sample is available in the Repo. The sample Web Application used here is as available in the documentation link [here](https://docs.microsoft.com/en-us/power-bi/developer/embed-sample-for-customers). Minor changes were made to implement query filter in the Report URL.

