---
title: C#에서 Excel 워크시트를 현명하게 분할

description: Visual C#.NET 애플리케이션에서 Microsoft Excel 파일을 여러 파일로 분할하는 방법을 설명하는 C# 소스 코드
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통한 Microsoft<sup>&reg;</sup> Excel 파일 분할" h2=".NET 기반 애플리케이션 내에서 C# 코드를 사용하여 단일 Excel 문서를 다른 파일로 분할" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET 엑셀 라이브러리](/cells/net/) Excel 문서를 .NET 기반 애플리케이션 내에서 여러 스프레드시트로 분할할 수 있습니다. 지원되는 파일 형식에는 XLS, XLSX, XLSB, XLSM, ODS가 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 문서를 여러 파일로 분할" %}}
Excel 파일을 시트로 분할하는 가장 간단한 방법은 다음을 통해 모든 시트에 액세스하는 것입니다. [워크시트](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), 각 시트를 반복하고 호출 [복사](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) 방법. 마지막으로 지정된 경로에 저장합니다. 

+ 다음을 사용하여 전체 경로로 Excel 파일 로드 [워크북 수업](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ 각 시트를 통해 반복
+ 새 통합 문서 클래스 개체 만들기
+ 다음을 통해 시트 복사 [복사 방법](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Save() 메서드를 호출하고 관련 SaveFormat이 있는 파일 이름(전체 경로)을 전달합니다.

{{% blocks/products/pf/feature-page-code h3="C# Excel 파일을 분할하는 코드" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 창으로 분할" %}}

워크시트 창을 창으로 분할하기 위해 API는 다음을 제공합니다. [분할 방법](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) 워크시트의 분할 보기를 제공하는 워크시트 클래스의 분할 보기를 제거하려면 API이(가) 제공합니다. [RemoveSplit 메서드](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). 마지막으로 지정된 경로에 저장합니다. 

{{% blocks/products/pf/feature-page-code h3="C# Excel 워크시트 창을 분할하는 코드" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# 분할된 팬 보기를 제거하는 코드" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
