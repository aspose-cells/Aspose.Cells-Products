---
title: Gestisci i metadati dei file Excel con Go tramite C++
description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel utilizzando Go tramite la libreria C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci i metadati del documento Excel Microsoft<sup>&reg;</sup> tramite Go tramite C++" h2="Visualizza, inserisci, aggiorna, rimuovi o estrai proprietà personalizzate e integrate dei documenti Excel all\'interno delle applicazioni C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadati in Excel: come visualizzare, inserire e rimuovere i metadati dei file Excel.[Vai alla libreria Excel C++](/cells/it/go-cpp/)Facilita in modo semplice supportando le proprietà integrate/definite dal sistema, come nome dell'autore, titolo, statistiche del documento, ecc., necessarie a volte per verificare quando un file è stato modificato o salvato, insieme a proprietà personalizzate/definite dall'utente sotto forma di coppie nome/valore. Per automatizzare il processo, la libreria supporta la creazione e la gestione di file Excel di metadati di grandi dimensioni.[Cartella di lavoro](https://reference.aspose.com/cells/go-cpp/workbook/) La classe apre una cartella di lavoro in base al percorso, al flusso e allo speciale FileFormatType. Quindi, carica il file con il metodo appropriato per un'ulteriore elaborazione. Alcune delle possibilità elencate di seguito consentono agli sviluppatori di migliorare facilmente il proprio codice in base ai requisiti dell'applicazione.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leggi e aggiorna le proprietà integrate" %}}

 Per automatizzare le proprietà integrate, API fornisce[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Metodo che restituisce una raccolta DocumentProperties che rappresenta tutte le proprietà predefinite del documento nel foglio di calcolo. Dopo aver effettuato l'accesso a tutte le proprietà predefinite, accedere alle proprietà rilevanti utilizzando metodi appropriati come GetTitle(), GetSubject() ecc. Per aggiornare le proprietà, API fornisce metodi come SetTitle, SetSubject, SetAuthor, SetComments ecc. Visualizza[raccolta di proprietà di documenti incorporata](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) per la funzione richiesta.

{{% blocks/products/pf/feature-page-code h3="Passare al codice C++ per leggere le proprietà definite dal sistema" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Passare al codice C++ per aggiornare le proprietà integrate" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizza e aggiungi proprietà definite personalizzate" %}}

 Per la gestione delle proprietà personalizzate, API fornisce[Cartella di lavoro::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)che restituisce l'intera raccolta di proprietà personalizzate del documento del foglio di calcolo. Accedendo innanzitutto alle proprietà personalizzate tramite questo metodo, gli sviluppatori possono utilizzare metodi pertinenti per aggiungere proprietà come AddIDocumentProperty, AddLinkToContentProperty e, in modo simile, utilizzare UpdateLinkedPropertyValue e UpdateLinkedRange per aggiornare il valore della proprietà personalizzata del documento che collega rispettivamente al contenuto e all'intervallo collegato. Gli sviluppatori possono utilizzare metodi pertinenti da[raccolta di proprietà di documenti personalizzati](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Vai tramite il codice C++ per visualizzare le proprietà personalizzate" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Passare al codice C++ per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}