---
title: Aspose.Cells을 통해 세로 막대형 차트를 추가하는 방법
weight: 7700
limit:
description: 세로 막대형 차트를 추가하는 방법을 알아보세요.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /ko/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells로 세로 막대형 차트를 추가하는 방법 알아보기" >}}

<p>
이번 튜토리얼에서는 엑셀 파일에 세로 막대형 차트를 추가해 보겠습니다.
</p>

<p>
 다음을 사용하여 새 통합 문서를 만드는 것부터 시작하겠습니다.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 도서관</a> 그리고 세로 막대형 차트를 추가하세요.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 세로 막대형 차트를 추가하는 방법은 다음 코드를 확인하세요.
//ExStepSummary:0: 다음 코드는 세로 막대형 차트를 추가하는 방법을 보여줍니다.
//ExStepImage:0:step-1.png
//ExStepSummary:1: 다음 코드는 범례를 왼쪽으로 이동하고 범례의 글꼴 색상을 설정하는 방법을 보여줍니다.
//ExStepImage:1:step-2.png
//ExStepSummary:2: 다음 코드는 차트 제목을 설정하고 글꼴 색상을 파란색으로 변경하는 방법을 보여줍니다.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cells 사용;
Aspose.Cells.드로잉 사용;

통합 문서 통합 문서 = 새 통합 문서();
워크시트 시트 = workbook.Worksheets[0];
sheet.Name = "차트시트";
Cells 셀 = 시트.Cells;
세포["A1"].Value = "과일";
셀["A2"].Value = "사과";
셀["A3"].Value = "주황색";
셀["A4"].Value = "블루베리";
셀["A5"].Value = "키위";

셀["B1"].Value = "가격";
셀["B2"].값 = 10;
셀["B3"].값 = 5;
셀["B4"].값 = 20;
셀["B5"].값 = 8;

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection 차트 = sheet.Charts;

//열 차트 추가
int index =charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
차트 차트 = 차트[색인];

//ExStep:1-
//범례를 왼쪽으로 이동하고 범례의 글꼴 색상을 설정합니다.
Chart.Legend.Font.Color = Color.Blue;
차트.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//차트 제목을 설정하고 글꼴 색상을 파란색으로 변경합니다.
Chart.Title.Text = "과일 가격 컬럼 차트";
Chart.Title.Font.Color = Color.Blue;

//ExStep:0-

//종료
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