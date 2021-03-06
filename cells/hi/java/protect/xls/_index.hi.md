---
title: XLS दस्तावेज़ को Java के माध्यम से सुरक्षित और लॉक करें 
weight: 5070
url: /hi/java/protect/xls/ 
description: Java JSP/JSF एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए रनटाइम एनवायरनमेंट पर पासवर्ड का उपयोग करके XLS फ़ाइल को लॉक करने के लिए Java नमूना कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java के माध्यम से XLS फ़ाइलें एन्क्रिप्ट करें" h2=".NET लाइब्रेरी का उपयोग करके एक्सएलएस प्रारूप सहित एक्सेल स्प्रेडशीट को पासवर्ड से सुरक्षित रखें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLS फ़ाइल को कैसे सुरक्षित करें" %}}

 XLS फ़ाइल की सुरक्षा के लिए, हम उपयोग करेंगे
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान एन्क्रिप्शन API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
 [मावेना](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने मावेन-आधारित प्रोजेक्ट में स्थापित करें।

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="कोष" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से XLS फ़ाइलों को सुरक्षित रखने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells API का उपयोग करके दस्तावेज़ सुरक्षा कोड की कुछ ही पंक्तियों के साथ की जा सकती है।

{{% /blocks/products/pf/agp/text %}}

1. वर्कबुक क्लास को इंस्टेंट करके XLS फाइल लोड करें1. प्रोटेक्शन टाइप और पासवर्ड के साथ प्रोटेक्ट (..) मेथड का इस्तेमाल करें1. सेव () विधि द्वारा संरक्षित XLS फाइल को सेव करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- Aspose.Cells for Java का नवीनतम संस्करण सीधे . से प्राप्त करें [मावेना](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="" %}}

```cs

// एक्सएलएस फ़ाइल खोलें
Workbook wkb = new Workbook("sourceFile.xls");

// सुरक्षा प्रकार निर्दिष्ट करके कार्यपुस्तिका को सुरक्षित रखें
wkb.protect(ProtectionType.ALL, "12345");

// XLS फ़ाइल सहेजें
wkb.save("lockedFile.xls");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for Java API" %}}

 Aspose.Cells API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="XLS की सुरक्षा के लिए फ्री ऐप" sectionDescription="हमारे लाइव डेमो की जांच करें [XLS फ़ाइलें एन्क्रिप्ट करें](https://products.aspose.app/cells/protect/xls) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की आवश्यकता नहीं है" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस XLS फ़ाइल अपलोड करें और \"अनलॉक\" बटन दबाएं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" लिंक से परिणामी XLS फ़ाइल डाउनलोड करें" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
एक्सएलएस एक्सटेंशन वाली फाइलें एक्सेल बाइनरी फाइल फॉर्मेट का प्रतिनिधित्व करती हैं। ऐसी फाइलें माइक्रोसॉफ्ट एक्सेल के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे ओपनऑफिस कैल्क या ऐप्पल नंबर्स द्वारा बनाई जा सकती हैं। एक्सेल द्वारा सेव की गई फाइल को वर्कबुक के रूप में जाना जाता है, जहां प्रत्येक वर्कबुक में एक या अधिक वर्कशीट हो सकती हैं। डेटा को कार्यपत्रक में तालिका प्रारूप में उपयोगकर्ताओं के लिए संग्रहीत और प्रदर्शित किया जाता है और संख्यात्मक मान, पाठ डेटा, सूत्र, बाहरी डेटा कनेक्शन, चित्र और चार्ट तक फैल सकता है। माइक्रोसॉफ्ट एक्सेल जैसे एप्लिकेशन आपको पीडीएफ, सीएसवी, एक्सएलएसएक्स, टीXT, एचटीएमएल, एक्सपीएस, और कई अन्य सहित कई अलग-अलग प्रारूपों में कार्यपुस्तिका डेटा निर्यात करने देता है। XLS फ़ाइल स्वरूप को Microsoft Excel 2007 की रिलीज़ के साथ एक अधिक खुले और संरचित प्रारूप, XLSX के साथ बदल दिया गया था। नवीनतम संस्करण अभी भी XLS फ़ाइलों को बनाने और पढ़ने के लिए समर्थन प्रदान करते हैं, हालाँकि XLSX अब उपयोग की पहली पसंद है।

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित सुरक्षा दस्तावेज" subTitle="Java का उपयोग करके, कोई अन्य फ़ाइलों की सुरक्षा कर सकता है, जिनमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="एक्सएलएसबी" description="बाइनरी एक्सेल वर्कबुक फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}