---
title: Converter HTML para MHTML por meio do aplicativo C++ 
weight: 4130
url: /pt/cpp/conversion/html-to-mhtml/ 
description: Exemplo de código de conversão C++ de documento HTML para formato MHTML. Os programadores podem usar esse código-fonte para conversão em lote de HTML para MHTML em qualquer aplicativo C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter HTML para MHTML via C++" h2="Conversão de HTML para MHTML de alto desempenho usando a biblioteca C++ sem a necessidade de instalação do Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter HTML para MHTML usando C++" %}}

 Para converter HTML para MHTML, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter HTML em MHTML via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ os desenvolvedores podem converter facilmente arquivos HTML em MHTML em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo HTML usando Factory::CreateIWorkbook.1. Chame o método Save().1. Passe o caminho do arquivo de saída com extensão de arquivo (MHTML).1. O arquivo MHTML será salvo no caminho especificado.1. Abra o arquivo MHTML em um programa compatível.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de amostra de conversão C++, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de HTML para MHTML C++" offSpacer="" %}}

```cs
// Carregue o HTML.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.html");

// Salve no formato MHTML.
wkb->Save(u"convertedFile.mhtml", SaveFormat_Mhtml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de HTML para MHTML" sectionDescription="[Converter HTML para MHTML](https://products.aspose.app/cells/conversion/html-to-mhtml) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo HTML, ele será convertido instantaneamente para MHTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulação de arquivos do Excel" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) é a extensão para páginas da web criadas para exibição em navegadores. Conhecido como linguagem da web, o HTML evoluiu com novas exigências de informações para serem exibidas como parte das páginas da web. A variante mais recente é conhecida como HTML 5, que oferece muita flexibilidade para trabalhar com a linguagem. As páginas HTML são recebidas do servidor, onde estão hospedadas, ou também podem ser carregadas do sistema local. Cada página HTML é composta por elementos HTML como formulários, texto, imagens, animações, links, etc. Esses elementos são representados por tags como img, a, pe várias outras onde cada tag tem início e fim. Ele também pode incorporar aplicativos escritos em linguagens de script, como JavaScript e Folhas de Estilo (CSS) para representação geral do layout.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Arquivos com extensão MHTML representam um formato de arquivo de página da web que pode ser criado por vários aplicativos diferentes. O formato é conhecido como formato de arquivo porque salva o código HTML da Web e os recursos associados em um único arquivo. Esses recursos incluem qualquer coisa vinculada à página da Web, como imagens, applets, animações, arquivos de áudio e assim por diante. Os arquivos MHTML podem ser abertos em vários aplicativos, como Internet Explorer e Microsoft Word. O Microsoft Windows usa o formato de arquivo MHTML para registrar cenários de problemas observados durante o uso de qualquer aplicativo no Windows que levante problemas. O formato de arquivo MHTML codifica o conteúdo da página de forma semelhante às especificações definidas em message/rfc822, que são especificações relacionadas a e-mail de texto simples. As especificações reais do formato são detalhadas pela RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter HTML em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML PARA BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML PARA CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="HTML PARA DIF" description="Formato de intercâmbio de dados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-emf/" name="HTML PARA EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-gif/" name="HTML PARA GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-jpeg/" name="HTML PARA JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-ods/" name="HTML PARA ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-pdf/" name="HTML PARA PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-png/" name="HTML PARA PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-svg/" name="HTML PARA SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tiff/" name="HTML PARA TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tsv/" name="HTML PARA TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xls/" name="HTML PARA XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsb/" name="HTML PARA XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsm/" name="HTML PARA XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsx/" name="HTML PARA XLSX" description="Arquivo OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltm/" name="HTML PARA XLTM" description="Modelo habilitado para macro do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltx/" name="HTML PARA XLTX" description="Modelo Excel do Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xps/" name="HTML PARA XPS" description="Especificações do papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}