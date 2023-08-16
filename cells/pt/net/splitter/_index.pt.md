---
title: Dividir a planilha do Excel em C#
description: C# códigos-fonte que explicam como dividir Microsoft arquivos Excel em vários arquivos em aplicativos Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Divisão de arquivo do Excel via .NET" h2="Divida um único documento do Excel em arquivos diferentes usando o código C# em aplicativos baseados em .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteca Excel](/cells/pt/net/) é capaz de dividir o documento do Excel em várias planilhas em aplicativos baseados em .NET. Os formatos de arquivo suportados incluem XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividir documento do Excel em vários arquivos" %}}
 A maneira mais simples de dividir os arquivos do Excel em planilhas é acessando todas as planilhas via[Fichas de trabalho](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Iterando em cada folha e chamando o[cópia de](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) método. Finalmente, salvando-o em um caminho especificado.

 + Carregue o arquivo do Excel com o caminho completo usando[classe de pasta de trabalho](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterar através de cada folha
+ Criar um novo objeto de classe Workbook
 + Copie a folha via[Copiar método](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Chame o método Save() e passe o nome do arquivo (caminho completo) tendo SaveFormat relevante.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir arquivos do Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividir planilha do Excel em painéis" %}}

 Para dividir a janela da planilha em painéis, API fornece[método de divisão](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)da classe de planilha, que fornece a visão dividida da planilha. Para remover a exibição dividida API fornece[Método RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Por fim, salve-o em um caminho especificado.

{{% blocks/products/pf/feature-page-code h3="C# Código para dividir a janela da planilha do Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Código para remover visualização panorâmica dividida" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
