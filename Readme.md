<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Dashboard_Coloring/Form1.cs) (VB: [Form1.vb](./VB/Dashboard_Coloring/Form1.vb))
<!-- default file list end -->
# How to customize a dashboard color scheme


<p>The following example demonstrates how to customize a dashboard color scheme to color specified dimension values using predefined colors.<br /><br />In this example, the dashboard contains a <a href="http://documentation.devexpress.com/#Dashboard/CustomDocument15262">Pie</a> dashboard item, whose dimension values and measures are colored by hue. The dashboard also contains a <a href="http://documentation.devexpress.com/#Dashboard/CustomDocument14719">Chart</a> dashboard item, whose dimension values are colored by hue. Dimension values, measures and corresponding colors are stored in a data table. <br /><br />To add custom colors to the dashboard color scheme (the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardCommonDashboard_ColorSchemetopic">Dashboard.ColorScheme</a> property), <a href="http://documentation.devexpress.com/#Dashboard/clsDevExpressDashboardCommonColorSchemeEntrytopic">ColorSchemeEntry</a> objects are created. The ColorSchemeEntry class allows you to specify the following properties:<br />- The <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardCommonColorSchemeEntry_DataSourcetopic">ColorSchemeEntry.DataSource</a> property specifies a data source containing dimension values to be colored.<br />- The <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardCommonColorSchemeEntry_DimensionKeystopic">ColorSchemeEntry.DimensionKeys</a> property allows you to specify required dimension values.<br />- The <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardCommonColorSchemeEntry_MeasureKeytopic">ColorSchemeEntry.MeasureKey</a> property allows you to specify a measure key used to specify measures to be colored.<br />- The <a href="https://documentation.devexpress.com/#Dashboard/DevExpressDashboardCommonColorSchemeEntry_ColorDefinitiontopic">ColorSchemeEntry.ColorDefinition</a> property sets a color used to color specified dimension values.</p>

<br/>


