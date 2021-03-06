---
title: Twórz pliki MS Excel XLT za pomocą C# 
url: /pl/net/create-xlt/ 
description: C# Przykładowy kod do generowania dokumentów XLT. Użyj tego kodu do tworzenia plików MS Excel XLT w VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Twórz dokumenty XLT za pomocą C#" h2="Natywne i wysokowydajne tworzenie arkuszy kalkulacyjnych MS Excel XLT programowo przy użyciu interfejsów API .NET po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Dynamiczne generowanie pliku MS Excel XLT w ramach uruchomionej aplikacji jest łatwe. Aby tworzyć dokumenty XLT od podstaw bez konieczności korzystania z pakietu MS Office, użyjemy
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, który oferuje różne funkcje tworzenia, manipulowania i konwersji arkuszy kalkulacyjnych przy użyciu platformy .NET. Deweloperzy mogą z łatwością ulepszać kod do pisania danych, generowania wykresów lub wykresów, a także tworzenia tabel w arkuszach kalkulacyjnych.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak utworzyć XLT za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

 Deweloperzy mogą łatwo tworzyć, ładować, modyfikować i konwertować arkusze kalkulacyjne MS Excel XLT w ramach uruchamiania różnych aplikacji raportowych do przetwarzania danych w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Dołącz przestrzeń nazw do pliku klasy1. Utwórz instancję klasy Workbook.1. Uzyskaj dostęp do pierwszego arkusza roboczego skoroszytu.1. Pobierz żądane komórki arkusza roboczego i wprowadź wartość do komórki (komórek).1. Użyj metody Save, aby zapisać skoroszyt jako plik XLT.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Upewnij się tylko, że system ma Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin Platforms, a także środowisko programistyczne, takie jak Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Zainstaluj z wiersza poleceń jako <code>nuget install Aspose.Cells</code> lub za pośrednictwem konsoli Menedżera pakietów programu Visual Studio z <code>Install-Package Aspose.Cells</code>.- Alternatywnie, pobierz instalator offline MSI lub wszystkie biblioteki DLL w pliku ZIP z <a href="https://downloads.aspose.com/cells/net">pliki do pobrania</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Poniższy kod źródłowy pokazuje, jak utworzyć plik MS Excel XLT przy użyciu C#." offSpacer="" %}}

```cs

// Utwórz instancję klasy Workbook.
Workbook wkb = new Workbook();

// Uzyskaj dostęp do pierwszego arkusza roboczego skoroszytu.
Worksheet sht = wkb.Worksheets[0];

// Pobierz żądane komórki arkusza.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// wprowadź wartość do komórki (komórek).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Zapisz skoroszyt jako plik .xlt.
wkb.Save("created_one.xlt");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Biblioteka programowania arkusza kalkulacyjnego Excel zdolna do tworzenia aplikacji wieloplatformowych z możliwością generowania, modyfikowania, konwertowania, renderowania i drukowania plików MS Excel XLT. .NET Excel API nie tylko konwertuje między formatami arkuszy kalkulacyjnych, ale może również renderować pliki Excela jako obrazy, PDF, HTML, ODS i inne, dzięki czemu jest idealnym wyborem do wymiany dokumentów w formatach standardowych branżowych.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Pliki z rozszerzeniem .xlt to pliki szablonów utworzone za pomocą programu Microsoft Excel, który jest aplikacją do obsługi arkuszy kalkulacyjnych, która jest częścią pakietu Microsoft Office. Microsoft Office 97-2003 obsługiwał tworzenie nowych plików XLT, a także ich otwieranie. Najnowsza wersja programu Excel nadal umożliwia otwieranie plików szablonów w starym formacie. Taki plik szablonu służy do szybkiego tworzenia nowych plików Excela z domyślnymi danymi i ustawieniami, takimi jak formatowanie strony, rozmiar czcionki, marginesy, wykresy itp., które można dalej zapisywać jako nowe pliki .xls.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane generowanie arkuszy kalkulacyjnych" subTitle="Możesz także tworzyć inne formaty Microsoft Excel, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Arkusz kalkulacyjny Microsoft Excel (starsza wersja)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="Otwórz skoroszyt XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Skoroszyt binarny programu Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="Arkusz kalkulacyjny z obsługą makr" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Szablon programu Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Szablon Excela" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Szablon programu Excel z obsługą makr" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="Wartości oddzielone przecinkami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="TSV" description="Wartości rozdzielane tabulatorami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="SZWO" description="Arkusz kalkulacyjny OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
