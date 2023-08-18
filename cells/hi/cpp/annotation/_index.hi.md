---
title: एक्सेल फ़ाइल एनोटेशन C++ के माध्यम से
description: C++ लाइब्रेरी के साथ एक्सेल और ओपनऑफिस स्प्रेडशीट की डेटा एनोटेशन टिप्पणियां जोड़ें या हटाएं।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>&reg;</sup> एक्सेल फ़ाइल एनोटेशन को C++ के माध्यम से प्रबंधित करें" h2="C++ आधारित अनुप्रयोगों के भीतर एनोटेशन या टिप्पणियों के लिए सरल नोट्स जोड़ें या हटाएं।" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ एक्सेल API](/cells/hi/cpp/) टिप्पणियों को जोड़ने, एक्सेस करने और हटाने के द्वारा सेल स्तर पर एनोटेशन प्रबंधित करने के लिए सहायता प्रदान करता है। API प्रदान करता है[मैंटिप्पणी](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) और[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) साथ ही[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)सभी पहलुओं में टिप्पणियों को संभालने के लिए। समर्थित एक्सेल प्रारूपों में ODS, XLS, XLSX, XLSB और XLSM शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल फ़ाइलें डेटा एनोटेशन" %}}
 वर्कशीट में टिप्पणियों में हेरफेर - एमएस एक्सेल में यह सीमित नहीं है कि एक शीट में कितनी टिप्पणियाँ हैं। कोई भी उतना ही सम्मिलित कर सकता है जितना अनुप्रयोग की आवश्यकता हो। टिप्पणियाँ सम्मिलित करने की प्रक्रिया है, बनाएँ[आईवर्कबुक](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) किसी मौजूदा फ़ाइल को लोड करने के लिए क्लास ऑब्जेक्ट का उपयोग करें और वर्कशीट का चयन करें जहां आप टिप्पणी जोड़ना चाहते हैं। GetComments() का उपयोग करके इसकी सभी टिप्पणियाँ प्राप्त करें। का उपयोग करके टिप्पणी जोड़ें[जोड़ना](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (घुसपैठ_ptr< Aspose::Cells::Systems::String > सेलनाम) विधि। सेल इंडेक्स प्राप्त करें और उपयोग करें[सेटनोट](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) टिप्पणियाँ सम्मिलित करने के लिए. इसके अलावा, API सभी टिप्पणियों को हटाने में सक्षम है। कुछ तरीके हैं[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) डिज़ाइनर स्प्रेडशीट में सभी टिप्पणियाँ साफ़ करने के लिए। इसके अतिरिक्त,[रिमूवएट](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(घुसपैठ_ptr< Aspose::Cells::Systems::String > नाम) एक निर्दिष्ट सूचकांक पर या निर्दिष्ट नाम के साथ तत्व को हटाने की विधि।

{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल फ़ाइल में टिप्पणियाँ जोड़ने के लिए कोड" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
