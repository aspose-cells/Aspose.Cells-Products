---
title: Dividir planilha do Excel em C#
description: Códigos-fonte C# que explicam como dividir arquivos Excel Microsoft em vários arquivos em aplicativos Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Divisão de arquivo Excel via .NET" h2="Divida um único documento Excel em arquivos diferentes usando o código C# em aplicativos baseados em .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca Excel](/cells/pt/net/) é capaz de dividir documentos Excel em várias planilhas em aplicativos baseados em .NET. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Divida o documento Excel em vários arquivos" %}}
 maneira mais simples de dividir arquivos do Excel em planilhas é acessar todas as planilhas via[Fichas de trabalho](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Iterando em cada planilha e chamando o[cópia de](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) método. Finalmente salvando-o em um caminho especificado.

 + Carregue o arquivo Excel com caminho completo usando[Aula de apostila](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterar em cada planilha
+ Crie um novo objeto de classe Workbook
 + Copie a planilha via[Método de cópia](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Chame o método Save() e passe o nome do arquivo (caminho completo) com SaveFormat relevante.

{{% blocks/products/pf/feature-page-code h3="Código C# para dividir arquivos Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Divida a planilha do Excel em painéis" %}}

 Para dividir a janela da planilha em painéis, API fornece[Método de divisão](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) da classe de planilha, que fornece a visualização dividida da planilha. Para remover a visualização dividida API fornece[Método RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Finalmente salve-o em um caminho especificado.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir a janela da planilha do Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Código C# para remover visualização panorâmica dividida" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
