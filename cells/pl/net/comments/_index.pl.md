---
title: Wstaw komentarze w programie Excel via .NET
description:  C# kody źródłowe, które umożliwiają wstawianie komentarzy do plików Excel Microsoft przy użyciu biblioteki .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Wstawianie komentarzy programu Excel via .NET" h2="Twórz dokumenty programu Excel i wstawiaj komentarze przy użyciu interfejsów API po stronie serwera w aplikacjach opartych na numerze .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Do komórek można dodawać komentarze. Gdy komórka zawiera komentarz, w rogu komórki pojawia się wskaźnik. Komentarze pojawiają się, gdy zatrzymasz kursor nad komórką. Komentarze te mogą być używane do dyskusji, specjalnych instrukcji lub oznaczania treści dokumentu.[.NET Biblioteka programu Excel](/cells/pl/net/)obsługuje wstawianie komentarzy w plikach Excel. W tym celu API zapewnia[Komentarz](https://reference.aspose.com/cells/net/aspose.cells/comment) klasa dla bloków konstrukcyjnych komentarzy.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Wstaw komentarze w pliku Excel" %}}

 Wstawianie komentarzy za pomocą programu Excel API jest proste. Proces to tworzenie[Klasa skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook) obiekt i wybierz pierwszy arkusz lub odpowiedni arkusz, podając jego indeks. Wstaw wymagane dane komórek za pomocą[Metoda PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Dodaj komentarz do arkusza za pomocą[Kolekcja komentarzy](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[Dodaj metodę](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kod do wstawienia komentarza w programie Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
