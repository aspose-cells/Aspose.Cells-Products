---
title: Converter HTML para GIF por meio do aplicativo C++ 
weight: 6750
url: /pt/cpp/conversion/html-to-gif/ 
description: Exemplo de código de conversão C++ de documento HTML para formato GIF. Os programadores podem usar esse código-fonte para conversão em lote de HTML para GIF em qualquer aplicativo C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter HTML em GIF por meio de C++" h2="Conversão de HTML para GIF de alto desempenho usando a biblioteca C++ sem a necessidade de instalação do Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter HTML para GIF usando C++" %}}

 Para converter HTML para GIF, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter HTML em GIF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ os desenvolvedores podem converter facilmente arquivos HTML em GIF em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo HTML usando Factory::CreateIWorkbook.1. Selecione a primeira planilha.1. Definir opções (GIF).1. Itere através de cada página da planilha e renderize.1. Abra o arquivo GIF em um programa compatível.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de amostra de conversão C++, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de HTML para GIF C++" offSpacer="" %}}

```cs
// Caminho do diretório de saída.
StringPtr outDir = new String("OutputDirectoryPath");

// Carregue o HTML.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.html");

// Acesse a primeira planilha.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Criar imagem ou objeto de opções de impressão.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Especifique o formato da imagem.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetGif());

// Especifique a resolução horizontal e vertical
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderize a folha em relação à imagem especificada ou às opções de impressão.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Obter contagem de páginas.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Crie um objeto construtor de strings para concatenações de strings.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderize cada página para imagem gif, uma por uma.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageGIF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".gif"));

	// Obtenha o caminho da imagem de saída.
	StringPtr outputGIF = sb->ToString();

	// Converter planilha em imagem gif.
	sr->ToImage(i, outputGIF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de HTML para GIF" sectionDescription="[Converter HTML para GIF](https://products.aspose.app/cells/conversion/html-to-gif) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo HTML, ele será convertido instantaneamente para GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulação de arquivos do Excel" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) é a extensão para páginas da web criadas para exibição em navegadores. Conhecido como linguagem da web, o HTML evoluiu com novas exigências de informações para serem exibidas como parte das páginas da web. A variante mais recente é conhecida como HTML 5, que oferece muita flexibilidade para trabalhar com a linguagem. As páginas HTML são recebidas do servidor, onde estão hospedadas, ou também podem ser carregadas do sistema local. Cada página HTML é composta por elementos HTML como formulários, texto, imagens, animações, links, etc. Esses elementos são representados por tags como img, a, pe várias outras onde cada tag tem início e fim. Ele também pode incorporar aplicativos escritos em linguagens de script, como JavaScript e Folhas de Estilo (CSS) para representação geral do layout.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

Um GIF ou Graphical Interchange Format é um tipo de imagem altamente compactada. De propriedade da Unisys, o GIF usa o algoritmo de compactação LZW que não degrada a qualidade da imagem. Para cada imagem, o GIF normalmente permite até 8 bits por pixel e até 256 cores são permitidas na imagem. Em contraste com uma imagem JPEG, que pode exibir até 16 milhões de cores e toca bastante os limites do olho humano. Quando a internet surgiu, os GIFs continuaram sendo a melhor escolha porque exigiam baixa largura de banda e compatível com os gráficos que consomem áreas sólidas de cor. Um GIF animado combina várias imagens ou quadros em um único arquivo e os exibe em uma sequência para gerar um clipe animado ou um vídeo curto. As limitações de cores são de até 256 para cada quadro e provavelmente serão as menos adequadas para reproduzir outras imagens e fotografias com gradiente de cores.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter HTML em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML PARA BMP" description="Imagem em formato bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML PARA CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="HTML PARA DIF" description="Formato de intercâmbio de dados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-emf/" name="HTML PARA EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-jpeg/" name="HTML PARA JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-mhtml/" name="HTML PARA MHTML" description="Formato de arquivo de página da Web" >}}
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