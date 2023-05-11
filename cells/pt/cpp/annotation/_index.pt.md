---
title: Anotações de arquivo do Excel via C++
description: Adicione ou remova comentários de anotação de dados de planilhas Excel e OpenOffice com a biblioteca C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar Microsoft<sup>&reg;</sup> Anotações de arquivo do Excel via C++" h2="Adicione ou remova notas simples para anotações ou comentários em aplicativos baseados em C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/pt/cpp/) fornece suporte para gerenciar anotações no nível da célula adicionando, acessando e removendo comentários. API fornece[IComentário](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) e[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) assim como[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)para lidar com comentários em todos os aspectos. Os formatos Excel suportados incluem ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotações de dados de arquivos do Excel" %}}
 Manipulação de comentários em planilhas - Não é limitado quantos comentários uma planilha possui no MS Excel. Pode-se inserir o quanto for necessário para a aplicação. O processo de inserção de comentários é, criar[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objeto de classe para carregar um arquivo existente e selecionar a planilha onde deseja adicionar o comentário. Obtenha todos os seus comentários usando getComments(). Adicione o comentário usando[Adicionar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > CellName) método. Obtenha o índice da célula e use[setNote](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) para inserir comentários. Além disso, API é capaz de remover todos os comentários. Poucos métodos são[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) para Limpa todos os comentários na planilha do designer. Além disso,[RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) para remover o elemento em um índice especificado ou com o nome especificado.

{{% blocks/products/pf/feature-page-code h3="C++ Código para adicionar comentários no arquivo do Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
