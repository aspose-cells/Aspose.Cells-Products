---
title: Aspose.Cells के माध्यम से टेक्स्टबॉक्स कैसे जोड़ें
weight: 7700
limit:
description: जानें कि टेक्स्टबॉक्स कैसे जोड़ें.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /hi/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="जानें कि Aspose.Cells के साथ टेक्स्टबॉक्स कैसे जोड़ें" >}}

<p>
इस ट्यूटोरियल में, हम एक्सेल फ़ाइल में टेक्स्टबॉक्स जोड़ेंगे।
</p>

<p>
 हम इसका उपयोग करके एक नई कार्यपुस्तिका बनाकर शुरुआत करेंगे<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells पुस्तकालय</a> और टेक्स्टबॉक्स जोड़ें।
</p>

<br />
{{< app/cells/tutorial >}}
//पूर्वसारांश: टेक्स्टबॉक्स जोड़ने का तरीका जानने के लिए कृपया निम्नलिखित कोड की जाँच करें।
//ExStepSummary:0: निम्नलिखित कोड दिखाता है कि टेक्स्टबॉक्स कैसे जोड़ें और टेक्स्ट कैसे सेट करें।
//ExStepImage:0:step-1.png
//ExStepSummary:1: निम्नलिखित कोड दिखाता है कि टेक्स्ट का रंग कैसे बदला जाए।
//ExStepImage:1:step-2.png
//ExStepSummary:2: निम्नलिखित कोड दिखाता है कि टेक्स्टबॉक्स के रोटेशन कोण को कैसे बदला जाए।
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

// टेक्स्टबॉक्स जोड़ें और टेक्स्ट सेट करें
टेक्स्टबॉक्स टेक्स्टबॉक्स = आकार.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET एक प्रोग्रामिंग क्लास लाइब्रेरी है जो सॉफ्टवेयर डेवलपर्स को अपने स्वयं के अनुप्रयोगों के भीतर स्प्रेडशीट फ़ाइलों में हेरफेर और प्रक्रिया करने की अनुमति देती है।";

//पूर्वचरण:1-
// टेक्स्ट का रंग बदलें
टेक्स्टबॉक्स.फ़ॉन्ट.रंग = रंग.नीला;

//पूर्वचरण:2-
// टेक्स्टबॉक्स का रोटेशन कोण बदलें
textBox.RotationAngle = 90;

//पूर्व चरण:0-

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