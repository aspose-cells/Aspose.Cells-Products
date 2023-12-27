---
title: Gerenciar metadados de arquivo Excel via .NET C#
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos Excel com apenas algumas linhas do código C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar metadados de arquivo Excel Microsoft<sup>&reg;</sup> via .NET" h2="Visualize, adicione, atualize, remova ou extraia propriedades de arquivo Excel integradas e personalizadas usando APIs .NET do lado do servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET](/cells/pt/net/) suporta o gerenciamento de propriedades definidas pelo sistema (integradas), como título, nome do autor, estatísticas do documento, etc., bem como propriedades definidas pelo usuário (personalizadas) na forma de par nome-valor. Há[Aula de apostila](https://reference.aspose.com/cells/net/aspose.cells/workbook) para carregar os arquivos e[Coleção de planilhas](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) lida com a coleta de planilhas, bem como[Aula de planilha](https://reference.aspose.com/cells/net/aspose.cells/worksheet) para representar uma única planilha. Junto com essas classes, BuiltInDocumentProperties, CustomDocumentProperties simplifica o processo de gerenciamento de metadados.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gerenciando propriedades integradas" %}}

 Para gerenciar propriedades definidas pelo sistema, API fornece[PropriedadesBuiltInDocument](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) e os programadores podem acessar facilmente uma propriedade integrada e atualizar seu valor. Dependendo dos requisitos do aplicativo, os desenvolvedores podem usar o índice ou o nome da propriedade do[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Código para gerenciar propriedades integradas" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gerenciando propriedades personalizadas definidas" %}}

 Para gerenciar propriedades definidas pelo usuário, API fornece[Propriedades de Documento Personalizado](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , e os desenvolvedores podem acessar facilmente propriedades já adicionadas, bem como adicionar novas propriedades. Para adicionar propriedades personalizadas,[Adicionar método](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) de[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) classe adiciona a propriedade e retorna uma referência para a nova propriedade como um[Propriedades.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objeto. A classe DocumentProperty é usada para recuperar o nome, valor e tipo da propriedade do documento como[DocumentProperty.Nome](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) que retorna um dos[Tipo de Propriedade](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) valores de enumeração.
 
{{% blocks/products/pf/feature-page-code h3="Código C# para adicionar metadados em arquivo Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Código C# para remover propriedade personalizada em arquivo Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
