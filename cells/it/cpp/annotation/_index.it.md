---
title: Aggiungi o rimuovi annotazioni di file Excel tramite C++
description: Aggiungi o rimuovi commenti di annotazione dati di fogli di calcolo Excel e OpenOffice con la libreria C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci annotazioni file Excel Microsoft<sup>&reg;</sup> tramite C++" h2="Aggiungi o rimuovi semplici note per annotazioni o commenti all\'interno delle applicazioni basate su C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/it/cpp/) fornisce supporto per gestire le annotazioni a livello di cella aggiungendo, accedendo e rimuovendo commenti. API fornisce[Commento](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) E[Raccolta commenti](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) così come[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)per gestire i commenti in tutti gli aspetti. I formati Excel supportati includono ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotazioni dei dati dei file Excel" %}}
 Manipolazione dei commenti nei fogli di lavoro: non è limitato al numero di commenti presenti in un foglio in MS Excel. È possibile inserire quanto necessario all'applicazione. Il processo di inserimento dei commenti è creare[Cartella di lavoro](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) oggetto class per caricare un file esistente e selezionare il foglio di lavoro in cui si desidera aggiungere il commento. Ottieni tutti i suoi commenti usando getComments(). Aggiungi il commento utilizzando[Aggiungi(const char16_t*nomecella)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) metodo. Ottieni l'indice della cella e usalo[Imposta nota](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) per inserire commenti. Inoltre, API è in grado di rimuovere tutti i commenti. Pochi metodi lo sono[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) a Cancella tutti i commenti nel foglio di calcolo del designer. Inoltre,***RimuoviAt*** metodo per rimuovere l'elemento in corrispondenza di un indice specificato o con un nome specificato.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiungere commenti all\'interno del file Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
