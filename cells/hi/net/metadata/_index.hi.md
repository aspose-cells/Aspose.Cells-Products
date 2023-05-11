---
title: एक्सेल फ़ाइल मेटाडेटा via .NET C# प्रबंधित करें
description: C# कोड की केवल कुछ पंक्तियों के साथ एक्सेल फाइल मेटाडेटा देखें, जोड़ें, संपादित करें, निकालें या निकालें
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> प्रबंधित करें Excel फ़ाइल मेटाडेटा via .NET" h2="सर्वर साइड .NET एपीआई का उपयोग करके अंतर्निहित और कस्टम एक्सेल फ़ाइल गुणों को देखें, जोड़ें, अपडेट करें, हटाएं या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET एक्सेल API](/cells/hi/net/) सिस्टम-डिफ़ाइंड (बिल्ट-इन) गुणों जैसे शीर्षक, लेखक का नाम, दस्तावेज़ आँकड़े आदि के साथ-साथ उपयोगकर्ता-परिभाषित (कस्टम) गुणों को नाम-मूल्य जोड़ी के रूप में प्रबंधित करने का समर्थन करता है। वहाँ है[कार्यपुस्तिका वर्ग](https://reference.aspose.com/cells/net/aspose.cells/workbook) फ़ाइलों को लोड करने के लिए, और[वर्कशीट संग्रह](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) साथ ही वर्कशीट के संग्रह से संबंधित है[वर्कशीट वर्ग](https://reference.aspose.com/cells/net/aspose.cells/worksheet) एकल कार्यपत्रक का प्रतिनिधित्व करने के लिए। इन वर्गों के साथ, बिल्टइनडॉक्यूमेंटप्रॉपर्टीज, कस्टमडॉक्यूमेंटप्रॉपर्टीज मेटाडेटा प्रबंधन के लिए प्रक्रिया को सरल बनाता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="अंतर्निहित गुणों का प्रबंधन" %}}

 सिस्टम-परिभाषित गुणों के प्रबंधन के लिए, API प्रदान करता है[बिल्टइनडॉक्यूमेंटप्रॉपर्टीज](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , और प्रोग्रामर आसानी से एक अंतर्निहित संपत्ति तक पहुंच सकते हैं और इसके मूल्य को अपडेट कर सकते हैं। एप्लिकेशन की आवश्यकता के आधार पर, डेवलपर्स इंडेक्स या संपत्ति के नाम का उपयोग कर सकते हैं[दस्तावेज़ संपत्ति संग्रह](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# निर्मित गुण प्रबंधित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित गुणों का प्रबंधन" %}}

 उपयोगकर्ता-परिभाषित गुणों के प्रबंधन के लिए, API प्रदान करता है[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , और डेवलपर पहले से जोड़े गए गुणों तक आसानी से पहुंच सकते हैं और साथ ही नई संपत्तियां भी जोड़ सकते हैं। कस्टम गुण जोड़ने के लिए,[जोड़ें विधि](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) का[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) वर्ग संपत्ति जोड़ता है और एक के रूप में नई संपत्ति के लिए एक संदर्भ देता है[गुण। दस्तावेज़प्रॉपर्टी](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) वस्तु। DocumentProperty वर्ग का उपयोग दस्तावेज़ गुण के नाम, मान और प्रकार को पुनः प्राप्त करने के लिए किया जाता है[दस्तावेज़ संपत्ति। नाम](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [दस्तावेज़ संपत्ति। मूल्य](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [दस्तावेज़प्रॉपर्टी.टाइप](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) जो किसी एक को लौटाता है[सम्पत्ती के प्रकार](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) गणना मूल्य।
 
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए C# कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# एक्सेल फाइल में कस्टम प्रॉपर्टी को हटाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
