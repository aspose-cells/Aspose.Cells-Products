---
title: Edytuj lub wyświetl metadane plików XLS za pomocą Java 
weight: 730
url: /pl/java/metadata/xls/ 
description: Java przykładowy kod do edycji lub przeglądania metadanych formatu XLS w Java środowisku wykonawczym dla aplikacji JSP/JSF i aplikacji komputerowych.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyodrębnij metadane XLS przez Java" h2="Twórz własne Java aplikacje, aby dodawać, edytować, usuwać lub wyodrębniać metadane z plików XLS za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak wyodrębnić metadane XLS za pomocą Java" %}}

 Aby uzyskać metadane pliku XLS, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą metadanych API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki wyodrębniania metadanych XLS za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

 Uzyskaj dostęp do przydatnych informacji przechowywanych w pliku XLS, w tym kiedy plik XLS został odebrany, przetworzony, oznaczony sygnaturą czasową i tak dalej.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik XLS w WorkbookMetadata
+ Utwórz obiekt MetadataOptions z odpowiednimi opcjami
+ Ustaw odpowiednie właściwości
+ Zapisz informacje o metadanych XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyodrębnij metadane XLS — Java" offSpacer="" %}}

```cs

// Otwórz metadane skoroszytu
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.xls", options);

// Ustaw niektóre właściwości
meta.getCustomDocumentProperties().add("test", "test");

// Zapisz informacje o metadanych
meta.save("Sample1.out.xls");

// Otwórz skoroszyt
Workbook w = new Workbook("Sample1.out.xls");

// Przeczytaj właściwość dokumentu
System.out.println(w.getCustomDocumentProperties().get("test"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Wyodrębnij metadane XLS za pośrednictwem aplikacji online" sectionDescription="Przeglądaj i edytuj Metadane do dokumentów XLS za pomocą naszego [Prezentacje na żywo](https://products.aspose.app/cells/metadata) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLS i edytuj właściwości dokumentu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Natychmiast uzyskaj link do pobrania pliku wynikowego" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Pliki z rozszerzeniem XLS reprezentują format pliku binarnego Excel. Takie pliki mogą być tworzone przez Microsoft Excel, a także inne podobne programy do arkuszy kalkulacyjnych, takie jak OpenOffice Calc lub Apple Numbers. Plik zapisany przez program Excel jest znany jako skoroszyt, w którym każdy skoroszyt może zawierać jeden lub więcej arkuszy. Dane są przechowywane i wyświetlane użytkownikom w formacie tabeli w arkuszu i mogą obejmować wartości liczbowe, dane tekstowe, formuły, połączenia danych zewnętrznych, obrazy i wykresy. Aplikacje takie jak Microsoft Excel umożliwiają eksportowanie danych ze skoroszytu do kilku różnych formatów, w tym PDF, CSV, XLSX, TXT, HTML, XPS i kilku innych. Format pliku XLS został zastąpiony bardziej otwartym i ustrukturyzowanym formatem, XLSX, wraz z wydaniem Microsoft Excel 2007. Najnowsze wersje nadal zapewniają obsługę tworzenia i odczytywania plików XLS, chociaż XLSX jest teraz pierwszym wyborem.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty metadanych" subTitle="Używając Java, można również manipulować metadanymi wielu innych formatów, w tym" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/ods/" name="SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="Plik OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}