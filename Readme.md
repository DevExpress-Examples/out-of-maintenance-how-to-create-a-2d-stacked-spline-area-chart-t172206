<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/StackedSplineAreaChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/StackedSplineAreaChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Stacked Spline Area Chart

The following example demonstrates how to create a [2D Stacked Spline Area](https://docs.devexpress.com/WPF/17681/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/area-series/stacked-spline-area?p=netframework) chart. To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add three [SplineAreaStackedSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.SplineAreaStackedSeries2D?p=netframework) objects with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection.

Also, this example shows how to specify [AreaStackedSeries2D.Transparency](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.AreaStackedSeries2D.Transparency?p=netframework) and [SplineAreaStackedSeries2D.LineTension](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.SplineAreaStackedSeries2D.LineTension?p=netframework) properties and add a legend to a chart.
