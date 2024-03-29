---
title:  Editar ou visualizar metadados de arquivos ODS via Java
weight: 2080
description: Código de amostra Java para editar ou visualizar metadados do formato ODS no Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.
keywords: [Java Aspose.Cells., Java view ods metadata., Java add ods metadata., Java insert ods metadata., Java edit ods metadata., Java remove ods metadata., Java extract ods metadata., Java modify ods metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extraia ODS Metadados via Java" h2="Crie seus próprios aplicativos Java para adicionar, editar, remover ou extrair metadados de arquivos ODS usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Como extrair metadados ODS usando Java" %}}

 Para obter metadados do arquivo ODS, usaremos
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, que é uma plataforma de metadados API for Java rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositório" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependência" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para extrair metadados de ODS via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Acesse informações úteis armazenadas no arquivo ODS, incluindo quando o arquivo ODS foi recebido, processado, marcado com data e hora e assim por diante.

{{% /blocks/products/pf/agp/text %}}

+ Carregue o arquivo ODS em WorkbookMetadata
+ Crie objeto MetadataOptions com opções relevantes
+ Defina as propriedades relevantes
+ Salve as informações de metadados ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java é compatível com todas as principais plataformas e sistemas operacionais. Certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.
-  Obtenha a versão mais recente de Aspose.Cells for Java diretamente de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extraia metadados de ODS - Java" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.ods", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.ods");

// Open the workbook
Workbook w = new Workbook("Sample1.out.ods");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for Java API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extraia metadados de ODS via aplicativo online" sectionDescription=" Visualize e edite metadados para documentos ODS usando nosso[Demonstrações ao vivo](https://products.aspose.app/cells/metadata) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta enviar seu arquivo ODS e editar as propriedades do documento" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtenha instantaneamente o link de download do arquivo resultante" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Arquivos com extensão ODS representam o formato de documento de planilha OpenDocument que pode ser editado pelo usuário. Os dados são armazenados dentro do arquivo ODF em linhas e colunas. É um formato baseado em XML e é um dos vários subtipos da família Open Document Formats (ODF). O formato é especificado como parte das especificações ODF 1.2 publicadas e mantidas pelo OASIS. Vários aplicativos no Windows, bem como em outros sistemas operacionais, podem abrir arquivos ODS para edição e manipulação, incluindo Microsoft Excel, NeoOffice e LibreOffice. Os arquivos ODS também podem ser convertidos em outros formatos de planilha, como XLS, XLSX e outros por diferentes aplicativos.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de metadados suportados" subTitle="Usando Java, também é possível manipular metadados de muitos outros formatos, incluindo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="Arquivo binário da pasta de trabalho do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
