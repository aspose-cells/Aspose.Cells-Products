---
title: Zarządzaj metadanymi plików Excel pod numerem C++
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą biblioteki C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj metadanymi dokumentu Excel Microsoft<sup>&reg;</sup> pod numerem C++" h2="Przeglądaj, wstawiaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości dokumentów Excel w aplikacjach C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadane w Excelu - Jak przeglądać, wstawiać i usuwać metadane pliku Excel.[C++ Biblioteka Excela](/cells/pl/cpp/) ułatwia to w łatwy sposób poprzez obsługę wbudowanych/zdefiniowanych przez system właściwości, takich jak imię i nazwisko autora, tytuł, statystyki dokumentu itp. potrzebnych czasami do sprawdzania, kiedy plik został ostatnio zmodyfikowany lub zapisany wraz z właściwościami niestandardowymi/zdefiniowanymi przez użytkownika w formie pary nazwa/wartość. Aby zautomatyzować proces, biblioteka umożliwia tworzenie i utrzymywanie dużych plików Excel z metadanymi.[zeszyt ćwiczeń](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Otwiera skoroszyt według ścieżki, strumienia i specjalnego FileFormatType. Zatem załaduj plik odpowiednią metodą w celu dalszego przetwarzania. Niewiele z możliwości wymienionych poniżej pozwala programistom łatwo ulepszyć swój kod zgodnie z wymaganiami aplikacji.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Przeczytaj i zaktualizuj wbudowane właściwości" %}}

 Do automatyzacji wbudowanych właściwości zapewnia API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) metoda zwracająca kolekcję DocumentProperties reprezentującą wszystkie wbudowane właściwości dokumentu arkusza kalkulacyjnego. Po uzyskaniu dostępu do wszystkich wbudowanych właściwości, uzyskaj dostęp do odpowiednich właściwości za pomocą odpowiednich metod, takich jak GetTitle(), GetSubject() itp. Aby zaktualizować właściwości, API udostępnia metody takie jak SetTitle, SetSubject, SetAuthor, SetComments itp. Zobacz[wbudowana kolekcja właściwości dokumentu](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) dla wymaganej funkcji.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do odczytu właściwości zdefiniowanych przez system" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kod do aktualizacji wbudowanych właściwości" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Przeglądaj i dodawaj niestandardowe zdefiniowane właściwości" %}}

Do obsługi właściwości niestandardowych udostępnia numer API[Skoroszyt::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) która zwraca całą kolekcję niestandardowych właściwości dokumentu arkusza kalkulacyjnego. Po pierwsze, uzyskując dostęp do właściwości niestandardowych za pomocą tej metody, programiści mogą użyć odpowiednich metod, aby dodać właściwości, takie jak AddIDocumentProperty, AddLinkToContentProperty i w podobny sposób użyć UpdateLinkedPropertyValue, UpdateLinkedRange do aktualizacji wartości niestandardowej właściwości dokumentu, która łączy się odpowiednio z treścią i połączonym zakresem. Programiści mogą użyć odpowiedniej metody z[zbiór niestandardowych właściwości dokumentu](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Kod umożliwiający wyświetlenie właściwości niestandardowych" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kod do dodania metadanych w pliku Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
