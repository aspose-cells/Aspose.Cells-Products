---
title: Konwertuj XLT na TIFF przez Java 
weight: 1530
url: /pl/java/conversion/xlt-to-tiff/ 
description: Przykładowy kod konwersji Java dla formatu XLT do pliku TIFF. Programiści mogą użyć tego przykładowego kodu, aby wyeksportować arkusze kalkulacyjne Excel i OpenOffice do formatu TIFF w dowolnej aplikacji internetowej lub desktopowej Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj XLT na TIFF przez Java" h2="Konwersja XLT do TIFF Java w celu konwersji jednej lub wielu stron do formatu TIFF przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować XLT na TIFF za pomocą Java" %}}

 Aby wyrenderować XLT do TIFF, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą konwersji API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pom.xml.

{{% blocks/products/pf/agp/code-block title="Magazyn" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować XLT na TIFF za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik XLT na TIFF w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik XLT z instancją Workbook1. Wybierz domyślny lub dowolny arkusz z kolekcji1. Utwórz i ustaw obiekt ImageOrPrintOptions1. Utwórz SheetRender z obiektami Worksheet i ImageOrPrintOptions1. Wywołaj metodę SheetRender.toImage, aby zapisać wynik w formacie TIFF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu źródłowego konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT do TIFF Java Kod źródłowy konwersji" offSpacer="" %}}

```cs
// załaduj plik XLT do renderowania
Workbook workbook = new Workbook("sourceFile.xlt");
// uzyskać dostęp do domyślnego arkusza roboczego z kolekcji
Worksheet worksheet = workbook.getWorksheets().get(0);
// zdefiniuj parametry dla obrazu wynikowego
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.TIFF);
// przekonwertuj arkusz na obraz w formacie TIFF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.tiff");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Konwersja na żywo z XLT do TIFF" sectionDescription="[Konwertuj XLT na TIFF](https://products.aspose.app/cells/conversion/xlt-to-tiff) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik XLT, zostanie on natychmiast przekonwertowany do formatu TIFF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteka manipulacji arkuszem kalkulacyjnym" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

Pliki z rozszerzeniem .XLT to pliki szablonów utworzone za pomocą programu Microsoft Excel, który jest aplikacją arkusza kalkulacyjnego, która jest częścią pakietu Microsoft Office. Microsoft Office 97-2003 obsługiwał tworzenie nowych plików XLT, a także ich otwieranie. Najnowsza wersja programu Excel nadal umożliwia otwieranie plików szablonów w starym formacie. Taki plik szablonu służy do szybkiego tworzenia nowych plików Excela z domyślnymi danymi i ustawieniami, takimi jak formatowanie strony, rozmiar czcionki, marginesy, wykresy itp., które można dalej zapisywać jako nowe pliki .XLS.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}

TIFF lub TIF, Tagged Image File Format, reprezentuje obrazy rastrowe przeznaczone do użytku na różnych urządzeniach zgodnych z tym standardem formatu plików. Jest w stanie opisać dane obrazu dwupoziomowego, w skali szarości, w palecie kolorów i w pełnym kolorze w kilku przestrzeniach kolorów. Obsługuje stratne i bezstratne schematy kompresji, aby wybrać między przestrzenią a czasem dla aplikacji korzystających z formatu. Format jest rozszerzalny i przeszedł kilka zmian, które umożliwiają włączenie nieograniczonej ilości informacji prywatnych lub informacji specjalnego przeznaczenia. Format nie jest zależny od komputera i nie zawiera ograniczeń, takich jak procesor, system operacyjny lub systemy plików.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować XLT na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-bmp/" name="XLT DO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-csv/" name="XLT DO CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-dif/" name="XLT NA RÓŻNICĘ" description="Format wymiany danych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-emf/" name="XLT DO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-gif/" name="XLT DO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-html/" name="XLT DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-jpeg/" name="XLT NA JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-mhtml/" name="XLT DO MHTML" description="Format archiwum stron internetowych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-ods/" name="XLT DO SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-pdf/" name="XLT DO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-png/" name="XLT DO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-svg/" name="XLT DO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-tsv/" name="XLT DO TSV" description="Wartości rozdzielane tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-txt/" name="XLT DO TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlm/" name="XLT DO XLM" description="Plik makr Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xls/" name="XLT DO XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlsb/" name="XLT DO XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlsx/" name="XLT DO XLSX" description="Plik OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xltm/" name="XLT DO XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xltx/" name="XLT NA XLTX" description="Szablon Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xps/" name="XLT DO XPS" description="Specyfikacje papieru XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-json/" name="XLT DO JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}