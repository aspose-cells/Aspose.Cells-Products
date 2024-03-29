---
title:  अनलॉक XLSX दस्तावेज़ via .NET
weight: 2040
description: .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म पर पासवर्ड संरक्षित XLSX फ़ाइल को अनलॉक करने के लिए C# स्रोत कोड।
keywords: [C# Aspose.Cells., c# unlock XLSX files., c# how to unlock XLSX document., c# unprotect XLSX files., remove protection from XLSX files., decrypt XLSX Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSX स्प्रेडशीट को C# के माध्यम से अनलॉक करें" h2=".NET लाइब्रेरी का उपयोग करके XLSX से सुरक्षा हटाएँ।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके XLSX फ़ाइल को कैसे अनलॉक करें" %}}

 सुरक्षा XLSX फ़ाइल को हटाने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ सुरक्षा API है। खुला
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 **Aspose.Cells** 
 और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSX को C# के माध्यम से अनलॉक करें" %}}

{{% blocks/products/pf/agp/text %}}

 आप की जरूरत है
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 निम्नलिखित वर्कफ़्लो को निष्पादित करने के लिए आपके प्रोजेक्ट में संदर्भित।

{{% /blocks/products/pf/agp/text %}}

1.  संरक्षित XLSX फ़ाइल के पथ के साथ कार्यपुस्तिका वर्ग को त्वरित करें
1.  सुरक्षा हटाने के लिए डिफ़ॉल्ट या कोई वर्कशीट प्राप्त करें
1.  वर्कशीट.अनप्रोटेक्ट पद्धति से वर्कशीट सुरक्षा हटाएँ
1.  Workbook.Unprotect पद्धति से कार्यपुस्तिका सुरक्षा हटाएँ
1.  रिजल्ट को XLSX फॉर्मेट में सेव करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस यह सुनिश्चित करें कि आपके पास निम्नलिखित आवश्यकताएँ हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म के साथ संगत ओएस
-  Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण
-  अपने प्रोजेक्ट में Aspose.Cells for .NET डीएलएल का संदर्भ जोड़ें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="" %}}

```cs

// instantiate a Workbook object with protected XLSX file
var workbook = new Aspose.Cells.Workbook("protected.xlsx");

// access the default worksheet in the Excel file
var worksheet = workbook.Worksheets[0];

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSX format
workbook.Save("unprotected.xlsx", Aspose.Cells.SaveFormat.Auto);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for .NET API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="अनलॉक करने के लिए निःशुल्क ऐप XLSX" sectionDescription=" हमारे लाइव डेमो देखें[XLSX फ़ाइलें अनलॉक करें](https://products.aspose.app/cells/unlock/xlsx) निम्नलिखित लाभों के साथ." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की कोई आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस XLSX फ़ाइल अपलोड करें और \"अनलॉक\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" लिंक से परिणामी XLSX फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX Microsoft एक्सेल दस्तावेजों के लिए प्रसिद्ध प्रारूप है जिसे Microsoft द्वारा Microsoft ऑफिस 2007 की रिलीज के साथ पेश किया गया था। ओओएक्सएमएल मानक ईसीएमए-376 के भाग 2 में उल्लिखित ओपन पैकेजिंग कन्वेंशन के अनुसार व्यवस्थित संरचना के आधार पर, नया प्रारूप है एक ज़िप पैकेज जिसमें कई XML फ़ाइलें होती हैं। अंतर्निहित संरचना और फ़ाइलों की जांच केवल .xlsx फ़ाइल को अनज़िप करके की जा सकती है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित अनलॉकिंग प्रारूप" subTitle="C# का उपयोग करके, कोई भी विभिन्न प्रारूपों की सुरक्षा/अनलॉकिंग को आसानी से हटा सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
