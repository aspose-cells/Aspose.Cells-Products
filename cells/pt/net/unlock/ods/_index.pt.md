---
title: Desbloqueie o documento ODS via .NET 
weight: 3110
url: /pt/net/unlock/ods/ 
description: C# código-fonte para desbloquear o arquivo ODS protegido por senha em plataformas .NET Framework, .NET Core, Mono ou Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloqueie a planilha ODS via C#" h2="Remova a proteção do ODS usando a biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como desbloquear o arquivo ODS usando C#" %}}

 Para remover o arquivo ODS de proteção, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API que é uma plataforma de proteção de documentos API rica em recursos, poderosa e fácil de usar para C#. Aberto
 [NuGetName](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure
 **Aspose.Cells** 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Desbloqueie ODS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Você precisa
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 referenciado em seu projeto para executar o fluxo de trabalho a seguir.

{{% /blocks/products/pf/agp/text %}}

1. Instanciar a classe Workbook com caminho para o arquivo ODS protegido1. Obtenha o padrão ou qualquer planilha para remover a proteção1. Remova a proteção da planilha com o método Worksheet.Unprotect1. Remova a proteção da pasta de trabalho com o método Workbook.Unprotect1. Salvar resultado no formato ODS
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Mono ou Xamarin- Ambiente de desenvolvimento como o Microsoft Visual Studio- Aspose.Cells for .NET referenciado em seu projeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="" %}}

```cs

// instanciar um objeto Workbook com arquivo ODS protegido
var workbook = new Aspose.Cells.Workbook("protected.ods");

// acessar a planilha padrão no arquivo Excel
var worksheet = workbook.Worksheets[0];

// desproteger planilha sem senha
worksheet.Unprotect();

// desproteger pasta de trabalho com senha
workbook.Unprotect("password");

// salve o resultado de volta no formato ODS
workbook.Save("unprotected.ods", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para desbloquear ODS" sectionDescription="Confira nossas demonstrações ao vivo para [desbloquear arquivos ODS](https://products.aspose.app/cells/unlock/ods) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do arquivo ODS e clicar no botão \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo ODS resultante do link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Arquivos com extensão ODS representam o formato OpenDocument Spreadsheet Document que é editável pelo usuário. Os dados são armazenados dentro do arquivo ODF em linhas e colunas. É um formato baseado em XML e é um dos vários subtipos da família Open Document Formats (ODF). O formato é especificado como parte das especificações ODF 1.2 publicadas e mantidas pelo OASIS. Vários aplicativos no Windows, bem como em outros sistemas operacionais, podem abrir arquivos ODS para edição e manipulação, incluindo Microsoft Excel, NeoOffice e LibreOffice. Os arquivos ODS também podem ser convertidos em outros formatos de planilha, como XLS, XLSX e outros por diferentes aplicativos.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de desbloqueio suportados" subTitle="Usando C#, pode-se remover facilmente a proteção / desbloqueio de diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="Arquivo OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}