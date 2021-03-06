---
title: XLTM को Java के माध्यम से XML में बदलें 
url: /hi/java/conversion/xltm-to-xml/ 
description: एक्सएमएल फ़ाइल में एक्सएलटीएम प्रारूप के लिए नमूना Java रूपांतरण कोड। प्रोग्रामर इस उदाहरण कोड का उपयोग किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन के भीतर एक्सेल और ओपनऑफिस स्प्रेडशीट को एक्सएमएल में निर्यात करने के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLTM को Java के माध्यम से XML में बदलें" h2="XLTM से XML Java रूपांतरण ऑन-प्रिमाइसेस Java लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को XML में बदलने के लिए।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLTM को XML में कैसे बदलें" %}}

 XLTM को XML में रेंडर करने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="XLTM को Java के माध्यम से XML में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Java डेवलपर कोड की कुछ ही पंक्तियों में आसानी से XLTM फ़ाइल को XML में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. कार्यपुस्तिका वर्ग के उदाहरण के साथ XLTM फ़ाइल लोड करें1. कार्यपुस्तिका को कॉल करें। विधि सहेजें1. XML एक्सटेंशन के साथ आउटपुट पथ पास करें और पैरामीटर के रूप में SaveFormat करें1. परिणामी XML फ़ाइल के लिए निर्दिष्ट पथ की जाँच करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- मावेन से सीधे Aspose.Cells for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTM से XML Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// कार्यपुस्तिका के उदाहरण में XLTM फ़ाइल लोड करें
Workbook book = new Workbook("template.xltm");
// XLTM को XML के रूप में सहेजें
book.save("output.xml", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="एक्सएलटीएम से एक्सएमएल रूपांतरण लाइव डेमो" sectionDescription="[XLTM को XML में बदलें](https://products.aspose.app/cells/conversion/xltm-to-xml) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी XLTM फ़ाइल अपलोड करें, यह तुरंत XML में कनवर्ट हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java स्प्रैडशीट मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTM" readMoreLink="https://docs.fileformat.com/spreadsheet/xltm/" >}}

XLTM फ़ाइल एक्सटेंशन उन फ़ाइलों का प्रतिनिधित्व करता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न होती हैं। XLTM फ़ाइलें संरचना में XLTX के समान हैं, इसके अलावा बाद में मैक्रोज़ के साथ टेम्प्लेट फ़ाइलें बनाने का समर्थन नहीं करता है। इस तरह की टेम्प्लेट फ़ाइलों का उपयोग मैक्रो के साथ लेआउट, स्वरूपण और अन्य सेटिंग्स को उत्पन्न करने और सेट करने के लिए किया जाता है ताकि समान XLSX फाइलें बनाने की सुविधा मिल सके।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

एक्सएमएल एक्स्टेंसिबल मार्कअप लैंग्वेज के लिए है जो एचटीएमएल के समान है लेकिन वस्तुओं को परिभाषित करने के लिए टैग का उपयोग करने में अलग है। एक्सएमएल फाइल फॉर्मेट के निर्माण के पीछे का पूरा विचार सॉफ्टवेयर या हार्डवेयर टूल्स पर निर्भर हुए बिना डेटा को स्टोर और ट्रांसपोर्ट करना था। इसकी लोकप्रियता इस वजह से है कि यह मानव और मशीन दोनों के पठनीय होने के कारण है। यह इसे वर्ल्ड वाइड वेब (WWW) जैसे नेटवर्क पर संग्रहीत और साझा की जाने वाली वस्तुओं के रूप में सामान्य डेटा प्रोटोकॉल बनाने में सक्षम बनाता है। एक्सएमएल में "एक्स" एक्स्टेंसिबल के लिए है जिसका अर्थ है कि उपयोगकर्ता की आवश्यकताओं के अनुसार भाषा को किसी भी संख्या में प्रतीकों तक बढ़ाया जा सकता है। इन सुविधाओं के लिए ही कई मानक फ़ाइल स्वरूप इसका उपयोग करते हैं जैसे कि माइक्रोसॉफ्ट ओपन एक्सएमएल, लिब्रे ऑफिस ओपन डॉक्यूमेंट, एक्सएचटीएमएल और एसवीजी।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप XLTM को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-bmp/" name="एक्सएलटीएम से बीएमपी" description="बिटमैप चित्र" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-csv/" name="एक्सएलटीएम से सीएसवी" description="अल्पविराम से अलग किये गए मान" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-dif/" name="एक्सएलटीएम टू डीआईएफ" description="डेटा इंटरचेंज प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-emf/" name="एक्सएलटीएम से ईएमएफ" description="उन्नत मेटाफ़ाइल स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-gif/" name="जीआईएफ के लिए एक्सएलटीएम" description="ग्राफिकल इंटरचेंज प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-html/" name="एक्सएलटीएम से एचटीएमएल" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-jpeg/" name="एक्सएलटीएम से जेपीईजी" description="जेपीईजी छवि" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-mhtml/" name="एक्सएलटीएम से एमएचटीएमएल" description="वेब पेज संग्रह प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-ods/" name="एक्सएलटीएम टू ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-pdf/" name="पीडीएफ के लिए एक्सएलटीएम" description="वहनीय दस्तावेज़ स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-png/" name="एक्सएलटीएम से पीएनजी" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-svg/" name="एक्सएलटीएम से एसवीजी" description="स्केलेबल वेक्टर ग्राफिक्स" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-tiff/" name="एक्सएलटीएम टू टीआईएफएफ" description="टैग की गई छवि प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-tsv/" name="XLTM से TSV" description="टैब से अलग किए गए मान" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-txt/" name="एक्सएलटीएम से टीXT" description="सामग्री या लेख दस्तावेज़" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlm/" name="एक्सएलटीएम से एक्सएलएम" description="एक्सेल मैक्रो फ़ाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xls/" name="एक्सएलटीएम से एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlsb/" name="एक्सएलटीएम से एक्सएलएसबी" description="बाइनरी एक्सेल वर्कबुक फाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlsx/" name="एक्सएलटीएम से एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xlt/" name="एक्सएलटीएम से एक्सएलटी" description="माइक्रोसॉफ्ट एक्सेल टेम्पलेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xltx/" name="एक्सएलटीएम से एक्सएलटीएक्स" description="ऑफिस ओपनएक्सएमएल एक्सेल टेम्प्लेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-xps/" name="एक्सएलटीएम से एक्सपीएस" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltm-to-json/" name="जेएसओएन के लिए एक्सएलटीएम" description="जावास्क्रिप्ट ऑब्जेक्ट नोटेशन" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}