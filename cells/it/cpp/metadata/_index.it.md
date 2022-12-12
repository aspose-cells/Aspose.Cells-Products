---
title: Gestisci i metadati dei file Excel tramite C++

description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel utilizzando la libreria C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci i metadati dei documenti Microsoft<sup>&reg;</sup> Excel tramite C++" h2="Visualizza, inserisci, aggiorna, rimuovi o estrai proprietà di documenti Excel personalizzate e integrate all\'interno di C++ applicazioni." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadati in Excel - Come visualizzare, inserire e rimuovere i metadati dei file excel. [C++ Libreria di Excel](/cells/cpp/) faclitates è in modo semplice supportando le proprietà integrate / definite dal sistema come il nome dell'autore, il titolo, le statistiche del documento ecc. necessarie a volte come controllare quando l'ultimo file viene modificato o salvato insieme a proprietà personalizzate / definite dall'utente sotto forma di coppie nome/valore. Per automatizzare il processo, la libreria supporta la creazione e il mantenimento di file Excel di metadati di grandi dimensioni. [Metodo CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) di [Classe di fabbrica](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Aprire una cartella di lavoro in base al percorso, al flusso e allo speciale FileFormatType. Quindi carica il file con il metodo appropriato per ulteriori elaborazioni. Poche delle possibilità elencate di seguito e gli sviluppatori possono facilmente migliorare il proprio codice in base ai requisiti dell'applicazione. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Leggi e aggiorna le proprietà integrate" %}}

Per automatizzare le proprietà integrate, API fornisce [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metodo che restituisce una raccolta DocumentProperties che rappresenta tutte le proprietà del documento integrate nel foglio di calcolo. Dopo aver effettuato l'accesso a tutte le proprietà integrate, accedi alle proprietà pertinenti utilizzando il metodo pertinente come GetTitle(), GetSubject() ecc. Per aggiornare le proprietà, API fornisce un metodo come SetTitle, SetSubject, SetAuthor, SetComments ecc. Visualizza il [raccolta di proprietà dei documenti incorporata](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) per la funzione richiesta.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per leggere le proprietà definite dal sistema" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiornare le proprietà integrate" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visualizza e aggiungi proprietà definite personalizzate" %}}

Per la gestione delle proprietà personalizzate, API fornisce [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) che restituisce tutta la raccolta di proprietà del documento personalizzata del foglio di calcolo. Accedendo in primo luogo alle proprietà personalizzate tramite questo metodo, gli sviluppatori possono utilizzare metodi pertinenti per aggiungere proprietà come AddIDocumentProperty, AddLinkToContentProperty e utilizzare in modo simile UpdateLinkedPropertyValue, UpdateLinkedRange per aggiornare il valore della proprietà del documento personalizzato che si collega rispettivamente al contenuto e all'intervallo collegato. Gli sviluppatori possono utilizzare il metodo pertinente da [raccolta di proprietà del documento personalizzate](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Codice per visualizzare le proprietà personalizzate" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
