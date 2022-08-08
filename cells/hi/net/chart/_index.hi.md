---
title: .NET के माध्यम से एक्सेल चार्ट निर्माण और छवियों में रूपांतरण
url: /hi/net/chart/
description: .NET लाइब्रेरी का उपयोग करके Microsoft Excel में चार्ट या आरेख बनाने और परिवर्तित करने के लिए C# स्रोत कोड। 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल चार्ट निर्माण और रूपांतरण .NET के माध्यम से" h2="एक्सेल दस्तावेज़ चार्ट बनाएं और .NET आधारित एप्लिकेशन के भीतर सर्वर-साइड एपीआई का उपयोग करके छवियों में कनवर्ट करें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
आरेखण चार्ट आसान विश्लेषण के लिए डेटा को आलेखीय रूप से प्रदर्शित करने की एक कला है। [.NET एक्सेल लाइब्रेरी](/cells/net/) एक्सेल फाइलों के भीतर आरेखण चार्ट का समर्थन करता है। API में सूचीबद्ध विभिन्न चार्ट निर्माण का समर्थन करता है [चार्ट प्रकार गणना](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) पाई, पिरामिड, रेखा और बबल चार्ट सहित। इसके अलावा, यह चार्ट को छवियों में भी परिवर्तित करता है। API प्रदान करता है [चार्ट वर्ग](https://reference.aspose.com/cells/net/aspose.cells.charts) चार्ट बिल्डिंग ब्लॉक्स के लिए।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल में चार्ट बनाएं" %}}

एक्सेल API का उपयोग करके चार्ट बनाना आसान है। प्रक्रिया है, बनाएँ [कार्यपुस्तिका वर्ग](https://reference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट और इसकी अनुक्रमणिका प्रदान करके पहली वर्कशीट या संबंधित शीट का चयन करें। का उपयोग करके आवश्यक सेल डेटा डालें [पुटवैल्यू विधि](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). चार्ट संग्रह का उपयोग करके कार्यपत्रक में चार्ट जोड़ें [विधि जोड़ें](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). विवरण दें [चार्ट प्रकार](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) चार्ट टाइप एन्यूमरेशन से।
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल चार्ट बनाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल चार्ट को इमेज में बदलें" %}}

चार्ट को इमेज में बदलने की प्रक्रिया है, एक्सेल फाइल को लोड करने के लिए वर्कबुक क्लास का उपयोग करें, चार्ट वाले संबंधित वर्कशीट का चयन करें और कॉल करें [ToImage विधि](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) रूपांतरण के लिए।

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल चार्ट को इमेज में बदलने के लिए कोड" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}