---
title: Konwertuj TSV na GIF przez Java 
weight: 1600
url: /pl/java/conversion/tsv-to-gif/ 
description: Przykładowy kod konwersji Java dla formatu TSV do pliku GIF. Programiści mogą użyć tego przykładowego kodu, aby wyeksportować arkusze kalkulacyjne Excel i OpenOffice do formatu GIF w dowolnej aplikacji internetowej lub desktopowej Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj TSV na GIF przez Java" h2="Konwersja TSV do GIF Java w celu konwersji jednej lub wielu stron do formatu GIF przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować TSV na GIF za pomocą Java" %}}

 Aby wyrenderować TSV do GIF, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować TSV na GIF za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik TSV na GIF w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik TSV z wystąpieniem Workbook1. Wybierz domyślny lub dowolny arkusz z kolekcji1. Utwórz i ustaw obiekt ImageOrPrintOptions1. Utwórz SheetRender z obiektami Worksheet i ImageOrPrintOptions1. Wywołaj metodę SheetRender.toImage, aby zapisać wynik w formacie GIF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu źródłowego konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV do GIF Java Kod źródłowy konwersji" offSpacer="" %}}

```cs
// załaduj plik TSV do renderowania
Workbook workbook = new Workbook("sourceFile.tsv");
// uzyskać dostęp do domyślnego arkusza roboczego z kolekcji
Worksheet worksheet = workbook.getWorksheets().get(0);
// zdefiniuj parametry dla obrazu wynikowego
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// przekonwertuj arkusz roboczy na obraz w formacie GIF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Prezentacje na żywo z konwersją TSV do GIF" sectionDescription="[Konwertuj TSV na GIF](https://products.aspose.app/cells/conversion/tsv-to-gif) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik TSV, zostanie on natychmiast przekonwertowany do formatu GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteka manipulacji arkuszem kalkulacyjnym" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

Format pliku wartości rozdzielanych tabulatorami (TSV) reprezentuje dane oddzielone tabulatorami w formacie zwykłego tekstu. Format pliku, podobny do CSV, służy do organizowania danych w sposób ustrukturyzowany w celu importowania i eksportowania między różnymi aplikacjami. Format jest używany głównie do importu/eksportu i wymiany danych w aplikacjach arkuszy kalkulacyjnych i bazach danych. Każdy rekord w pliku TSV jest zawarty w pojedynczym wierszu pliku tekstowego, w którym każda wartość pola jest oddzielona znakiem tabulacji. Typ mediów dla formatu pliku TSV to tekst/wartości rozdzielane tabulatorami.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

GIF lub Graphical Interchange Format to rodzaj wysoce skompresowanego obrazu. Będący własnością Unisys plik GIF wykorzystuje algorytm kompresji LZW, który nie pogarsza jakości obrazu. Dla każdego obrazu GIF zazwyczaj dopuszcza do 8 bitów na piksel i do 256 kolorów na całym obrazie. W przeciwieństwie do obrazu JPEG, który może wyświetlać do 16 milionów kolorów i dość mocno dotyka granic ludzkiego oka. Kiedy pojawił się internet, GIF-y pozostały najlepszym wyborem, ponieważ wymagały niskiej przepustowości i były kompatybilne z grafiką, która pochłania jednolite obszary koloru. Animowany GIF łączy wiele obrazów lub klatek w jeden plik i wyświetla je w sekwencji, aby wygenerować animowany klip lub krótki film. Ograniczenia kolorów wynoszą do 256 dla każdej klatki i prawdopodobnie będą najmniej odpowiednie do reprodukcji innych obrazów i fotografii z gradientem kolorów.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować TSV na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-bmp/" name="TSV DO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-csv/" name="TSV DO CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-dif/" name="TSV DO DIF" description="Format wymiany danych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-emf/" name="TSV DO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-html/" name="TSV DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-jpeg/" name="TSV DO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-mhtml/" name="TSV DO MHTML" description="Format archiwum stron internetowych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-ods/" name="TSV DO ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-pdf/" name="TSV DO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-png/" name="TSV DO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-svg/" name="TSV DO SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-tiff/" name="TSV DO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-txt/" name="TSV DO TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlm/" name="TSV DO XLM" description="Plik makr Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xls/" name="TSV DO XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsb/" name="TSV DO XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsx/" name="TSV DO XLSX" description="Plik OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlt/" name="TSV DO XLT" description="Szablon Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltm/" name="TSV DO XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltx/" name="TSV DO XLTX" description="Szablon Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xps/" name="TSV DO XPS" description="Specyfikacje papieru XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-json/" name="TSV DO JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}