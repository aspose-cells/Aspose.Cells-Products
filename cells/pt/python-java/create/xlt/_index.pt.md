---
title: Crie arquivos MS Excel XLT por meio de Python 
url: /pt/python-java/create-xlt/ 
description: Python Código de amostra para gerar documentos XLT. Use este código para criar arquivos MS Excel XLT no aplicativo Python.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crie documentos XLT por meio de Python" h2="Criação de planilhas MS Excel XLT nativa e de alto desempenho programaticamente usando Python APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Gerar o arquivo XLT do MS Excel dinamicamente no aplicativo em execução é fácil. Para criar documentos XLT do zero sem exigir o MS Office, usaremos
 [Aspose.Cells para Python](https://pypi.org/project/aspose-cells) 
 API que oferece diferentes recursos para criação, manipulação e conversão de planilhas usando a plataforma Python. Os desenvolvedores podem aprimorar facilmente o código para escrever dados, gerar tabelas ou gráficos, bem como criar tabelas em planilhas.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar XLT via Python" %}}

{{% blocks/products/pf/agp/text %}}

 É fácil para os desenvolvedores criar, carregar, modificar e converter planilhas do MS Excel XLT dentro da execução de diferentes aplicativos de relatórios para processamento de dados em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Importe asposecells em seu arquivo de código.1. Crie a instância da classe Workbook.1. Acesse a primeira planilha da pasta de trabalho.1. Obtenha a(s) célula(s) desejada(s) da planilha e insira o valor na(s) célula(s).1. Use o método Save para salvar a pasta de trabalho como arquivo XLT.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells para Python via Java é independente de plataforma API e pode ser usado em qualquer plataforma (Windows, Linux e MacOS), apenas certifique-se de que o sistema tenha Java 1.8 ou superior, [Python](https://www.python.org/downloads/) 3,5 ou superior. 

{{% /blocks/products/pf/agp/text %}}

- Instale Java e adicione-o à variável de ambiente PATH, por exemplo: <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- Instale Aspose.Cells para Python via Java de <a href="https://pypi.org/project/aspose-cells/">pypi</a>, use o comando como: <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="O código-fonte a seguir mostra como criar um arquivo XLT do MS Excel usando Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Criar objeto Pasta de trabalho.
workbook = Workbook(FileFormatType.XLT)

// Acesse a primeira planilha da pasta de trabalho.
worksheet = workbook.getWorksheets().get(0)

// Obtenha a(s) célula(s) desejada(s) da planilha e insira o valor na(s) célula(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Salve a pasta de trabalho como arquivo XLT.
workbook.save("output.xlt")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Uma biblioteca de programação de planilhas do Excel capaz de criar aplicativos multiplataforma com a capacidade de gerar, modificar, converter, renderizar e imprimir arquivos MS Excel XLT. Python API não apenas converte entre formatos de planilha, mas também pode renderizar arquivos Excel como imagens, PDF, HTML, ODS e muito mais, tornando-o a escolha perfeita para trocar documentos em formatos padrão do setor.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Arquivos com extensão .xlt são arquivos de modelo criados com o Microsoft Excel, que é um aplicativo de planilha que vem como parte do pacote Microsoft Office. O Microsoft Office 97-2003 suportava a criação de novos arquivos XLT, bem como a abertura deles. A versão mais recente do Excel ainda é capaz de abrir esses arquivos de modelo de formato antigo. Esse arquivo de modelo é usado para criar rapidamente novos arquivos do Excel com dados e configurações padrão, como formatação de página, tamanho da fonte, margens, gráficos, etc., que podem ser salvos como novos arquivos .xls.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras Gerações de Planilhas Suportadas" subTitle="Você também pode criar outros formatos do Microsoft Excel, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Planilha do Microsoft Excel (Legado)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="Abra a pasta de trabalho XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Pasta de trabalho binária do Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="Planilha habilitada para macro" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Modelo Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Modelo Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Modelo habilitado para macro do Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="Valores Separados Por Virgula" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="TSV" description="Valores Separados por Tabulação" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ODS" description="Planilha OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
