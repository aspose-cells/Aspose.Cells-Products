---
title:  Microsoft एक्सेल फ़ाइल रूपांतरण C++ के माध्यम से
description: Aspose.Cells for C++ पुस्तकालय। C++ कोड की कुछ पंक्तियों के साथ एक्सेल, JSON, PDF, एक्सएमएल, HTML, TXT, TSV, CSV, एसक्यूएल, जेपीजी, PNG और अधिक प्रारूपों में कनवर्ट करें।
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++ के माध्यम से एक्सेल दस्तावेज़ रूपांतरण" h2="Microsoft<sup>&reg;</sup> एक्सेल फ़ाइलों को स्प्रेडशीट, वेब, छवि और फिक्स्ड-लेआउट प्रारूपों के रूप में सहेजें" >}}

{{% blocks/products/pf/feature-page-summary %}}
 किसी भी स्प्रेडशीट कनवर्टर एप्लिकेशन या समाधान के लिए,**C++ एक्सेल लाइब्रेरी** XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS सहित कई फाइलों को संभालते हुए कोडिंग, स्वचालन और रूपांतरण प्रक्रियाओं को गति देता है। यह एक्सेल को *कन्वर्ट करने की भी अनुमति देता है। PDF**, XPS, HTML, MHTML, सादा टेक्स्ट और लोकप्रिय छवियाँ जैसे JPG, TIFF, PNG, BMP और SVG।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft एक्सेल प्रारूपों का अंतर-रूपांतरण" %}}
 स्प्रेडशीट प्रारूपों के बीच कनवर्ट करने के लिए केवल स्प्रेडशीट को लोड करने की आवश्यकता होती है[वर्कबुक](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) क्लास बनाएं और इसका उपयोग करके आवश्यक प्रारूप में इसे पुनः सहेजें[बचाना](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) की विधि[वर्कबुक](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) कक्षा।
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए उदाहरण कोड" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="अनुपालन स्तर सेटिंग्स के साथ एक्सेल प्रारूप को PDF में बदलें" %}}
C++ एक्सेल ऑटोमेशन API वर्कबुक को PDF में बदलने के साथ-साथ अनुपालन स्तर और निर्माण तिथि की सेटिंग का समर्थन करता है। डेवलपर्स उपयोग कर सकते हैं[पीडीएफसेवविकल्प](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) साथ में[Aspose::Cells::प्रतिपादन](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) PDF अनुपालन सेट करने के लिए। रूपांतरण के लिए, API सेव विधि जिसमें पैरामीटर के रूप में पीडीएफसेवऑप्शंस और निर्दिष्ट आउटपुट फ़ाइल पथ है।
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल से PDF रूपांतरण के लिए नमूना कोड" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को इमेजेज में सेव करें" %}}
**C++ एक्सेल पार्सर** इसमें छवियों के रूप में डेटा निर्यात करने की क्षमता है। प्रत्येक वर्कशीट को BMP, JPEG, PNG और GIF सहित विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, जो इसके द्वारा निर्धारित हैं।[प्रतिपादन::छवियाप्रिंटविकल्प](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . किसी के लिए**एक्सेल को इमेज में कनवर्ट करें** मामला, लिंक से प्रासंगिक मामला चुनें।
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल से छवि रूपांतरण के लिए कोड" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
