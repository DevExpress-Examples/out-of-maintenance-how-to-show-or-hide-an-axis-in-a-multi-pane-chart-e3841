<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128568195/11.2.8%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3841)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/SilverlightApplication1/MainPage.xaml) (VB: [MainPage.xaml](./VB/SilverlightApplication1/MainPage.xaml))
<!-- default file list end -->
# How to show or hide an axis in a multi-pane chart
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e3841)**
<!-- run online end -->


<p>The following sample demonstrates how to show (hide) an axis for a particular pane of the <a href="http://help.devexpress.com/#Silverlight/clsDevExpressXpfChartsXYDiagram2Dtopic"><u>XYDiagram2D</u></a> object.</p><br />



<h3>Description</h3>

<p>To accomplish this task for a specific <strong>Axis2D</strong> object, it is necessary to add the <strong>VisibilityInPane</strong> instance to the collection returned by the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsAxis2D_VisibilityInPanestopic"><u>Axis2D.VisibilityInPanes</u></a>  property. </p><p>And then, bind its <strong>VisibilityInPane.Pane</strong> property to a particular pane (in which you want to show or hide this axis) and set the <strong>VisibilityInPane.Visible </strong>property<strong> </strong>to<strong> True</strong> or <strong>False</strong>, as appropriate.</p><br />


<br/>


