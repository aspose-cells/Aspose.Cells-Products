---
title: Desbloqueie o documento ODS via C++ 
weight: 1190
url: /pt/cpp/unlock/ods/ 
description: C++ código de exemplo para desbloquear arquivo ODS protegido por senha em C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloqueie arquivos ODS via C++" h2="Remova a proteção de planilhas do Excel, incluindo arquivo ODS, usando a Biblioteca C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como remover a proteção do arquivo ODS usando C++" %}}

 Para desbloquear o arquivo ODS, usaremos
 [Aspose.Cells para C++](https://products.aspose.com/cells/cpp) 
 API que é uma plataforma de proteção de documentos API rica em recursos, poderosa e fácil de usar para C++. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGetName](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure
 **Aspose.Cells.Cpp** 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Desbloqueie ODS via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Você precisa
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 referenciado em seu projeto para executar o fluxo de trabalho a seguir.

{{% /blocks/products/pf/agp/text %}}

1. Carregue o arquivo bloqueado ODS usando CreateIWorkbook.1. Chame a função Unprotect() para desbloquear.1. Defina a senha como NULL usando SetPassword.1. Salve o arquivo ODS em um local especificado.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells para C++ é compatível com todas as principais plataformas e sistemas operacionais. Verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="" %}}

```cs

// Caminho do diretório de origem.
StringPtr srcDir = new String("SourceDirectory\\");

// Caminho do diretório de saída.
StringPtr outDir = new String("OutputDirectory\\");

// Carregar arquivo ODS
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sampleExcelFileProtected.ods")));

// Desproteger pasta de trabalho
workbook->Unprotect(new String("12345"));

// Definir senha como nula
workbook->GetISettings()->SetPassword(NULL);

// Salve o arquivo ODS
workbook->Save(outDir->StringAppend(new String("sampleExcelFileUnprotected_out.ods")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells para C++ API" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de desbloqueio suportados" subTitle="Usando C++, pode-se remover facilmente a proteção / desbloqueio de diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="Arquivo OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}