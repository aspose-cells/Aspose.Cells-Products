---
title: Konwertuj MHTML na SVG za pomocą Java 
weight: 8850
url: /pl/java/conversion/mhtml-to-svg/ 
description: Przykładowy kod konwersji Java dla formatu MHTML do pliku SVG. Programiści mogą użyć tego przykładowego kodu, aby wyeksportować arkusze kalkulacyjne Excel i OpenOffice do formatu SVG w dowolnej aplikacji internetowej lub desktopowej Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj MHTML na SVG za pomocą Java" h2="Konwersja MHTML do SVG Java w celu konwersji jednej lub wielu stron do formatu SVG przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować MHTML na SVG przy użyciu Java" %}}

 Aby wyrenderować MHTML do SVG, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować MHTML na SVG za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik MHTML na SVG w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik MHTML z instancją Workbook1. Wybierz domyślny lub dowolny arkusz z kolekcji1. Utwórz i ustaw obiekt ImageOrPrintOptions1. Utwórz SheetRender z obiektami Worksheet i ImageOrPrintOptions1. Wywołaj metodę SheetRender.toImage, aby zapisać wynik w formacie SVG
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu źródłowego konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="MHTML do SVG Java Kod źródłowy konwersji" offSpacer="" %}}

```cs
// załaduj plik MHTML do renderowania
Workbook workbook = new Workbook("sourceFile.mhtml");
// uzyskać dostęp do domyślnego arkusza roboczego z kolekcji
Worksheet worksheet = workbook.getWorksheets().get(0);
// zdefiniuj parametry dla obrazu wynikowego
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.SVG);
// przekonwertuj arkusz roboczy na obraz w formacie SVG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.svg");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Prezentacje na żywo konwersji MHTML do SVG" sectionDescription="[Konwertuj MHTML na SVG](https://products.aspose.app/cells/conversion/mhtml-to-svg) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik MHTML, zostanie on natychmiast przekonwertowany do formatu SVG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteka manipulacji arkuszem kalkulacyjnym" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Pliki z rozszerzeniem MHTML reprezentują format archiwum stron internetowych, który może być tworzony przez wiele różnych aplikacji. Format ten jest znany jako format archiwum, ponieważ zapisuje internetowy kod HTML i powiązane zasoby w jednym pliku. Zasoby te obejmują wszystko, co jest powiązane ze stroną internetową, takie jak obrazy, aplety, animacje, pliki audio i tak dalej. Pliki MHTML można otwierać w różnych aplikacjach, takich jak Internet Explorer i Microsoft Word. Microsoft Windows używa formatu pliku MHTML do rejestrowania scenariuszy problemów zaobserwowanych podczas korzystania z dowolnej aplikacji w systemie Windows, która powoduje problemy. Format pliku MHTML koduje zawartość strony podobną do specyfikacji zdefiniowanych w message/rfc822, czyli specyfikacjach związanych ze zwykłym tekstem wiadomości e-mail. Rzeczywiste specyfikacje formatu są zgodne z RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

Pliki SVG to skalowalne pliki grafiki wektorowej, które wykorzystują format tekstowy oparty na XML do opisywania wyglądu obrazu. Słowo Skalowalny odnosi się do faktu, że SVG można skalować do różnych rozmiarów bez utraty jakości. Opis tekstowy takich plików czyni je niezależnymi od rozdzielczości. Jest to jeden z najczęściej używanych formatów do budowy stron internetowych i grafiki drukowanej w celu uzyskania skalowalności. Format ten może być jednak używany tylko do grafiki dwuwymiarowej. Pliki SVG można przeglądać/otwierać w prawie wszystkich nowoczesnych przeglądarkach, w tym Chrome, Internet Explorer, Firefox i Safari.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować MHTML na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-bmp/" name="MHTML DO BMP" description="Bitmapa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-csv/" name="MHTML DO CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-dif/" name="MHTML DO RÓŻNICY" description="Format wymiany danych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-emf/" name="MHTML DO EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-gif/" name="MHTML DO GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-html/" name="MHTML DO HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-jpeg/" name="MHTML DO JPEG" description="Obraz JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-ods/" name="MHTML DO SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-pdf/" name="MHTML DO PDF" description="format dokumentu przenośnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-png/" name="MHTML DO PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tiff/" name="MHTML DO TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tsv/" name="MHTML DO TSV" description="Wartości rozdzielane tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-txt/" name="MHTML DO TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlm/" name="MHTML DO XLM" description="Plik makr Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xls/" name="MHTML DO XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsb/" name="MHTML DO XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsx/" name="MHTML DO XLSX" description="Plik OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlt/" name="MHTML DO XLT" description="Szablon Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltm/" name="MHTML DO XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltx/" name="MHTML DO XLTX" description="Szablon Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xps/" name="MHTML DO XPS" description="Specyfikacje papieru XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-json/" name="MHTML DO JSON" description="Notacja obiektu JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}