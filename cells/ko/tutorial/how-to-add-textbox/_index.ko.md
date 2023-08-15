---
title: Aspose.Cells을 통해 TextBox를 추가하는 방법
weight: 7700
limit:
description: TextBox를 추가하는 방법을 알아보세요.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /ko/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells로 TextBox를 추가하는 방법 알아보기" >}}

<p>
이 자습서에서는 Excel 파일에 TextBox를 추가합니다.
</p>

<p>
 다음을 사용하여 새 통합 문서를 만드는 것으로 시작합니다.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 도서관</a> TextBox를 추가합니다.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: TextBox를 추가하는 방법은 다음 코드를 확인하세요.
//ExStepSummary:0: 다음 코드는 TextBox를 추가하고 텍스트를 설정하는 방법을 보여줍니다.
//ExStepImage:0:step-1.png
//ExStepSummary:1: 다음 코드는 텍스트 색상을 변경하는 방법을 보여줍니다.
//ExStepImage:1:step-2.png
//ExStepSummary:2: 다음 코드는 TextBox의 회전 각도를 변경하는 방법을 보여줍니다.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cells 사용;
Aspose.Cells.도면 사용;

통합 문서 통합 문서 = new Workbook();
워크시트 시트 = workbook.Worksheets[0];
sheet.PageSetup.PrintGridlines = 참;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection 도형 = sheet.Shapes;

//TextBox 추가 및 텍스트 설정
TextBox textBox = shapes.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET은 소프트웨어 개발자가 자신의 응용 프로그램 내에서 스프레드시트 파일을 조작하고 처리할 수 있도록 하는 프로그래밍 클래스 라이브러리입니다.";

//Ex단계:1-
//텍스트 색상 변경
textBox.Font.Color = 색상.파란색;

//Ex단계:2-
//TextBox의 회전 각도 변경
textBox.RotationAngle = 90;

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