---
title:  Generuj raporty w plikach XLSB via Java
weight: 3560
description: Java przykładowy kod do tworzenia raportów w formacie XLSB w środowisku wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.
keywords: [Java Aspose.Cells., Java Create XLSB Reports Based on Predesigned Excel Template., Java Generate XLSB Reports Based on Predesigned Excel Template., Java Create XLSB Reports Based on Excel Template., Java Generate XLSB Reports Based on Excel Template., Java Create XLSB files Based on Excel Template., Java Generate XLSB files Based on Excel Template]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Zbiorcze generowanie raportu w formacie XLSB via Java" h2="Generuj raporty w formacie XLSB, korzystając ze źródła danych i szablonu." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak wygenerować raporty XLSB przy użyciu Java" %}}

 Aby utworzyć raporty w pliku XLSB, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, który jest bogatą w funkcje, wydajną i łatwą w użyciu platformą montażową API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio ze strony
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 i zainstaluj go w projekcie opartym na Maven, dodając następujące konfiguracje do pliku pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby wygenerować raporty XLSB via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Utwórz instancję klasy WorkbookDesigner
1. Dodaj obiekty Datasouce do listy ArrayList
1.  Ustaw źródło danych i proces dla obiektu WorkbookDesigner
1.  Zapisz wynik w formacie XLSB za pomocą metody Worbook.save

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.
- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio z Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Generuj raporty Excel w formacie XLSB - Java" offSpacer="" %}}

```java
//Create a workbook designer
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Create Persons objects with photos
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Set the data source and process smart marker tags
designer.setDataSource("Person", persons);
designer.process();

//Save the workbook
workbook.save(dataDir + "output.xlsb", SaveFormat.XLSB);
	
System.out.println("File saved");
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Bezpłatna aplikacja do montażu XLSB" sectionDescription=" Sprawdź nasze demonstracje na żywo[utwórz pliki XLSB](https://products.aspose.app/cells/assembly/xlsb) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLSB i naciśnij przycisk „Assembluj”." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Pobierz wynikowy plik XLSB z łącza" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Format pliku XLSB określa format pliku binarnego programu Excel, który jest zbiorem rekordów i struktur określających zawartość skoroszytu programu Excel. Treść może obejmować nieustrukturyzowane lub częściowo ustrukturyzowane tabele liczb, tekst lub zarówno liczby, jak i tekst, formuły, zewnętrzne połączenia danych, wykresy i obrazy. W przeciwieństwie do XLSX (opartego na formacie pliku Open XML), XLSB reprezentuje binarny plik skoroszytu programu Excel. Pliki XLSB można szybciej odczytywać i zapisywać, co czyni je przydatnymi do pracy z dużymi plikami. Numer XLSB jest rzadko używany do przechowywania skoroszytów, ponieważ XLSX (a wcześniej XLS) to najpopularniejsze formaty plików wybierane przez użytkowników do zapisywania skoroszytów. Można go otworzyć pod numerem Microsoft Office 2007 i nowszych.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty generowania raportów" subTitle="Za pomocą numeru Java można łatwo generować raporty w wielu formatach, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
