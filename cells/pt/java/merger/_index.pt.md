---
title: Mesclar diferentes arquivos Excel em um único em Java
description: Mesclar arquivos Excel usando Java em várias planilhas ou em uma única planilha. Mesclar, combinar ou concatenar documentos Excel para PDF, Imagens e HTML também.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Mesclagem de arquivos Excel via Java" h2="Combine dois ou mais arquivos Excel em uma única planilha usando o código Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteca Excel](/cells/pt/java/)fornece várias maneiras de combinar pastas de trabalho com vários tipos de conteúdo, como fórmulas, imagens, dados, gráficos, etc., em um único documento de planilha. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV e muito mais.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine arquivos Excel com imagens e gráficos" %}}
 A maneira mais simples de combinar dois arquivos Excel com imagens e gráficos é chamando o método[Pasta de trabalho.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) método. Ele permite mesclar arquivos Excel de tipo semelhante em uma única planilha.
{{% blocks/products/pf/feature-page-code h3="Código Java para combinar arquivos Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar vários arquivos Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) O método suporta a mesclagem de dados, estilos e fórmulas de um arquivo Excel em uma nova planilha do mesmo formato. É uma maneira eficiente de mesclar vários arquivos enquanto usa o cache.
{{% blocks/products/pf/feature-page-code h3="Código Java para mesclar vários arquivos Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar arquivos do Excel copiando planilhas" %}}
[Planilha.copiar](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)pode ser usado para copiar dados e formatação de uma planilha de origem para outra planilha dentro ou entre pastas de trabalho. O método usa o objeto da planilha de origem como parâmetro.
{{% blocks/products/pf/feature-page-code h3="Java Código para copiar planilhas entre pastas de trabalho" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de mesclagem suportados" subTitle="Usando Java, também é possível mesclar muitos outros formatos de arquivo, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formato de arquivo de página da web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Arquivo binário da pasta de trabalho do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Modelo Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Modelo habilitado para macro do Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
