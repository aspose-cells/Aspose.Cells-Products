---
title: Desbloqueie o documento XLSB via Java 
weight: 5860
url: /pt/java/unlock/xlsb/ 
description: Java código de amostra para desbloquear arquivo XLSB protegido por senha no Java ambiente de tempo de execução para aplicativos JSP/JSF e aplicativos de desktop.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloqueie arquivos XLSB via Java" h2="Remova a proteção de planilhas do Excel, incluindo arquivo XLSB, usando a biblioteca Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Como remover o arquivo XLSB de proteção usando Java" %}}

 Para desbloquear o arquivo XLSB, usaremos
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API que é uma plataforma de proteção API for Java rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente de
 [Especialista](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositório" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositório.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para desbloquear XLSB via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Instanciar a classe Workbook com caminho para o arquivo XLSB protegido1. Obtenha o padrão ou qualquer planilha para remover a proteção1. Remova a proteção da planilha com o método Worksheet.Unprotect1. Remova a proteção da pasta de trabalho com o método Workbook.Unprotect1. Salvar resultado no formato XLSB
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java é compatível com todas as principais plataformas e sistemas operacionais. Verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Desbloqueie arquivos XLSB via C#" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xlsb");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// Desprotegendo o XLSB
wks.unprotect();

// Salve o arquivo XLSB.
wkb.save("Worksheet_out.xlsb", FileFormatType.EXCEL_97_TO_2003);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for Java API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para desbloquear XLSB" sectionDescription="Confira nossas demonstrações ao vivo para [desbloquear arquivos XLSB](https://products.aspose.app/cells/unlock/xlsb) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do arquivo XLSB e clicar no botão \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo XLSB resultante do link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
O formato de arquivo XLSB especifica o formato de arquivo binário do Excel, que é uma coleção de registros e estruturas que especificam o conteúdo da pasta de trabalho do Excel. O conteúdo pode incluir tabelas de números não estruturadas ou semiestruturadas, texto ou ambos, números e texto, fórmulas, conexões de dados externos, gráficos e imagens. Ao contrário do XLSX (que é baseado no formato de arquivo Open XML), o XLSB representa o arquivo binário da pasta de trabalho do Excel. Os arquivos XLSB podem ser lidos e gravados mais rapidamente, o que os torna úteis para trabalhar com arquivos grandes. XLSB raramente é usado para armazenar pastas de trabalho, pois XLSX (e anteriormente XLS) são os formatos de arquivo selecionados pelo usuário mais comuns para salvar pastas de trabalho. Ele pode ser aberto pelo Microsoft Office 2007 e superior.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de desbloqueio suportados" subTitle="Usando Java, pode-se remover facilmente a proteção / desbloqueio de diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsx/" name="XLSX" description="Arquivo OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}