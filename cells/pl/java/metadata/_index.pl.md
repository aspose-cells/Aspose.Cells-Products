---
title: Zarządzaj metadanymi pliku Excel za pomocą Java

description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą zaledwie kilku linijek kodu Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj metadanymi plików Microsoft<sup>&reg;</sup> Excel za pomocą Java" h2="Wyświetlaj, dodawaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości plików programu Excel za pomocą interfejsów API Java po stronie serwera." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) obsługuje zarządzanie wbudowanymi (zdefiniowanymi przez system) właściwościami, takimi jak tytuł, nazwisko autora, statystyki dokumentów itp., a także niestandardowymi (zdefiniowanymi przez użytkownika) właściwościami w postaci pary nazwa/wartość. Jest [Zajęcia ze skoroszytu](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) załadować pliki i [Kolekcja arkuszy roboczych](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) zajmuje się zbieraniem kart pracy oraz [Klasa arkusza](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) do reprezentowania pojedynczego arkusza roboczego. Aby uzyskać dostęp do właściwości wbudowanych i niestandardowych, BuiltInDocumentProperties, CustomDocumentProperties upraszcza proces zarządzania metadanymi. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zarządzanie właściwościami zdefiniowanymi przez system" %}}

Do zarządzania wbudowanymi właściwościami API zapewnia [Wbudowane właściwości dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), a programiści mogą łatwo uzyskać dostęp do wbudowanej właściwości i zaktualizować jej wartość. W zależności od wymagań aplikacji programiści mogą używać nazwy indeksu lub właściwości z [Kolekcja właściwości dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kod do zarządzania właściwościami zdefiniowanymi przez system" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Dodaj i usuń niestandardowe metadane" %}}

Do obsługi właściwości niestandardowych API zapewnia [Niestandardowe właściwości dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), a programiści mogą łatwo uzyskać dostęp do istniejących właściwości, a także dodawać nowe za pomocą [dodaj metodę](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) z [Niestandardowa kolekcja właściwościDokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class dodaje właściwość i zwraca odwołanie do nowej właściwości jako [Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) obiekt. Klasa DocumentProperty służy do pobierania nazwy, wartości i typu właściwości dokumentu jako [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) który zwraca jeden z [Typ nieruchomości](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) wartości wyliczenia. 
 
{{% blocks/products/pf/feature-page-code h3="Java Kod dodawania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kod do usunięcia niestandardowej właściwości w pliku Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
