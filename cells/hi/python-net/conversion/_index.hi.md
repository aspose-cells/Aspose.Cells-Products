---
title: Microsoft एक्सेल फ़ाइल रूपांतरण Python via NET का उपयोग कर
description: Excel XLS, XLSX, ODS, CSV को PDF, XPS, HTML, JPEG, HTML और कई अन्य लोकप्रिय प्रारूपों को Python कोड की कुछ पंक्तियों के साथ परिवर्तित करें .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Python के माध्यम से एक्सेल प्रारूप रूपांतरण" h2="एक्सेल फ़ाइलों को स्प्रेडशीट, वेब, छवि और फिक्स्ड-लेआउट प्रारूपों के रूप में आयात और निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python एक्सेल लाइब्रेरी XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076193 सहित लोकप्रिय प्रारूपों का समर्थन करते हुए स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। 481. यह एक्सेल फ़ाइलों को PDF, XPS, HTML, MHTML, प्लेन पर निर्यात करने की भी अनुमति देता है टेक्स्ट और लोकप्रिय छवि प्रारूप जैसे TIFF, जेपीजी, PNG, BMP और SVG।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को XLSX, ODS, SXC और FODS में कनवर्ट करें" %}}
 स्प्रेडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक उदाहरण के साथ स्प्रेडशीट लोड करने की आवश्यकता होती है[वर्कबुक](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) और उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना[प्रारूप सहेजें](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) गणना
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए Python कोड" %}}

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


{{% blocks/products/pf/feature-page-section h2="एक्सेल को PDF, XPS, HTML एवं एमडी में बदलें" %}}
 विशिष्ट आउटपुट स्वरूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशेष कक्षाएं उपलब्ध हैं[पीडीएफसेवविकल्प](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) एक्सेल फ़ाइलों को PDF के रूप में निर्यात करने के लिए,[XpsSaveविकल्प](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) एक्सेल से XPS रूपांतरण के लिए,[HTMLSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) एक्सेल को HTML के रूप में प्रस्तुत करना और[मार्कडाउनसेवऑप्शंस](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) एक्सेल से मार्कडाउन रूपांतरण के लिए।
{{% blocks/products/pf/feature-page-code h3="Python एक्सेल के लिए कोड PDF और वेब फॉर्मेट के लिए" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON को एक्सेल में और एक्सेल को JSON में बदलें" %}}
Python डेवलपर्स कोड की कुछ पंक्तियों में JSON फ़ाइलों को एक्सेल में आसानी से लोड और परिवर्तित कर सकते हैं। इसी तरह एक्सेल डेटा को JSON डेटा पर एक्सपोर्ट किया जा सकता है।
{{% blocks/products/pf/feature-page-code h3="Python कोड JSON से एक्सेल रूपांतरण के लिए" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="एक्सेल के लिए Python कोड से JSON रूपांतरण" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को JPG, BMP, PNG और GIF में कनवर्ट करें" %}}
 एक्सेल फ़ाइल की प्रत्येक वर्कशीट को विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, कॉल करें[छवियाप्रिंटविकल्प](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/) छवि प्रारूप सेट करने के लिए .setImageFormat।
{{% blocks/products/pf/feature-page-code h3="Python एक्सेल से छवि रूपांतरण के लिए कोड" %}}
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

{{% blocks/products/pf/feature-page-section h2="एक्सेल को वर्ड में बदलें और PowerPoint" %}}
 उपयोग करते समय किसी भी स्प्रेडशीट को लोड करना और उसे Word DOCX और PowerPoint PPTX फ़ाइलों में परिवर्तित करना संभव है[DocxSaveविकल्प](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [पीपीटीएक्ससेवऑप्शंस](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/)कक्षाएं जैसा कि नीचे दिखाया गया है।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से वर्ड के लिए Python कोड और PowerPoint रूपांतरण" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
