---
title: Pesquisar documento CSV sem abrir via C++ 
weight: 5540
url: /pt/cpp/search/csv/ 
description: C++ código de exemplo para pesquisar palavras com padrão no arquivo CSV em C++ Runtime Environment para Windows 32 bits, Windows 64 bits e Linux 64 bits.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Pesquisar formatos CSV em C++" h2="Pesquisa de documentos CSV nativa e de alto desempenho usando Aspose.Cells do lado do servidor para C++ APIs, sem o uso de qualquer software como Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como pesquisar arquivo CSV usando C++" %}}

 Para pesquisar o arquivo CSV, usaremos
 [Aspose.Cells para C++](https://products.aspose.com/cells/cpp) 
 API que é uma plataforma de pesquisa de documentos API rica em recursos, poderosa e fácil de usar para C++. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGetName](https://www.nuget.org/packages/aspose.cells) 
 gerenciador de pacotes, procure
 **Aspose.Cells.Cpp** 
 e instalar. Você também pode usar o seguinte comando do Console do Gerenciador de Pacotes.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para pesquisar arquivos CSV em C++" %}}

{{% blocks/products/pf/agp/text %}}

 Uma pesquisa básica de documentos usando APIs Aspose.Cells pode ser feita com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+ Carregar arquivo CSV instanciando uma classe IWorkbook.
Instanciar a classe IReplaceOptions.
+ Defina o padrão necessário como SetCaseSensitive(bool value), SetMatchEntireCellContents(bool value) .
+ Use o método IWorkbook->Replace(..) com opções relevantes.
+ Salve o arquivo CSV usando o método IWorkbook->Save(.).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells para C++ é compatível com todas as principais plataformas e sistemas operacionais. Verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.- Aspose.Cells para C++ DLL referenciada em seu projeto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Pesquisar arquivos CSV - C++" offSpacer="" %}}

```cs

// Caminho do diretório de origem.
StringPtr srcDir = new String("SourcePath\\");

// Caminho do diretório de saída.
StringPtr outDir = new String("OutputPath\\");

// Carregar arquivo CSV
intrusive_ptr<IWorkbook>  wkb = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.csv")));

// Crie uma instância da classe IReplaceOptions
intrusive_ptr<IReplaceOptions> replaceOptions = Factory::CreateIReplaceOptions();

// Definir opção de diferenciação de maiúsculas e minúsculas
replaceOptions->SetCaseSensitive(false);

// Definir opção de correspondência de texto
replaceOptions->SetMatchEntireCellContents(false);

// Substituir texto
wkb->Replace(new String("Text to find"), new String("Text replacement"), replaceOptions);

// Salvar como arquivo CSV
wkb->Save(outDir->StringAppend(new String("outputFile.csv")));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Sobre Aspose.Cells para C++ API" %}}

 Aspose.Cells API pode ser usado para criar, editar, converter e renderizar formatos do Microsoft Excel para diferentes formatos. Além disso, ele pode ser usado para gráficos abrangentes, relatórios escaláveis e cálculos confiáveis em aplicativos de software. Aspose.Cells é um API autônomo e não requer nenhum software como Microsoft ou OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo da pesquisa CSV on-line" sectionDescription="Pesquise textos, palavras e frases em documentos CSV agora mesmo visitando nosso [Site de demonstrações ao vivo](https://products.aspose.app/cells/search). A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta carregar seus arquivos CSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" O resultado da pesquisa aparece instantaneamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
Arquivos com extensão CSV (Comma Separated Values) representam arquivos de texto simples que contêm registros de dados com valores separados por vírgulas. Cada linha em um arquivo CSV é um novo registro do conjunto de registros contido no arquivo. Esses arquivos são gerados quando a transferência de dados é pretendida de um sistema de armazenamento para outro. Como todos os aplicativos podem reconhecer registros separados por vírgula, a importação desses arquivos de dados para o banco de dados é feita de forma muito conveniente. Quase todos os aplicativos de planilhas, como o Microsoft Excel ou o OpenOffice Calc, podem importar CSV sem muito esforço. Os dados importados desses arquivos são organizados em células de uma planilha para representação ao usuário. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros documentos de pesquisa suportados" subTitle="Usando C++, também é possível pesquisar outros arquivos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="Arquivo de planilha OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Valores separados por tabulação" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Documento de texto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Formato binário do Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Arquivo de pasta de trabalho do Excel binário" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Arquivo de planilha" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}