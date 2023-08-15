---
title: Microsoft C++ 経由の Excel ファイル変換
description: わずか数行の C++ コードで、Excel XLS、XLSX、ODS、CSV を PDF、XPS、HTML、JPEG およびその他の形式に変換します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++ 経由の Excel ドキュメント変換" h2="Microsoft<sup>&reg;</sup> Excel ファイルをスプレッドシート、Web、画像、固定レイアウト形式で保存します" >}}

{{% blocks/products/pf/feature-page-summary %}}
スプレッドシート コンバータ アプリケーションまたはソリューションの場合、**C++ エクセルライブラリ** XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS などの複数のファイルを処理しながら、コーディング、自動化、変換プロセスを高速化します。また、Excel を * に変換することもできます。 PDF**、XPS、HTML、MHTML、プレーンテキストと JPG、TIFF、PNG、BMP、SVG などの人気のある画像。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 形式の相互変換" %}}
スプレッドシート形式の相互変換には、次のインスタンスを含むスプレッドシートをロードするだけで済みます。[侵入的_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)ポインタを使用して希望の形式で保存し直す[保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)の方法[IWorkbook クラス](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel ファイル形式変換のコード例" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="コンプライアンスレベル設定を使用して Excel 形式を PDF に変換する" %}}
C++ Excel オートメーション API は、ワークブックの PDF への変換をサポートし、準拠レベルと作成日の設定もサポートします。開発者が使用できるのは、[IPdfSaveオプション](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options)とともに[Aspose::Cells::レンダリング](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)PDF 準拠を設定します。変換の場合は、パラメータとして PdfSaveOptions を指定し、出力ファイルのパスを指定した API save メソッドを使用します。
{{% blocks/products/pf/feature-page-code h3="C++ Excel から PDF への変換のサンプル コード" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel を画像として保存" %}}
**C++ Excel パーサー**データを画像の形式でエクスポートする機能があります。各ワークシートは、BMP、JPEG、PNG、GIF など、[レンダリング::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) 。どれについても**Excelを画像に変換**ケースの場合は、リンクから該当するケースを選択してください。
{{% blocks/products/pf/feature-page-code h3="C++ Excel から画像への変換用のコード" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
