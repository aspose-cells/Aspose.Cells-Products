---
title: Excelファイルの統合API.NETC#
url: /ja/net/merger/
description: ExcelとOpenOfficeのスプレッドシートファイルを数行のC#コードで連結します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>.NETを介したExcelファイルのマージ" h2="C#コードを使用して2つ以上のExcelファイルを1つのスプレッドシートに結合する" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NETExcelライブラリ](/cells/net/) ワークブックを数式、データ、画像、グラフなどのさまざまな種類のコンテンツと組み合わせて1つのスプレッドシートファイルにする複数の方法を提供します。サポートされているファイル形式には、XLS、XLSX、XLSB、XLT、XLTX、XLTM、ODS、CSV、TSVなどがあります。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイルを画像やグラフと組み合わせる" %}}
画像とグラフを含む2つのExcelファイルを組み合わせる最も簡単な方法は、 [Workbook.Combine](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) 方法。これにより、同様のタイプのExcelファイルを1つのスプレッドシートにマージできます。
{{% blocks/products/pf/feature-page-code h3="C#Excelファイルを結合するコード" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="複数のExcelファイルをマージする" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) methodは、Excelファイルのデータ、スタイル、および式を同じ形式の新しいスプレッドシートにマージすることをサポートします。これは、キャッシングを使用しながら複数のファイルをマージする効率的な方法です。 
{{% blocks/products/pf/feature-page-code h3="C#複数のExcelファイルをマージするコード" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ワークシートをコピーしてExcelファイルをマージする" %}}
[Worksheet.Copy](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) データとフォーマットをソースワークシートからワークブック内またはワークブック間で別のワークシートにコピーするために使用できます。このメソッドは、ソースワークシートオブジェクトをパラメーターとして受け取ります。
{{% blocks/products/pf/feature-page-code h3="C#Excelファイル間でワークシートをコピーするためのコード" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}