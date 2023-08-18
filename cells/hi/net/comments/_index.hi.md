---
title: एक्सेल via .NET में टिप्पणियाँ सम्मिलित करें
description:  C# स्रोत कोड बताते हैं कि .NET लाइब्रेरी का उपयोग करके Microsoft एक्सेल फाइलों में टिप्पणी कैसे डालें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल टिप्पणियाँ प्रविष्टि via .NET" h2="एक्सेल दस्तावेज़ बनाएं और .NET-आधारित अनुप्रयोगों में सर्वर-साइड एपीआई का उपयोग करके टिप्पणियाँ डालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}

 आप कक्षों में टिप्पणियाँ जोड़ सकते हैं. जब किसी सेल में कोई टिप्पणी होती है, तो सेल के कोने में एक संकेतक दिखाई देता है। जब आप किसी सेल पर अपना कर्सर घुमाते हैं तो टिप्पणियाँ दिखाई देती हैं। इन टिप्पणियों का उपयोग चर्चा, विशेष निर्देशों या दस्तावेज़ सामग्री के मार्कअप के लिए किया जा सकता है।[.NET एक्सेल लाइब्रेरी](/cells/hi/net/)Excel फ़ाइलों में टिप्पणियाँ सम्मिलित करने का समर्थन करता है। इसके लिए, API एक प्रदान करता है[टिप्पणी](https://reference.aspose.com/cells/net/aspose.cells/comment) टिप्पणियों के निर्माण खंड के लिए कक्षा।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel फ़ाइल में टिप्पणियाँ सम्मिलित करें" %}}

 एक्सेल API का उपयोग करके टिप्पणियाँ सम्मिलित करना सरल है। प्रक्रिया है, बनाएँ[कार्यपुस्तिका कक्षा](https://reference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट करें और उसकी अनुक्रमणिका प्रदान करके पहली वर्कशीट या संबंधित शीट का चयन करें। का उपयोग करके आवश्यक सेल डेटा डालें[पुटवैल्यू विधि](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . का उपयोग करके वर्कशीट में टिप्पणी जोड़ें[टिप्पणी संग्रह](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'एस[विधि जोड़ें](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल में टिप्पणी सम्मिलित करने के लिए कोड" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
