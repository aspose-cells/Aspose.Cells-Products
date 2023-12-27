---
title: Adicionar ou remover anotações de arquivo Excel via C++
description: Adicione ou remova comentários de anotação de dados de planilhas Excel e OpenOffice com a biblioteca C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar anotações de arquivo Excel Microsoft<sup>&reg;</sup> via C++" h2="Adicione ou remova notas simples para anotações ou comentários em aplicativos baseados em C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++](/cells/pt/cpp/) fornece suporte para gerenciar anotações em nível de célula adicionando, acessando e removendo comentários. API fornece[Comente](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) e[ComentárioCollection](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) assim como[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)para lidar com comentários em todos os aspectos. Os formatos Excel suportados incluem ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotações de dados de arquivos Excel" %}}
 Manipulação de comentários em planilhas - Não se limita a quantos comentários uma planilha possui no MS Excel. Pode-se inserir o quanto for necessário para a aplicação. O processo de inserção de comentários é criar[Pasta de trabalho](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) objeto de classe para carregar um arquivo existente e selecione a planilha onde deseja adicionar o comentário. Obtenha todos os seus comentários usando getComments(). Adicione o comentário usando[Adicionar(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) método. Obtenha o índice da célula e use[Definir Nota](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) para inserir comentários. Além disso, API é capaz de remover todos os comentários. Poucos métodos são[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) para Limpa todos os comentários na planilha do designer. Além disso,***RemoverEm*** método para remover o elemento em um índice especificado ou com nome especificado.

{{% blocks/products/pf/feature-page-code h3="C++ Código para adicionar comentários no arquivo Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
