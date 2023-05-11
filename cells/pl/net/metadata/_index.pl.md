---
title: Zarządzaj metadanymi pliku programu Excel via .NET C#
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą zaledwie kilku wierszy kodu C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj Microsoft<sup>&reg;</sup> metadanymi pliku programu Excel via .NET" h2="Przeglądaj, dodawaj, aktualizuj, usuwaj lub wyodrębniaj wbudowane i niestandardowe właściwości plików programu Excel za pomocą interfejsów API .NET po stronie serwera." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/pl/net/) obsługuje zarządzanie właściwościami zdefiniowanymi przez system (wbudowanymi), takimi jak tytuł, nazwisko autora, statystyki dokumentu itp., a także właściwościami zdefiniowanymi przez użytkownika (niestandardowymi) w postaci pary nazwa-wartość. Jest[Klasa skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook) aby załadować pliki i[Kolekcja arkuszy roboczych](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) zajmuje się również zbieraniem kart pracy[Klasa arkusza](https://reference.aspose.com/cells/net/aspose.cells/worksheet) do reprezentowania pojedynczego arkusza. Wraz z tymi klasami BuiltInDocumentProperties, CustomDocumentProperties upraszcza proces zarządzania metadanymi.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zarządzanie wbudowanymi właściwościami" %}}

 Do zarządzania właściwościami zdefiniowanymi przez system służy API[Wbudowane właściwości dokumentu](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , a programiści mogą łatwo uzyskać dostęp do wbudowanej właściwości i aktualizować jej wartość. W zależności od wymagań aplikacji programiści mogą używać indeksu lub nazwy właściwości z pliku[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kod do zarządzania wbudowanymi właściwościami" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Zarządzanie zdefiniowanymi przez użytkownika właściwościami" %}}

 Do zarządzania właściwościami zdefiniowanymi przez użytkownika służy numer API[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , a programiści mogą łatwo uzyskać dostęp do już dodanych właściwości, a także dodawać nowe właściwości. Aby dodać niestandardowe właściwości,[Dodaj metodę](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) z[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class dodaje właściwość i zwraca odwołanie do nowej właściwości jako[Właściwości.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) obiekt. Klasa DocumentProperty służy do pobierania nazwy, wartości i typu właściwości dokumentu jako[NazwaWłaściwościDokumentu](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Typ](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) który zwraca jeden z[Typ nieruchomości](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) wartości wyliczeniowe.
 
{{% blocks/products/pf/feature-page-code h3="C# Kod dodawania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kod do usuwania niestandardowej właściwości w pliku programu Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
