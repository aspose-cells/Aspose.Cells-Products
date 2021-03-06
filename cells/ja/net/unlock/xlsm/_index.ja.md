---
title: .NETを介してXLSMドキュメントのロックを解除します 
weight: 9810
url: /ja/net/unlock/xlsm/ 
description: .NETフレームワーク、.NETコア、Mono、またはXamarinプラットフォームでパスワードで保護されたXLSMファイルのロックを解除するためのC#ソースコード。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#を介してXLSMスプレッドシートのロックを解除します" h2=".NETライブラリを使用してXLSMから保護を削除します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してXLSMファイルのロックを解除する方法" %}}

 保護XLSMファイルを削除するには、
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 APIは、C#プラットフォーム向けの機能が豊富で、強力で、使いやすいドキュメント保護APIです。開ける
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 パッケージマネージャー、検索
 ** Aspose.Cells ** 
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#を介してXLSMのロックを解除します" %}}

{{% blocks/products/pf/agp/text %}}

 あなたが必要です
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 次のワークフローを実行するためにプロジェクトで参照されます。

{{% /blocks/products/pf/agp/text %}}

1. 保護されたXLSMファイルへのパスを使用してワークブッククラスをインスタンス化します1. デフォルトまたは任意のワークシートを取得して保護を削除します1. Worksheet.Unprotectメソッドを使用してワークシート保護を削除します1. Workbook.Unprotectメソッドを使用してワークブック保護を削除します1. 結果をXLSM形式で保存
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NETは、すべての主要なオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Mono、またはXamarinプラットフォームと互換性のあるOS- MicrosoftVisualStudioのような開発環境- プロジェクトで参照されているAspose.Cellsfor .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="" %}}

```cs

// 保護されたXLSMファイルを使用してWorkbookオブジェクトをインスタンス化します
var workbook = new Aspose.Cells.Workbook("protected.xlsm");

// Excelファイルのデフォルトのワークシートにアクセスします
var worksheet = workbook.Worksheets[0];

// パスワードなしでワークシートの保護を解除する
worksheet.Unprotect();

// パスワードでワークブックの保護を解除する
workbook.Unprotect("password");

// 結果をXLSM形式で保存します
workbook.Save("unprotected.xlsm", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="約Aspose.Cellsfor .NETAPI" %}}

 Aspose.Cells APIは、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングするために使用できます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンのAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="XLSMのロックを解除する無料アプリ" sectionDescription="ライブデモをチェックして [XLSMファイルのロックを解除する](https://products.aspose.app/cells/unlock/xlsm) 以下の利点があります。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書いたりコンパイルしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSMファイルをアップロードして[ロック解除]ボタンを押すだけです" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" リンクから結果のXLSMファイルをダウンロードします" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
XLSM拡張子の付いたファイルは、マクロをサポートするSpreasheetファイルの一種です。アプリケーションの観点からは、マクロはプロセスの自動化に使用される一連の命令です。マクロは、繰り返し実行されるステップを記録するために使用され、マクロを再度実行することによってアクションの実行を容易にします。マクロは、VisualBasicEditorを使用してExcelワークブック内からMicrosoftのVisualBasicfor Applications（VBA）でプログラムされ、そこから直接実行/デバッグできます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされているロック解除フォーマット" subTitle="C#を使用すると、を含むさまざまな形式の保護/ロック解除を簡単に削除できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Excelバイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="バイナリExcelワークブックファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="OOXMLExcelファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}