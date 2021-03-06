---
title: Converter TSV para HTML por meio do aplicativo C++ 
weight: 4980
url: /pt/cpp/conversion/tsv-to-html/ 
description: Exemplo de código de conversão C++ de documento TSV para formato HTML. Os programadores podem usar esse código-fonte para conversão em lote de TSV para HTML em qualquer aplicativo C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter TSV para HTML via C++" h2="Conversão de TSV para HTML de alto desempenho usando a biblioteca C++ sem a necessidade de instalação do Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter TSV para HTML usando C++" %}}

 Para converter TSV para HTML, usaremos
 [Aspose.Cells para C++](https://products.aspose.com/cells/cpp) 
 API que é uma plataforma de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar API para C++. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGetName](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure
 Aspose.Cells.Cpp 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter TSV em HTML via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ os desenvolvedores podem converter facilmente arquivos TSV em HTML em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo TSV usando Factory::CreateIWorkbook.1. Chame o método Save().1. Passe o caminho do arquivo de saída com extensão de arquivo (HTML).1. arquivo HTML será salvo no caminho especificado.1. Abra o arquivo HTML em um programa compatível.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de amostra de conversão C++, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de TSV para HTML C++" offSpacer="" %}}

```cs
// Carregue o TSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");

// Salve em formato HTML.
wkb->Save(u"convertedFile.html", SaveFormat_Html);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de TSV para HTML" sectionDescription="[Converter TSV para HTML](https://products.aspose.app/cells/conversion/tsv-to-html) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo TSV, ele será convertido instantaneamente para HTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulação de arquivos do Excel" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Um formato de arquivo de valores separados por tabulação (TSV) representa dados separados por tabulações em formato de texto simples. O formato de arquivo, semelhante ao CSV, é utilizado para organização dos dados de forma estruturada para importação e exportação entre diferentes aplicações. O formato é usado principalmente para importação/exportação e troca de dados em aplicativos e bancos de dados de planilhas. Cada registro em um arquivo TSV está contido em uma única linha de arquivo de texto onde cada valor de campo é separado por um caractere de tabulação. O tipo de mídia para o formato de arquivo TSV é texto/valores separados por tabulação.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) é a extensão para páginas da web criadas para exibição em navegadores. Conhecido como linguagem da web, o HTML evoluiu com novas exigências de informações para serem exibidas como parte das páginas da web. A variante mais recente é conhecida como HTML 5, que oferece muita flexibilidade para trabalhar com a linguagem. As páginas HTML são recebidas do servidor, onde estão hospedadas, ou também podem ser carregadas do sistema local. Cada página HTML é composta por elementos HTML como formulários, texto, imagens, animações, links, etc. Esses elementos são representados por tags como img, a, pe várias outras onde cada tag tem início e fim. Ele também pode incorporar aplicativos escritos em linguagens de script, como JavaScript e Folhas de Estilo (CSS) para representação geral do layout.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter TSV em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-bmp/" name="TSV PARA BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-csv/" name="TSV PARA CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-dif/" name="TSV PARA DIF" description="Formato de intercâmbio de dados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-emf/" name="TSV PARA EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-gif/" name="TSV PARA GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-jpeg/" name="TSV PARA JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-mhtml/" name="TSV PARA MHTML" description="Formato de arquivo de página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-ods/" name="TSV PARA ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-pdf/" name="TSV PARA PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-png/" name="TSV PARA PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-svg/" name="TSV PARA SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-tiff/" name="TSV PARA TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xls/" name="TSV PARA XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsb/" name="TSV PARA XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsm/" name="TSV PARA XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsx/" name="TSV PARA XLSX" description="Arquivo OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltm/" name="TSV PARA XLTM" description="Modelo habilitado para macro do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltx/" name="TSV PARA XLTX" description="Modelo Excel do Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xps/" name="TSV PARA XPS" description="Especificações do papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}