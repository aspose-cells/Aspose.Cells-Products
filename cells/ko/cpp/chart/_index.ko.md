---
title: C++을 통해 Excel 차트를 만들고 이미지로 변환
description: C++ C++ 라이브러리를 사용하여 Microsoft Excel에서 차트 또는 다이어그램을 그리고 변환하는 소스 코드
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 차트를 생성하고 C++을 통해 이미지로 변환" h2="C++ 기반 애플리케이션 내에서 Excel 문서 차트를 이미지로 변환하고 원형, 피라미드, 꺾은선형 및 거품형 차트를 포함한 차트를 생성할 수 있습니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Excel 차트를 사용하면 더 큰 그림을 얻고 데이터를 쉽게 분석하여 올바른 결정을 내릴 수 있습니다.[C++ 엑셀 라이브러리](/cells/ko/cpp/) 다음과 같이 나열된 다양한 차트 생성을 지원합니다.[열거형 Aspose::Cells::차트::차트 유형
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) 영역형, 막대형, 원형, 피라미드형, 선형 및 거품형 차트를 포함합니다. 또한 차트를 이미지로 변환하려면 API에서[이미지로](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) 필요한 이미지 형식으로 변환합니다.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel 차트 만들기" %}}

 Excel 차트를 만드는 과정은[워크북 수업](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) 원하는 것을 선택하고[워크시트](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . 다음을 사용하여 차트를 추가합니다.[메소드 추가](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)차트 유형을 포함한 관련 매개변수를 사용합니다. 인덱스를 통해 차트에 액세스하고[추가하다](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) 차트의 데이터 소스입니다.

{{% blocks/products/pf/feature-page-code h3="C++ Excel 차트를 생성하는 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="차트를 이미지로 변환" %}}


차트 변환 과정은 먼저 위의 코드를 이용하여 해당 유형의 차트를 생성하거나 해당 시트에서 접근합니다. 이미지의 출력 저장 경로를 정의하고 ToImage 메서드를 사용하여 변환합니다.

 
{{% blocks/products/pf/feature-page-code h3="C++ Excel 차트를 변환하는 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
