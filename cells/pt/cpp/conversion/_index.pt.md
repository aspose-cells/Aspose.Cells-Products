---
title:  Microsoft Conversão de arquivo Excel via C++
description: Aspose.Cells for C++ biblioteca. Converta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG e mais formatos com apenas algumas linhas de código C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de documento Excel via C++" h2="Salve arquivos Microsoft<sup>&reg;</sup> Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Para qualquer aplicativo ou solução de conversão de planilhas,**C++ Biblioteca Excel** acelera os processos de codificação, automação e conversão enquanto lida com vários arquivos, incluindo XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite *converter Excel para PDF**, XPS, HTML, MHTML, Simples Texto e imagens populares como JPG, TIFF, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversão de formatos Excel Microsoft" %}}
 A conversão entre formatos de planilha requer apenas o carregamento da planilha usando o[Pasta de trabalho](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) classe e salvando-a novamente no formato necessário usando o[Salvar](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) método do[Pasta de trabalho](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) aula.
{{% blocks/products/pf/feature-page-code h3="C++ Código de exemplo para conversão de formato de arquivo Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converta formatos Excel para PDF com configurações de nível de conformidade" %}}
C++ Excel Automation API oferece suporte à conversão de pastas de trabalho para PDF, bem como suporte à configuração do nível de conformidade e data de criação. Os desenvolvedores podem usar[Opções de salvamento de PDF](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) juntamente com[Aspose::Cells::Renderização](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) para definir a conformidade PDF. Para conversão, método save API tendo PdfSaveOptions como parâmetro e caminho do arquivo de saída específico.
{{% blocks/products/pf/feature-page-code h3="C++ Código de exemplo para Excel para conversão PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Salvar Excel em imagens" %}}
**C++ Analisador Excel** tem a capacidade de exportar dados na forma de imagens. Cada planilha pode ser convertida em diferentes formatos de imagem, incluindo BMP, JPEG, PNG e GIF, definidos pelo[Renderização::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Para qualquer**Converter Excel em imagens** caso, selecione o caso relevante nos links.
{{% blocks/products/pf/feature-page-code h3="C++ Código para conversão de Excel em imagem" %}}

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
