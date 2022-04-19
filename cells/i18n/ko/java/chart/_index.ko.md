---
title: Java을(를) 통해 Excel 차트를 만들고 이미지로 변환
url: /ko/java/chart/
description: Java 소스 코드는 Java 라이브러리를 사용하여 Microsoft Excel에서 차트 또는 다이어그램을 그리고 변환합니다. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Java을 통한 Excel 파일 차트 변환 및 생성" h2="Excel 문서 차트를 이미지로 변환하고 Java 기반 애플리케이션 내에서 서버 측 API를 사용하여 다양한 차트를 생성합니다." >}}


{{% blocks/products/pf/feature-page-summary %}}

차트를 통해 데이터를 분석하면 더 큰 그림을 볼 수 있으며 더 명확한 통찰력으로 더 많은 정보에 입각한 결정을 내리기가 쉽습니다. [Java 엑셀 라이브러리](/cells/java/) 에 의해 나열된 다른 차트 생성 그리기 지원 [차트 유형](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) 파이, 피라미드, 꺾은선형 및 거품형 차트를 포함합니다. 또한 차트를 이미지로 변환합니다. API 제공 [차트 클래스](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) 단일 Excel 차트를 나타내기 위한 것입니다.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel 차트를 이미지로 변환" %}}

차트를 JPG, PNG, TIFF, BMP 등의 이미지로 변환하는 프로세스는 [학습장](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) 클래스를 사용하여 Excel 파일을 로드하고 관련 선택 [작업장](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) 차트를 포함하거나 각 워크시트의 각 차트를 반복합니다. 정의하다 [이미지 또는 인쇄 옵션](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) 다음을 사용하여 차트의 출력 이미지를 렌더링합니다. [Chart.toImage](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel 차트를 이미지로 변환하는 코드" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excel 파일 내에서 차트 만들기" %}}

Excel API을(를) 사용하여 차트를 만드는 것은 간단합니다. API에서 다양한 종류의 차트에 대해 Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection 등과 같은 다양한 클래스 세트를 제공하기 때문입니다. 프로세스는 Workbook 클래스 개체를 만들고 인덱스를 제공하여 첫 번째 워크시트 또는 관련 시트를 선택하는 것입니다. 차트의 데이터 소스의 경우 다음을 사용하여 워크시트 셀에 값을 삽입합니다. [설정값](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) 방법. ChartCollection 컬렉션 사용 [메소드 추가](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) 차트를 추가하려면 ChartType 열거형으로 차트 유형을 정의합니다. 해당 인덱스를 전달하여 ChartCollection 컬렉션에서 새 Chart 개체에 액세스합니다. 사용 [시리즈 컬렉션](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) 차트의 데이터 소스를 지정하는 차트 개체.

{{% blocks/products/pf/feature-page-code h3="Java Excel 차트를 만드는 코드" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}