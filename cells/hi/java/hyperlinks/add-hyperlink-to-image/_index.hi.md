---
title: Java छवि में हाइपरलिंक डालें या जोड़ें
description: एमएस एक्सेल के बिना Aspose.Cells लाइब्रेरी के साथ छवि में हाइपरलिंक कैसे डालें।
keywords: [Aspose Excel., Java Aspose.Cells., Image Hyperlink., Add a hyperlink to an image., How to Embed a Hyperlink in an Image., How do I hyperlink an image., Add a Link to an image., How to use an image as a link]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java में छवि में हाइपरलिंक जोड़ें" h2="छवि में हाइपरलिंक जोड़ने के लिए हाई-स्पीड Java लाइब्रेरी। यह Java का उपयोग करके एक्सेल फ़ाइल से निपटने के लिए एक पेशेवर सॉफ़्टवेयर समाधान है।" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके छवि में हाइपरलिंक जोड़ें" %}}

 मैं किसी छवि को हाइपरलिंक कैसे करूँ? Aspose.Cells for Java लाइब्रेरी के साथ, आप कोड की कुछ पंक्तियों के साथ प्रोग्रामेटिक रूप से आसानी से किसी छवि के लिए URL बना सकते हैं।[Aspose.Cells for Java](https://products.aspose.com/cells/java)सभी एक्सेल फ़ाइलों को बनाने, संशोधित करने, परिवर्तित करने, रेंडर करने और प्रिंट करने की क्षमता के साथ क्रॉस-प्लेटफ़ॉर्म एप्लिकेशन बनाने में सक्षम है। Java एक्सेल API न केवल स्प्रेडशीट प्रारूपों के बीच कनवर्ट करता है, बल्कि यह एक्सेल फ़ाइलों को छवियों, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT और अधिक के रूप में भी प्रस्तुत कर सकता है, इस प्रकार यह उद्योग-मानक प्रारूपों में दस्तावेज़ों का आदान-प्रदान करने के लिए एक आदर्श विकल्प है। आप इसका नवीनतम संस्करण सीधे यहाँ से डाउनलोड कर सकते हैं[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने Maven-आधारित प्रोजेक्ट में स्थापित करें।

{{% blocks/products/pf/agp/code-block title="कोष" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="true" %}}

```cs

<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Java में छवि में हाइपरलिंक जोड़ें" %}}

{{% blocks/products/pf/agp/text %}}

 डेवलपर्स के लिए कोड की कुछ पंक्तियों में ही छवि में हाइपरलिंक जोड़ना आसान है।

{{% /blocks/products/pf/agp/text %}}

1.  कार्यपुस्तिका वर्ग उदाहरण बनाएँ.
1.  कार्यपुस्तिका की पहली वर्कशीट तक पहुँचें.
1.  वर्कशीट का चित्र संग्रह ऑब्जेक्ट प्राप्त करें और "C4" सेल में एक चित्र जोड़ें।
1.  किसी छवि में हाइपरलिंक जोड़ें.
1.  हाइपरलिंक के लिए स्क्रीन टिप सेट करें.
1.  कार्यपुस्तिका को XLSX फ़ाइल के रूप में सहेजने के लिए Save विधि का उपयोग करें।

{{% blocks/products/pf/agp/code-block title="छवि में हाइपरलिंक जोड़ें - Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "5876dc77e47649b66bdb5deefb4b5639" "Landingpages-add-hyperlink-to-image.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Java लाइब्रेरी छवि के लिए हाइपरलिंक जोड़ने के लिए" %}}
{{% blocks/products/pf/agp/text %}}

 हम अपने Java पैकेज होस्ट करते हैं[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) रिपॉजिटरी. 'Aspose.Cells for Java' एक सामान्य JAR फ़ाइल है जिसमें बाइट-कोड होता है। कृपया अनुसरण करें[चरण-दर-चरण निर्देश](https://docs.aspose.com/cells/java/installation/) इसे अपने Java डेवलपर वातावरण में कैसे स्थापित करें।

{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या JSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए Java रनटाइम वातावरण के साथ संगत OS.
- Aspose.Cells for Java का नवीनतम संस्करण सीधे Maven से प्राप्त करें।

{{% /blocks/products/pf/agp/content %}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
