---
title:  Extraia texto e imagens do documento XLS via .NET
weight: 5600
description: Código-fonte C# para extrair texto e imagens do arquivo XLS em .NET Framework, .NET Core, Mono ou plataformas Xamarin.
keywords: [C# Aspose.Cells., c# Extract text and images from XLS file., c# How to Parse XLS File., c# Extract text from XLS file., Extract images from XLS file using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Analisar formatos XLS em C#" h2="Análise de documento XLS nativa e de alto desempenho usando APIs Aspose.Cells for .NET do lado do servidor, sem o uso de qualquer software como Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como analisar o arquivo XLS usando C#" %}}

 Para analisar o arquivo XLS, usaremos[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API, que é um API de manipulação de documentos rico em recursos, poderoso e fácil de usar para a plataforma C#. Abrir[NuGet](https://www.nuget.org/packages/aspose.cells) gerenciador de pacotes, procure por
 **Aspose.Cells** e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para analisar arquivos XLS em C#" %}}

{{% blocks/products/pf/agp/text %}}

 Uma análise básica de documentos com[Aspose.Cells for .NET](https://products.aspose.com/cells/net)APIs podem ser feitas com apenas algumas linhas de código. Analise texto e imagens de arquivos Microsoft Excel XLS, XLSX, XLSM, XLSB e OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ Carregue o documento XLS.
+ Selecione a planilha.
+ Obtenha a imagem e o tipo de imagem.
+ Salve a imagem.
+ Salvar documento

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, certifique-se de ter os seguintes pré-requisitos em seu sistema.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Mono ou plataformas Xamarin
-  Ambiente de desenvolvimento como Microsoft Visual Studio
-  Adicione referência à DLL Aspose.Cells for .NET em seu projeto - Instale a partir de NuGet usando o botão Download acima

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analisar arquivos XLS - C#" offSpacer="" %}}

```cs
    // extract images from Worksheets 
    // open a template Excel file
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xls");
    
    // get the first worksheet
    Worksheet worksheet = workbook.Worksheets[0];
    
    // get the first Picture in the first worksheet
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // set the output image file path
    string picformat = pic.ImageType.ToString();
                
    // Note: you may evaluate the image format before specifying the image path
    // define ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // specify the image format
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // save the image
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo do analisador on-line XLS" sectionDescription="Extraia texto e imagens de documentos XLS agora mesmo visitando nosso[Site de demonstrações ao vivo](https://products.aspose.app/cells/parser). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta enviar seus arquivos XLS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ele será analisado instantaneamente." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Arquivos com extensão XLS representam o formato de arquivo binário do Excel. Esses arquivos podem ser criados pelo Microsoft Excel, bem como por outros programas de planilhas semelhantes, como OpenOffice Calc ou Apple Numbers. O arquivo salvo pelo Excel é conhecido como Pasta de trabalho, onde cada pasta de trabalho pode ter uma ou mais planilhas. Os dados são armazenados e exibidos aos usuários em formato de tabela na planilha e podem abranger valores numéricos, dados de texto, fórmulas, conexões de dados externos, imagens e gráficos. Aplicativos como Microsoft Excel permitem exportar dados da pasta de trabalho para vários formatos diferentes, incluindo PDF, CSV, XLSX, TXT, HTML, XPS e vários outros. O formato de arquivo XLS foi substituído por um formato mais aberto e estruturado, XLSX, com o lançamento do Microsoft Excel 2007. As versões mais recentes ainda oferecem suporte para criação e leitura de arquivos XLS, embora XLSX seja a primeira escolha para uso agora.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de análise suportados" subTitle="Usando C#, é possível analisar facilmente outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="Arquivo binário da pasta de trabalho do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
