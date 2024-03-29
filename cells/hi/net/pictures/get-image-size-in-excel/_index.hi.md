---
title:  एक्सेल via .NET में छवियाँ/चित्रों का आकार प्राप्त करें
weight: 10
description: .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म पर एक्सेल में छवियाँ/चित्रों का आकार प्राप्त करने के लिए C# स्रोत कोड।
keywords: [C# Aspose.Cells., c# Get Images/Pictures Size In Excel., c# Obtain Images/Pictures Size In Excel., c# Access Images/Pictures Size In Excel]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="एक्सेल via .NET में छवियाँ/चित्रों का आकार प्राप्त करें" h2="Microsoft या ओपन ऑफिस, एडोब PDF आदि जैसे किसी सॉफ्टवेयर के बिना विभिन्न वस्तुओं के साथ काम करने के लिए Aspose.Cells\' API का उपयोग करना।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके एक्सेल फ़ाइल में छवियों/चित्रों का आकार कैसे प्राप्त करें" %}}

 एक्सेल फ़ाइल में छवियों/तस्वीरों का आकार प्राप्त करने के लिए, हम इसका उपयोग करेंगे
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और स्प्लिटर API है। खुला
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 Aspose.Cells 
 और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से एक्सेल फ़ाइल में छवियों/चित्रों का आकार प्राप्त करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

आपको अपने परिवेश में निम्नलिखित वर्कफ़्लो को आज़माने के लिए aspose. Cells.dll की आवश्यकता है।

{{% /blocks/products/pf/agp/text %}}

+ XLSX फ़ाइल को पूर्ण पथ के साथ लोड किया जा रहा है।
+ इसके सूचकांक के माध्यम से वर्कशीट का चयन करें।
+ वर्कशीट की 'चित्र' विशेषता से उसके सूचकांक के माध्यम से चित्र वस्तु का चयन करें।
 + किसी चयनित चित्र वस्तु से आकार प्राप्त करने के विभिन्न तरीके हैं। भाग नीचे सूचीबद्ध हैं, अधिक जानकारी के लिए, कृपया देखें[MORE](https://reference.aspose.com/cells/net/aspose.cells.drawing/picture/)सूचना: 'चौड़ाई' और 'ऊंचाई' एक्सेल में दिखाए गए आयाम हैं जो मूल चित्र से बड़े या छोटे हो सकते हैं।
    + [चौड़ाई](https://reference.aspose.com/cells/net/aspose.cells.drawing/shape/width/) पिक्सेल की इकाई में, आकार की चौड़ाई का प्रतिनिधित्व करता है।
    + [ऊंचाई](https://reference.aspose.com/cells/net/aspose.cells.drawing/shape/height/) पिक्सेल की इकाई में, आकार की ऊंचाई का प्रतिनिधित्व करता है।
    + [मूल चौड़ाई](https://reference.aspose.com/cells/net/aspose.cells.drawing/picture/originalwidth/) चित्र की मूल चौड़ाई, पिक्सेल की इकाई में प्राप्त होती है।
    + [मूल ऊँचाई](https://reference.aspose.com/cells/net/aspose.cells.drawing/picture/originalheight/)पिक्सेल की इकाई में, चित्र की मूल ऊंचाई प्राप्त होती है।


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस यह सुनिश्चित करें कि आपके पास निम्नलिखित आवश्यकताएँ हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म के साथ संगत ओएस
-  Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण
-  अपने प्रोजेक्ट में Aspose.Cells for .NET डीएलएल का संदर्भ जोड़ें - ऊपर डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}


{{% blocks/products/pf/agp/text %}}
 
दो आकार-संबंधित विशेषताएँ 'विड्थस्केल' और 'हाइटस्केल' भी हैं, जो क्रमशः वर्तमान प्रदर्शन चौड़ाई और ऊंचाई के वास्तविक चौड़ाई और ऊंचाई के प्रतिशत का प्रतिनिधित्व करती हैं।
 यह ध्यान दिया जाना चाहिए कि इन दो विशेषता मानों में एक निश्चित त्रुटि है, कृपया उच्च परिशुद्धता आवश्यकताओं के मामले में उनका उपयोग न करें।
 
 निम्नलिखित कोड नमूना दर्शाता है कि किसी छवि/चित्र का आकार और प्रदर्शन ज़ूम अनुपात कैसे प्राप्त करें।

{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/code-block title="छवियों/चित्रों का आकार प्राप्त करें - C#" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "GetPictureSize.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for .NET API" %}}

Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using C#, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
