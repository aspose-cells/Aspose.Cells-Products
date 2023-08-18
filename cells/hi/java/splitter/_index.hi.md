---
title: Java में एक्सेल स्प्रेडशीट को वर्कशीट में विभाजित करें
description: Java स्रोत कोड जो बताते हैं कि Java एक्सेल लाइब्रेरी का उपयोग करके Microsoft एक्सेल फाइलों को कई दस्तावेजों में कैसे विभाजित किया जाए
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल विभाजन via Java" h2="एक्सेल स्प्रेडशीट को Java आधारित अनुप्रयोगों के भीतर वर्कशीट में विभाजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
 विभिन्न प्रकार के परिदृश्य होते हैं, जब एक्सेल फ़ाइलों को एक स्प्रेडशीट की तरह विभाजित करने की आवश्यकता होती है जिसमें प्रत्येक छात्र के लिए एकल शीट के आवंटन के साथ छात्रों का डेटा होता है। और प्रत्येक शीट को छात्रवार एक अलग फ़ाइल के रूप में विभाजित करने की आवश्यकता है। इसे स्वचालित करने के लिए via Java एप्लिकेशन,[Java एक्सेल API](/cells/hi/java/) एक्सेल दस्तावेज़ को शीटवार विभाजित करने के लिए है। समर्थित प्रारूपों में XLS, XLSX, XLSB, XLSM, ODS शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल दस्तावेज़ को एकाधिक फ़ाइलों में विभाजित करें" %}}

एक्सेल फ़ाइल को शीट में विभाजित करने का सबसे सरल तरीका है, सभी शीटों तक पहुंचें, प्रत्येक शीट के माध्यम से पुनरावृत्त करें और वांछित प्रारूप में एक-एक करके सहेजें। वर्कशीट लोड करने के लिए API उपलब्ध कराता है[वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) कक्षा।[गेटवर्कशीट्स().गेटकाउंट()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) विधि से शीटों की कुल संख्या प्राप्त होती है। प्रत्येक शीट को दोहराएँ और उपयोग करें[getवर्कशीट्स().get(शीटइंडेक्स)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) विशिष्ट शीट तक पहुँचने के लिए। का उपयोग करके चयनित शीट डेटा को नव निर्मित वर्कबुक क्लास ऑब्जेक्ट में ले जाएँ[प्रतिलिपि विधि](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). अंत में इसे आवश्यक प्रारूप में सहेजें।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फाइलों को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को पैन में विभाजित करें" %}}

API एक्सेल वर्कशीट को विभिन्न पैन में विभाजित करने की कार्यक्षमता भी प्रदान करता है। प्रक्रिया है, वर्कबुक क्लास का उपयोग करके फ़ाइल लोड करें। पहली वर्कशीट या किसी आवश्यक शीट का सूचकांक प्रदान करके उसका चयन करें। पैरामीटर के रूप में प्रासंगिक सेल इंडेक्स वाले सेटएक्टिवसेल को कॉल करें। और अंत में स्प्लिट() विधि को कॉल करके वर्कशीट विंडो को अलग-अलग पैन में विभाजित करें।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल शीट को फलक दृश्य में विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
