---
title: एक्सेल फ़ाइल मेटाडेटा via Java प्रबंधित करें
description: Java कोड की केवल कुछ पंक्तियों के साथ एक्सेल फाइल मेटाडेटा देखें, जोड़ें, संपादित करें, निकालें या निकालें
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> प्रबंधित करें Excel फ़ाइल मेटाडेटा via Java" h2="सर्वर साइड Java एपीआई का उपयोग करके कस्टम और बिल्ट-इन एक्सेल फ़ाइल गुणों को देखें, जोड़ें, अपडेट करें, हटाएं या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java एक्सेल API](/cells/hi/java/) बिल्ट-इन (सिस्टम-डिफ़ाइंड) गुणों जैसे कि शीर्षक, लेखक का नाम, दस्तावेज़ आँकड़े आदि के साथ-साथ नाम/वैल्यू पेयर के रूप में कस्टम (यूज़र-डिफ़ाइंड) प्रॉपर्टी के प्रबंधन का समर्थन करता है। वहाँ है[कार्यपुस्तिका वर्ग](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) फ़ाइलों को लोड करने के लिए, और[वर्कशीट संग्रह](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) साथ ही वर्कशीट के संग्रह से संबंधित है[वर्कशीट वर्ग](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) एकल कार्यपत्रक का प्रतिनिधित्व करने के लिए। बिल्टइन और कस्टम गुणों तक पहुँचने के लिए, बिल्टइनडॉक्यूमेंटप्रॉपर्टीज़, कस्टमडॉक्यूमेंटप्रॉपर्टीज़ मेटाडेटा प्रबंधन के लिए प्रक्रिया को सरल बनाता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="प्रबंधन प्रणाली परिभाषित गुण" %}}

 अंतर्निहित संपत्तियों के प्रबंधन के लिए, API प्रदान करता है[बिल्टइनडॉक्यूमेंटप्रॉपर्टीज](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) , और प्रोग्रामर आसानी से एक अंतर्निहित संपत्ति तक पहुंच सकते हैं और इसके मूल्य को अपडेट कर सकते हैं। एप्लिकेशन की आवश्यकता के आधार पर, डेवलपर्स इंडेक्स या संपत्ति के नाम का उपयोग कर सकते हैं[दस्तावेज़ संपत्ति संग्रह](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="सिस्टम परिभाषित गुणों को प्रबंधित करने के लिए Java कोड" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित मेटाडेटा जोड़ें और निकालें" %}}

कस्टम गुणों को संभालने के लिए, API प्रदान करता है[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , और डेवलपर आसानी से मौजूदा संपत्तियों तक पहुंच सकते हैं और साथ ही नई संपत्तियों का उपयोग करके जोड़ सकते हैं[विधि जोड़ें](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) का[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) वर्ग संपत्ति जोड़ता है और एक के रूप में नई संपत्ति के लिए एक संदर्भ देता है[गुण। दस्तावेज़प्रॉपर्टी](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) वस्तु। DocumentProperty वर्ग का उपयोग दस्तावेज़ गुण के नाम, मान और प्रकार को पुनः प्राप्त करने के लिए किया जाता है[दस्तावेज़ संपत्ति। नाम](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [दस्तावेज़ संपत्ति। मूल्य](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [दस्तावेज़प्रॉपर्टी.टाइप](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) जो किसी एक को लौटाता है[सम्पत्ती के प्रकार](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) गणना मूल्य।
 
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए Java कोड" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फ़ाइल में कस्टम संपत्ति को हटाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
