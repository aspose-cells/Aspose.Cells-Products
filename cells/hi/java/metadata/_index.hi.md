---
title: एक्सेल फ़ाइल मेटाडेटा via Java प्रबंधित करें
description: Java कोड की कुछ पंक्तियों के साथ एक्सेल फ़ाइलों के मेटाडेटा को देखें, जोड़ें, संपादित करें, हटाएं या निकालें
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल मेटाडेटा via Java प्रबंधित करें" h2="सर्वर साइड Java एपीआई का उपयोग करके कस्टम और अंतर्निहित एक्सेल फ़ाइल गुणों को देखें, जोड़ें, अपडेट करें, हटाएं या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java एक्सेल API](/cells/hi/java/) अंतर्निहित (सिस्टम-परिभाषित) गुणों जैसे शीर्षक, लेखक का नाम, दस्तावेज़ आँकड़े आदि के साथ-साथ नाम/मूल्य जोड़ी के रूप में कस्टम (उपयोगकर्ता-परिभाषित) गुणों के प्रबंधन का समर्थन करता है। वहाँ है[कार्यपुस्तिका कक्षा](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) फ़ाइलें लोड करने के लिए, और[वर्कशीट संग्रह](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) कार्यपत्रकों के संग्रहण के साथ-साथ कार्य करता है[वर्कशीट क्लास](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) एकल वर्कशीट का प्रतिनिधित्व करने के लिए। बिल्टइन और कस्टम प्रॉपर्टीज तक पहुंचने के लिए, बिल्टइनडॉक्यूमेंटप्रॉपर्टीज, कस्टमडॉक्यूमेंटप्रॉपर्टीज मेटाडेटा प्रबंधन के लिए प्रक्रिया को सरल बनाता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="सिस्टम परिभाषित गुणों का प्रबंधन" %}}

 अंतर्निहित संपत्तियों के प्रबंधन के लिए, API प्रदान करता है[बिल्टइनडॉक्यूमेंटप्रॉपर्टीज़](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) और प्रोग्रामर आसानी से अंतर्निहित संपत्ति तक पहुंच सकते हैं और उसके मूल्य को अपडेट कर सकते हैं। एप्लिकेशन की आवश्यकता के आधार पर, डेवलपर्स इंडेक्स या प्रॉपर्टी नाम का उपयोग कर सकते हैं[दस्तावेज़संपत्ति संग्रह](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="सिस्टम परिभाषित गुणों को प्रबंधित करने के लिए Java कोड" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="कस्टम परिभाषित मेटाडेटा जोड़ें और निकालें" %}}

कस्टम संपत्तियों को संभालने के लिए, API प्रदान करता है[कस्टम दस्तावेज़ गुण](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , और डेवलपर्स मौजूदा संपत्तियों तक आसानी से पहुंच सकते हैं और साथ ही नई संपत्तियों का उपयोग भी कर सकते हैं[विधि जोड़ें](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) का[कस्टमडॉक्यूमेंटप्रॉपर्टीकलेक्शन](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) क्लास प्रॉपर्टी जोड़ता है और नई प्रॉपर्टी के लिए एक संदर्भ लौटाता है[गुण.दस्तावेज़संपत्ति](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) वस्तु। DocumentProperty वर्ग का उपयोग दस्तावेज़ संपत्ति के नाम, मूल्य और प्रकार को पुनः प्राप्त करने के लिए किया जाता है[दस्तावेज़संपत्ति.नाम](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [दस्तावेज़प्रॉपर्टी.मूल्य](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [दस्तावेज़प्रॉपर्टी.प्रकार](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) जो इनमें से एक लौटाता है[सम्पत्ती के प्रकार](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) गणना मान.
 
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल में मेटाडेटा जोड़ने के लिए Java कोड" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फ़ाइल में कस्टम प्रॉपर्टी को हटाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
