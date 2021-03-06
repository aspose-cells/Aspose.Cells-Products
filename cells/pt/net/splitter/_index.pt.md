---
title: Dividir planilha do Excel em C#
url: /pt/net/splitter/
description: C# códigos-fonte que explicam como dividir arquivos do Microsoft Excel em vários arquivos em aplicativos Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Divisão de arquivos do Excel via .NET" h2="Divida um único documento do Excel em diferentes arquivos usando o código C# em aplicativos baseados em .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca do Excel](/cells/net/) é capaz de dividir o documento do Excel em várias planilhas dentro de aplicativos baseados em .NET. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento do Excel em vários arquivos" %}}
A maneira mais simples de dividir arquivos do Excel em planilhas é acessar todas as planilhas via [Fichas de trabalho](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterando em cada planilha e chamando o [cópia de](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) método. Finalmente, salvando-o em um caminho especificado. 

+ Carregue o arquivo do Excel com o caminho completo usando [Aula de pasta de trabalho](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterar em cada planilha
+ Criar um novo objeto de classe Workbook
+ Copie a planilha via [Copiar método](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Chame o método Save() e passe o nome do arquivo (caminho completo) com SaveFormat relevante.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir arquivos do Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir planilha do Excel em painéis" %}}

Para dividir a janela da planilha em painéis, API fornece [Método de divisão](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) da classe de planilha, que fornece a visão dividida da planilha. Para remover a visualização dividida API fornece [Método RemoveSplit](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Por fim, salve-o em um caminho especificado. 

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir a janela da planilha do Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Código para remover a visualização panorâmica dividida" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
