---
title: Gerenciar metadados de arquivo Excel via Java
description: Visualize, adicione, edite, remova ou extraia metadados de arquivos Excel com apenas algumas linhas do código Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gerenciar metadados de arquivo Excel Microsoft<sup>&reg;</sup> via Java" h2="Visualize, adicione, atualize, exclua ou extraia propriedades personalizadas e integradas de arquivos do Excel usando APIs Java do lado do servidor." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java](/cells/pt/java/) suporta o gerenciamento de propriedades integradas (definidas pelo sistema), como título, nome do autor, estatísticas do documento, etc., bem como propriedades personalizadas (definidas pelo usuário) na forma de par nome/valor. Há[Aula de apostila](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) para carregar os arquivos e[Coleção de planilhas](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) lida com a coleta de planilhas, bem como[Aula de planilha](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) para representar uma única planilha. Para acessar propriedades integradas e personalizadas, BuiltInDocumentProperties, CustomDocumentProperties simplifica o processo de gerenciamento de metadados.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gerenciando propriedades definidas pelo sistema" %}}

 Para gerenciar propriedades integradas, API fornece[PropriedadesBuiltInDocument](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) e os programadores podem acessar facilmente uma propriedade integrada e atualizar seu valor. Dependendo dos requisitos do aplicativo, os desenvolvedores podem usar o índice ou o nome da propriedade do[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Código para gerenciar propriedades definidas pelo sistema" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Adicionar e remover metadados personalizados" %}}

Para lidar com propriedades personalizadas, API fornece[Propriedades de Documento Personalizado](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , e os desenvolvedores podem acessar facilmente as propriedades existentes, bem como adicionar novas propriedades usando[adicionar método](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) de[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) classe adiciona a propriedade e retorna uma referência para a nova propriedade como um[Propriedades.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objeto. A classe DocumentProperty é usada para recuperar o nome, valor e tipo da propriedade do documento como[DocumentProperty.Nome](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) que retorna um dos[Tipo de Propriedade](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) valores de enumeração.
 
{{% blocks/products/pf/feature-page-code h3="Código Java para adicionar metadados em arquivo Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Código para excluir propriedade personalizada em arquivo Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
