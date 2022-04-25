---
title: Gestisci i metadati dei file Excel tramite .NET C#
url: /it/net/metadata/
description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel con poche righe di codice C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci i metadati dei file Microsoft<sup>&reg;</sup> Excel tramite .NET" h2="Visualizza, aggiungi, aggiorna, rimuovi o estrai le proprietà dei file Excel integrate e personalizzate utilizzando le API .NET lato server." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) supporta la gestione di proprietà definite dal sistema (integrate) come titolo, nome dell'autore, statistiche del documento ecc., nonché proprietà definite dall'utente (personalizzate) sotto forma di coppia nome-valore. C'è [Classe cartella di lavoro](https://apireference.aspose.com/cells/net/aspose.cells/workbook) per caricare i file e [Raccolta di fogli di lavoro](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) si occupa della raccolta di fogli di lavoro e [Classe di fogli di lavoro](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) per rappresentare un singolo foglio di lavoro. Insieme a queste classi, BuiltInDocumentProperties, CustomDocumentProperties semplifica il processo per la gestione dei metadati. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestione delle proprietà integrate" %}}

Per la gestione delle proprietà definite dal sistema, API fornisce [BuiltInDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)e i programmatori possono accedere facilmente a una proprietà incorporata e aggiornarne il valore. A seconda dei requisiti dell'applicazione, gli sviluppatori possono utilizzare l'indice o il nome della proprietà da [DocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Codice per la gestione delle proprietà integrate" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gestione delle proprietà personalizzate" %}}

Per la gestione delle proprietà definite dall'utente, API fornisce [CustomDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)e gli sviluppatori possono accedere facilmente alle proprietà già aggiunte e aggiungere nuove proprietà. Per aggiungere proprietà personalizzate, [Aggiungi metodo](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) di [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) la classe aggiunge la proprietà e restituisce un riferimento per la nuova proprietà come an [Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) oggetto. La classe DocumentProperty viene utilizzata per recuperare il nome, il valore e il tipo della proprietà del documento come [DocumentProperty.Name](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [Tipo.Proprietà Documento](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) che restituisce uno dei [Tipo di proprietà](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) valori di enumerazione. 
 
{{% blocks/products/pf/feature-page-code h3="C# Codice per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Codice per rimuovere la proprietà personalizzata nel file Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
