---
title: Adnotacje do pliku Excel za pośrednictwem Java
url: /pl/java/annotation/
description: Dodaj lub usuń adnotacje danych w arkuszach kalkulacyjnych Excel i OpenOffice za pomocą biblioteki Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zarządzaj adnotacjami do plików Microsoft<sup>&reg;</sup> Excel za pomocą Java" h2="Wstawiaj proste notatki do adnotacji lub usuwaj komentarze na poziomie komórek arkusza kalkulacyjnego Excel w aplikacjach opartych na Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) zapewnia wsparcie w zarządzaniu adnotacjami na poziomie komórki, dodając, otwierając i usuwając komentarze. API zapewnia [Komentarz](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [Kolekcja komentarzy](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Komentarz w wątku](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) oraz [Kolekcja komentarzy wątkowych](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) do obsługi komentarzy we wszystkich aspektach.
Obsługiwane formaty plików to ODS, XLS, XLSX, XLSB i XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Adnotacje do danych w plikach Excel" %}}
Zarządzanie komentarzami w arkuszach — nie ma żadnego limitu liczby komentarzy w arkuszu w programie MS Excel. Można dodać tyle, ile wymaga aplikacja. Proces dodawania komentarzy to tworzenie [zeszyt ćwiczeń](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) obiekt klasy lub załaduj istniejący plik przy użyciu klasy Workbook. Uzyskaj dostęp do wszystkich komentarzy za pomocą funkcji getComments(). Pobierz indeks komórek i użyj [setNote](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) do wstawiania komentarzy. Ponadto API może usuwać wszystkie komentarze. 

{{% blocks/products/pf/feature-page-code h3="Java Kod do dodawania komentarzy w pliku Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kod do usuwania komentarzy w pliku Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}