---
title: Zarządzaj metadanymi pliku programu Excel via Java
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą zaledwie kilku wierszy kodu Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj Microsoft<sup>&reg;</sup> metadanymi pliku programu Excel via Java" h2="Przeglądaj, dodawaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości plików programu Excel za pomocą interfejsów API Java po stronie serwera." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/pl/java/) obsługuje zarządzanie wbudowanymi (zdefiniowanymi przez system) właściwościami, takimi jak tytuł, nazwisko autora, statystyki dokumentu itp., jak również właściwościami niestandardowymi (zdefiniowanymi przez użytkownika) w postaci pary nazwa/wartość. Jest[Klasa skoroszytu](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) aby załadować pliki i[Kolekcja arkuszy roboczych](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)zajmuje się również zbieraniem kart pracy[Klasa arkusza](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) do reprezentowania pojedynczego arkusza. Aby uzyskać dostęp do wbudowanych i niestandardowych właściwości, BuiltInDocumentProperties, CustomDocumentProperties upraszcza proces zarządzania metadanymi.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zarządzanie właściwościami zdefiniowanymi przez system" %}}

 Do zarządzania wbudowanymi właściwościami służy API[Wbudowane właściwości dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) , a programiści mogą łatwo uzyskać dostęp do wbudowanej właściwości i aktualizować jej wartość. W zależności od wymagań aplikacji programiści mogą używać indeksu lub nazwy właściwości z pliku[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kod do zarządzania właściwościami zdefiniowanymi przez system" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Dodawaj i usuwaj niestandardowe zdefiniowane metadane" %}}

Do obsługi właściwości niestandardowych służy numer API[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , a programiści mogą łatwo uzyskiwać dostęp do istniejących właściwości, a także dodawać nowe właściwości za pomocą[dodaj metodę](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) z[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class dodaje właściwość i zwraca odwołanie do nowej właściwości jako[Właściwości.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)obiekt. Klasa DocumentProperty służy do pobierania nazwy, wartości i typu właściwości dokumentu jako[NazwaWłaściwościDokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Typ](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) który zwraca jeden z[Typ nieruchomości](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) wartości wyliczeniowe.
 
{{% blocks/products/pf/feature-page-code h3="Java Kod dodawania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kod do usunięcia niestandardowej właściwości w pliku programu Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
