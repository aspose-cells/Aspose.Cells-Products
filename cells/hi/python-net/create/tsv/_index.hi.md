---
title: TSV बनाएँ - Python में TSV फ़ाइल बनाएँ
description: Aspose एक्सेल. Python एक्सेल. Python Aspose.Cells के साथ TSV फ़ाइल को जल्दी और आसानी से बनाएँ. Python एक्सेल लाइब्रेरी का उपयोग करके TSV फ़ाइल बनाएँ. Python एक्सेल लाइब्रेरी में TSV बनाएँ. Python TSV क्रिएटर.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create TSV file., Generate TSV file in Python Excel Library., Create TSV file using Python Excel Library., Write data to TSV file via Python Excel Library., Create a TSV file in Python Excel Library., Python Generate a TSV file., Python TSV Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Python एक्सेल लाइब्रेरी में TSV फ़ाइल बनाएँ" h2="TSV फ़ाइल बनाने के लिए हाई-स्पीड Python एक्सेल लाइब्रेरी। Python में उच्च-स्तरीय, प्लेटफ़ॉर्म स्वतंत्र सॉफ़्टवेयर विकसित करने के लिए हमारे एक्सेल रूपांतरण API का उपयोग करें।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-net/" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी का उपयोग करके TSV फ़ाइल बनाएँ" %}}

TSV फ़ाइल कैसे बनाएँ? Aspose.Cells for Python NET एक्सेल लाइब्रेरी के माध्यम से, आप आसानी से कोड की कुछ पंक्तियों के साथ प्रोग्रामेटिक रूप से TSV फ़ाइल बना सकते हैं।[Aspose.Cells for Python](https://pypi.org/project/aspose-cells-python/)सभी एक्सेल फाइलों को उत्पन्न करने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफॉर्म अनुप्रयोगों का निर्माण करने में सक्षम है। Python एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित करता है, यह एक्सेल फाइलों को छवियों, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प है।

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी में TSV कैसे बनाएं" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ ही पंक्तियों में डेटा प्रोसेसिंग के लिए विभिन्न रिपोर्टिंग अनुप्रयोगों के अंतर्गत TSV फाइलें बनाना, लोड करना, संशोधित करना और परिवर्तित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  कार्यपुस्तिका वर्ग उदाहरण बनाएँ.
1.  कार्यपुस्तिका की पहली वर्कशीट तक पहुँचें.
1. वर्कशीट के वांछित सेल(सेल्स) प्राप्त करें और सेल(सेल्स) में मान इनपुट करें।
1.  कार्यपुस्तिका को TSV फ़ाइल के रूप में सहेजने के लिए Save विधि का उपयोग करें।

{{% blocks/products/pf/agp/code-block title="नमूना कोड दिखाता है कि Python एक्सेल लाइब्रेरी में TSV फ़ाइल कैसे बनाई जाए।" offSpacer="" %}}

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

# Save the workbook as TSV file.
workbook.save("output.tsv")

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी TSV फ़ाइल बनाने के लिए" %}}

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
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}टैब-सेपरेटेड वैल्यूज़ (TSV) फ़ाइल फ़ॉर्मेट सादे टेक्स्ट फ़ॉर्मेट में टैब से अलग किए गए डेटा को दर्शाता है। CSV के समान फ़ाइल फ़ॉर्मेट का उपयोग विभिन्न अनुप्रयोगों के बीच आयात और निर्यात करने के लिए संरचित तरीके से डेटा के संगठन के लिए किया जाता है। फ़ॉर्मेट का उपयोग मुख्य रूप से स्प्रेडशीट अनुप्रयोगों और डेटाबेस में डेटा आयात/निर्यात और विनिमय के लिए किया जाता है। TSV फ़ाइल में प्रत्येक रिकॉर्ड टेक्स्ट फ़ाइल की एक पंक्ति में समाहित होता है जहाँ प्रत्येक फ़ील्ड मान को टैब वर्ण द्वारा अलग किया जाता है। TSV फ़ाइल फ़ॉर्मेट के लिए मीडिया प्रकार टेक्स्ट/टैब-सेपरेटेड-वैल्यूज़ है।{{< /blocks/products/pf/agp/i18n/about-file-text >}}
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
