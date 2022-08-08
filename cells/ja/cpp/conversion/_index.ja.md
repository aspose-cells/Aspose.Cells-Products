---
title: C++によるMicrosoftExcelファイル変換 
url: /ja/cpp/conversion/
description: Excel XLS、XLSX、ODS、CSVをPDF、XPS、HTML、JPEG、およびその他の形式に数行のC++コードで変換します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>C++を介したExcelドキュメントの変換" h2="Microsoft <sup>＆reg; </ sup> Excelファイルをスプレッドシート、Web、画像、および固定レイアウト形式で保存します" >}}

{{% blocks/products/pf/feature-page-summary %}}
スプレッドシートコンバータアプリケーションまたはソリューションの場合、** C++ Excel Library **は、XLSX、XLS、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODSなどの複数のファイルを処理しながら、コーディング、自動化、および変換プロセスを高速化します。また、** ExcelをPDFに変換**、XPS、HTML、MHTML、プレーンテキスト、およびJPG、TIFF、PNG、BMP、SVGなどの一般的な画像を使用することもできます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="MicrosoftExcel形式の相互変換" %}}
スプレッドシート形式の相互変換では、次のインスタンスを含むスプレッドシートを読み込むだけで済みます。 [ intrusive_ptr <Aspose :: Cells :: IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ポインタを使用して、目的の形式で保存し直します。 [保存する](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) の方法 [IWorkbookクラス](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)。
{{% blocks/products/pf/feature-page-code h3="C++Excelファイル形式変換のサンプルコード" %}}

```cs

// ソースexcel形式をロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// 必要な出力形式で保存します。
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="コンプライアンスレベル設定を使用してExcel形式をPDFに変換する" %}}
C++ Excel Automation APIは、ワークブックからPDFへの変換をサポートし、コンプライアンスレベルと作成日の設定をサポートします。開発者は使用できます [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) 一緒に [Aspose ::Cells::レンダリング](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) PDFコンプライアンスを設定します。変換の場合、パラメータとしてPdfSaveOptionsを持ち、出力ファイルパスを指定したAPIsaveメソッド。 
{{% blocks/products/pf/feature-page-code h3="C++ExcelからPDFへの変換のサンプルコード" %}}

```cs
// サンプルExcelファイルをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// pdf保存オプションオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// コンプライアンスをPDF/A-1bに設定します。
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// またはPdfCompliance_PdfA1a 
// 通常のPDFの場合はPdfCompliance_Noneになります

// ExcelドキュメントをPDF形式で保存します
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excelを画像に保存" %}}
** C++ Excel Parser **には、画像の形式でデータをエクスポートする機能があります。各ワークシートは、BMP、JPEG、PNG、GIFなどのさまざまな画像形式に変換できます。 [Rendering :: IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options)。 ** Excelを画像に変換**の場合は、リンクから関連するケースを選択してください。
{{% blocks/products/pf/feature-page-code h3="C++Excelから画像への変換のコード" %}}

```cs
// 出力ディレクトリパス。
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// XLSXをロードします。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// 最初のワークシートにアクセスします。
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// 画像または印刷オプションオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 画像フォーマットを指定します。以下のコードはJPEG用です
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// GIF、BMP、PNGなどの他の画像の場合、それぞれGetGif（）、GetBmp（）、GetPng（）を使用できます。 

// 水平および垂直解像度を指定します
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 指定された画像または印刷オプションに関してシートをレンダリングします。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// ページ数を取得します。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 文字列連結用の文字列ビルダーオブジェクトを作成します。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 各ページを1つずつjpeg画像にレンダリングします。
for (int i = 0; i < pageCount; i++){
	// 文字列ビルダーをクリアし、文字列を連結して出力イメージパスを作成します。
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// 出力画像パスを取得します。
	StringPtr outputJPEG = sb->ToString();
	// ワークシートを画像に変換します。
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}