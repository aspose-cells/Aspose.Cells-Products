---
title: ExcelスプレッドシートをJavaのワークシートに分割
url: /ja/java/splitter/
description: JavaExcelライブラリを使用してMicrosoftExcelファイルを複数のドキュメントに分割する方法を説明するJavaソースコード
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>JavaによるExcelファイルの分割" h2="ExcelスプレッドシートをJavaベースのアプリケーション内のワークシートに分割します" >}}
{{% blocks/products/pf/feature-page-summary %}}
さまざまなシナリオがあります。生徒のデータを含むスプレッドシートのようにExcelファイルを分割し、生徒ごとに1枚のシートを割り当てる必要がある場合。そして、各シートを個別のファイルとして生徒ごとに分割する必要があります。 Javaアプリケーションを介して自動化するには、 [Java Excel API](/cells/java/) Excelドキュメントをシートごとに分割するためにあります。サポートされている形式には、XLS、XLSX、XLSB、XLSM、ODSが含まれます。 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelドキュメントを複数のファイルに分割" %}}

Excelファイルをシートに分割する最も簡単な方法は、すべてのシートにアクセスし、各シートを繰り返し処理して、目的の形式で1つずつ保存することです。ワークシートをロードするために、APIは [ワークブック](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) クラス。 [getWorksheets（）。getCount（）](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) メソッドはシートの総数を取得します。各シートを繰り返して使用します [getWorksheets（）。get（sheetindex）](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) 特定のシートにアクセスするため。を使用して、選択したシートデータを新しく作成したWorkbookクラスオブジェクトに移動します [コピー方法](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)）。最後に、必要な形式で保存します。

{{% blocks/products/pf/feature-page-code h3="JavaExcelファイルを分割するためのコード" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excelワークシートをペインに分割" %}}

APIは、Excelワークシートをさまざまなペインに分割する機能も提供します。プロセスは、Workbookクラスを使用してファイルをロードします。インデックスを指定して、最初のワークシートまたは必要なシートを選択します。関連するセルインデックスをパラメータとして持つsetActiveCellを呼び出します。最後に、split（）メソッドを呼び出して、ワークシートウィンドウをさまざまなペインに分割します。

{{% blocks/products/pf/feature-page-code h3="JavaExcelシートをペインビューに分割するためのコード" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}