---
title:  Desbloqueie o documento XLSB via C++
weight: 7420
description: C++ código de exemplo para desbloquear o arquivo XLSB protegido por senha no C++ Runtime Environment para Windows 32 bits, Windows 64 bits e Linux 64 bits.
keywords: [C++ Aspose.Cells., C++ unlock XLSB files., C++ how to unlock XLSB document., C++ unprotect XLSB files., remove protection from XLSB files., decrypt XLSB Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Desbloqueie arquivos XLSB por meio de C++" h2="Remova a proteção das planilhas do Excel, incluindo o arquivo XLSB, usando a Biblioteca C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como remover a proteção do arquivo XLSB usando C++" %}}

 Para desbloquear o arquivo XLSB, usaremos
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API, que é uma plataforma de proteção de documentos API for C++ rica em recursos, poderosa e fácil de usar. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure por
 **Aspose.Cells.Cpp** 
 e instale. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Desbloqueie XLSB através de C++" %}}

{{% blocks/products/pf/agp/text %}}

 Você precisa
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 referenciado em seu projeto para executar o fluxo de trabalho a seguir.

{{% /blocks/products/pf/agp/text %}}

1.  Instancie a classe Workbook com caminho para o arquivo XLSB protegido
1.  Obtenha o padrão ou qualquer planilha para remover a proteção
1.  Remova a proteção da planilha com o método Worksheet.Unprotect
1.  Remova a proteção da pasta de trabalho com o método Workbook.Unprotect
1.  Salvar resultado no formato XLSB

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ é compatível com todas as principais plataformas e sistemas operacionais. Certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows 32 bits, Windows 64 bits e Linux 64 bits.
-  Adicione referência à DLL Aspose.Cells for C++ em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// instantiate a Workbook object with protected XLSB file
Workbook workbook(u"protected.xlsb");

// access the default worksheet in the Excel file
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSB format
workbook.Save("unprotected.xlsb", SaveFormat::Auto);

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

        {{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para desbloquear XLSB" sectionDescription=" Confira nossas demonstrações ao vivo para[desbloquear arquivos XLSB](https://products.aspose.app/cells/unlock/xlsb) com os seguintes benefícios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever ou compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta fazer upload do arquivo XLSB e clicar no botão \"Desbloquear\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Baixe o arquivo XLSB resultante no link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
O formato de arquivo XLSB especifica o formato de arquivo binário do Excel, que é uma coleção de registros e estruturas que especificam o conteúdo da pasta de trabalho do Excel. O conteúdo pode incluir tabelas de números não estruturadas ou semiestruturadas, texto ou números e texto, fórmulas, conexões de dados externos, gráficos e imagens. Ao contrário de XLSX (que é baseado no formato de arquivo Open XML), XLSB representa um arquivo binário da pasta de trabalho do Excel. Os arquivos XLSB podem ser lidos e gravados mais rapidamente, o que os torna úteis para trabalhar com arquivos grandes. XLSB raramente é usado para armazenar pastas de trabalho, pois XLSX (e anteriormente XLS) são os formatos de arquivo mais comuns selecionados pelo usuário para salvar pastas de trabalho. Ele pode ser aberto pelo Microsoft Office 2007 e superior.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de desbloqueio suportados" subTitle="Usando C++, pode-se facilmente remover a proteção/desbloqueio de diferentes formatos, inclusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="Arquivo de planilha" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="Arquivo Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
