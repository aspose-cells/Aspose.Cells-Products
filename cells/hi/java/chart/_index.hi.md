---
title: एक्सेल चार्ट बनाएं और Java के माध्यम से छवियों में कनवर्ट करें

description: Java लाइब्रेरी का उपयोग करके Microsoft Excel में चार्ट या आरेख बनाने और परिवर्तित करने के लिए Java स्रोत कोड। 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel फ़ाइल चार्ट Java के माध्यम से रूपांतरण और निर्माण" h2="एक्सेल दस्तावेज़ चार्ट को छवियों में कनवर्ट करें और साथ ही Java आधारित एप्लिकेशन के भीतर सर्वर-साइड एपीआई का उपयोग करके विभिन्न चार्ट बनाएं।" >}}


{{% blocks/products/pf/feature-page-summary %}}

चार्ट के माध्यम से डेटा का विश्लेषण बड़ी तस्वीर दिखाता है और स्पष्ट अंतर्दृष्टि के साथ अधिक सूचित निर्णय लेना आसान है। [Java एक्सेल लाइब्रेरी](/cells/java/) द्वारा सूचीबद्ध विभिन्न चार्ट निर्माण का समर्थन करता है [चार्ट प्रकार](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) पाई, पिरामिड, रेखा और बबल चार्ट सहित। इसके अलावा, यह चार्ट को छवियों में भी परिवर्तित करता है। API प्रदान करता है [चार्ट वर्ग](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) एकल एक्सेल चार्ट का प्रतिनिधित्व करने के लिए।

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="एक्सेल चार्ट को इमेज में बदलें" %}}

जेपीजी, पीएनजी, टीआईएफएफ, बीएमपी आदि सहित चार्ट को छवियों में बदलने की प्रक्रिया है, का प्रयोग करें [वर्कबुक](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) एक्सेल फ़ाइल लोड करने के लिए कक्षा, प्रासंगिक का चयन करें [कार्यस्थल](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) प्रत्येक कार्यपत्रक में प्रत्येक चार्ट के माध्यम से चार्ट या पुनरावृति युक्त। परिभाषित करना [इमेजऑरप्रिंटविकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) और चार्ट की आउटपुट छवि का उपयोग करके प्रस्तुत करें [चार्ट.टूइमेज](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions))


{{% blocks/products/pf/feature-page-code h3="Java एक्सेल चार्ट को इमेज में बदलने के लिए कोड" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल में चार्ट बनाएं" %}}

एक्सेल API का उपयोग करके चार्ट बनाना सरल है, क्योंकि API विभिन्न प्रकार के चार्ट के लिए एक्सिस, चार्ट, चार्ट एरिया, चार्टडेटाटेबल, चार्टफ्रेम, चार्टपॉइंट, चार्टपॉइंटकोलेक्शन, चार्टकोलेक्शन इत्यादि जैसे विभिन्न वर्गों का सेट प्रदान करता है। प्रक्रिया है, वर्कबुक क्लास ऑब्जेक्ट बनाएं और इसकी इंडेक्स प्रदान करके पहले वर्कशीट या संबंधित शीट का चयन करें। चार्ट के डेटा स्रोत के लिए, का उपयोग करके वर्कशीट सेल में मान डालें [मूल्य ते करना](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) तरीका। चार्ट संग्रह संग्रह का उपयोग करें [विधि जोड़ें](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) चार्ट जोड़ने के लिए, चार्ट टाइप एन्यूमरेशन के साथ चार्ट के प्रकार को परिभाषित करें। चार्टकोलेक्शन संग्रह से नए चार्ट ऑब्जेक्ट को उसकी अनुक्रमणिका पास करके एक्सेस करें। उपयोग [श्रृंखला संग्रह](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) चार्ट के डेटा स्रोत को निर्दिष्ट करने के लिए चार्टिंग ऑब्जेक्ट।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल चार्ट बनाने के लिए कोड" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
