---
title:  Microsoft एक्सेल फ़ाइल रूपांतरण C++ के माध्यम से
description: एक्सेल XLS, XLSX, ODS, CSV से PDF, XPS, HTML, JPEG और C++ कोड की कुछ पंक्तियों के साथ अन्य प्रारूपों में कनवर्ट करें।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++ के माध्यम से एक्सेल दस्तावेज़ रूपांतरण" h2="Microsoft<sup>&reg;</sup> एक्सेल फाइल को स्प्रेडशीट, वेब, इमेज और फिक्स्ड-लेआउट फॉर्मेट के रूप में सेव करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
 किसी भी स्प्रेडशीट परिवर्तक अनुप्रयोग या समाधान के लिए,**C++ एक्सेल लाइब्रेरी**XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS सहित कई फाइलों को संभालने के दौरान कोडिंग, स्वचालन और रूपांतरण प्रक्रियाओं को गति देता है। PDF**, XPS, HTML, MHTML, सादा टेक्स्ट और लोकप्रिय चित्र जैसे JPG, TIFF, PNG, BMP और SVG।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft एक्सेल प्रारूपों का अंतर-रूपांतरण" %}}
 स्प्रेडशीट प्रारूप के अंतर-रूपांतरण के लिए केवल एक उदाहरण के साथ एक स्प्रेडशीट लोड करने की आवश्यकता होती है[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) सूचक और उपयोग करके वांछित प्रारूप में वापस सहेजना[बचाना](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) उसकि विधि[आई वर्कबुक क्लास](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="एक्सेल फ़ाइल स्वरूप रूपांतरण के लिए C++ उदाहरण कोड" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="अनुपालन स्तर सेटिंग्स के साथ एक्सेल प्रारूप को PDF में बदलें" %}}
 C++ एक्सेल ऑटोमेशन API कार्यपुस्तिकाओं को PDF में बदलने के साथ-साथ अनुपालन स्तर और निर्माण तिथि की समर्थन सेटिंग का समर्थन करता है। डेवलपर्स उपयोग कर सकते हैं[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) साथ[Aspose::Cells::रेंडरिंग](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)PDF अनुपालन सेट करने के लिए। रूपांतरण के लिए, API पैरामीटर और विशिष्ट आउटपुट फ़ाइल पथ के रूप में PdfSaveOptions वाली विधि सहेजें।
{{% blocks/products/pf/feature-page-code h3="एक्सेल के लिए C++ नमूना कोड PDF रूपांतरण के लिए" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="एक्सेल को इमेज में सेव करें" %}}
**C++ एक्सेल पार्सर** छवियों के रूप में डेटा निर्यात करने की क्षमता है। प्रत्येक वर्कशीट को BMP, JPEG, PNG और GIF सहित विभिन्न छवि प्रारूपों में परिवर्तित किया जा सकता है, जो इसके द्वारा निर्धारित किया गया है।[प्रतिपादन :: IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . किसी के लिए**एक्सेल को छवियों में बदलें** मामला, लिंक से प्रासंगिक मामले का चयन करें।
{{% blocks/products/pf/feature-page-code h3="C++ एक्सेल से छवि रूपांतरण के लिए कोड" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
