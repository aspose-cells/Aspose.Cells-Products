---
title: C# के माध्यम से एमएचटीएमएल फ़ाइलें बनाएं 
url: /hi/net/create-mhtml/ 
description: C# एमएचटीएमएल दस्तावेज़ जनरेट करने के लिए नमूना कोड। VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन के भीतर MHTML फ़ाइलें बनाने के लिए इस कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से एमएचटीएमएल दस्तावेज़ बनाएं" h2="सर्वर साइड .NET APIs का उपयोग करके प्रोग्रामेटिक रूप से मूल और उच्च प्रदर्शन MHTML निर्माण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 चल रहे एप्लिकेशन के भीतर गतिशील रूप से एमएचटीएमएल फ़ाइल उत्पन्न करना आसान है। एमएस ऑफिस की आवश्यकता के बिना खरोंच से एमएचटीएमएल दस्तावेज़ बनाने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API जो .NET प्लेटफ़ॉर्म का उपयोग करके स्प्रेडशीट निर्माण, हेरफेर और रूपांतरण के लिए विभिन्न सुविधाएँ प्रदान करता है। डेवलपर्स आसानी से डेटा लिखने, चार्ट या ग्राफ़ बनाने के साथ-साथ स्प्रेडशीट में तालिका बनाने के लिए कोड बढ़ा सकते हैं।
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से एमएचटीएमएल कैसे बनाएं" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ ही पंक्तियों में डेटा प्रोसेसिंग के लिए अलग-अलग रिपोर्टिंग एप्लिकेशन चलाने के भीतर एमएचटीएमएल बनाना, लोड करना, संशोधित करना और परिवर्तित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1. अपनी कक्षा फ़ाइल में नाम स्थान शामिल करें1. वर्कबुक क्लास इंस्टेंस बनाएं।1. कार्यपुस्तिका की पहली कार्यपत्रक तक पहुँचें।1. वर्कशीट के वांछित सेल प्राप्त करें और सेल (सेलों) में मान इनपुट करें।1. कार्यपुस्तिका को MHTML फ़ाइल के रूप में सहेजने के लिए सहेजें विधि का उपयोग करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 बस सुनिश्चित करें कि सिस्टम में Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म के साथ-साथ Microsoft Visual Studio जैसे विकास परिवेश के साथ संगत OS है। 

{{% /blocks/products/pf/agp/text %}}

- कमांड लाइन से के रूप में स्थापित करें <code>nuget install Aspose.Cells</code> या विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से <code>Install-Package Aspose.Cells</code>.- वैकल्पिक रूप से, एक ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या सभी DLL प्राप्त करें <a href="https://downloads.aspose.com/cells/net">डाउनलोड</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="निम्न स्रोत कोड दिखाता है कि C# का उपयोग करके MHTML फ़ाइल कैसे बनाई जाती है।" offSpacer="" %}}

```cs

// वर्कबुक क्लास इंस्टेंस बनाएं।
Workbook wkb = new Workbook();

// कार्यपुस्तिका की पहली कार्यपत्रक तक पहुँचें।
Worksheet sht = wkb.Worksheets[0];

// वर्कशीट की वांछित सेल प्राप्त करें।
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// सेल (ओं) में मान इनपुट करें।
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// कार्यपुस्तिका को .mhtml फ़ाइल के रूप में सहेजें।
wkb.Save("created_one.mhtml");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 एक एक्सेल स्प्रेडशीट प्रोग्रामिंग लाइब्रेरी जो एमएचटीएमएल फाइलों को जेनरेट करने, संशोधित करने, कन्वर्ट करने, रेंडर करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफॉर्म एप्लिकेशन बनाने में सक्षम है। .NET एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित होता है, यह एक्सेल फाइलों को छवियों, पीडीएफ, एचटीएमएल, ओडीएस और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प बन जाता है।

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
एमएचटीएमएल एक्सटेंशन वाली फाइलें एक वेब पेज संग्रह प्रारूप का प्रतिनिधित्व करती हैं जिसे कई अलग-अलग अनुप्रयोगों द्वारा बनाया जा सकता है। प्रारूप को संग्रह प्रारूप के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़ी कोई भी चीज शामिल है जैसे कि चित्र, एप्लेट, एनिमेशन, ऑडियो फाइलें आदि। एमएचटीएमएल फाइलें इंटरनेट एक्सप्लोरर और माइक्रोसॉफ्ट वर्ड जैसे विभिन्न अनुप्रयोगों में खोली जा सकती हैं। Microsoft Windows MHTML फ़ाइल स्वरूप का उपयोग विंडोज़ पर किसी भी अनुप्रयोग के उपयोग के दौरान देखी गई समस्याओं के परिदृश्य को रिकॉर्ड करने के लिए करता है जो समस्याएँ उठाता है। एमएचटीएमएल फ़ाइल प्रारूप संदेश/rfc822 में परिभाषित विनिर्देशों के समान पृष्ठ सामग्री को एन्कोड करता है जो सादा पाठ ईमेल संबंधित विनिर्देश है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित स्प्रेडशीट जनरेशन" subTitle="आप नीचे सूचीबद्ध कुछ सहित अन्य Microsoft Excel स्वरूप भी बना सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="एक्सएलएस" description="माइक्रोसॉफ्ट एक्सेल स्प्रेडशीट (विरासत)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="एक्सएलएसएक्स" description="एक्सएमएल वर्कबुक खोलें" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="एक्सएलएसबी" description="एक्सेल बाइनरी वर्कबुक" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="एक्सएलएसएम" description="मैक्रो-सक्षम स्प्रेडशीट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="एक्सएलटी" description="एक्सेल 97 - 2003 टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="एक्सएलटीएक्स" description="एक्सेल टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="एक्सएलटीएम" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="सीएसवी" description="अल्पविराम से अलग किये गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="टीएसवी" description="टैब से अलग किए गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="ओडीएस" description="ओपन डॉक्यूमेंट स्प्रेडशीट" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
