---
title: XLSB दस्तावेज़ से Java के माध्यम से टेक्स्ट और चित्र निकालें 
weight: 440
url: /hi/java/parser/xlsb/ 
description: Java JSP/JSF एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए रनटाइम एनवायरनमेंट पर XLSB फ़ाइल से टेक्स्ट और छवियों को निकालने के लिए Java नमूना कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSB स्वरूपों को Java में पार्स करें" h2="Microsoft या Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना सर्वर-साइड Aspose.Cells for Java API का उपयोग करके मूल और उच्च प्रदर्शन XLSB दस्तावेज़ पार्स करना।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLSB फ़ाइल को कैसे पार्स करें" %}}

 XLSB फ़ाइल को पार्स करने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान पार्सिंग API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
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

{{% blocks/products/pf/agp/feature-section-col title="XLSB फ़ाइलों को Java में पार्स करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 के साथ पार्सिंग एक मूल दस्तावेज़
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 एपीआई कोड की कुछ ही पंक्तियों के साथ किया जा सकता है। Microsoft Excel XLS, XLSX, XLSM, XLSB और OpenDocument ODS फ़ाइलों से पाठ और छवियों को पार्स करें।

{{% /blocks/products/pf/agp/text %}}

+ कार्यपुस्तिका वर्ग का उपयोग करके XLSB दस्तावेज़ लोड करें।
+ getWorksheets().get विधि का उपयोग करके आवश्यक शीट का चयन करें।
+ GetCells () का उपयोग करके चयनित शीट के सभी सेल प्राप्त करें।
+ प्रत्येक सेल पर पुनरावृति करें, उसका पाठ प्राप्त करें।
+ प्रत्येक सेल मान को प्रिंट करें या संपूर्ण रूप से देखने के लिए StringBuilder एपेंड () विधि का उपयोग करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JavaJSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश के साथ संगत OS।- Aspose.Cells for Java का नवीनतम संस्करण सीधे . से प्राप्त करें [मावेना](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="पार्स एक्सएलएसबी फ़ाइलें - Java" offSpacer="" %}}

```cs
StringBuilder stringBuilder = new StringBuilder();
Workbook book = new Workbook(dir + "book1.xlsb");
Worksheet sheet = book.getWorksheets().get(0);
Cells cells = sheet.getCells();
Iterator iterator = cells.iterator();
while(iterator.hasNext())
{
Cell cell = (Cell)iterator.next();
stringBuilder.append(cell.getStringValue());
stringBuilder.append(" ");
}
System.out.println(stringBuilder.toString());  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for Java API" %}}

 Aspose.Cells API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन एक्सएलएसबी पार्सर लाइव डेमो" sectionDescription="हमारे . पर जाकर अभी XLSB दस्तावेज़ों से टेक्स्ट और चित्र निकालें [लाइव डेमो वेबसाइट](https://products.aspose.app/cells/parser). लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी एक्सएलएसबी फाइलें अपलोड करें।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" इसे तुरंत पार्स किया जाएगा।" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB फ़ाइल स्वरूप Excel बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो Excel कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। सामग्री में संख्याओं की असंरचित या अर्ध-संरचित तालिकाएँ, पाठ, या दोनों संख्याएँ और पाठ, सूत्र, बाहरी डेटा कनेक्शन, चार्ट और चित्र शामिल हो सकते हैं। एक्सएलएसएक्स (जो ओपन एक्सएमएल फाइल फॉर्मेट पर आधारित है) के विपरीत, एक्सएलएसबी बाइनरी एक्सेल वर्कबुक फाइल का प्रतिनिधित्व करता है। XLSB फाइलें तेजी से पढ़ी और लिखी जा सकती हैं जो उन्हें बड़ी फाइलों के साथ काम करने के लिए उपयोगी बनाती हैं। XLSB का उपयोग शायद ही कभी कार्यपुस्तिकाओं को संग्रहीत करने के लिए किया जाता है क्योंकि XLSX (और पहले XLS) कार्यपुस्तिकाओं को सहेजने के लिए सबसे आम उपयोगकर्ता चयनित फ़ाइल स्वरूप हैं। इसे माइक्रोसॉफ्ट ऑफिस 2007 और इसके बाद के संस्करण द्वारा खोला जा सकता है। 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित पार्सिंग दस्तावेज़" subTitle="Java का उपयोग करके, कोई भी अन्य प्रारूपों को आसानी से पार्स कर सकता है, जिनमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/ods/" name="ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xls/" name="एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsm/" name="एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}