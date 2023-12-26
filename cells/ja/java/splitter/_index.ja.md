---
title: Java で Excel スプレッドシートをワークシートに分割
description: Java Excel ライブラリを使用して Microsoft Excel ファイルを複数のドキュメントに分割する方法を説明する Java ソース コード
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルの分割 via Java" h2="Excel スプレッドシートを Java ベースのアプリケーション内のワークシートに分割する" >}}
{{% blocks/products/pf/feature-page-summary %}}
生徒ごとに 1 つのシートを割り当て、生徒データを含むスプレッドシートなどの Excel ファイルを分割する必要がある場合、さまざまなシナリオがあります。また、各シートを生徒ごとに別のファイルとして分割する必要があります。 via Java アプリケーションを自動化するには、[Java エクセル API](/cells/ja/java/) Excelドキュメントをシートごとに分割するためにあります。サポートされている形式は、XLS、XLSX、XLSB、XLSM、ODS です。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel ドキュメントを複数のファイルに分割する" %}}

Excel ファイルをシートに分割する最も簡単な方法は、すべてのシートにアクセスし、各シートを繰り返し処理し、目的の形式で 1 つずつ保存することです。ワークシートをロードするには、API が提供します。[ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラス。[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count)メソッドはシートの総数を取得します。各シートを繰り返し処理して使用します[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)特定のシートにアクセスするため。選択したシート データを、新しく作成した Workbook クラス オブジェクトに移動します。[コピー方法](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)）。最後に必要な形式で保存します。

{{% blocks/products/pf/feature-page-code h3="Java Excel ファイルを分割するコード" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel ワークシートをペインに分割する" %}}

API は、Excel ワークシートを異なるペインに分割する機能も提供します。処理は、Workbookクラスを使用してファイルをロードします。最初のワークシートまたはインデックスを指定して必要なシートを選択します。関連するセル インデックスをパラメータとして持つ setActiveCell を呼び出します。最後に、split() メソッドを呼び出して、ワークシート ウィンドウを異なるペインに分割します。

{{% blocks/products/pf/feature-page-code h3="Java Excel シートをペイン ビューに分割するコード" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
