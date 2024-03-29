---
title: नंबर बनाएं - C# में नंबर फ़ाइल बनाएं
description:  Aspose एक्सेल। C# Aspose.Cells के साथ जल्दी और आसानी से NUMBERS फ़ाइल बनाएँ। C# का उपयोग करके NUMBERS फ़ाइल बनाएँ। C# में NUMBERS बनाएँ। C# NUMBERS क्रिएटर।
keywords: [Aspose Excel., C# Aspose.Cells., C# Create NUMBERS file., Generate NUMBERS file in C#., Create NUMBERS file using C#., Write data to NUMBERS file via C#., Create a NUMBERS file in C#., C# Generate a NUMBERS file., C# NUMBERS Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# में NUMBERS फ़ाइल बनाएँ" h2="नंबर बनाने के लिए हाई-स्पीड C# लाइब्रेरी। यह XLSX, PDF और कई अन्य प्रारूपों को .NET फ्रेमवर्क, .NET कोर या Mono प्लेटफॉर्म पर आयात और निर्यात करने के लिए एक पेशेवर सॉफ्टवेयर समाधान है।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="NUMBERS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके नंबर फ़ाइल बनाएं" %}}
 NUMBERS फ़ाइल कैसे बनाएं? Aspose.Cells for .NET लाइब्रेरी के साथ, आप कोड की कुछ पंक्तियों के साथ प्रोग्रामेटिक रूप से आसानी से NUMBERS फ़ाइल बना सकते हैं।[Aspose.Cells for .NET](https://products.aspose.com/cells/net)सभी एक्सेल फ़ाइलों को उत्पन्न करने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन बनाने में सक्षम है। .NET एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित होता है, बल्कि यह एक्सेल फाइलों को छवियों, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प बन जाता है। खुला[NuGet](https://www.nuget.org/packages/aspose.cells) पैकेज मैनेजर, Aspose.Cells खोजें और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="C# में नंबर कैसे बनाएं" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ पंक्तियों में डेटा प्रोसेसिंग के लिए विभिन्न रिपोर्टिंग एप्लिकेशन चलाने के भीतर NUMBERS फ़ाइलों को बनाना, लोड करना, संशोधित करना और परिवर्तित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  अपनी क्लास फ़ाइल में नेमस्पेस शामिल करें
1.  वर्कबुक क्लास इंस्टेंस बनाएं।
1.  कार्यपुस्तिका की पहली वर्कशीट तक पहुँचें।
1.  वर्कशीट के वांछित सेल प्राप्त करें और सेल में मान इनपुट करें।
1.  कार्यपुस्तिका को NUMBERS फ़ाइल के रूप में सहेजने के लिए सेव विधि का उपयोग करें।

{{% blocks/products/pf/agp/code-block title="नमूना कोड दिखाता है कि C# में NUMBERS फ़ाइल कैसे बनाएं।" offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .numbers file.
wkb.Save("created_one.numbers");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="NUMBERS फ़ाइल बनाने के लिए C# लाइब्रेरी" %}}

{{% blocks/products/pf/agp/text %}}

आपके सिस्टम पर "Aspose.Cells for .NET" इंस्टॉल करने के लिए दो वैकल्पिक विकल्प हैं। कृपया वह चुनें जो आपकी आवश्यकताओं से मेल खाता हो और चरण-दर-चरण निर्देशों का पालन करें:

{{% /blocks/products/pf/agp/text %}}

1.  ए स्थापित करें[NuGet पैकेज](https://www.nuget.org/packages/Aspose.Cells/) . देखना[प्रलेखन](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  का उपयोग करके लाइब्रेरी स्थापित करें[पैकेज मैनेजर कंसोल](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) विजुअल स्टूडियो आईडीई के भीतर

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण उदाहरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows या .NET, .NET कोर, Windows एज़्योर या Mono प्लेटफ़ॉर्म के साथ संगत ओएस।
-  Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण।
-  अपने प्रोजेक्ट में Aspose.Cells for .NET डीएलएल का संदर्भ जोड़ें।

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="NUMBERS" readMoreLink="https://docs.fileformat.com/spreadsheet/numbers/" >}} .numbers एक्सटेंशन वाली फ़ाइलों को स्प्रेडशीट फ़ाइल प्रकार के रूप में वर्गीकृत किया जाता है, इसीलिए वे .xlsx फ़ाइलों के समान होती हैं; लेकिन Numbers फ़ाइलें Apple iWork Numbers स्प्रेडशीट सॉफ़्टवेयर का उपयोग करके बनाई गई हैं। Apple iWork Numbers iWork Productivity Suite का एक यूनिट सॉफ्टवेयर है। iWork उत्पादकता सुइट Microsoft ऑफिस सुइट के बराबर है जिसका उपयोग Windows पीसी पर किया जाता है। इसलिए, हम कह सकते हैं कि Numbers जो MacOS के लिए उपलब्ध है, Microsoft Excel का भी प्रतिस्पर्धी है। इसी तरह, Microsoft एक्सेल, NUMBERS फ़ाइल में तालिकाएँ, चार्ट और सूत्र भी हो सकते हैं।{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित स्प्रैडशीट जनरेशन" subTitle="आप नीचे सूचीबद्ध कुछ सहित अन्य Microsoft एक्सेल प्रारूप भी बना सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft एक्सेल स्प्रेडशीट (विरासत)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="XML वर्कबुक खोलें" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="एक्सेल बाइनरी वर्कबुक" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="मैक्रो-सक्षम स्प्रेडशीट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="एक्सेल 97 - 2003 टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="एक्सेल टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="अल्पविराम से अलग किये गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="टैब अलग किए गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="संवहन दस्तावेज़ स्वरूप" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
