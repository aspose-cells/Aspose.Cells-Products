---
title: Aspose.Cells के माध्यम से पाई चार्ट कैसे जोड़ें
weight: 7700
limit:
description: पाई चार्ट जोड़ना सीखें.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /hi/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells के साथ पाई चार्ट जोड़ना सीखें" >}}

<p>
इस ट्यूटोरियल में, हम एक्सेल फ़ाइल में पाई चार्ट जोड़ेंगे।
</p>

<p>
 हम इसका उपयोग करके एक नई कार्यपुस्तिका बनाकर शुरुआत करेंगे<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells पुस्तकालय</a> और पाई चार्ट जोड़ें.
</p>

<br />
{{< app/cells/tutorial >}}
//पूर्वसारांश: पाई चार्ट जोड़ने का तरीका जानने के लिए कृपया निम्नलिखित कोड की जांच करें।
//ExStepSummary:0: निम्नलिखित कोड दिखाता है कि पाई चार्ट कैसे जोड़ें, श्रृंखला डेटा रेंज सेट करें और श्रेणी डेटा रेंज सेट करें।
//ExStepImage:0:step-1.png
//ExStepSummary:1: निम्नलिखित कोड दिखाता है कि लेजेंड को कैसे बंद किया जाए।
//ExStepImage:1:step-2.png
//ExStepSummary:2: निम्नलिखित कोड दिखाता है कि डेटा लेबल तक कैसे पहुंचें, श्रेणी के नाम चालू करें, प्रतिशत प्रारूप चालू करें और स्थिति निर्धारित करें।
//ExStepImage:2:step-3.png
//एक्सस्टार्ट
//पूर्व चरण:0-
Aspose.Cells का उपयोग करना;
Aspose.Cells का उपयोग करना।ड्राइंग;

कार्यपुस्तिका कार्यपुस्तिका = नई कार्यपुस्तिका();
वर्कशीट शीट = वर्कबुक.वर्कशीट्स[0];
शीट.नाम = "चार्टशीट";
Cells सेल = शीट.Cells;
कोशिकाएं["ए1"].मान = "फल";
सेल["ए2"].वैल्यू = "सेब";
सेल["ए3"].वैल्यू = "नारंगी";
सेल["ए4"].वैल्यू = "ब्लूबेरी";
सेल["A5"].वैल्यू = "कीवी";

सेल["बी1"].वैल्यू = "कीमत";
सेल["बी2"].मान = 10;
सेल["बी3"].मान = 5;
सेल["बी4"].मान = 20;
सेल["बी5"].मान = 8;

शीट.पेजसेटअप.प्रिंटग्रिडलाइन्स = सत्य;
शीट.पेजसेटअप.प्रिंटएरिया = "ए1:एफ20";

चार्टकलेक्शन चार्ट = शीट.चार्ट;

// पाई चार्ट जोड़ें, श्रृंखला डेटा रेंज सेट करें और श्रेणी डेटा रेंज सेट करें
int सूचकांक = शीट.चार्ट्स.जोड़ें(चार्टटाइप.पाई, 6, 0, 19, 5);
चार्ट चार्ट = शीट.चार्ट्स[सूचकांक];
Chart.NSseries.Add('B2:B5', true);
चार्ट.NSseries.CategoryData = "A2:A5";

//पूर्वचरण:1-
//लेजेंड बंद करें
चार्ट.ShowLegend = गलत;

//पूर्वचरण:2-
// डेटा लेबल तक पहुंचें, श्रेणी के नाम चालू करें, प्रतिशत प्रारूप चालू करें और स्थिति निर्धारित करें
डेटालेबल्स डेटालेबल्स = चार्ट.एनएसरीज[0].डेटलेबल्स;
dataLabels.ShowCategoryName = सत्य;
dataLabels.ShowPercentage = सत्य;
dataLabels.Position = LabelPositionType.OutsideEnd;

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