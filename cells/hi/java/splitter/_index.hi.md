---
title: Java में एक्सेल स्प्रेडशीट को वर्कशीट में विभाजित करें
description: Java स्रोत कोड जो बताते हैं कि Microsoft एक्सेल फाइलों को Java एक्सेल लाइब्रेरी का उपयोग करके कई दस्तावेजों में कैसे विभाजित किया जाए
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल फाइल स्प्लिटिंग via Java" h2="Java आधारित अनुप्रयोगों के भीतर एक्सेल स्प्रेडशीट को वर्कशीट में विभाजित करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
 विभिन्न प्रकार के परिदृश्य हैं, जब प्रत्येक छात्र के लिए एकल शीट के आवंटन के साथ छात्रों के डेटा वाली स्प्रेडशीट जैसी एक्सेल फ़ाइलों को विभाजित करने की आवश्यकता होती है। और प्रत्येक शीट को एक अलग फ़ाइल के रूप में छात्रवार विभाजित करने की आवश्यकता है। इसे स्वचालित करने के लिए via Java आवेदन,[Java एक्सेल API](/cells/hi/java/) एक्सेल दस्तावेज़ को शीटवार विभाजित करने के लिए है। समर्थित स्वरूपों में XLS, XLSX, XLSB, XLSM, ODS शामिल हैं।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल दस्तावेज़ को कई फाइलों में विभाजित करें" %}}

 एक्सेल फाइल को शीट में विभाजित करने का सबसे सरल तरीका है, सभी शीटों तक पहुंचें, प्रत्येक शीट के माध्यम से पुनरावृति करें और वांछित प्रारूप में एक-एक करके सहेजें। वर्कशीट लोड करने के लिए API प्रदान करता है[वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) कक्षा।[getWorksheets ()। GetCount ()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) विधि शीट्स की कुल संख्या प्राप्त करती है। प्रत्येक शीट के माध्यम से पुनरावृति करें और उपयोग करें[वर्कशीट्स प्राप्त करें ()। प्राप्त करें (शीटइंडेक्स)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)विशिष्ट शीट तक पहुँचने के लिए। उपयोग करके चयनित शीट डेटा को नए बनाए गए वर्कबुक क्लास ऑब्जेक्ट में ले जाएँ[कॉपी विधि](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). अंत में इसे आवश्यक फॉर्मेट में सेव करें।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल फाइल को विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल वर्कशीट को पैन में विभाजित करें" %}}

API एक्सेल वर्कशीट को अलग-अलग पैन में विभाजित करने की कार्यक्षमता भी प्रदान करता है। प्रक्रिया है, कार्यपुस्तिका वर्ग का उपयोग करके फ़ाइल लोड करें। अपनी अनुक्रमणिका प्रदान करके पहली वर्कशीट या किसी आवश्यक शीट का चयन करें। पैरामीटर के रूप में प्रासंगिक सेल इंडेक्स वाले सेटएक्टिवसेल को कॉल करें। और अंत में स्प्लिट () विधि को कॉल करके वर्कशीट विंडो को अलग-अलग पैन में विभाजित करें।

{{% blocks/products/pf/feature-page-code h3="Java एक्सेल शीट को फलक दृश्य में विभाजित करने के लिए कोड" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
