---
title: Crie arquivos do Excel por meio de Java
url: /pt/java/assembly/
description: Gere planilhas do Microsoft Excel a partir de uma planilha de modelo usando a biblioteca de planilhas Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Criação de relatórios baseados em modelos do Excel via Java" h2="Gere relatórios de arquivos do Excel em massa com base em um modelo predefinido em aplicativos baseados em Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteca do Excel](/cells/java/) suporta a geração de arquivos Excel baseados em modelos para geração de relatórios em massa. Ele é necessário para a maioria dos casos, como a criação de cobranças de taxas, cartões de resultados e registros de pacientes, etc. Os modelos são padrões predefinidos. O código abaixo de Java gera os arquivos do Excel em massa da mesma forma que o documento de modelo preenchido com dados. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Criar relatórios com base no modelo de Excel pré-projetado" %}}

Usando Java Assembly API os desenvolvedores podem programar facilmente o código de geração de relatórios em massa incluindo os trechos de código abaixo. API fornece [importar dados](https://docs.aspose.com/cells/java/import-and-export-data/) recurso de diferentes fontes e criar documentos do Excel dependendo desses dados. Para padrões baseados em modelo, API fornece um [Classe de designer da pasta de trabalho](https://apireference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) para representar uma planilha de designer. O processo é, crie seu objeto e use-o para abrir o arquivo de modelo. Defina a fonte de dados, que pode ser Array, DataTable, Json etc. Processe-a para importar os dados e salve o arquivo no formato desejado. Os programadores podem reunir dados em relatórios em outros formatos de arquivo, incluindo XLS, XLSX, XLSB, XLSM, ODS a partir dos links listados abaixo.



{{% blocks/products/pf/feature-page-code h3="Java Código para criar relatórios do Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}