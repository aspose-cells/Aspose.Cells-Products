---
title: Pesquisar documento XLSB sem abrir via .NET 
weight: 8880
url: /pt/net/search/xlsb/ 
description: C# código-fonte para pesquisar palavras com padrão no arquivo XLSB nas plataformas .NET Framework, .NET Core, Mono ou Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Pesquisar formatos XLSB em C#" h2="Pesquisa de documentos XLSB nativa e de alto desempenho usando APIs Aspose.Cells for .NET do lado do servidor, sem o uso de qualquer software como Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como pesquisar arquivo XLSB usando C#" %}}

 Para pesquisar o arquivo XLSB, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API que é uma plataforma de pesquisa de documentos API rica em recursos, poderosa e fácil de usar para C#. Aberto
 [NuGetName](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure
 **Aspose.Cells** 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para pesquisar arquivos XLSB em C#" %}}

{{% blocks/products/pf/agp/text %}}

 Uma pesquisa básica de documentos com
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 APIs podem ser feitas com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+ Carregue o arquivo XLSB usando a classe Workbook.
+ Obtenha as células na planilha relevante.
+ Números de pesquisa, data e texto usando o método Find

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, verifique se você possui os seguintes pré-requisitos em seu sistema.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Mono ou Xamarin- Ambiente de desenvolvimento como o Microsoft Visual Studio- Aspose.Cells for .NET DLL referenciada em seu projeto - Instale do NuGet usando o botão Download acima
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Pesquisar arquivos XLSB - C#" offSpacer="" %}}

```cs
// pesquisando células contendo o valor ou número da string especificada
Workbook workbook = new Workbook("book1.xlsb");

// obter coleção de células
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// encontre a célula com o inteiro de entrada ou duplo
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// encontre a célula com a string de entrada
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// encontre a célula contendo com a string de entrada
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells for .NET API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demos on-line de pesquisa XLSB ao vivo" sectionDescription="Pesquise texto, palavras, frases em documentos XLSB agora mesmo, visitando nosso [Site de demonstrações ao vivo](https://products.aspose.app/cells/search). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta carregar seus arquivos XLSB." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" O resultado da pesquisa aparece instantaneamente." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
O formato de arquivo XLSB especifica o formato de arquivo binário do Excel, que é uma coleção de registros e estruturas que especificam o conteúdo da pasta de trabalho do Excel. O conteúdo pode incluir tabelas de números não estruturadas ou semiestruturadas, texto ou ambos, números e texto, fórmulas, conexões de dados externos, gráficos e imagens. Ao contrário do XLSX (que é baseado no formato de arquivo Open XML), o XLSB representa o arquivo binário da pasta de trabalho do Excel. Os arquivos XLSB podem ser lidos e gravados mais rapidamente, o que os torna úteis para trabalhar com arquivos grandes. XLSB raramente é usado para armazenar pastas de trabalho, pois XLSX (e anteriormente XLS) são os formatos de arquivo selecionados pelo usuário mais comuns para salvar pastas de trabalho. Ele pode ser aberto pelo Microsoft Office 2007 e superior. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de pesquisa suportados" subTitle="Usando C#, também é possível pesquisar outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="Valores Separados Por Virgula" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Arquivo de planilha" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}