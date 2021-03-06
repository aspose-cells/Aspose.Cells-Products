---
title: TABDELIMITED को SVG में C++ एप्लिकेशन के माध्यम से कनवर्ट करें 
url: /hi/cpp/conversion/tabdelimited-to-svg/ 
description: SVG प्रारूप में TABDELIMITED दस्तावेज़ के लिए नमूना C++ रूपांतरण कोड। प्रोग्रामर इस स्रोत कोड का उपयोग किसी भी C++ एप्लिकेशन में TABDELIMITED से SVG रूपांतरण के बैच के लिए कर सकते हैं।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TABDELIMITED को C++ के माध्यम से SVG में बदलें" h2="Microsoft Excel, OpenOffice या Adobe Acrobat स्थापना की आवश्यकता के बिना C++ लाइब्रेरी का उपयोग करके SVG रूपांतरण के लिए उच्च प्रदर्शन TABDELIMITED।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ का उपयोग करके TABDELIMITED को SVG में कैसे बदलें" %}}

 TABDELIMITED को SVG में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="TABDELIMITED को SVG में बदलने के लिए कदम C++ के माध्यम से" %}}

{{% blocks/products/pf/agp/text %}}

 C++ डेवलपर कोड की कुछ ही पंक्तियों में आसानी से TABDELIMITED फ़ाइल को SVG में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. फ़ैक्टरी :: CreateIWorkbook का उपयोग करके TABDELIMITED फ़ाइल लोड करें।1. पहली वर्कशीट का चयन करें।1. सेट (एसवीजी) विकल्प।1. शीट के प्रत्येक पृष्ठ के माध्यम से पुनरावृति करें और प्रस्तुत करें।1. संगत प्रोग्राम में SVG फ़ाइल खोलें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 C++ रूपांतरण नमूना कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
- Microsoft Windows या C++Windows 32 बिट, Windows 64 बिट और Linux 64 बिट के लिए रनटाइम वातावरण के साथ संगत OS।- आपके प्रोजेक्ट में संदर्भित C++ DLL के लिए Aspose.Cells।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SVG से TABDELIMITED C++ रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// आउटपुट निर्देशिका पथ।
StringPtr outDir = new String("OutputDirectoryPath");

// TABDELIMITED लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.tabdelimited");

// पहले वर्कशीट तक पहुँचें।
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// छवि या प्रिंट विकल्प ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// छवि प्रारूप निर्दिष्ट करें।
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetSvg());

// क्षैतिज और लंबवत संकल्प निर्दिष्ट करें
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// निर्दिष्ट छवि या प्रिंट विकल्पों के संबंध में शीट को प्रस्तुत करें।
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// पृष्ठ संख्या प्राप्त करें।
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// स्ट्रिंग कॉन्सटेनेशन के लिए स्ट्रिंग बिल्डर ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// प्रत्येक पृष्ठ को एक-एक करके छवि को svg में प्रस्तुत करें।
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageSVG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".svg"));

	// आउटपुट छवि पथ प्राप्त करें।
	StringPtr outputSVG = sb->ToString();

	// वर्कशीट को svg इमेज में बदलें।
	sr->ToImage(i, outputSVG);
}


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

    {{% blocks/products/pf/agp/content h2="C++ एक्सेल फ़ाइल मैनिपुलेशन लाइब्रेरी" %}}

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