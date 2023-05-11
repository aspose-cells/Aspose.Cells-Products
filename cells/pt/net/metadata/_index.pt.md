---
title: Gerenciar metadados de arquivos do Excel via .NET C#
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos do Excel com apenas algumas linhas do código C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar Microsoft<sup>&reg;</sup> Metadados de arquivo do Excel via .NET" h2="Visualize, adicione, atualize, remova ou extraia propriedades internas e personalizadas de arquivos do Excel usando APIs .NET do lado do servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/pt/net/) suporta o gerenciamento de propriedades definidas pelo sistema (incorporadas), como título, nome do autor, estatísticas do documento, etc., bem como propriedades definidas pelo usuário (personalizadas) na forma de par nome-valor. Há[classe de pasta de trabalho](https://reference.aspose.com/cells/net/aspose.cells/workbook) para carregar os arquivos e[PlanilhaColeção](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) lida com a coleta de planilhas, bem como[aula de planilha](https://reference.aspose.com/cells/net/aspose.cells/worksheet) para representar uma única planilha. Juntamente com essas classes, BuiltInDocumentProperties, CustomDocumentProperties simplifica o processo de gerenciamento de metadados.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gerenciando Propriedades Integradas" %}}

 Para gerenciar propriedades definidas pelo sistema, API fornece[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , e os programadores podem acessar facilmente uma propriedade interna e atualizar seu valor. Dependendo do requisito do aplicativo, os desenvolvedores podem usar o índice ou o nome da propriedade do[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Código para gerenciar propriedades incorporadas" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gerenciando Propriedades Definidas Personalizadas" %}}

 Para gerenciar propriedades definidas pelo usuário, API fornece[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , e os desenvolvedores podem acessar facilmente as propriedades já adicionadas, bem como adicionar novas propriedades. Para adicionar propriedades personalizadas,[Adicionar método](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) de[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) classe adiciona a propriedade e retorna uma referência para a nova propriedade como um[Propriedades.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objeto. A classe DocumentProperty é usada para recuperar o nome, valor e tipo da propriedade do documento como[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) que retorna um dos[Tipo de Propriedade](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) valores de enumeração.
 
{{% blocks/products/pf/feature-page-code h3="C# Código para Adicionar Metadados em Arquivo Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Código para remover propriedade personalizada no arquivo do Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
