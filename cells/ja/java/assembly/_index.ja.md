---
title: Excel ファイルの作成 via Java
description: Java スプレッドシート ライブラリを使用してテンプレート シートから Microsoft Excel スプレッドシートを生成
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel テンプレート ベースのレポート作成 via Java" h2="Java ベースのアプリケーション内の事前定義されたテンプレートに基づいて、一括 Excel ファイル レポートを生成します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java エクセルライブラリ](/cells/ja/java/)一括レポート生成用のテンプレート ベースの Excel ファイルの生成をサポートします。これは、料金シャラン、結果カード、患者記録などの作成など、ほとんどの場合に必要です。テンプレートは事前定義されたパターンです。以下の Java コードは、データが入力されたテンプレート ドキュメントと同じバルク Excel ファイルを生成します。サポートされているファイル形式には、XLS、XLSX、XLSB、XLSM、ODS が含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="事前に設計された Excel テンプレートに基づいてレポートを作成" %}}

Java アセンブリ API を使用すると、開発者は以下のコード スニペットを含めることで、一括レポート生成コードを簡単にプログラムできます。 APIが提供します[データをインポートする](https://docs.aspose.com/cells/java/import-and-export-data/)さまざまなソースから特徴を取得し、そのデータに応じて Excel ドキュメントを作成します。テンプレートベースのパターンの場合、API は[WorkbookDesigner クラス](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner)デザイナーのワークシートを表します。プロセスは、そのオブジェクトを作成し、それを使用してテンプレート ファイルを開きます。データソース (配列、DataTable、Json など) を設定します。それを処理してデータをインポートし、ファイルを目的の形式で保存します。プログラマは、以下のリンクにあるように、XLS、XLSX、XLSB、XLSM、ODS などの他のファイル形式のレポートにデータを組み立てることができます。



{{% blocks/products/pf/feature-page-code h3="Java Excel レポートを作成するコード" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}
