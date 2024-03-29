---
title: XLSX दस्तावेज़ में टेक्स्ट को C++ के माध्यम से खोजें और बदलें
weight: 9570
description: Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए C++ रनटाइम एनवायरनमेंट पर XLSX फ़ाइल में संवेदनशील जानकारी को संशोधित करने के लिए C++ उदाहरण कोड।
keywords: [C++ Aspose.Cells., C++ Search and replace text in XLSX file., C++ redact XLSX file., C++ edit XLSX file., C++ XLSX file redaction., C++ Search and replace string in XLSX file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ में XLSX प्रारूप को संशोधित करें" h2="मूल और उच्च प्रदर्शन XLSX, Microsoft या एडोब PDF जैसे किसी भी सॉफ्टवेयर के उपयोग के बिना, सर्वर-साइड Aspose.Cells for C++ एपीआई का उपयोग करके संवेदनशील संपादन जानकारी को दस्तावेज़ित करता है।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके XLSX फ़ाइल को कैसे संशोधित करें" %}}

 XLSX फ़ाइल को पुनः संपादित करने के लिए, हम इसका उपयोग करेंगे[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ संशोधन API for C++ प्लेटफ़ॉर्म है। आप इसका नवीनतम संस्करण सीधे डाउनलोड कर सकते हैं, बस खोलें[NuGet](https://www.nuget.org/packages/aspose.cells) पैकेज मैनेजर, खोजें**Aspose.Cells.Cpp** और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ में XLSX फ़ाइलों को पुनः संपादित करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 एक मूल दस्तावेज़ सामग्री, टिप्पणियों या मेटाडेटा में टेक्स्ट को खोजता है और प्रतिस्थापित करता है[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) एपीआई को कोड की कुछ पंक्तियों के साथ किया जा सकता है।

{{% /blocks/products/pf/agp/text %}}

+ XLSX फ़ाइल लोड करें।
+ बदलें विकल्प परिभाषित करें।
केस संवेदनशीलता विकल्प सेट करें।
+ टेक्स्ट मिलान विकल्प सेट करें
+ Replace(...) विधि का उपयोग करके टेक्स्ट बदलें
+ कार्यपुस्तिका सहेजें.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ सभी प्रमुख प्लेटफार्मों और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित शर्तें हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए C++ रनटाइम एनवायरमेंट के साथ एक संगत ओएस।
-  अपने प्रोजेक्ट में Aspose.Cells for C++ डीएलएल का संदर्भ जोड़ें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redact XLSX फ़ाइलें - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Load XLSX file
Workbook wb(u"Input.xlsx");
//Create an instance of the ReplaceOptions class
ReplaceOptions replaceOptions;
// Set text matching option
replaceOptions.SetRegexKey(true);
// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);
// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);
// Replace text
wb.Replace(u"\bKIM\b", u"^^^^^^^^", replaceOptions);
// Save as XLSX file
wb.Save("output.xlsx");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for C++ API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन XLSX रिडक्शन लाइव डेमो" sectionDescription=" XLSX दस्तावेज़ों में सामग्री, टिप्पणियों या मेटाडेटा में टेक्स्ट को अभी हमारे यहां जाकर खोजें और बदलें[लाइव डेमो वेबसाइट](https://products.aspose.app/cells/redaction). लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी XLSX फ़ाइलें अपलोड करें।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" इसे तुरंत संशोधित कर दिया जाएगा." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX Microsoft एक्सेल दस्तावेजों के लिए प्रसिद्ध प्रारूप है जिसे Microsoft द्वारा Microsoft ऑफिस 2007 की रिलीज के साथ पेश किया गया था। ओओएक्सएमएल मानक ईसीएमए-376 के भाग 2 में उल्लिखित ओपन पैकेजिंग कन्वेंशन के अनुसार व्यवस्थित संरचना के आधार पर, नया प्रारूप है एक ज़िप पैकेज जिसमें कई XML फ़ाइलें होती हैं। अंतर्निहित संरचना और फ़ाइलों की जांच केवल .xlsx फ़ाइल को अनज़िप करके की जा सकती है।

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुधार दस्तावेज़" subTitle="C++ का उपयोग करके, कोई भी आसानी से विभिन्न प्रारूपों को संपादित कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
