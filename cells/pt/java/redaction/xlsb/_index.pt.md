---
title:  Pesquise e substitua texto no documento XLSB via Java
weight: 4590
description: Código de amostra Java para editar informações confidenciais no arquivo XLSB no Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.
keywords: [Java Aspose.Cells., Java Search and replace text in XLSB file., Java redact XLSB file., Java edit XLSB file., Java XLSB file redaction., Java Search and replace string in XLSB file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Editar formatos XLSB em Java" h2="Informações de redação confidenciais de documentos XLSB nativos e de alto desempenho usando APIs Aspose.Cells for Java do lado do servidor, sem o uso de qualquer software como Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Como redigir o arquivo XLSB usando Java" %}}

 Para redigir o arquivo XLSB, usaremos[Aspose.Cells for Java](https://products.aspose.com/cells/java) API, que é uma plataforma de redação API for Java rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente de[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para redigir arquivos XLSB em Java" %}}

{{% blocks/products/pf/agp/text %}}

 Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários ou metadados por[Aspose.Cells for Java](https://products.aspose.com/cells/java) APIs podem ser feitas com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+ Carregue o arquivo XLSB.
+ Selecione a planilha relevante.
+ Definir e especificar FindOptions.
+ Especifique o intervalo onde deseja pesquisar
Percorra cada célula e use getCells().find(...).
+ Substitua o valor.
+ Salve a pasta de trabalho.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java é compatível com todas as principais plataformas e sistemas operacionais. Certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.
-  Obtenha a versão mais recente de Aspose.Cells for Java diretamente de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Editar arquivos XLSB - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.xlsb");

Worksheet worksheet = workbook.getWorksheets().get(0);

// Specify the range where you want to search
// Here the range is E3:H6
CellArea area = CellArea.createCellArea("E3", "H6");

// Specify Find options
FindOptions opts = new FindOptions();
opts.setLookInType(LookInType.VALUES);
opts.setLookAtType(LookAtType.ENTIRE_CONTENT);
opts.setRange(area);

Cell cell = null;

do {
	// Search the cell with value search within range
	cell = worksheet.getCells().find("search", cell, opts);

	// If no such cell found, then break the loop
	if (cell == null)
		break;

	// Replace the cell with value replace
	cell.putValue("replace");

} while (true);

// Save the workbook
workbook.save(dataDir + "output.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for Java API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de redação on-line XLSB" sectionDescription=" Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos XLSB agora mesmo, visitando nosso[Site de demonstrações ao vivo](https://products.aspose.app/cells/redaction). A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta enviar seus arquivos XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ele será redigido instantaneamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
 formato de arquivo XLSB especifica o formato de arquivo binário do Excel, que é uma coleção de registros e estruturas que especificam o conteúdo da pasta de trabalho do Excel. O conteúdo pode incluir tabelas de números não estruturadas ou semiestruturadas, texto ou números e texto, fórmulas, conexões de dados externos, gráficos e imagens. Ao contrário de XLSX (que é baseado no formato de arquivo Open XML), XLSB representa um arquivo binário da pasta de trabalho do Excel. Os arquivos XLSB podem ser lidos e gravados com mais rapidez, o que os torna úteis para trabalhar com arquivos grandes. XLSB raramente é usado para armazenar pastas de trabalho, pois XLSX (e anteriormente XLS) são os formatos de arquivo mais comuns selecionados pelo usuário para salvar pastas de trabalho. Ele pode ser aberto pelo Microsoft Office 2007 e superior.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros documentos de redação suportados" subTitle="Usando Java, é possível redigir facilmente diferentes formatos, inclusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
