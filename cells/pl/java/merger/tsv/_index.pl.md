---
title: Scal pliki TSV przez Java 
weight: 9260
url: /pl/java/merger/tsv/ 
description: Java przykładowy kod do łączenia dokumentów TSV w Java środowisku wykonawczym dla aplikacji JSP/JSF i aplikacji komputerowych.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Scal formaty TSV w Java" h2="Natywne scalanie dokumentów TSV przy użyciu interfejsów API Java po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak scalić pliki TSV za pomocą Java" %}}

 Aby scalić plik TSV, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą do łączenia API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki scalania plików TSV w Java" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowy dokument łączący i łączący z
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API można wykonać za pomocą kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj pierwszy plik TSV z wystąpieniem klasy Workbook.
+ Załaduj drugi dokument TSV z instancją klasy Workbook.
+ Scal pliki za pomocą metody merge().
+ zapisz scalony plik TSV pod określoną ścieżką

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Scal pliki TSV — Java" offSpacer="" %}}

```cs
// Otwórz pierwszy plik TSV.
Workbook tsvFile1 = new Workbook("chartsFileWithPath.tsv");

// Zdefiniuj drugą książkę źródłową.
// Otwórz drugi plik TSV.
Workbook tsvFile2 = new Workbook("pictureFileWithPath.tsv");

// Łączenie dwóch skoroszytów
tsvFile1.combine(tsvFile2);

// Zapisz docelowy plik księgi.
tsvFile1.save("combinedFileWithPath.tsv");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Internetowe demonstracje połączenia TSV na żywo" sectionDescription="Scal dokumenty TSV już teraz, odwiedzając nasz [Witryna demonstracyjna na żywo](https://products.aspose.app/cells/merger). Demo na żywo ma następujące zalety" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Po prostu prześlij swoje pliki TSV." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Zostanie on natychmiast scalony i połączony." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Format pliku wartości rozdzielanych tabulatorami (TSV) reprezentuje dane oddzielone tabulatorami w formacie zwykłego tekstu. Format pliku, podobny do CSV, służy do organizowania danych w sposób ustrukturyzowany w celu importowania i eksportowania między różnymi aplikacjami. Format jest używany głównie do importu/eksportu i wymiany danych w aplikacjach arkuszy kalkulacyjnych i bazach danych. Każdy rekord w pliku TSV jest zawarty w pojedynczym wierszu pliku tekstowego, w którym każda wartość pola jest oddzielona znakiem tabulacji. Typ mediów dla formatu pliku TSV to tekst/wartości rozdzielane tabulatorami. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty scalania" subTitle="Używając Java, można również połączyć wiele innych formatów plików, w tym..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Format archiwum stron internetowych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="tekst" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Plik OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Szablon Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Szablon programu Excel z obsługą makr" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Szablon Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}