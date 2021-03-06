---
title: C++ एप्लिकेशन के माध्यम से CSV को XLAM में बदलें 
url: /hi/cpp/conversion/csv-to-xlam/ 
description: सीएसवी दस्तावेज़ के लिए नमूना C++ रूपांतरण कोड XLAM प्रारूप में। प्रोग्रामर इस स्रोत कोड का उपयोग किसी भी C++ एप्लिकेशन में CSV से XLAM रूपांतरण के बैच के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ के माध्यम से CSV को XLAM में बदलें" h2="Microsoft Excel, OpenOffice या Adobe Acrobat स्थापना की आवश्यकता के बिना C++ लाइब्रेरी का उपयोग करके उच्च प्रदर्शन CSV से XLAM रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLAM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके CSV को XLAM में कैसे बदलें" %}}

 CSV को XLAM में बदलने के लिए, हम उपयोग करेंगे
 [Aspose.Cells के लिए C++](https://products.aspose.com/cells/cpp) 
 API जो C++ प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और रूपांतरण API है। आप इसका नवीनतम संस्करण सीधे डाउनलोड कर सकते हैं, बस खोलें
 [नुगेट](https://www.nuget.org/packages/aspose.cells) 
 पैकेज मैनेजर, खोजें
 Aspose.Cells.सीपीपी 
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="आज्ञा" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ के माध्यम से CSV को XLAM में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 C++ डेवलपर CSV फ़ाइल को कोड की कुछ ही पंक्तियों में आसानी से XLAM में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. फ़ैक्टरी :: CreateIWorkbook का उपयोग करके CSV फ़ाइल लोड करें।1. सहेजें () विधि को कॉल करें।1. आउटपुट फ़ाइल पथ को (XLAM) फ़ाइल एक्सटेंशन के साथ पास करें।1. XLAM फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी।1. संगत प्रोग्राम में XLAM फ़ाइल खोलें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 C++ रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV से XLAM C++ रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// सीएसवी लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");

// XLAM फॉर्मेट में सेव करें।
wkb->Save(u"convertedFile.xlam", SaveFormat_Xlam);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="CSV से XLAM रूपांतरण लाइव डेमो" sectionDescription="[CSV को XLAM में बदलें](https://products.aspose.app/cells/conversion/csv-to-xlam) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी CSV फ़ाइल अपलोड करें, यह तुरंत XLAM में बदल जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="C++ एक्सेल फ़ाइल मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

CSV (कॉमा सेपरेटेड वैल्यू) एक्सटेंशन वाली फाइलें सादा टेक्स्ट फाइलों का प्रतिनिधित्व करती हैं जिनमें कॉमा सेपरेटेड वैल्यू वाले डेटा के रिकॉर्ड होते हैं। CSV फ़ाइल की प्रत्येक पंक्ति फ़ाइल में निहित रिकॉर्ड्स के सेट से एक नया रिकॉर्ड है। ऐसी फाइलें तब उत्पन्न होती हैं जब डेटा ट्रांसफर एक स्टोरेज सिस्टम से दूसरे स्टोरेज सिस्टम में करना होता है। चूंकि सभी एप्लिकेशन कॉमा द्वारा अलग किए गए रिकॉर्ड को पहचान सकते हैं, इसलिए डेटाबेस में ऐसी डेटा फ़ाइलों का आयात बहुत आसानी से किया जाता है। लगभग सभी स्प्रेडशीट एप्लिकेशन जैसे कि माइक्रोसॉफ्ट एक्सेल या ओपनऑफिस कैल्क बिना अधिक प्रयास के सीएसवी आयात कर सकते हैं। ऐसी फ़ाइलों से आयात किए गए डेटा को उपयोगकर्ता के प्रतिनिधित्व के लिए स्प्रेडशीट के सेल में व्यवस्थित किया जाता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLAM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlam/" >}}

XLAM एक एक्सेल मैक्रो-सक्षम ऐड-इन फ़ाइल है जिसका उपयोग एक्सेल में नए कार्यों को जोड़ने के लिए किया जाता है। ऐड-इन एक पूरक प्रोग्राम है जो अतिरिक्त कोड चलाता है और एक्सेल स्प्रेडशीट के लिए अतिरिक्त कार्यक्षमता प्रदान करता है। XLAM फाइलें .xlam एक्सटेंशन के साथ स्टोर की जाती हैं। एक्सएलएएम फाइलें एक्सएलएसएम और एक्सएलएसएक्स फ़ाइल स्वरूपों के समान एक्सएमएल-आधारित फाइलें हैं और समग्र फ़ाइल आकार को कम करने के लिए ज़िप संपीड़न के साथ सहेजी जाती हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप सीएसवी को नीचे सूचीबद्ध कुछ सहित कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="सीएसवी टू बीएमपी" description="बिटमैप चित्र" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="सीएसवी टू डीआईएफ" description="डेटा इंटरचेंज प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="सीएसवी से ईएमएफ" description="उन्नत मेटाफ़ाइल स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="सीएसवी टू जीआईएफ" description="ग्राफिकल इंटरचेंज प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="सीएसवी से एचटीएमएल" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-jpeg/" name="सीएसवी टू जेपीईजी" description="जेपीईजी छवि" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="सीएसवी से एमएचटीएम" description="वेब पेज संग्रह प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="सीएसवी टू ओडीएस" description="OpenDocument स्प्रेडशीट फ़ाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-pdf/" name="पीडीएफ के लिए सीएसवी" description="वहनीय दस्तावेज़ स्वरूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="पीएनजी के लिए सीएसवी" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="सीएसवी से एसवीजी" description="स्केलेबल वेक्टर ग्राफिक्स" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="झगड़ा करने के लिए सीएसवी" description="टैग की गई छवि प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="सीएसवी से टीएसवी" description="टैब से अलग किए गए मान" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="सीएसवी से एक्सएलएस" description="एक्सेल बाइनरी प्रारूप" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsb/" name="सीएसवी से एक्सएलएसबी" description="बाइनरी एक्सेल वर्कबुक फाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="सीएसवी से एक्सएलएसएम" description="स्प्रेडशीट फ़ाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="सीएसवी टू एक्सएलएसएक्स" description="ओओएक्सएमएल एक्सेल फाइल" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="सीएसवी से एक्सएलटीएम" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="सीएसवी टू एक्सएलटीएक्स" description="ऑफिस ओपनएक्सएमएल एक्सेल टेम्प्लेट" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="सीएसवी टू एक्सपीएस" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}