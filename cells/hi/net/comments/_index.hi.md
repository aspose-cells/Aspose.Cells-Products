---
title: .NET के द्वारा Excel में टिप्पणियाँ सम्मिलित करें
url: /hi/net/comment/
description: C# स्रोत कोड कि .NET लाइब्रेरी का उपयोग करके Microsoft Excel फ़ाइलों में टिप्पणी कैसे सम्मिलित करें। 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel टिप्पणियों का सम्मिलन .NET के माध्यम से" h2=".NET-आधारित ऐप्लिकेशन में सर्वर-साइड API का उपयोग करके Excel दस्तावेज़ बनाएं और टिप्पणियां डालें." >}}
{{% blocks/products/pf/feature-page-summary %}}

आप कक्षों में टिप्पणियाँ जोड़ सकते हैं। जब किसी सेल में कोई टिप्पणी होती है, तो सेल के कोने में एक संकेतक दिखाई देता है। जब आप किसी सेल पर अपना कर्सर घुमाते हैं तो टिप्पणियाँ दिखाई देती हैं। इन टिप्पणियों का उपयोग चर्चा, विशेष निर्देशों या दस्तावेज़ सामग्री के मार्कअप के लिए किया जा सकता है। [.NET एक्सेल लाइब्रेरी](/cells/net/) Excel फ़ाइलों में टिप्पणियाँ सम्मिलित करने का समर्थन करता है। इसके लिए, API a . प्रदान करता है [टिप्पणी](https://apireference.aspose.com/cells/net/aspose.cells/comment) टिप्पणी बिल्डिंग ब्लॉक के लिए कक्षा।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल में कमेंट डालें" %}}

Excel API का उपयोग करके टिप्पणियाँ सम्मिलित करना सरल है। प्रक्रिया है, बनाएँ [कार्यपुस्तिका वर्ग](https://apireference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट और इसकी अनुक्रमणिका प्रदान करके पहली वर्कशीट या संबंधित शीट का चयन करें। का उपयोग करके आवश्यक सेल डेटा डालें [पुटवैल्यू विधि](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). का उपयोग करके कार्यपत्रक में टिप्पणी जोड़ें [टिप्पणी संग्रह](https://apireference.aspose.com/cells/net/aspose.cells/commentcollection)'एस [विधि जोड़ें](https://apireference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल में टिप्पणी सम्मिलित करने के लिए कोड" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
