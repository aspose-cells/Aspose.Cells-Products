---
title:  Microsoft Excel XLS फ़ाइलों में C# के माध्यम से पिवट चार्ट डालें
weight: 7690
description: C# .NET लाइब्रेरी का उपयोग करके XLS में पिवट चार्ट जोड़ने के लिए नमूना कोड। VB.NET, Asp.NET या किसी भी .NET आधारित एप्लिकेशन के भीतर XLS फ़ाइल में पिवट चार्ट डालने के लिए इस कोड का उपयोग करें।
keywords: [C# Aspose.Cells., c# add pivot chart in xls., c# insert pivot chart in xls., c# create pivot chart in xls., c# modify pivot chart in xls., access pivot chart in xls]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS दस्तावेज़ों में C# के माध्यम से पिवट चार्ट डालें" h2="सर्वर साइड .NET APIs का उपयोग करके प्रोग्रामेटिक रूप से पिवट चार्ट निर्माण के साथ मूल और उच्च प्रदर्शन Microsoft एक्सेल XLS स्प्रेडशीट।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

चल रहे एप्लिकेशन के भीतर गतिशील रूप से पिवट चार्ट के साथ MS Excel XLS फ़ाइल बनाना आसान है। MS Office की आवश्यकता के बिना स्क्रैच से पिवट चार्ट के साथ XLS दस्तावेज़ बनाने के लिए, हम उपयोग करेंगे[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API जो .NET प्लेटफ़ॉर्म का उपयोग करके स्प्रेडशीट निर्माण, हेरफेर और रूपांतरण के लिए विभिन्न सुविधाएँ प्रदान करता है। डेवलपर्स आसानी से डेटा लिखने, चार्ट या ग्राफ़ बनाने के साथ-साथ स्प्रेडशीट में टेबल बनाने के लिए कोड को बढ़ा सकते हैं।
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLS से C# तक पिवट चार्ट कैसे डालें" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ ही पंक्तियों में डेटा प्रोसेसिंग के लिए विभिन्न रिपोर्टिंग अनुप्रयोगों को चलाने के लिए XLS प्रारूप स्प्रेडशीट में पिवट चार्ट सम्मिलित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  अपनी क्लास फ़ाइल में नामस्थान शामिल करें
1.  कार्यपुस्तिका वर्ग उदाहरण बनाएँ.
1.  कार्यपुस्तिका की पहली वर्कशीट तक पहुँचें.
1.  वर्कशीट के वांछित सेल(सेल्स) प्राप्त करें और सेल(सेल्स) में मान डालें।
1.  PivotTable डालें और शैली सेट करें
1.  PivotTable के डेटा का उपयोग करके Pivot Chart डालें
1.  कार्यपुस्तिका को XLS फ़ाइल के रूप में सहेजने के लिए Save विधि का उपयोग करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

बस यह सुनिश्चित करें कि सिस्टम में Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Windows एज़्योर, Mono या ज़ेमारिन प्लेटफ़ॉर्म के साथ संगत ओएस और साथ ही Microsoft विज़ुअल स्टूडियो जैसा विकास वातावरण हो।

{{% /blocks/products/pf/agp/text %}}

-  कमांड लाइन से इस प्रकार स्थापित करें<code>nuget install Aspose.Cells</code> या विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से<code>Install-Package Aspose.Cells</code>.
-  वैकल्पिक रूप से, ऑफ़लाइन MSI इंस्टॉलर या सभी DLL को ZIP फ़ाइल में प्राप्त करें<a href="https://downloads.aspose.com/cells/net">डाउनलोड</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS - C# में पिवट चार्ट डालें" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "PivotTables-LandingPage-Insert-Pivot-Cylinder-Chart-xls.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->     
{{% blocks/products/pf/agp/content h2="" %}}

एक एक्सेल स्प्रेडशीट प्रोग्रामिंग लाइब्रेरी जो क्रॉस-प्लेटफॉर्म अनुप्रयोगों का निर्माण करने में सक्षम है, जिसमें एक्सेल XLS फाइलें बनाने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता है। .NET एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच रूपांतरित करता है, बल्कि यह एक्सेल फाइलों को छवियों, PDF, HTML, ODS और अधिक के रूप में प्रस्तुत भी कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प है।



{{% /blocks/products/pf/agp/content %}}
{{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS एक्सटेंशन वाली फ़ाइलें एक्सेल बाइनरी फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करती हैं। ऐसी फ़ाइलें Microsoft एक्सेल के साथ-साथ ओपनऑफ़िस कैल्क या ऐप्पल Numbers जैसे अन्य समान स्प्रेडशीट प्रोग्राम द्वारा बनाई जा सकती हैं। एक्सेल द्वारा सहेजी गई फ़ाइल को वर्कबुक के रूप में जाना जाता है जहाँ प्रत्येक वर्कबुक में एक या अधिक वर्कशीट हो सकती हैं। डेटा को वर्कशीट में टेबल फ़ॉर्मेट में उपयोगकर्ताओं को संग्रहीत और प्रदर्शित किया जाता है और संख्यात्मक मान, टेक्स्ट डेटा, सूत्र, बाहरी डेटा कनेक्शन, चित्र और चार्ट तक फैला हो सकता है। Microsoft एक्सेल जैसे एप्लिकेशन आपको PDF, CSV, XLSX, TXT, HTML, XPS और कई अन्य सहित कई अलग-अलग फ़ॉर्मेट में वर्कबुक डेटा निर्यात करने देता है। XLS फ़ाइल प्रारूप को Microsoft एक्सेल 2007 के जारी होने के साथ अधिक खुले और संरचित प्रारूप, XLSX से प्रतिस्थापित किया गया। नवीनतम संस्करण अभी भी XLS फ़ाइलों को बनाने और पढ़ने के लिए समर्थन प्रदान करते हैं, हालांकि XLSX अब उपयोग की पहली पसंद है।

{{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित पिवट चार्ट प्रारूप" subTitle="आप पिवट चार्ट के साथ अन्य Microsoft एक्सेल प्रारूप भी बना सकते हैं, जिनमें से कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/pivottable/insert-pivot-chart-to-xls/" name="XLS" description="Microsoft एक्सेल स्प्रेडशीट (विरासत)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/pivottable/insert-pivot-chart-to-xlsx/" name="XLSX" description="XML कार्यपुस्तिका खोलें" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/pivottable/insert-pivot-chart-to-xlsb/" name="XLSB" description="एक्सेल बाइनरी वर्कबुक" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/pivottable/insert-pivot-chart-to-xlsm/" name="XLSM" description="मैक्रो-सक्षम स्प्रेडशीट" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
