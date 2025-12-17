---
title: Go で Excel ファイルの注釈を追加または削除する（C++ 経由）
description: C++ ライブラリを介して、Go を使用して Excel および OpenOffice スプレッドシートのデータ注釈コメントを追加または削除します。
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" C++ 経由で Go を使用して Microsoft<sup>&reg;</sup> Excel ファイルの注釈を管理する" h2="C++ ベースのアプリケーションを介して、Go 内で注釈またはコメント用の簡単なメモを追加または削除します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API 経由でアクセス](/cells/ja/go-cpp/)コメントの追加、アクセス、削除によってセルレベルで注釈を管理するためのサポートを提供します。APIは、[コメント](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/)そして[コメントコレクション](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)同様に[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/)あらゆる側面からコメントを処理します。サポートされているExcel形式は、ODS、XLS、XLSX、XLSB、XLSMです。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイルのデータ注釈" %}}
ワークシートのコメント操作 - MS Excelでは、シートに挿入できるコメントの数に制限はありません。必要に応じて、必要なだけコメントを挿入できます。コメントを挿入する手順は、[ワークブック](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/)クラスオブジェクトを使用して既存のファイルを読み込み、コメントを追加したいワークシートを選択します。getComments()を使用してすべてのコメントを取得します。コメントを追加するには[追加(const char16_t* セル名)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/)メソッド。セルのインデックスを取得し、[メモを設定する](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/)コメントを挿入するためのものです。さらに、APIはすべてのコメントを削除できます。いくつかのメソッドは[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/)デザイナーのスプレッドシート内のすべてのコメントをクリアします。さらに、***削除先***指定されたインデックスまたは指定された名前の要素を削除するメソッド。

{{% blocks/products/pf/feature-page-code h3="C++コードを使用してExcelファイル内にコメントを追加する" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
