---
title: Java में विभिन्न एक्सेल फ़ाइलों को एक में मर्ज करें
description: Java का उपयोग करके एक्सेल फ़ाइलों को एकाधिक शीट या एकल शीट में मर्ज करें। Excel दस्तावेज़ों को PDF, छवियाँ और HTML पर भी मर्ज करें, संयोजित करें या संयोजित करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल मर्जिंग via Java" h2="Java कोड का उपयोग करके दो या दो से अधिक एक्सेल फ़ाइलों को एक ही स्प्रेडशीट में संयोजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java एक्सेल लाइब्रेरी](/cells/hi/java/) विभिन्न प्रकार की सामग्री जैसे सूत्र, चित्र, डेटा, चार्ट आदि के साथ कार्यपुस्तिकाओं को एक ही स्प्रेडशीट दस्तावेज़ में संयोजित करने के कई तरीके प्रदान करता है। समर्थित फ़ाइल स्वरूपों में XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV और अधिक शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फ़ाइलों को छवियों और चार्ट के साथ संयोजित करें" %}}
 छवियों और चार्ट वाली दो एक्सेल फ़ाइलों को संयोजित करने का सबसे सरल तरीका कॉल करना है[कार्यपुस्तिका.संयोजन](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) तरीका। यह समान प्रकार की एक्सेल फ़ाइलों को एक एकल स्प्रेडशीट में मर्ज करने की अनुमति देता है।
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फाइलों को संयोजित करने के लिए कोड" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="एकाधिक एक्सेल फ़ाइलें मर्ज करें" %}}
[सेल्सहेल्पर.मर्जफ़ाइलें](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)विधि एक्सेल फ़ाइल के डेटा, शैली और सूत्रों को उसी प्रारूप की एक नई स्प्रेडशीट में मर्ज करने का समर्थन करती है। यह कैशिंग का उपयोग करते हुए कई फ़ाइलों को मर्ज करने का एक प्रभावी तरीका है।
{{% blocks/products/pf/feature-page-code h3="Java कई एक्सेल फाइलों को मर्ज करने के लिए कोड" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="वर्कशीट को कॉपी करके एक्सेल फाइलों को मर्ज करें" %}}
[वर्कशीट.कॉपी](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) का उपयोग किसी स्रोत वर्कशीट से किसी अन्य वर्कशीट में या कार्यपुस्तिकाओं के बीच डेटा और फ़ॉर्मेटिंग की प्रतिलिपि बनाने के लिए किया जा सकता है। विधि स्रोत वर्कशीट ऑब्जेक्ट को एक पैरामीटर के रूप में लेती है।
{{% blocks/products/pf/feature-page-code h3="Java वर्कबुक के बीच वर्कशीट कॉपी करने के लिए कोड" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित विलय प्रारूप" subTitle="Java का उपयोग करके, कोई भी कई अन्य फ़ाइल स्वरूपों को मर्ज कर सकता है..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="अल्पविराम से अलग किये गए मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="वेब पेज पुरालेख प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="टैब-पृथक मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="सामग्री या लेख दस्तावेज़" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft एक्सेल टेम्पलेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
