---
title: Converter MHTML para BMP por meio do aplicativo C++ 
weight: 1020
url: /pt/cpp/conversion/mhtml-to-bmp/ 
description: Exemplo de código de conversão C++ de documento MHTML para formato BMP. Os programadores podem usar esse código-fonte para conversão em lote de MHTML para BMP em qualquer aplicativo C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter MHTML para BMP via C++" h2="Conversão de MHTML para BMP de alto desempenho usando a biblioteca C++ sem a necessidade de instalação do Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter MHTML para BMP usando C++" %}}

 Para converter MHTML para BMP, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter MHTML em BMP via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ os desenvolvedores podem converter facilmente arquivos MHTML em BMP em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo MHTML usando Factory::CreateIWorkbook.1. Selecione a primeira planilha.1. Definir opções (BMP).1. Itere através de cada página da planilha e renderize.1. Abra o arquivo BMP em um programa compatível.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de amostra de conversão C++, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de MHTML para BMP C++" offSpacer="" %}}

```cs
// Caminho do diretório de saída.
StringPtr outDir = new String("OutputDirectoryPath");

// Carregue o MHTML.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.mhtml");

// Acesse a primeira planilha.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Criar imagem ou objeto de opções de impressão.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Especifique o formato da imagem.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetBmp());

// Especifique a resolução horizontal e vertical
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderize a folha em relação à imagem especificada ou às opções de impressão.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Obter contagem de páginas.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Crie um objeto construtor de strings para concatenações de strings.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderize cada página para a imagem bmp uma por uma.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageBMP_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".bmp"));

	// Obtenha o caminho da imagem de saída.
	StringPtr outputBMP = sb->ToString();

	// Converter planilha em imagem bmp.
	sr->ToImage(i, outputBMP);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de MHTML para BMP" sectionDescription="[Converter MHTML para BMP](https://products.aspose.app/cells/conversion/mhtml-to-bmp) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo MHTML, ele será convertido instantaneamente para BMP." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulação de arquivos do Excel" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Arquivos com extensão MHTML representam um formato de arquivo de página da web que pode ser criado por vários aplicativos diferentes. O formato é conhecido como formato de arquivo porque salva o código HTML da Web e os recursos associados em um único arquivo. Esses recursos incluem qualquer coisa vinculada à página da Web, como imagens, applets, animações, arquivos de áudio e assim por diante. Os arquivos MHTML podem ser abertos em vários aplicativos, como Internet Explorer e Microsoft Word. O Microsoft Windows usa o formato de arquivo MHTML para registrar cenários de problemas observados durante o uso de qualquer aplicativo no Windows que levante problemas. O formato de arquivo MHTML codifica o conteúdo da página de forma semelhante às especificações definidas em message/rfc822, que são especificações relacionadas a e-mail de texto simples. As especificações reais do formato são detalhadas pela RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

Arquivos com extensão .BMP representam arquivos de imagem de bitmap que são usados para armazenar imagens digitais de bitmap. Essas imagens são independentes do adaptador gráfico e também são chamadas de formato de arquivo de bitmap independente de dispositivo (DIB). Essa independência serve para abrir o arquivo em várias plataformas, como Microsoft Windows e Mac. O formato de arquivo BMP pode armazenar dados como imagens digitais bidimensionais em formato monocromático e colorido com várias profundidades de cor.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter MHTML em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-csv/" name="MHTML PARA CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-dif/" name="MHTML PARA DIF" description="Formato de intercâmbio de dados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-emf/" name="MHTML PARA EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-gif/" name="MHTML PARA GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-html/" name="MHTML PARA HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-jpeg/" name="MHTML PARA JPEG" description="Imagem JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-ods/" name="MHTML PARA ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-pdf/" name="MHTML PARA PDF" description="Formato de Documento Portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-png/" name="MHTML PARA PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-svg/" name="MHTML PARA SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tiff/" name="MHTML PARA TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tsv/" name="MHTML PARA TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xls/" name="MHTML PARA XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsb/" name="MHTML PARA XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsm/" name="MHTML PARA XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsx/" name="MHTML PARA XLSX" description="Arquivo OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltm/" name="MHTML PARA XLTM" description="Modelo habilitado para macro do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltx/" name="MHTML PARA XLTX" description="Modelo Excel do Office OpenXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xps/" name="MHTML PARA XPS" description="Especificações do papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}