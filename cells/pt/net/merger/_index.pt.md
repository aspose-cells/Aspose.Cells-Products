---
title: Fusão de arquivos do Excel API .NET C#
url: /pt/net/merger/
description: Concatene arquivos de planilha do Excel e OpenOffice com apenas algumas linhas de código C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Mesclagem de arquivos do Excel via .NET" h2="Combine 2 ou mais arquivos do Excel em uma única planilha usando o código C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca do Excel](/cells/net/) fornece várias maneiras de combinar pastas de trabalho com vários tipos de conteúdo, como fórmulas, dados, imagens, gráficos e assim por diante em um único arquivo de planilha. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV e muito mais.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combine arquivos do Excel com imagens e gráficos" %}}
A maneira mais simples de combinar 2 arquivos do Excel com imagens e gráficos é chamando o [Pasta de trabalho. Combinar](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) método. Permite mesclar arquivos do Excel de tipo semelhante em uma única planilha.
{{% blocks/products/pf/feature-page-code h3="C# Código para combinar arquivos do Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar vários arquivos do Excel" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) O método suporta a fusão de dados, estilo e fórmulas de um arquivo Excel em uma nova planilha do mesmo formato. É uma maneira eficiente de mesclar vários arquivos ao usar o cache. 
{{% blocks/products/pf/feature-page-code h3="C# Código para mesclar vários arquivos do Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mesclar arquivos do Excel copiando planilhas" %}}
[Planilha. Copiar](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) pode ser usado para copiar dados e formatação de uma planilha de origem para outra planilha dentro ou entre pastas de trabalho. O método usa o objeto de planilha de origem como parâmetro.
{{% blocks/products/pf/feature-page-code h3="C# Código para copiar planilhas em arquivos do Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}