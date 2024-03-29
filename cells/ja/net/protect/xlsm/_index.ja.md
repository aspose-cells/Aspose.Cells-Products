---
title: 保護とロック XLSM ドキュメント via .NET
weight: 7530
description: C# フレームワーク、.NET コア、Mono または Xamarin プラットフォームでパスワードを使用して XLSM ファイルをロックするための C# ソース コード。
keywords: [C# Aspose.Cells., c# Lock XLSM files., c# How to Protect and lock XLSM document., c# Protect XLSM files., Encrypt XLSM Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSM 経由で XLSM ファイルを暗号化する" h2=".NET ライブラリを使用して、XLSM 形式を含む Excel スプレッドシートをパスワードで保護します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してXLSMファイルを保護する方法" %}}

XLSM ファイルを保護するには、次を使用します。
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
API は、C# プラットフォーム用の機能が豊富で強力で使いやすい文書保護 API です。開ける
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
パッケージマネージャー、検索
 **Aspose.Cells** 
そしてインストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# 経由で XLSM を保護" %}}

{{% blocks/products/pf/agp/text %}}

必要です
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
プロジェクト内で参照され、次のワークフローを実行します。

{{% /blocks/products/pf/agp/text %}}

1. XLSM ファイルへのパスを使用して Workbook クラスをインスタンス化します。
1. デフォルトまたは任意のワークシートを取得して保護を追加します
1. Worksheet.Protect メソッドでワークシートを保護する
1. Workbook.Protect メソッドでブックを保護する
1. 結果をXLSM形式で保存

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for .NET は、すべての主要なオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows、または .NET フレームワーク、.NET コア、Mono または Xamarin プラットフォームと互換性のある OS
-  Microsoft Visual Studio のような開発環境
- プロジェクトに Aspose.Cells for .NET DLL への参照を追加します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="" %}}

```cs

// load the XLSM Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsm");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="約 Aspose.Cells for .NET API" %}}

 Aspose.Cells API は、Excel 形式を作成、編集、変換し、さまざまな形式にレンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="保護する無料アプリ XLSM" sectionDescription="ライブデモをチェックしてください[XLSM ファイルを暗号化する](https://products.aspose.app/cells/protect/xlsm)以下の特典付き。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="何もダウンロードしたり設定したりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="コードを書いたりコンパイルしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="XLSM ファイルをアップロードして「ロック解除」ボタンを押すだけです" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="結果の XLSM ファイルをリンクからダウンロードします。" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
XLSM拡張子を持つファイルは、マクロをサポートするスプレッドシートファイルの一種です。アプリケーションの観点から見ると、マクロはプロセスを自動化するために使用される一連の命令です。マクロは、繰り返し実行される手順を記録するために使用され、マクロを再度実行することでアクションの実行が容易になります。マクロは、Visual Basic Editor を使用して Excel ワークブック内から Microsoft の Visual Basic for Applications (VBA) でプログラムされ、そこから直接実行/デバッグできます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている保護形式" subTitle="C# を使用すると、次のような他の形式を簡単に保護できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="OpenDocument スプレッドシート ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Excel バイナリ形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="バイナリ Excel ワークブック ファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="OOXML Excel ファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
