---
title:  XLT को C# के माध्यम से बाइट ऐरे में बदलें
weight: 7690
description: C# XLT से बाइट ऐरे रूपांतरण के लिए नमूना कोड। VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन के भीतर Excel XLT से बाइट ऐरे रूपांतरण के लिए इस कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT को C# के माध्यम से बाइट सरणी में बदलें" h2="सर्वर साइड .NET एपीआई का उपयोग करके स्प्रेडशीट डेटा प्रोसेसिंग के लिए मूल और उच्च प्रदर्शन Microsoft एक्सेल XLT बाइट सरणी रूपांतरण या इसके विपरीत।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 बाइट ऐरे डेटा प्रोसेसिंग या भंडारण के लिए सहायक है। आप XLT फ़ाइल को बाइट ऐरे में भी परिवर्तित कर सकते हैं**बाइट ऐरे को XLT पर** C# भाषा का उपयोग कर दस्तावेज़। XLT को बाइट ऐरे में बदलने के लिए, हम उपयोग करेंगे
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API जो .NET प्लेटफॉर्म का उपयोग करके दस्तावेज़ हेरफेर और रूपांतरण के लिए विभिन्न सुविधाएँ प्रदान करता है।
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLT को C# के माध्यम से बाइट ऐरे में कैसे परिवर्तित करें" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ पंक्तियों में आगे के हेरफेर कार्यों के लिए XLT फ़ाइलों को बाइट सरणी में लोड करना और परिवर्तित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  अपनी क्लास फ़ाइल में नेमस्पेस शामिल करें
1.  वर्कबुक का उपयोग करके इनपुट XLT फ़ाइल लोड करें
1.  मेमोरीस्ट्रीम ऑब्जेक्ट को प्रारंभ करें
1.  स्ट्रीम डेटा को बाइट सरणी में बदलें
1.  अपनी आवश्यकता के अनुसार डेटा संसाधित करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

बस सुनिश्चित करें कि सिस्टम में Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म के साथ-साथ Microsoft विज़ुअल स्टूडियो जैसे विकास वातावरण के साथ एक संगत ओएस है।

{{% /blocks/products/pf/agp/text %}}

-  कमांड लाइन से इस रूप में इंस्टॉल करें<code>nuget install Aspose.Cells</code> या विज़ुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से<code>Install-Package Aspose.Cells</code>.
-  वैकल्पिक रूप से, ऑफ़लाइन एमएसआई इंस्टॉलर या ज़िप फ़ाइल में सभी डीएलएल प्राप्त करें<a href="https://downloads.aspose.com/cells/net">डाउनलोड</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड XLT से बाइट सरणी C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xlt");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xlt);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

एक एक्सेल स्प्रेडशीट प्रोग्रामिंग लाइब्रेरी सभी एक्सेल फ़ाइलों को उत्पन्न करने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन बनाने में सक्षम है। .NET एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित होता है, यह XLT को छवियों के रूप में, PDF, HTML, ODS और अधिक सहित एक्सेल फाइलों को भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प बन जाता है।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
.xlt एक्सटेंशन वाली फ़ाइलें Microsoft Excel के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं जो एक स्प्रेडशीट एप्लिकेशन है जो Microsoft Office सुइट के भाग के रूप में आती है। Microsoft Office 97-2003 नई XLT फ़ाइलें बनाने के साथ-साथ इन्हें खोलने का समर्थन करता है। एक्सेल का नवीनतम संस्करण अभी भी इस पुराने प्रारूप टेम्पलेट फ़ाइलों को खोलने में सक्षम है। ऐसी टेम्प्लेट फ़ाइल का उपयोग डिफ़ॉल्ट डेटा और सेटिंग्स जैसे पेज फ़ॉर्मेटिंग, फ़ॉन्ट आकार, मार्जिन, चार्ट इत्यादि के साथ नई एक्सेल फ़ाइलें बनाने के लिए किया जाता है, जिन्हें आगे नई .xls फ़ाइलों के रूप में सहेजा जा सकता है।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप नीचे सूचीबद्ध कुछ सहित अन्य फ़ाइल स्वरूपों को बाइट सरणी में या इसके विपरीत भी परिवर्तित कर सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS बाइट ऐरे के लिए" description="Microsoft एक्सेल स्प्रेडशीट (विरासत)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX बाइट ऐरे के लिए" description="XML वर्कबुक खोलें" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB बाइट ऐरे के लिए" description="एक्सेल बाइनरी वर्कबुक" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM बाइट ऐरे के लिए" description="मैक्रो-सक्षम स्प्रेडशीट" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT बाइट ऐरे के लिए" description="एक्सेल 97 - 2003 टेम्पलेट" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX बाइट ऐरे के लिए" description="एक्सेल टेम्पलेट" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM बाइट ऐरे के लिए" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV बाइट ऐरे के लिए" description="अल्पविराम से अलग किए गए मान" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV बाइट ऐरे के लिए" description="टैब अलग मान" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS बाइट ऐरे के लिए" description="ओपनडॉक्यूमेंट स्प्रेडशीट" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS से PDF तक" description="संवहन दस्तावेज़ स्वरूप" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS से HTML तक" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX से XPS तक" description="Microsoft एक्सेल ओओएक्सएमएल एक्सेल फ़ाइल" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX से HTML तक" description="ओओएक्सएमएल एक्सेल फ़ाइल" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX से SVG तक" description="स्केलेबल वेक्टर ग्राफिक्स" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS से JPEG तक" description="JPEG छवि" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
