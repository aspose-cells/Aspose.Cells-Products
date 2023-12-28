---
title: Excel 차트 작성 및 이미지로 변환 via Java
description:  Java Java 라이브러리를 사용하여 Microsoft Excel에서 차트 또는 다이어그램을 그리고 변환하는 소스 코드입니다.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 차트 변환 및 생성 via Java" h2="Java 기반 애플리케이션 내에서 서버사이드 API를 이용해 엑셀 문서 차트를 이미지로 변환하고 다양한 차트를 생성할 수 있습니다." >}}


{{% blocks/products/pf/feature-page-summary %}}

 차트를 통해 데이터를 분석하면 더 큰 그림을 볼 수 있으며, 더 명확한 통찰력으로 더 많은 정보에 기초한 결정을 쉽게 내릴 수 있습니다.[Java 엑셀 라이브러리](/cells/ko/java/) 다음에 나열된 다양한 차트 생성 그리기를 지원합니다.[차트 유형](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) 원형, 피라미드, 선 및 거품형 차트를 포함합니다. 또한 차트를 이미지로 변환하기도 합니다. API은[차트 수업](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) 단일 Excel 차트를 표현하는 데 사용됩니다.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel 차트를 이미지로 변환" %}}

 차트를 JPG, PNG, TIFF, BMP 등의 이미지로 변환하는 과정은,[학습장](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Excel 파일을 로드하는 클래스에서 관련 항목을 선택합니다.[작업 시트](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) 차트를 포함하거나 각 워크시트의 각 차트를 반복합니다. 정의하다[이미지또는인쇄옵션](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) 다음을 사용하여 차트의 출력 이미지를 렌더링합니다.[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel 차트를 이미지로 변환하는 코드" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excel 파일 내에서 차트 만들기" %}}

API은 다양한 종류의 차트에 대해 Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection 등과 같은 다양한 클래스 세트를 제공하므로 Excel API을 사용하여 차트를 만드는 것은 간단합니다. 프로세스는 Workbook 클래스 개체를 생성하고 해당 인덱스를 제공하여 첫 번째 워크시트 또는 관련 시트를 선택하는 것입니다. 차트의 데이터 소스의 경우 다음을 사용하여 워크시트 셀에 값을 삽입합니다.[세트값](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) 방법. ChartCollection 컬렉션 사용[메소드 추가](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) 차트를 추가하려면 ChartType 열거로 차트 유형을 정의합니다. 해당 인덱스를 전달하여 ChartCollection 컬렉션에서 새 Chart 개체에 액세스합니다. 사용[시리즈컬렉션](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) 차트의 데이터 소스를 지정하는 차트 개체입니다.

{{% blocks/products/pf/feature-page-code h3="Java Excel 차트를 생성하는 코드" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
