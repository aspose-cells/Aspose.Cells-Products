---
title:  ODS फ़ाइलें मेटाडेटा via .NET देखें या संपादित करें
weight: 320
description: .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म पर ODS प्रारूप मेटाडेटा को संपादित करने या देखने के लिए C# स्रोत कोड।
keywords: [C# Aspose.Cells., c# view ods metadata., c# add ods metadata., c# insert ods metadata., c# edit ods metadata., c# remove ods metadata., c# extract ods metadata., c# modify ods metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS मेटाडेटा via .NET निकालें" h2="सर्वर-साइड एपीआई का उपयोग करके ODS फ़ाइलों से मेटाडेटा जोड़ने, संपादित करने, हटाने या निकालने के लिए अपने स्वयं के .NET ऐप्स बनाएं।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके ODS मेटाडेटा कैसे निकालें" %}}

ODS मेटाडेटा निकालने के लिए, हम इसका उपयोग करेंगे
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ मेटाडेटा API है। खुला
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 **Aspose.Cells** 
 और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से ODS का मेटाडेटा निकालने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 ODS फ़ाइल में संग्रहीत उपयोगी जानकारी तक पहुँचें, जिसमें ODS फ़ाइल कब प्राप्त हुई, संसाधित हुई, समय-मुद्रांकित इत्यादि शामिल हैं।

{{% /blocks/products/pf/agp/text %}}

+ कार्यपुस्तिका के उदाहरण के साथ ODS लोड करें
+ वर्कबुक ऑब्जेक्ट का बिल्टइनडॉक्यूमेंटप्रॉपर्टीज़ संग्रह प्राप्त करें
+ संग्रह पर पुनरावृति करें
+ संपत्ति का नाम, प्रकार और मूल्य प्रदर्शित करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस यह सुनिश्चित करें कि आपके पास निम्नलिखित आवश्यकताएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म के साथ संगत ओएस।
-  Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण।
-  अपने प्रोजेक्ट में Aspose.Cells for .NET डीएलएल का संदर्भ जोड़ें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS - C# का मेटाडेटा निकालें" offSpacer="" %}}

```cs

// load the ODS with an instance of Workbook
var book = new Aspose.Cells.Workbook("template.ods");
// iterate over the BuiltInDocumentProperties collection
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Some properties may store multiple values
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for .NET API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन ऐप के माध्यम से ODS का मेटाडेटा निकालें" sectionDescription=" हमारे का उपयोग करके मेटाडेटा को ODS दस्तावेज़ों में देखें और संपादित करें[लाइव डेमो](https://products.aspose.app/cells/metadata) निम्नलिखित लाभों के साथ." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी ODS फ़ाइल अपलोड करें और दस्तावेज़ गुणों को संपादित करें" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" परिणामी फ़ाइल के लिए तुरंत डाउनलोड लिंक प्राप्त करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ODS एक्सटेंशन वाली फ़ाइलें ओपन डॉक्यूमेंट स्प्रेडशीट दस्तावेज़ प्रारूप के लिए हैं जो उपयोगकर्ता द्वारा संपादन योग्य हैं। डेटा को ODF फ़ाइल के अंदर पंक्तियों और स्तंभों में संग्रहीत किया जाता है। यह XML-आधारित प्रारूप है और ओपन दस्तावेज़ प्रारूप (ODF) परिवार में कई उपप्रकारों में से एक है। प्रारूप OASIS द्वारा प्रकाशित और अनुरक्षित ODF 1.2 विनिर्देशों के भाग के रूप में निर्दिष्ट है। Windows के साथ-साथ अन्य ऑपरेटिंग सिस्टम पर कई एप्लिकेशन संपादन और हेरफेर के लिए Microsoft एक्सेल, नियोऑफिस और लिबरऑफिस सहित ODS फाइलें खोल सकते हैं। ODS फ़ाइलों को विभिन्न अनुप्रयोगों द्वारा अन्य स्प्रेडशीट प्रारूपों जैसे XLS, XLSX और अन्य में भी परिवर्तित किया जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित मेटाडेटा प्रारूप" subTitle="C# का उपयोग करके, कोई भी कई अन्य प्रारूपों के मेटाडेटा में हेरफेर कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
