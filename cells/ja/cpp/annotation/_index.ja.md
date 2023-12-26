---
title: C++ 経由で Excel ファイルの注釈を追加または削除する
description: C++ ライブラリを使用して Excel および OpenOffice スプレッドシートのデータ注釈コメントを追加または削除します。
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルの注釈を C++ 経由で管理する" h2="C++ ベースのアプリケーション内の注釈またはコメントの簡単なメモを追加または削除します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ エクセル API](/cells/ja/cpp/)コメントの追加、アクセス、削除によりセル レベルで注釈を管理するためのサポートを提供します。 APIが提供します[コメント](https://reference.aspose.com/cells/cpp/aspose.cells/comment/)そして[コメントコレクション](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/)同様に[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)あらゆる面でコメントを処理します。サポートされている Excel 形式には、ODS、XLS、XLSX、XLSB、XLSM が含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel ファイル データの注釈" %}}
ワークシート内のコメントの操作 - MS Excel では、シートに含まれるコメントの数に制限はありません。アプリケーションに必要なだけ挿入できます。コメントを挿入するプロセスは、[ワークブック](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)クラス オブジェクトを使用して既存のファイルをロードし、コメントを追加するワークシートを選択します。 getComments() を使用してすべてのコメントを取得します。を使用してコメントを追加します[Add(const char16_t* セル名)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/)方法。セルインデックスを取得して使用します[セットノート](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/)コメントを挿入するため。さらに、API はすべてのコメントを削除できます。いくつかの方法は、[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) to デザイナー スプレッドシート内のすべてのコメントをクリアします。さらに、***削除場所***指定されたインデックスまたは指定された名前の要素を削除するメソッド。

{{% blocks/products/pf/feature-page-code h3="C++ Excel ファイル内にコメントを追加するコード" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
