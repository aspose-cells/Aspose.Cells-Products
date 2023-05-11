---
title:  Microsoft 엑셀 파일 변환 via Java
description: Excel XLS, XLSX, ODS, 07613481 ~ PDF, XPS, HTML, JPEG, HTML 및 Java 코드의 몇 줄을 가진 다른 많은 형식을 가진 많은 다른 형식을 가진 다른 많은 형식을 갖는다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 변환 via Java" h2="Microsoft Excel 문서를 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 저장" >}}

{{% blocks/products/pf/feature-page-summary %}}
 어떠한 것도**엑셀 변환기** 응용 프로그램 또는 솔루션, Java Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619를 포함한 여러 형식을 처리하면서 스프레드시트 프로그래밍 및 변환 프로세스의 속도를 높입니다. 3481. 또한 *Excel 파일을 PDF로 변환**할 수 있습니다. XPS, HTML, MHTML, 일반 텍스트 및 TIFF, JPG, PNG, BMP 및 SVG과 같은 널리 사용되는 이미지 형식.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 형식의 상호 변환" %}}
 스프레드시트 형식의 상호 변환은 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다.[학습장](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 에서 적절한 값을 선택하면서 원하는 형식으로 다시 저장[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) 열거.
{{% blocks/products/pf/feature-page-code h3="Java Excel 파일 형식 변환을 위한 예제 코드" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
 다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하기 위해 특수 클래스를 사용할 수 있습니다.[Pdf저장 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) Excel 파일을 PDF로 변환하려면,[XpsSave옵션](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) Excel을 XPS로 내보내려면[HTML저장옵션](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) Excel을 HTML로 렌더링하고[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) Excel에서 Markdown으로 변환하는 경우.
{{% blocks/products/pf/feature-page-code h3="Java Excel에서 PDF로의 샘플 코드 및 웹 형식" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON을 Excel로, Excel을 JSON로 변환" %}}
 JSON 다음을 사용하여 Workbook 클래스의 인스턴스로 데이터를 가져올 수 있습니다.[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) 추가 처리 또는 지원되는 형식으로의 간단한 변환을 위해. 마찬가지로 워크시트 데이터는 다음을 만들어 JSON로 내보낼 수 있습니다.[범위](https://reference.aspose.com/cells/java/com.aspose.cells/range) 또는 셀을 호출하고[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) 방법.
{{% blocks/products/pf/feature-page-code h3="Java JSON을 Excel로 변환하는 코드" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel용 소스 코드를 JSON로 변환" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 이미지에 저장" %}}
 각 워크시트는 ImageType 속성으로 설정된 JPG, BMP, PNG 및 GIF을 포함한 다양한 이미지 형식으로 변환할 수 있습니다. 어떠한 것도**Excel을 이미지로 변환** 사례, 링크에서 해당 사례를 선택합니다.
{{% blocks/products/pf/feature-page-code h3="Java Excel에서 이미지로 변환하는 코드" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel을 Word로 변환하고 PowerPoint을 변환합니다." %}}
 사용하는 동안 모든 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다.[DocxSave옵션](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSave옵션](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) 아래에 설명된 클래스.
{{% blocks/products/pf/feature-page-code h3="Java Excel에서 Word로의 코드 및 PowerPoint 변환" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
