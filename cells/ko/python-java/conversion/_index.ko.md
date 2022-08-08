---
title: Python을 통한 Microsoft Excel 파일 변환 
url: /ko/python/conversion/
description: 몇 줄의 Python 코드로 Excel XLS, XLSX, ODS, CSV를 PDF, XPS, HTML, JPEG, HTML 및 기타 널리 사용되는 형식으로 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을 통한 Microsoft<sup>&reg;</sup> Excel 형식 변환" h2="스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 Excel 파일 가져오기 및 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS를 비롯한 널리 사용되는 형식을 지원하는 동시에 스프레드시트 프로그래밍 및 변환 프로세스의 속도를 높입니다. 또한 Excel 파일을 PDF, XPS, HTML, MHTML, 일반 텍스트 및 TIFF, JPG, PNG, BMP 및 SVG와 같은 인기 있는 이미지 형식으로 내보낼 수 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel을 XLSX, ODS, SXC 및 FODS로 변환" %}}
스프레드시트 형식의 상호 변환은 다음 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다. [학습장](https://reference.aspose.com/cells/python/asposecells.api/Workbook) 에서 적절한 값을 선택하는 동안 원하는 형식으로 다시 저장 [저장 형식](https://reference.aspose.com/cells/python/asposecells.api/saveformat) 열거.
{{% blocks/products/pf/feature-page-code h3="Python Excel 파일 형식 변환용 코드" %}}

```cs
// 템플릿 파일 로드
workbook = Workbook("Book1.xls")
  
// XLSX, ODS, SXC 및 FODS 형식으로 저장
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하는 데 특수 클래스를 사용할 수 있습니다. [PDF 저장 옵션](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) Excel 파일을 PDF로 내보내려면, [XpsSave 옵션](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) Excel에서 XPS로 변환하는 경우, [HTML 저장 옵션](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) Excel을 HTML로 렌더링하고 [마크다운 저장 옵션](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) Excel에서 Markdown으로 변환하는 경우. 
{{% blocks/products/pf/feature-page-code h3="Python Excel에서 PDF 및 웹 형식으로 변환하는 코드" %}}

```cs
// 디스크에서 템플릿 Excel 파일 로드
book = Workbook("template.xlsx")

// Excel을 PDF_A_1_B 형식으로 저장
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// 워크시트당 1페이지로 Excel을 XPS에 저장
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// Base64로 이미지가 포함된 HTML로 Excel 저장
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// 셀 서식을 유지하면서 Excel을 Markdown(MD)으로 저장
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON을 Excel로, Excel을 JSON으로 변환" %}}
Python 개발자는 몇 줄의 코드로 JSON 파일을 Excel로 쉽게 로드하고 변환할 수 있습니다. 마찬가지로 Excel 데이터를 JSON 데이터로 내보낼 수 있습니다.
{{% blocks/products/pf/feature-page-code h3="Python JSON에서 Excel로의 변환용 코드" %}}
```cs
//소스 json 파일 로드
workbook = Workbook("Data.json")
//파일을 xlsx 형식으로 저장
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel에서 JSON으로의 변환용 코드" %}}
```cs
//소스 xlsx 파일 로드
workbook = Workbook("input.xlsx")
//파일을 json 형식으로 저장
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 JPG, BMP, PNG 및 GIF로 변환" %}}
Excel 파일의 각 워크시트는 다른 이미지 형식으로 변환할 수 있습니다. [이미지 또는 인쇄 옵션](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat 이미지 형식을 설정합니다. 
{{% blocks/products/pf/feature-page-code h3="Python Excel에서 이미지로 변환하는 코드" %}}
```cs
// 템플릿 스프레드시트 로드
workbook = Workbook("template.xlsx")
// ImageOrPrintOptions의 인스턴스 생성 및 설정
options = ImageOrPrintOptions()
// 출력 이미지 형식 설정
options.setImageFormat(ImageFormat.getPng())
// 컬렉션의 첫 번째 워크시트에 대해 SheetRender 만들기
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// 워크시트를 이미지로 렌더링
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel을 Word 및 PowerPoint로 변환" %}}
사용하는 동안 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다. [DocxSave 옵션](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSave 옵션](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) 아래에 설명된 클래스.
{{% blocks/products/pf/feature-page-code h3="Excel에서 Word 및 PowerPoint로의 변환을 위한 Python 코드" %}}
```cs
// 템플릿 파일 로드
workbook = Workbook("template.xlsx")

// 스프레드시트를 DOCX로 저장
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// 스프레드시트를 PPTX로 저장
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}