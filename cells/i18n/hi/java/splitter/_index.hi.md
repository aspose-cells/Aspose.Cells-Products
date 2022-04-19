---
title: एक्सेल स्प्रेडशीट को वर्कशीट में Java में विभाजित करें
url: /hi/java/splitter/
description: Java स्रोत कोड जो Java एक्सेल लाइब्रेरी का उपयोग करके Microsoft Excel फ़ाइलों को एकाधिक दस्तावेज़ों में विभाजित करने का तरीका बताते हैं
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइल Java के माध्यम से विभाजित करना" h2="एक्सेल स्प्रैडशीट को Java आधारित एप्लिकेशन के भीतर वर्कशीट में विभाजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
विभिन्न प्रकार के परिदृश्य हैं, जब प्रत्येक छात्र के लिए एकल शीट के आवंटन के साथ छात्रों के डेटा वाली स्प्रेडशीट की तरह एक्सेल फाइलों को विभाजित करने की आवश्यकता होती है। और प्रत्येक शीट को छात्रवार एक अलग फाइल के रूप में विभाजित करने की आवश्यकता है। इसे Java एप्लिकेशन के माध्यम से स्वचालित करने के लिए, [Java एक्सेल API](/cells/java/) एक्सेल दस्तावेज़ को शीटवार विभाजित करने के लिए है। समर्थित स्वरूपों में XLS, XLSX, XLSB, XLSM, ODS शामिल हैं। 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल दस्तावेज़ को कई फाइलों में विभाजित करें" %}}

एक्सेल फ़ाइल को शीट में विभाजित करने का सबसे सरल तरीका है, सभी शीट तक पहुँचें, प्रत्येक शीट के माध्यम से पुनरावृति करें और एक-एक करके वांछित प्रारूप में सहेजें। कार्यपत्रक लोड करने के लिए, API प्रदान करता है [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) कक्षा। [गेटवर्कशीट्स ()। गेटकाउंट ()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) विधि चादरों की कुल संख्या प्राप्त करती है। प्रत्येक शीट के माध्यम से पुनरावृति करें और उपयोग करें [गेटवर्कशीट्स ()। प्राप्त करें (शीटइंडेक्स)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) विशिष्ट शीट तक पहुँचने के लिए। चयनित शीट डेटा का उपयोग करके नव निर्मित वर्कबुक क्लास ऑब्जेक्ट में ले जाएँ [कॉपी विधि](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)) अंत में इसे आवश्यक प्रारूप में सहेजें।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फाइलों को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को पैन में विभाजित करें" %}}

API एक्सेल वर्कशीट को अलग-अलग पैन में विभाजित करने की कार्यक्षमता भी प्रदान करता है। प्रक्रिया है, कार्यपुस्तिका वर्ग का उपयोग करके फ़ाइल लोड करें। इसकी अनुक्रमणिका प्रदान करके पहले वर्कशीट या किसी आवश्यक शीट का चयन करें। पैरामीटर के रूप में प्रासंगिक सेल इंडेक्स वाले सेटएक्टिवसेल को कॉल करें। और अंत में स्प्लिट () विधि को कॉल करके वर्कशीट विंडो को अलग-अलग पैन में विभाजित करें।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल शीट को पेन व्यू में विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}