---
title: Conversão de arquivo do Microsoft Excel via C++ 
url: /pt/cpp/conversion/
description: Converta Excel XLS, XLSX, ODS, CSV para PDF, XPS, HTML, JPEG e outros formatos com apenas algumas linhas de código C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de Documentos Excel via C++" h2="Salve arquivos do Microsoft<sup>&reg;</sup> Excel como planilha, Web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
Para qualquer aplicativo ou solução de conversão de planilhas, a **C++Excel Library** acelera os processos de codificação, automação e conversão enquanto lida com vários arquivos, incluindo XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite **converter Excel para PDF**, XPS, HTML, MHTML, Texto Simples e imagens populares como JPG, TIFF, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversão de formatos do Microsoft Excel" %}}
A interconversão do formato da planilha requer apenas o carregamento de uma planilha com uma instância de [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ponteiro e salvando de volta no formato desejado usando [Salve ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) método de [Classe IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Código de exemplo para conversão de formato de arquivo do Excel" %}}

```cs

// Carregue o formato excel de origem.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Salve no formato de saída necessário.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converta formatos do Excel em PDF com configurações de nível de conformidade" %}}
C++ Excel Automation API oferece suporte à conversão de pastas de trabalho em PDF, bem como à configuração de nível de conformidade e data de criação. Os desenvolvedores podem usar [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) juntamente com [Aspose::Cells::Renderização](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) para definir a conformidade do PDF. Para conversão, API salve o método com PdfSaveOptions como parâmetro e caminho do arquivo de saída especificado. 
{{% blocks/products/pf/feature-page-code h3="C++ Código de exemplo para conversão de Excel para PDF" %}}

```cs
// Carregue o arquivo Excel de amostra.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Criar objeto de opções de salvamento em pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Defina a conformidade para PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// ou PDFCompliance_PdfA1a 
// para PDF normal será PdfCompliance_None

// Salve o documento do Excel em formato PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Salvar Excel em Imagens" %}}
**C++ Excel Parser** pode exportar dados na forma de imagens. Cada planilha pode ser convertida em diferentes formatos de imagem, incluindo BMP, JPEG, PNG e GIF, definidos pelo [Renderizando::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Para qualquer caso de **Converter Excel em Imagens**, selecione o caso relevante nos links.
{{% blocks/products/pf/feature-page-code h3="C++ Código para conversão de Excel em imagem" %}}

```cs
// Caminho do diretório de saída.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Carregue o XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Acesse a primeira planilha.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Criar imagem ou objeto de opções de impressão.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Especifique o formato da imagem. O código abaixo é para JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Para outras imagens como GIF, BMP e PNG pode-se usar GetGif(), GetBmp() e GetPng() respectivamente 

// Especifique a resolução horizontal e vertical
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderize a folha em relação à imagem especificada ou às opções de impressão.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Obter contagem de páginas.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Crie um objeto construtor de strings para concatenações de strings.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderize cada página para imagem jpeg, uma por uma.
for (int i = 0; i < pageCount; i++){
	// Limpe o construtor de strings e crie o caminho da imagem de saída com concatenações de strings.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Obtenha o caminho da imagem de saída.
	StringPtr outputJPEG = sb->ToString();
	// Converter planilha em imagem.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}