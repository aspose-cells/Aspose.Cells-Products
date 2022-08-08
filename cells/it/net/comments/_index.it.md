---
title: Inserisci commenti in Excel tramite .NET
url: /it/net/comment/
description: C# codici sorgente su come inserire commenti nei file di Microsoft Excel utilizzando .NET Libreria. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Inserimento commenti Microsoft<sup>&reg;</sup> Excel tramite .NET" h2="Crea documenti Excel e inserisci commenti utilizzando le API lato server in applicazioni basate su .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

Puoi aggiungere commenti alle celle. Quando una cella ha un commento, viene visualizzato un indicatore nell'angolo della cella. I commenti vengono visualizzati quando si posiziona il cursore su una cella. Questi commenti possono essere utilizzati per discussioni, istruzioni speciali o markup del contenuto del documento. [.NET Libreria di Excel](/cells/net/) supporta l'inserimento di commenti nei file Excel. Per questo, API fornisce a [Commento](https://reference.aspose.com/cells/net/aspose.cells/comment) classe per il blocco di costruzione dei commenti.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inserisci i commenti nel file Excel" %}}

L'inserimento di commenti utilizzando Excel API è semplice. Il processo è Crea [Classe cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook) oggetto e selezionare il primo foglio di lavoro o il foglio pertinente fornendo il relativo indice. Inserisci i dati delle celle richieste utilizzando [Metodo PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Aggiungi un commento al foglio di lavoro utilizzando [CommentCollection](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'S [Aggiungi metodo](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Codice per inserire commenti in Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
