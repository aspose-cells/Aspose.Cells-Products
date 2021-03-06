---
title: Dividi il foglio di lavoro di Excel in base a C#
url: /it/net/splitter/
description: C# codici sorgente che spiegano come dividere i file di Microsoft Excel in più file nelle applicazioni Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Divisione file Microsoft<sup>&reg;</sup> Excel tramite .NET" h2="Dividi un singolo documento Excel in diversi file utilizzando il codice C# all\'interno di applicazioni basate su .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Libreria di Excel](/cells/net/) è in grado di dividere il documento Excel in più fogli di lavoro all'interno di applicazioni basate su .NET. I formati di file supportati includono XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividi il documento Excel in più file" %}}
Il modo più semplice per dividere i fogli di file Excel in base al foglio è Accedere a tutti i fogli tramite [Fogli di lavoro](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterando ogni foglio e chiamando il [copia](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metodo. Infine salvandolo in un percorso specificato. 

+ Carica il file Excel con il percorso completo utilizzando [Classe cartella di lavoro](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterare attraverso ogni foglio
+ Crea un nuovo oggetto classe Cartella di lavoro
+ Copia il foglio tramite [Metodo di copia](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Chiama il metodo Save() e passa il nome del file (percorso completo) con il relativo SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Codice per dividere i file Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividi il foglio di lavoro di Excel in riquadri" %}}

Per dividere la finestra del foglio di lavoro in riquadri, API fornisce [Metodo diviso](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) della classe del foglio di lavoro, che fornisce la vista suddivisa del foglio di lavoro. Per rimuovere la vista divisa API fornisce [Metodo RemoveSplit](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Infine salvalo in un percorso specificato. 

{{% blocks/products/pf/feature-page-code h3="C# Codice per dividere la finestra del foglio di lavoro di Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Codice per rimuovere la vista panoramica divisa" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
