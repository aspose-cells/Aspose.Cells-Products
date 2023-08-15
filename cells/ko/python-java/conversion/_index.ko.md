---
title: Microsoft Python via을 사용한 Excel 파일 변환 Java
description: Excel XLS, XLSX, ODS, 07613481 ~ PDF, XPS, HTML, JPEG, HTML 및 Python 코드의 몇 줄을 가진 다른 많은 형식을 가진 많은 다른 형식을 가진 다른 많은 형식을 갖는다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Python을 통한 Excel 형식 변환" h2="Excel 파일을 스프레드시트, 웹, 이미지 및 고정 레이아웃 형식으로 가져오기 및 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel 라이브러리는 XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS을 포함한 널리 사용되는 형식을 지원하면서 스프레드시트 프로그래밍 및 변환 프로세스를 가속화합니다. 또한 Excel 파일을 PDF, XPS, HTML, MHTML, Plain으로 내보낼 수 있습니다. TIFF, JPG, PNG, BMP 및 SVG과 같은 텍스트 및 널리 사용되는 이미지 형식.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel을 XLSX, ODS, SXC 및 FODS로 변환" %}}
 스프레드시트 형식의 상호 변환은 인스턴스가 있는 스프레드시트를 로드하기만 하면 됩니다.[학습장](https://reference.aspose.com/cells/python/asposecells.api/Workbook) 에서 적절한 값을 선택하면서 원하는 형식으로 다시 저장[SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) 열거.
{{% blocks/products/pf/feature-page-code h3="Python Excel 파일 형식 변환용 코드" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel을 PDF, XPS, HTML 및 MD로 변환" %}}
 다음과 같은 특정 출력 형식에 대한 변환 프로세스를 제어하기 위해 특수 클래스를 사용할 수 있습니다.[Pdf저장 옵션](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) Excel 파일을 PDF로 내보내려면[XpsSave옵션](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) Excel에서 XPS로 변환,[HTML저장옵션](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) Excel을 HTML로 렌더링하고[MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) Excel에서 Markdown으로 변환하는 경우.
{{% blocks/products/pf/feature-page-code h3="Python Excel용 코드 PDF 및 웹 형식" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON을 Excel로, Excel을 JSON로 변환" %}}
Python 개발자는 단 몇 줄의 코드로 JSON 파일을 Excel로 쉽게 로드하고 변환할 수 있습니다. 마찬가지로 Excel 데이터를 JSON 데이터로 내보낼 수 있습니다.
{{% blocks/products/pf/feature-page-code h3="Python JSON을 Excel로 변환하는 코드" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel용 코드를 JSON로 변환" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 JPG, BMP, PNG 및 GIF로 변환" %}}
 Excel 파일의 각 워크시트는 다른 이미지 형식으로 변환할 수 있습니다.[이미지 또는 인쇄 옵션](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions) .setImageFormat 이미지 형식을 설정합니다.
{{% blocks/products/pf/feature-page-code h3="Python Excel에서 이미지로 변환하는 코드" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel을 Word로 변환 & PowerPoint" %}}
 사용하는 동안 모든 스프레드시트를 로드하고 Word DOCX 및 PowerPoint PPTX 파일로 변환할 수 있습니다.[DocxSave옵션](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSave옵션](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions)아래에 설명된 클래스.
{{% blocks/products/pf/feature-page-code h3="Excel에서 Word로의 Python 코드 및 PowerPoint 변환" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
