---
title:  Microsoft एक्सेल फ़ाइल रूपांतरण C# के माध्यम से
description: Aspose.Cells for .NET पुस्तकालय। C# कोड की कुछ पंक्तियों के साथ एक्सेल, JSON, PDF, एक्सएमएल, HTML, TXT, TSV, CSV, एसक्यूएल, जेपीजी, PNG और अधिक प्रारूपों में कनवर्ट करें।
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल प्रारूप रूपांतरण via .NET" h2="एक्सेल फ़ाइलों को स्प्रेडशीट, वेब, छवि और फिक्स्ड-लेआउट प्रारूपों के रूप में आयात और निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET एक्सेल लाइब्रेरी XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619348 सहित लोकप्रिय प्रारूपों का समर्थन करते हुए स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। 1. यह एक्सेल फ़ाइलों को PDF, XPS, HTML, MHTML, प्लेन पर निर्यात करने की भी अनुमति देता है टेक्स्ट और लोकप्रिय छवि प्रारूप जैसे TIFF, जेपीजी, PNG, BMP और SVG।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को XLSX, ODS, SXC और FODS में कनवर्ट करें" %}}
 स्प्रेडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक उदाहरण के साथ स्प्रेडशीट लोड करने की आवश्यकता होती है[वर्कबुक](https://reference.aspose.com/cells/net/aspose.cells/workbook) और उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना[प्रारूप सहेजें](https://reference.aspose.com/cells/net/aspose.cells/saveformat) गणना
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए C# कोड" %}}

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


{{% blocks/products/pf/feature-page-section h2="एक्सेल को PDF, XPS, HTML एवं एमडी में बदलें" %}}
 विशिष्ट आउटपुट स्वरूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशेष कक्षाएं उपलब्ध हैं[पीडीएफसेवविकल्प](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) एक्सेल फ़ाइलों को PDF के रूप में निर्यात करने के लिए,[XpsSaveविकल्प](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) एक्सेल से XPS रूपांतरण के लिए,[HTMLSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) एक्सेल को HTML के रूप में प्रस्तुत करना और[मार्कडाउनसेवऑप्शंस](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) एक्सेल से मार्कडाउन रूपांतरण के लिए।
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल के लिए कोड PDF और वेब फॉर्मेट के लिए" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON को एक्सेल में और एक्सेल को JSON में बदलें" %}}
 JSON डेटा को एक उदाहरण में आयात किया जा सकता है[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) की मदद से कक्षा[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) किसी भी समर्थित प्रारूप में आगे की प्रक्रिया या सरल रूपांतरण के लिए। इसी प्रकार,[कार्यपत्रक](https://reference.aspose.com/cells/net/aspose.cells/worksheet) बनाकर डेटा को JSON के रूप में निर्यात किया जा सकता है[श्रेणी](https://reference.aspose.com/cells/net/aspose.cells/range) या सेल और कॉल कर रहे हैं[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) तरीका।
{{% blocks/products/pf/feature-page-code h3="C# कोड JSON से एक्सेल रूपांतरण के लिए" %}}
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

{{% blocks/products/pf/feature-page-code h3="एक्सेल के लिए C# कोड से JSON रूपांतरण" %}}
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

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को JPG, BMP, PNG और GIF में कनवर्ट करें" %}}
 एक्सेल फ़ाइल की प्रत्येक वर्कशीट को द्वारा निर्धारित विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) संपत्ति। डिफ़ॉल्ट मान `ImageFormat.Bmp` है।
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल से छवि रूपांतरण के लिए कोड" %}}
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

{{% blocks/products/pf/feature-page-section h2="एक्सेल को वर्ड में बदलें और PowerPoint" %}}
उपयोग करते समय किसी भी स्प्रेडशीट को लोड करना और उसे Word DOCX और PowerPoint PPTX फ़ाइलों में परिवर्तित करना संभव है[DocxSaveविकल्प](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [पीपीटीएक्ससेवऑप्शंस](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) कक्षाएं जैसा कि नीचे दिखाया गया है।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से वर्ड के लिए C# कोड और PowerPoint रूपांतरण" %}}
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
