---
title: Extraia texto e imagens do documento XLSB via C++
weight: 3140
description: Código de exemplo C++ para extrair texto e imagens do arquivo XLSB em C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
keywords: [C++ Aspose.Cells., C++ Extract text and images from XLSB file., C++ How to Parse XLSB File., C++ Extract text from XLSB file., Extract images from XLSB file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Analisar formatos XLSB em C++" h2="Análise de documento XLSB nativa e de alto desempenho usando APIs Aspose.Cells for C++ do lado do servidor, sem o uso de qualquer software como Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como analisar o arquivo XLSB usando C++" %}}

 Para analisar o arquivo XLSB, usaremos[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API, que é uma plataforma API for C++ de análise de documentos rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente, basta abrir[NuGet](https://www.nuget.org/packages/aspose.cells) gerenciador de pacotes, procure por**Aspose.Cells.Cpp** e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para analisar arquivos XLSB em C++" %}}

{{% blocks/products/pf/agp/text %}}

 Uma análise básica de documentos com[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)APIs podem ser feitas com apenas algumas linhas de código. Analise texto e imagens de arquivos Microsoft Excel XLS, XLSX, XLSM, XLSB e OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ é compatível com todas as principais plataformas e sistemas operacionais. Certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows 32 bits, Windows 64 bits e Linux 64 bits.
-  Adicione referência à DLL Aspose.Cells for C++ em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analisar arquivos XLSB - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.xlsb");

// get the first worksheet
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// get the first Picture in the first worksheet
Picture pic = worksheet.GetPictures().Get(0);

// Note: you may evaluate the image format before specifying the image path
// define ImageOrPrintOptions
ImageOrPrintOptions printoption;

// specify the image format
printoption.SetImageType(ImageType::Jpeg);

// save the image
pic.ToImage(u"outputExtractImagesFromWorksheets.jpg", printoption);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for C++ API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo do analisador on-line XLSB" sectionDescription="Extraia texto e imagens de documentos XLSB agora mesmo visitando nosso[Site de demonstrações ao vivo](https://products.aspose.app/cells/parser). A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta enviar seus arquivos XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ele será analisado instantaneamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
 formato de arquivo XLSB especifica o formato de arquivo binário do Excel, que é uma coleção de registros e estruturas que especificam o conteúdo da pasta de trabalho do Excel. O conteúdo pode incluir tabelas de números não estruturadas ou semiestruturadas, texto ou números e texto, fórmulas, conexões de dados externos, gráficos e imagens. Ao contrário de XLSX (que é baseado no formato de arquivo Open XML), XLSB representa um arquivo binário da pasta de trabalho do Excel. Os arquivos XLSB podem ser lidos e gravados com mais rapidez, o que os torna úteis para trabalhar com arquivos grandes. XLSB raramente é usado para armazenar pastas de trabalho, pois XLSX (e anteriormente XLS) são os formatos de arquivo mais comuns selecionados pelo usuário para salvar pastas de trabalho. Ele pode ser aberto pelo Microsoft Office 2007 e superior.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros documentos de análise suportados" subTitle="Usando C++, é possível analisar facilmente outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
