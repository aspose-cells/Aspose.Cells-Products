---
title: C++ के माध्यम से एक्सेल फ़ाइल एनोटेशन
url: /hi/cpp/annotation/
description: C++ लाइब्रेरी के साथ Excel और OpenOffice स्प्रैडशीट की डेटा एनोटेशन टिप्पणियां जोड़ें या निकालें.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel फ़ाइल एनोटेशन को C++ के माध्यम से प्रबंधित करें" h2="C++ आधारित एप्लिकेशन में एनोटेशन या टिप्पणियों के लिए साधारण नोट जोड़ें या निकालें।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ एक्सेल API](/cells/cpp/) टिप्पणियों को जोड़ने, एक्सेस करने और हटाने के द्वारा सेल स्तर पर एनोटेशन प्रबंधित करने के लिए सहायता प्रदान करता है। API प्रदान करता है [IComment](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) और [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) साथ ही [GetIComments ()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) सभी पहलुओं में टिप्पणियों को संभालने के लिए। समर्थित एक्सेल प्रारूपों में ओडीएस, एक्सएलएस, एक्सएलएसएक्स, एक्सएलएसबी और एक्सएलएसएम शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल डेटा एनोटेशन" %}}
वर्कशीट में टिप्पणियों में हेरफेर - यह सीमित नहीं है कि एमएस एक्सेल में एक शीट में कितनी टिप्पणियां हैं। आवेदन पत्र की आवश्यकता के अनुसार कोई भी उतना ही सम्मिलित कर सकता है। टिप्पणियाँ डालने की प्रक्रिया है, create [आई वर्कबुक](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) क्लास ऑब्जेक्ट किसी मौजूदा फ़ाइल को लोड करने के लिए और वर्कशीट का चयन करें जहाँ आप टिप्पणी जोड़ना चाहते हैं। GetComments() का उपयोग करके इसकी सभी टिप्पणियां प्राप्त करें। का उपयोग करके टिप्पणी जोड़ें [जोड़ें](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(घुसपैठ_ptr < Aspose::Cells::Systems::String > सेलनाम) विधि। सेल इंडेक्स प्राप्त करें और उपयोग करें [सेट नोट](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) टिप्पणियाँ डालने के लिए। इसके अलावा, API सभी टिप्पणियों को हटाने में सक्षम है। कुछ तरीके हैं [स्पष्ट टिप्पणियाँ ()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) डिज़ाइनर स्प्रेडशीट में सभी टिप्पणियों को साफ़ करने के लिए। इसके अलावा, [निकालेंएट](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(घुसपैठ_ptr< Aspose::Cells::Systems::String > नाम) एक निर्दिष्ट सूचकांक पर या निर्दिष्ट नाम के साथ तत्व को हटाने के लिए विधि।

{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल फ़ाइल में टिप्पणियाँ जोड़ने के लिए कोड" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}