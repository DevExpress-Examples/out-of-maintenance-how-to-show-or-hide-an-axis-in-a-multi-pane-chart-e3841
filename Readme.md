<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/SilverlightApplication1/MainPage.xaml) (VB: [MainPage.xaml](./VB/SilverlightApplication1/MainPage.xaml))
<!-- default file list end -->
# How to show or hide an axis in a multi-pane chart


<p>The following sample demonstrates how to show (hide) an axis for a particular pane of the <a href="http://help.devexpress.com/#Silverlight/clsDevExpressXpfChartsXYDiagram2Dtopic"><u>XYDiagram2D</u></a> object.</p><br />



<h3>Description</h3>

<p>To accomplish this task for a specific <strong>Axis2D</strong> object, it is necessary to add the <strong>VisibilityInPane</strong> instance to the collection returned by the <a href="http://help.devexpress.com/#Silverlight/DevExpressXpfChartsAxis2D_VisibilityInPanestopic"><u>Axis2D.VisibilityInPanes</u></a>  property. </p><p>And then, bind its <strong>VisibilityInPane.Pane</strong> property to a particular pane (in which you want to show or hide this axis) and set the <strong>VisibilityInPane.Visible </strong>property<strong> </strong>to<strong> True</strong> or <strong>False</strong>, as appropriate.</p><br />


<br/>


