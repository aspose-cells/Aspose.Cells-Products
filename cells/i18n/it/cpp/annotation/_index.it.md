---
title: Annotazioni file Excel tramite C++
url: /it/cpp/annotation/
description: Aggiungi o rimuovi commenti di annotazione dati di fogli di lavoro Excel e OpenOffice con la libreria C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gestisci le annotazioni dei file Microsoft<sup>&reg;</sup> Excel tramite C++" h2="Aggiungi o rimuovi semplici note per annotazioni o commenti all\'interno di applicazioni basate su C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) fornisce supporto per gestire le annotazioni a livello di cella aggiungendo, accedendo e rimuovendo commenti. API fornisce [Commento](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) e [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) così come [GetIComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) per la gestione dei commenti in tutti gli aspetti. I formati Excel supportati includono ODS, XLS, XLSX, XLSB e XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotazioni sui dati dei file Excel" %}}
Manipolazione dei commenti nei fogli di lavoro - Non è limitato al numero di commenti che un foglio ha in MS Excel. Si può inserire quanto necessario per l'applicazione. Il processo di inserimento dei commenti è creare [Cartella di lavoro](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class per caricare un file esistente e selezionare il foglio di lavoro in cui si desidera aggiungere il commento. Ottieni tutti i suoi commenti usando getComments(). Aggiungi il commento usando [Aggiungere](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(ptr_intrusivo < Aspose::Cells::Systems::String > cellName). Ottieni l'indice della cella e usa [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) per l'inserimento di commenti. Inoltre, API è in grado di rimuovere tutti i commenti. Pochi dei metodi lo sono [Cancella commenti()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) a Cancella tutti i commenti nel foglio di calcolo del designer. Inoltre, [RimuoviA](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(ptr_intrusivo< Aspose::Cells::Systems::String > name) per rimuovere l'elemento in corrispondenza di un indice specificato o con il nome specificato.

{{% blocks/products/pf/feature-page-code h3="C++ Codice per aggiungere commenti all\'interno del file Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}