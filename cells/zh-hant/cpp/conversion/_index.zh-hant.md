---
title: Microsoft Excel 檔案轉換透過 C++
description: Aspose.Cells for C++ 圖書館。只需幾行 C++ 程式碼即可轉換 EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、07683481、CSV、SQL、JPG、0768381、CSV、SQL138176。
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 透過 C++ 轉換 Excel 文檔" h2="將 Microsoft<sup>&reg;</sup> Excel 檔案儲存為電子表格、網頁、圖片和固定版面格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於任何電子表格轉換器應用程式或解決方案，**C++ Excel 庫**加速編碼、自動化和轉換過程，同時處理多個文件，包括XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、07617383868381、CSV、0761738386863481、0761738386863481、0761738383863481、76173838389638383897639979999393。 1**、XPS、HTML、 MHTML、普通文字和流行圖像，例如 JPG、TIFF、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互轉換" %}}
電子表格格式之間的轉換只需要使用以下命令載入電子表格[練習冊](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)類別並使用以下命令將其重新儲存為所需的格式[節省](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/)的方法[練習冊](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)班級。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 檔案格式轉換範例程式碼" %}}

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


{{% blocks/products/pf/feature-page-section h2="使用合規等級設定將 Excel 格式轉換為 PDF" %}}
C++ Excel自動化API支援將工作簿轉換為PDF，並支援合規等級和建立日期的設定。開發者可以使用[Pdf保存選項](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/)隨著[Aspose::Cells::渲染](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/)設定 PDF 合規性。對於轉換，API save 方法以 PdfSaveOptions 作為參數並指定輸出檔案路徑。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到 PDF 轉換的範例程式碼" %}}

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

{{% blocks/products/pf/feature-page-section h2="將 Excel 儲存到影像" %}}
**C++ Excel 解析器**具有以圖像形式導出資料的能力。每個工作表都可以轉換為不同的圖像格式，包括 BMP、JPEG、PNG 和 GIF，由設置[渲染::圖像或列印選項](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/)。對於任何**將 Excel 轉換為影像**案例，從連結中選擇相關案例。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到影像轉換的程式碼" %}}

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
