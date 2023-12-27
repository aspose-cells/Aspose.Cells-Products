---
title: Divida a planilha do Excel em planilhas em Java
description: Códigos-fonte Java que explicam como dividir arquivos Microsoft Excel em vários documentos usando a biblioteca Java Excel
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Divisão de arquivo Excel via Java" h2="Divida a planilha do Excel em planilhas em aplicativos baseados em Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Existem vários cenários, quando há necessidade de dividir arquivos Excel como uma planilha contendo dados dos alunos com alocação de planilha única para cada aluno. E é necessário dividir cada planilha do aluno como um arquivo separado. Para automatizar o aplicativo via Java,[Java](/cells/pt/java/) existe para dividir o documento do Excel em planilhas. Os formatos suportados incluem XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Divida o documento Excel em vários arquivos" %}}

 A maneira mais simples de dividir o arquivo Excel em planilhas é acessar todas as planilhas, percorrer cada planilha e salvar uma por uma no formato desejado. Para carregar a planilha, API fornece[Pasta de trabalho](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) aula.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) método obtém o número total de folhas. Itere em cada planilha e use[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) para acessar planilha específica. Mova os dados da planilha selecionada para o objeto de classe Workbook recém-criado usando[Método de cópia](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Por fim, salve-o no formato necessário.

{{% blocks/products/pf/feature-page-code h3="Código Java para dividir arquivos Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Divida a planilha do Excel em painéis" %}}

API também oferece funcionalidade de divisão de planilhas do Excel em painéis diferentes. O processo é carregar o arquivo usando a classe Workbook. Selecione a primeira planilha ou qualquer planilha necessária, fornecendo seu índice. Chame o setActiveCell tendo o índice de célula relevante como parâmetro. E, finalmente, divida a janela da planilha em painéis diferentes chamando o método split().

{{% blocks/products/pf/feature-page-code h3="Java Código para dividir planilha do Excel em visualização em painel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
