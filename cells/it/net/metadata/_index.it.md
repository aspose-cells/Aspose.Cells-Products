---
title: Gestisci metadati file Excel via .NET C#
description: Visualizza, aggiungi, modifica, rimuovi o estrai i metadati dei file Excel con solo poche righe di codice C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci Microsoft<sup>&reg;</sup> Metadati file Excel via .NET" h2="Visualizza, aggiungi, aggiorna, rimuovi o estrai le proprietà dei file Excel integrate e personalizzate utilizzando le API .NET lato server." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/it/net/) supporta la gestione di proprietà definite dal sistema (incorporate) come titolo, nome dell'autore, statistiche del documento, ecc., nonché proprietà definite dall'utente (personalizzate) sotto forma di coppia nome-valore. C'è[Classe cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook) per caricare i file e[Raccolta di fogli di lavoro](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) si occupa anche della raccolta di fogli di lavoro[Classe di fogli di lavoro](https://reference.aspose.com/cells/net/aspose.cells/worksheet) per rappresentare un singolo foglio di lavoro. Insieme a queste classi, BuiltInDocumentProperties, CustomDocumentProperties semplifica il processo di gestione dei metadati.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestione delle proprietà integrate" %}}

 Per la gestione delle proprietà definite dal sistema, fornisce API[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) i programmatori possono accedere facilmente a una proprietà incorporata e aggiornarne il valore. A seconda dei requisiti dell'applicazione, gli sviluppatori possono utilizzare l'indice o il nome della proprietà dal file[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Codice per gestire le proprietà integrate" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gestione delle proprietà definite personalizzate" %}}

 Per la gestione delle proprietà definite dall'utente mette a disposizione API[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) e gli sviluppatori possono accedere facilmente alle proprietà già aggiunte e aggiungere nuove proprietà. Per aggiungere proprietà personalizzate,[Aggiungi metodo](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) Di[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) aggiunge la proprietà e restituisce un riferimento per la nuova proprietà come file[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) oggetto. La classe DocumentProperty viene utilizzata per recuperare il nome, il valore e il tipo della proprietà del documento come[DocumentProperty.Nome](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) che restituisce uno dei[Tipo di proprietà](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) valori di enumerazione.
 
{{% blocks/products/pf/feature-page-code h3="C# Codice per aggiungere metadati nel file Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Codice per rimuovere la proprietà personalizzata nel file Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
