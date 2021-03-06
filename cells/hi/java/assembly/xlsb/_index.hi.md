---
title: Java के माध्यम से XLSB फ़ाइलों में रिपोर्ट जेनरेट करें 
weight: 3560
url: /hi/java/assembly/xlsb/ 
description: Java जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए Java रनटाइम एनवायरनमेंट पर एक्सएलएसबी प्रारूप रिपोर्ट बनाने के लिए नमूना कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSB प्रारूप में Java के माध्यम से बल्क रिपोर्ट जनरेशन" h2="डेटा स्रोत और टेम्प्लेट का उपयोग करके XLSB प्रारूप में रिपोर्ट जेनरेट करें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLSB रिपोर्ट कैसे जेनरेट करें" %}}

 XLSB फ़ाइल रिपोर्ट बनाने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान असेंबली API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से XLSB रिपोर्ट जेनरेट करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. तत्काल कार्यपुस्तिकाडिज़ाइनर वर्ग1. एक ArrayList में डेटासॉस ऑब्जेक्ट जोड़ें1. कार्यपुस्तिका डिज़ाइनर ऑब्जेक्ट के लिए डेटा स्रोत और प्रक्रिया सेट करें1. Worbook.save विधि के माध्यम से परिणाम को XLSB फॉर्मेट में सेव करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- मावेन से सीधे Aspose.Cells for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="एक्सएलएसबी प्रारूप में एक्सेल रिपोर्ट जेनरेट करें - C#" offSpacer="" %}}

```cs
//एक कार्यपुस्तिका डिज़ाइनर बनाएँ
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//फ़ोटो के साथ व्यक्ति ऑब्जेक्ट बनाएं
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//डेटा स्रोत सेट करें और स्मार्ट मार्कर टैग संसाधित करें
designer.setDataSource("Person", persons);
designer.process();

//कार्यपुस्तिका सहेजें
workbook.save(dataDir + "output.xlsb", SaveFormat.XLSB);
	
System.out.println("File saved");
    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for Java API" %}}

 Aspose.Cells API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="एक्सएलएसबी इकट्ठा करने के लिए नि: शुल्क ऐप" sectionDescription="हमारे लाइव डेमो की जांच करें [एक्सएलएसबी फाइलें बनाएं](https://products.aspose.app/cells/assembly/xlsb) निम्नलिखित लाभों के साथ।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस XLSB फ़ाइल अपलोड करें और \"इकट्ठा करें\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" लिंक से परिणामी XLSB फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB फ़ाइल स्वरूप Excel बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो Excel कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। सामग्री में संख्याओं की असंरचित या अर्ध-संरचित तालिकाएँ, पाठ, या दोनों संख्याएँ और पाठ, सूत्र, बाहरी डेटा कनेक्शन, चार्ट और चित्र शामिल हो सकते हैं। एक्सएलएसएक्स (जो ओपन एक्सएमएल फाइल फॉर्मेट पर आधारित है) के विपरीत, एक्सएलएसबी बाइनरी एक्सेल वर्कबुक फाइल का प्रतिनिधित्व करता है। XLSB फाइलें तेजी से पढ़ी और लिखी जा सकती हैं जो उन्हें बड़ी फाइलों के साथ काम करने के लिए उपयोगी बनाती हैं। XLSB का उपयोग शायद ही कभी कार्यपुस्तिकाओं को संग्रहीत करने के लिए किया जाता है क्योंकि XLSX (और पहले XLS) कार्यपुस्तिकाओं को सहेजने के लिए सबसे आम उपयोगकर्ता चयनित फ़ाइल स्वरूप हैं। इसे माइक्रोसॉफ्ट ऑफिस 2007 और इसके बाद के संस्करण द्वारा खोला जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रिपोर्ट जनरेशन प्रारूप" subTitle="Java का उपयोग करके, कोई भी व्यक्ति आसानी से सहित कई प्रारूपों की रिपोर्ट तैयार कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xls/" name="एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}