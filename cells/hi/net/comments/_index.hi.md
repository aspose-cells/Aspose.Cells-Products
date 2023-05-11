---
title: एक्सेल via .NET में टिप्पणियां डालें
description:  C# स्रोत कोड जो .NET लाइब्रेरी का उपयोग करके Microsoft एक्सेल फ़ाइलों में टिप्पणी कैसे सम्मिलित करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल टिप्पणी प्रविष्टि via .NET" h2="एक्सेल दस्तावेज़ बनाएं और .NET-आधारित अनुप्रयोगों में सर्वर-साइड एपीआई का उपयोग करके टिप्पणियां डालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}

 आप सेल में टिप्पणियाँ जोड़ सकते हैं। जब सेल में कोई टिप्पणी होती है, तो सेल के कोने में एक संकेतक दिखाई देता है। टिप्पणियाँ तब दिखाई देती हैं जब आप अपने कर्सर को सेल पर हॉवर करते हैं। इन टिप्पणियों का उपयोग चर्चा, विशेष निर्देशों या दस्तावेज़ सामग्री के मार्कअप के लिए किया जा सकता है।[.NET एक्सेल लाइब्रेरी](/cells/hi/net/)एक्सेल फाइलों में टिप्पणियां डालने का समर्थन करता है। इसके लिए, API एक प्रदान करता है[टिप्पणी](https://reference.aspose.com/cells/net/aspose.cells/comment) टिप्पणी बिल्डिंग ब्लॉक के लिए वर्ग।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल में कमेंट डालें" %}}

 Excel API का उपयोग करके टिप्पणियाँ सम्मिलित करना सरल है। प्रक्रिया है, बनाएँ[कार्यपुस्तिका वर्ग](https://reference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट और इसकी अनुक्रमणिका प्रदान करके पहली वर्कशीट या प्रासंगिक शीट का चयन करें। आवश्यक सेल डेटा का उपयोग करके डालें[पुटवैल्यू विधि](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . का उपयोग करके वर्कशीट में टिप्पणी जोड़ें[टिप्पणी संग्रह](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'एस[जोड़ें विधि](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="एक्सेल में टिप्पणी डालने के लिए C# कोड" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
