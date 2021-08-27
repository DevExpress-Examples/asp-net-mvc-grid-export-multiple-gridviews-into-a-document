<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128551526/14.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3891)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/Controllers/HomeController.vb))
* [Model.cs](./CS/Models/Model.cs) (VB: [Model.vb](./VB/Models/Model.vb))
* [GridViewPartialCategories.cshtml](./CS/Views/Home/GridViewPartialCategories.cshtml)
* [GridViewPartialProducts.cshtml](./CS/Views/Home/GridViewPartialProducts.cshtml)
* [Index.cshtml](./CS/Views/Home/Index.cshtml)
<!-- default file list end -->
# How to export multiple GridViews into a single print document
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e3891/)**
<!-- run online end -->


<p>This example illustrates how to create several MVC GridView Extensions into a single XLS document via the <a href="https://docs.devexpress.com/CoreLibraries/DevExpress.XtraPrintingLinks.PrintableComponentLinkBase._members"><u>PrintableComponentLinkBase</u></a> entries (the XtraPrinting library).<br /> These entries should be combined with the use of the IPrintable objects. The <a href="https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.GridViewExtension.CreatePrintableObject(DevExpress.Web.Mvc.GridViewSettings-System.Object)?p=netframework"><u>GridViewExtension.CreatePrintableObject</u></a> method allows creating the required IPrintable object from the GridView based on its GridViewSettings.</p>
<p>This example is also an extended ASP.NET MVC version of the <a href="https://www.devexpress.com/Support/Center/p/E70">E70: How to show detail information in a separate ASPxGridView</a> ASP.NET WebForms scenario.<br /><br /><strong>See Also:</strong><br /><strong>WebForms Version:</strong> <a href="https://www.devexpress.com/Support/Center/p/E1535">How to combine a number of ASPxGridView documents in one when exporting</a></p>

<br/>


