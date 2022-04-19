---
title: एक्सेल फ़ाइल मेटाडेटा को C++ के माध्यम से प्रबंधित करें
url: /hi/cpp/metadata/
description: C++ लाइब्रेरी . का उपयोग करके एक्सेल फाइल मेटाडेटा देखें, जोड़ें, संपादित करें, निकालें या निकालें
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel दस्तावेज़ मेटाडेटा को C++ के माध्यम से प्रबंधित करें" h2="C++ अनुप्रयोगों के भीतर कस्टम और अंतर्निहित एक्सेल दस्तावेज़ गुण देखें, डालें, अपडेट करें, निकालें या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
एक्सेल में मेटाडेटा - एक्सेल फ़ाइल मेटाडेटा को कैसे देखें, डालें और निकालें। [C++ एक्सेल लाइब्रेरी](/cells/cpp/) अंतर्निहित / सिस्टम-परिभाषित गुणों जैसे कि लेखक का नाम, शीर्षक, दस्तावेज़ आँकड़े आदि का समर्थन करके आसान तरीके से सुविधा होती है, जैसे कि यह जाँचने के लिए कि अंतिम रूप से फ़ाइल को संशोधित या सहेजा गया है या कस्टम / उपयोगकर्ता-परिभाषित गुणों के रूप में सहेजा गया है। नाम/मूल्य जोड़े। प्रक्रिया को स्वचालित करने के लिए, पुस्तकालय बड़ी मेटाडेटा एक्सेल फ़ाइलों को बनाने और बनाए रखने का समर्थन करता है। [CreateIकार्यपुस्तिका विधि](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) का [कारखाना वर्ग](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) पथ द्वारा, स्ट्रीम द्वारा और विशेष FileFormatType द्वारा कार्यपुस्तिका खोलें। इसलिए आगे की प्रक्रिया के लिए फ़ाइल को उपयुक्त विधि से लोड करें। नीचे सूचीबद्ध संभावनाओं में से कुछ और डेवलपर्स आसानी से आवेदन की आवश्यकता के अनुसार अपने कोड को बढ़ा सकते हैं। 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="अंतर्निहित गुण पढ़ें और अपडेट करें" %}}

अंतर्निहित गुणों को स्वचालित करने के लिए, API प्रदान करता है [गेटआईबिल्टइनडॉक्यूमेंटप्रॉपर्टीज ()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) वह विधि जो स्प्रैडशीट के सभी अंतर्निहित दस्तावेज़ गुणों का प्रतिनिधित्व करने वाला दस्तावेज़प्रॉपर्टीज संग्रह लौटाती है। सभी अंतर्निहित गुणों तक पहुँचने के बाद, प्रासंगिक विधि जैसे GetTitle (), GetSubject () आदि का उपयोग करके प्रासंगिक गुणों तक पहुँचें। गुणों को अद्यतन करने के लिए, API विधि प्रदान करता है जैसे कि SetTitle, SetSubject, SetAuthor, SetComments आदि। देखें [बिल्टिन दस्तावेज़ संपत्ति संग्रह](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) आवश्यक समारोह के लिए।

{{% blocks/products/pf/feature-page-code h3="C++ सिस्टम परिभाषित गुण पढ़ने के लिए कोड" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ अंतर्निहित गुणों को अद्यतन करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित गुण देखें और जोड़ें" %}}

कस्टम गुणों को संभालने के लिए, API प्रदान करता है [IWorkbookMetadata::GetICustomDocumentProperties](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) जो स्प्रैडशीट के सभी कस्टम दस्तावेज़ गुण संग्रह लौटाता है। सबसे पहले इस पद्धति के माध्यम से कस्टम गुणों तक पहुँचने के लिए, डेवलपर्स AddIDocumentProperty, AddLinkToContentProperty जैसी संपत्तियों को जोड़ने के लिए प्रासंगिक तरीकों का उपयोग कर सकते हैं और इसी तरह कस्टम दस्तावेज़ संपत्ति मूल्य को अपडेट करने के लिए UpdateLinkedPropertyValue, UpdateLinkedRange का उपयोग कर सकते हैं जो क्रमशः सामग्री और लिंक की गई सीमा से लिंक करता है। डेवलपर्स प्रासंगिक विधि का उपयोग कर सकते हैं [कस्टम दस्तावेज़ गुणों का संग्रह](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ कस्टम गुण देखने के लिए कोड" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए कोड" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}