---
title: Annotazioni file Excel tramite Java
url: /it/java/annotation/
description: Aggiungi o rimuovi l'annotazione dei dati dei fogli di lavoro di Excel e OpenOffice con la libreria Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci le annotazioni dei file Microsoft<sup>&reg;</sup> Excel tramite Java" h2="Inserisci semplici note per l\'annotazione o elimina i commenti a livello di cella del foglio di lavoro Excel all\'interno di applicazioni basate su Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) fornisce supporto per gestire le annotazioni a livello di cella aggiungendo, accedendo ed eliminando commenti. API fornisce [Commento](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [CommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Commento filettato](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) e [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) per la gestione dei commenti in tutti gli aspetti.
I formati di file supportati includono ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotazioni sui dati dei file Excel" %}}
Gestione dei commenti nei fogli di lavoro - Non c'è alcun limite al numero di commenti che un foglio ha in MS Excel. Si può aggiungere quanto richiesto dall'applicazione. Il processo di aggiunta di commenti è creare [Cartella di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) oggetto classe o caricare un file esistente utilizzando la classe Cartella di lavoro. Accedi a tutti i suoi commenti usando getComments(). Ottieni l'indice della cella e usa [setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) per l'inserimento di commenti. Inoltre, API è in grado di rimuovere tutti i commenti. 

{{% blocks/products/pf/feature-page-code h3="Java Codice per aggiungere commenti all\'interno del file Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Codice per rimuovere i commenti all\'interno del file Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}