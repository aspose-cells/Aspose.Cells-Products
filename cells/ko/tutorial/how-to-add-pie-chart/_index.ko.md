---
title: Aspose.Cells을 통해 원형 차트를 추가하는 방법
weight: 7700
limit:
description: 원형 차트를 추가하는 방법을 알아보세요.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /ko/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells로 원형 차트를 추가하는 방법 알아보기" >}}

<p>
이 자습서에서는 Excel 파일에 원형 차트를 추가합니다.
</p>

<p>
 다음을 사용하여 새 통합 문서를 만드는 것으로 시작합니다.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 도서관</a> 원형 차트를 추가합니다.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 원형 차트를 추가하는 방법은 다음 코드를 확인하세요.
//ExStepSummary:0: 다음 코드는 원형 차트를 추가하고 시리즈 데이터 범위를 설정하고 카테고리 데이터 범위를 설정하는 방법을 보여줍니다.
//ExStepImage:0:step-1.png
//ExStepSummary:1: 다음 코드는 범례를 끄는 방법을 보여줍니다.
//ExStepImage:1:step-2.png
//ExStepSummary:2: 다음 코드는 데이터 레이블에 액세스하고 범주 이름을 켜고 백분율 형식을 켜고 위치를 설정하는 방법을 보여줍니다.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cells 사용;
Aspose.Cells.도면 사용;

통합 문서 통합 문서 = new Workbook();
워크시트 시트 = workbook.Worksheets[0];
sheet.Name = "차트시트";
Cells 셀 = 시트.Cells;
cells["A1"].Value = "과일";
cells["A2"].Value = "사과";
cells["A3"].Value = "주황색";
cells["A4"].Value = "블루베리";
cells["A5"].Value = "키위";

cells["B1"].Value = "가격";
셀["B2"].값 = 10;
셀["B3"].값 = 5;
셀["B4"].값 = 20;
셀["B5"].값 = 8;

sheet.PageSetup.PrintGridlines = 참;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection 차트 = sheet.Charts;

//원형 차트 추가, 시리즈 데이터 범위 설정 및 카테고리 데이터 범위 설정
int index = sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
차트 차트 = sheet.Charts[인덱스];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//Ex단계:1-
//범례 끄기
chart.ShowLegend = 거짓;

//Ex단계:2-
//데이터 레이블에 액세스하고 범주 이름을 켜고 백분율 형식을 켜고 위치를 설정합니다.
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = 참;
dataLabels.ShowPercentage = 참;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Aspose.Cells 설치</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells 편집자</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}