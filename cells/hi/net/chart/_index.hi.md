---
title: एक्सेल चार्ट निर्माण और छवियों में रूपांतरण via .NET
description:  C# स्रोत कोड Microsoft एक्सेल में .NET लाइब्रेरी का उपयोग करके चार्ट या आरेख बनाने और परिवर्तित करने के लिए।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल चार्ट निर्माण और रूपांतरण via .NET" h2="एक्सेल दस्तावेज़ चार्ट बनाएं और .NET आधारित अनुप्रयोगों के भीतर सर्वर-साइड एपीआई का उपयोग करके छवियों में परिवर्तित करें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
 आरेखण चार्ट आसान विश्लेषण के लिए डेटा को ग्राफ़िक रूप से प्रदर्शित करने की एक कला है।[.NET एक्सेल लाइब्रेरी](/cells/hi/net/) एक्सेल फाइलों के भीतर ड्राइंग चार्ट का समर्थन करता है। API में सूचीबद्ध विभिन्न चार्ट निर्माण का समर्थन करता है[चार्ट प्रकार गणना](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) पाई, पिरामिड, लाइन और बबल चार्ट सहित। इसके अलावा, यह चार्ट को छवियों में भी परिवर्तित करता है। API एक प्रदान करता है[चार्ट वर्ग](https://reference.aspose.com/cells/net/aspose.cells.charts) चार्ट बिल्डिंग ब्लॉक्स के लिए।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल में चार्ट बनाएं" %}}

 Excel API का उपयोग करके चार्ट बनाना सरल है। प्रक्रिया है, बनाएँ[कार्यपुस्तिका वर्ग](https://reference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट और इसकी अनुक्रमणिका प्रदान करके पहली वर्कशीट या प्रासंगिक शीट का चयन करें। आवश्यक सेल डेटा का उपयोग करके डालें[पुटवैल्यू विधि](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . चार्ट संग्रह का उपयोग कर वर्कशीट में चार्ट जोड़ें[जोड़ें विधि](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . विवरण दें[चार्ट प्रकार](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)चार्टटाइप गणना से।
{{% blocks/products/pf/feature-page-code h3="एक्सेल चार्ट बनाने के लिए C# कोड" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल चार्ट को छवियों में बदलें" %}}

 चार्ट को छवियों में बदलने की प्रक्रिया है, एक्सेल फाइल को लोड करने के लिए वर्कबुक क्लास का उपयोग करें, चार्ट वाले प्रासंगिक वर्कशीट का चयन करें और कॉल करें[ToImage विधि](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) रूपांतरण के लिए।

{{% blocks/products/pf/feature-page-code h3="एक्सेल चार्ट को छवि में बदलने के लिए C# कोड" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
