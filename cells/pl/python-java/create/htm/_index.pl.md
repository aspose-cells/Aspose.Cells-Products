---
title: Utwórz HTM — utwórz plik HTM pod numerem Python
description:  Aspose Excel. Python Excel. Python Szybko i łatwo utwórz plik HTM za pomocą Aspose.Cells. Wygeneruj plik HTM za pomocą biblioteki Excel Python. Utwórz HTM w bibliotece Excel Python. Python Kreator HTM.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create HTM file., Generate HTM file in Python Excel Library., Create HTM file using Python Excel Library., Write data to HTM file via Python Excel Library., Create a HTM file in Python Excel Library., Python Generate a HTM file., Python HTM Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Utwórz plik HTM w bibliotece Excel Python" h2="Szybka biblioteka Excel Python do tworzenia pliku HTM. Jest to profesjonalne oprogramowanie do importowania i eksportowania numerów XLSX, PDF i wielu innych formatów przy użyciu numeru Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Utwórz plik HTM przy użyciu biblioteki programu Excel Python" %}}

 Jak utworzyć plik HTM? Dzięki bibliotece Excel Aspose.Cells for Python via Java możesz łatwo programowo utworzyć plik HTM za pomocą kilku linii kodu.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)potrafi budować aplikacje wieloplatformowe z możliwością generowania, modyfikowania, konwertowania, renderowania i drukowania wszystkich plików Excel. Python Excel API nie tylko konwertuje pomiędzy formatami arkuszy kalkulacyjnych, ale może także renderować pliki Excel jako obrazy, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT i więcej, co czyni go idealnym wyborem do wymiany dokumentów w formatach będących standardami branżowymi.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Jak utworzyć HTM w bibliotece Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

Programiści mogą z łatwością tworzyć, ładować, modyfikować i konwertować pliki HTM w ramach uruchamiania różnych aplikacji raportujących do przetwarzania danych w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1.  Zaimportuj asposecells do pliku kodu.
1.  Utwórz instancję klasy Workbook.
1.  Uzyskaj dostęp do pierwszego arkusza skoroszytu.
1. Pobierz żądane komórki arkusza i wprowadź wartość do komórek.
1.  Użyj metody Zapisz, aby zapisać skoroszyt jako plik HTM.

{{% blocks/products/pf/agp/code-block title="Przykładowy kod pokazuje, jak utworzyć plik HTM w bibliotece Excel Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.HTM)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as HTM file.
workbook.save("output.htm")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Biblioteka programu Excel do tworzenia pliku HTM" %}}

{{% blocks/products/pf/agp/text %}}

Istnieją trzy możliwości zainstalowania w systemie „Aspose.Cells for Python via Java”. Wybierz ten, który odpowiada Twoim potrzebom i postępuj zgodnie z instrukcjami krok po kroku:

{{% /blocks/products/pf/agp/text %}}

1.  Zainstaluj Aspose.Cells for Python via Java w Windows. Zobacz[Dokumentacja](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Zainstaluj Aspose.Cells for Python via Java w systemie Linux. Widzieć[Dokumentacja](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  Zainstaluj Aspose.Cells for Python via Java w systemie macOS. Widzieć[Dokumentacja](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java jest niezależny od platformy API i może być używany na dowolnej platformie (Windows, Linux i MacOS), tylko upewnij się, że system ma Java 1.8 lub nowszy,[Python](https://www.python.org/downloads/) 3,5 lub wyższy.

{{% /blocks/products/pf/agp/text %}}

-  Zainstaluj Java i dodaj go do zmiennej środowiskowej PATH, na przykład:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Zainstaluj Aspose.Cells for Python via Java z<a href="https://pypi.org/project/aspose-cells/">pypi</a> , użyj polecenia jako:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTM" readMoreLink="https://docs.fileformat.com/web/htm/" >}}Pliki z rozszerzeniem .htm reprezentują język Hypertext Markup Language służący do tworzenia stron internetowych do wyświetlania w przeglądarkach internetowych, takich jak Google Chrome, Internet Explorer, Firefox i wiele innych. Definiuje znaczniki do tworzenia statycznych stron, które mają być publikowane w sieci WWW (WWW) w celu umożliwienia dostępu innym osobom. Te znaczniki informują przeglądarki, jak wyświetlić zawartość strony internetowej. Takie strony mogą zawierać zwykły tekst, obrazy, hiperłącza do innych stron, filmy i inne informacje multimedialne. Po opublikowaniu strony internetowej możesz sprawdzić kod znaczników, który się za nią kryje, przeglądając źródło strony. Nowoczesne przeglądarki umożliwiają wgląd w każdą sekcję strony internetowej, w której opracowano każdy podpodział lub element znaczników w źródle HTM.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane generowanie arkuszy kalkulacyjnych" subTitle="Możesz także utworzyć inne formaty Microsoft Excel, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Arkusz kalkulacyjny Excel (starsza wersja)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="Otwórz skoroszyt XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Skoroszyt binarny programu Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="Arkusz kalkulacyjny z obsługą makr" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Szablon Excela 97 – 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Szablon Excela" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Szablon programu Excel z obsługą makr" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="Wartości oddzielone przecinkami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="Zakładka Wartości rozdzielone" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="Arkusz kalkulacyjny OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="format dokumentu przenośnego" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="hipertekstowy język znaczników" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
