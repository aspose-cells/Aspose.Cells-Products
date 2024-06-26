---
title: Vytvořit MHT – Vytvořte soubor MHT v Python
description:  Aspose Excel. Python Excel. Python Vytvořte soubor MHT rychle a snadno pomocí Aspose.Cells. Vygenerujte soubor MHT pomocí knihovny Excel Python. Vytvořte MHT v knihovně Excel Python. Python MHT Creater.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create MHT file., Generate MHT file in Python Excel Library., Create MHT file using Python Excel Library., Write data to MHT file via Python Excel Library., Create a MHT file in Python Excel Library., Python Generate a MHT file., Python MHT Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vytvořte soubor MHT v knihovně Excel Python" h2="Vysokorychlostní Python Excel knihovna pro vytváření MHT souboru. Toto je profesionální softwarové řešení pro import a export XLSX, PDF a mnoha dalších formátů pomocí Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Vytvořte soubor MHT pomocí knihovny Excel Python" %}}

 Jak vytvořit soubor MHT? S knihovnou Excel Aspose.Cells for Python via Java můžete snadno vytvořit soubor MHT programově pomocí několika řádků kódu.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)je schopen vytvářet multiplatformní aplikace se schopností generovat, upravovat, konvertovat, vykreslovat a tisknout všechny soubory aplikace Excel. Python Excel API nejen převádí mezi tabulkovými formáty, ale umí také vykreslovat soubory Excel jako obrázky, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT a další, takže je perfektní volbou pro výměnu dokumentů ve standardních průmyslových formátech.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Jak vytvořit MHT v knihovně Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

 Pro vývojáře je snadné vytvářet, načítat, upravovat a převádět soubory MHT v rámci různých aplikací pro vytváření sestav pro zpracování dat v několika řádcích kódu.

{{% /blocks/products/pf/agp/text %}}

1.  Importujte buňky asposecell do souboru kódu.
1.  Vytvořte instanci třídy Sešit.
1.  Otevřete první list sešitu.
1. Získejte požadovanou buňku (buňky) listu a zadejte hodnotu do buněk.
1. Pomocí metody Uložit uložte sešit jako soubor MHT.

{{% blocks/products/pf/agp/code-block title="Ukázkový kód ukazuje, jak vytvořit soubor MHT v knihovně Excel Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.MHT)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as MHT file.
workbook.save("output.mht")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Knihovna Excel pro vytvoření souboru MHT" %}}

{{% blocks/products/pf/agp/text %}}

Existují tři možnosti instalace „Aspose.Cells for Python via Java“ do vašeho systému. Vyberte si prosím ten, který odpovídá vašim potřebám, a postupujte podle pokynů krok za krokem:

{{% /blocks/products/pf/agp/text %}}

1.  Nainstalujte Aspose.Cells for Python via Java na Windows. Viz.[Dokumentace](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Nainstalujte Aspose.Cells for Python via Java v Linuxu. Vidět[Dokumentace](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  Nainstalujte Aspose.Cells for Python via Java v macOS. Vidět[Dokumentace](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java je nezávislý na platformě API a lze jej použít na jakékoli platformě (Windows, Linux a MacOS), jen se ujistěte, že systém má Java 1.8 nebo vyšší,[Python](https://www.python.org/downloads/) 3.5 nebo vyšší.

{{% /blocks/products/pf/agp/text %}}

-  Nainstalujte Java a přidejte jej do proměnné prostředí PATH, například:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Instalovat Aspose.Cells for Python via Java z<a href="https://pypi.org/project/aspose-cells/">pypi</a> , použijte příkaz jako:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHT" readMoreLink="https://docs.fileformat.com/web/mht/" >}}Soubor s příponou .mht je formát archivačního souboru s povoleným MIME, který obsahuje různé typy dat do jednoho souboru. Může ukládat data jako text, obrázky, styly stránek ve formě souborů CSS, JavaScript a další zdroje jako vložené prostředky. Soubory MHT, které mají typ MIME message/rfc822, zapouzdřují veškerý obsah souboru HTML jako jeden archivní soubor pro uložení při archivaci na úložných zařízeních. Softwarové aplikace, jako je Microsoft Word, vám umožní převést vaše dokumenty WORD na MHT exportem jako soubor MHT. Soubory MHT lze otevřít pomocí oblíbených prohlížečů, jako je Microsoft Internet Explore a Google Chrome.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované generování tabulek" subTitle="Můžete také vytvořit další Microsoft formáty Excelu, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Excelová tabulka (starší)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="Otevřete sešit XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Binární sešit Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="Tabulka s podporou maker" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Šablona Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Excel šablona" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Šablona s podporou maker aplikace Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="hodnoty oddělené čárkami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="Hodnoty oddělené záložkou" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="Tabulka OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="Přenosný formát dokumentu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
