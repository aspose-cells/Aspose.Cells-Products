---
title: SXC को JSON में C++ एप्लिकेशन के माध्यम से कनवर्ट करें 
url: /hi/cpp/conversion/sxc-to-json/ 
description: नमूना C++ एसएक्ससी दस्तावेज़ के लिए जेएसओएन प्रारूप में रूपांतरण कोड। प्रोग्रामर इस स्रोत कोड का उपयोग किसी भी C++ एप्लिकेशन के भीतर बैच SXC से JSON रूपांतरण के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="SXC को JSON में C++ के माध्यम से कनवर्ट करें" h2="Microsoft Excel, OpenOffice या Adobe Acrobat स्थापना की आवश्यकता के बिना C++ लाइब्रेरी का उपयोग करके उच्च प्रदर्शन SXC से JSON रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SXC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके SXC को JSON में कैसे बदलें" %}}

 SXC को JSON में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="SXC को JSON में बदलने के लिए कदम C++ के माध्यम से" %}}

{{% blocks/products/pf/agp/text %}}

 C++ डेवलपर कोड की कुछ ही पंक्तियों में आसानी से SXC फ़ाइल को JSON में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. फ़ैक्टरी :: CreateIWorkbook का उपयोग करके SXC फ़ाइल लोड करें।1. सहेजें () विधि को कॉल करें।1. आउटपुट फ़ाइल पथ को (JSON) फ़ाइल एक्सटेंशन के साथ पास करें।1. JSON फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी।1. संगत प्रोग्राम में JSON फ़ाइल खोलें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 C++ रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SXC से JSON C++ रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// एसएक्ससी लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");

// JSON प्रारूप में सहेजें।
wkb->Save(u"convertedFile.json", SaveFormat_Json);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="SXC से JSON रूपांतरण लाइव डेमो" sectionDescription="[SXC को JSON में बदलें](https://products.aspose.app/cells/conversion/sxc-to-json) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी SXC फ़ाइल अपलोड करें, यह तुरंत JSON में बदल जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="C++ एक्सेल फ़ाइल मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SXC" readMoreLink="https://docs.fileformat.com/spreadsheet/sxc/" >}}

फ़ाइल स्वरूप SXC (Sun XML Calc) OpenOffice.org नामक कार्यालय सुइट से संबंधित है। यह प्रारूप आम तौर पर उपयोगकर्ताओं की स्प्रेडशीट आवश्यकताओं से संबंधित है क्योंकि यह एक एक्सएमएल आधारित स्प्रेडशीट फ़ाइल प्रारूप है। SXC प्रारूप डेटापायलट के साथ फ़ार्मुलों, फ़ंक्शंस, मैक्रोज़ और चार्ट्स का समर्थन करता है, जो एक अविश्वसनीय विशेषता है क्योंकि यह स्वचालित रूप से कच्चे आयातित डेटा के सारांश को व्यक्तिगत और प्रदान करता है। इस सॉफ़्टवेयर से बनाई गई फ़ाइलें एक्सटेंशन .sxc के साथ सहेजी जाती हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (जावास्क्रिप्ट ऑब्जेक्ट नोटेशन) डेटा साझा करने के लिए एक खुला मानक फ़ाइल स्वरूप है जो डेटा को संग्रहीत और संचारित करने के लिए मानव-पठनीय पाठ का उपयोग करता है। JSON फ़ाइलें .json एक्सटेंशन के साथ संग्रहीत की जाती हैं। JSON को कम स्वरूपण की आवश्यकता होती है और यह XML के लिए एक अच्छा विकल्प है। JSON जावास्क्रिप्ट से लिया गया है लेकिन एक भाषा-स्वतंत्र डेटा प्रारूप है। JSON की पीढ़ी और पार्सिंग कई आधुनिक प्रोग्रामिंग भाषाओं द्वारा समर्थित है। application/json JSON के लिए उपयोग किया जाने वाला मीडिया प्रकार है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}