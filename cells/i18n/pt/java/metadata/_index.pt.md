---
title: Gerenciar metadados de arquivos do Excel por meio de Java
url: /pt/java/metadata/
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos do Excel com apenas algumas linhas de código Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar metadados de arquivos do Microsoft<sup>&reg;</sup> por meio de Java" h2="Visualize, adicione, atualize, exclua ou extraia propriedades de arquivo do Excel personalizadas e integradas usando APIs Java do lado do servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java ExcelAPI](/cells/java/) suporta o gerenciamento de propriedades internas (definidas pelo sistema), como título, nome do autor, estatísticas do documento, etc., bem como propriedades personalizadas (definidas pelo usuário) na forma de par nome/valor. Há [Aula de pasta de trabalho](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) para carregar os arquivos e [Coleção de planilhas](https://apireference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) lida com a coleta de planilhas, bem como [Aula de planilha](https://apireference.aspose.com/cells/java/com.aspose.cells/Worksheet) para representar planilha única. Para acessar propriedades internas e personalizadas, BuiltInDocumentProperties, CustomDocumentProperties simplifica o processo de gerenciamento de metadados. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gerenciando Propriedades Definidas pelo Sistema" %}}

Para gerenciar propriedades integradas, API fornece [BuiltInDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), e os programadores podem acessar facilmente uma propriedade interna e atualizar seu valor. Dependendo do requisito do aplicativo, os desenvolvedores podem usar o índice ou o nome da propriedade do [DocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Código para gerenciar propriedades definidas pelo sistema" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Adicionar e remover metadados definidos personalizados" %}}

Para lidar com propriedades personalizadas, API fornece [Propriedades do documento personalizado](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), e os desenvolvedores podem acessar facilmente as propriedades existentes, bem como adicionar novas propriedades usando [adicionar método](https://apireference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) de [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class adiciona a propriedade e retorna uma referência para a nova propriedade como um [Propriedades.DocumentoPropriedade](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objeto. A classe DocumentProperty é usada para recuperar o nome, valor e tipo da propriedade do documento como [DocumentProperty.Name](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) que retorna um dos [Tipo de Propriedade](https://apireference.aspose.com/cells/java/com.aspose.cells/PropertyType) valores de enumeração. 
 
{{% blocks/products/pf/feature-page-code h3="Java Código para adicionar metadados no arquivo Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Código para excluir propriedade personalizada no arquivo Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
