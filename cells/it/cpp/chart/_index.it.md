---
title: Crea grafici Excel e converti in immagini tramite C++
description: Codice sorgente C++ per disegnare e convertire un grafico o un diagramma in Excel Microsoft utilizzando la Libreria C++
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea grafici Excel Microsoft<sup>&reg;</sup> e convertili in immagini tramite C++" h2="Converti grafici di documenti Excel in immagini e crea grafici tra cui grafici a torta, a piramide, a linee e a bolle all\'interno di applicazioni basate su C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Utilizzando i grafici Excel, è possibile ottenere un quadro più ampio e analizzare facilmente i dati per prendere le giuste decisioni.[C++ Libreria Excel](/cells/it/cpp/) supporta la creazione di diversi grafici elencati per[enum Aspose::Cells::Grafici::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) inclusi grafici ad area, a barre, a torta, a piramide, a linee e a bolle. Inoltre, per la conversione dei grafici in immagini, lo API mette a disposizione un[Immaginare](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) mehtod nel formato immagine richiesto.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Crea grafici Excel" %}}

 Il processo di creazione del grafico Excel consiste nel creare un'istanza del file[Classe cartella di lavoro](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) e selezionare quello desiderato[Foglio di lavoro](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Aggiungi il grafico utilizzando[Aggiungi metodo](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)con parametri rilevanti incluso il tipo di grafico. Accedi al grafico tramite indice e[Aggiungere](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) l'origine dati per il grafico.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per Creare Grafici Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Converti grafici in immagini" %}}


Per convertire i grafici, il processo consiste nel creare innanzitutto un grafico del tipo pertinente utilizzando il codice riportato sopra o accedervi dal foglio pertinente. Definire il percorso di salvataggio dell'output per l'immagine e utilizzare il metodo ToImage per la conversione.

 
{{% blocks/products/pf/feature-page-code h3="C++ Codice per Convertire Grafici Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
