---
title: Java के माध्यम से Microsoft Excel फ़ाइल रूपांतरण 
url: /hi/java/conversion/
description: एक्सेल एक्सएलएस, एक्सएलएसएक्स, ओडीएस, सीएसवी को पीडीएफ, एक्सपीएस, एचटीएमएल, जेपीईजी, एचटीएमएल और कई अन्य लोकप्रिय प्रारूपों को Java कोड की कुछ पंक्तियों के साथ कनवर्ट करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel फ़ाइलें Java के माध्यम से रूपांतरण" h2="Microsoft Excel दस्तावेज़ों को स्प्रेडशीट, वेब, छवि और फ़िक्स्ड-लेआउट स्वरूपों के रूप में सहेजें" >}}

{{% blocks/products/pf/feature-page-summary %}}
किसी भी **एक्सेल कन्वर्टर** एप्लिकेशन या समाधान के लिए, एक्सएलएस, एक्सएलएसएक्स, एक्सएलएसएम, एक्सएलएसबी, एक्सएलटीएक्स, एक्सएलटीएम, सीएसवी, स्प्रेडशीटएमएल, ओडीएस सहित कई प्रारूपों को संभालने के दौरान एक्सेल लाइब्रेरी स्प्रेडशीट प्रोग्रामिंग और रूपांतरण प्रक्रियाओं को गति देती है। यह **एक्सेल फाइलों को पीडीएफ**, एक्सपीएस, एचटीएमएल, एमएचटीएमएल, प्लेन टेक्स्ट और लोकप्रिय छवि प्रारूपों जैसे टीआईएफएफ, जेपीजी, पीएनजी, बीएमपी और एसवीजी में बदलने की भी अनुमति देता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="माइक्रोसॉफ्ट एक्सेल प्रारूपों का अंतर-रूपांतरण" %}}
स्प्रैडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक स्प्रैडशीट लोड करने की आवश्यकता होती है जिसका उदाहरण: [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) और से उचित मूल्य का चयन करते हुए वांछित प्रारूप में वापस सहेजना [प्रारूप सहेजें](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) गणना
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फ़ाइल प्रारूप रूपांतरण के लिए उदाहरण कोड" %}}

```cs
// स्रोत फ़ाइल लोड करें
var wkb = new Workbook("sourceFile.xls");
// XLSX, ODS, SXC और FODS प्रारूपों के रूप में सहेजें
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल को पीडीएफ, एक्सपीएस, एचटीएमएल और एमडी में बदलें" %}}
विशिष्ट आउटपुट स्वरूपों के लिए रूपांतरण प्रक्रिया को नियंत्रित करने के लिए विशिष्ट वर्ग उपलब्ध हैं जैसे कि [पीडीएफ सेव विकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) एक्सेल फाइलों को पीडीएफ में बदलने के लिए, [एक्सपीएससेवविकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) एक्सेल को एक्सपीएस के रूप में निर्यात करने के लिए, [एचटीएमएल सेव विकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) एक्सेल को HTML के रूप में प्रस्तुत करने के लिए और [मार्कडाउन सेव विकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) एक्सेल से मार्कडाउन रूपांतरण के लिए। 
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल से पीडीएफ और वेब प्रारूपों के लिए नमूना कोड" %}}

```cs
// डिस्क से टेम्पलेट एक्सेल फ़ाइल लोड करें
var bk = new Workbook("source-file.xlsx");

// Java का उपयोग करके एक्सेल को पीडीएफ में बदलें
// पीडीएफ विकल्प बनाएं
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// एक्सेल को एक्सपीएस में सेव करें
bk.save("output.xps", new XpsSaveOptions());
// एक्सेल को HTML में सेव करें
bk.save("output.html", new HtmlSaveOptions());
// एक्सेल को मार्कडाउन (एमडी) में सेव करें
bk.save("output.md", new MarkdownSaveOptions());

// प्रासंगिक प्रारूप में सहेजने से पहले कोई भी अपनी पसंद के अनुसार प्रासंगिक बचत विकल्प सेट कर सकता है

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON को एक्सेल और एक्सेल को JSON में बदलें" %}}
JSON डेटा को किसकी मदद से वर्कबुक क्लास के इंस्टेंस में इंपोर्ट किया जा सकता है? [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) किसी भी समर्थित प्रारूप में आगे की प्रक्रिया या सरल रूपांतरण के लिए। इसी तरह, वर्कशीट डेटा को JSON के रूप में निर्यात करके a . बनाया जा सकता है [श्रेणी](https://reference.aspose.com/cells/java/com.aspose.cells/range) या सेल और कॉल कर रहे हैं [ExportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) तरीका।
{{% blocks/products/pf/feature-page-code h3="Java JSON से Excel रूपांतरण के लिए कोड" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// फ़ाइल पढ़ें
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// JsonLayoutOptions सेट करें
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSON डेटा आयात करें
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// एक्सेल फाइल सेव करें
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल से JSON रूपांतरण के लिए स्रोत कोड" %}}
```cs
// कार्यपुस्तिका के उदाहरण के साथ XLSX फ़ाइल लोड करें
Workbook workbook = new Workbook("sourceFile.xlsx");
// परिवर्तित किए जाने वाले डेटा वाले कार्यपत्रक के कक्षों तक पहुँच प्राप्त करें
Cells cells = workbook.getWorksheets().get(0).getCells();
// उन्नत विकल्पों के लिए ExportRangeToJsonOptions बनाएं और सेट करें
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// निर्यात किए जाने वाले डेटा वाले कक्षों की एक श्रृंखला बनाएं
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// JSON डेटा के रूप में निर्यात सीमा
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// JSON प्रारूप में डिस्क पर डेटा लिखें
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को इमेज में सेव करें" %}}
प्रत्येक वर्कशीट को इमेज टाइप प्रॉपर्टी द्वारा सेट किए गए जेपीजी, बीएमपी, पीएनजी और जीआईएफ सहित विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है। किसी भी **एक्सेल को इमेज में बदलें** मामले के लिए, लिंक से प्रासंगिक मामले का चयन करें।
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल से छवि रूपांतरण के लिए कोड" %}}
```cs
// टेम्पलेट स्प्रैडशीट लोड करें
var wkb = new Workbook("template.xlsx");

// ImageOptions के लिए एक वस्तु बनाएँ
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// छवि प्रकार सेट करें
imgOptions.setImageType(ImageType.PNG);

// पहली वर्कशीट प्राप्त करें।
Worksheet sheet = wkb.getWorksheets().get(0);

// लक्ष्य पत्रक के लिए शीटरेंडर ऑब्जेक्ट बनाएं
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// वर्कशीट के लिए इमेज जेनरेट करें
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="माइक्रोसॉफ्ट एक्सेल को वर्ड और पॉवरपॉइंट में बदलें" %}}
उपयोग करते समय किसी भी स्प्रैडशीट को लोड करना और उसे Word DOCX और PowerPoint PPTX फ़ाइलों में बदलना संभव है [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) और [पीपीटीएक्स सेव विकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) नीचे दिखाए गए अनुसार कक्षाएं।
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल से वर्ड और पॉवरपॉइंट रूपांतरण के लिए कोड" %}}
```cs
// टेम्पलेट फ़ाइल लोड करें
var wkb = new Workbook("template.xlsx");
// स्प्रेडशीट को DOCX के रूप में सहेजें
wkb.save("output.docx", new DocxSaveOptions());
// स्प्रेडशीट को PPTX के रूप में सहेजें
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}