---
title: Anotações de arquivo do Excel via Java
url: /pt/java/annotation/
description: Adicione ou remova anotações de dados de planilhas do Excel e OpenOffice com a biblioteca Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar anotações de arquivos do Microsoft<sup>&reg;</sup> por meio de Java" h2="Insira notas simples para anotação ou exclua comentários em nível de célula de planilha do Excel em aplicativos baseados em Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java ExcelAPI](/cells/java/) fornece suporte para gerenciar anotações em nível de célula adicionando, acessando e excluindo comentários. API fornece [Comente](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [Coleção de comentários](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Comentário encadeado](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) e [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) para lidar com comentários em todos os aspectos.
Os formatos de arquivo suportados incluem ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotações de dados de arquivos do Excel" %}}
Gerenciando Comentários em Planilhas - Não há limite de quantos comentários uma planilha possui no MS Excel. Pode-se adicionar tanto quanto de exigência de aplicação. O processo de adicionar comentários é criar [Pasta de trabalho](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class objeto ou carregue um arquivo existente usando a classe Workbook. Acesse todos os seus comentários usando getComments(). Obtenha o índice de células e use [setNota](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) para inserir comentários. Além disso, API é capaz de remover todos os comentários. 

{{% blocks/products/pf/feature-page-code h3="Java Código para adicionar comentários no arquivo Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Código para remover comentários no arquivo Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}