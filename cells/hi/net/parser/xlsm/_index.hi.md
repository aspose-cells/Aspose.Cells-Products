---
title:  XLSM दस्तावेज़ via .NET से पाठ और छवियाँ निकालें
weight: 4010
description: .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म पर XLSM फ़ाइल से पाठ और चित्र निकालने के लिए C# स्रोत कोड।
keywords: [C# Aspose.Cells., c# Extract text and images from XLSM file., c# How to Parse XLSM File., c# Extract text from XLSM file., Extract images from XLSM file using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# में पार्स XLSM प्रारूप" h2="Microsoft या एडोब PDF जैसे किसी भी सॉफ़्टवेयर के उपयोग के बिना, सर्वर-साइड Aspose.Cells for .NET एपीआई का उपयोग करके मूल और उच्च प्रदर्शन XLSM दस्तावेज़ पार्सिंग।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके XLSM फ़ाइल को कैसे पार्स करें" %}}

 XLSM फ़ाइल को पार्स करने के लिए, हम इसका उपयोग करेंगे[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर API है। खुला[NuGet](https://www.nuget.org/packages/aspose.cells) पैकेज मैनेजर, खोजें
 **Aspose.Cells** और इंस्टॉल करें. आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# में XLSM फ़ाइलों को पार्स करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 एक बुनियादी दस्तावेज़ पार्सिंग के साथ[Aspose.Cells for .NET](https://products.aspose.com/cells/net)एपीआई को कोड की कुछ पंक्तियों के साथ किया जा सकता है। Microsoft Excel XLS, XLSX, XLSM, XLSB और OpenDocument ODS फ़ाइलों से पाठ और छवियों को पार्स करें।

{{% /blocks/products/pf/agp/text %}}

+ XLSM दस्तावेज़ लोड करें।
+ शीट का चयन करें.
+ चित्र और छवि प्रकार प्राप्त करें।
+ छवि सहेजें.
+ दस्तावेज़ सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

हमारे एपीआई सभी प्रमुख प्लेटफार्मों और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित आवश्यकताएँ हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Mono या ज़ामरिन प्लेटफ़ॉर्म के साथ संगत ओएस
-  Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण
-  अपने प्रोजेक्ट में Aspose.Cells for .NET डीएलएल का संदर्भ जोड़ें - ऊपर डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="पार्स XLSM फ़ाइलें - C#" offSpacer="" %}}

```cs
    // extract images from Worksheets 
    // open a template Excel file
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xlsm");
    
    // get the first worksheet
    Worksheet worksheet = workbook.Worksheets[0];
    
    // get the first Picture in the first worksheet
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // set the output image file path
    string picformat = pic.ImageType.ToString();
                
    // Note: you may evaluate the image format before specifying the image path
    // define ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // specify the image format
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // save the image
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for .NET API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन XLSM पार्सर लाइव डेमो" sectionDescription="अभी हमारे यहां जाकर XLSM दस्तावेज़ों से पाठ और छवियाँ निकालें[लाइव डेमो वेबसाइट](https://products.aspose.app/cells/parser). लाइव डेमो के निम्नलिखित लाभ हैं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी XLSM फ़ाइलें अपलोड करें।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" इसे तुरंत पार्स किया जाएगा." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
XLSM एक्सटेंशन वाली फ़ाइलें एक प्रकार की स्प्रेडशीट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। अनुप्रयोग के दृष्टिकोण से, मैक्रो निर्देशों का एक सेट है जिसका उपयोग प्रक्रियाओं को स्वचालित करने के लिए किया जाता है। मैक्रो का उपयोग उन चरणों को रिकॉर्ड करने के लिए किया जाता है जो बार-बार किए जाते हैं और मैक्रो को फिर से चलाकर क्रियाओं को निष्पादित करने की सुविधा प्रदान करते हैं। मैक्रोज़ को विज़ुअल बेसिक एडिटर का उपयोग करके एक्सेल वर्कबुक के भीतर से Microsoft के विज़ुअल बेसिक फॉर एप्लिकेशन (वीबीए) के साथ प्रोग्राम किया गया है और वहां से सीधे चलाया/डीबग किया जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित पार्सिंग प्रारूप" subTitle="C# का उपयोग करके, कोई भी अन्य प्रारूपों को आसानी से पार्स कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
