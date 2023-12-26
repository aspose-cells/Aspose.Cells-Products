---
title: Microsoft Excel 文件转换通过 C++
description: Aspose.Cells for C++ 图书馆。只需几行 C++ 代码即可转换 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG 等格式。
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通过 C++ 转换 Excel 文档" h2="将 Microsoft<sup>&reg;</sup> Excel 文件另存为电子表格、网页、图像和固定布局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于任何电子表格转换器应用程序或解决方案，**C++ Excel 库**加速编码、自动化和转换过程，同时处理多个文件，包括 XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS。它还允许*将 Excel 转换为 07 6193481**、XPS、HTML、MHTML、普通文本和流行图像，例如 JPG、TIFF、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互转换" %}}
电子表格格式之间的转换只需要使用以下命令加载电子表格[练习册](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)类并使用以下命令将其重新保存为所需的格式[节省](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/)的方法[练习册](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)班级。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 文件格式转换示例代码" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="使用合规级别设置将 Excel 格式转换为 PDF" %}}
C++ Excel自动化API支持将工作簿转换为PDF，并支持合规级别和创建日期的设置。开发者可以使用[Pdf保存选项](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/)随着[Aspose::Cells::渲染](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/)设置 PDF 合规性。对于转换，API save 方法以 PdfSaveOptions 作为参数并指定输出文件路径。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到 PDF 转换的示例代码" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="将 Excel 保存到图像" %}}
**C++ Excel 解析器**具有以图像形式导出数据的能力。每个工作表都可以转换为不同的图像格式，包括 BMP、JPEG、PNG 和 GIF，由设置[渲染::图像或打印选项](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/)。对于任何**将 Excel 转换为图像**案例，从链接中选择相关案例。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到图像转换的代码" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
