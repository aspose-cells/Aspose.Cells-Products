---
title: C# 経由でグラフに線を追加します
description: C# .NET ライブラリを使用して Excel にグラフに線を追加するサンプル コード。 VB.NET、Asp.NET、または .NET ベースのアプリケーション内の MS Excel にグラフに線を追加するには、このコードを使用します。
keywords: [C# Aspose.Cells., c# add a line in chart., c# insert a line in chart., c# create a line in chart]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# 経由でグラフに線を追加します" h2="サーバー側 .NET API を使用して、プログラムによるネイティブで高パフォーマンスの MS Excel の作成。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

実行中のアプリケーション内でグラフに線を動的に追加するのは簡単です。 MS Office を必要とせずにスプレッドシートにさまざまなグラフを最初から作成するには、次を使用します。[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API プラットフォームを使用してスプレッドシートの作成、操作、変換のためのさまざまな機能を提供します。 Aspose.Cells は、多くの柔軟なグラフ オブジェクトを提供します。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# 経由でチャートに線を追加する方法" %}}

{{% blocks/products/pf/agp/text %}}

開発者は、わずか数行のコードでデータ処理用のさまざまなレポート アプリケーションを実行する際に、グラフに線を追加するのが簡単です。

{{% /blocks/products/pf/agp/text %}}

1. 作成する[**ワークブック**](https://reference.aspose.com/cells/net/aspose.cells/workbook)クラスインスタンス。
1. 次のコマンドを使用して、ワークシートのセルにデータを追加します。[**Cell**](https://reference.aspose.com/cells/net/aspose.cells/cell)オブジェクトの[**PutValue**](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)方法。
これはグラフのデータ ソースとして使用されます。
1. を呼び出して、チャートをワークシートに追加します。[**チャート**](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection)コレクションの[**追加**](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add)メソッドにカプセル化されている[**ワークシート**](https://reference.aspose.com/cells/net/aspose.cells/worksheet)物体。
1. 新しいものにアクセスする[**チャート**](https://reference.aspose.com/cells/net/aspose.cells.charts/chart)インデックスを渡して Charts コレクションからオブジェクトを取得し、呼び出してグラフのデータ ソースを指定します[**Chart.SetChartDataRange**](https://https://reference.aspose.com/cells/net/aspose.cells.charts/chart/methods/setchartdatarange).
1. を呼び出してチャートの位置を計算します。[**計算する**](https://https://reference.aspose.com/cells/net/aspose.cells.charts/chart/methods/Calculate)方法。
1. 追加[**ライン**](https://reference.aspose.com/cells/net/aspose.cells.drawing/shape/properties/msodrawingtype)Chart.Shapes.AddShapeInChartByScale メソッドを呼び出して整形します。
1. 線の形式を設定する

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

システムに Microsoft Windows、または .NET Framework、.NET Core、Windows Azure、Mono または Xamarin プラットフォームと互換性のある OS、および Microsoft Visual Studio などの開発環境が搭載されていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- コマンドラインから次のようにインストールします<code>nuget install Aspose.Cells</code>または Visual Studio のパッケージ マネージャー コンソール経由で<code>Install-Package Aspose.Cells</code>.
- または、オフライン MSI インストーラーまたは ZIP ファイル内のすべての DLL を次のサイトから入手します。<a href="https://downloads.aspose.com/cells/net">ダウンロード</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="次のソース コードは、C# を使用して MS Excel XLSX ファイルにグラフに線を追加する方法を示しています。" offSpacer="" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "Examples-CSharp-Charts-AddLineInChart.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

上記のコードを実行すると、次の結果が得られます。

![](line-in-chart.png)

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->
