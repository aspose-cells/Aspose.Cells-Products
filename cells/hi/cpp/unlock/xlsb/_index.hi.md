---
title:  C++ के माध्यम से XLSB दस्तावेज़ को अनलॉक करें
weight: 7420
description: Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए C++ रनटाइम एनवायरनमेंट पर पासवर्ड संरक्षित XLSB फ़ाइल को अनलॉक करने के लिए उदाहरण कोड।
keywords: [C++ Aspose.Cells., C++ unlock XLSB files., C++ how to unlock XLSB document., C++ unprotect XLSB files., remove protection from XLSB files., decrypt XLSB Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ के माध्यम से XLSB फ़ाइलें अनलॉक करें" h2="C++ लाइब्रेरी का उपयोग करके XLSB फ़ाइल सहित एक्सेल स्प्रेडशीट से सुरक्षा हटाएँ।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके XLSB फ़ाइल की सुरक्षा कैसे हटाएँ" %}}

 XLSB फ़ाइल को अनलॉक करने के लिए, हम इसका उपयोग करेंगे
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ सुरक्षा प्लेटफ़ॉर्म है API for C++। आप इसका नवीनतम संस्करण सीधे डाउनलोड कर सकते हैं, बस खोलें
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 **Aspose.Cells.Cpp** 
 और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB को C++ के माध्यम से अनलॉक करें" %}}

{{% blocks/products/pf/agp/text %}}

 आप की जरूरत है
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 निम्नलिखित वर्कफ़्लो को निष्पादित करने के लिए आपके प्रोजेक्ट में संदर्भित।

{{% /blocks/products/pf/agp/text %}}

1.  संरक्षित XLSB फ़ाइल के पथ के साथ कार्यपुस्तिका वर्ग को त्वरित करें
1.  सुरक्षा हटाने के लिए डिफ़ॉल्ट या कोई वर्कशीट प्राप्त करें
1.  वर्कशीट.अनप्रोटेक्ट पद्धति से वर्कशीट सुरक्षा हटाएँ
1.  Workbook.Unprotect पद्धति से कार्यपुस्तिका सुरक्षा हटाएँ
1.  रिजल्ट को XLSB फॉर्मेट में सेव करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ सभी प्रमुख प्लेटफार्मों और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित शर्तें हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए C++ रनटाइम एनवायरमेंट के साथ एक संगत ओएस।
-  अपने प्रोजेक्ट में Aspose.Cells for C++ डीएलएल का संदर्भ जोड़ें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// instantiate a Workbook object with protected XLSB file
Workbook workbook(u"protected.xlsb");

// access the default worksheet in the Excel file
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSB format
workbook.Save("unprotected.xlsb", SaveFormat::Auto);

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

        {{< blocks/products/pf/agp/demobox sectionTitle="अनलॉक करने के लिए निःशुल्क ऐप XLSB" sectionDescription=" हमारे लाइव डेमो देखें[XLSB फ़ाइलें अनलॉक करें](https://products.aspose.app/cells/unlock/xlsb) निम्नलिखित लाभों के साथ." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की कोई आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस XLSB फ़ाइल अपलोड करें और \"अनलॉक\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" लिंक से परिणामी XLSB फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB फ़ाइल स्वरूप एक्सेल बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो एक्सेल कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। सामग्री में संख्याओं, पाठ, या दोनों संख्याओं और पाठ, सूत्रों, बाहरी डेटा कनेक्शन, चार्ट और छवियों की असंरचित या अर्ध-संरचित तालिकाएँ शामिल हो सकती हैं। XLSX (जो ओपन एक्सएमएल फ़ाइल प्रारूप पर आधारित है) के विपरीत, XLSB बाइनरी एक्सेल वर्कबुक फ़ाइल का प्रतिनिधित्व करता है। XLSB फ़ाइलों को तेजी से पढ़ा और लिखा जा सकता है जो उन्हें बड़ी फ़ाइलों के साथ काम करने के लिए उपयोगी बनाता है। XLSB का उपयोग कार्यपुस्तिकाओं को संग्रहीत करने के लिए शायद ही कभी किया जाता है क्योंकि XLSX (और पहले XLS) कार्यपुस्तिकाओं को सहेजने के लिए सबसे आम उपयोगकर्ता द्वारा चयनित फ़ाइल स्वरूप हैं। इसे Microsoft Office 2007 और इससे ऊपर के नंबर पर खोला जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित अनलॉकिंग प्रारूप" subTitle="C++ का उपयोग करके, कोई भी विभिन्न प्रारूपों की सुरक्षा/अनलॉकिंग को आसानी से हटा सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
