---
title: Javaを介してExcelファイルを作成する
url: /ja/java/assembly/
description: Javaスプレッドシートライブラリを使用して、テンプレートシートからMicrosoftExcelスプレッドシートを生成します
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>JavaによるExcelテンプレートベースのレポート作成" h2="Javaベースのアプリケーション内の事前定義されたテンプレートに基づいてバルクExcelファイルレポートを生成します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[JavaExcelライブラリ](/cells/java/) 一括レポート生成用のテンプレートベースのExcelファイルの生成をサポートします。これは、料金表、結果カード、患者記録などの作成など、ほとんどの場合に必要です。テンプレートは事前定義されたパターンです。 Java以下のコードは、データが入力されたテンプレートドキュメントと同じバルクExcelファイルを生成します。サポートされているファイル形式には、XLS、XLSX、XLSB、XLSM、ODSが含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="事前に設計されたExcelテンプレートに基づいてレポートを作成する" %}}

JavaアセンブリAPIを使用すると、開発者は以下のコードスニップを含めることで、一括レポート生成コードを簡単にプログラムできます。 APIは提供します [データのインポート](https://docs.aspose.com/cells/java/import-and-export-data/) さまざまなソースから機能を提供し、そのデータに応じてExcelドキュメントを作成します。テンプレートベースのパターンの場合、APIは [WorkbookDesignerクラス](https://apireference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) デザイナーワークシートを表すため。プロセスは、そのオブジェクトを作成し、それを使用してテンプレートファイルを開きます。データソース（Array、DataTable、Jsonなど）を設定します。データを処理してデータをインポートし、ファイルを目的の形式で保存します。プログラマーは、以下にリストされているリンクのように、XLS、XLSX、XLSB、XLSM、ODSを含む他のファイル形式のレポートにデータを組み立てることができます。



{{% blocks/products/pf/feature-page-code h3="JavaExcelレポートを作成するためのコード" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}