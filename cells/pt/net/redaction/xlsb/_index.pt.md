---
title:  Pesquise e substitua texto no documento XLSB via .NET
weight: 3890
description: Código-fonte C# para editar informações confidenciais no arquivo XLSB em .NET Framework, .NET Core, Mono ou plataformas Xamarin.
keywords: [C# Aspose.Cells., c# Search and replace text in XLSB file., c# redact XLSB file., c# edit XLSB file., c# XLSB file redaction., c# Search and replace string in XLSB file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Editar formatos XLSB em C#" h2="Informações de redação confidenciais de documentos XLSB nativos e de alto desempenho usando APIs Aspose.Cells for .NET do lado do servidor, sem o uso de qualquer software como Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como redigir o arquivo XLSB usando C#" %}}

 Para redigir o arquivo XLSB, usaremos[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API, que é um API de manipulação de documentos rico em recursos, poderoso e fácil de usar para a plataforma C#. Abrir[NuGet](https://www.nuget.org/packages/aspose.cells) gerenciador de pacotes, procure por**Aspose.Cells** e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para redigir arquivos XLSB em C#" %}}

{{% blocks/products/pf/agp/text %}}

 Uma pesquisa básica de documentos e substituição de texto em conteúdos, comentários ou metadados por[Aspose.Cells for .NET](https://products.aspose.com/cells/net) APIs podem ser feitas com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+ Carregue o arquivo XLSB.
+ Selecione a planilha.
+ Crie o objeto FindOptions.
Definir opções de pesquisa
+ Percorra cada célula e use o método Find.
+ Salve a pasta de trabalho.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, certifique-se de ter os seguintes pré-requisitos em seu sistema.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com .NET Framework, .NET Core, Mono ou plataformas Xamarin
-  Ambiente de desenvolvimento como Microsoft Visual Studio
-  Adicione referência à DLL Aspose.Cells for .NET em seu projeto - Instale a partir de NuGet usando o botão Download acima

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Editar arquivos XLSB - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.xlsb");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //find only whole word and not part of any word.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.xlsb");

// Find/Replace in whole workbook.

Workbook wb = new Workbook("e:\test2\Input.xlsb");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos Excel Microsoft em diferentes formatos. Além disso, pode ser usado para gráficos abrangentes, relatórios escalonáveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API independente e não requer nenhum software como Microsoft ou OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de redação on-line XLSB" sectionDescription=" Pesquise e substitua texto em conteúdos, comentários ou metadados em documentos XLSB agora mesmo, visitando nosso[Site de demonstrações ao vivo](https://products.aspose.app/cells/redaction). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta enviar seus arquivos XLSB." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ele será redigido instantaneamente." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
 formato de arquivo XLSB especifica o formato de arquivo binário do Excel, que é uma coleção de registros e estruturas que especificam o conteúdo da pasta de trabalho do Excel. O conteúdo pode incluir tabelas de números não estruturadas ou semiestruturadas, texto ou números e texto, fórmulas, conexões de dados externos, gráficos e imagens. Ao contrário de XLSX (que é baseado no formato de arquivo Open XML), XLSB representa um arquivo binário da pasta de trabalho do Excel. Os arquivos XLSB podem ser lidos e gravados com mais rapidez, o que os torna úteis para trabalhar com arquivos grandes. XLSB raramente é usado para armazenar pastas de trabalho, pois XLSX (e anteriormente XLS) são os formatos de arquivo mais comuns selecionados pelo usuário para salvar pastas de trabalho. Ele pode ser aberto pelo Microsoft Office 2007 e superior.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de redação suportados" subTitle="Usando C#, é possível redigir facilmente diferentes formatos, inclusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
