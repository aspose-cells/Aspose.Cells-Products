---
title: C# 経由でローソク足チャートを作成する
description: C# .NET ライブラリを使用して Excel にローソク足（始値、高値、安値、終値）チャートを作成するサンプル コードです。 VB.NET、Asp.NET、または .NET ベースのアプリケーション内で MS Excel にローソク足チャートを作成するには、このコードを使用します。
keywords: [C# Aspose.Cells., c# add Candlestick Chart., c# insert Candlestick Chart., c# create Candlestick Chart]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/i18n/upper-banner h1="C# 経由でローソク足 (始値、高値、安値、終値) チャートを作成する" h2="サーバー側 .NET API を使用して、ネイティブで高性能の MS Excel グラフをプログラムで作成します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}
{{% blocks/products/pf/agp/content h2="" %}}

始値-高値-安値-終値 (OHLC) チャートでは、カテゴリ、始値、高値、安値、終値の順に 5 列のデータが使用されます。各カテゴリの価格の範囲は再び垂直線で示され、始値と終値の間の範囲は幅の広い浮動バーで示されます。カテゴリ内の価格が上昇すると (終値が始値よりも高くなります)、バーは 1 つの色で塗りつぶされ、価格が下がると、バーは別の色で塗りつぶされます。このタイプのチャートは、多くの場合、ローソク足チャートと呼ばれます。
{{% /blocks/products/pf/agp/content %}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ローソク足（始値、高値、安値、終値）チャートを作成する方法（C#経由）" %}}

{{% blocks/products/pf/agp/text %}}

開発者は、データ処理用のさまざまなレポート アプリケーションを実行しながら、わずか数行のコードでローソク足チャートを簡単に作成できます。

{{% /blocks/products/pf/agp/text %}}

1. クラスファイルに名前空間を含めます
1. 作成する[**ワークブック**](https://reference.aspose.com/cells/net/aspose.cells/workbook)クラスインスタンスによる[サンプル Excel ファイル](Open-High-Low-Close.xlsx).
1. 追加[**始値-高値-安値-終値株価**](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)を呼び出してワークシートにグラフを作成します。[**チャート**](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection)コレクションの[**追加**](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add)メソッドにカプセル化されている[**ワークシート**](https://reference.aspose.com/cells/net/aspose.cells/worksheet)物体。
1. 新しいものにアクセスする[**チャート**](https://reference.aspose.com/cells/net/aspose.cells.charts/chart)インデックスを渡すことで、Charts コレクションからオブジェクトを取得します。
1. チャートのデータソースを設定します。[**Chart.SetChartDataRange**](https://reference.aspose.com/cells/net/aspose.cells.charts/chart/methods/setchartdatarange)方法。
1. カテゴリデータを設定するには[**カテゴリデータ**](https://reference.aspose.com/cells/net/aspose.cells.charts/seriescollection/categorydata/)財産。
1.  Excel または ODS として保存[出力ファイル](out.xlsx).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}
{{% blocks/products/pf/agp/text %}}
システムに Microsoft Windows、または .NET Framework、.NET Core、Windows Azure、Mono または Xamarin プラットフォームと互換性のある OS、および Microsoft Visual Studio などの開発環境が搭載されていることを確認してください。
{{% /blocks/products/pf/agp/text %}}
- コマンドラインから次のようにインストールします<code><a href="https://downloads.aspose.com/cells/net">nuget install Aspose.Cells</a></code>または Visual Studio のパッケージ マネージャー コンソール経由で<code>Install-Package Aspose.Cells</code>.
- または、オフライン MSI インストーラーまたは ZIP ファイル内のすべての DLL を次のサイトから入手します。<a href="https://downloads.aspose.com/cells/net">ダウンロード</a>

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/code-block title="次のソース コードは、C# を使用して MS Excel XLSX ファイルにローソク足 (始値、高値、安値、終値) チャートを作成する方法を示しています。" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "create-open-high-low-close-stock-chart.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
