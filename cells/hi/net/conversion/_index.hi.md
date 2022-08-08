---
title: C# के माध्यम से Microsoft Excel फ़ाइल रूपांतरण 
url: /hi/net/conversion/
description: एक्सेल एक्सएलएस, एक्सएलएसएक्स, ओडीएस, सीएसवी को पीडीएफ, एक्सपीएस, एचटीएमएल, जेपीईजी, एचटीएमएल और कई अन्य लोकप्रिय प्रारूपों को C# कोड की कुछ पंक्तियों के साथ कनवर्ट करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल प्रारूप रूपांतरण .NET के माध्यम से" h2="एक्सेल फाइलों को स्प्रेडशीट, वेब, इमेज और फिक्स्ड-लेआउट फॉर्मेट के रूप में इम्पोर्ट और एक्सपोर्ट करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET एक्सेल लाइब्रेरी एक्सएलएस, एक्सएलएसएक्स, एक्सएलएसएम, एक्सएलएसबी, एक्सएलटीएक्स, एक्सएलटीएम, सीएसवी, स्प्रेडशीटएमएल, ओडीएस सहित लोकप्रिय प्रारूपों का समर्थन करते हुए स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। यह एक्सेल फाइलों को पीडीएफ, एक्सपीएस, एचटीएमएल, एमएचटीएमएल, प्लेन टेक्स्ट और लोकप्रिय इमेज फॉर्मेट जैसे टीआईएफएफ, जेपीजी, पीएनजी, बीएमपी और एसवीजी में निर्यात करने की भी अनुमति देता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को XLSX, ODS, SXC और FODS में बदलें" %}}
स्प्रैडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक स्प्रैडशीट लोड करने की आवश्यकता होती है जिसका उदाहरण: [वर्कबुक](https://reference.aspose.com/cells/net/aspose.cells/workbook) और से उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना [प्रारूप सहेजें](https://reference.aspose.com/cells/net/aspose.cells/saveformat) गणना
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए कोड" %}}

```cs
// टेम्पलेट फ़ाइल लोड करें
var workbook = new Aspose.Cells.Workbook("template.xls");
// XLSX, ODS, SXC और FODS प्रारूपों के रूप में सहेजें
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल को पीडीएफ, एक्सपीएस, एचटीएमएल और एमडी में बदलें" %}}
विशिष्ट आउटपुट स्वरूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशिष्ट वर्ग उपलब्ध हैं जैसे कि [पीडीएफ सेव विकल्प](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) एक्सेल फाइलों को पीडीएफ के रूप में निर्यात करने के लिए, [एक्सपीएससेवविकल्प](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) एक्सेल से एक्सपीएस रूपांतरण के लिए, [एचटीएमएल सेव विकल्प](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) एक्सेल को HTML के रूप में प्रस्तुत करने के लिए और [मार्कडाउन सेव विकल्प](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) एक्सेल से मार्कडाउन रूपांतरण के लिए। 
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल से पीडीएफ और वेब प्रारूपों के लिए कोड" %}}

```cs
// डिस्क से टेम्पलेट एक्सेल फ़ाइल लोड करें
var book = new Aspose.Cells.Workbook("template.xlsx");
// एक्सेल को पीडीएफ/ए-1ए फॉर्मेट में सेव करें
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// एक्सपीएस में एक्सेल को 1 पेज प्रति वर्कशीट के साथ सेव करें
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// बेस 64 के रूप में छवियों के साथ HTML में एक्सेल को सेव करें
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// सेल फ़ॉर्मेटिंग को बनाए रखते हुए एक्सेल को मार्कडाउन (एमडी) में सेव करें
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON को एक्सेल और एक्सेल को JSON में बदलें" %}}
JSON डेटा को एक उदाहरण में आयात किया जा सकता है [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) की मदद से कक्षा [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) किसी भी समर्थित प्रारूप में आगे की प्रक्रिया या सरल रूपांतरण के लिए। इसी तरह, [कार्यपत्रक](https://reference.aspose.com/cells/net/aspose.cells/worksheet) डेटा को JSON के रूप में निर्यात किया जा सकता है a [श्रेणी](https://reference.aspose.com/cells/net/aspose.cells/range) या सेल और कॉल कर रहे हैं [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) तरीका।
{{% blocks/products/pf/feature-page-code h3="C# JSON से Excel रूपांतरण के लिए कोड" %}}
```cs
// वर्कबुक ऑब्जेक्ट बनाएं
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// फ़ाइल से JSON डेटा पढ़ें
string jsonInput = File.ReadAllText("Data.json");
// तालिका के रूप में सरणी का इलाज करने के लिए JsonLayoutOptions सेट करें
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// सेल A1 से शुरू होने वाली वर्कशीट में JSON डेटा आयात करें
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// परिणामी फ़ाइल को XLSX प्रारूप में सहेजें
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल से JSON रूपांतरण के लिए कोड" %}}
```cs
// कार्यपुस्तिका के उदाहरण के साथ XLSX फ़ाइल लोड करें
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// परिवर्तित किए जाने वाले डेटा वाले कार्यपत्रक के कक्षों तक पहुँच प्राप्त करें
var cells = workbook.Worksheets[0].Cells;
// उन्नत विकल्पों के लिए ExportRangeToJsonOptions बनाएं और सेट करें
var exportOptions = new Utility.ExportRangeToJsonOptions();
// निर्यात किए जाने वाले डेटा वाले कक्षों की एक श्रृंखला बनाएं
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// JSON डेटा के रूप में निर्यात सीमा
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// JSON प्रारूप में डिस्क पर डेटा फ़ाइल लिखें
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को जेपीजी, बीएमपी, पीएनजी और जीआईएफ में बदलें" %}}
एक्सेल फ़ाइल की प्रत्येक वर्कशीट को किसके द्वारा सेट किए गए विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है? [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) संपत्ति। डिफ़ॉल्ट मान `ImageFormat.Bmp` है।
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल से छवि रूपांतरण के लिए कोड" %}}
```cs
// टेम्पलेट स्प्रैडशीट लोड करें
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// ImageOrPrintOptions का एक उदाहरण बनाएं और सेट करें
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// आउटपुट छवि प्रारूप सेट करें
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// संग्रह में पहली वर्कशीट के लिए शीटरेंडर बनाएं
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// छवि के लिए कार्यपत्रक प्रस्तुत करें
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को वर्ड और पॉवरपॉइंट में बदलें" %}}
उपयोग करते समय किसी भी स्प्रैडशीट को लोड करना और उसे Word DOCX और PowerPoint PPTX फ़ाइलों में बदलना संभव है [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) और [पीपीटीएक्स सेव विकल्प](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) नीचे दिखाए गए अनुसार कक्षाएं।
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल से वर्ड और पॉवरपॉइंट रूपांतरण के लिए कोड" %}}
```cs
// टेम्पलेट फ़ाइल लोड करें
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// स्प्रेडशीट को DOCX के रूप में सहेजें
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// स्प्रेडशीट को PPTX के रूप में सहेजें
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}