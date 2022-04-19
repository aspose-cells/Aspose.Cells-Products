---
title: Gerenciar metadados de arquivos do Excel por meio de .NET C#
url: /pt/net/metadata/
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos do Excel com apenas algumas linhas de código C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar metadados de arquivos do Microsoft<sup>&reg;</sup> por meio de .NET" h2="Visualize, adicione, atualize, remova ou extraia propriedades de arquivo do Excel integradas e personalizadas usando APIs .NET do lado do servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET ExcelAPI](/cells/net/) suporta o gerenciamento de propriedades definidas pelo sistema (embutidas), como título, nome do autor, estatísticas do documento, etc., bem como propriedades definidas pelo usuário (personalizadas) na forma de par nome-valor. Há [Aula de pasta de trabalho](https://apireference.aspose.com/cells/net/aspose.cells/workbook) para carregar os arquivos e [Coleção de planilhas](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) lida com a coleta de planilhas, bem como [Aula de planilha](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) para representar planilha única. Junto com essas classes, BuiltInDocumentProperties, CustomDocumentProperties simplifica o processo de gerenciamento de metadados. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gerenciando Propriedades Integradas" %}}

Para gerenciar propriedades definidas pelo sistema, API fornece [BuiltInDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), e os programadores podem acessar facilmente uma propriedade interna e atualizar seu valor. Dependendo do requisito do aplicativo, os desenvolvedores podem usar o índice ou o nome da propriedade do [DocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Código para gerenciar propriedades integradas" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gerenciando Propriedades Definidas Personalizadas" %}}

Para gerenciar propriedades definidas pelo usuário, API fornece [Propriedades do documento personalizado](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), e os desenvolvedores podem acessar facilmente as propriedades já adicionadas, bem como adicionar novas propriedades. Para adicionar propriedades personalizadas, [Adicionar método](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) de [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class adiciona a propriedade e retorna uma referência para a nova propriedade como um [Propriedades.DocumentoPropriedade](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objeto. A classe DocumentProperty é usada para recuperar o nome, valor e tipo da propriedade do documento como [DocumentProperty.Name](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) que retorna um dos [Tipo de Propriedade](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) valores de enumeração. 
 
{{% blocks/products/pf/feature-page-code h3="C# Código para adicionar metadados no arquivo Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Código para remover propriedade personalizada em arquivo Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
