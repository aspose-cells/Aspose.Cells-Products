---
title:  XLS फ़ाइलें via Java में रिपोर्ट जनरेट करें
weight: 1090
description: जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए Java रनटाइम एनवायरमेंट पर XLS प्रारूप रिपोर्ट बनाने के लिए Java नमूना कोड।
keywords: [Java Aspose.Cells., Java Create XLS Reports Based on Predesigned Excel Template., Java Generate XLS Reports Based on Predesigned Excel Template., Java Create XLS Reports Based on Excel Template., Java Generate XLS Reports Based on Excel Template., Java Create XLS files Based on Excel Template., Java Generate XLS files Based on Excel Template]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS प्रारूप via Java में थोक रिपोर्ट जनरेशन" h2="डेटा स्रोत और टेम्पलेट का उपयोग करके XLS प्रारूप में रिपोर्ट तैयार करें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLS रिपोर्ट कैसे तैयार करें" %}}

 XLS फ़ाइल रिपोर्ट बनाने के लिए, हम इसका उपयोग करेंगे
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान असेंबली API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे यहां से डाउनलोड कर सकते हैं
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने Maven-आधारित प्रोजेक्ट में स्थापित करें।

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

{{% blocks/products/pf/agp/feature-section-col title="XLS रिपोर्ट जनरेट करने के चरण via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  वर्कबुकडिज़ाइनर क्लास को त्वरित करें
1. ArrayList में डेटासौस ऑब्जेक्ट जोड़ें
1.  वर्कबुकडिज़ाइनर ऑब्जेक्ट के लिए डेटा स्रोत और प्रक्रिया सेट करें
1.  Worbook.save विधि के माध्यम से परिणाम को XLS प्रारूप में सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java सभी प्रमुख प्लेटफार्मों और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित शर्तें हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए Java रनटाइम एनवायरमेंट के साथ एक संगत ओएस।
- Aspose.Cells for Java का नवीनतम संस्करण सीधे Maven से प्राप्त करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS प्रारूप में एक्सेल रिपोर्ट तैयार करें - Java" offSpacer="" %}}

```java
//Create a workbook designer
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Create Persons objects with photos
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Set the data source and process smart marker tags
designer.setDataSource("Person", persons);
designer.process();

//Save the workbook
workbook.save(dataDir + "output.xls", SaveFormat.XLS);
	
System.out.println("File saved");
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for Java API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="असेंबल करने के लिए निःशुल्क ऐप XLS" sectionDescription=" हमारे लाइव डेमो देखें[XLS फ़ाइलें बनाएँ](https://products.aspose.app/cells/assembly/xls) निम्नलिखित लाभों के साथ." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की कोई आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस XLS फ़ाइल अपलोड करें और \"असेंबल\" बटन दबाएँ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" लिंक से परिणामी XLS फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS एक्सटेंशन वाली फ़ाइलें एक्सेल बाइनरी फ़ाइल स्वरूप का प्रतिनिधित्व करती हैं। ऐसी फ़ाइलें Microsoft एक्सेल के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे ओपनऑफिस कैल्क या ऐप्पल Numbers द्वारा बनाई जा सकती हैं। एक्सेल द्वारा सहेजी गई फ़ाइल को वर्कबुक के रूप में जाना जाता है जहां प्रत्येक वर्कबुक में एक या अधिक वर्कशीट हो सकती हैं। डेटा को वर्कशीट में तालिका प्रारूप में उपयोगकर्ताओं के लिए संग्रहीत और प्रदर्शित किया जाता है और इसमें संख्यात्मक मान, पाठ डेटा, सूत्र, बाहरी डेटा कनेक्शन, चित्र और चार्ट शामिल हो सकते हैं। Microsoft एक्सेल जैसे एप्लिकेशन आपको वर्कबुक डेटा को PDF, CSV, XLSX, TXT, HTML, XPS, और कई अन्य सहित कई अलग-अलग प्रारूपों में निर्यात करने की सुविधा देते हैं। Microsoft Excel 2007 के रिलीज़ के साथ, XLS फ़ाइल स्वरूप को अधिक खुले और संरचित प्रारूप, XLSX से बदल दिया गया था। नवीनतम संस्करण अभी भी XLS फ़ाइलें बनाने और पढ़ने के लिए समर्थन प्रदान करते हैं, हालाँकि XLSX अब उपयोग की पहली पसंद है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रिपोर्ट जनरेशन प्रारूप" subTitle="Java का उपयोग करके, कोई भी आसानी से कई प्रारूपों की रिपोर्ट तैयार कर सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
