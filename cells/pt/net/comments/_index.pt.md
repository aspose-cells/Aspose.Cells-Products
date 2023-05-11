---
title: Inserir comentários no Excel via .NET
description:  C# códigos-fonte que informam como inserir comentários em Microsoft arquivos do Excel usando a biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Inserção de comentários do Excel via .NET" h2="Crie documentos do Excel e insira comentários usando APIs do lado do servidor em aplicativos baseados em .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Você pode adicionar comentários às células. Quando uma célula tem um comentário, um indicador aparece no canto da célula. Os comentários aparecem quando você passa o cursor sobre uma célula. Esses comentários podem ser usados para discussão, instruções especiais ou marcação do conteúdo do documento.[.NET Biblioteca Excel](/cells/pt/net/)suporta a inserção de comentários em arquivos Excel. Para isso, o API disponibiliza um[Comente](https://reference.aspose.com/cells/net/aspose.cells/comment) classe para bloco de construção de comentários.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inserir comentários no arquivo do Excel" %}}

 Inserir comentários usando o Excel API é simples. Processo é, Criar[classe de pasta de trabalho](https://reference.aspose.com/cells/net/aspose.cells/workbook) objeto e selecione a primeira planilha ou a planilha relevante fornecendo seu índice. Insira os dados de células necessários usando[Método PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Adicionar comentário à planilha usando[ComentárioColeção](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) de[Adicionar método](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Código para Inserir Comentário no Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
