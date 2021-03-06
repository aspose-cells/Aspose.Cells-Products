---
title: .NETを介してXLSドキュメントを保護およびロックする 
weight: 7010
url: /ja/net/protect/xls/ 
description: .NETフレームワーク、.NETコア、Mono、またはXamarinプラットフォームでパスワードを使用してXLSファイルをロックするためのC#ソースコード。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#を介してXLSファイルを暗号化する" h2=".NETライブラリを使用してXLS形式を含むExcelスプレッドシートをパスワードで保護します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してXLSファイルを保護する方法" %}}

 XLSファイルを保護するために、
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

{{% blocks/products/pf/agp/feature-section-col title="C#を介してXLSを保護する" %}}

{{% blocks/products/pf/agp/text %}}

 あなたが必要です
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 次のワークフローを実行するためにプロジェクトで参照されます。

{{% /blocks/products/pf/agp/text %}}

1. XLSファイルへのパスを使用してWorkbookクラスをインスタンス化します1. デフォルトまたは任意のワークシートを取得して保護を追加します1. Worksheet.Protectメソッドでワークシートを保護する1. Workbook.Protectメソッドでブックを保護する1. 結果をXLS形式で保存する
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NETは、すべての主要なオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Mono、またはXamarinプラットフォームと互換性のあるOS- MicrosoftVisualStudioのような開発環境- プロジェクトで参照されているAspose.Cellsfor .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="" %}}

```cs

// XLSExcelファイルをロードします 
var book = new Aspose.Cells.Workbook("unlocked.xls");

// 最初のワークシートにアクセスする
var worksheet = book.Worksheets[0];

// ワークシートをパスワードで保護する
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// ブック全体をパスワードで保護する
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// 変更したファイルをデフォルトの形式で保存します
book.Save("protected.xls");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="約Aspose.Cellsfor .NETAPI" %}}

 Aspose.Cells APIは、Microsoft Excel形式を作成、編集、変換、およびさまざまな形式にレンダリングするために使用できます。さらに、ソフトウェアアプリケーション内での包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.CellsはスタンドアロンのAPIであり、MicrosoftやOpenOfficeなどのソフトウェアは必要ありません。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="XLSを保護するための無料アプリ" sectionDescription="ライブデモをチェックして [XLSファイルを暗号化する](https://products.aspose.app/cells/protect/xls) 以下の利点があります。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書いたりコンパイルしたりする必要はありません" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSファイルをアップロードして[ロック解除]ボタンを押すだけです" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" リンクから結果のXLSファイルをダウンロードします" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS拡張子の付いたファイルは、Excelバイナリファイル形式を表します。このようなファイルは、Microsoft Excelだけでなく、OpenOfficeCalcやAppleNumbersなどの他の同様のスプレッドシートプログラムでも作成できます。 Excelによって保存されたファイルは、各ワークブックに1つ以上のワークシートを含めることができるワークブックと呼ばれます。データはワークシートに表形式で保存および表示され、数値、テキストデータ、数式、外部データ接続、画像、およびグラフにまたがることができます。 Microsoft Excelなどのアプリケーションを使用すると、ワークブックデータをPDF、CSV、XLSX、TXT、HTML、XPSなどのさまざまな形式にエクスポートできます。 XLSファイル形式は、Microsoft Excel 2007のリリースにより、よりオープンで構造化された形式であるXLSXに置き換えられました。現在、XLSXが最初に使用されていますが、最新バージョンではXLSファイルの作成と読み取りが引き続きサポートされています。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている保護フォーマット" subTitle="C#を使用すると、を含む他の形式を簡単に保護できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="OpenDocumentスプレッドシートファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="バイナリExcelワークブックファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Spreasheetファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="OOXMLExcelファイル" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}