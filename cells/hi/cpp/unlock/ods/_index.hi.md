---
title:  C++ के माध्यम से ODS दस्तावेज़ को अनलॉक करें
weight: 1190
description: Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए C++ रनटाइम एनवायरनमेंट पर पासवर्ड संरक्षित ODS फ़ाइल को अनलॉक करने के लिए उदाहरण कोड।
keywords: [C++ Aspose.Cells., C++ unlock ODS files., C++ how to unlock ODS document., C++ unprotect ODS files., remove protection from ODS files., decrypt ODS Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ के माध्यम से ODS फ़ाइलें अनलॉक करें" h2="C++ लाइब्रेरी का उपयोग करके ODS फ़ाइल सहित एक्सेल स्प्रेडशीट से सुरक्षा हटाएँ।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके ODS फ़ाइल की सुरक्षा कैसे हटाएँ" %}}

 ODS फ़ाइल को अनलॉक करने के लिए, हम इसका उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="ODS को C++ के माध्यम से अनलॉक करें" %}}

{{% blocks/products/pf/agp/text %}}

 आप की जरूरत है
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 निम्नलिखित वर्कफ़्लो को निष्पादित करने के लिए आपके प्रोजेक्ट में संदर्भित।

{{% /blocks/products/pf/agp/text %}}

1.  संरक्षित ODS फ़ाइल के पथ के साथ कार्यपुस्तिका वर्ग को त्वरित करें
1.  सुरक्षा हटाने के लिए डिफ़ॉल्ट या कोई वर्कशीट प्राप्त करें
1.  वर्कशीट.अनप्रोटेक्ट पद्धति से वर्कशीट सुरक्षा हटाएँ
1.  Workbook.Unprotect पद्धति से कार्यपुस्तिका सुरक्षा हटाएँ
1.  रिजल्ट को ODS फॉर्मेट में सेव करें

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

// instantiate a Workbook object with protected ODS file
Workbook workbook(u"protected.ods");

// access the default worksheet in the Excel file
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in ODS format
workbook.Save("unprotected.ods", SaveFormat::Auto);

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

        {{< blocks/products/pf/agp/demobox sectionTitle="अनलॉक करने के लिए निःशुल्क ऐप ODS" sectionDescription=" हमारे लाइव डेमो देखें[ODS फ़ाइलें अनलॉक करें](https://products.aspose.app/cells/unlock/ods) निम्नलिखित लाभों के साथ." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की कोई आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस ODS फ़ाइल अपलोड करें और \"अनलॉक\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" लिंक से परिणामी ODS फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ODS एक्सटेंशन वाली फ़ाइलें ओपन डॉक्यूमेंट स्प्रेडशीट दस्तावेज़ प्रारूप के लिए हैं जो उपयोगकर्ता द्वारा संपादन योग्य हैं। डेटा को ODF फ़ाइल के अंदर पंक्तियों और स्तंभों में संग्रहीत किया जाता है। यह XML-आधारित प्रारूप है और ओपन दस्तावेज़ प्रारूप (ODF) परिवार में कई उपप्रकारों में से एक है। प्रारूप OASIS द्वारा प्रकाशित और अनुरक्षित ODF 1.2 विनिर्देशों के भाग के रूप में निर्दिष्ट है। Windows के साथ-साथ अन्य ऑपरेटिंग सिस्टम पर कई एप्लिकेशन संपादन और हेरफेर के लिए Microsoft एक्सेल, नियोऑफिस और लिबरऑफिस सहित ODS फाइलें खोल सकते हैं। ODS फ़ाइलों को विभिन्न अनुप्रयोगों द्वारा अन्य स्प्रेडशीट प्रारूपों जैसे XLS, XLSX और अन्य में भी परिवर्तित किया जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित अनलॉकिंग प्रारूप" subTitle="C++ का उपयोग करके, कोई भी विभिन्न प्रारूपों की सुरक्षा/अनलॉकिंग को आसानी से हटा सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
