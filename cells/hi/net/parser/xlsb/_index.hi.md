---
title: XLSB दस्तावेज़ से .NET के माध्यम से टेक्स्ट और चित्र निकालें 
weight: 2200
url: /hi/net/parser/xlsb/ 
description: .NET Framework, .NET Core, Mono या Xamarin प्लेटफॉर्म पर XLSB फ़ाइल से टेक्स्ट और छवियों को निकालने के लिए C# स्रोत कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSB स्वरूपों को C# में पार्स करें" h2="Microsoft या Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना सर्वर-साइड Aspose.Cells for .NET API का उपयोग करके मूल और उच्च प्रदर्शन XLSB दस्तावेज़ पार्स करना।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके XLSB फ़ाइल को कैसे पार्स करें" %}}

 XLSB फ़ाइल को पार्स करने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर API है। खुला
 [नुगेट](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 ***** 
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB फ़ाइलों को C# में पार्स करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 के साथ पार्सिंग एक मूल दस्तावेज़
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 एपीआई कोड की कुछ ही पंक्तियों के साथ किया जा सकता है। Microsoft Excel XLS, XLSX, XLSM, XLSB और OpenDocument ODS फ़ाइलों से पाठ और छवियों को पार्स करें।

{{% /blocks/products/pf/agp/text %}}

+ XLSB दस्तावेज़ लोड करें।
+ शीट का चयन करें।
+ चित्र और छवि प्रकार प्राप्त करें।
+ छवि सहेजें।
+ दस्तावेज़ सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 हमारे एपीआई सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono या Xamarin Platforms के साथ संगत OS- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल- Aspose.Cells for .NET DLL आपके प्रोजेक्ट में संदर्भित है - ऊपर दिए गए डाउनलोड बटन का उपयोग करके NuGet से इंस्टॉल करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="पार्स एक्सएलएसबी फ़ाइलें - C#" offSpacer="" %}}

```cs
    // कार्यपत्रकों से चित्र निकालें 
    // एक टेम्पलेट एक्सेल फ़ाइल खोलें
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xlsb");
    
    // पहली वर्कशीट प्राप्त करें
    Worksheet worksheet = workbook.Worksheets[0];
    
    // पहली वर्कशीट में पहला चित्र प्राप्त करें
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // आउटपुट छवि फ़ाइल पथ सेट करें
    string picformat = pic.ImageType.ToString();
                
    // नोट: आप छवि पथ निर्दिष्ट करने से पहले छवि प्रारूप का मूल्यांकन कर सकते हैं
    // ImageOrPrintOptions को परिभाषित करें
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // छवि प्रारूप निर्दिष्ट करें
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // छवि सहेजें
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for .NET API" %}}

 Aspose.Cells API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन एक्सएलएसबी पार्सर लाइव डेमो" sectionDescription="हमारे . पर जाकर अभी XLSB दस्तावेज़ों से टेक्स्ट और चित्र निकालें [लाइव डेमो वेबसाइट](https://products.aspose.app/cells/parser). लाइव डेमो के निम्नलिखित लाभ हैं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी एक्सएलएसबी फाइलें अपलोड करें।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" इसे तुरंत पार्स किया जाएगा।" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB फ़ाइल स्वरूप Excel बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो Excel कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। सामग्री में संख्याओं की असंरचित या अर्ध-संरचित तालिकाएँ, पाठ, या दोनों संख्याएँ और पाठ, सूत्र, बाहरी डेटा कनेक्शन, चार्ट और चित्र शामिल हो सकते हैं। एक्सएलएसएक्स (जो ओपन एक्सएमएल फाइल फॉर्मेट पर आधारित है) के विपरीत, एक्सएलएसबी बाइनरी एक्सेल वर्कबुक फाइल का प्रतिनिधित्व करता है। XLSB फाइलें तेजी से पढ़ी और लिखी जा सकती हैं जो उन्हें बड़ी फाइलों के साथ काम करने के लिए उपयोगी बनाती हैं। XLSB का उपयोग शायद ही कभी कार्यपुस्तिकाओं को संग्रहीत करने के लिए किया जाता है क्योंकि XLSX (और पहले XLS) कार्यपुस्तिकाओं को सहेजने के लिए सबसे आम उपयोगकर्ता चयनित फ़ाइल स्वरूप हैं। इसे माइक्रोसॉफ्ट ऑफिस 2007 और इसके बाद के संस्करण द्वारा खोला जा सकता है। 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित पार्सिंग प्रारूप" subTitle="C# का उपयोग करके, कोई भी अन्य प्रारूपों को आसानी से पार्स कर सकता है, जिनमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}