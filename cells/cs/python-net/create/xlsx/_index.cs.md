---
title: Vytvořit XLSX - Vytvořit soubor XLSX v Python
description: Aspose Excel. Python Excel. Python Vytvořte XLSX Soubor rychle a snadno pomocí Aspose.Cells. Vygenerujte soubor XLSX pomocí knihovny Excel Python. Vytvořte XLSX v knihovně Excel Python. Python XLSX Tvůrce.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create XLSX file., Generate XLSX file in Python Excel Library., Create XLSX file using Python Excel Library., Write data to XLSX file via Python Excel Library., Create a XLSX file in Python Excel Library., Python Generate a XLSX file., Python XLSX Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vytvořte soubor XLSX v knihovně Excel Python" h2="Vysokorychlostní knihovna Python Excel pro vytváření souboru XLSX. Použijte naši konverzi Excel API k vývoji softwaru na vysoké úrovni, nezávislého na platformě v Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-net/" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Vytvořte soubor XLSX pomocí knihovny Excel Python" %}}

Jak vytvořit soubor XLSX? S Aspose.Cells for Python prostřednictvím knihovny Excel NET můžete snadno vytvořit soubor XLSX programově pomocí několika řádků kódu.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells-python/)je schopen vytvářet multiplatformní aplikace se schopností generovat, upravovat, konvertovat, vykreslovat a tisknout všechny soubory aplikace Excel. Python Excel API nejen převádí mezi tabulkovými formáty, ale umí také vykreslovat soubory Excel jako obrázky, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT a další, takže je perfektní volbou pro výměnu dokumentů ve standardních průmyslových formátech.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Jak vytvořit XLSX v knihovně Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

 Pro vývojáře je snadné vytvářet, načítat, upravovat a převádět soubory XLSX v rámci různých aplikací pro vytváření sestav pro zpracování dat v několika řádcích kódu.

{{% /blocks/products/pf/agp/text %}}

1.  Vytvořte instanci třídy Sešit.
1.  Otevřete první list sešitu.
1. Získejte požadovanou buňku (buňky) listu a zadejte hodnotu do buněk.
1.  Pomocí metody Uložit uložte sešit jako soubor XLSX.

{{% blocks/products/pf/agp/code-block title="Ukázkový kód ukazuje, jak vytvořit soubor XLSX v knihovně Excel Python." offSpacer="" %}}

```cs

from aspose import pycore
from aspose.cells import Workbook, SaveFormat, FileFormatType

# Create Workbook object.
workbook = Workbook()

# Access the first worksheet of the workbook.
worksheet = workbook.worksheets[0]

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.cells.get("A1").put_value("ColumnA")
worksheet.cells.get("B1").put_value("ColumnB")
worksheet.cells.get("A2").put_value("ValueA")
worksheet.cells.get("B2").put_value("ValueB")

# Save the workbook as XLSX file.
workbook.save("output.xlsx")

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Knihovna Excel k vytvoření souboru XLSX" %}}

Naše balíčky Python hostujeme v úložištích PyPi.

{{% blocks/products/pf/agp/text %}}
 Nainstalujte Aspose.Cells for Python z<a href="https://pypi.org/project/aspose-cells-python/">pypi</a> , použijte příkaz jako:<code>$ pip install aspose-cells-python</code>.
{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/text %}}
 A můžete také sledovat[pokyny krok za krokem](https://docs.aspose.com/cells/python-net/getting-started/) jak nainstalovat "Aspose.Cells for Python via .NET" do vašeho vývojářského prostředí.
{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python je nezávislý na platformě API a lze jej použít na jakékoli platformě (Windows, Linux), jen se ujistěte, že systém má[Python](https://www.python.org/downloads/) 3.7 nebo vyšší.
 
{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}XLSX je dobře známý formát pro dokumenty Excel Microsoft, který byl představen společností Microsoft vydáním Microsoft Office 2007. Na základě struktury organizované podle konvencí otevřeného balení, jak je uvedeno v části 2 standardu OOXML ECMA-376, je nový formát ECMA-376 zip balíček, který obsahuje řadu souborů XML. Základní strukturu a soubory lze prozkoumat jednoduchým rozbalením souboru .xlsx.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované generování tabulek" subTitle="Můžete také vytvořit další Microsoft formáty Excelu, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xls/" name="XLS" description="Microsoft Excelová tabulka (starší)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsx/" name="XLSX" description="Otevřete sešit XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsb/" name="XLSB" description="Binární sešit Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsm/" name="XLSM" description="Tabulka s podporou maker" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlt/" name="XLT" description="Šablona Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltx/" name="XLTX" description="Excel šablona" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltm/" name="XLTM" description="Šablona s podporou maker aplikace Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/csv/" name="CSV" description="hodnoty oddělené čárkami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/tsv/" name="TSV" description="Hodnoty oddělené záložkou" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/ods/" name="ODS" description="Tabulka OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/pdf/" name="PDF" description="Přenosný formát dokumentu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
