---
title: XLSB को Java के माध्यम से MHTML में कनवर्ट करें 
weight: 4300
url: /hi/java/conversion/xlsb-to-mhtml/ 
description: एमएचटीएमएल फ़ाइल में एक्सएलएसबी प्रारूप के लिए नमूना Java रूपांतरण कोड। प्रोग्रामर इस उदाहरण कोड का उपयोग किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन के भीतर एक्सेल और ओपनऑफिस स्प्रेडशीट को एमएचटीएमएल में निर्यात करने के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSB को Java के माध्यम से MHTML में कनवर्ट करें" h2="ऑन-प्रिमाइसेस Java लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को एमएचटीएमएल में बदलने के लिए एक्सएलएसबी से एमएचटीएमएल Java रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLSB को MHTML में कैसे बदलें" %}}

 XLSB को MHTML में रेंडर करने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="एक्सएलएसबी को एमएचटीएमएल में बदलने के लिए कदम Java के माध्यम से" %}}

{{% blocks/products/pf/agp/text %}}

 Java डेवलपर XLSB फ़ाइल को कोड की कुछ ही पंक्तियों में आसानी से MHTML में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. कार्यपुस्तिका वर्ग के उदाहरण के साथ XLSB फ़ाइल लोड करें1. कार्यपुस्तिका को कॉल करें। विधि सहेजें1. पैरामीटर के रूप में MHTML एक्सटेंशन और SaveFormat के साथ आउटपुट पथ पास करें1. परिणामी एमएचटीएमएल फ़ाइल के लिए निर्दिष्ट पथ की जाँच करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- मावेन से सीधे Aspose.Cells for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSB से MHTML Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// कार्यपुस्तिका के उदाहरण में XLSB फ़ाइल लोड करें
Workbook book = new Workbook("template.xlsb");
// XLSB को MHTML के रूप में सहेजें
book.save("output.mhtml", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSB से MHTML रूपांतरण लाइव डेमो" sectionDescription="[XLSB को MHTML में कनवर्ट करें](https://products.aspose.app/cells/conversion/xlsb-to-mhtml) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी XLSB फ़ाइल अपलोड करें, यह तुरंत MHTML में कनवर्ट हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java स्प्रैडशीट मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

XLSB फ़ाइल स्वरूप Excel बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो Excel कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। सामग्री में संख्याओं की असंरचित या अर्ध-संरचित तालिकाएँ, पाठ, या दोनों संख्याएँ और पाठ, सूत्र, बाहरी डेटा कनेक्शन, चार्ट और चित्र शामिल हो सकते हैं। एक्सएलएसएक्स (जो ओपन एक्सएमएल फाइल फॉर्मेट पर आधारित है) के विपरीत, एक्सएलएसबी बाइनरी एक्सेल वर्कबुक फाइल का प्रतिनिधित्व करता है। XLSB फाइलें तेजी से पढ़ी और लिखी जा सकती हैं जो उन्हें बड़ी फाइलों के साथ काम करने के लिए उपयोगी बनाती हैं। XLSB का उपयोग शायद ही कभी कार्यपुस्तिकाओं को संग्रहीत करने के लिए किया जाता है क्योंकि XLSX (और पहले XLS) कार्यपुस्तिकाओं को सहेजने के लिए सबसे आम उपयोगकर्ता चयनित फ़ाइल स्वरूप हैं। इसे माइक्रोसॉफ्ट ऑफिस 2007 और इसके बाद के संस्करण द्वारा खोला जा सकता है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

एमएचटीएमएल एक्सटेंशन वाली फाइलें एक वेब पेज संग्रह प्रारूप का प्रतिनिधित्व करती हैं जिसे कई अलग-अलग अनुप्रयोगों द्वारा बनाया जा सकता है। प्रारूप को संग्रह प्रारूप के रूप में जाना जाता है क्योंकि यह वेब HTML कोड और संबंधित संसाधनों को एक फ़ाइल में सहेजता है। इन संसाधनों में वेबपेज से जुड़ी कोई भी चीज शामिल है जैसे कि चित्र, एप्लेट, एनिमेशन, ऑडियो फाइलें आदि। एमएचटीएमएल फाइलें इंटरनेट एक्सप्लोरर और माइक्रोसॉफ्ट वर्ड जैसे विभिन्न अनुप्रयोगों में खोली जा सकती हैं। Microsoft Windows MHTML फ़ाइल स्वरूप का उपयोग विंडोज़ पर किसी भी अनुप्रयोग के उपयोग के दौरान देखी गई समस्याओं के परिदृश्य को रिकॉर्ड करने के लिए करता है जो समस्याएँ उठाता है। एमएचटीएमएल फ़ाइल प्रारूप संदेश/rfc822 में परिभाषित विनिर्देशों के समान पृष्ठ सामग्री को एन्कोड करता है जो सादा पाठ ईमेल संबंधित विनिर्देश है। प्रारूप के वास्तविक विनिर्देश RFC 2557 द्वारा विस्तृत हैं।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप XLSB को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-bmp/" name="एक्सएलएसबी टू बीएमपी" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-csv/" name="एक्सएलएसबी से सीएसवी" description="अल्पविराम से अलग किये गए मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-dif/" name="एक्सएलएसबी टू डीआईएफ" description="डेटा इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-emf/" name="XLSB से EMF" description="उन्नत मेटाफ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-gif/" name="एक्सएलएसबी टू जीआईएफ" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-html/" name="एक्सएलएसबी से एचटीएमएल" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-jpeg/" name="एक्सएलएसबी से जेपीईजी" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-ods/" name="एक्सएलएसबी टू ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-pdf/" name="पीडीएफ के लिए एक्सएलएसबी" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-png/" name="एक्सएलएसबी से पीएनजी" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-svg/" name="एक्सएलएसबी से एसवीजी" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tiff/" name="एक्सएलएसबी टू टीआईएफएफ" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tsv/" name="XLSB से TSV" description="टैब से अलग किए गए मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-txt/" name="XLSB से TXT" description="सामग्री या लेख दस्तावेज़" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xls/" name="एक्सएलएसबी से एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsm/" name="एक्सएलएसबी से एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsx/" name="एक्सएलएसबी से एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlt/" name="एक्सएलएसबी से एक्सएलटी" description="माइक्रोसॉफ्ट एक्सेल टेम्पलेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltm/" name="एक्सएलएसबी से एक्सएलटीएम" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltx/" name="एक्सएलएसबी से एक्सएलटीएक्स" description="ऑफिस ओपनएक्सएमएल एक्सेल टेम्प्लेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xps/" name="एक्सएलएसबी से एक्सपीएस" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-json/" name="जेएसओएन के लिए एक्सएलएसबी" description="जावास्क्रिप्ट ऑब्जेक्ट नोटेशन" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}