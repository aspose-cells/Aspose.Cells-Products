---
title: Java में अलग-अलग एक्सेल फाइलों को एक में मर्ज करें
url: /hi/java/merger/
description: Java का उपयोग करके एक्सेल फाइलों को एक से अधिक शीट या सिंगल शीट में मर्ज करें। एक्सेल दस्तावेज़ों को पीडीएफ, इमेज और एचटीएमएल में भी मर्ज, संयोजित या संयोजित करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel फ़ाइल Java के माध्यम से विलय" h2="Java कोड . का उपयोग करके एक ही स्प्रैडशीट में दो या अधिक एक्सेल फ़ाइलों को संयोजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java एक्सेल लाइब्रेरी](/cells/java/) एक स्प्रेडशीट दस्तावेज़ में सूत्र, चित्र, डेटा, चार्ट आदि जैसे विभिन्न प्रकार की सामग्री के साथ कार्यपुस्तिकाओं को संयोजित करने के कई तरीके प्रदान करता है। समर्थित फ़ाइल स्वरूपों में XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV और बहुत कुछ शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="इमेज और चार्ट के साथ एक्सेल फाइल्स को मिलाएं" %}}
छवियों और चार्ट वाली दो एक्सेल फ़ाइलों को संयोजित करने का सबसे सरल तरीका है [कार्यपुस्तिका.संयोजन](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) तरीका। यह समान प्रकार की एक्सेल फ़ाइलों को एकल स्प्रेडशीट में मर्ज करने की अनुमति देता है।
{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फाइलों को मिलाने के लिए कोड" %}}

```cs
// पहली एक्सेल फ़ाइल लोड करें
var book1 = new Workbook("with-charts.xlsx");
// दूसरी एक्सेल फाइल को एक अलग इंस्टेंस में लोड करें
var book2 = new Workbook("with-images.xlsx");

// दो कार्यपुस्तिकाओं को मिलाएं
book1.combine(book2);
// लक्ष्य कार्यपुस्तिका सहेजें 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="एकाधिक एक्सेल फ़ाइलें मर्ज करें" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) विधि एक्सेल फ़ाइल के डेटा, शैली और सूत्रों को उसी प्रारूप की एक नई स्प्रेडशीट में मर्ज करने का समर्थन करती है। कैशिंग का उपयोग करते समय कई फाइलों को मर्ज करने का यह एक प्रभावी तरीका है। 
{{% blocks/products/pf/feature-page-code h3="Java कई एक्सेल फाइलों को मर्ज करने के लिए कोड" %}}

```cs
// एक ऐरे बनाएं (लंबाई = 2)
String[] files = new String[2];
// मर्ज किए जाने के लिए फ़ाइल पथ निर्दिष्ट करें
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// परिणाम को बचाने के लिए फाइलों को मर्ज करें
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="वर्कशीट को कॉपी करके एक्सेल फाइल्स को मर्ज करें" %}}
[वर्कशीट.कॉपी](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)का उपयोग डेटा की प्रतिलिपि बनाने और किसी स्रोत कार्यपत्रक से किसी अन्य कार्यपत्रक में या कार्यपुस्तिकाओं के बीच स्वरूपण करने के लिए किया जा सकता है। विधि स्रोत वर्कशीट ऑब्जेक्ट को पैरामीटर के रूप में लेती है।
{{% blocks/products/pf/feature-page-code h3="Java कार्यपुस्तिकाओं के बीच कार्यपत्रकों की प्रतिलिपि बनाने के लिए कोड" %}}

```cs
// एक कार्यपुस्तिका बनाएँ।
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// एक और कार्यपुस्तिका बनाएँ।
Workbook excelWorkbook1 = new Workbook();

// पहली किताब की पहली शीट को दूसरी किताब में कॉपी करें।
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// फ़ाइल सहेजें।
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}