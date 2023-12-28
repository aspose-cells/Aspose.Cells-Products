---
title: Zarządzaj metadanymi pliku Excel via .NET C#
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą zaledwie kilku wierszy kodu C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj Microsoft<sup>&reg;</sup> Metadanymi pliku Excel via .NET" h2="Przeglądaj, dodawaj, aktualizuj, usuwaj lub wyodrębniaj wbudowane i niestandardowe właściwości plików Excel za pomocą interfejsów API po stronie serwera .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/pl/net/) wspiera zarządzanie właściwościami zdefiniowanymi przez system (wbudowanymi), takimi jak tytuł, nazwisko autora, statystyki dokumentu itp., a także właściwościami zdefiniowanymi przez użytkownika (niestandardowymi) w formie pary nazwa-wartość. Jest[Zajęcia ze skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook) aby załadować pliki i[Kolekcja arkuszy roboczych](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) zajmuje się także zbieraniem arkuszy ćwiczeń[Klasa arkusza roboczego](https://reference.aspose.com/cells/net/aspose.cells/worksheet) do reprezentowania pojedynczego arkusza. Wraz z tymi klasami BuildInDocumentProperties i CustomDocumentProperties upraszczają proces zarządzania metadanymi.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zarządzanie wbudowanymi właściwościami" %}}

 Do zarządzania właściwościami zdefiniowanymi przez system służy numer API[Wbudowane właściwości dokumentu](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) a programiści mogą łatwo uzyskać dostęp do wbudowanej właściwości i zaktualizować jej wartość. W zależności od wymagań aplikacji programiści mogą użyć indeksu lub nazwy właściwości z pliku[Kolekcja DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kod do zarządzania wbudowanymi właściwościami" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Zarządzanie niestandardowymi właściwościami" %}}

 Do zarządzania właściwościami zdefiniowanymi przez użytkownika służy numer API[Niestandardowe właściwości dokumentu](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , a programiści mogą łatwo uzyskać dostęp do już dodanych właściwości, a także dodawać nowe. Aby dodać właściwości niestandardowe,[Dodaj metodę](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) z[Kolekcja CustomDocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class dodaje właściwość i zwraca odwołanie do nowej właściwości jako[Właściwości.Właściwość dokumentu](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) obiekt. Klasa DocumentProperty służy do pobierania nazwy, wartości i typu właściwości dokumentu jako[Nazwa właściwości dokumentu.Nazwa](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [Właściwość dokumentu.Wartość](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [Właściwość dokumentu.Typ](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) która zwraca jedną z[Typ nieruchomości](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) wartości wyliczeniowe.
 
{{% blocks/products/pf/feature-page-code h3="C# Kod do dodania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kod umożliwiający usunięcie właściwości niestandardowej z pliku Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
