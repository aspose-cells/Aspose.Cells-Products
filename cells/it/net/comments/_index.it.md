---
title: Inserisci commenti in Excel via .NET
description:  C# codici sorgente che spiegano come inserire commenti nei file Excel Microsoft utilizzando la libreria .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Inserimento commenti Excel via .NET" h2="Crea documenti Excel e inserisci commenti utilizzando le API lato server nelle applicazioni basate su .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Puoi aggiungere commenti alle celle. Quando una cella contiene un commento, viene visualizzato un indicatore nell'angolo della cella. I commenti vengono visualizzati quando si posiziona il cursore su una cella. Questi commenti possono essere utilizzati per discussioni, istruzioni speciali o markup del contenuto del documento.[.NET Libreria Excel](/cells/it/net/)supporta l'inserimento di commenti nei file Excel. Per questo, il API fornisce a[Commento](https://reference.aspose.com/cells/net/aspose.cells/comment) classe per i commenti elemento costitutivo.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inserisci commenti nel file Excel" %}}

 Inserire commenti utilizzando Excel API è semplice. Il processo è, Crea[Classe di cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook) oggetto e selezionare il primo foglio di lavoro o il relativo foglio fornendone l'indice. Inserisci i dati delle celle richieste utilizzando[Metodo PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Aggiungi commento al foglio di lavoro utilizzando[Raccolta commenti](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[Aggiungi metodo](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Codice per inserire commento in Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
