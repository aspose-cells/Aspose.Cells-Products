---
title:  C# के माध्यम से लाइन चार्ट बनाएं
description: C# .NET लाइब्रेरी का उपयोग करके एक्सेल में लाइन चार्ट बनाने के लिए नमूना कोड। VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन के भीतर MS Excel के लिए एक लाइन चार्ट बनाने के लिए इस कोड का उपयोग करें।
keywords: [C# Aspose.Cells., c# add Line Chart., c# insert Line Chart., c# create Line Chart]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से लाइन चार्ट बनाएं" h2="सर्वर साइड .NET एपीआई का उपयोग करके प्रोग्रामेटिक रूप से मूल और उच्च प्रदर्शन एमएस एक्सेल चार्ट निर्माण।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

चल रहे एप्लिकेशन के भीतर गतिशील रूप से लाइन चार्ट बनाना आसान है। एमएस ऑफिस की आवश्यकता के बिना स्क्रैच से विभिन्न प्रकार के चार्ट से लेकर स्प्रेडशीट बनाने के लिए, हम इसका उपयोग करेंगे[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API जो .NET प्लेटफॉर्म का उपयोग करके स्प्रेडशीट निर्माण, हेरफेर और रूपांतरण के लिए विभिन्न सुविधाएँ प्रदान करता है। Aspose.Cells कई लचीले चार्ट ऑब्जेक्ट प्रदान करता है।
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से लाइन चार्ट कैसे बनाएं" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ पंक्तियों में डेटा प्रोसेसिंग के लिए विभिन्न रिपोर्टिंग एप्लिकेशन चलाने के भीतर एक लाइन चार्ट बनाना आसान है।

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Cells नेमस्पेस शामिल करें
1.  बनाएं[**वर्कबुक**](https://reference.aspose.com/cells/net/aspose.cells/workbook) वर्ग उदाहरण.
1. वर्कशीट में कुछ डेटा जोड़ें.
1.  एक जोड़ना[**रेखा**](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) वर्कशीट का चार्ट.
1.  नये तक पहुंचें[**चार्ट**](https://reference.aspose.com/cells/net/aspose.cells.charts/chart)वस्तु।
1.  चार्ट के डेटा स्रोत को निर्दिष्ट करें[**चार्ट.सेटचार्टडेटारेंज**](https://https://reference.aspose.com/cells/net/aspose.cells.charts/chart/methods/setchartdatarange) तरीका।


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

बस सुनिश्चित करें कि सिस्टम में Microsoft Windows या .NET फ्रेमवर्क, .NET कोर, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म के साथ-साथ Microsoft विज़ुअल स्टूडियो जैसे विकास वातावरण के साथ एक संगत ओएस है।

{{% /blocks/products/pf/agp/text %}}

-  कमांड लाइन से इस रूप में इंस्टॉल करें<code>nuget install Aspose.Cells</code> या विज़ुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से<code>Install-Package Aspose.Cells</code>.
-  वैकल्पिक रूप से, ऑफ़लाइन एमएसआई इंस्टॉलर या ज़िप फ़ाइल में सभी डीएलएल प्राप्त करें<a href="https://downloads.aspose.com/cells/net">डाउनलोड</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="निम्नलिखित स्रोत कोड दिखाता है कि C# का उपयोग करके एमएस एक्सेल XLSX फ़ाइल के लिए एक लाइन चार्ट कैसे बनाया जाए।" offSpacer="" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "Examples-CSharp-Charts-CreateLineChart.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
