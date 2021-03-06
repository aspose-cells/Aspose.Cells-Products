---
title: TABDELIMITED को Java के माध्यम से SVG में बदलें 
url: /hi/java/conversion/tabdelimited-to-svg/ 
description: SVG फ़ाइल में TABDELIMITED प्रारूप के लिए नमूना Java रूपांतरण कोड। प्रोग्रामर इस उदाहरण कोड का उपयोग किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन में एसवीजी को एक्सेल और ओपनऑफिस स्प्रेडशीट निर्यात करने के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TABDELIMITED को Java के माध्यम से SVG में बदलें" h2="ऑन-प्रिमाइसेस Java लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को एसवीजी में बदलने के लिए TABDELIMITED से SVG Java रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके TABDELIMITED को SVG में कैसे बदलें" %}}

 SVG को TABDELIMITED रेंडर करने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="TABDELIMITED को SVG में बदलने के लिए कदम Java के माध्यम से" %}}

{{% blocks/products/pf/agp/text %}}

 Java डेवलपर कोड की कुछ ही पंक्तियों में आसानी से TABDELIMITED फ़ाइल को SVG में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. कार्यपुस्तिका के उदाहरण के साथ TABDELIMITED फ़ाइल लोड करें1. संग्रह से डिफ़ॉल्ट या किसी वर्कशीट का चयन करें1. ImageOrPrintOptions का ऑब्जेक्ट बनाएं और सेट करें1. वर्कशीट और इमेजऑरप्रिंटऑप्शन ऑब्जेक्ट्स के साथ शीटरेंडर बनाएं1. SVG फॉर्मेट में रिजल्ट सेव करने के लिए SheetRender.toImage मेथड को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- मावेन से सीधे Aspose.Cells for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SVG से TABDELIMITED Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// TABDELIMITED फ़ाइल को रेंडर करने के लिए लोड करें
Workbook workbook = new Workbook("sourceFile.tabdelimited");
// संग्रह से डिफ़ॉल्ट वर्कशीट तक पहुंचें
Worksheet worksheet = workbook.getWorksheets().get(0);
// परिणामी छवि के लिए पैरामीटर परिभाषित करें
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.SVG);
// वर्कशीट को एसवीजी फॉर्मेट में इमेज में बदलें
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.svg");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SVG रूपांतरण लाइव डेमो के लिए TABDELIMITED" sectionDescription="[TABDELIMITED को SVG में बदलें](https://products.aspose.app/cells/conversion/tabdelimited-to-svg) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी TABDELIMITED फाइल अपलोड करें, यह तुरंत SVG में बदल जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java स्प्रैडशीट मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

एसवीजी फाइलें स्केलेबल वेक्टर ग्राफिक्स फाइलें हैं जो छवि की उपस्थिति का वर्णन करने के लिए एक्सएमएल आधारित टेक्स्ट प्रारूप का उपयोग करती हैं। स्केलेबल शब्द इस तथ्य को संदर्भित करता है कि एसवीजी को बिना किसी गुणवत्ता को खोए विभिन्न आकारों में बढ़ाया जा सकता है। ऐसी फाइलों का पाठ आधारित विवरण उन्हें संकल्प से स्वतंत्र बनाता है। यह स्केलेबिलिटी प्राप्त करने के लिए वेबसाइट और प्रिंट ग्राफिक्स बनाने के लिए सबसे अधिक उपयोग किए जाने वाले प्रारूप में से एक है। प्रारूप का उपयोग केवल द्वि-आयामी ग्राफिक्स के लिए किया जा सकता है। SVG फाइलें क्रोम, इंटरनेट एक्सप्लोरर, फायरफॉक्स और सफारी सहित लगभग सभी आधुनिक ब्राउज़रों में देखी/खोली जा सकती हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}