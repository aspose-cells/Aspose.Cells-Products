---
title: Dodaj lub usuń adnotacje do pliku Excel pod numerem C++
description: Dodaj lub usuń komentarze do adnotacji danych w arkuszach kalkulacyjnych Excel i OpenOffice z biblioteką C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj adnotacjami plików Excel Microsoft<sup>&reg;</sup> pod numerem C++" h2="Dodawaj lub usuwaj proste notatki do adnotacji lub komentarzy w aplikacjach opartych na C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/pl/cpp/) zapewnia obsługę zarządzania adnotacjami na poziomie komórki poprzez dodawanie, uzyskiwanie dostępu i usuwanie komentarzy. API zapewnia[Komentarz](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) I[Kolekcja komentarzy](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) jak również[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)za rozpatrywanie komentarzy we wszystkich aspektach. Obsługiwane formaty Excela to ODS, XLS, XLSX, XLSB i XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Adnotacje danych w plikach Excel" %}}
 Manipulowanie komentarzami w arkuszach — liczba komentarzy w arkuszu w programie MS Excel nie jest ograniczona. Można wstawić tyle, ile potrzeba aplikacji. Proces wstawiania komentarzy polega na utworzeniu[zeszyt ćwiczeń](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class, aby załadować istniejący plik i wybrać arkusz, do którego chcesz dodać komentarz. Pobierz wszystkie komentarze za pomocą getComments(). Dodaj komentarz za pomocą[Add(const char16_t* nazwa_komórki)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) metoda. Zdobądź indeks komórki i użyj[Ustaw notatkę](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) do wstawiania komentarzy. Co więcej, numer API może usunąć wszystkie komentarze. Niewiele jest takich metod[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) do Usuwa wszystkie komentarze w arkuszu kalkulacyjnym projektanta. Ponadto,***Usuń o*** metoda usuwająca element o określonym indeksie lub o określonej nazwie.

{{% blocks/products/pf/feature-page-code h3="C++ Kod umożliwiający dodawanie komentarzy w pliku Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
