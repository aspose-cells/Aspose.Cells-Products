---
title: C++ के माध्यम से Microsoft Excel फ़ाइल रूपांतरण 
url: /hi/cpp/conversion/
description: एक्सेल एक्सएलएस, एक्सएलएसएक्स, ओडीएस, सीएसवी को पीडीएफ, एक्सपीएस, एचटीएमएल, जेपीईजी और अन्य प्रारूपों में C++ कोड की कुछ पंक्तियों के साथ कनवर्ट करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> एक्सेल दस्तावेज़ रूपांतरण C++ के माध्यम से" h2="Microsoft<sup>&reg;</sup> एक्सेल फाइलों को स्प्रेडशीट, वेब, इमेज और फिक्स्ड-लेआउट फॉर्मेट के रूप में सेव करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
किसी भी स्प्रेडशीट कनवर्टर एप्लिकेशन या समाधान के लिए, **C++ एक्सेल लाइब्रेरी** एक्सएलएसएक्स, एक्सएलएस, एक्सएलएसएम, एक्सएलएसबी, एक्सएलटीएक्स, एक्सएलटीएम, सीएसवी, स्प्रेडशीटएमएल, ओडीएस सहित कई फाइलों को संभालने के दौरान कोडिंग, ऑटोमेशन और रूपांतरण प्रक्रियाओं को गति देता है। यह **एक्सेल को पीडीएफ**, एक्सपीएस, एचटीएमएल, एमएचटीएमएल, प्लेन टेक्स्ट और जेपीजी, टीआईएफएफ, पीएनजी, बीएमपी और एसवीजी जैसी लोकप्रिय छवियों में बदलने की भी अनुमति देता है।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="माइक्रोसॉफ्ट एक्सेल प्रारूपों का अंतर-रूपांतरण" %}}
स्प्रैडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक स्प्रैडशीट लोड करने की आवश्यकता होती है जिसका उदाहरण: [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) सूचक और वांछित प्रारूप में वापस सहेजना [बचाना](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) उसकि विधि [आई वर्कबुक क्लास](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल फ़ाइल प्रारूप रूपांतरण के लिए उदाहरण कोड" %}}

```cs

// स्रोत एक्सेल प्रारूप लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// आवश्यक आउटपुट स्वरूप में सहेजें।
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="अनुपालन स्तर सेटिंग्स के साथ एक्सेल प्रारूपों को पीडीएफ में बदलें" %}}
C++ एक्सेल ऑटोमेशन API कार्यपुस्तिकाओं के पीडीएफ में रूपांतरण के साथ-साथ अनुपालन स्तर और निर्माण तिथि की समर्थन सेटिंग का समर्थन करता है। डेवलपर्स उपयोग कर सकते हैं [आईपीडीएफसेवविकल्प](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) साथ में [Aspose::Cells::रेंडरिंग](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) पीडीएफ अनुपालन सेट करने के लिए। रूपांतरण के लिए, API PdfSaveOptions को पैरामीटर और निर्दिष्ट आउटपुट फ़ाइल पथ के रूप में सहेजें विधि। 
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल से पीडीएफ रूपांतरण के लिए नमूना कोड" %}}

```cs
// नमूना एक्सेल फ़ाइल लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// पीडीएफ सेव ऑप्शन ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// अनुपालन को PDF/A-1b पर सेट करें।
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// या पीडीएफ अनुपालन_पीडीएफए1ए 
// सामान्य PDF के लिए यह होगा PdfCompliance_None

// एक्सेल डॉक्यूमेंट को पीडीएफ फॉर्मेट में सेव करें
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को इमेज में सेव करें" %}}
**C++ एक्सेल पार्सर** में छवियों के रूप में डेटा निर्यात करने की क्षमता है। प्रत्येक कार्यपत्रक को बीएमपी, जेपीईजी, पीएनजी और जीआईएफ सहित विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, जिसे द्वारा निर्धारित किया गया है [प्रतिपादन :: IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). किसी भी **एक्सेल को इमेज में बदलें** मामले के लिए, लिंक से प्रासंगिक मामले का चयन करें।
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल से छवि रूपांतरण के लिए कोड" %}}

```cs
// आउटपुट निर्देशिका पथ।
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// एक्सएलएसएक्स लोड करें।
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// पहले वर्कशीट तक पहुँचें।
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// छवि या प्रिंट विकल्प ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// छवि प्रारूप निर्दिष्ट करें। नीचे कोड जेपीईजी के लिए है
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// जीआईएफ, बीएमपी और पीएनजी जैसी अन्य छवियों के लिए क्रमशः GetGif (), GetBmp () और GetPng () का उपयोग कर सकते हैं 

// क्षैतिज और लंबवत संकल्प निर्दिष्ट करें
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// निर्दिष्ट छवि या प्रिंट विकल्पों के संबंध में शीट को प्रस्तुत करें।
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// पृष्ठ संख्या प्राप्त करें।
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// स्ट्रिंग कॉन्सटेनेशन के लिए स्ट्रिंग बिल्डर ऑब्जेक्ट बनाएं।
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// प्रत्येक पृष्ठ को जेपीईजी छवि में एक-एक करके प्रस्तुत करें।
for (int i = 0; i < pageCount; i++){
	// स्ट्रिंग बिल्डर को साफ़ करें और स्ट्रिंग कॉन्सटेनेशन के साथ आउटपुट इमेज पाथ बनाएं।
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// आउटपुट छवि पथ प्राप्त करें।
	StringPtr outputJPEG = sb->ToString();
	// वर्कशीट को इमेज में बदलें।
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}