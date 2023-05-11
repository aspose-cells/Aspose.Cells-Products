---
title: Adnotacje do plików programu Excel pod numerem C++
description: Dodawaj lub usuwaj komentarze adnotacji danych z arkuszy kalkulacyjnych Excel i OpenOffice za pomocą biblioteki C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj adnotacjami do plików programu Excel Microsoft<sup>&reg;</sup> za pośrednictwem numeru C++" h2="Dodawaj lub usuwaj proste notatki do adnotacji lub komentarzy w aplikacjach opartych na numerze C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/pl/cpp/) zapewnia obsługę zarządzania adnotacjami na poziomie komórki poprzez dodawanie, uzyskiwanie dostępu i usuwanie komentarzy. API zapewnia[IKomentarz](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) I[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) jak również[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)za obsługę komentarzy we wszystkich aspektach. Obsługiwane formaty programu Excel to ODS, XLS, XLSX, XLSB i XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Adnotacje danych w plikach Excel" %}}
 Manipulowanie komentarzami w arkuszach kalkulacyjnych — Nie ma ograniczeń co do liczby komentarzy w arkuszu w programie MS Excel. Można włożyć tyle, ile potrzeba aplikacji. Proces wstawiania komentarzy to tworzenie[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class obiekt, aby załadować istniejący plik i wybierz arkusz, w którym chcesz dodać komentarz. Pobierz wszystkie jego komentarze za pomocą funkcji getComments(). Dodaj komentarz za pomocą[Dodać](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (natrętny_ptr< Aspose::Cells::Systems::String > nazwa_komórki) metoda. Pobierz indeks komórki i użyj[ustaw Uwaga](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) do wstawiania komentarzy. Ponadto API jest w stanie usunąć wszystkie komentarze. Niewiele jest metod[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) do Czyści wszystkie komentarze w arkuszu kalkulacyjnym projektanta. Ponadto,[Usuń o godz](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(natrętny_ptr< Aspose::Cells::Systems::String > name) w celu usunięcia elementu o określonym indeksie lub o określonej nazwie.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do dodawania komentarzy w pliku Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
