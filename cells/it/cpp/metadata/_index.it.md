---
title: Gestisci i metadati dei file Excel tramite C++
description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel utilizzando la libreria C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci i metadati del documento Excel Microsoft<sup>&reg;</sup> tramite C++" h2="Visualizza, inserisci, aggiorna, rimuovi o estrai le proprietà del documento Excel personalizzate e integrate all\'interno delle applicazioni C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadati in Excel - Come visualizzare, inserire e rimuovere i metadati dei file excel.[C++ Libreria Excel](/cells/it/cpp/) facilita è in modo semplice supportando le proprietà integrate/definite dal sistema come il nome dell'autore, il titolo, le statistiche del documento ecc. coppie nome/valore. Per automatizzare il processo, la libreria supporta la creazione e la gestione di file Excel di metadati di grandi dimensioni.[Metodo CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) Di[Classe di fabbrica](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Apri una cartella di lavoro per percorso, per flusso e per FileFormatType speciale. Quindi carica il file con un metodo appropriato per un'ulteriore elaborazione. Poche delle possibilità elencate di seguito e gli sviluppatori possono facilmente migliorare il proprio codice in base ai requisiti dell'applicazione.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leggere e aggiornare le proprietà integrate" %}}

 Per automatizzare le proprietà integrate, API fornisce[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metodo che restituisce una raccolta DocumentProperties che rappresenta tutte le proprietà del documento predefinite del foglio di calcolo. Dopo aver effettuato l'accesso a tutte le proprietà integrate, accedi alle proprietà pertinenti utilizzando il metodo pertinente come GetTitle(), GetSubject() ecc. Per aggiornare le proprietà, API fornisce metodi come SetTitle, SetSubject, SetAuthor, SetComments ecc. Visualizza il[raccolta di proprietà del documento incorporata](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) per la funzione richiesta.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per leggere le proprietà definite dal sistema" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiornare le proprietà integrate" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizza e aggiungi proprietà definite dall\'utente" %}}

Per la gestione delle proprietà personalizzate, API fornisce[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) che restituisce tutta la raccolta di proprietà del documento personalizzato del foglio di calcolo. Accedendo innanzitutto alle proprietà personalizzate tramite questo metodo, gli sviluppatori possono utilizzare metodi pertinenti per aggiungere proprietà come AddIDocumentProperty, AddLinkToContentProperty e allo stesso modo utilizzare UpdateLinkedPropertyValue, UpdateLinkedRange per aggiornare il valore della proprietà del documento personalizzato che si collega rispettivamente al contenuto e all'intervallo collegato. Gli sviluppatori possono utilizzare il metodo pertinente da[raccolta di proprietà del documento personalizzate](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Codice per visualizzare le proprietà personalizzate" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
