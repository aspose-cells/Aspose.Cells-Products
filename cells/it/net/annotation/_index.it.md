---
title: Annotazioni file Excel NET C#
description: Aggiungi o rimuovi l'annotazione dei dati dei fogli di calcolo Excel e OpenOffice con poche righe di codice C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rimuovi Microsoft<sup>&reg;</sup> Annotazioni file Excel via .NET" h2="Aggiungi o elimina annotazioni di file Excel utilizzando il codice C# all\'interno di applicazioni basate su .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Libreria Excel](/cells/it/net/) fornisce supporto per gestire le annotazioni a livello di cella aggiungendo, accedendo e rimuovendo commenti. Utilizzando i commenti a livello di cella, è possibile archiviare informazioni rilevanti per gli utenti finali. I formati di file supportati includono ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotazioni dei dati dei file Excel" %}}
 Gestione dei commenti nei fogli di lavoro - Non c'è alcun limite al numero di commenti che un foglio ha in MS Excel. Si può aggiungere tanto quanto il requisito dell'applicazione. Useremo il[Classe di commento](https://reference.aspose.com/cells/net/aspose.cells/comment)per tutte queste funzionalità.

+ Carica il file Excel utilizzando l'oggetto della classe Workbook
+ Accedi al foglio di lavoro pertinente e al relativo indice Cell
+ Chiama RemoveAt con l'ID Cell per rimuoverlo
 + Usa[Nota proprietà](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) per aggiungere contenuti di commenti
+ Salva la cartella di lavoro prima e dopo aver chiamato il metodo RemoveAt per confrontare

{{% blocks/products/pf/feature-page-code h3="C# Codice per accedere, inserire ed eliminare file Excel Cell Commenti" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
