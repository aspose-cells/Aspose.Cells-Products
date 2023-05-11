---
title: एक्सेल चार्ट बनाएं और छवियों में कनवर्ट करें via Java
description:  Java स्रोत कोड Microsoft एक्सेल में Java लाइब्रेरी का उपयोग करके चार्ट या आरेख बनाने और परिवर्तित करने के लिए।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल चार्ट रूपांतरण और निर्माण via Java" h2="Java आधारित अनुप्रयोगों के भीतर सर्वर-साइड एपीआई का उपयोग करके एक्सेल दस्तावेज़ चार्ट को छवियों में बदलें और साथ ही विभिन्न चार्ट बनाएं।" >}}


{{% blocks/products/pf/feature-page-summary %}}

 चार्ट के माध्यम से डेटा का विश्लेषण बड़ी तस्वीर दिखाता है और स्पष्ट अंतर्दृष्टि के साथ अधिक सूचित निर्णय लेना आसान होता है।[Java एक्सेल लाइब्रेरी](/cells/hi/java/) द्वारा सूचीबद्ध विभिन्न चार्ट निर्माण को चित्रित करने का समर्थन करता है[चार्ट प्रकार](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) पाई, पिरामिड, लाइन और बबल चार्ट सहित। इसके अलावा, यह चार्ट को छवियों में भी परिवर्तित करता है। API एक प्रदान करता है[चार्ट वर्ग](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)एकल एक्सेल चार्ट का प्रतिनिधित्व करने के लिए।

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="एक्सेल चार्ट को छवियों में बदलें" %}}

 जेपीजी, PNG, TIFF, BMP आदि सहित चार्ट को छवियों में बदलने की प्रक्रिया है, इसका उपयोग करें[वर्कबुक](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) कक्षा एक्सेल फ़ाइल लोड करने के लिए, प्रासंगिक का चयन करें[वर्कशीट](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) चार्ट युक्त या प्रत्येक वर्कशीट में प्रत्येक चार्ट के माध्यम से पुनरावृति। परिभाषित करना[छवि या प्रिंट विकल्प](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) और उपयोग करके चार्ट की आउटपुट छवि प्रस्तुत करें[चार्ट.टूइमेज](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="एक्सेल चार्ट को छवि में बदलने के लिए Java कोड" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="एक्सेल फाइल में चार्ट बनाएं" %}}

 एक्सेल API का उपयोग करके चार्ट बनाना सरल है, क्योंकि API विभिन्न प्रकार के चार्ट के लिए एक्सिस, चार्ट, चार्टएरिया, चार्टडेटाटेबल, चार्टफ्रेम, चार्टपॉइंट, चार्टपॉइंटकलेक्शन, चार्टकोलेक्शन आदि जैसे विभिन्न वर्गों का सेट प्रदान करता है। प्रक्रिया है, वर्कबुक क्लास ऑब्जेक्ट बनाएं और इसकी अनुक्रमणिका प्रदान करके पहली वर्कशीट या प्रासंगिक शीट का चयन करें। चार्ट के डेटा स्रोत के लिए, वर्कशीट सेल का उपयोग करके मान डालें[मूल्य ते करना](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)तरीका। चार्टकोलेक्शन संग्रह का प्रयोग करें[विधि जोड़ें](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) चार्ट जोड़ने के लिए, चार्टटाइप गणना के साथ चार्ट के प्रकार को परिभाषित करें। नए चार्ट ऑब्जेक्ट को चार्टकोलेक्शन संग्रह से उसके इंडेक्स को पास करके एक्सेस करें। उपयोग[श्रृंखला संग्रह](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) चार्ट के डेटा स्रोत को निर्दिष्ट करने के लिए चार्टिंग ऑब्जेक्ट।

{{% blocks/products/pf/feature-page-code h3="एक्सेल चार्ट बनाने के लिए Java कोड" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
