---
title: Gestisci i metadati dei file Excel tramite C++
description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel utilizzando la libreria C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci i metadati del documento Excel Microsoft<sup>&reg;</sup> tramite C++" h2="Visualizza, inserisci, aggiorna, rimuovi o estrai proprietà di documenti Excel personalizzate e integrate all\'interno delle applicazioni C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadati in Excel: come visualizzare, inserire e rimuovere i metadati dei file Excel.[C++ Libreria Excel](/cells/it/cpp/) faclitates è semplice supportando le proprietà integrate/definite dal sistema come nome dell'autore, titolo, statistiche del documento, ecc. necessarie a volte come controllare quando l'ultimo file viene modificato o salvato insieme alle proprietà personalizzate/definite dall'utente sotto forma di coppie nome/valore. Per automatizzare il processo, la libreria supporta la creazione e la gestione di file Excel di metadati di grandi dimensioni.[Cartella di lavoro](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Apre una cartella di lavoro per percorso, per flusso e per FileFormatType speciale. Quindi carica il file con il metodo appropriato per l'ulteriore elaborazione. Sono poche le possibilità elencate di seguito e gli sviluppatori possono facilmente migliorare il proprio codice in base ai requisiti dell'applicazione.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leggere e aggiornare le proprietà integrate" %}}

 Per automatizzare le proprietà integrate, fornisce API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) metodo che restituisce una raccolta DocumentProperties che rappresenta tutte le proprietà del documento integrate nel foglio di calcolo. Dopo aver effettuato l'accesso a tutte le proprietà integrate, accedere alle proprietà pertinenti utilizzando il metodo pertinente come GetTitle(), GetSubject() ecc. Per aggiornare le proprietà, API fornisce metodi come SetTitle, SetSubject, SetAuthor, SetComments ecc. Visualizza il[raccolta di proprietà del documento incorporata](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) per la funzione richiesta.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per leggere le proprietà definite dal sistema" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiornare le proprietà integrate" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizza e aggiungi proprietà personalizzate" %}}

Per la gestione delle proprietà personalizzate, fornisce API[Cartella di lavoro::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) che restituisce tutta la raccolta di proprietà del documento personalizzato del foglio di calcolo. Accedendo innanzitutto alle proprietà personalizzate tramite questo metodo, gli sviluppatori possono utilizzare metodi pertinenti per aggiungere proprietà come AddIDocumentProperty, AddLinkToContentProperty e utilizzare in modo simile UpdateLinkedPropertyValue, UpdateLinkedRange per aggiornare il valore della proprietà del documento personalizzato che si collega rispettivamente al contenuto e all'intervallo collegato. Gli sviluppatori possono utilizzare il metodo pertinente da[raccolta di proprietà del documento personalizzate](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Codice per visualizzare le proprietà personalizzate" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
