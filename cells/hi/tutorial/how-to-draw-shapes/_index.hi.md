---
title: Aspose.Cells के माध्यम से आकृतियाँ कैसे जोड़ें
weight: 7700
limit:
description: आकृतियाँ जोड़ना सीखें.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /hi/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells के साथ आकृतियाँ जोड़ना सीखें" >}}

<p>
इस ट्यूटोरियल में, हम एक्सेल फ़ाइल में आकृतियाँ जोड़ेंगे।
</p>

<p>
 हम इसका उपयोग करके एक नई कार्यपुस्तिका बनाकर शुरुआत करेंगे<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells पुस्तकालय</a> और आकृतियाँ जोड़ें.
</p>

<br />
{{< app/cells/tutorial >}}
//पूर्वसारांश: आकृतियाँ जोड़ने का तरीका जानने के लिए कृपया निम्नलिखित कोड की जाँच करें।
//ExStepSummary:0: निम्नलिखित कोड दिखाता है कि आयत आकार कैसे जोड़ें।
//ExStepImage:0:step-1.png
//ExStepSummary:1: निम्नलिखित कोड दिखाता है कि लाइन आकार कैसे जोड़ें।
//ExStepImage:1:step-2.png
//ExStepSummary:2: निम्नलिखित कोड दिखाता है कि अंडाकार आकार कैसे जोड़ा जाए।
//ExStepImage:2:step-3.png
//एक्सस्टार्ट
//पूर्व चरण:0-
Aspose.Cells का उपयोग करना;
Aspose.Cells का उपयोग करना।ड्राइंग;





कार्यपुस्तिका कार्यपुस्तिका = नई कार्यपुस्तिका();
वर्कशीट शीट = वर्कबुक.वर्कशीट्स[0];
शीट.पेजसेटअप.प्रिंटग्रिडलाइन्स = सत्य;
शीट.पेजसेटअप.प्रिंटएरिया = "ए1:एफ20";

आकारसंग्रह आकृतियाँ = शीट.आकृतियाँ;

//आयत आकार जोड़ें
आकार.जोड़ेंआयताकार(1, 0, 1, 0, 100, 150);

//पूर्वचरण:1-
// लाइन आकार जोड़ें
आकार.ऐडलाइन(8, 0, 1, 0, 100, 150);

//पूर्वचरण:2-
//अंडाकार आकार जोड़ें
आकार.अंडाकार जोड़ें(13, 0, 1, 0, 100, 150);

//पूर्व चरण:0-
कार्यपुस्तिका
//एक्सएंड
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Aspose.Cells की स्थापना</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells संपादक</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}