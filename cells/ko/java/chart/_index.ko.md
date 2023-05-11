---
title: Excel 차트 작성 및 이미지로 변환 via Java
description:  Java 라이브러리를 사용하여 Microsoft Excel에서 차트 또는 다이어그램을 그리고 변환하는 Java 소스 코드.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 차트 변환 및 생성 via Java" h2="Java 기반 어플리케이션 내에서 서버측 API를 이용하여 엑셀 문서 차트를 이미지로 변환하고 다양한 차트를 생성합니다." >}}


{{% blocks/products/pf/feature-page-summary %}}

 차트를 통한 데이터 분석은 더 큰 그림을 보여주고 더 명확한 통찰력으로 더 많은 정보에 입각한 결정을 내리는 것이 쉽습니다.[Java 엑셀 라이브러리](/cells/ko/java/) 에 의해 나열된 다양한 차트 생성 그리기 지원[차트 유형](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) 원형, 피라미드, 선 및 거품형 차트를 포함합니다. 또한 차트를 이미지로 변환합니다. API은[차트 클래스](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)단일 Excel 차트를 나타내는 데 사용됩니다.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel 차트를 이미지로 변환" %}}

 차트를 JPG, PNG, TIFF, BMP 등의 이미지로 변환하는 과정은[학습장](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Excel 파일을 로드하려면 해당 클래스를 선택하십시오.[작업 시트](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) 차트를 포함하거나 각 워크시트의 각 차트를 반복합니다. 정의하다[이미지 또는 인쇄 옵션](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) 다음을 사용하여 차트의 출력 이미지를 렌더링합니다.[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel 차트를 이미지로 변환하는 코드" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excel 파일 내에서 차트 만들기" %}}

 Excel API을 사용하여 차트를 만드는 것은 간단합니다. API은 다양한 종류의 차트에 대해 Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection 등과 같은 다양한 클래스 세트를 제공합니다. 프로세스는 Workbook 클래스 개체를 생성하고 해당 인덱스를 제공하여 첫 번째 워크시트 또는 해당 시트를 선택하는 것입니다. 차트의 데이터 소스의 경우 다음을 사용하여 워크시트 셀에 값을 삽입합니다.[설정값](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)방법. ChartCollection 컬렉션 사용[메소드 추가](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) 차트를 추가하려면 ChartType 열거형으로 차트 유형을 정의합니다. 해당 인덱스를 전달하여 ChartCollection 컬렉션에서 새 Chart 개체에 액세스합니다. 사용[시리즈컬렉션](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) 차트의 데이터 소스를 지정하는 차트 개체입니다.

{{% blocks/products/pf/feature-page-code h3="Java Excel 차트를 만드는 코드" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
