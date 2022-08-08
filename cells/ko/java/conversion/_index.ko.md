---
title: Java을 통한 Microsoft Excel 파일 변환 
url: /ko/java/conversion/
description: 몇 줄의 Java 코드로 Excel XLS, XLSX, ODS, CSV를 PDF, XPS, HTML, JPEG, HTML 및 기타 널리 사용되는 형식으로 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java을 통한 Microsoft<sup>&reg;</sup> Excel 파일 변환" h2="Microsoft Excel 문서를 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 저장" >}}

{{% blocks/products/pf/feature-page-summary %}}
모든 **Excel 변환기** 응용 프로그램 또는 솔루션의 경우 Java Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS를 비롯한 여러 형식을 처리하면서 스프레드시트 프로그래밍 및 변환 프로세스의 속도를 높입니다. 또한 **Excel 파일을 PDF**, XPS, HTML, MHTML, 일반 텍스트 및 TIFF, JPG, PNG, BMP 및 SVG와 같은 인기 있는 이미지 형식으로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel 형식의 상호 변환" %}}
스프레드시트 형식의 상호 변환은 다음 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다. [학습장](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 에서 적절한 값을 선택하는 동안 원하는 형식으로 다시 저장 [저장 형식](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) 열거.
{{% blocks/products/pf/feature-page-code h3="Java Excel 파일 형식 변환을 위한 예제 코드" %}}

```cs
// 소스 파일을 로드
var wkb = new Workbook("sourceFile.xls");
// XLSX, ODS, SXC 및 FODS 형식으로 저장
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하는 데 특수 클래스를 사용할 수 있습니다. [PDF 저장 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) Excel 파일을 PDF로 변환하려면, [XpsSave 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) Excel을 XPS로 내보내려면 [HTML 저장 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) Excel을 HTML로 렌더링하고 [마크다운 저장 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) Excel에서 Markdown으로 변환하는 경우. 
{{% blocks/products/pf/feature-page-code h3="Java Excel에서 PDF 및 웹 형식으로 변환하는 샘플 코드" %}}

```cs
// 디스크에서 템플릿 Excel 파일 로드
var bk = new Workbook("source-file.xlsx");

// Java를 사용하여 Excel을 PDF로 변환
// PDF 생성 옵션
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// XPS에 Excel 저장
bk.save("output.xps", new XpsSaveOptions());
// Excel을 HTML로 저장
bk.save("output.html", new HtmlSaveOptions());
// 마크다운(MD)으로 Excel 저장
bk.save("output.md", new MarkdownSaveOptions());

// 관련 형식으로 저장하기 전에 자신이 선택한 관련 저장 옵션을 설정할 수 있습니다.

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON을 Excel로, Excel을 JSON으로 변환" %}}
JSON 데이터는 다음을 사용하여 Workbook 클래스의 인스턴스로 가져올 수 있습니다. [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) 추가 처리 또는 지원되는 형식으로의 간단한 변환을 위해. 마찬가지로 워크시트 데이터는 다음을 생성하여 JSON으로 내보낼 수 있습니다. [범위](https://reference.aspose.com/cells/java/com.aspose.cells/range) 또는 세포를 호출하고 [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) 방법.
{{% blocks/products/pf/feature-page-code h3="Java JSON에서 Excel로의 변환용 코드" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// 파일 읽기
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// JsonLayoutOptions 설정
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSON 데이터 가져오기
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// 엑셀 파일 저장
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel에서 JSON으로의 변환을 위한 소스 코드" %}}
```cs
// 통합 문서 인스턴스와 함께 XLSX 파일 로드
Workbook workbook = new Workbook("sourceFile.xlsx");
// 변환할 데이터가 포함된 워크시트의 CellsCollection에 액세스
Cells cells = workbook.getWorksheets().get(0).getCells();
// 고급 옵션을 위한 ExportRangeToJsonOptions 생성 및 설정
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// 내보낼 데이터가 포함된 셀 범위 만들기
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// 범위를 JSON 데이터로 내보내기
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// JSON 형식으로 디스크에 데이터 쓰기
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 이미지로 저장" %}}
각 워크시트는 ImageType 속성으로 설정한 JPG, BMP, PNG 및 GIF를 포함한 다양한 이미지 형식으로 변환할 수 있습니다. **Excel을 이미지로 변환** 사례의 경우 링크에서 관련 사례를 선택합니다.
{{% blocks/products/pf/feature-page-code h3="Java Excel에서 이미지로 변환하는 코드" %}}
```cs
// 템플릿 스프레드시트 로드
var wkb = new Workbook("template.xlsx");

// ImageOptions에 대한 개체 만들기
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// 이미지 유형 설정
imgOptions.setImageType(ImageType.PNG);

// 첫 번째 워크시트를 가져옵니다.
Worksheet sheet = wkb.getWorksheets().get(0);

// 대상 시트에 대한 SheetRender 개체 만들기
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// 워크시트에 대한 이미지 생성
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel을 Word 및 PowerPoint로 변환" %}}
사용하는 동안 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다. [DocxSave 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSave 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) 아래에 설명된 클래스.
{{% blocks/products/pf/feature-page-code h3="Java Excel에서 Word 및 PowerPoint로 변환하는 코드" %}}
```cs
// 템플릿 파일 로드
var wkb = new Workbook("template.xlsx");
// 스프레드시트를 DOCX로 저장
wkb.save("output.docx", new DocxSaveOptions());
// 스프레드시트를 PPTX로 저장
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}