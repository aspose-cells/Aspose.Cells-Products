---
title: Python के माध्यम से Microsoft Excel फ़ाइल रूपांतरण 
url: /hi/python/conversion/
description: एक्सेल एक्सएलएस, एक्सएलएसएक्स, ओडीएस, सीएसवी को पीडीएफ, एक्सपीएस, एचटीएमएल, जेपीईजी, एचटीएमएल और कई अन्य लोकप्रिय प्रारूपों को Python कोड की कुछ पंक्तियों के साथ कनवर्ट करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल प्रारूप रूपांतरण Python के माध्यम से" h2="एक्सेल फाइलों को स्प्रेडशीट, वेब, इमेज और फिक्स्ड-लेआउट फॉर्मेट के रूप में इम्पोर्ट और एक्सपोर्ट करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python एक्सेल लाइब्रेरी एक्सएलएस, एक्सएलएसएक्स, एक्सएलएसएम, एक्सएलएसबी, एक्सएलटीएक्स, एक्सएलटीएम, सीएसवी, स्प्रेडशीटएमएल, ओडीएस सहित लोकप्रिय प्रारूपों का समर्थन करते हुए स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। यह एक्सेल फाइलों को पीडीएफ, एक्सपीएस, एचटीएमएल, एमएचटीएमएल, प्लेन टेक्स्ट और लोकप्रिय इमेज फॉर्मेट जैसे टीआईएफएफ, जेपीजी, पीएनजी, बीएमपी और एसवीजी में निर्यात करने की भी अनुमति देता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को XLSX, ODS, SXC और FODS में बदलें" %}}
स्प्रैडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक स्प्रैडशीट लोड करने की आवश्यकता होती है जिसका उदाहरण: [वर्कबुक](https://apireference.aspose.com/cells/python/asposecells.api/Workbook) और से उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना [प्रारूप सहेजें](https://apireference.aspose.com/cells/python/asposecells.api/saveformat) गणना
{{% blocks/products/pf/feature-page-code h3="Python एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए कोड" %}}

```cs
// टेम्पलेट फ़ाइल लोड करें
workbook = Workbook("Book1.xls")
  
// XLSX, ODS, SXC और FODS प्रारूपों के रूप में सहेजें
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल को पीडीएफ, एक्सपीएस, एचटीएमएल और एमडी में बदलें" %}}
विशिष्ट आउटपुट स्वरूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशिष्ट वर्ग उपलब्ध हैं जैसे कि [पीडीएफ सेव विकल्प](https://apireference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) एक्सेल फाइलों को पीडीएफ के रूप में निर्यात करने के लिए, [एक्सपीएससेवविकल्प](https://apireference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) एक्सेल से एक्सपीएस रूपांतरण के लिए, [एचटीएमएल सेव विकल्प](https://apireference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) एक्सेल को HTML के रूप में प्रस्तुत करने के लिए और [मार्कडाउन सेव विकल्प](https://apireference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) एक्सेल से मार्कडाउन रूपांतरण के लिए। 
{{% blocks/products/pf/feature-page-code h3="Python एक्सेल से पीडीएफ और वेब प्रारूपों के लिए कोड" %}}

```cs
// डिस्क से टेम्पलेट एक्सेल फ़ाइल लोड करें
book = Workbook("template.xlsx")

// एक्सेल को PDF_A_1_B फॉर्मेट में सेव करें
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// एक्सपीएस में एक्सेल को 1 पेज प्रति वर्कशीट के साथ सेव करें
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// बेस 64 के रूप में छवियों के साथ HTML में एक्सेल को सेव करें
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// सेल फ़ॉर्मेटिंग को बनाए रखते हुए एक्सेल को मार्कडाउन (एमडी) में सेव करें
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON को एक्सेल और एक्सेल को JSON में बदलें" %}}
Python डेवलपर कोड की कुछ ही पंक्तियों में आसानी से JSON फ़ाइलों को एक्सेल में लोड और कनवर्ट कर सकते हैं। इसी तरह, एक्सेल डेटा को JSON डेटा में निर्यात किया जा सकता है।
{{% blocks/products/pf/feature-page-code h3="Python JSON से Excel रूपांतरण के लिए कोड" %}}
```cs
//अपनी स्रोत जेसन फ़ाइल लोड करें
workbook = Workbook("Data.json")
//फ़ाइल को xlsx प्रारूप में सहेजें
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python एक्सेल से JSON रूपांतरण के लिए कोड" %}}
```cs
//अपनी स्रोत xlsx फ़ाइल लोड करें
workbook = Workbook("input.xlsx")
//फ़ाइल को json फॉर्मेट में सेव करें
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को जेपीजी, बीएमपी, पीएनजी और जीआईएफ में बदलें" %}}
एक्सेल फ़ाइल की प्रत्येक वर्कशीट को विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, कॉल करें [इमेजऑरप्रिंटविकल्प](https://apireference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat छवि प्रारूप सेट करने के लिए। 
{{% blocks/products/pf/feature-page-code h3="Python एक्सेल से छवि रूपांतरण के लिए कोड" %}}
```cs
// टेम्पलेट स्प्रैडशीट लोड करें
workbook = Workbook("template.xlsx")
// ImageOrPrintOptions का एक उदाहरण बनाएं और सेट करें
options = ImageOrPrintOptions()
// आउटपुट छवि प्रारूप सेट करें
options.setImageFormat(ImageFormat.getPng())
// संग्रह में पहली वर्कशीट के लिए शीटरेंडर बनाएं
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// छवि के लिए कार्यपत्रक प्रस्तुत करें
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को वर्ड और पॉवरपॉइंट में बदलें" %}}
उपयोग करते समय किसी भी स्प्रैडशीट को लोड करना और उसे Word DOCX और PowerPoint PPTX फ़ाइलों में बदलना संभव है [DocxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) और [पीपीटीएक्स सेव विकल्प](https://apireference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) नीचे दिखाए गए अनुसार कक्षाएं।
{{% blocks/products/pf/feature-page-code h3="Python एक्सेल से वर्ड और पॉवरपॉइंट रूपांतरण के लिए कोड" %}}
```cs
// टेम्पलेट फ़ाइल लोड करें
workbook = Workbook("template.xlsx")

// स्प्रेडशीट को DOCX के रूप में सहेजें
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// स्प्रेडशीट को PPTX के रूप में सहेजें
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}