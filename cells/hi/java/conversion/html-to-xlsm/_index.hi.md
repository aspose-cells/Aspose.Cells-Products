---
title: Java के माध्यम से HTML को XLSM में बदलें 
url: /hi/java/conversion/html-to-xlsm/ 
description: HTML प्रारूप के लिए XLSM फ़ाइल में नमूना Java रूपांतरण कोड। प्रोग्रामर इस उदाहरण कोड का उपयोग किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन के भीतर एक्सेल और ओपनऑफिस स्प्रेडशीट को एक्सएलएसएम में निर्यात करने के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java के माध्यम से HTML को XLSM में बदलें" h2="ऑन-प्रिमाइसेस Java लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को XLSM में बदलने के लिए HTML से XLSM Java रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके HTML को XLSM में कैसे बदलें" %}}

 HTML को XLSM में रेंडर करने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
 [मावेना](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने मावेन-आधारित प्रोजेक्ट में स्थापित करें।

{{% blocks/products/pf/agp/code-block title="कोष" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से HTML को XLSM में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Java डेवलपर कोड की कुछ ही पंक्तियों में HTML फ़ाइल को आसानी से XLSM में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. कार्यपुस्तिका वर्ग के उदाहरण के साथ HTML फ़ाइल लोड करें1. कार्यपुस्तिका को कॉल करें। विधि सहेजें1. पैरामीटर के रूप में XLSM एक्सटेंशन और SaveFormat के साथ आउटपुट पथ पास करें1. परिणामी XLSM फ़ाइल के लिए निर्दिष्ट पथ की जाँच करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- मावेन से सीधे Aspose.Cells for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="HTML से XLSM Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// कार्यपुस्तिका के उदाहरण में HTML फ़ाइल लोड करें
Workbook book = new Workbook("template.html");
// HTML को XLSM के रूप में सहेजें
book.save("output.xlsm", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="HTML से XLSM रूपांतरण लाइव डेमो" sectionDescription="[HTML को XLSM में बदलें](https://products.aspose.app/cells/conversion/html-to-xlsm) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी HTML फ़ाइल अपलोड करें, यह तुरंत XLSM में बदल जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java स्प्रैडशीट मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (हाइपर टेक्स्ट मार्कअप लैंग्वेज) ब्राउज़र में प्रदर्शन के लिए बनाए गए वेब पेजों का एक्सटेंशन है। वेब की भाषा के रूप में जाना जाता है, एचटीएमएल वेब पेजों के हिस्से के रूप में प्रदर्शित होने वाली नई सूचना आवश्यकताओं की आवश्यकताओं के साथ विकसित हुआ है। नवीनतम संस्करण को HTML 5 के रूप में जाना जाता है जो भाषा के साथ काम करने के लिए बहुत अधिक लचीलापन देता है। HTML पृष्ठ या तो सर्वर से प्राप्त होते हैं, जहां इन्हें होस्ट किया जाता है, या स्थानीय सिस्टम से भी लोड किया जा सकता है। प्रत्येक HTML पृष्ठ HTML तत्वों से बना होता है जैसे कि फॉर्म, टेक्स्ट, इमेज, एनिमेशन, लिंक आदि। इन तत्वों को टैग द्वारा दर्शाया जाता है जैसे कि img, a, p और कई अन्य जहां प्रत्येक टैग का प्रारंभ और अंत होता है। यह समग्र लेआउट प्रतिनिधित्व के लिए स्क्रिप्टिंग भाषाओं जैसे जावास्क्रिप्ट और स्टाइल शीट्स (सीएसएस) में लिखे गए अनुप्रयोगों को भी एम्बेड कर सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

XLSM एक्सटेंशन वाली फ़ाइलें एक प्रकार की स्प्रैडशीट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। एप्लिकेशन के दृष्टिकोण से, मैक्रो निर्देशों का सेट है जो प्रक्रियाओं को स्वचालित करने के लिए उपयोग किया जाता है। मैक्रो का उपयोग उन चरणों को रिकॉर्ड करने के लिए किया जाता है जो बार-बार किए जाते हैं और मैक्रो को फिर से चलाकर क्रियाओं को करने में सुविधा प्रदान करते हैं। मैक्रो को माइक्रोसॉफ्ट के विजुअल बेसिक फॉर एप्लिकेशन (वीबीए) के साथ एक्सेल वर्कबुक के भीतर विजुअल बेसिक एडिटर का उपयोग करके प्रोग्राम किया जाता है और इसे सीधे वहां से चलाया/डीबग किया जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप HTML को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-bmp/" name="एचटीएमएल टू बीएमपी" description="बिटमैप चित्र" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-csv/" name="एचटीएमएल से सीएसवी" description="अल्पविराम से अलग किये गए मान" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-dif/" name="एचटीएमएल टू डीआईएफ" description="डेटा इंटरचेंज प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-emf/" name="ईएमएफ के लिए एचटीएमएल" description="उन्नत मेटाफ़ाइल स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-gif/" name="जीआईएफ के लिए एचटीएमएल" description="ग्राफिकल इंटरचेंज प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-jpeg/" name="एचटीएमएल से जेपीईजी" description="जेपीईजी छवि" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-mhtml/" name="एचटीएमएल से एमएचटीएमएल" description="वेब पेज संग्रह प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-ods/" name="एचटीएमएल टू ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-pdf/" name="एचटीएमएल से पीडीएफ" description="वहनीय दस्तावेज़ स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-png/" name="एचटीएमएल से पीएनजी" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-svg/" name="एसवीजी के लिए एचटीएमएल" description="स्केलेबल वेक्टर ग्राफिक्स" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-tiff/" name="झगड़ा करने के लिए HTML" description="टैग की गई छवि प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-tsv/" name="HTML से TSV" description="टैब से अलग किए गए मान" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-txt/" name="HTML से TXT" description="सामग्री या लेख दस्तावेज़" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlm/" name="एचटीएमएल से एक्सएलएम" description="एक्सेल मैक्रो फ़ाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xls/" name="एचटीएमएल से एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlsb/" name="एचटीएमएल से एक्सएलएसबी" description="बाइनरी एक्सेल वर्कबुक फाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlsx/" name="एचटीएमएल से एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlt/" name="एचटीएमएल से एक्सएलटी" description="माइक्रोसॉफ्ट एक्सेल टेम्पलेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xltm/" name="एचटीएमएल से एक्सएलटीएम" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xltx/" name="एचटीएमएल से एक्सएलटीएक्स" description="ऑफिस ओपनएक्सएमएल एक्सेल टेम्प्लेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xps/" name="एचटीएमएल टू एक्सपीएस" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-json/" name="जेएसओएन के लिए एचटीएमएल" description="जावास्क्रिप्ट ऑब्जेक्ट नोटेशन" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}