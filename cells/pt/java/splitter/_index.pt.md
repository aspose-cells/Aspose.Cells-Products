---
title: Dividir planilha do Excel em planilhas em Java
description: Java códigos-fonte que explicam como dividir Microsoft arquivos Excel em vários documentos usando a biblioteca Java Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Divisão de arquivo do Excel via Java" h2="Divida a planilha do Excel em planilhas dentro de aplicativos baseados em Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Existem vários cenários, quando há necessidade de dividir arquivos do Excel como uma planilha contendo os dados dos alunos com alocação de folha única para cada aluno. E há necessidade de dividir cada folha do aluno como um arquivo separado. Para automatizar o aplicativo via Java,[Java Excel API](/cells/pt/java/) está lá para dividir o documento do Excel em planilhas. Os formatos suportados incluem XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento do Excel em vários arquivos" %}}

 A maneira mais simples de dividir o arquivo do Excel em uma planilha é acessar todas as planilhas, percorrer cada planilha e salvar uma a uma no formato desejado. Para carregar a planilha, API fornece[pasta de trabalho](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) aula.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) método obtém o número total de folhas. Percorra cada folha e use[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)para acessar folha específica. Mova os dados da planilha selecionada para o objeto de classe Workbook recém-criado usando[Copiar método](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Por fim, salve-o no formato necessário.

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir arquivos do Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir planilha do Excel em painéis" %}}

API também fornece a funcionalidade de dividir a planilha do Excel em diferentes painéis. O processo é carregar o arquivo usando a classe Workbook. Selecione a primeira planilha ou qualquer planilha necessária fornecendo seu índice. Chame o setActiveCell tendo o índice de célula relevante como parâmetro. E, finalmente, divida a janela da planilha em diferentes painéis chamando o método split().

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir planilha do Excel em exibição de painel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
