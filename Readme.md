<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128600472/15.1.9%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E889)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [XtraReport1.cs](./CS/WebSite/App_Code/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/WebSite/App_Code/XtraReport1.vb))
* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to dynamically generate a report with a parameterized SQL query as a data source

<strong>Description</strong>:

I need a web report viewer to display the result of my SQL query, which accepts some parameters.

<strong>Solution</strong>:

Create an <a href="https://documentation.devexpress.com/#XtraReports/clsDevExpressXtraReportsUIXRTabletopic">XRTable</a> control dynamically.

Use a query string variable to pass the table name as a query parameter, as follows:
  
`href="http://hostname/PassSQLQuery/ReportViewer.aspx?TableName=Customers`

The XtraReport code-behind method populates the data source with data retrieved from the SQL query. The XRTable control is created in code. Table cells are bound to the column names of the data table.


<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=reporting-web-forms-generate-report-dynamically-for-specified-query&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=reporting-web-forms-generate-report-dynamically-for-specified-query&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
