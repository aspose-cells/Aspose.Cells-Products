---
title: Microsoft Conversão de arquivos Excel com Go via C++
description: Aspose.Cells para Go via biblioteca C++. Converta arquivos EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG e muitos outros formatos com apenas algumas linhas de código Go via C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Conversão de documentos do Excel com Go via C++" h2="Salve arquivos do Excel Microsoft como planilhas, formatos web, imagens e layout fixo." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Para qualquer aplicativo ou solução de conversão de planilhas,**Acesse a Biblioteca Excel pelo código C++.**Acelera os processos de codificação, automação e conversão, lidando com vários arquivos, incluindo XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML e ODS. Também permite converter arquivos do Excel para PDF, XPS, HTML, MHTML, texto simples e imagens populares como JPG, TIFF, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversão de formatos Excel Microsoft" %}}
 A conversão entre formatos de planilha requer apenas o carregamento da planilha usando o[Pasta de trabalho](https://reference.aspose.com/cells/go-cpp/workbook/) classe e salvando-a novamente no formato necessário usando o[Salvar](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) método do[Pasta de trabalho](https://reference.aspose.com/cells/go-cpp//workbook/) aula.
{{% blocks/products/pf/feature-page-code h3="Acesse o código de exemplo C++ para conversão de formato de arquivo Excel." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)
// Load the source excel format.
workbook,_:= NewWorkbook_String("src_excel_file.xlsx")
// Save in required output format.
workbook.Save_String("output_excel_format.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converter formatos do Excel para PDF com configurações de nível de conformidade" %}}
 A Automação do Excel (C++) suporta a conversão de pastas de trabalho para o formato PDF, além de permitir a configuração do nível de conformidade e da data de criação. Os desenvolvedores podem usar[Opções de salvamento de PDF](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Para definir a conformidade com PDF. Para conversão, o método de salvamento API tem PdfSaveOptions como parâmetro e o caminho do arquivo de saída especificado.
{{% blocks/products/pf/feature-page-code h3="Acesse o código de exemplo C++ para conversão de Excel para PDF." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

workbook, _ := NewWorkbook()
worksheets, _ := workbook.GetWorksheets()
worksheet, _ := worksheets.Get_Int(0)
cells, _ := worksheet.GetCells()
cell, _ := cells.Get_String("A1")
cell.PutValue_Int(5)
cell, _ = cells.Get_String("A2")
cell.PutValue_Int(15)
cell, _ = cells.Get_String("A3")
cell.PutValue_Int(25)
workbook.Save_String("HELLO_Convert.pdf")
println("Finish to convert to PDF , check .pdf file in output folder.")


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Salvar Excel em Imagens" %}}
**Acesse o analisador do Excel C++** Possui a capacidade de exportar dados em formato de imagens. Cada planilha pode ser convertida para diferentes formatos de imagem, incluindo BMP, JPEG, PNG e GIF, definidos pelo usuário.[Renderização::OpçõesDeImagemOuImpressão](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Para qualquer**Converter Excel em imagens** Em caso afirmativo, selecione o caso relevante a partir dos links.
{{% blocks/products/pf/feature-page-code h3="Acesse o código C++ para conversão de Excel em imagem." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

 // Load the XLSX.
    workbook, _ := NewWorkbook("source-excel-file.xlsx")

// Access first worksheet.
    worksheets, _ := workbook.GetWorksheets()
    worksheet, _ := worksheets.Get_Int(0)

// Create image or print options object.
    imgOptions, _ := NewImageOrPrintOptions()

// Specify the image format. Below code is for JPEG
    imgOptions.SetImageType(ImageType_Jpeg)

// Specify horizontal and vertical resolution
    imgOptions.SetHorizontalResolution(200)
    imgOptions.SetVerticalResolution(200)

// Render the sheet with respect to specified image or print options.
    sheetRender, _ := NewSheetRender(worksheet, imgOptions)

// Get page count.
    pageCount, _ := sheetRender.GetPageCount()

// Render each page to jpeg image one by one.
    for i := int32(0); i < pageCount; i++ {
        data, _ := sheetRender.ToImage_Int(i)
        filename := "Image" + string(i) + ".jpg"
        file, _ := os.OpenFile(filename, os.O_WRONLY|os.O_CREATE|os.O_APPEND, 0644)
        defer file.Close()
        file.Write(data)
    }

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
