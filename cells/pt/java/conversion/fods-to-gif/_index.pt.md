---
title: Converter FODS para GIF via Java 
url: /pt/java/conversion/fods-to-gif/ 
description: Exemplo de código de conversão Java para formato FODS para arquivo GIF. Os programadores podem usar este código de exemplo para exportar planilhas do Excel e OpenOffice para GIF em qualquer aplicativo baseado na Web ou Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter FODS para GIF via Java" h2="Conversão de FODS para GIF Java para converter uma ou várias páginas em GIF usando a biblioteca local Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Como converter FODS para GIF usando Java" %}}

 Para renderizar FODS para GIF, usaremos
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API que é uma plataforma de conversão API for Java rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente de
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter FODS em GIF via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java os desenvolvedores podem facilmente converter arquivos FODS para GIF em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar arquivo FODS com uma instância do Workbook1. Selecione o padrão ou qualquer planilha da coleção1. Crie e defina o objeto de ImageOrPrintOptions1. Criar SheetRender com objetos Worksheet e ImageOrPrintOptions1. Chame o método SheetRender.toImage para salvar o resultado no formato GIF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte de conversão Java, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.- Obtenha a versão mais recente do Aspose.Cells for Java diretamente do Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de FODS para GIF Java" offSpacer="" %}}

```cs
// carregue o arquivo FODS a ser renderizado
Workbook workbook = new Workbook("sourceFile.fods");
// acessar a planilha padrão da coleção
Worksheet worksheet = workbook.getWorksheets().get(0);
// definir parâmetros para a imagem resultante
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// converter planilha para imagem no formato GIF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de FODS para GIF" sectionDescription="[Converter FODS para GIF](https://products.aspose.app/cells/conversion/fods-to-gif) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo FODS, ele será convertido instantaneamente para GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteca de manipulação de planilhas" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FODS" readMoreLink="https://docs.fileformat.com/spreadsheet/fods/" >}}

Um arquivo com extensão .fods é um tipo de formato de documento OpenDocument Spreadsheet que armazena dados em linhas e colunas. O formato é especificado como parte das especificações ODF 1.2 publicadas e mantidas pelo OASIS. Os arquivos FODS não podem ser abertos com o Excel, outro aplicativo de software de planilha da Microsoft. Os arquivos FODS podem ser salvos como ODS usando o LibreOffice e podem ser convertidos para outros formatos, como XLS e XLSX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

Um GIF ou Graphical Interchange Format é um tipo de imagem altamente compactada. De propriedade da Unisys, o GIF usa o algoritmo de compactação LZW que não degrada a qualidade da imagem. Para cada imagem, o GIF normalmente permite até 8 bits por pixel e até 256 cores são permitidas na imagem. Em contraste com uma imagem JPEG, que pode exibir até 16 milhões de cores e toca bastante os limites do olho humano. Quando a internet surgiu, os GIFs continuaram sendo a melhor escolha porque exigiam baixa largura de banda e compatível com os gráficos que consomem áreas sólidas de cor. Um GIF animado combina várias imagens ou quadros em um único arquivo e os exibe em uma sequência para gerar um clipe animado ou um vídeo curto. As limitações de cores são de até 256 para cada quadro e provavelmente serão as menos adequadas para reproduzir outras imagens e fotografias com gradiente de cores.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}