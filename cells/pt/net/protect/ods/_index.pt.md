---
title:  Proteja e bloqueie o documento ODS via .NET
weight: 5580
description: Código-fonte C# para bloquear o arquivo ODS usando senha no .NET Framework, .NET Core, Mono ou plataformas Xamarin.
keywords: [C# Aspose.Cells., c# Lock ODS files., c# How to Protect and lock ODS document., c# Protect ODS files., Encrypt ODS Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Criptografar arquivos ODS por meio de C#" h2="Planilhas Excel protegidas por senha, incluindo formato ODS usando a Biblioteca .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como proteger o arquivo ODS usando C#" %}}

 Para proteger o arquivo ODS, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Proteja ODS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Você precisa
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 referenciado em seu projeto para executar o fluxo de trabalho a seguir.

{{% /blocks/products/pf/agp/text %}}

1.  Instancie a classe Workbook com caminho para o arquivo ODS
1.  Obtenha o padrão ou qualquer planilha para adicionar proteção
1.  Proteger planilha com método Worksheet.Protect
1.  Proteger a pasta de trabalho com o método Workbook.Protect
1.  Salvar resultado no formato ODS

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

// load the ODS Excel file 
var book = new Aspose.Cells.Workbook("unlocked.ods");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.ods");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para proteger ODS" sectionDescription=" Confira nossas demonstrações ao vivo para[criptografar arquivos ODS](https://products.aspose.app/cells/protect/ods) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer upload do arquivo ODS e clicar no botão \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo ODS resultante no link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Arquivos com extensão ODS representam o formato de documento de planilha OpenDocument que pode ser editado pelo usuário. Os dados são armazenados dentro do arquivo ODF em linhas e colunas. É um formato baseado em XML e é um dos vários subtipos da família Open Document Formats (ODF). O formato é especificado como parte das especificações ODF 1.2 publicadas e mantidas pelo OASIS. Vários aplicativos no Windows, bem como em outros sistemas operacionais, podem abrir arquivos ODS para edição e manipulação, incluindo Microsoft Excel, NeoOffice e LibreOffice. Os arquivos ODS também podem ser convertidos em outros formatos de planilha, como XLS, XLSX e outros por diferentes aplicativos.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de proteção suportados" subTitle="Usando C#, é possível proteger facilmente outros formatos, inclusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Arquivo binário da pasta de trabalho do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
