---
title: Gerencie os metadados de arquivos do Excel com o Go via C++
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos do Excel usando o Go por meio da biblioteca C++.
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar metadados de documentos do Excel via Go via C++" h2="Visualize, insira, atualize, remova ou extraia propriedades personalizadas e integradas de documentos do Excel em aplicativos C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadados no Excel - Como visualizar, inserir e remover metadados de arquivos do Excel.[Acesse a Biblioteca Excel pelo código C++.](/cells/pt/go-cpp/) biblioteca facilita o processo ao suportar propriedades integradas/definidas pelo sistema, como nome do autor, título, estatísticas do documento etc., necessárias ocasionalmente para verificar quando o arquivo foi modificado ou salvo pela última vez, além de propriedades personalizadas/definidas pelo usuário na forma de pares nome/valor. Para automatizar o processo, a biblioteca permite a criação e manutenção de grandes arquivos Excel de metadados.[Pasta de trabalho](https://reference.aspose.com/cells/go-cpp/workbook/) A classe abre uma pasta de trabalho por caminho, por fluxo e por um tipo de formato de arquivo específico. Assim, o arquivo é carregado com o método apropriado para processamento posterior. Algumas das possibilidades estão listadas abaixo, e os desenvolvedores podem facilmente aprimorar seu código de acordo com os requisitos da aplicação.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ler e atualizar propriedades integradas" %}}

 Para automatizar as propriedades integradas, o código API fornece[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Método que retorna uma coleção DocumentProperties representando todas as propriedades internas do documento da planilha. Após acessar todas as propriedades internas, acesse as propriedades relevantes usando o método apropriado, como GetTitle(), GetSubject(), etc. Para atualizar as propriedades, o código API fornece métodos como SetTitle, SetSubject, SetAuthor, SetComments, etc. Veja o[coleção de propriedades de documentos integrada](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) para a função requerida.

{{% blocks/products/pf/feature-page-code h3="Acesse o código C++ para ler as propriedades definidas pelo sistema." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Acesse o código C++ para atualizar as propriedades integradas." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizar e adicionar propriedades definidas pelo usuário." %}}

 Para lidar com propriedades personalizadas, API fornece[Workbook::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)que retorna toda a coleção de propriedades personalizadas do documento da planilha. Ao acessar as propriedades personalizadas por meio desse método, os desenvolvedores podem usar os métodos relevantes para adicionar propriedades, como AddIDocumentProperty, AddLinkToContentProperty e, da mesma forma, usar UpdateLinkedPropertyValue e UpdateLinkedRange para atualizar o valor da propriedade personalizada do documento que se vincula ao conteúdo e ao intervalo vinculado, respectivamente. Os desenvolvedores podem usar o método relevante de[coleção de propriedades de documento personalizadas](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Acesse o código C++ para visualizar propriedades personalizadas." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Acesse o código C++ para adicionar metadados em um arquivo Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}