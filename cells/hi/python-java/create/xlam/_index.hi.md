---
title: XLAM बनाएँ - Python में XLAM फ़ाइल बनाएँ
description: Aspose एक्सेल. Python एक्सेल. Python Aspose.Cells के साथ XLAM फ़ाइल को जल्दी और आसानी से बनाएँ. Python एक्सेल लाइब्रेरी का उपयोग करके XLAM फ़ाइल बनाएँ. Python एक्सेल लाइब्रेरी में XLAM बनाएँ. Python XLAM क्रिएटर.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create XLAM file., Generate XLAM file in Python Excel Library., Create XLAM file using Python Excel Library., Write data to XLAM file via Python Excel Library., Create a XLAM file in Python Excel Library., Python Generate a XLAM file., Python XLAM Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Python एक्सेल लाइब्रेरी में XLAM फ़ाइल बनाएँ" h2="XLAM फ़ाइल बनाने के लिए हाई-स्पीड Python एक्सेल लाइब्रेरी। यह XLSX, PDF, और Python का उपयोग करके कई अन्य प्रारूपों को आयात और निर्यात करने के लिए एक पेशेवर सॉफ़्टवेयर समाधान है।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLAM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी का उपयोग करके XLAM फ़ाइल बनाएँ" %}}

 XLAM फ़ाइल कैसे बनाएँ? Aspose.Cells for Python via Java एक्सेल लाइब्रेरी के साथ, आप आसानी से कोड की कुछ पंक्तियों के साथ प्रोग्रामेटिक रूप से XLAM फ़ाइल बना सकते हैं।[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)सभी एक्सेल फाइलों को उत्पन्न करने, संशोधित करने, परिवर्तित करने, प्रस्तुत करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफॉर्म अनुप्रयोगों का निर्माण करने में सक्षम है। Python एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच परिवर्तित करता है, यह एक्सेल फाइलों को छवियों, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेजों का आदान-प्रदान करने के लिए एक आदर्श विकल्प है।

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी में XLAM कैसे बनाएं" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ ही पंक्तियों में डेटा प्रोसेसिंग के लिए विभिन्न रिपोर्टिंग अनुप्रयोगों के अंतर्गत XLAM फाइलें बनाना, लोड करना, संशोधित करना और परिवर्तित करना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  अपनी कोड फ़ाइल में asposecells आयात करें.
1.  कार्यपुस्तिका वर्ग उदाहरण बनाएँ.
1.  कार्यपुस्तिका की पहली वर्कशीट तक पहुँचें.
1. वर्कशीट के वांछित सेल(सेल्स) प्राप्त करें और सेल(सेल्स) में मान इनपुट करें।
1.  कार्यपुस्तिका को XLAM फ़ाइल के रूप में सहेजने के लिए Save विधि का उपयोग करें।

{{% blocks/products/pf/agp/code-block title="नमूना कोड दिखाता है कि Python एक्सेल लाइब्रेरी में XLAM फ़ाइल कैसे बनाई जाए।" offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.XLAM)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as XLAM file.
workbook.save("output.xlam")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python एक्सेल लाइब्रेरी XLAM फ़ाइल बनाने के लिए" %}}

{{% blocks/products/pf/agp/text %}}

आपके सिस्टम पर "Aspose.Cells for Python via Java" इंस्टॉल करने के लिए तीन विकल्प हैं। कृपया अपनी ज़रूरतों के हिसाब से कोई एक विकल्प चुनें और चरण-दर-चरण निर्देशों का पालन करें:

{{% /blocks/products/pf/agp/text %}}

1.  Aspose.Cells for Python via Java को Windows में स्थापित करें। देखें[प्रलेखन](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Linux में Aspose.Cells for Python via Java स्थापित करें। देखें[प्रलेखन](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  macOS में Aspose.Cells for Python via Java इंस्टॉल करें। देखें[प्रलेखन](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java प्लेटफ़ॉर्म-स्वतंत्र है और किसी भी प्लेटफ़ॉर्म (Windows, Linux और MacOS) पर उपयोग किया जा सकता है, बस सुनिश्चित करें कि सिस्टम में Java 1.8 या उच्चतर है,[Python](https://www.python.org/downloads/) 3.5 या अधिक.

{{% /blocks/products/pf/agp/text %}}

-  Java को स्थापित करें और इसे PATH पर्यावरण चर में जोड़ें, उदाहरण के लिए:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Aspose.Cells for Python via Java को यहां से इंस्टॉल करें<a href="https://pypi.org/project/aspose-cells/">pypi</a> , कमांड का उपयोग इस प्रकार करें:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLAM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlam/" >}}XLAM एक मैक्रो-सक्षम ऐड-इन फ़ाइल है जिसका उपयोग स्प्रेडशीट में नए फ़ंक्शन जोड़ने के लिए किया जाता है। ऐड-इन एक पूरक प्रोग्राम है जो अतिरिक्त कोड चलाता है और स्प्रेडशीट के लिए अतिरिक्त कार्यक्षमता प्रदान करता है। XLAM फ़ाइलें .xlam एक्सटेंशन के साथ संग्रहीत की जाती हैं। XLAM फ़ाइलें XML-आधारित फ़ाइलें हैं जो XLSM और XLSX फ़ाइल स्वरूपों के समान हैं और समग्र फ़ाइल आकार को कम करने के लिए ज़िप संपीड़न के साथ सहेजी जाती हैं।{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित स्प्रेडशीट जनरेशन" subTitle="आप नीचे सूचीबद्ध कुछ सहित अन्य Microsoft एक्सेल प्रारूप भी बना सकते हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft एक्सेल स्प्रेडशीट (विरासत)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="XML कार्यपुस्तिका खोलें" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="एक्सेल बाइनरी वर्कबुक" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="मैक्रो-सक्षम स्प्रेडशीट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="एक्सेल 97 - 2003 टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="एक्सेल टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="एक्सेल मैक्रो-सक्षम टेम्पलेट" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="अल्पविराम से अलग किये गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="टैब अलग किए गए मान" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="ओपनडॉक्यूमेंट स्प्रेडशीट" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="संवहन दस्तावेज़ स्वरूप" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
