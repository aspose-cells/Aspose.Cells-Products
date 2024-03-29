---
title:  Edytuj lub wyświetl XLSM Metadane plików via Java
weight: 9030
description: Java przykładowy kod do edycji lub przeglądania metadanych w formacie XLSM w środowisku wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.
keywords: [Java Aspose.Cells., Java view xlsm metadata., Java add xlsm metadata., Java insert xlsm metadata., Java edit xlsm metadata., Java remove xlsm metadata., Java extract xlsm metadata., Java modify xlsm metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wyciąg XLSM Metadane via Java" h2="Twórz własne aplikacje Java, aby dodawać, edytować, usuwać lub wyodrębniać metadane z plików XLSM za pomocą interfejsów API po stronie serwera." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak wyodrębnić metadane XLSM przy użyciu Java" %}}

 Aby uzyskać metadane pliku XLSM, użyjemy
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu platformą metadanych API for Java. Możesz pobrać jego najnowszą wersję bezpośrednio ze strony
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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby wyodrębnić metadane z numeru XLSM via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Uzyskaj dostęp do przydatnych informacji przechowywanych w pliku XLSM, w tym o tym, kiedy plik XLSM został odebrany, przetworzony, oznaczony znacznikiem czasu i tak dalej.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik XLSM w WorkbookMetadata
+ Utwórz obiekt MetadataOptions z odpowiednimi opcjami
+ Ustaw odpowiednie właściwości
+ Zapisz informacje o metadanych XLSM

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java obsługuje wszystkie główne platformy i systemy operacyjne. Upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub zgodny system operacyjny ze środowiskiem wykonawczym Java dla aplikacji JSP/JSF i aplikacji komputerowych.
-  Pobierz najnowszą wersję Aspose.Cells for Java bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wyodrębnij metadane XLSM–Java" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.xlsm", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.xlsm");

// Open the workbook
Workbook w = new Workbook("Sample1.out.xlsm");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API można używać do tworzenia, edytowania, konwertowania i renderowania formatów Excel Microsoft do różnych formatów. Co więcej, można go używać do kompleksowych wykresów, skalowalnych raportów i niezawodnych obliczeń w aplikacjach. Numer Aspose.Cells jest samodzielnym numerem API i nie wymaga żadnego oprogramowania takiego jak Microsoft czy OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Wyodrębnij metadane numeru XLSM za pośrednictwem aplikacji internetowej" sectionDescription=" Przeglądaj i edytuj metadane do dokumentów XLSM, korzystając z naszego[Demo na żywo](https://products.aspose.app/cells/metadata) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie trzeba niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać żadnego kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik XLSM i edytuj właściwości dokumentu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Natychmiast uzyskaj łącze do pobrania pliku wynikowego" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Pliki z rozszerzeniem XLSM to rodzaj plików arkuszy kalkulacyjnych obsługujących makra. Z aplikacyjnego punktu widzenia Makro to zestaw instrukcji służących do automatyzacji procesów. Makro służy do rejestrowania powtarzających się kroków i ułatwia wykonanie czynności poprzez ponowne uruchomienie makra. Makra są programowane w języku Visual Basic for Applications (VBA) Microsoft z poziomu skoroszytu programu Excel za pomocą edytora Visual Basic i można je bezpośrednio z niego uruchamiać/debugować.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty metadanych" subTitle="Używając numeru Java, można także manipulować metadanymi w wielu innych formatach, w tym" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
