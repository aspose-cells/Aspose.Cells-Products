---
title: C# में एक्सेल वर्कशीट को शीट के अनुसार विभाजित करें
description: C# स्रोत कोड जो बताते हैं कि विज़ुअल C#.NET अनुप्रयोगों में Microsoft एक्सेल फ़ाइलों को एकाधिक फ़ाइलों में कैसे विभाजित किया जाए
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल विभाजन via .NET" h2=".NET आधारित अनुप्रयोगों के भीतर C# कोड का उपयोग करके एकल एक्सेल दस्तावेज़ को विभिन्न फ़ाइलों में विभाजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET एक्सेल लाइब्रेरी](/cells/hi/net/) .NET आधारित अनुप्रयोगों के भीतर एक्सेल दस्तावेज़ को कई स्प्रेडशीट में विभाजित करने में सक्षम है। समर्थित फ़ाइल स्वरूपों में XLS, XLSX, XLSB, XLSM, ODS शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल दस्तावेज़ को एकाधिक फ़ाइलों में विभाजित करें" %}}
एक्सेल फ़ाइलों को शीट के अनुसार विभाजित करने का सबसे सरल तरीका है, सभी शीटों तक पहुँचना[कार्यपत्रक](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , प्रत्येक शीट के माध्यम से पुनरावृत्ति करना और कॉल करना[प्रतिलिपि](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) तरीका। अंत में इसे एक निर्दिष्ट पथ में सहेजना।

 + एक्सेल फ़ाइल को पूर्ण पथ के साथ लोड करें[कार्यपुस्तिका कक्षा](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ प्रत्येक शीट में पुनरावृति करें
+ एक नई वर्कबुक क्लास ऑब्जेक्ट बनाएं
 + शीट को कॉपी करें[प्रतिलिपि विधि](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ सेव() विधि को कॉल करें और प्रासंगिक सेवफॉर्मेट वाले फ़ाइल नाम (पूर्ण पथ) को पास करें।

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फाइलों को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को पैन में विभाजित करें" %}}

 वर्कशीट विंडो को पैन में विभाजित करने के लिए, API प्रदान करता है[विभाजन विधि](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) वर्कशीट वर्ग का, जो वर्कशीट का विभाजित दृश्य प्रदान करता है। विभाजित दृश्य को हटाने के लिए API प्रदान करता है[रिमूवस्प्लिट विधि](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . अंत में इसे एक निर्दिष्ट पथ में सहेजें।

{{% blocks/products/pf/feature-page-code h3="C# एक्सेल वर्कशीट विंडो को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="स्प्लिट पैन व्यू को हटाने के लिए C# कोड" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
