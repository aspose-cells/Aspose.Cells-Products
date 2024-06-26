---
title: C++" के माध्यम से एन्क्रिप्टेड पीडीएफ फाइलों को सहेजना
weight: 10010
description: C++ उदाहरण कोड C++ रनटाइम वातावरण पर Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए पासवर्ड का उपयोग करके फ़ाइल एन्क्रिप्ट करने के लिए।
keywords: [C++ Aspose.Cells., C++ Encrypt PDF files., C++ How to Encrypt document., C++ Encrypt files., Encrypt PDF Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PDF फ़ाइलों को C++ के माध्यम से एन्क्रिप्ट करें" h2="एक्सेल स्प्रेडशीट को PDF फाइलों में बदलें और Aspose.Cells C++ लाइब्रेरी का उपयोग करके उन्हें पासवर्ड से सुरक्षित करें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके PDF फ़ाइल को एन्क्रिप्ट कैसे करें" %}}

 PDF फ़ाइल को एन्क्रिप्ट करने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ एन्क्रिप्शन API for C++ प्लेटफ़ॉर्म है। आप इसका नवीनतम संस्करण सीधे डाउनलोड कर सकते हैं, बस खोलें
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 **Aspose.Cells.Cpp** 
 और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ के माध्यम से PDF फ़ाइलों को एन्क्रिप्ट करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells एपीआई का उपयोग करके दस्तावेज़ संरक्षण केवल कुछ पंक्तियों के कोड के साथ किया जा सकता है।

{{% /blocks/products/pf/agp/text %}}

1.  नई Excel फ़ाइल लोड करने या बनाने के लिए Workbook क्लास का उपयोग करें
1.  PdfSecurityOptions वर्ग का उपयोग करके सुरक्षा विकल्प सेट करें
1.  एन्क्रिप्टेड PDF फ़ाइल को Save() विधि द्वारा सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ सभी प्रमुख प्लेटफ़ॉर्म और ऑपरेटिंग सिस्टम पर सपोर्ट करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या Windows 32 बिट, Windows 64 बिट और लिनक्स 64 बिट के लिए C++ रनटाइम एनवायरनमेंट के साथ संगत ओएस।
-  अपने प्रोजेक्ट में Aspose.Cells for C++ DLL का संदर्भ जोड़ें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//load/creat the Excel file
Workbook wb;

//Set cell value
wb.GetWorksheets().Get(0).GetCells().Get(u"A1").PutValue(u"test");

//Set security options using PdfSecurityOptions class
PdfSecurityOptions securityOptions;
securityOptions.SetOwnerPassword(u"123");
securityOptions.SetPrintPermission(true);
securityOptions.SetAccessibilityExtractContent(true);

//Set saving PDF parameters
PdfSaveOptions pdfSaveOptions;
pdfSaveOptions.SetSecurityOptions(securityOptions);

//Save encrypted PDF files
wb.Save("security.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for C++ API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणनाओं के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसे Microsoft या ओपनऑफिस जैसे किसी भी सॉफ्टवेयर की आवश्यकता नहीं है।



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="निःशुल्क सुरक्षा ऐप PDF" sectionDescription=" हमारे लाइव डेमो देखें[PDF फ़ाइलें एन्क्रिप्ट करें](https://products.aspose.app/cells/protect/pdf) निम्नलिखित लाभ के साथ." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की कोई आवश्यकता नहीं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस PDF फ़ाइल अपलोड करें और \"अनलॉक\" बटन दबाएं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" परिणामी PDF फ़ाइल को लिंक से डाउनलोड करें" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/spreadsheet/pdf/" >}}
    
पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट (PDF) 1990 के दशक में एडोब द्वारा बनाया गया एक प्रकार का दस्तावेज़ है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य दस्तावेज़ों और अन्य संदर्भ सामग्री को ऐसे फ़ॉर्मेट में प्रस्तुत करने के लिए एक मानक पेश करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो। PDF फ़ाइल फ़ॉर्मेट में टेक्स्ट, इमेज, हाइपरलिंक, फ़ॉर्म-फ़ील्ड, रिच मीडिया, डिजिटल सिग्नेचर, अटैचमेंट, मेटाडेटा, जियोस्पेशियल फ़ीचर और 3D ऑब्जेक्ट जैसी जानकारी रखने की पूरी क्षमता है जो स्रोत दस्तावेज़ का हिस्सा बन सकती है।

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुरक्षा दस्तावेज़" subTitle="C++ का उपयोग करके, अन्य फ़ाइलों की सुरक्षा की जा सकती है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="एक्सेल बाइनरी प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="OOXML एक्सेल फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
