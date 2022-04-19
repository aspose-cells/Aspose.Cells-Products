---
title: एक्सेल फ़ाइल मेटाडेटा को .NET C# के माध्यम से प्रबंधित करें
url: /hi/net/metadata/
description: देखें, जोड़ें, संपादित करें, निकालें या एक्सेल फ़ाइल मेटाडेटा को केवल C# कोड की कुछ पंक्तियों के साथ निकालें
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel फ़ाइल मेटाडेटा को .NET के द्वारा प्रबंधित करें" h2="सर्वर साइड .NET एपीआई का उपयोग करके अंतर्निहित और कस्टम एक्सेल फ़ाइल गुणों को देखें, जोड़ें, अपडेट करें, निकालें या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET एक्सेल API](/cells/net/) सिस्टम-डिफ़ाइंड (अंतर्निहित) गुणों जैसे शीर्षक, लेखक का नाम, दस्तावेज़ आँकड़े आदि के साथ-साथ उपयोगकर्ता-परिभाषित (कस्टम) गुणों के प्रबंधन का समर्थन करता है नाम-मूल्य जोड़ी के रूप में। वहाँ है [कार्यपुस्तिका वर्ग](https://apireference.aspose.com/cells/net/aspose.cells/workbook) फ़ाइलें लोड करने के लिए, और [वर्कशीटसंग्रह](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) कार्यपत्रकों के संग्रह के साथ-साथ से संबंधित है [वर्कशीट क्लास](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) एकल कार्यपत्रक का प्रतिनिधित्व करने के लिए। इन वर्गों के साथ, बिल्टइनडॉक्यूमेंटप्रॉपर्टीज, कस्टमडॉक्यूमेंटप्रॉपर्टीज मेटाडेटा प्रबंधन के लिए प्रक्रिया को सरल बनाता है। 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="अंतर्निहित गुणों का प्रबंधन" %}}

सिस्टम-परिभाषित गुणों के प्रबंधन के लिए, API प्रदान करता है [बिल्टइनडॉक्यूमेंटप्रॉपर्टीज](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), और प्रोग्रामर आसानी से एक अंतर्निहित संपत्ति तक पहुंच सकते हैं और इसके मूल्य को अपडेट कर सकते हैं। एप्लिकेशन की आवश्यकता के आधार पर, डेवलपर्स इंडेक्स या संपत्ति के नाम का उपयोग कर सकते हैं [दस्तावेज़संपत्ति संग्रह](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# अंतर्निहित गुणों को प्रबंधित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित गुणों का प्रबंधन" %}}

उपयोगकर्ता द्वारा परिभाषित संपत्तियों के प्रबंधन के लिए, API प्रदान करता है [कस्टम दस्तावेज़ गुण](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), और डेवलपर पहले से जोड़ी गई संपत्तियों तक आसानी से पहुंच सकते हैं और साथ ही नई संपत्तियां भी जोड़ सकते हैं। कस्टम गुण जोड़ने के लिए, [विधि जोड़ें](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) का [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) वर्ग संपत्ति जोड़ता है और नई संपत्ति के लिए एक संदर्भ देता है a [गुण।दस्तावेज़संपत्ति](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) वस्तु। DocumentProperty वर्ग का उपयोग दस्तावेज़ संपत्ति के नाम, मूल्य और प्रकार को पुनः प्राप्त करने के लिए किया जाता है: [दस्तावेज़प्रॉपर्टी.नाम](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) जो इनमें से एक लौटाता है [सम्पत्ती के प्रकार](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) गणना मूल्य। 
 
{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फ़ाइल में कस्टम संपत्ति को हटाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
