---
title: Crea grafici Excel e converti in immagini tramite C++
url: /it/cpp/chart/
description: C++ codice sorgente per disegnare e convertire grafici o diagrammi in Microsoft Excel utilizzando C++ Libreria
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea grafici Microsoft<sup>&reg;</sup> Excel e converti in immagini tramite C++" h2="Converti i grafici dei documenti Excel in immagini e crea grafici inclusi grafici a torta, a piramide, a linee e a bolle all\'interno di applicazioni basate su C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Utilizzando i grafici Excel, è possibile ottenere un quadro più ampio e analizzare facilmente i dati per prendere le decisioni giuste. [C++ Libreria di Excel](/cells/cpp/) supporta la creazione di diversi grafici elencati da [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) inclusi grafici ad area, a barre, a torta, piramidali, a linee e a bolle. Inoltre, per la conversione di grafici in immagini, API fornisce a [ToImage metodo](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) nel formato immagine richiesto.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Crea grafici Excel" %}}

Il processo di creazione di un grafico Excel consiste nel creare un'istanza di [Classe di Cartella di lavoro](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e selezionare quello desiderato [Foglio di lavoro](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Aggiungi il grafico usando [Aggiungi metodo](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) con parametri rilevanti incluso il tipo di grafico. Accedi al grafico tramite indice e [Aggiungere](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) l'origine dati per il grafico.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per creare grafici Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Converti grafici in immagini" %}}


Per la conversione dei grafici, il processo è, prima di tutto creare un grafico del tipo pertinente utilizzando il codice sopra o accedervi dal foglio pertinente. Definire il percorso di salvataggio dell'output per l'immagine e utilizzare il metodo ToImage per la conversione.

 
{{% blocks/products/pf/feature-page-code h3="C++ Codice per convertire i grafici Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}