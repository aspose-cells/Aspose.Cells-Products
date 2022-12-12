---
title: Wstawiaj komentarze w Excelu za pomocą .NET

description: C# kody źródłowe, jak wstawiać komentarz do plików programu Microsoft Excel za pomocą biblioteki .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Wstawianie komentarzy Microsoft<sup>&reg;</sup> Excel przez .NET" h2="Twórz dokumenty Excel i wstawiaj komentarze za pomocą interfejsów API po stronie serwera w aplikacjach opartych na .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

Możesz dodawać komentarze do komórek. Gdy komórka zawiera komentarz, w rogu komórki pojawia się wskaźnik. Komentarze pojawiają się po najechaniu kursorem na komórkę.Te komentarze mogą być używane do dyskusji, specjalnych instrukcji lub oznaczania treści dokumentu. [.NET Biblioteka Excela](/cells/net/) obsługuje wstawianie komentarzy w plikach Excel. W tym celu API zapewnia [Komentarz](https://reference.aspose.com/cells/net/aspose.cells/comment) klasa do tworzenia komentarzy.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Wstaw komentarze w pliku Excel" %}}

Wstawianie komentarzy za pomocą programu Excel API jest proste. Proces to tworzenie [Zajęcia ze skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook) obiekt i wybierz pierwszy arkusz lub odpowiedni arkusz, podając jego indeks. Wstaw wymagane dane komórek za pomocą [Metoda PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Dodaj komentarz do arkusza roboczego za pomocą [Kolekcja komentarzy](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Dodaj metodę](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kod do wstawiania komentarza w programie Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
