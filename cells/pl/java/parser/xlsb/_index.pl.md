---
title: Wyodrębnij tekst i obrazy z dokumentu XLSB za pomocą Java 
weight: 440
url: /pl/java/parser/xlsb/ 
description: Java przykładowy kod do wyodrębniania tekstu i obrazów z pliku XLSB w Java środowisku wykonawczym dla aplikacji JSP/JSF i aplikacji komputerowych.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Analizuj formaty XLSB w Java" h2="Natywne i wysoce wydajne analizowanie dokumentów XLSB przy użyciu interfejsów API Aspose.Cellsfor Java po stronie serwera, bez użycia oprogramowania, takiego jak Microsoft lub Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak przeanalizować plik XLSB za pomocą Java" %}}

 Aby przeanalizować plik XLSB, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą do analizowania API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio z
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przeanalizować pliki XLSB w Java" %}}

{{% blocks/products/pf/agp/text %}}

 Podstawowe parsowanie dokumentów za pomocą
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API można wykonać za pomocą kilku linijek kodu. Analizuj tekst i obrazy z plików Microsoft Excel XLS, XLSX, XLSM, XLSB i OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj dokument XLSB za pomocą klasy Workbook.
+ Wybierz żądany arkusz za pomocą metody getWorksheets().get.
+ Pobierz wszystkie komórki wybranego arkusza za pomocą getCells().
+ Iteruj po każdej komórce, pobierz jej tekst.
+ Wydrukuj wartość każdej komórki lub użyj metody Append() StringBuilder, aby wyświetlić jako całość

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.- Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analizuj pliki XLSB — Java" offSpacer="" %}}

```cs
StringBuilder stringBuilder = new StringBuilder();
Workbook book = new Workbook(dir + "book1.xlsb");
Worksheet sheet = book.getWorksheets().get(0);
Cells cells = sheet.getCells();
Iterator iterator = cells.iterator();
while(iterator.hasNext())
{
Cell cell = (Cell)iterator.next();
stringBuilder.append(cell.getStringValue());
stringBuilder.append(" ");
}
System.out.println(stringBuilder.toString());  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API może służyć do tworzenia, edytowania, konwertowania i renderowania formatów programu Microsoft Excel do różnych formatów. Co więcej, może być używany do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Aspose.Cells jest samodzielnym API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Internetowe prezentacje na żywo Parser XLSB" sectionDescription="Wyodrębnij tekst i obrazy z dokumentów XLSB już teraz, odwiedzając nasz [Witryna demonstracyjna na żywo](https://products.aspose.app/cells/parser). Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie ma potrzeby pobierania Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swoje pliki XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Zostanie on natychmiast przeanalizowany." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Format pliku XLSB określa format pliku binarnego programu Excel, który jest zbiorem rekordów i struktur określających zawartość skoroszytu programu Excel. Treść może obejmować nieustrukturyzowane lub częściowo ustrukturyzowane tabele liczb, tekst lub zarówno liczby, jak i tekst, formuły, połączenia danych zewnętrznych, wykresy i obrazy. W przeciwieństwie do XLSX (który jest oparty na formacie pliku Open XML), XLSB reprezentuje binarny plik skoroszytu programu Excel. Pliki XLSB można szybciej odczytywać i zapisywać, co czyni je przydatnymi do pracy z dużymi plikami. XLSB jest rzadko używany do przechowywania skoroszytów, ponieważ XLSX (i wcześniej XLS) to najczęściej wybierane przez użytkowników formaty plików do zapisywania skoroszytów. Można go otworzyć w Microsoft Office 2007 i nowszych. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane dokumenty analizowania" subTitle="Używając Java, można łatwo analizować inne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/ods/" name="SZWO" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xls/" name="XLS" description="Format binarny programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}