---
title: Wstaw komentarze w programie Excel via .NET
description:  Kody źródłowe C# pokazujące, jak wstawić komentarz do plików Excel Microsoft przy użyciu biblioteki .NET.
keywords: [C# Aspose.Cells., add excel comments., insert excel comments., access excel comments., remove excel comments., delete excel comments., add comments in excel., insert comments in excel., access comments in excel., remove comments in excel., delete comments in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Wstawianie komentarzy w programie Excel via .NET" h2="Twórz dokumenty Excel i wstawiaj komentarze za pomocą interfejsów API po stronie serwera w aplikacjach opartych na .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Możesz dodawać komentarze do komórek. Gdy komórka zawiera komentarz, w rogu komórki pojawia się wskaźnik. Komentarze pojawiają się po najechaniu kursorem na komórkę.Komentarze te można wykorzystać do dyskusji, specjalnych instrukcji lub oznaczania treści dokumentu.[.NET Biblioteka Excela](/cells/pl/net/)obsługuje wstawianie komentarzy w plikach Excel. W tym celu API zapewnia[Komentarz](https://reference.aspose.com/cells/net/aspose.cells/comment) klasa bloku konstrukcyjnego komentarzy.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Wstaw komentarze do pliku Excel" %}}

 Wstawianie komentarzy za pomocą programu Excel API jest proste. Proces polega na tworzeniu[Zajęcia ze skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook)obiekt i wybierz pierwszy arkusz lub odpowiedni arkusz, podając jego indeks. Wstaw wymagane dane komórek za pomocą[Metoda PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Dodaj komentarz do arkusza za pomocą[Kolekcja komentarzy](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[Dodaj metodę](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kod do wstawienia komentarza w programie Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
