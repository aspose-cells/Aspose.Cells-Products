---
title: HTM बनाएँ - Python में HTM फ़ाइल बनाएँ
description:  Aspose Excel. Python Excel. Python Aspose.Cells के साथ जल्दी और आसानी से HTM फ़ाइल बनाएँ. Python Excel लाइब्रेरी का उपयोग करके HTM फ़ाइल बनाएँ. Python Excel लाइब्रेरी में HTM बनाएँ. Python HTM क्रिएटर.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create HTM file., Generate HTM file in Python Excel Library., Create HTM file using Python Excel Library., Write data to HTM file via Python Excel Library., Create a HTM file in Python Excel Library., Python Generate a HTM file., Python HTM Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Python एक्सेल लाइब्रेरी में HTM फ़ाइल बनाएँ" h2="HTM फ़ाइल बनाने के लिए हाई-स्पीड Python एक्सेल लाइब्रेरी। Python में उच्च-स्तरीय, प्लेटफ़ॉर्म स्वतंत्र सॉफ़्टवेयर विकसित करने के लिए हमारे एक्सेल रूपांतरण API का उपयोग करें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-net/" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी का उपयोग करके HTM फ़ाइल बनाएँ" %}}

 HTM फ़ाइल कैसे बनाएँ? Aspose.Cells for Python via NET एक्सेल लाइब्रेरी के साथ, आप आसानी से कोड की कुछ पंक्तियों के साथ प्रोग्रामेटिक रूप से HTM फ़ाइल बना सकते हैं।[Aspose.Cells for Python](https://pypi.org/project/aspose-cells-python/)सभी एक्सेल फाइलों को उत्पन्न करने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफॉर्म अनुप्रयोगों का निर्माण करने में सक्षम है। Python एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित करता है, यह एक्सेल फाइलों को छवियों, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प है।

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी में HTM कैसे बनाएं" %}}

{{% blocks/products/pf/agp/text %}}

डेवलपर्स के लिए डेटा प्रोसेसिंग के लिए विभिन्न रिपोर्टिंग अनुप्रयोगों के अंतर्गत कोड की कुछ ही पंक्तियों में HTM फाइलें बनाना, लोड करना, संशोधित करना और परिवर्तित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  कार्यपुस्तिका वर्ग उदाहरण बनाएँ.
1.  कार्यपुस्तिका की पहली वर्कशीट तक पहुँचें.
1. वर्कशीट के वांछित सेल(सेल्स) प्राप्त करें और सेल(सेल्स) में मान इनपुट करें।
1.  कार्यपुस्तिका को HTM फ़ाइल के रूप में सहेजने के लिए Save विधि का उपयोग करें।

{{% blocks/products/pf/agp/code-block title="नमूना कोड दिखाता है कि Python एक्सेल लाइब्रेरी में HTM फ़ाइल कैसे बनाई जाती है।" offSpacer="" %}}

```cs

from aspose import pycore
from aspose.cells import Workbook, SaveFormat, FileFormatType

# Create Workbook object.
workbook = Workbook()

# Access the first worksheet of the workbook.
worksheet = workbook.worksheets[0]

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.cells.get("A1").put_value("ColumnA")
worksheet.cells.get("B1").put_value("ColumnB")
worksheet.cells.get("A2").put_value("ValueA")
worksheet.cells.get("B2").put_value("ValueB")

# Save the workbook as HTM file.
workbook.save("output.htm")

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python HTM फ़ाइल बनाने के लिए एक्सेल लाइब्रेरी" %}}

हम अपने Python पैकेजों को PyPi रिपॉजिटरी में होस्ट करते हैं।

{{% blocks/products/pf/agp/text %}}
 Aspose.Cells for Python को यहां से इंस्टॉल करें<a href="https://pypi.org/project/aspose-cells-python/">pypi</a> , कमांड का उपयोग इस प्रकार करें:<code>$ pip install aspose-cells-python</code>.
{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/text %}}
 और आप इसका अनुसरण भी कर सकते हैं[चरण-दर-चरण निर्देश](https://docs.aspose.com/cells/python-net/getting-started/) अपने डेवलपर वातावरण में "Aspose.Cells for Python via .NET" स्थापित करने के तरीके पर।
{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python प्लेटफ़ॉर्म-स्वतंत्र API है और इसे किसी भी प्लेटफ़ॉर्म (Windows, लिनक्स) पर इस्तेमाल किया जा सकता है, बस सुनिश्चित करें कि सिस्टम में[Python](https://www.python.org/downloads/) 3.7 या अधिक.
 
{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTM" readMoreLink="https://docs.fileformat.com/web/htm/" >}}.htm एक्सटेंशन वाली फ़ाइलें Google क्रोम, इंटरनेट एक्सप्लोरर, फ़ायरफ़ॉक्स और कई अन्य जैसे वेब ब्राउज़र में प्रदर्शित करने के लिए वेब पेज बनाने के लिए हाइपरटेक्स्ट मार्कअप लैंग्वेज का प्रतिनिधित्व करती हैं। यह वर्ल्ड वाइड वेब (WWW) पर दूसरों द्वारा एक्सेस के लिए प्रकाशित किए जाने वाले स्थिर पेज बनाने के लिए मार्कअप को परिभाषित करता है। ये मार्कअप ब्राउज़र को बताते हैं कि वेब पेज की सामग्री को कैसे प्रदर्शित किया जाए। ऐसे पेजों में सादा पाठ, चित्र, अन्य पेजों के हाइपरलिंक, वीडियो और अन्य मीडिया जानकारी हो सकती है। जब कोई वेब पेज प्रकाशित होता है, तो आप उसके पेज स्रोत को देखकर उसके पीछे के मार्कअप कोड को देख सकते हैं। आधुनिक ब्राउज़र वेब पेज के प्रत्येक अनुभाग का निरीक्षण करने की अनुमति देते हैं जहाँ HTM स्रोत में प्रत्येक उप-विभाजन या मार्कअप तत्व विस्तृत होता है।{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित स्प्रेडशीट जनरेशन" subTitle="आप नीचे सूचीबद्ध कुछ सहित अन्य Microsoft एक्सेल प्रारूप भी बना सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xls/" name="XLS" description="Microsoft एक्सेल स्प्रेडशीट (विरासत)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsx/" name="XLSX" description="XML कार्यपुस्तिका खोलें" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsb/" name="XLSB" description="एक्सेल बाइनरी वर्कबुक" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsm/" name="XLSM" description="मैक्रो-सक्षम स्प्रेडशीट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlt/" name="XLT" description="एक्सेल 97 - 2003 टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltx/" name="XLTX" description="एक्सेल टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltm/" name="XLTM" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/csv/" name="CSV" description="अल्पविराम से अलग किये गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/tsv/" name="TSV" description="टैब अलग किए गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/pdf/" name="PDF" description="संवहन दस्तावेज़ स्वरूप" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/html/" name="HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
