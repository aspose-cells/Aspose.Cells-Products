---
title: C# SqlServer から EXCEL - SqlServer から EXCEL コンバータ
description: Aspose エクセル。 Aspose.Cells を使用して、SqlServer を EXCEL にすばやく簡単に変換します。 C# SqlServer を EXCEL に変換します。 C# SqlServer を EXCEL に保存します。 C# を使用して SqlServer を EXCEL として保存します。
keywords: [Aspose Excel., C# Aspose.Cells., Convert SqlServer to EXCEL in C#., Save SqlServer to EXCEL using C#., C# SqlServer to EXCEL saveformat., SqlServer to EXCEL Converter., C# Save SqlServer as EXCEL]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# で SqlServer を EXCEL に変換" h2="SqlServer を EXCEL に変換するための高速 C# ライブラリ。これは、EXCEL、SqlServer、およびその他の多くの形式を .NET フレームワーク、.NET コア、または Mono プラットフォームでインポートおよびエクスポートするためのプロフェッショナル ソフトウェア ソリューションです。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SqlServer" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してSqlServerをEXCELに変換する" %}}
SqlServer を EXCEL に変換するにはどうすればよいですか? Aspose.Cells for .NET ライブラリを使用すると、数行のコードでプログラム的に SqlServer を EXCEL に簡単に変換できます。[Aspose.Cells for .NET](https://products.aspose.com/cells/net)すべての Excel ファイルを生成、変更、変換、レンダリング、印刷できるクロスプラットフォーム アプリケーションを構築できます。 .NET Excel API は、スプレッドシート形式間で変換するだけでなく、Excel ファイルを画像 PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT などとしてレンダリングすることもできるため、業界標準形式でドキュメントを交換するのに最適です。開ける[NuGet](https://www.nuget.org/packages/aspose.cells)パッケージ マネージャーで、Aspose.Cells を検索してインストールします。パッケージ マネージャー コンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="C# 経由で SqlServer を EXCEL に変換する方法" %}}

{{% blocks/products/pf/agp/text %}}

SqlServer データをプログラムで EXCEL に変換する必要がありますか? .NET 開発者は、わずか数行のコードで SqlServer を簡単にロードして EXCEL に変換できます。

{{% /blocks/products/pf/agp/text %}}

1.  「Aspose.Cells for .NET」をインストールします。
1. ライブラリ参照を C# プロジェクトに追加します (ライブラリをインポートします)。
1.  SqlServer データベースからデータをクエリして、DataTable オブジェクトを取得します。
1. 新しいワークブックを作成し、DataTable オブジェクトからデータをインポートします。
1. Workbook.Save メソッドを呼び出して、データを xlsx 形式で保存します。

{{% blocks/products/pf/agp/code-block title="SqlServer を EXCEL に変換するサンプル コード - C#" offSpacer="" %}}

```cs
var connectionString = "Server=localhost;Database=SqlServerTestDataBase;User ID=root;Password=admin;Trusted_Connection=False;";
var tableName = "countrylanguage";

string query = $"SELECT * FROM {tableName}";

using (SqlConnection connection = new SqlConnection(connectionString))
{
    connection.Open();
    SqlCommand cmd = new SqlCommand(query, connection);
    SqlDataAdapter adapter = new SqlDataAdapter(cmd);

    DataTable dataTable = new DataTable();
    adapter.Fill(dataTable);

    Workbook workbook = new Workbook();
    Worksheet worksheet = workbook.Worksheets[0];
    worksheet.Cells.ImportData(dataTable, 0, 0, new ImportTableOptions() { InsertRows = true });
    workbook.Save("SQLServerData.xlsx");
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="C# SqlServer を EXCEL に変換するライブラリ" %}}

{{% blocks/products/pf/agp/text %}}

「Aspose.Cells for .NET」をシステムにインストールするには、2 つの代替オプションがあります。ニーズに近いものを選択し、ステップバイステップの指示に従ってください。

{{% /blocks/products/pf/agp/text %}}

1. をインストールします[NuGet パッケージ](https://www.nuget.org/packages/Aspose.Cells/)。見る[ドキュメンテーション](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1. を使用してライブラリをインストールします[パッケージマネージャーコンソール](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console)Visual Studio IDE内で

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

.NET 変換サンプル コードを実行する前に、次の前提条件を満たしていることを確認してください。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows、または .NET、.NET コア、Windows Azure または Mono プラットフォームと互換性のある OS。
-  Microsoft Visual Studio のような開発環境。
- プロジェクトに Aspose.Cells for .NET DLL への参照を追加します。

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
