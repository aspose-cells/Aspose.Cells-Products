---
title: C++ के माध्यम से एक्सेल फ़ाइल मेटाडेटा प्रबंधित करें
description: C++ लाइब्रेरी का उपयोग करके एक्सेल फ़ाइलों के मेटाडेटा को देखें, जोड़ें, संपादित करें, हटाएं या निकालें
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>&reg;</sup> एक्सेल दस्तावेज़ मेटाडेटा को C++ के माध्यम से प्रबंधित करें" h2="C++ अनुप्रयोगों के भीतर कस्टम और अंतर्निहित एक्सेल दस्तावेज़ गुणों को देखें, सम्मिलित करें, अपडेट करें, हटाएं या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
 एक्सेल में मेटाडेटा - एक्सेल फ़ाइल मेटाडेटा को कैसे देखें, डालें और हटाएँ।[C++ एक्सेल लाइब्रेरी](/cells/hi/cpp/) सुविधा आसान तरीके से अंतर्निहित / सिस्टम-परिभाषित गुणों जैसे लेखक का नाम, शीर्षक, दस्तावेज़ आँकड़े आदि का समर्थन करती है, जैसे कि यह जांचना कि अंतिम फ़ाइल कब संशोधित या कस्टम / उपयोगकर्ता-परिभाषित गुणों के साथ सहेजी गई है नाम/मूल्य जोड़े. प्रक्रिया को स्वचालित करने के लिए, लाइब्रेरी बड़ी मेटाडेटा एक्सेल फ़ाइलों को बनाने और बनाए रखने का समर्थन करती है।[वर्कबुक](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)क्लास किसी कार्यपुस्तिका को पथ, स्ट्रीम और विशेष FileFormatType द्वारा खोलता है। इसलिए आगे की प्रक्रिया के लिए फ़ाइल को उचित विधि से लोड करें। नीचे सूचीबद्ध कुछ संभावनाएं और डेवलपर्स एप्लिकेशन की आवश्यकता के अनुसार अपने कोड को आसानी से बढ़ा सकते हैं।
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="अंतर्निहित गुण पढ़ें और अद्यतन करें" %}}

 अंतर्निहित संपत्तियों को स्वचालित करने के लिए, API प्रदान करता है[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) वह विधि जो स्प्रेडशीट के सभी अंतर्निहित दस्तावेज़ गुणों का प्रतिनिधित्व करते हुए एक DocumentProperties संग्रह लौटाती है। सभी अंतर्निहित संपत्तियों तक पहुंचने के बाद, प्रासंगिक विधि जैसे GetTitle(), GetSubject() आदि का उपयोग करके संबंधित गुणों तक पहुंचें। गुणों को अद्यतन करने के लिए, API SetTitle, SetSubject, SetAuthor, SetComments आदि जैसी विधि प्रदान करता है। देखें[अंतर्निहित दस्तावेज़ संपत्ति संग्रह](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) आवश्यक कार्य के लिए.

{{% blocks/products/pf/feature-page-code h3="सिस्टम परिभाषित गुणों को पढ़ने के लिए C++ कोड" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ अंतर्निहित संपत्तियों को अद्यतन करने के लिए कोड" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित गुण देखें और जोड़ें" %}}

कस्टम संपत्तियों को संभालने के लिए, API प्रदान करता है[कार्यपुस्तिका::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) जो स्प्रैडशीट के सभी कस्टम दस्तावेज़ गुण संग्रह लौटाता है। सबसे पहले इस विधि के माध्यम से कस्टम गुणों तक पहुंच, डेवलपर्स AddIDocumentProperty, AddLinkToContentProperty जैसे गुणों को जोड़ने के लिए प्रासंगिक तरीकों का उपयोग कर सकते हैं और इसी तरह कस्टम दस्तावेज़ प्रॉपर्टी मान को अपडेट करने के लिए UpdateLinkedPropertyValue, UpdateLinkedRange का उपयोग कर सकते हैं जो क्रमशः सामग्री और लिंक की गई श्रेणी से लिंक होते हैं। डेवलपर्स प्रासंगिक विधि का उपयोग कर सकते हैं[कस्टम दस्तावेज़ गुणों का संग्रह](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="कस्टम गुण देखने के लिए C++ कोड" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए C++ कोड" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
