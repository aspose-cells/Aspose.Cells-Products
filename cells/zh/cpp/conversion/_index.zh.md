---
title: 通过 C++ 转换 Microsoft Excel 文件 
url: /zh/cpp/conversion/
description: 只需几行 C++ 代码，即可将 Excel XLS、XLSX、ODS、CSV 转换为 PDF、XPS、HTML、JPEG 和其他格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C++ 进行 Microsoft<sup>&reg;</sup> Excel 文档转换" h2="将 Microsoft<sup>&reg;</sup> Excel 文件保存为电子表格、Web、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于任何电子表格转换器应用程序或解决方案，**C++ Excel 库** 可在处理多个文件（包括 XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS）时加快编码、自动化和转换过程。它还允许**将 Excel 转换为 PDF**、XPS、HTML、MHTML、纯文本和流行的图像，例如 JPG、TIFF、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互转换" %}}
电子表格格式的相互转换只需要加载一个带有实例的电子表格 [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 指针并保存回所需的格式使用 [节省](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 的方法 [IWorkbook 类](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel 文件格式转换的示例代码" %}}

```cs

// 加载源 excel 格式。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// 以所需的输出格式保存。
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="使用合规级别设置将 Excel 格式转换为 PDF" %}}
C++ Excel 自动化API 支持将工作簿转换为 PDF 并支持合规级别和创建日期的设置。开发者可以使用 [Ipdf保存选项](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) 随着 [Aspose::Cells::渲染](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) 设置 PDF 合规性。对于转换，API 以 PdfSaveOptions 作为参数并指定输出文件路径的保存方法。 
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到 PDF 转换的示例代码" %}}

```cs
// 加载示例 Excel 文件。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// 创建 pdf 保存选项对象。
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// 将合规性设置为 PDF/A-1b。
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// 或 PdfCompliance_PdfA1a 
// 对于普通 PDF，它将是 PdfCompliance_None

// 以 PDF 格式保存 Excel 文档
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 保存到图像" %}}
**C++ Excel Parser** 能够以图像的形式导出数据。每个工作表都可以转换为不同的图像格式，包括 BMP、JPEG、PNG 和 GIF，由 [渲染::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options).对于任何 **Convert Excel to Images** 案例，请从链接中选择相关案例。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到图像转换的代码" %}}

```cs
// 输出目录路径。
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// 加载 XLSX。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// 访问第一个工作表。
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// 创建图像或打印选项对象。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 指定图像格式。下面的代码是JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// 对于 GIF、BMP 和 PNG 等其他图像，可以分别使用 GetGif()、GetBmp() 和 GetPng() 

// 指定水平和垂直分辨率
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 根据指定的图像或打印选项渲染工作表。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// 获取页数。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 为字符串连接创建字符串构建器对象。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 将每一页一张一张地渲染成 jpeg 图像。
for (int i = 0; i < pageCount; i++){
	// 清除字符串生成器并使用字符串连接创建输出图像路径。
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// 获取输出图像路径。
	StringPtr outputJPEG = sb->ToString();
	// 将工作表转换为图像。
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}