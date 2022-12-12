---
title: C#을 통한 Microsoft Excel 파일 변환 

description: 몇 줄의 C# 코드로 Excel XLS, XLSX, ODS, CSV를 PDF, XPS, HTML, JPEG, HTML 및 기타 널리 사용되는 형식으로 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통한 Microsoft<sup>&reg;</sup> Excel 형식 변환" h2="스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 Excel 파일 가져오기 및 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS를 비롯한 널리 사용되는 형식을 지원하는 동시에 스프레드시트 프로그래밍 및 변환 프로세스의 속도를 높입니다. 또한 Excel 파일을 PDF, XPS, HTML, MHTML, 일반 텍스트 및 TIFF, JPG, PNG, BMP 및 SVG와 같은 인기 있는 이미지 형식으로 내보낼 수 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel을 XLSX, ODS, SXC 및 FODS로 변환" %}}
스프레드시트 형식의 상호 변환은 다음 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다. [학습장](https://reference.aspose.com/cells/net/aspose.cells/workbook) 에서 적절한 값을 선택하는 동안 원하는 형식으로 다시 저장 [저장 형식](https://reference.aspose.com/cells/net/aspose.cells/saveformat) 열거.
{{% blocks/products/pf/feature-page-code h3="C# Excel 파일 형식 변환용 코드" %}}

```cs
// 템플릿 파일 로드
var workbook = new Aspose.Cells.Workbook("template.xls");
// XLSX, ODS, SXC 및 FODS 형식으로 저장
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하는 데 특수 클래스를 사용할 수 있습니다. [PDF 저장 옵션](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) Excel 파일을 PDF로 내보내려면, [XpsSave 옵션](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) Excel에서 XPS로 변환하는 경우, [HTML 저장 옵션](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) Excel을 HTML로 렌더링하고 [마크다운 저장 옵션](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) Excel에서 Markdown으로 변환하는 경우. 
{{% blocks/products/pf/feature-page-code h3="C# Excel에서 PDF 및 웹 형식으로 변환하는 코드" %}}

```cs
// 디스크에서 템플릿 Excel 파일 로드
var book = new Aspose.Cells.Workbook("template.xlsx");
// Excel을 PDF/A-1a 형식으로 저장
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// 워크시트당 1페이지로 Excel을 XPS에 저장
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// Base64로 이미지가 포함된 HTML로 Excel 저장
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// 셀 서식을 유지하면서 Excel을 Markdown(MD)으로 저장
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON을 Excel로, Excel을 JSON으로 변환" %}}
JSON 데이터를 인스턴스로 가져올 수 있습니다. [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) 의 도움으로 수업 [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) 추가 처리 또는 지원되는 형식으로의 간단한 변환을 위해. 비슷하게, [워크시트](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 데이터를 생성하여 JSON으로 내보낼 수 있습니다. [범위](https://reference.aspose.com/cells/net/aspose.cells/range) 또는 세포를 호출하고 [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) 방법.
{{% blocks/products/pf/feature-page-code h3="C# JSON에서 Excel로의 변환용 코드" %}}
```cs
// 통합 문서 개체 만들기
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// 파일에서 JSON 데이터 읽기
string jsonInput = File.ReadAllText("Data.json");
// 배열을 테이블로 처리하도록 JsonLayoutOptions 설정
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// A1 셀에서 시작하는 워크시트로 JSON 데이터 가져오기
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// 결과 파일을 XLSX 형식으로 저장
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Excel에서 JSON으로의 변환용 코드" %}}
```cs
// 통합 문서 인스턴스와 함께 XLSX 파일 로드
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// 변환할 데이터가 포함된 워크시트의 CellsCollection에 액세스
var cells = workbook.Worksheets[0].Cells;
// 고급 옵션을 위한 ExportRangeToJsonOptions 생성 및 설정
var exportOptions = new Utility.ExportRangeToJsonOptions();
// 내보낼 데이터가 포함된 셀 범위 만들기
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// 범위를 JSON 데이터로 내보내기
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// JSON 형식으로 디스크에 데이터 파일 쓰기
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 JPG, BMP, PNG 및 GIF로 변환" %}}
Excel 파일의 각 워크시트는 설정한 다른 이미지 형식으로 변환할 수 있습니다. [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) 특성. 기본값은 'ImageFormat.Bmp'입니다.
{{% blocks/products/pf/feature-page-code h3="C# Excel에서 이미지로 변환하는 코드" %}}
```cs
// 템플릿 스프레드시트 로드
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// ImageOrPrintOptions의 인스턴스 생성 및 설정
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// 출력 이미지 형식 설정
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// 컬렉션의 첫 번째 워크시트에 대해 SheetRender 만들기
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// 워크시트를 이미지로 렌더링
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel을 Word 및 PowerPoint로 변환" %}}
사용하는 동안 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다. [DocxSave 옵션](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSave 옵션](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) 아래에 설명된 클래스.
{{% blocks/products/pf/feature-page-code h3="Excel에서 Word 및 PowerPoint로의 변환을 위한 C# 코드" %}}
```cs
// 템플릿 파일 로드
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// 스프레드시트를 DOCX로 저장
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// 스프레드시트를 PPTX로 저장
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
