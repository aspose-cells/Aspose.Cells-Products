---
title: Converter CSV para MD por meio do aplicativo C++ 
url: /pt/cpp/conversion/csv-to-md/ 
description: Exemplo de código de conversão C++ de documento CSV para formato MD. Os programadores podem usar esse código-fonte para conversão em lote de CSV para MD em qualquer aplicativo C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter CSV para MD via C++" h2="Conversão de CSV para MD de alto desempenho usando a biblioteca C++ sem a necessidade de instalação do Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MD" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter CSV para MD usando C++" %}}

 Para converter CSV para MD, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter CSV em MD via C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ os desenvolvedores podem facilmente converter arquivos CSV para MD em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo CSV usando Factory::CreateIWorkbook.1. Chame o método Save().1. Passe o caminho do arquivo de saída com a extensão de arquivo (MD).1. arquivo MD será salvo no caminho especificado.1. Abra o arquivo MD em um programa compatível.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de amostra de conversão C++, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código-fonte de conversão de CSV para MD C++" offSpacer="" %}}

```cs
// Carregue o CSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");

// Salve no formato MD.
wkb->Save(u"convertedFile.md", SaveFormat_Md);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de CSV para MD" sectionDescription="[Converter CSV para MD](https://products.aspose.app/cells/conversion/csv-to-md) agora mesmo visitando nosso site de Demonstrações ao Vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do seu arquivo CSV, ele será convertido instantaneamente para MD." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Biblioteca de manipulação de arquivos do Excel" %}}

 Excel API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Arquivos com extensão CSV (Comma Separated Values) representam arquivos de texto simples que contêm registros de dados com valores separados por vírgulas. Cada linha em um arquivo CSV é um novo registro do conjunto de registros contido no arquivo. Esses arquivos são gerados quando a transferência de dados é pretendida de um sistema de armazenamento para outro. Como todos os aplicativos podem reconhecer registros separados por vírgula, a importação desses arquivos de dados para o banco de dados é feita de forma muito conveniente. Quase todos os aplicativos de planilhas, como o Microsoft Excel ou o OpenOffice Calc, podem importar CSV sem muito esforço. Os dados importados desses arquivos são organizados em células de uma planilha para representação ao usuário.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MD" readMoreLink="https://docs.fileformat.com/word-processing/md/" >}}

Arquivos de texto criados com dialetos de linguagem Markdown são salvos com extensão de arquivo .MD ou .MARKDOWN. Os arquivos MD são salvos em formato de texto simples que usa a linguagem Markdown, que também inclui símbolos de texto embutidos, definindo como um texto pode ser formatado, como recuos, formatação de tabela, fontes e cabeçalhos. Os arquivos MD podem ser convertidos em HTML com um programa chamado Markdown. A linguagem Markdown é lançada por John Gruber.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter CSV em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="CSV PARA BMP" description="Imagem em formato bitmap" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="CSV PARA DIF" description="Formato de intercâmbio de dados" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="CSV PARA EMF" description="Formato de metarquivo aprimorado" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="CSV PARA GIF" description="Formato de intercâmbio gráfico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="CSV PARA HTML" description="Linguagem de marcação de hipertexto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-jpeg/" name="CSV PARA JPEG" description="Imagem JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="CSV PARA MHTML" description="Formato de arquivo de página da Web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="CSV PARA ODS" description="Arquivo de planilha OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-pdf/" name="CSV PARA PDF" description="Formato de Documento Portátil" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="CSV PARA PNG" description="Gráficos Portáteis de Rede" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="CSV para SVG" description="Gráficos vetoriais escalonáveis" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="CSV PARA TIFF" description="Formato de imagem marcada" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="CSV para TSV" description="Valores separados por tabulação" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="CSV PARA XLS" description="Formato binário do Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsb/" name="CSV para XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="CSV PARA XLSM" description="Arquivo de planilha" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="CSV para XLSX" description="Arquivo OOXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="CSV PARA XLTM" description="Modelo habilitado para macro do Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="CSV PARA XLTX" description="Modelo Excel do Office OpenXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="CSV PARA XPS" description="Especificações do papel XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}