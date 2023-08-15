---
title: Aspose.Cells 経由で図形を追加する方法
weight: 7700
limit:
description: 図形を追加する方法を学びます。
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /ja/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells で図形を追加する方法を学ぶ" >}}

<p>
このチュートリアルでは、Excel ファイルに図形を追加します。
</p>

<p>
まず、次を使用して新しいワークブックを作成します。<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 図書館</a>そして図形を追加します。
</p>

<br />
{{< app/cells/tutorial >}}
//例概要: 図形を追加する方法については、次のコードを確認してください。
//ExStepsummary:0: 次のコードは、長方形の形状を追加する方法を示しています。
//ExStepImage:0:step-1.png
//ExStepsummary:1: 次のコードは、線の形状を追加する方法を示しています。
//ExStepImage:1:step-2.png
//ExStepsummary:2: 次のコードは、楕円形を追加する方法を示しています。
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cellsを使用します。
Aspose.Cellsを使用しています。図面;





ワークブック workbook = new Workbook();
ワークシートsheet = workbook.Worksheets[0];
シート.PageSetup.PrintGridlines = true;
Sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection の形状 =sheet.Shapes;

// 長方形の形状を追加します
シェイプ.AddRectangle(1, 0, 1, 0, 100, 150);

//例ステップ:1-
//線の形状を追加
形状.AddLine(8, 0, 1, 0, 100, 150);

//例ステップ:2-
//楕円形を追加します
形状.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
ワークブック
//拡張終了
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Aspose.Cellsの設置</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells 編集者</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}