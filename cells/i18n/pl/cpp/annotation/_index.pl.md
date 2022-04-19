---
title: Adnotacje do pliku Excel za pośrednictwem C++
url: /pl/cpp/annotation/
description: Dodaj lub usuń komentarze adnotacji danych w arkuszach kalkulacyjnych Excel i OpenOffice za pomocą biblioteki C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj adnotacjami do plików Microsoft<sup>&reg;</sup> Excel za pomocą C++" h2="Dodaj lub usuń proste notatki do adnotacji lub komentarzy w aplikacjach opartych na C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) zapewnia wsparcie w zarządzaniu adnotacjami na poziomie komórki poprzez dodawanie, dostęp i usuwanie komentarzy. API zapewnia [IKomentarz](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) oraz [IComment Collection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) jak również [Pobierz IKomentarze()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) do obsługi komentarzy we wszystkich aspektach. Obsługiwane formaty Excela obejmują ODS, XLS, XLSX, XLSB i XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Adnotacje do danych w plikach Excel" %}}
Manipulowanie komentarzami w arkuszach — nie jest ograniczone, ile komentarzy ma arkusz w MS Excel. Można wstawić tyle, ile potrzeba do aplikacji. Proces wstawiania komentarzy to tworzenie [IZeszyt ćwiczeń](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) obiekt klasy, aby załadować istniejący plik i wybierz arkusz, do którego chcesz dodać komentarz. Pobierz wszystkie jego komentarze za pomocą metody getComments(). Dodaj komentarz za pomocą [Dodać](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName). Pobierz indeks komórek i użyj [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) do wstawiania komentarzy. Ponadto API może usuwać wszystkie komentarze. Niewiele metod jest [WyczyśćKomentarze()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) do Czyści wszystkie komentarze w arkuszu kalkulacyjnym projektanta. Ponadto, [UsuńO](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) metoda usuwania elementu o określonym indeksie lub o określonej nazwie.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do dodawania komentarzy w pliku Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}