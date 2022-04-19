---
title: एक्सेल चार्ट बनाएं और C++ के माध्यम से छवियों में कनवर्ट करें
url: /hi/cpp/chart/
description: C++ लाइब्रेरी का उपयोग करके Microsoft Excel में चार्ट या आरेख बनाने और परिवर्तित करने के लिए C++ स्रोत कोड
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल चार्ट बनाएं और C++ के माध्यम से छवियों में कनवर्ट करें" h2="एक्सेल दस्तावेज़ चार्ट को छवियों में कनवर्ट करें और साथ ही C++ आधारित एप्लिकेशन के भीतर पाई, पिरामिड, लाइन और बबल चार्ट सहित चार्ट बनाएं।" >}}

{{% blocks/products/pf/feature-page-summary %}}

एक्सेल चार्ट का उपयोग करके, कोई भी बड़ी तस्वीर प्राप्त कर सकता है और सही निर्णय लेने के लिए आसानी से डेटा का विश्लेषण कर सकता है। [C++ एक्सेल लाइब्रेरी](/cells/cpp/) द्वारा सूचीबद्ध विभिन्न चार्ट बनाने का समर्थन करता है [एनम Aspose::Cells::चार्ट्स::चार्टटाइप
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) क्षेत्र, बार, पाई, पिरामिड, रेखा और बबल चार्ट सहित। इसके अलावा, चार्ट को छवियों में बदलने के लिए, API प्रदान करता है a [ToImage मेहतोद](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) आवश्यक छवि प्रारूप में।

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="एक्सेल चार्ट बनाएं" %}}

एक्सेल चार्ट बनाने की प्रक्रिया है, इसका एक उदाहरण बनाएं [आई वर्कबुक क्लास](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) और वांछित का चयन करें [कार्यपत्रक](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). चार्ट का उपयोग करके जोड़ें [विधि जोड़ें](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) चार्ट प्रकार सहित प्रासंगिक मापदंडों के साथ। इंडेक्स के माध्यम से चार्ट तक पहुंचें और [जोड़ें](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) चार्ट के लिए डेटा स्रोत।

{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल चार्ट बनाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="चार्ट को इमेज में बदलें" %}}


चार्ट प्रक्रिया को परिवर्तित करने के लिए, पहले उपरोक्त कोड का उपयोग करके प्रासंगिक प्रकार के चार्ट बनाएं या संबंधित शीट से इसे एक्सेस करें। छवि के लिए आउटपुट बचत पथ को परिभाषित करें और रूपांतरण के लिए ToImage विधि का उपयोग करें।

 
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल चार्ट बदलने के लिए कोड" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}