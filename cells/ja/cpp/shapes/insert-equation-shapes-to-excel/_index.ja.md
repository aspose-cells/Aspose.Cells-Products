---
title: C++ 経由で数式図形を Excel に挿入
weight: 780
description: C++ 32 ビット、Windows 64 ビット、および Linux 64 ビットの C++ ランタイム環境で Excel ファイルに数式図形を挿入するための C++ コード例。
keywords: [C++ Aspose.Cells., C++ add equation shapes., C++ insert equation shapes., C++ create equation shapes]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ 経由で数式図形を Excel に挿入" h2="Microsoft や Adobe PDF などのソフトウェアを使用せずに、サーバー側 Aspose.Cells for C++ API のネイティブで高いパフォーマンスを使用してオブジェクトを挿入します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ を使用して数式図形を Excel ファイルに挿入する方法" %}}

数式の図形を Excel ファイルに挿入するには、次を使用します。
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API は、機能が豊富で強力で使いやすいドキュメント検索 API for C++ プラットフォームです。最新バージョンを直接ダウンロードできます。開くだけです。
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
パッケージマネージャー、検索
 **Aspose.Cells.Cpp** 
そしてインストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="指示" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ 経由で数式図形を Excel ファイルに挿入する手順" %}}

Workbook オブジェクトをインスタンス化します。(または -> XLSX ファイルをフルパスでロードします。)
+ インデックスからワークシートを選択します。
 + を使用してください[メソッドの追加](https://reference.aspose.com/cells/cpp/aspose.cells.drawing/shapecollection/addautoshape/)選択したワークシートに数式図形を挿入するには
ワークブックを XLSX 形式で保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for C++ は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows、または Windows 32 ビット、Windows 64 ビット、および Linux 64 ビットの C++ ランタイム環境と互換性のある OS。
- プロジェクトに Aspose.Cells for C++ DLL への参照を追加します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/text %}}

以下のサンプル コードは、「数学プラス」を挿入する方法を示しています。その他のタイプについては、以下の「方程式形状タイプの概要」を参照してください。

{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/code-block title="数式の図形を挿入 - C++" offSpacer="" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "InsertEquationIntoWorksheet-new.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
方程式の形状タイプの概要
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/plus.png" align="left" width="28" height="28">
    <p class="col-lg-10">
AutoShapeType::AutoShapeType_MathPlus
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/minus.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::AutoShapeType_MathMinus
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/multiplication.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::AutoShapeType_MathMultiply
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/division.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::AutoShapeType_MathDivide
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/equals.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::AutoShapeType_MathEqual
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/not_equal.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType::AutoShapeType_MathNotEqual
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}


{{% blocks/products/pf/agp/content h2="約 Aspose.Cells for C++ API" %}}

Aspose.Cells API は、Excel 形式を作成、編集、変換し、さまざまな形式にレンダリングするために使用できます。さらに、ソフトウェア アプリケーション内で包括的なグラフ作成、スケーラブルなレポート作成、および信頼性の高い計算に使用できます。 Aspose.Cells はスタンドアロンの API であり、Microsoft や OpenOffice などのソフトウェアは必要ありません。

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
