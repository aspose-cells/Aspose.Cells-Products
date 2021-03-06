---
title: Konwertuj TABDELIMITED na PNG przez Java 
url: /pl/java/conversion/tabdelimited-to-png/ 
description: Przykładowy kod konwersji Java dla formatu TABDELIMITED do pliku PNG. Programiści mogą użyć tego przykładowego kodu, aby wyeksportować arkusze kalkulacyjne Excel i OpenOffice do formatu PNG w dowolnej aplikacji internetowej lub desktopowej Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj TABDELIMITED na PNG przez Java" h2="Konwersja TABDELIMITED do PNG Java w celu konwersji jednej lub wielu stron do formatu PNG przy użyciu lokalnej biblioteki Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować TABDELIMITED na PNG za pomocą Java" %}}

 Aby wyrenderować TABDELIMITED do PNG, użyjemy
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować TABDELIMITED na PNG za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą łatwo przekonwertować plik TABDELIMITED na PNG w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik TABDELIMITED z instancją Workbook1. Wybierz domyślny lub dowolny arkusz z kolekcji1. Utwórz i ustaw obiekt ImageOrPrintOptions1. Utwórz SheetRender z obiektami Worksheet i ImageOrPrintOptions1. Wywołaj metodę SheetRender.toImage, aby zapisać wynik w formacie PNG

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu źródłowego konwersji Java upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio od firmy Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED do PNG Java Kod źródłowy konwersji" offSpacer="" %}}

```cs
// załaduj plik TABDELIMITED do renderowania
Workbook workbook = new Workbook("sourceFile.tabdelimited");
// uzyskać dostęp do domyślnego arkusza roboczego z kolekcji
Worksheet worksheet = workbook.getWorksheets().get(0);
// zdefiniuj parametry dla obrazu wynikowego
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.PNG);
// przekonwertuj arkusz roboczy na obraz w formacie PNG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.png");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED do konwersji na żywo w formacie PNG" sectionDescription="[Konwertuj TABDELIMITED na PNG](https://products.aspose.app/cells/conversion/tabdelimited-to-png) teraz, odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik TABDELIMITED, zostanie on natychmiast przekonwertowany do formatu PNG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java Biblioteka manipulacji arkuszem kalkulacyjnym" %}}

 Excel API może być używany do tworzenia, edytowania, konwertowania i renderowania formatów Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG, Portable Network Graphics, odnosi się do formatu pliku obrazu rastrowego, który wykorzystuje kompresję bezstratną. Ten format pliku został utworzony jako zamiennik formatu Graphics Interchange Format (GIF) i nie ma ograniczeń dotyczących praw autorskich. Jednak format pliku PNG nie obsługuje animacji. Format plików PNG obsługuje bezstratną kompresję obrazu, dzięki czemu jest popularny wśród użytkowników. Z biegiem czasu PNG stał się jednym z najczęściej używanych formatów plików graficznych. Prawie wszystkie systemy operacyjne obsługują otwieranie plików PNG. Na przykład przeglądarka Microsoft Windows ma możliwość otwierania plików PNG, ponieważ system operacyjny domyślnie obsługuje wsparcie dostępne w ramach instalacji.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}