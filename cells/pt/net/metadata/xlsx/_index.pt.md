---
title: Visualize ou edite metadados de arquivos XLSX via .NET 
weight: 3430
url: /pt/net/metadata/xlsx/ 
description: C# código-fonte para editar ou visualizar metadados de formato XLSX em plataformas .NET Framework, .NET Core, Mono ou Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extraia metadados XLSX por meio de .NET" h2="Crie seus próprios aplicativos .NET para adicionar, editar, remover ou extrair metadados de arquivos XLSX usando APIs do lado do servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como extrair metadados XLSX usando C#" %}}

 Para extrair metadados XLSX, usaremos
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API que é rico em recursos, poderoso e fácil de usar metadados de documento API para a plataforma C#. Aberto
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para extrair metadados de XLSX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Acesse informações úteis armazenadas no arquivo XLSX, incluindo quando o arquivo XLSX foi recebido, processado, marcado com data e hora e assim por diante.

{{% /blocks/products/pf/agp/text %}}

+ Carregar XLSX com uma instância do Workbook
+ Obtenha a coleção BuiltInDocumentProperties do objeto Workbook
+ Iterar sobre a coleção
+ Exibir nome, tipo e valor da propriedade

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Mono ou Xamarin.- Ambiente de desenvolvimento como o Microsoft Visual Studio.- Aspose.Cells for .NET referenciado em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrair metadados de XLSX - C#" offSpacer="" %}}

```cs

// carregue o XLSX com uma instância do Workbook
var book = new Aspose.Cells.Workbook("template.xlsx");
// iterar sobre a coleção BuiltInDocumentProperties
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Algumas propriedades podem armazenar vários valores
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
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

        {{< blocks/products/pf/agp/demobox sectionTitle="Extrair metadados de XLSX via aplicativo online" sectionDescription="Visualize e edite metadados para documentos XLSX usando nosso [Demonstrações ao vivo](https://products.aspose.app/cells/metadata) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta carregar seu arquivo XLSX e editar as propriedades do documento" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtenha instantaneamente o link de download para o arquivo resultante" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX é um formato bem conhecido para documentos do Microsoft Excel que foi introduzido pela Microsoft com o lançamento do Microsoft Office 2007. um pacote zip que contém vários arquivos XML. A estrutura e os arquivos subjacentes podem ser examinados simplesmente descompactando o arquivo .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de metadados suportados" subTitle="Usando C#, também é possível manipular metadados de muitos outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsm/" name="XLSM" description="Arquivo de planilha" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}