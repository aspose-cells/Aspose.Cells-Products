---
title: Microsoft C++ 経由の Excel ファイル変換
description: Aspose.Cells for C++ 図書館。わずか数行の C++ コードで、EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL、JPG、PNG などの形式を変換します。
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++ 経由の Excel ドキュメント変換" h2="Microsoft<sup>&reg;</sup> Excel ファイルをスプレッドシート、Web、画像、固定レイアウト形式で保存します" >}}

{{% blocks/products/pf/feature-page-summary %}}
スプレッドシート コンバータ アプリケーションまたはソリューションの場合、**C++ エクセルライブラリ** XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS などの複数のファイルを処理しながら、コーディング、自動化、変換プロセスを高速化します。また、*Excel を 0 に変換することもできます。 76193481**、XPS、HTML、MHTML、プレーンテキストと JPG、TIFF、PNG、BMP、SVG などの人気のある画像。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 形式の相互変換" %}}
スプレッドシート形式間の変換には、[ワークブック](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)クラスを作成し、それを使用して必要な形式で再保存します。[保存](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/)の方法[ワークブック](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)クラス。
{{% blocks/products/pf/feature-page-code h3="C++ Excel ファイル形式変換のコード例" %}}

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


{{% blocks/products/pf/feature-page-section h2="コンプライアンスレベル設定を使用して Excel 形式を PDF に変換する" %}}
C++ Excel オートメーション API は、ワークブックの PDF への変換をサポートし、準拠レベルと作成日の設定もサポートします。開発者が使用できるのは、[PDF保存オプション](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/)とともに[Aspose::Cells::レンダリング](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/)PDF 準拠を設定します。変換の場合は、パラメータとして PdfSaveOptions を指定し、出力ファイルのパスを指定した API save メソッドを使用します。
{{% blocks/products/pf/feature-page-code h3="C++ Excel から PDF への変換のサンプル コード" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel を画像として保存" %}}
**C++ Excel パーサー**データを画像の形式でエクスポートする機能があります。各ワークシートは、BMP、JPEG、PNG、GIF など、[レンダリング::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) 。どれについても**Excelを画像に変換**ケースの場合は、リンクから該当するケースを選択してください。
{{% blocks/products/pf/feature-page-code h3="C++ Excel から画像への変換用のコード" %}}

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
