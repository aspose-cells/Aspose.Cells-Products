---
title: Excel 파일 병합기 API .NET C#
url: /ko/net/merger/
description: 몇 줄의 C# 코드로 Excel 및 OpenOffice 스프레드시트 파일을 연결합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통한 Microsoft<sup>&reg;</sup> Excel 파일 병합" h2="C# 코드를 사용하여 단일 스프레드시트에서 2개 이상의 Excel 파일 결합" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET 엑셀 라이브러리](/cells/net/) 수식, 데이터, 이미지, 차트 등과 같은 다양한 유형의 콘텐츠가 포함된 통합 문서를 단일 스프레드시트 파일로 결합하는 여러 방법을 제공합니다. 지원되는 파일 형식에는 XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV 등이 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일을 이미지 및 차트와 결합" %}}
이미지와 차트가 있는 2개의 Excel 파일을 결합하는 가장 간단한 방법은 [통합 문서.결합](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) 방법. 유사한 유형의 Excel 파일을 단일 스프레드시트로 병합할 수 있습니다.
{{% blocks/products/pf/feature-page-code h3="C# Excel 파일을 결합하는 코드" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="여러 Excel 파일 병합" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) 이 방법은 Excel 파일의 데이터, 스타일 및 공식을 동일한 형식의 새 스프레드시트로 병합하는 것을 지원합니다. 캐싱을 사용하면서 여러 파일을 병합하는 효율적인 방법입니다. 
{{% blocks/products/pf/feature-page-code h3="C# 여러 Excel 파일을 병합하는 코드" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="워크시트를 복사하여 Excel 파일 병합" %}}
[워크시트.복사](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) 원본 워크시트의 데이터 및 서식을 통합 문서 내에서 또는 통합 문서 간에 다른 워크시트로 복사하는 데 사용할 수 있습니다. 이 메서드는 원본 워크시트 개체를 매개 변수로 사용합니다.
{{% blocks/products/pf/feature-page-code h3="C# Excel 파일 간에 워크시트를 복사하는 코드" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}