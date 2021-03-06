---
title: XLSM को C++ एप्लिकेशन के माध्यम से HTML में बदलें 
url: /hi/cpp/conversion/xlsm-to-html/ 
description: XLSM दस्तावेज़ के लिए HTML प्रारूप में नमूना C++ रूपांतरण कोड। प्रोग्रामर इस स्रोत कोड का उपयोग किसी भी C++ एप्लिकेशन में बैच XLSM से HTML रूपांतरण के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSM को C++ के माध्यम से HTML में बदलें" h2="Microsoft Excel, OpenOffice या Adobe Acrobat स्थापना की आवश्यकता के बिना C++ लाइब्रेरी का उपयोग करके उच्च प्रदर्शन XLSM से HTML रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके XLSM को HTML में कैसे बदलें" %}}

 XLSM को HTML में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="XLSM को C++ के माध्यम से HTML में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 C++ डेवलपर कोड की कुछ ही पंक्तियों में आसानी से XLSM फ़ाइल को HTML में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. फ़ैक्टरी :: CreateIWorkbook का उपयोग करके XLSM फ़ाइल लोड करें।1. सहेजें () विधि को कॉल करें।1. आउटपुट फ़ाइल पथ को (HTML) फ़ाइल एक्सटेंशन के साथ पास करें।1. HTML फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी।1. संगत प्रोग्राम में HTML फ़ाइल खोलें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 C++ रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM से HTML C++ रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// एक्सएलएसएम लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");

// HTML फॉर्मेट में सेव करें।
wkb->Save(u"convertedFile.html", SaveFormat_Html);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSM से HTML रूपांतरण लाइव डेमो" sectionDescription="[XLSM को HTML में बदलें](https://products.aspose.app/cells/conversion/xlsm-to-html) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी XLSM फ़ाइल अपलोड करें, यह तुरंत HTML में कनवर्ट हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="C++ एक्सेल फ़ाइल मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

XLSM एक्सटेंशन वाली फ़ाइलें एक प्रकार की स्प्रैडशीट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। एप्लिकेशन के दृष्टिकोण से, मैक्रो निर्देशों का सेट है जो प्रक्रियाओं को स्वचालित करने के लिए उपयोग किया जाता है। मैक्रो का उपयोग उन चरणों को रिकॉर्ड करने के लिए किया जाता है जो बार-बार किए जाते हैं और मैक्रो को फिर से चलाकर क्रियाओं को करने में सुविधा प्रदान करते हैं। मैक्रो को माइक्रोसॉफ्ट के विजुअल बेसिक फॉर एप्लिकेशन (वीबीए) के साथ एक्सेल वर्कबुक के भीतर विजुअल बेसिक एडिटर का उपयोग करके प्रोग्राम किया जाता है और इसे सीधे वहां से चलाया/डीबग किया जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (हाइपर टेक्स्ट मार्कअप लैंग्वेज) ब्राउज़र में प्रदर्शन के लिए बनाए गए वेब पेजों का एक्सटेंशन है। वेब की भाषा के रूप में जाना जाता है, एचटीएमएल वेब पेजों के हिस्से के रूप में प्रदर्शित होने वाली नई सूचना आवश्यकताओं की आवश्यकताओं के साथ विकसित हुआ है। नवीनतम संस्करण को HTML 5 के रूप में जाना जाता है जो भाषा के साथ काम करने के लिए बहुत अधिक लचीलापन देता है। HTML पृष्ठ या तो सर्वर से प्राप्त होते हैं, जहां इन्हें होस्ट किया जाता है, या स्थानीय सिस्टम से भी लोड किया जा सकता है। प्रत्येक HTML पृष्ठ HTML तत्वों से बना होता है जैसे कि फॉर्म, टेक्स्ट, इमेज, एनिमेशन, लिंक आदि। इन तत्वों को टैग द्वारा दर्शाया जाता है जैसे कि img, a, p और कई अन्य जहां प्रत्येक टैग का प्रारंभ और अंत होता है। यह समग्र लेआउट प्रतिनिधित्व के लिए स्क्रिप्टिंग भाषाओं जैसे जावास्क्रिप्ट और स्टाइल शीट्स (सीएसएस) में लिखे गए अनुप्रयोगों को भी एम्बेड कर सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}