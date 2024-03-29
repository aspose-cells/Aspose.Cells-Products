---
title:  XLT फ़ाइलें via Java मर्ज करें
weight: 9960
description: जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए Java रनटाइम एनवायरमेंट पर XLT दस्तावेजों को संयोजित करने के लिए Java नमूना कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT प्रारूपों को Java में मर्ज करें" h2="सर्वर-साइड Java एपीआई का उपयोग करके मूल XLT दस्तावेज़ विलय।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके XLT फ़ाइलों को कैसे मर्ज करें" %}}

 XLT फ़ाइल को मर्ज करने के लिए, हम उपयोग करेंगे[Aspose.Cells for Java](https://products.aspose.com/cells/java) API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान विलय API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे यहां से डाउनलोड कर सकते हैं[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने Maven-आधारित प्रोजेक्ट में स्थापित करें।

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

{{% blocks/products/pf/agp/feature-section-col title="Java में XLT फ़ाइलों को मर्ज करने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 एक बुनियादी दस्तावेज़ जिसका विलय और संयोजन हो रहा है[Aspose.Cells for Java](https://products.aspose.com/cells/java) एपीआई को कोड की कुछ पंक्तियों के साथ किया जा सकता है।

{{% /blocks/products/pf/agp/text %}}

+ वर्कबुक क्लास के उदाहरण के साथ पहली XLT फ़ाइल लोड करें।
+ वर्कबुक क्लास के उदाहरण के साथ दूसरा XLT दस्तावेज़ लोड करें।
+ कंबाइन() विधि का उपयोग करके फ़ाइलें मर्ज करें।
+ मर्ज की गई XLT फ़ाइल को निर्दिष्ट पथ पर सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java सभी प्रमुख प्लेटफार्मों और ऑपरेटिंग सिस्टम पर समर्थन करता है। कृपया सुनिश्चित करें कि आपके पास निम्नलिखित शर्तें हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या जेएसपी/जेएसएफ एप्लिकेशन और डेस्कटॉप एप्लिकेशन के लिए Java रनटाइम एनवायरमेंट के साथ एक संगत ओएस।
-  Aspose.Cells for Java का नवीनतम संस्करण सीधे प्राप्त करें
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT फ़ाइलें मर्ज करें - Java" offSpacer="" %}}

```cs
// Open the first XLT file.
Workbook xltFile1 = new Workbook("chartsFileWithPath.xlt");

// Define the second source book.
// Open the second XLT file.
Workbook xltFile2 = new Workbook("pictureFileWithPath.xlt");

// Combining the two workbooks
xltFile1.combine(xltFile2);

// Save the target book file.
xltFile1.save("combinedFileWithPath.xlt");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन XLT मर्जर लाइव डेमो" sectionDescription=" अभी हमारे यहां जाकर XLT दस्तावेज़ मर्ज करें[लाइव डेमो वेबसाइट](https://products.aspose.app/cells/merger). लाइव डेमो के निम्नलिखित लाभ हैं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="बस अपनी XLT फ़ाइलें अपलोड करें।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" इसे तुरंत विलय और संयोजित किया जाएगा।" >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.Cells for Java API" %}}

 Aspose.Cells API का उपयोग Microsoft एक्सेल प्रारूपों को विभिन्न प्रारूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या ओपनऑफिस जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
 .XLT एक्सटेंशन वाली फ़ाइलें Microsoft एक्सेल के साथ बनाई गई टेम्पलेट फ़ाइलें हैं जो एक स्प्रेडशीट एप्लिकेशन है जो Microsoft ऑफिस सूट के हिस्से के रूप में आती है। Microsoft Office 97-2003 नई XLT फ़ाइलें बनाने के साथ-साथ इन्हें खोलने का समर्थन करता है। एक्सेल का नवीनतम संस्करण अभी भी इस पुराने प्रारूप टेम्पलेट फ़ाइलों को खोलने में सक्षम है। ऐसी टेम्प्लेट फ़ाइल का उपयोग डिफ़ॉल्ट डेटा और पेज फ़ॉर्मेटिंग, फ़ॉन्ट आकार, मार्जिन, चार्ट आदि जैसी सेटिंग्स के साथ नई एक्सेल फ़ाइलें बनाने के लिए किया जाता है, जिन्हें आगे नई .XLS फ़ाइलों के रूप में सहेजा जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित विलय प्रारूप" subTitle="Java का उपयोग करके, कोई भी कई अन्य फ़ाइल स्वरूपों को मर्ज कर सकता है..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="अल्पविराम से अलग किये गए मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="वेब पेज पुरालेख प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="टैब-पृथक मान" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="सामग्री या लेख दस्तावेज़" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="एक्सेल बाइनरी फॉर्मेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="बाइनरी एक्सेल वर्कबुक फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="स्प्रेडशीट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="ऑफिस ओपनएक्सएमएल एक्सेल टेम्पलेट" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
