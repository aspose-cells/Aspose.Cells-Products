---
title: 创建 Excel 图表并转换为图像 via Java
description:  Java 使用 Java 库在 Microsoft Excel 中绘制和转换图表或图表的源代码。
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 文件图表转换与创建 via Java" h2="将 Excel 文档图表转换为图像，并在基于 Java 的应用程序中使用服务器端 API 创建各种图表。" >}}


{{% blocks/products/pf/feature-page-summary %}}

通过图表分析数据可以显示更大的图景，并且可以通过更清晰的见解轻松做出更明智的决策。[Java Excel 库](/cells/zh/java/)支持绘制列出的不同图表创建[图表类型](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType)包括饼图、金字塔图、折线图和气泡图。此外，它还将图表转换为图像。 API 提供[图表类](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)用于表示单个 Excel 图表。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="将 Excel 图表转换为图像" %}}

将图表转换为图像（包括 JPG、PNG、TIFF、BMP 等）的过程是，使用[练习册](https://reference.aspose.com/java/cells/com.aspose.cells/workbook)加载Excel文件的类，选择相关[工作区](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet)包含图表或迭代每个工作表中的每个图表。定义[图像或打印选项](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions)并使用渲染图表的输出图像[图表转图像](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java 将Excel图表转换为图像的代码" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中创建图表" %}}

使用 Excel API 创建图表很简单，因为 API 为不同类型的图表提供了一组不同的类，例如 Axis、Chart、ChartArea、ChartDataTable、ChartFrame、ChartPoint、ChartPointCollection、ChartCollection 等。过程是，创建 Workbook 类对象并通过提供其索引来选择第一个工作表或相关工作表。对于图表的数据源，使用以下命令将值插入工作表单元格[设定值](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)方法。使用 ChartCollection 集合[添加方法](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) 要添加图表，请使用 ChartType 枚举定义图表类型。通过传递索引从 ChartCollection 集合中访问新的 Chart 对象。使用[系列合集](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection)图表对象来指定图表的数据源。

{{% blocks/products/pf/feature-page-code h3="Java 创建 Excel 图表的代码" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
