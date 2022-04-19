---
title: Zarządzaj metadanymi pliku Excel za pośrednictwem .NET C#
url: /pl/net/metadata/
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą zaledwie kilku linijek kodu C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj metadanymi plików Microsoft<sup>&reg;</sup> Excel za pomocą .NET" h2="Wyświetlaj, dodawaj, aktualizuj, usuwaj lub wyodrębniaj wbudowane i niestandardowe właściwości plików programu Excel za pomocą interfejsów API .NET po stronie serwera." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) obsługuje zarządzanie właściwościami zdefiniowanymi przez system (wbudowanymi), takimi jak tytuł, nazwisko autora, statystyki dokumentów itp., a także właściwościami zdefiniowanymi przez użytkownika (niestandardowymi) w postaci pary nazwa-wartość. Jest [Zajęcia ze skoroszytu](https://apireference.aspose.com/cells/net/aspose.cells/workbook) załadować pliki i [Kolekcja arkuszy roboczych](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) zajmuje się zbieraniem kart pracy oraz [Klasa arkusza](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) do reprezentowania pojedynczego arkusza roboczego. Wraz z tymi klasami BuiltInDocumentProperties, CustomDocumentProperties upraszczają proces zarządzania metadanymi. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zarządzanie wbudowanymi właściwościami" %}}

Do zarządzania właściwościami zdefiniowanymi przez system API zapewnia [Wbudowane właściwości dokumentu](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), a programiści mogą łatwo uzyskać dostęp do wbudowanej właściwości i zaktualizować jej wartość. W zależności od wymagań aplikacji programiści mogą używać nazwy indeksu lub właściwości z [Kolekcja właściwości dokumentu](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kod do zarządzania wbudowanymi właściwościami" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Zarządzanie właściwościami zdefiniowanymi przez użytkownika" %}}

Do zarządzania właściwościami zdefiniowanymi przez użytkownika API zapewnia [Niestandardowe właściwości dokumentu](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), a programiści mogą łatwo uzyskać dostęp do już dodanych właściwości, a także dodawać nowe. Aby dodać niestandardowe właściwości, [Dodaj metodę](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) z [Niestandardowa kolekcja właściwościDokumentu](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class dodaje właściwość i zwraca odwołanie do nowej właściwości jako [Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) obiekt. Klasa DocumentProperty służy do pobierania nazwy, wartości i typu właściwości dokumentu jako [DocumentProperty.Name](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) który zwraca jeden z [Typ nieruchomości](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) wartości wyliczenia. 
 
{{% blocks/products/pf/feature-page-code h3="C# Kod dodawania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kod do usuwania niestandardowej właściwości w pliku Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
