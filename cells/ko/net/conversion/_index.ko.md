---
title:  Microsoft C#을 통한 Excel 파일 변환
description: Excel XLS, XLSX, ODS, 07613481 ~ PDF, XPS, HTML, JPEG, HTML 및 C# 코드의 몇 줄을 가진 다른 많은 형식을 가진 많은 다른 형식을 가진 다른 많은 형식을 갖는다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 형식 변환 via .NET" h2="Excel 파일을 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 가져오기 및 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS을 포함한 널리 사용되는 형식을 지원하면서 스프레드시트 프로그래밍 및 변환 프로세스를 가속화합니다. 또한 Excel 파일을 PDF, XPS, HTML, MHTML, Plain으로 내보낼 수 있습니다. TIFF, JPG, PNG, BMP 및 SVG과 같은 텍스트 및 널리 사용되는 이미지 형식.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel을 XLSX, ODS, SXC 및 FODS로 변환" %}}
 스프레드시트 형식의 상호 변환은 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다.[학습장](https://reference.aspose.com/cells/net/aspose.cells/workbook) 에서 적절한 값을 선택하면서 원하는 형식으로 다시 저장[SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) 열거.
{{% blocks/products/pf/feature-page-code h3="C# Excel 파일 형식 변환용 코드" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
 다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하기 위해 특수 클래스를 사용할 수 있습니다.[Pdf저장 옵션](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) Excel 파일을 PDF로 내보내려면[XpsSave옵션](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) Excel에서 XPS로 변환,[HTML저장옵션](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) Excel을 HTML로 렌더링하고[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) Excel에서 Markdown으로 변환하는 경우.
{{% blocks/products/pf/feature-page-code h3="C# Excel용 코드 PDF 및 웹 형식" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON을 Excel로, Excel을 JSON로 변환" %}}
 JSON 데이터를 인스턴스로 가져올 수 있습니다.[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) 의 도움으로 수업[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)추가 처리 또는 지원되는 형식으로의 간단한 변환을 위해. 비슷하게,[워크시트](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 데이터를 생성하여 JSON로 내보낼 수 있습니다.[범위](https://reference.aspose.com/cells/net/aspose.cells/range) 또는 셀을 호출하고[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) 방법.
{{% blocks/products/pf/feature-page-code h3="C# JSON을 Excel로 변환하는 코드" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Excel용 코드를 JSON로 변환" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 JPG, BMP, PNG 및 GIF로 변환" %}}
 Excel 파일의 각 워크시트는[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) 재산. 기본값은 `ImageFormat.Bmp`입니다.
{{% blocks/products/pf/feature-page-code h3="C# Excel에서 이미지로 변환하는 코드" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel을 Word로 변환 & PowerPoint" %}}
 사용하는 동안 모든 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다.[DocxSave옵션](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSave옵션](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)아래에 설명된 클래스.
{{% blocks/products/pf/feature-page-code h3="Excel에서 Word로의 C# 코드 및 PowerPoint 변환" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
