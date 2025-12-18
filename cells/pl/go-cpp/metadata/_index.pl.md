---
title: Zarządzaj metadanymi plików Excel za pomocą Go pod numerem C++
description: Przeglądaj, dodawaj, edytuj, usuwaj lub wyodrębniaj metadane plików Excel za pomocą biblioteki Go o numerze C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj metadanymi dokumentu Excel Microsoft<sup>&reg;</sup> za pomocą programu Go i C++" h2="Przeglądaj, wstawiaj, aktualizuj, usuwaj lub wyodrębniaj niestandardowe i wbudowane właściwości dokumentów programu Excel w aplikacjach C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadane w programie Excel — jak przeglądać, wstawiać i usuwać metadane plików programu Excel.[Przejdź przez bibliotekę Excel C++](/cells/pl/go-cpp/)Ułatwia to w prosty sposób, obsługując wbudowane/zdefiniowane przez system właściwości, takie jak nazwisko autora, tytuł, statystyki dokumentu itp., potrzebne na przykład do sprawdzenia, kiedy plik został ostatnio zmodyfikowany lub zapisany, wraz z niestandardowymi/zdefiniowanymi przez użytkownika właściwościami w postaci par nazwa/wartość. Aby zautomatyzować ten proces, biblioteka obsługuje tworzenie i zarządzanie dużymi plikami metadanych w formacie Excel.[zeszyt ćwiczeń](https://reference.aspose.com/cells/go-cpp/workbook/) Klasa otwiera skoroszyt według ścieżki, strumienia i specjalnego typu formatu pliku (FileFormatType). W ten sposób plik jest ładowany odpowiednią metodą do dalszego przetwarzania. Kilka z poniższych możliwości pozwala programistom na łatwe ulepszanie kodu zgodnie z wymaganiami aplikacji.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Odczyt i aktualizacja wbudowanych właściwości" %}}

 W celu zautomatyzowania wbudowanych właściwości, API zapewnia[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Metoda zwracająca kolekcję DocumentProperties reprezentującą wszystkie wbudowane właściwości dokumentu arkusza kalkulacyjnego. Po uzyskaniu dostępu do wszystkich wbudowanych właściwości, należy uzyskać dostęp do odpowiednich właściwości za pomocą odpowiednich metod, takich jak GetTitle(), GetSubject() itp. Aby zaktualizować właściwości, API udostępnia metody takie jak SetTitle, SetSubject, SetAuthor, SetComments itp. Wyświetl[wbudowana kolekcja właściwości dokumentu](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) dla wymaganej funkcji.

{{% blocks/products/pf/feature-page-code h3="Przejdź przez kod C++, aby odczytać właściwości zdefiniowane w systemie" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Przejdź przez kod C++, aby zaktualizować wbudowane właściwości" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Wyświetl i dodaj niestandardowe zdefiniowane właściwości" %}}

 Do obsługi właściwości niestandardowych, API zapewnia[Skoroszyt::PobierzWłaściwościDokumentuNiestandardowego](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Zwraca ona wszystkie niestandardowe właściwości dokumentu z arkusza kalkulacyjnego. Uzyskując dostęp do niestandardowych właściwości za pomocą tej metody, programiści mogą użyć odpowiednich metod, aby dodać właściwości, takie jak AddIDocumentProperty, AddLinkToContentProperty, a także użyć UpdateLinkedPropertyValue i UpdateLinkedRange, aby zaktualizować wartość niestandardowej właściwości dokumentu, która łączy się odpowiednio z treścią i zakresem linków. Programiści mogą użyć odpowiedniej metody z[zbiór niestandardowych właściwości dokumentu](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Przejdź przez kod C++, aby wyświetlić właściwości niestandardowe" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Przejdź przez kod C++, aby dodać metadane do pliku Excel" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}