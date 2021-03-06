---
title: Converter CSV para JPEG via Java 
weight: 7490
url: /pt/java/conversion/csv-to-jpeg/ 
description: Exemplo de código de conversão Java para formato CSV para arquivo JPEG. Os programadores podem usar este código de exemplo para exportar planilhas do Excel e OpenOffice para JPEG em qualquer aplicativo baseado na Web ou Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter CSV para JPEG via Java" h2="Conversão de CSV para JPEG Java para converter uma ou várias páginas em JPEG usando a biblioteca local Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Como converter CSV para JPEG usando Java" %}}

 Para renderizar CSV para JPEG, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter CSV em JPEG via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java os desenvolvedores podem converter facilmente arquivos CSV para JPEG em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar arquivo CSV com uma instância da pasta de trabalho1. Selecione o padrão ou qualquer planilha da coleção1. Crie e defina o objeto de ImageOrPrintOptions1. Criar SheetRender com objetos Worksheet e ImageOrPrintOptions1. Chame o método SheetRender.toImage para salvar o resultado no formato JPEG
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte de conversão Java, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.- Obtenha a versão mais recente do Aspose.Cells for Java diretamente do Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de CSV para JPEG Java" offSpacer="" %}}

```cs
// carregue o arquivo CSV a ser renderizado
Workbook workbook = new Workbook("sourceFile.csv");
// acessar a planilha padrão da coleção
Worksheet worksheet = workbook.getWorksheets().get(0);
// definir parâmetros para a imagem resultante
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.JPEG);
// converter planilha para imagem no formato JPEG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.jpeg");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de CSV para JPEG" sectionDescription="[Converter CSV para JPEG](https://products.aspose.app/cells/conversion/csv-to-jpeg) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo CSV, ele será convertido instantaneamente para JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteca de manipulação de planilhas" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Arquivos com extensão CSV (Comma Separated Values) representam arquivos de texto simples que contêm registros de dados com valores separados por vírgulas. Cada linha em um arquivo CSV é um novo registro do conjunto de registros contido no arquivo. Esses arquivos são gerados quando a transferência de dados é pretendida de um sistema de armazenamento para outro. Como todos os aplicativos podem reconhecer registros separados por vírgula, a importação desses arquivos de dados para o banco de dados é feita de forma muito conveniente. Quase todos os aplicativos de planilhas, como o Microsoft Excel ou o OpenOffice Calc, podem importar CSV sem muito esforço. Os dados importados desses arquivos são organizados em células de uma planilha para representação ao usuário.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

Um JPEG é um tipo de formato de imagem que é salvo usando o método de compactação com perdas. A imagem de saída, como resultado da compactação, é uma compensação entre o tamanho do armazenamento e a qualidade da imagem. Os usuários podem ajustar o nível de compactação para atingir o nível de qualidade desejado e, ao mesmo tempo, reduzir o tamanho do armazenamento. A qualidade da imagem é afetada de forma insignificante se a compressão 10:1 for aplicada à imagem. Quanto maior o valor de compactação, maior a degradação na qualidade da imagem. O formato de arquivo de imagem JPEG foi padronizado pelo Joint Photographic Experts Group e, portanto, o nome JPEG. O formato tem sido a escolha de armazenamento e transmissão de imagens fotográficas na web. Quase todos os sistemas operacionais agora têm visualizadores que suportam a visualização de imagens JPEG, que geralmente também são armazenadas com extensão JPG. Até os navegadores da web suportam a visualização de imagens JPEG.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter CSV em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-bmp/" name="CSV PARA BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-dif/" name="CSV PARA DIF" description="Formato de intercâmbio de dados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-emf/" name="CSV PARA EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-gif/" name="CSV PARA GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-html/" name="CSV PARA HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-mhtml/" name="CSV PARA MHTML" description="Formato de arquivo de página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-ods/" name="CSV PARA ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-pdf/" name="CSV PARA PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-png/" name="CSV PARA PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-svg/" name="CSV para SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tiff/" name="CSV PARA TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tsv/" name="CSV para TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-txt/" name="CSV para TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlm/" name="CSV PARA XLM" description="Arquivo de macro do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xls/" name="CSV PARA XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsb/" name="CSV para XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsx/" name="CSV para XLSX" description="Arquivo OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlt/" name="CSV PARA XLT" description="Modelo do Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltm/" name="CSV PARA XLTM" description="Modelo habilitado para macro do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltx/" name="CSV PARA XLTX" description="Modelo Excel do Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xps/" name="CSV PARA XPS" description="Especificações do papel XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-json/" name="CSV para JSON" description="Notação de Objeto JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}