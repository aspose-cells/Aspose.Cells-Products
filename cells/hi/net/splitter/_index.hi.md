---
title: एक्सेल वर्कशीट शीट को C# में विभाजित करें
url: /hi/net/splitter/
description: C# स्रोत कोड जो यह बताते हैं कि Microsoft Excel फ़ाइलों को विज़ुअल C#.NET अनुप्रयोगों में एकाधिक फ़ाइलों में कैसे विभाजित किया जाए
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल .NET के माध्यम से विभाजित करना" h2=".NET आधारित अनुप्रयोगों में C# कोड का उपयोग करके एकल एक्सेल दस्तावेज़ को विभिन्न फाइलों में विभाजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET एक्सेल लाइब्रेरी](/cells/net/) एक्सेल दस्तावेज़ को .NET आधारित अनुप्रयोगों में एकाधिक स्प्रेडशीट में विभाजित करने में सक्षम है। समर्थित फ़ाइल स्वरूपों में XLS, XLSX, XLSB, XLSM, ODS शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल दस्तावेज़ को कई फाइलों में विभाजित करें" %}}
एक्सेल फाइलों को शीट के अनुसार विभाजित करने का सबसे आसान तरीका है, सभी शीट्स को एक्सेस करना [कार्यपत्रक](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), प्रत्येक शीट के माध्यम से पुनरावृति करना और कॉल करना [प्रतिलिपि](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) तरीका। अंत में इसे एक निर्दिष्ट पथ में सहेजना। 

+ एक्सेल फ़ाइल को पूर्ण पथ का उपयोग करके लोड करें [कार्यपुस्तिका वर्ग](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+ प्रत्येक शीट के माध्यम से पुनरावृति
+ एक नई वर्कबुक क्लास ऑब्जेक्ट बनाएं
+ के माध्यम से शीट की प्रतिलिपि बनाएँ [कॉपी विधि](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ सहेजें () विधि को कॉल करें और प्रासंगिक SaveFormat वाले फ़ाइल नाम (पूर्ण पथ) को पास करें।

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फाइलों को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को पैन में विभाजित करें" %}}

कार्यपत्रक विंडो को पैन में विभाजित करने के लिए, API प्रदान करता है [विभाजित विधि](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) कार्यपत्रक वर्ग का, जो कार्यपत्रक का विभाजित दृश्य प्रदान करता है। विभाजित दृश्य को हटाने के लिए API प्रदान करता है [निकालेंविभाजन विधि](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). अंत में इसे एक निर्दिष्ट पथ में सहेजें। 

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल वर्कशीट विंडो को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# विभाजित पैन दृश्य को हटाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
