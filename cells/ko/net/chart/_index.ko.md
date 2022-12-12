---
title: Excel 차트 생성 및 .NET을 통한 이미지 변환

description: C# 소스 코드는 .NET 라이브러리를 사용하여 Microsoft Excel에서 차트 또는 다이어그램을 그리고 변환합니다. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> .NET을 통한 Excel 파일 차트 생성 및 변환" h2="Excel 문서 차트를 만들고 .NET 기반 애플리케이션 내에서 서버 측 API를 사용하여 이미지로 변환합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
차트 그리기는 쉽게 분석할 수 있도록 데이터를 그래픽으로 표시하는 예술입니다. [.NET 엑셀 라이브러리](/cells/net/) Excel 파일 내의 도면 차트를 지원합니다. API은(는) 다음에 나열된 다양한 차트 생성을 지원합니다. [차트 유형 열거](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) 파이, 피라미드, 꺾은선형 및 거품형 차트를 포함합니다. 또한 차트를 이미지로 변환합니다. API 제공 [차트 클래스](https://reference.aspose.com/cells/net/aspose.cells.charts) 차트 빌딩 블록용.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일 내에서 차트 만들기" %}}

Excel API을 사용하여 차트를 만드는 것은 간단합니다. 프로세스는 생성 [워크북 수업](https://reference.aspose.com/cells/net/aspose.cells/workbook) 개체를 선택하고 색인을 제공하여 첫 번째 워크시트 또는 관련 시트를 선택합니다. 다음을 사용하여 필요한 셀 데이터를 삽입하십시오. [PutValue 메서드](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Charts 컬렉션을 사용하여 워크시트에 차트 추가 [메소드 추가](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). 지정 [차트 유형](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) ChartType 열거에서.
{{% blocks/products/pf/feature-page-code h3="C# Excel 차트를 만드는 코드" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Excel 차트를 이미지로 변환" %}}

차트를 이미지로 변환하는 프로세스는 워크북 클래스를 사용하여 Excel 파일을 로드하고 차트가 포함된 관련 워크시트를 선택하고 [ToImage 메서드](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) 변환을 위해.

{{% blocks/products/pf/feature-page-code h3="C# Excel 차트를 이미지로 변환하는 코드" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
