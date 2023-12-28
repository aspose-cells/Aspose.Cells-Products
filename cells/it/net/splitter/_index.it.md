---
title: Dividi il foglio di lavoro Excel in C#
description: C# codici sorgente che spiegano come dividere i file Excel Microsoft in più file nelle applicazioni Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Suddivisione file Excel via .NET" h2="Dividi un singolo documento Excel in diversi file utilizzando il codice C# all\'interno di applicazioni basate su .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Libreria Excel](/cells/it/net/) è in grado di dividere il documento Excel in più fogli di calcolo all'interno di applicazioni basate su .NET. I formati di file supportati includono XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dividi il documento Excel in più file" %}}
Il modo più semplice per dividere i file Excel in base al foglio è accedere a tutti i fogli tramite[Fogli di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Scorrendo ogni foglio e chiamando il file[copia](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metodo. Infine salvandolo in un percorso specificato.

 + Carica il file Excel con il percorso completo utilizzando[Classe cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Itera attraverso ogni foglio
+ Crea un nuovo oggetto di classe Workbook
 + Copia il foglio tramite[Metodo di copia](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Chiama il metodo Save() e passa il nome del file (percorso completo) con SaveFormat rilevante.

{{% blocks/products/pf/feature-page-code h3="C# Codice per dividere file Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dividi il foglio di lavoro Excel in riquadri" %}}

 Per dividere la finestra del foglio di lavoro in riquadri, fornisce API[Metodo diviso](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) della classe del foglio di lavoro, che fornisce la visualizzazione divisa del foglio di lavoro. Per rimuovere la visualizzazione divisa fornisce API[Metodo RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Infine salvalo in un percorso specificato.

{{% blocks/products/pf/feature-page-code h3="C# Codice per dividere la finestra del foglio di lavoro Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Codice per rimuovere la vista panoramica divisa" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
