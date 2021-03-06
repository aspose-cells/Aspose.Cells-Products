---
title: C++ एप्लिकेशन के माध्यम से JSON को JPEG में बदलें 
url: /hi/cpp/conversion/json-to-jpeg/ 
description: नमूना C++ JSON दस्तावेज़ के लिए JPEG प्रारूप में रूपांतरण कोड। प्रोग्रामर इस स्रोत कोड का उपयोग किसी भी C++ एप्लिकेशन में JSON से JPEG रूपांतरण के बैच के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="JSON को JPEG में C++ के माध्यम से बदलें" h2="Microsoft Excel, OpenOffice या Adobe Acrobat स्थापना की आवश्यकता के बिना C++ लाइब्रेरी का उपयोग करके उच्च निष्पादन JSON से JPEG रूपांतरण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके JSON को JPEG में कैसे बदलें" %}}

 JSON को JPEG में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="C++ के माध्यम से JSON को JPEG में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 C++ डेवलपर कोड की कुछ ही पंक्तियों में आसानी से JSON फ़ाइल को JPEG में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. फ़ैक्टरी :: CreateIWorkbook का उपयोग करके JSON फ़ाइल लोड करें।1. पहली वर्कशीट का चयन करें।1. सेट (जेपीईजी) विकल्प।1. शीट के प्रत्येक पृष्ठ के माध्यम से पुनरावृति करें और प्रस्तुत करें।1. संगत प्रोग्राम में JPEG फ़ाइल खोलें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 C++ रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JSON से JPEG C++ रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// आउटपुट निर्देशिका पथ।
StringPtr outDir = new String("OutputDirectoryPath");

// JSON लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.json");

// पहले वर्कशीट तक पहुँचें।
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// छवि या प्रिंट विकल्प ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// छवि प्रारूप निर्दिष्ट करें।
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// क्षैतिज और लंबवत संकल्प निर्दिष्ट करें
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// निर्दिष्ट छवि या प्रिंट विकल्पों के संबंध में शीट को प्रस्तुत करें।
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// पृष्ठ संख्या प्राप्त करें।
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// स्ट्रिंग कॉन्सटेनेशन के लिए स्ट्रिंग बिल्डर ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// प्रत्येक पृष्ठ को जेपीईजी छवि में एक-एक करके प्रस्तुत करें।
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));

	// आउटपुट छवि पथ प्राप्त करें।
	StringPtr outputJPEG = sb->ToString();

	// वर्कशीट को जेपीईजी इमेज में बदलें।
	sr->ToImage(i, outputJPEG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="JSON से JPEG रूपांतरण लाइव डेमो" sectionDescription="[JSON को JPEG में बदलें](https://products.aspose.app/cells/conversion/json-to-jpeg) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी JSON फ़ाइल अपलोड करें, यह तुरंत JPEG में बदल जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="C++ एक्सेल फ़ाइल मैनिपुलेशन लाइब्रेरी" %}}

 Excel API का उपयोग Microsoft Excel स्वरूपों को विभिन्न स्वरूपों में बनाने, संपादित करने, परिवर्तित करने और प्रस्तुत करने के लिए किया जा सकता है। इसके अलावा, इसका उपयोग सॉफ्टवेयर अनुप्रयोगों के भीतर व्यापक चार्टिंग, स्केलेबल रिपोर्टिंग और विश्वसनीय गणना के लिए किया जा सकता है। Aspose.Cells एक स्टैंडअलोन API है और इसके लिए Microsoft या OpenOffice जैसे किसी सॉफ़्टवेयर की आवश्यकता नहीं है।  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (जावास्क्रिप्ट ऑब्जेक्ट नोटेशन) डेटा साझा करने के लिए एक खुला मानक फ़ाइल स्वरूप है जो डेटा को संग्रहीत और संचारित करने के लिए मानव-पठनीय पाठ का उपयोग करता है। JSON फ़ाइलें .json एक्सटेंशन के साथ संग्रहीत की जाती हैं। JSON को कम स्वरूपण की आवश्यकता होती है और यह XML के लिए एक अच्छा विकल्प है। JSON जावास्क्रिप्ट से लिया गया है लेकिन एक भाषा-स्वतंत्र डेटा प्रारूप है। JSON की पीढ़ी और पार्सिंग कई आधुनिक प्रोग्रामिंग भाषाओं द्वारा समर्थित है। application/json JSON के लिए उपयोग किया जाने वाला मीडिया प्रकार है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG एक प्रकार का छवि प्रारूप है जिसे हानिपूर्ण संपीड़न की विधि का उपयोग करके सहेजा जाता है। संपीड़न के परिणामस्वरूप आउटपुट छवि, भंडारण आकार और छवि गुणवत्ता के बीच एक व्यापार-बंद है। उपयोगकर्ता वांछित गुणवत्ता स्तर प्राप्त करने के लिए संपीड़न स्तर को समायोजित कर सकते हैं जबकि साथ ही भंडारण आकार को कम कर सकते हैं। यदि छवि पर 10:1 संपीड़न लागू किया जाता है, तो छवि गुणवत्ता नगण्य रूप से प्रभावित होती है। संपीड़न मूल्य जितना अधिक होगा, छवि गुणवत्ता में गिरावट उतनी ही अधिक होगी। जेपीईजी छवि फ़ाइल प्रारूप को संयुक्त फोटोग्राफिक विशेषज्ञ समूह द्वारा मानकीकृत किया गया था और इसलिए, जेपीईजी नाम। प्रारूप वेब पर फोटोग्राफिक छवियों को संग्रहीत और प्रसारित करने का विकल्प रहा है। लगभग सभी ऑपरेटिंग सिस्टम में अब ऐसे दर्शक हैं जो JPEG छवियों के विज़ुअलाइज़ेशन का समर्थन करते हैं, जिन्हें अक्सर JPG एक्सटेंशन के साथ भी संग्रहीत किया जाता है। यहां तक कि वेब ब्राउज़र भी JPEG इमेज के विज़ुअलाइज़ेशन का समर्थन करते हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}