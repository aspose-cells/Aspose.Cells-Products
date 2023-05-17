---
title: Adnotacje do pliku programu Excel NET C#
description: Dodaj lub usuń adnotacje danych z arkuszy kalkulacyjnych Excel i OpenOffice za pomocą zaledwie kilku wierszy kodu C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Usuń Microsoft<sup>&reg;</sup> adnotacje do pliku programu Excel via .NET" h2="Dodawaj lub usuwaj adnotacje do plików programu Excel za pomocą kodu C# w aplikacjach opartych na .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteka programu Excel](/cells/pl/net/) zapewnia obsługę zarządzania adnotacjami na poziomie komórki poprzez dodawanie, uzyskiwanie dostępu i usuwanie komentarzy. Korzystając z komentarzy na poziomie komórki, można przechowywać istotne informacje dla użytkowników końcowych. Obsługiwane formaty plików to ODS, XLS, XLSX, XLSB i XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Adnotacje danych w plikach Excel" %}}
 Zarządzanie komentarzami w arkuszach — nie ma żadnego limitu liczby komentarzy w arkuszu w programie MS Excel. Można dodać tyle, ile wymaga aplikacja. Będziemy korzystać z[Klasa komentarza](https://reference.aspose.com/cells/net/aspose.cells/comment)dla całej tej funkcjonalności.

+ Załaduj plik Excela za pomocą obiektu klasy Workbook
+ Uzyskaj dostęp do odpowiedniego arkusza roboczego i jego odpowiedniego indeksu Cell
+ Zadzwoń do RemoveAt z identyfikatorem Cell, aby go usunąć
 + Użyj[Uwaga właściwość](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) za dodawanie treści komentarzy
+ Zapisz skoroszyt przed i po wywołaniu metody RemoveAt w celu porównania

{{% blocks/products/pf/feature-page-code h3="C# Kod umożliwiający dostęp, wstawianie i usuwanie plików Excel Cell Komentarze" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
