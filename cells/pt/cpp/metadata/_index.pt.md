---
title: Gerenciar metadados de arquivos Excel via C++
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos Excel usando a biblioteca C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar metadados de documentos Excel Microsoft<sup>&reg;</sup> via C++" h2="Visualize, insira, atualize, remova ou extraia propriedades personalizadas e integradas de documentos Excel em aplicativos C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadados no Excel - Como visualizar, inserir e remover metadados de arquivos Excel.[C++ Biblioteca Excel](/cells/pt/cpp/) faclitates é de maneira fácil, suportando as propriedades integradas/definidas pelo sistema, como nome do autor, título, estatísticas do documento, etc., necessárias em algum momento, como verificar quando o último arquivo é modificado ou salvo junto com propriedades personalizadas/definidas pelo usuário na forma de pares nome/valor. Para automatizar o processo, a biblioteca suporta a criação e manutenção de grandes arquivos Excel de metadados.[Pasta de trabalho](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Abre uma pasta de trabalho por caminho, por fluxo e por FileFormatType especial. Portanto, carregue o arquivo com o método apropriado para processamento posterior. Poucas das possibilidades listadas abaixo e os desenvolvedores podem facilmente aprimorar seu código de acordo com os requisitos da aplicação.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ler e atualizar propriedades integradas" %}}

 Para automatizar as propriedades integradas, API fornece[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) método que retorna uma coleção DocumentProperties que representa todas as propriedades internas do documento da planilha. Depois de acessar todas as propriedades integradas, acesse as propriedades relevantes usando métodos relevantes, como GetTitle(), GetSubject() etc. Para atualizar as propriedades, API fornece métodos como SetTitle, SetSubject, SetAuthor, SetComments etc.[coleção de propriedades de documentos integradas](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) para a função necessária.

{{% blocks/products/pf/feature-page-code h3="C++ Código para ler propriedades definidas pelo sistema" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Código C++ para atualizar propriedades integradas" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizar e adicionar propriedades personalizadas" %}}

Para lidar com propriedades personalizadas, API fornece[Pasta de trabalho::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) que retorna toda a coleção de propriedades personalizadas do documento da planilha. Acessando primeiro as propriedades personalizadas por meio deste método, os desenvolvedores podem usar métodos relevantes para adicionar propriedades como AddIDocumentProperty, AddLinkToContentProperty e, da mesma forma, usar UpdateLinkedPropertyValue, UpdateLinkedRange para atualizar o valor da propriedade do documento personalizado vinculado ao conteúdo e ao intervalo vinculado, respectivamente. Os desenvolvedores podem usar o método relevante de[coleção de propriedades personalizadas de documentos](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="Código C++ para visualizar propriedades personalizadas" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Código C++ para adicionar metadados em arquivo Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
