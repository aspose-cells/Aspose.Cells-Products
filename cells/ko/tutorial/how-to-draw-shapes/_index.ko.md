---
title: Aspose.Cells을 통해 도형을 추가하는 방법
weight: 7700
limit:
description: 도형을 추가하는 방법을 알아보세요.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /ko/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells로 도형을 추가하는 방법 알아보기" >}}

<p>
이 튜토리얼에서는 Excel 파일에 모양을 추가합니다.
</p>

<p>
 다음을 사용하여 새 통합 문서를 만드는 것부터 시작하겠습니다.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 도서관</a> 그리고 모양을 추가하세요.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: 도형을 추가하는 방법은 다음 코드를 확인하세요.
//ExStepSummary:0: 다음 코드는 직사각형 모양을 추가하는 방법을 보여줍니다.
//ExStepImage:0:step-1.png
//ExStepSummary:1: 다음 코드는 선 모양을 추가하는 방법을 보여줍니다.
//ExStepImage:1:step-2.png
//ExStepSummary:2: 다음 코드는 타원형 모양을 추가하는 방법을 보여줍니다.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cells 사용;
Aspose.Cells.드로잉 사용;





통합 문서 통합 문서 = 새 통합 문서();
워크시트 시트 = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection 모양 = sheet.Shapes;

//사각형 모양 추가
모양.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//선 모양 추가
모양.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//타원형 추가
모양.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
학습장
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