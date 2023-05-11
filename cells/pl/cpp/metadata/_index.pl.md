---
title: Zarządzaj metadanymi plików programu Excel pod numerem C++
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą biblioteki C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj metadanymi dokumentu Excel Microsoft<sup>&reg;</sup> za pośrednictwem C++" h2="Przeglądaj, wstawiaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości dokumentów programu Excel w aplikacjach C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadane w programie Excel — jak przeglądać, wstawiać i usuwać metadane plików programu Excel.[C++ Biblioteka programu Excel](/cells/pl/cpp/) ułatwia to w łatwy sposób poprzez obsługę wbudowanych/zdefiniowanych przez system właściwości, takich jak nazwisko autora, tytuł, statystyki dokumentu itp. pary nazwa/wartość. Aby zautomatyzować ten proces, biblioteka obsługuje tworzenie i utrzymywanie dużych plików metadanych Excel.[Metoda CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) z[Klasa fabryczna](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Otwórz skoroszyt według ścieżki, strumienia i specjalnego typu FileFormatType. Więc załaduj plik odpowiednią metodą do dalszego przetwarzania. Kilka z wymienionych poniżej możliwości, a programiści mogą łatwo ulepszyć swój kod zgodnie z wymaganiami aplikacji.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Odczytywanie i aktualizowanie właściwości wbudowanych" %}}

 Do automatyzacji wbudowanych właściwości zapewnia API[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metoda, która zwraca kolekcję DocumentProperties reprezentującą wszystkie wbudowane właściwości dokumentu arkusza kalkulacyjnego. Po uzyskaniu dostępu do wszystkich wbudowanych właściwości, uzyskaj dostęp do odpowiednich właściwości za pomocą odpowiedniej metody, takiej jak GetTitle(), GetSubject() itp. Aby zaktualizować właściwości, API zapewnia metodę, taką jak SetTitle, SetSubject, SetAuthor, SetComments itp. Zobacz[wbudowana kolekcja właściwości dokumentu](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) dla wymaganej funkcji.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do odczytu właściwości zdefiniowanych przez system" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kod aktualizujący wbudowane właściwości" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Wyświetl i dodaj niestandardowe właściwości zdefiniowane" %}}

Do obsługi właściwości niestandardowych służy numer API[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) która zwraca całą kolekcję niestandardowych właściwości dokumentu arkusza kalkulacyjnego. Po pierwsze, uzyskując dostęp do właściwości niestandardowych za pomocą tej metody, programiści mogą użyć odpowiednich metod, aby dodać właściwości, takie jak AddIDocumentProperty, AddLinkToContentProperty i podobnie użyć UpdateLinkedPropertyValue, UpdateLinkedRange, aby zaktualizować niestandardową wartość właściwości dokumentu, która łączy się odpowiednio z treścią i połączonym zakresem. Deweloperzy mogą użyć odpowiedniej metody z[zbiór niestandardowych właściwości dokumentu](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Kod do przeglądania właściwości niestandardowych" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kod dodawania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
