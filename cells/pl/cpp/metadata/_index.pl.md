---
title: Zarządzaj metadanymi pliku Excel za pomocą C++
url: /pl/cpp/metadata/
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą C++biblioteki
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj metadanymi dokumentów Microsoft<sup>&reg;</sup> Excel za pomocą C++" h2="Przeglądaj, wstawiaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości dokumentów programu Excel w C++ aplikacjach." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadane w programie Excel — jak wyświetlać, wstawiać i usuwać metadane pliku programu Excel. [C++ Biblioteka Excela](/cells/cpp/) ułatwia to w łatwy sposób, obsługując wbudowane / zdefiniowane przez system właściwości, takie jak imię i nazwisko autora, tytuł, statystyki dokumentu itp., potrzebne czasami, np. sprawdzanie, kiedy plik został ostatnio zmodyfikowany lub zapisany wraz z niestandardowymi / zdefiniowanymi przez użytkownika właściwościami w postaci pary nazwa/wartość. Aby zautomatyzować proces, biblioteka wspiera tworzenie i utrzymywanie dużych metadanych plików Excel. [Metoda CreateIWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) z [Klasa fabryczna](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) Otwórz skoroszyt według ścieżki, strumienia i specjalnego typu FileFormatType. Załaduj plik odpowiednią metodą do dalszego przetwarzania. Niewiele z wymienionych poniżej możliwości, a programiści mogą łatwo ulepszyć swój kod zgodnie z wymaganiami aplikacji. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Odczytywanie i aktualizowanie wbudowanych właściwości" %}}

Aby zautomatyzować wbudowane właściwości, API zapewnia [GetIBuiltInDocumentProperties()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) Metoda zwracająca kolekcję DocumentProperties reprezentującą wszystkie wbudowane właściwości dokumentu arkusza kalkulacyjnego. Po uzyskaniu dostępu do wszystkich wbudowanych właściwości, uzyskaj dostęp do odpowiednich właściwości za pomocą odpowiedniej metody, takiej jak GetTitle(), GetSubject() itp. Aby zaktualizować właściwości, API udostępnia metodę, taką jak SetTitle, SetSubject, SetAuthor, SetComments itp. Wyświetl [wbudowana kolekcja właściwości dokumentów](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) dla wymaganej funkcji.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do odczytu właściwości zdefiniowanych przez system" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kod do aktualizacji wbudowanych właściwości" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Wyświetl i dodaj niestandardowe zdefiniowane właściwości" %}}

Do obsługi właściwości niestandardowych API zapewnia [IWorkbookMetadata::GetICustomDocumentProperties](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) zwraca wszystkie niestandardowe właściwości dokumentu w arkuszu kalkulacyjnym. Po pierwsze, uzyskując dostęp do właściwości niestandardowych za pomocą tej metody, programiści mogą użyć odpowiednich metod, aby dodać właściwości, takie jak AddIDocumentProperty, AddLinkToContentProperty i podobnie użyć UpdateLinkedPropertyValue, UpdateLinkedRange do aktualizacji niestandardowej wartości właściwości dokumentu, która łączy się odpowiednio z treścią i połączonym zakresem. Deweloperzy mogą użyć odpowiedniej metody z [zbiór niestandardowych właściwości dokumentu](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Kod do wyświetlania właściwości niestandardowych" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kod dodawania metadanych w pliku Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}