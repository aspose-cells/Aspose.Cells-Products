---
title: C++을(를) 통해 Excel 차트를 만들고 이미지로 변환
url: /ko/cpp/chart/
description: C++ 라이브러리를 사용하여 Microsoft Excel에서 차트 또는 다이어그램을 그리고 변환하는 C++ 소스 코드
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 차트를 만들고 C++을 통해 이미지로 변환" h2="Excel 문서 차트를 이미지로 변환하고 C++ 기반 애플리케이션 내에서 원형, 피라미드, 선 및 거품 차트를 포함한 차트를 생성합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Excel 차트를 사용하면 더 큰 그림을 보고 올바른 결정을 내리기 위해 데이터를 쉽게 분석할 수 있습니다. [C++ 엑셀 라이브러리](/cells/cpp/) 에 의해 나열된 다른 차트 생성을 지원합니다. [열거형 Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) 영역, 막대, 파이, 피라미드, 꺾은선형 및 거품형 차트를 포함합니다. 또한 차트를 이미지로 변환하기 위해 API는 다음을 제공합니다. [ToImage 메소드](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) 필요한 이미지 형식으로.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel 차트 만들기" %}}

Excel 차트를 생성하는 과정은 의 인스턴스를 생성하는 것입니다. [아이워크북 클래스](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 그리고 원하는 선택 [워크시트](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). 다음을 사용하여 차트 추가 [메소드 추가](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) 차트 유형을 포함한 관련 매개변수로 인덱스를 통해 차트에 액세스하고 [추가하다](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) 차트의 데이터 소스입니다.

{{% blocks/products/pf/feature-page-code h3="C++ Excel 차트를 만드는 코드" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="차트를 이미지로 변환" %}}


차트 변환 프로세스는 먼저 위의 코드를 사용하여 해당 유형의 차트를 생성하거나 관련 시트에서 액세스합니다. 이미지의 출력 저장 경로를 정의하고 변환을 위해 ToImage 메서드를 사용합니다.

 
{{% blocks/products/pf/feature-page-code h3="C++ Excel 차트를 변환하는 코드" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}