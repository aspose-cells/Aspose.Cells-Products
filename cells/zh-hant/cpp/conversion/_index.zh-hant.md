---
title: 通過 C++ 轉換 Microsoft Excel 文件 
url: /zh-hant/cpp/conversion/
description: 只需幾行 C++ 代碼，即可將 Excel XLS、XLSX、ODS、CSV 轉換為 PDF、XPS、HTML、JPEG 和其他格式。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C++ 進行 Microsoft<sup>&reg;</sup> Excel 文檔轉換" h2="將 Microsoft<sup>&reg;</sup> Excel 文件保存為電子表格、Web、圖像和固定佈局格式" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於任何電子表格轉換器應用程序或解決方案，**C++ Excel 庫** 可在處理多個文件（包括 XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS）時加快編碼、自動化和轉換過程。它還允許**將 Excel 轉換為 PDF**、XPS、HTML、MHTML、純文本和流行的圖像，例如 JPG、TIFF、PNG、BMP 和 SVG。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 格式的相互轉換" %}}
電子表格格式的相互轉換只需要加載一個帶有實例的電子表格 [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 指針並保存回所需的格式使用 [節省](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 的方法 [IWorkbook 類](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel 文件格式轉換的示例代碼" %}}

```cs

// 加載源 excel 格式。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// 以所需的輸出格式保存。
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="使用合規級別設置將 Excel 格式轉換為 PDF" %}}
C++ Excel 自動化API 支持將工作簿轉換為 PDF 並支持合規級別和創建日期的設置。開發者可以使用 [Ipdf保存選項](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) 隨著 [Aspose::Cells::渲染](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) 設置 PDF 合規性。對於轉換，API 以 PdfSaveOptions 作為參數並指定輸出文件路徑的保存方法。 
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到 PDF 轉換的示例代碼" %}}

```cs
// 加載示例 Excel 文件。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// 創建 pdf 保存選項對象。
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// 將合規性設置為 PDF/A-1b。
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// 或 PdfCompliance_PdfA1a 
// 對於普通 PDF，它將是 PdfCompliance_None

// 以 PDF 格式保存 Excel 文檔
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 保存到圖像" %}}
**C++ Excel Parser** 能夠以圖像的形式導出數據。每個工作表都可以轉換為不同的圖像格式，包括 BMP、JPEG、PNG 和 GIF，由 [渲染::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options).對於任何 **Convert Excel to Images** 案例，請從鏈接中選擇相關案例。
{{% blocks/products/pf/feature-page-code h3="C++ Excel 到圖像轉換的代碼" %}}

```cs
// 輸出目錄路徑。
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// 加載 XLSX。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// 訪問第一個工作表。
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// 創建圖像或打印選項對象。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 指定圖像格式。下面的代碼是JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// 對於 GIF、BMP 和 PNG 等其他圖像，可以分別使用 GetGif()、GetBmp() 和 GetPng() 

// 指定水平和垂直分辨率
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 根據指定的圖像或打印選項渲染工作表。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// 獲取頁數。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 為字符串連接創建字符串構建器對象。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 將每一頁一張一張地渲染成 jpeg 圖像。
for (int i = 0; i < pageCount; i++){
	// 清除字符串生成器並使用字符串連接創建輸出圖像路徑。
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// 獲取輸出圖像路徑。
	StringPtr outputJPEG = sb->ToString();
	// 將工作表轉換為圖像。
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}