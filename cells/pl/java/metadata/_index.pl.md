---
title: Zarządzaj metadanymi pliku Excel via Java
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą zaledwie kilku wierszy kodu Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj Microsoft<sup>&reg;</sup> Metadanymi pliku Excel via Java" h2="Przeglądaj, dodawaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości plików Excel za pomocą interfejsów API po stronie serwera Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/pl/java/) obsługuje zarządzanie wbudowanymi (zdefiniowanymi przez system) właściwościami, takimi jak tytuł, nazwisko autora, statystyki dokumentu itp., a także właściwościami niestandardowymi (zdefiniowanymi przez użytkownika) w postaci pary nazwa/wartość. Jest[Zajęcia ze skoroszytu](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) aby załadować pliki i[Kolekcja arkuszy roboczych](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) zajmuje się także zbieraniem arkuszy ćwiczeń[Klasa arkusza roboczego](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) do reprezentowania pojedynczego arkusza. Aby uzyskać dostęp do właściwości wbudowanych i niestandardowych, BuildingInDocumentProperties, CustomDocumentProperties upraszcza proces zarządzania metadanymi.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zarządzanie właściwościami zdefiniowanymi przez system" %}}

 Do zarządzania wbudowanymi właściwościami służy numer API[Wbudowane właściwości dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) a programiści mogą łatwo uzyskać dostęp do wbudowanej właściwości i zaktualizować jej wartość. W zależności od wymagań aplikacji programiści mogą użyć indeksu lub nazwy właściwości z pliku[Kolekcja DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kod do zarządzania właściwościami zdefiniowanymi przez system" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Dodawaj i usuwaj niestandardowe metadane" %}}

Do obsługi właściwości niestandardowych udostępnia numer API[Niestandardowe właściwości dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , a programiści mogą łatwo uzyskać dostęp do istniejących właściwości, a także dodawać nowe za pomocą[dodaj metodę](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) z[Kolekcja CustomDocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class dodaje właściwość i zwraca odwołanie do nowej właściwości jako[Właściwości.Właściwość dokumentu](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) obiekt. Klasa DocumentProperty służy do pobierania nazwy, wartości i typu właściwości dokumentu jako[Nazwa właściwości dokumentu.Nazwa](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [Właściwość dokumentu.Wartość](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [Właściwość dokumentu.Typ](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) która zwraca jedną z[Typ nieruchomości](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) wartości wyliczeniowe.
 
{{% blocks/products/pf/feature-page-code h3="Java Kod do dodania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kod umożliwiający usunięcie właściwości niestandardowej z pliku Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
