---
title: XLS को JSON में Java के माध्यम से कनवर्ट करें 
weight: 9680
url: /hi/java/conversion/xls-to-json/ 
description: नमूना Java XLS प्रारूप के लिए JSON फ़ाइल में रूपांतरण कोड। प्रोग्रामर इस उदाहरण कोड का उपयोग किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन के भीतर JSON को एक्सेल और ओपनऑफिस स्प्रेडशीट निर्यात करने के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS को JSON में Java के माध्यम से कनवर्ट करें" h2="ऑन-प्रिमाइसेस Java लाइब्रेरी का उपयोग करके एकल या एकाधिक पृष्ठों को JSON में बदलने के लिए XLS से JSON Java रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLS को JSON में कैसे बदलें" %}}

 JSON को XLS रेंडर करने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="XLS को JSON में बदलने के चरण Java के माध्यम से" %}}

{{% blocks/products/pf/agp/text %}}

कोड की कुछ ही पंक्तियों में डेवलपर्स आसानी से XLS फ़ाइल को JSON में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. कार्यपुस्तिका वर्ग के उदाहरण के साथ XLS फ़ाइल लोड करें1. Cells.createRange विधि . का उपयोग करके निर्यात किए जाने वाले डेटा की एक श्रेणी बनाएं1. रेंज और ExportRangeToJsonOptions के संदर्भों के साथ JsonUtility.exportRangeToJson विधि को कॉल करें1. BufferedWriter.write विधि के माध्यम से फाइल करने के लिए स्ट्रिंग JSON डेटा लिखें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 नमूना कोड का उपयोग करने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- मावेन से सीधे Aspose.Cells for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS से JSON Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// कार्यपुस्तिका के उदाहरण के साथ XLSX फ़ाइल लोड करें
Workbook workbook = new Workbook("template.xlsx");
// परिवर्तित किए जाने वाले डेटा वाले कार्यपत्रक के कक्षों तक पहुँच प्राप्त करें
Cells cells = workbook.getWorksheets().get(0).getCells();
// उन्नत विकल्पों के लिए ExportRangeToJsonOptions बनाएं और सेट करें
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// निर्यात किए जाने वाले डेटा वाले कक्षों की एक श्रृंखला बनाएं
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// JSON डेटा के रूप में निर्यात सीमा
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// JSON प्रारूप में डिस्क पर डेटा लिखें
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS से JSON रूपांतरण लाइव डेमो" sectionDescription="[XLS को JSON में बदलें](https://products.aspose.app/cells/conversion/xls-to-json) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी XLS फ़ाइल अपलोड करें, यह तुरंत JSON में बदल जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java स्प्रैडशीट मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

एक्सएलएस एक्सटेंशन वाली फाइलें एक्सेल बाइनरी फाइल फॉर्मेट का प्रतिनिधित्व करती हैं। ऐसी फाइलें माइक्रोसॉफ्ट एक्सेल के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे ओपनऑफिस कैल्क या ऐप्पल नंबर्स द्वारा बनाई जा सकती हैं। एक्सेल द्वारा सेव की गई फाइल को वर्कबुक के रूप में जाना जाता है, जहां प्रत्येक वर्कबुक में एक या अधिक वर्कशीट हो सकती हैं। डेटा को कार्यपत्रक में तालिका प्रारूप में उपयोगकर्ताओं के लिए संग्रहीत और प्रदर्शित किया जाता है और संख्यात्मक मान, पाठ डेटा, सूत्र, बाहरी डेटा कनेक्शन, चित्र और चार्ट तक फैल सकता है। माइक्रोसॉफ्ट एक्सेल जैसे एप्लिकेशन आपको पीडीएफ, सीएसवी, एक्सएलएसएक्स, टीXT, एचटीएमएल, एक्सपीएस, और कई अन्य सहित कई अलग-अलग प्रारूपों में कार्यपुस्तिका डेटा निर्यात करने देता है। XLS फ़ाइल स्वरूप को Microsoft Excel 2007 की रिलीज़ के साथ एक अधिक खुले और संरचित प्रारूप, XLSX के साथ बदल दिया गया था। नवीनतम संस्करण अभी भी XLS फ़ाइलों को बनाने और पढ़ने के लिए समर्थन प्रदान करते हैं, हालाँकि XLSX अब उपयोग की पहली पसंद है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (जावास्क्रिप्ट ऑब्जेक्ट नोटेशन) डेटा साझा करने के लिए एक खुला मानक फ़ाइल स्वरूप है जो डेटा को संग्रहीत और संचारित करने के लिए मानव-पठनीय पाठ का उपयोग करता है। JSON फ़ाइलें .json एक्सटेंशन के साथ संग्रहीत की जाती हैं। JSON को कम स्वरूपण की आवश्यकता होती है और यह XML के लिए एक अच्छा विकल्प है। JSON जावास्क्रिप्ट से लिया गया है लेकिन एक भाषा-स्वतंत्र डेटा प्रारूप है। JSON की पीढ़ी और पार्सिंग कई आधुनिक प्रोग्रामिंग भाषाओं द्वारा समर्थित है। application/json JSON के लिए उपयोग किया जाने वाला मीडिया प्रकार है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप XLS को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-bmp/" name="एक्सएलएस टू बीएमपी" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-csv/" name="सीएसवी के लिए एक्सएलएस" description="अल्पविराम से अलग किये गए मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-dif/" name="एक्सएलएस टू डीआईएफ" description="डेटा इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-emf/" name="ईएमएफ के लिए एक्सएलएस" description="उन्नत मेटाफ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-gif/" name="एक्सएलएस टू जीआईएफ" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-html/" name="एचटीएमएल के लिए एक्सएलएस" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-jpeg/" name="जेपीईजी के लिए एक्सएलएस" description="जेपीईजी छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-mhtml/" name="एक्सएलएस से एमएचटीएमएल" description="वेब पेज संग्रह प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-ods/" name="एक्सएलएस टू ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-pdf/" name="पीडीएफ के लिए एक्सएलएस" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-png/" name="पीएनजी के लिए एक्सएलएस" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-svg/" name="एक्सएलएस से एसवीजी" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tiff/" name="एक्सएलएस टू टीआईएफएफ" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tsv/" name="XLS से TSV" description="टैब से अलग किए गए मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-txt/" name="XLS से TXT" description="सामग्री या लेख दस्तावेज़" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsb/" name="एक्सएलएस से एक्सएलएसबी" description="बाइनरी एक्सेल वर्कबुक फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsm/" name="एक्सएलएस से एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsx/" name="एक्सएलएस से एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlt/" name="एक्सएलएस से एक्सएलटी" description="माइक्रोसॉफ्ट एक्सेल टेम्पलेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltm/" name="एक्सएलएस से एक्सएलटीएम" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltx/" name="एक्सएलएस से एक्सएलटीएक्स" description="ऑफिस ओपनएक्सएमएल एक्सेल टेम्प्लेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xps/" name="एक्सएलएस से एक्सपीएस" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}