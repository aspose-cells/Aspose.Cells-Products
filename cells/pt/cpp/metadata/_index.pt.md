---
title: Gerenciar metadados de arquivos do Excel por meio de C++
url: /pt/cpp/metadata/
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos do Excel usando a biblioteca C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerencie os metadados de documentos do Microsoft<sup>&reg;</sup> por meio de C++" h2="Visualize, insira, atualize, remova ou extraia propriedades personalizadas e integradas de documentos do Excel em C++ aplicativos." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadados no Excel - Como visualizar, inserir e remover metadados de arquivos do Excel. [C++ Biblioteca do Excel](/cells/cpp/) faclitates é de maneira fácil, suportando as propriedades internas / definidas pelo sistema, como nome do autor, título, estatísticas do documento etc. pares nome/valor. Para automatizar o processo, a biblioteca suporta a criação e manutenção de grandes arquivos Excel de metadados. [Método CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) de [Classe de fábrica](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Abra uma pasta de trabalho por caminho, por fluxo e por FileFormatType especial. Portanto, carregue o arquivo com o método apropriado para processamento adicional. Poucas das possibilidades listadas abaixo e os desenvolvedores podem facilmente aprimorar seu código de acordo com os requisitos do aplicativo. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ler e atualizar propriedades internas" %}}

Para automatizar as propriedades integradas, API fornece [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) método que retorna uma coleção DocumentProperties que representa todas as propriedades de documento internas da planilha. Após acessar todas as propriedades internas, acesse as propriedades relevantes usando métodos relevantes como GetTitle(), GetSubject() etc. Para atualizar as propriedades, API fornece métodos como SetTitle, SetSubject, SetAuthor, SetComments etc. [coleção de propriedades de documentos internos](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) para a função necessária.

{{% blocks/products/pf/feature-page-code h3="C++ Código para ler as propriedades definidas pelo sistema" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Código para atualizar as propriedades internas" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizar e adicionar propriedades definidas personalizadas" %}}

Para lidar com propriedades personalizadas, API fornece [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) que retorna toda a coleção de propriedades de documentos personalizados da planilha. Em primeiro lugar, acessando as propriedades personalizadas por meio desse método, os desenvolvedores podem usar métodos relevantes para adicionar propriedades como AddIDocumentProperty, AddLinkToContentProperty e, da mesma forma, usar UpdateLinkedPropertyValue, UpdateLinkedRange para atualizar o valor da propriedade do documento personalizado que vincula ao conteúdo e ao intervalo vinculado, respectivamente. Os desenvolvedores podem usar o método relevante de [coleção de propriedades de documentos personalizados](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Código para visualizar propriedades personalizadas" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Código para adicionar metadados no arquivo Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}