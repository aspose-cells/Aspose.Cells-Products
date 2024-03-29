---
title:  Desbloquear documento XLS via .NET
weight: 4260
description: Código-fonte C# para desbloquear o arquivo XLS protegido por senha nas plataformas .NET Framework, .NET Core, Mono ou Xamarin.
keywords: [C# Aspose.Cells., c# unlock XLS files., c# how to unlock XLS document., c# unprotect XLS files., remove protection from XLS files., decrypt XLS Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloquear planilha XLS via C#" h2="Remova a proteção de XLS usando a biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como desbloquear o arquivo XLS usando C#" %}}

 Para remover a proteção do arquivo XLS, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, que é um API de proteção de documentos rico em recursos, poderoso e fácil de usar para a plataforma C#. Abrir
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure por
 **Aspose.Cells** 
 e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Desbloqueie XLS através de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Você precisa
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 referenciado em seu projeto para executar o fluxo de trabalho a seguir.

{{% /blocks/products/pf/agp/text %}}

1.  Instancie a classe Workbook com caminho para o arquivo XLS protegido
1.  Obtenha o padrão ou qualquer planilha para remover a proteção
1.  Remova a proteção da planilha com o método Worksheet.Unprotect
1.  Remova a proteção da pasta de trabalho com o método Workbook.Unprotect
1.  Salvar resultado no formato XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Mono ou plataformas Xamarin
-  Ambiente de desenvolvimento como Microsoft Visual Studio
-  Adicione referência à DLL Aspose.Cells for .NET em seu projeto

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="" %}}

```cs

// instantiate a Workbook object with protected XLS file
var workbook = new Aspose.Cells.Workbook("protected.xls");

// access the default worksheet in the Excel file
var worksheet = workbook.Worksheets[0];

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLS format
workbook.Save("unprotected.xls", Aspose.Cells.SaveFormat.Auto);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para desbloquear XLS" sectionDescription=" Confira nossas demonstrações ao vivo para[desbloquear arquivos XLS](https://products.aspose.app/cells/unlock/xls) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer upload do arquivo XLS e clicar no botão \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo XLS resultante no link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Arquivos com extensão XLS representam o formato de arquivo binário do Excel. Esses arquivos podem ser criados pelo Microsoft Excel, bem como por outros programas de planilhas semelhantes, como OpenOffice Calc ou Apple Numbers. O arquivo salvo pelo Excel é conhecido como Pasta de trabalho, onde cada pasta de trabalho pode ter uma ou mais planilhas. Os dados são armazenados e exibidos aos usuários em formato de tabela na planilha e podem abranger valores numéricos, dados de texto, fórmulas, conexões de dados externos, imagens e gráficos. Aplicativos como Microsoft Excel permitem exportar dados da pasta de trabalho para vários formatos diferentes, incluindo PDF, CSV, XLSX, TXT, HTML, XPS e vários outros. O formato de arquivo XLS foi substituído por um formato mais aberto e estruturado, XLSX, com o lançamento do Microsoft Excel 2007. As versões mais recentes ainda oferecem suporte para criação e leitura de arquivos XLS, embora XLSX seja a primeira escolha para uso agora.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de desbloqueio suportados" subTitle="Usando C#, pode-se facilmente remover a proteção/desbloqueio de diferentes formatos, inclusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="Arquivo binário da pasta de trabalho do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
