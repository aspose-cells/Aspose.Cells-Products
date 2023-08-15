---
title: Aspose.Cells 経由で TextBox を追加する方法
weight: 7700
limit:
description: TextBox を追加する方法を学びます。
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /ja/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells で TextBox を追加する方法を学びます" >}}

<p>
このチュートリアルでは、Excel ファイルに TextBox を追加します。
</p>

<p>
まず、次を使用して新しいワークブックを作成します。<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 図書館</a>そしてTextBoxを追加します。
</p>

<br />
{{< app/cells/tutorial >}}
//例概要: TextBox を追加する方法については、次のコードを確認してください。
//ExStepsummary:0: 次のコードは、TextBox を追加してテキストを設定する方法を示しています。
//ExStepImage:0:step-1.png
//ExStepsummary:1: 次のコードは、テキストの色を変更する方法を示しています。
//ExStepImage:1:step-2.png
//ExStepsummary:2: 次のコードは、TextBox の回転角度を変更する方法を示しています。
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

//TextBoxを追加し、テキストを設定します
TextBox textBox =シェイプ.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET は、ソフトウェア開発者が独自のアプリケーション内でスプレッドシート ファイルを操作および処理できるようにするプログラミング クラス ライブラリです。";

//例ステップ:1-
// 文字の色を変更します
textBox.Font.Color = Color.Blue;

//例ステップ:2-
//TextBoxの回転角度を変更する
textBox.RotationAngle = 90;

//ExStep:0-

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