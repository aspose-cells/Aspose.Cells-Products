---
title: Vytvořit soubory TSV prostřednictvím Python 
url: /cs/python-java/create-tsv/ 
description: Python Ukázkový kód pro generování dokumentů TSV. Tento kód použijte k vytváření souborů TSV v aplikaci Python.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vytvořit dokumenty TSV prostřednictvím Python" h2="Nativní a vysoce výkonné vytváření TSV (hodnoty oddělené tabulátory) programově pomocí rozhraní API Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Dynamické generování souboru TSV v rámci běžící aplikace je snadné. Abychom mohli vytvářet dokumenty TSV od nuly bez potřeby MS Office, použijeme
 [Aspose.Cells za Python](https://pypi.org/project/aspose-cells) 
 API, která nabízí různé funkce pro vytváření, manipulaci a konverzi tabulek pomocí platformy Python. Vývojáři mohou snadno vylepšit kód pro zápis dat, generování tabulek nebo grafů a také vytváření tabulek v tabulkách.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit TSV prostřednictvím Python" %}}

{{% blocks/products/pf/agp/text %}}

 Pro vývojáře je snadné vytvářet, načítat, upravovat a konvertovat TSV (hodnoty oddělené tabulátory) v rámci různých aplikací pro vytváření sestav pro zpracování dat v několika řádcích kódu.

{{% /blocks/products/pf/agp/text %}}

1. Importujte buňky asposecell do souboru kódu.1. Vytvořte instanci třídy Sešit.1. Otevřete první list sešitu.1. Získejte požadovanou buňku (buňky) listu a zadejte hodnotu do buněk.1. Pomocí metody Uložit uložte sešit jako soubor TSV.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells pro Python prostřednictvím Java je nezávislý na platformě API a lze jej použít na jakékoli platformě (Windows, Linux a MacOS), pouze se ujistěte, že systém má Java 1.8 nebo vyšší, [Python](https://www.python.org/downloads/) 3.5 nebo vyšší. 

{{% /blocks/products/pf/agp/text %}}

- Nainstalujte Java a přidejte jej do proměnné prostředí PATH, například: <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- Nainstalujte Aspose.Cells pro Python prostřednictvím Java od <a href="https://pypi.org/project/aspose-cells/">pypi</a>, použijte příkaz jako: <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Následující zdrojový kód ukazuje, jak vytvořit soubor TSV pomocí Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Vytvořit objekt sešitu.
workbook = Workbook(FileFormatType.TSV)

// Otevřete první list sešitu.
worksheet = workbook.getWorksheets().get(0)

// Získejte požadovanou buňku (buňky) listu a zadejte hodnotu do buněk.
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Uložte sešit jako soubor TSV.
workbook.save("output.tsv")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna programování tabulkových procesorů Excel schopná vytvářet aplikace pro různé platformy se schopností generovat, upravovat, konvertovat, vykreslovat a tisknout soubory TSV. Python API nejen převádí mezi tabulkovými formáty, ale umí také vykreslovat soubory Excel jako obrázky, PDF, HTML, ODS a další, takže je perfektní volbou pro výměnu dokumentů ve standardních průmyslových formátech.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Formát souboru Hodnoty oddělené tabulátory (TSV) představuje data oddělená tabulátory ve formátu prostého textu. Formát souboru, podobný CSV, se používá pro uspořádání dat strukturovaným způsobem za účelem importu a exportu mezi různými aplikacemi. Formát se primárně používá pro import/export a výměnu dat v tabulkových aplikacích a databázích. Každý záznam v souboru TSV je obsažen na jednom řádku textového souboru, kde je každá hodnota pole oddělena znakem tabulátoru. Typ média pro formát souboru TSV je text/hodnoty oddělené tabulátory.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované generování tabulek" subTitle="Můžete také vytvořit další formáty aplikace Microsoft Excel, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Tabulka Microsoft Excel (starší)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="Otevřete sešit XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Binární sešit Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="Tabulka s podporou maker" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Šablona Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Excel šablona" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Šablona s podporou maker aplikace Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="hodnoty oddělené čárkami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="TSV" description="Hodnoty oddělené tabulátorem" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ODS" description="Tabulka OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
