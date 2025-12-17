---
title: C++ के ज़रिए Go के साथ Excel फ़ाइल मेटाडेटा मैनेज करें
description: Go via C++ लाइब्रेरी का इस्तेमाल करके Excel फ़ाइल मेटाडेटा देखें, जोड़ें, एडिट करें, हटाएं या निकालें
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel डॉक्यूमेंट मेटाडेटा को Go के ज़रिए C++ से मैनेज करें" h2="C++ एप्लिकेशन में कस्टम और बिल्ट-इन Excel डॉक्यूमेंट प्रॉपर्टीज़ देखें, डालें, अपडेट करें, हटाएं या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
 एक्सेल में मेटाडेटा - एक्सेल फ़ाइल मेटाडेटा को कैसे देखें, डालें और निकालें।[C++ एक्सेल लाइब्रेरी के ज़रिए जाएं](/cells/hi/go-cpp/)लेखक का नाम, टाइटल, डॉक्यूमेंट स्टैटिस्टिक्स वगैरह जैसी बिल्ट-इन / सिस्टम-डिफाइंड प्रॉपर्टीज़ को सपोर्ट करके आसान तरीके से सुविधा मिलती है, जैसे कभी-कभी यह चेक करना कि आखिरी बार फ़ाइल कब बदली या सेव हुई है, साथ ही नाम/वैल्यू पेयर के रूप में कस्टम / यूज़र-डिफाइंड प्रॉपर्टीज़ भी। प्रोसेस को ऑटोमेट करने के लिए, लाइब्रेरी बड़ी मेटाडेटा एक्सेल फ़ाइलें बनाने और मेंटेन करने में मदद करती है।[वर्कबुक](https://reference.aspose.com/cells/go-cpp/workbook/) क्लास पाथ, स्ट्रीम और स्पेशल FileFormatType से वर्कबुक खोलता है। इसलिए आगे की प्रोसेसिंग के लिए फ़ाइल को सही मेथड से लोड करें। नीचे कुछ ऑप्शन दिए गए हैं और डेवलपर्स आसानी से एप्लिकेशन की ज़रूरत के हिसाब से अपने कोड को बेहतर बना सकते हैं।

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="अंतर्निहित गुण पढ़ें और अपडेट करें" %}}

 बिल्ट-इन प्रॉपर्टीज़ को ऑटोमेट करने के लिए, API देता है[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)मेथड जो स्प्रेडशीट की सभी बिल्ट-इन डॉक्यूमेंट प्रॉपर्टीज़ को दिखाने वाला एक DocumentProperties कलेक्शन लौटाता है। सभी बिल्ट-इन प्रॉपर्टीज़ को एक्सेस करने के बाद, GetTitle(), GetSubject() वगैरह जैसे संबंधित मेथड का इस्तेमाल करके संबंधित प्रॉपर्टीज़ को एक्सेस करें। प्रॉपर्टीज़ को अपडेट करने के लिए, API SetTitle, SetSubject, SetAuthor, SetComments वगैरह जैसे मेथड देता है। देखें[अंतर्निहित दस्तावेज़ संपत्ति संग्रह](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) ज़रूरी फ़ंक्शन के लिए।

{{% blocks/products/pf/feature-page-code h3="सिस्टम डिफाइन्ड प्रॉपर्टीज़ पढ़ने के लिए C++ कोड पर जाएं" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="बिल्ट-इन प्रॉपर्टीज़ को अपडेट करने के लिए C++ कोड का इस्तेमाल करें" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित प्रॉपर्टीज़ देखें और जोड़ें" %}}

 कस्टम प्रॉपर्टीज़ को हैंडल करने के लिए, API देता है[कार्यपुस्तिका::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)जो स्प्रेडशीट के सभी कस्टम डॉक्यूमेंट प्रॉपर्टी कलेक्शन को रिटर्न करता है। सबसे पहले इस मेथड से कस्टम प्रॉपर्टी को एक्सेस करके, डेवलपर्स AddIDocumentProperty, AddLinkToContentProperty जैसी प्रॉपर्टी जोड़ने के लिए रिलेवेंट मेथड का इस्तेमाल कर सकते हैं और इसी तरह UpdateLinkedPropertyValue, UpdateLinkedRange का इस्तेमाल कस्टम डॉक्यूमेंट प्रॉपर्टी वैल्यू को अपडेट करने के लिए कर सकते हैं जो क्रमशः कंटेंट और लिंक्ड रेंज से लिंक होती हैं। डेवलपर्स रिलेवेंट मेथड का इस्तेमाल कर सकते हैं[कस्टम दस्तावेज़ गुणों का संग्रह](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="कस्टम प्रॉपर्टी देखने के लिए C++ कोड का इस्तेमाल करें" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Excel फ़ाइल में मेटाडेटा जोड़ने के लिए C++ कोड का इस्तेमाल करें" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}