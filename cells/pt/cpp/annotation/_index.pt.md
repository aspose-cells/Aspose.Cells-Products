---
title: Anotações de arquivo do Excel via C++
url: /pt/cpp/annotation/
description: Adicione ou remova comentários de anotações de dados de planilhas do Excel e OpenOffice com a biblioteca C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar anotações de arquivos do Microsoft<sup>&reg;</sup> por meio de C++" h2="Adicione ou remova notas simples para anotações ou comentários em aplicativos baseados em C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ ExcelAPI](/cells/cpp/) fornece suporte para gerenciar anotações em nível de célula adicionando, acessando e removendo comentários. API fornece [IComentário](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) e [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) assim como [GetIComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) para lidar com comentários em todos os aspectos. Os formatos Excel suportados incluem ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotações de dados de arquivos do Excel" %}}
Manipulando Comentários em Planilhas - Não se limita a quantos comentários uma planilha possui no MS Excel. Pode-se inserir o quanto de necessidade de aplicação. O processo de inserção de comentários é criar [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class para carregar um arquivo existente e selecione a planilha onde deseja adicionar o comentário. Obtenha todos os comentários usando getComments(). Adicione o comentário usando [Adicionar](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) método. Obtenha o índice de células e use [setNota](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) para inserir comentários. Além disso, API é capaz de remover todos os comentários. Poucos métodos são [Limpar comentários()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) para Limpa todos os comentários na planilha do designer. Além disso, [Remover em](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) para remover o elemento em um índice especificado ou com o nome especificado.

{{% blocks/products/pf/feature-page-code h3="C++ Código para adicionar comentários no arquivo Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}