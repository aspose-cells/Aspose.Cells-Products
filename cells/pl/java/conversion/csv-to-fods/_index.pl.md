---
title: Konwertuj CSV na FODS przez Java 
url: /pl/java/conversion/csv-to-fods/ 
description: Przykładowy kod konwersji Java dla formatu CSV do pliku FODS. Programiści mogą użyć tego przykładowego kodu, aby wyeksportować arkusze kalkulacyjne Excel i OpenOffice do FODS w dowolnej aplikacji internetowej lub desktopowej Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj CSV na FODS przez Java" h2="Konwersja CSV do FODS Java w celu konwersji jednej lub wielu stron do FODS przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="FODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować CSV na FODS za pomocą Java" %}}

 Aby wyrenderować CSV do FODS, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować CSV na FODS za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik CSV na FODS w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik CSV z instancją klasy Workbook1. Wywołaj metodę Workbook.save1. Przekaż ścieżkę wyjściową z rozszerzeniem FODS i SaveFormat jako parametrami1. Sprawdź określoną ścieżkę dla wynikowego pliku FODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu źródłowego konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV do FODS Java Kod źródłowy konwersji" offSpacer="" %}}

```cs
// załaduj plik CSV w instancji Workbook
Workbook book = new Workbook("template.csv");
// zapisz CSV jako FODS
book.save("output.fods", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Prezentacje na żywo konwersji CSV do FODS" sectionDescription="[Konwertuj CSV na FODS](https://products.aspose.app/cells/conversion/csv-to-fods) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik CSV, zostanie on natychmiast przekonwertowany na FODS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteka manipulacji arkuszem kalkulacyjnym" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Pliki z rozszerzeniem CSV (wartości oddzielone przecinkami) reprezentują zwykłe pliki tekstowe, które zawierają rekordy danych z wartościami oddzielonymi przecinkami. Każdy wiersz w pliku CSV jest nowym rekordem ze zbioru rekordów zawartych w pliku. Takie pliki są generowane, gdy zamierzone jest przesyłanie danych z jednego systemu pamięci masowej do drugiego. Ponieważ wszystkie aplikacje rozpoznają rekordy oddzielone przecinkami, import takich plików danych do bazy danych odbywa się bardzo wygodnie. Prawie wszystkie aplikacje do obsługi arkuszy kalkulacyjnych, takie jak Microsoft Excel lub OpenOffice Calc, mogą bez większego wysiłku importować CSV. Dane importowane z takich plików są uporządkowane w komórkach arkusza kalkulacyjnego w celu przedstawienia użytkownikowi.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FODS" readMoreLink="https://docs.fileformat.com/spreadsheet/fods/" >}}

Plik z rozszerzeniem .fods jest rodzajem formatu dokumentu OpenDocument Spreadsheet, który przechowuje dane w wierszach i kolumnach. Format jest określony jako część specyfikacji ODF 1.2 opublikowanych i utrzymywanych przez OASIS. Plików FODS nie można otwierać za pomocą programu Excel, innej aplikacji do obsługi arkuszy kalkulacyjnych firmy Microsoft. Pliki FODS można zapisywać jako ODS za pomocą LibreOffice i konwertować na inne formaty, takie jak XLS i XLSX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować CSV na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-bmp/" name="CSV DO BMP" description="Bitmapa" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-dif/" name="CSV DO DIF" description="Format wymiany danych" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-emf/" name="CSV DO EMF" description="Ulepszony format metapliku" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-gif/" name="CSV DO GIF" description="Graficzny format wymiany" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-html/" name="CSV DO HTML" description="hipertekstowy język znaczników" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-jpeg/" name="CSV DO JPEG" description="Obraz JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-mhtml/" name="CSV DO MHTML" description="Format archiwum stron internetowych" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-ods/" name="CSV DO ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-pdf/" name="CSV DO PDF" description="format dokumentu przenośnego" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-png/" name="CSV DO PNG" description="Przenośna Grafika Sieciowa" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-svg/" name="CSV DO SVG" description="Skalowalna Grafika wektorowa" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tiff/" name="CSV DO TIFF" description="Oznaczony format obrazu" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tsv/" name="CSV DO TSV" description="Wartości rozdzielane tabulatorami" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-txt/" name="CSV DO TXT" description="Dokument tekstowy" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlm/" name="CSV DO XLM" description="Plik makr Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xls/" name="CSV DO XLS" description="Format binarny programu Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsb/" name="CSV DO XLSB" description="Binarny plik skoroszytu programu Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsx/" name="CSV DO XLSX" description="Plik OOXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlt/" name="CSV DO XLT" description="Szablon Microsoft Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltm/" name="CSV DO XLTM" description="Szablon programu Excel z obsługą makr" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltx/" name="CSV DO XLTX" description="Szablon Office OpenXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xps/" name="CSV DO XPS" description="Specyfikacje papieru XML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-json/" name="CSV DO JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}