---
title: Gestisci i metadati dei file Excel tramite Java
url: /it/java/metadata/
description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel con poche righe di codice Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci i metadati dei file Microsoft<sup>&reg;</sup> Excel tramite Java" h2="Visualizza, aggiungi, aggiorna, elimina o estrai le proprietà dei file Excel personalizzate e integrate utilizzando le API Java lato server." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) supporta la gestione di proprietà integrate (definite dal sistema) come titolo, nome dell'autore, statistiche del documento ecc., nonché proprietà personalizzate (definite dall'utente) sotto forma di coppia nome/valore. C'è [Classe cartella di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) per caricare i file e [Raccolta di fogli di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) si occupa della raccolta di fogli di lavoro e [Classe di fogli di lavoro](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) per rappresentare un singolo foglio di lavoro. Per l'accesso alle proprietà integrate e personalizzate, BuiltInDocumentProperties, CustomDocumentProperties semplifica il processo di gestione dei metadati. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestione delle proprietà definite dal sistema" %}}

Per la gestione delle proprietà integrate, API fornisce [BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)e i programmatori possono accedere facilmente a una proprietà incorporata e aggiornarne il valore. A seconda dei requisiti dell'applicazione, gli sviluppatori possono utilizzare l'indice o il nome della proprietà da [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Codice per la gestione delle proprietà definite dal sistema" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Aggiungi e rimuovi metadati personalizzati" %}}

Per la gestione delle proprietà personalizzate, API fornisce [CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)e gli sviluppatori possono accedere facilmente alle proprietà esistenti e aggiungere nuove proprietà utilizzando [aggiungi metodo](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) di [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) la classe aggiunge la proprietà e restituisce un riferimento per la nuova proprietà come an [Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) oggetto. La classe DocumentProperty viene utilizzata per recuperare il nome, il valore e il tipo della proprietà del documento come [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [Tipo.Proprietà Documento](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) che restituisce uno dei [Tipo di proprietà](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) valori di enumerazione. 
 
{{% blocks/products/pf/feature-page-code h3="Java Codice per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Codice per eliminare la proprietà personalizzata nel file Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
