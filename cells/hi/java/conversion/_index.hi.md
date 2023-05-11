---
title:  Microsoft एक्सेल फ़ाइल रूपांतरण via Java
description: एक्सेल XLS, XLSX, ODS, CSV से PDF, XPS, HTML, JPEG, HTML, HTML और कई अन्य लोकप्रिय स्वरूपों के साथ कन्वर्ट करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फाइल रूपांतरण via Java" h2="Microsoft एक्सेल दस्तावेज़ों को स्प्रेडशीट, वेब, इमेज और फिक्स्ड-लेआउट स्वरूपों के रूप में सहेजें" >}}

{{% blocks/products/pf/feature-page-summary %}}
 किसी के लिए**एक्सेल कनवर्टर** आवेदन या समाधान, Java एक्सेल लाइब्रेरी XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619 सहित कई प्रारूपों को संभालने के दौरान स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। 3481. यह *Excel फ़ाइलों को PDF** में बदलने की भी अनुमति देता है, XPS, HTML, MHTML, सादा पाठ और लोकप्रिय छवि प्रारूप जैसे TIFF, JPG, PNG, BMP और SVG।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft एक्सेल प्रारूपों का अंतर-रूपांतरण" %}}
 स्प्रेडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक उदाहरण के साथ एक स्प्रेडशीट लोड करने की आवश्यकता होती है[वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) और उचित मूल्य का चयन करते समय वांछित प्रारूप में वापस सहेजना[सेवफॉर्मेट](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) गणना।
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए Java उदाहरण कोड" %}}

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


{{% blocks/products/pf/feature-page-section h2="एक्सेल को PDF, XPS, HTML और एमडी में कनवर्ट करें" %}}
 विशिष्ट आउटपुट स्वरूपों जैसे रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशिष्ट वर्ग उपलब्ध हैं[पीडीएफ सहेजें विकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) एक्सेल फाइल को PDF के रूप में बदलने के लिए,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) एक्सेल को XPS के रूप में निर्यात करने के लिए,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) एक्सेल को HTML के रूप में प्रस्तुत करने के लिए और[मार्कडाउन सेवऑप्शन](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) एक्सेल से मार्कडाउन रूपांतरण के लिए।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से PDF और वेब प्रारूपों के लिए Java नमूना कोड" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON को एक्सेल और एक्सेल को JSON में बदलें" %}}
 JSON डेटा को वर्कबुक क्लास के इंस्टेंस में किसकी मदद से इम्पोर्ट किया जा सकता है[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) किसी भी समर्थित प्रारूप में आगे की प्रक्रिया या सरल रूपांतरण के लिए। इसी प्रकार, वर्कशीट डेटा को JSON बनाकर निर्यात किया जा सकता है[श्रेणी](https://reference.aspose.com/cells/java/com.aspose.cells/range) या सेल और कॉलिंग[ExportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) तरीका।
{{% blocks/products/pf/feature-page-code h3="एक्सेल रूपांतरण के लिए JSON के लिए Java कोड" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल के लिए JSON रूपांतरण के लिए स्रोत कोड" %}}
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

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को छवियों में सहेजें" %}}
 प्रत्येक वर्कशीट को जेपीजी, BMP, PNG और GIF सहित इमेजटाइप संपत्ति द्वारा निर्धारित विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है। किसी के लिए**एक्सेल को छवियों में बदलें** मामला, लिंक से प्रासंगिक मामले का चयन करें।
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल से छवि रूपांतरण के लिए कोड" %}}
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

{{% blocks/products/pf/feature-page-section h2="Microsoft एक्सेल को वर्ड और PowerPoint में कनवर्ट करें" %}}
 उपयोग करते समय किसी भी स्प्रेडशीट को लोड करना और इसे वर्ड DOCX और PowerPoint PPTX फाइलों में बदलना संभव है[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [पीपीटीएक्ससेवऑप्शन](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) कक्षाएं जैसा कि नीचे दिखाया गया है।
{{% blocks/products/pf/feature-page-code h3="एक्सेल से वर्ड के लिए Java कोड और PowerPoint रूपांतरण" %}}
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
