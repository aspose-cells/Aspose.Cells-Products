---
title:  Chroń i zablokuj dokument XLS via Java
weight: 5070
description: Java przykładowy kod do blokowania pliku XLS przy użyciu hasła w Java Środowisko wykonawcze dla aplikacji JSP/JSF i aplikacji komputerowych.
keywords: [Java Aspose.Cells., Java Lock XLS files., Java How to Protect and lock XLS document., Java Protect XLS files., Encrypt XLS Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Zaszyfruj XLS Pliki via Java" h2="Zabezpiecz hasłem arkusze kalkulacyjne Excel, w tym format XLS, korzystając z biblioteki .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak zabezpieczyć plik XLS za pomocą Java" %}}

 Aby chronić plik XLS, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą szyfrującą API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio ze strony
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 i zainstaluj go w projekcie opartym na Maven, dodając następujące konfiguracje do pliku pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Magazyn" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby chronić pliki XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Ochronę dokumentów za pomocą interfejsów API Aspose.Cells można wykonać za pomocą zaledwie kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

1.  Załaduj plik XLS, tworząc instancję klasy Workbook
1.  Użyj metody Protect(..) z Typem ochrony i Hasłem
1.  Zapisz chroniony plik XLS metodą save().

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.
-  Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="" %}}

```cs

// Open the XLS file
Workbook wkb = new Workbook("sourceFile.xls");

// Protect workbook by specifying protection type
wkb.protect(ProtectionType.ALL, "12345");

// Save the XLS file
wkb.save("lockedFile.xls");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Bezpłatna aplikacja do ochrony XLS" sectionDescription=" Sprawdź nasze demonstracje na żywo[zaszyfruj pliki XLS](https://products.aspose.app/cells/protect/xls) z następującymi korzyściami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLS i naciśnij przycisk „Odblokuj”." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Pobierz wynikowy plik XLS z łącza" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Pliki z rozszerzeniem XLS reprezentują format pliku binarnego programu Excel. Takie pliki można utworzyć za pomocą Microsoft Excel, a także innych podobnych programów do obsługi arkuszy kalkulacyjnych, takich jak OpenOffice Calc lub Apple Numbers. Plik zapisany w programie Excel jest znany jako skoroszyt, gdzie każdy skoroszyt może zawierać jeden lub więcej arkuszy. Dane są przechowywane i wyświetlane użytkownikom w formie tabeli w arkuszu i mogą obejmować wartości liczbowe, dane tekstowe, formuły, zewnętrzne połączenia danych, obrazy i wykresy. Aplikacje takie jak Microsoft Excel umożliwiają eksportowanie danych skoroszytu do kilku różnych formatów, w tym PDF, CSV, XLSX, TXT, HTML, XPS i kilku innych. Format pliku XLS został zastąpiony bardziej otwartym i ustrukturyzowanym formatem XLSX wraz z wydaniem Microsoft Excel 2007. Najnowsze wersje nadal zapewniają obsługę tworzenia i odczytywania plików XLS, chociaż XLSX jest obecnie pierwszym wyborem.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty zabezpieczające" subTitle="Używając numeru Java, można chronić inne pliki, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
