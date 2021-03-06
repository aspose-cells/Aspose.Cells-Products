---
title: Visualize Formatos de Arquivo XLT via .NET 
weight: 3610
url: /pt/net/viewer/xlt/ 
description: C# código-fonte para carregar, renderizar e exibir documentos XLT em plataformas .NET Framework, .NET Core, Mono ou Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Visualizador de Arquivos XLT for .NET" h2="Visualize planilhas do Excel e do OpenOffice, como XLT, sem precisar do Microsoft Excel ou do Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como visualizar o arquivo XLT usando C#" %}}

 Para visualizar o arquivo XLT, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API que é uma plataforma rica em recursos, poderosa e fácil de usar API para C# para ser usada com qualquer Visualizador. Aberto
 [NuGetName](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure
 **Aspose.Cells** 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do console do gerenciador de pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para visualizar XLT via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells facilita para os desenvolvedores a visualização do arquivo XLT com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar o arquivo XLT em uma instância do Workbook1. Crie uma instância de HtmlSaveOptions e defina a propriedade ExportHeadings como true1. Salve o arquivo XLT no formato HTML usando o método Workbook.Save1. Carregar HTML resultante no navegador padrão com Process.Start
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Mono ou Xamarin- Ambiente de desenvolvimento como o Microsoft Visual Studio- Aspose.Cells for .NET referenciado em seu projeto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código de exemplo para visualizar o arquivo XLT" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// carregue o arquivo XLT em uma instância do Workbook
var book = new Aspose.Cells.Workbook("template.xlt");
// crie uma instância de HtmlSaveOptions e defina a propriedade ExportHeadings como true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// salve o arquivo XLT no formato HTML
book.Save(output, options);
// carregar HTML resultante no navegador padrão
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para visualizar XLT" sectionDescription="Confira nossas demonstrações ao vivo para [Ver XLT](https://products.aspose.app/cells/viewer/xlt) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer o upload do arquivo XLT e clicar no botão \"Visualizar\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo XLT do link, se necessário" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Arquivos com extensão .XLT são arquivos de modelo criados com o Microsoft Excel, que é um aplicativo de planilha que vem como parte do pacote Microsoft Office. O Microsoft Office 97-2003 suportava a criação de novos arquivos XLT, bem como a abertura deles. A versão mais recente do Excel ainda é capaz de abrir esses arquivos de modelo de formato antigo. Esse arquivo de modelo é usado para criar rapidamente novos arquivos do Excel com dados e configurações padrão, como formatação de página, tamanho da fonte, margens, gráficos, etc., que podem ser salvos como novos arquivos .XLS.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de visualizador compatíveis" subTitle="Usando C#, também é possível visualizar muitos outros formatos de arquivo, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="Arquivo OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Modelo habilitado para macro do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Modelo Excel do Office OpenXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}