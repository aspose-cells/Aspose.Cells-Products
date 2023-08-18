---
title: एक्सेल फ़ाइल मेटाडेटा via .NET C# प्रबंधित करें
description: C# कोड की कुछ पंक्तियों के साथ एक्सेल फ़ाइलों के मेटाडेटा को देखें, जोड़ें, संपादित करें, हटाएं या निकालें
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल मेटाडेटा via .NET प्रबंधित करें" h2="सर्वर साइड .NET एपीआई का उपयोग करके अंतर्निहित और कस्टम एक्सेल फ़ाइल गुणों को देखें, जोड़ें, अपडेट करें, हटाएं या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET एक्सेल API](/cells/hi/net/) सिस्टम-परिभाषित (अंतर्निहित) गुणों जैसे शीर्षक, लेखक का नाम, दस्तावेज़ आँकड़े आदि के साथ-साथ नाम-मूल्य जोड़ी के रूप में उपयोगकर्ता-परिभाषित (कस्टम) गुणों के प्रबंधन का समर्थन करता है। वहाँ है[कार्यपुस्तिका कक्षा](https://reference.aspose.com/cells/net/aspose.cells/workbook) फ़ाइलें लोड करने के लिए, और[वर्कशीट संग्रह](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)कार्यपत्रकों के संग्रहण के साथ-साथ कार्य करता है[वर्कशीट क्लास](https://reference.aspose.com/cells/net/aspose.cells/worksheet) एकल वर्कशीट का प्रतिनिधित्व करने के लिए। इन कक्षाओं के साथ, बिल्टइनडॉक्यूमेंटप्रॉपर्टीज, कस्टमडॉक्यूमेंटप्रॉपर्टीज मेटाडेटा प्रबंधन के लिए प्रक्रिया को सरल बनाता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="अंतर्निहित संपत्तियों का प्रबंधन" %}}

 सिस्टम-परिभाषित संपत्तियों के प्रबंधन के लिए, API प्रदान करता है[बिल्टइनडॉक्यूमेंटप्रॉपर्टीज़](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , और प्रोग्रामर आसानी से अंतर्निहित संपत्ति तक पहुंच सकते हैं और उसके मूल्य को अपडेट कर सकते हैं। एप्लिकेशन की आवश्यकता के आधार पर, डेवलपर्स इंडेक्स या प्रॉपर्टी नाम का उपयोग कर सकते हैं[दस्तावेज़संपत्ति संग्रह](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="अंतर्निहित संपत्तियों को प्रबंधित करने के लिए C# कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित गुणों का प्रबंधन" %}}

 उपयोगकर्ता-परिभाषित संपत्तियों के प्रबंधन के लिए, API प्रदान करता है[कस्टम दस्तावेज़ गुण](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , और डेवलपर्स पहले से जोड़ी गई संपत्तियों तक आसानी से पहुंच सकते हैं और साथ ही नई संपत्तियां भी जोड़ सकते हैं। कस्टम गुण जोड़ने के लिए,[विधि जोड़ें](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) का[कस्टमडॉक्यूमेंटप्रॉपर्टीकलेक्शन](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) क्लास प्रॉपर्टी जोड़ता है और नई प्रॉपर्टी के लिए एक संदर्भ लौटाता है[गुण.दस्तावेज़संपत्ति](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)वस्तु। DocumentProperty वर्ग का उपयोग दस्तावेज़ संपत्ति के नाम, मूल्य और प्रकार को पुनः प्राप्त करने के लिए किया जाता है[दस्तावेज़संपत्ति.नाम](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [दस्तावेज़प्रॉपर्टी.मूल्य](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [दस्तावेज़प्रॉपर्टी.प्रकार](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) जो इनमें से एक लौटाता है[सम्पत्ती के प्रकार](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) गणना मान.
 
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए C# कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फ़ाइल में कस्टम प्रॉपर्टी हटाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
