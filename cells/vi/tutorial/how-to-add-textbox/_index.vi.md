---
title: Cách thêm TextBox qua Aspose.Cells
weight: 7700
limit:
description: Tìm hiểu cách thêm TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /vi/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Tìm hiểu cách thêm TextBox bằng Aspose.Cells" >}}

<p>
Trong hướng dẫn này, chúng ta sẽ thêm TextBox vào một tệp excel.
</p>

<p>
 Chúng ta sẽ bắt đầu bằng cách tạo một sổ làm việc mới bằng cách sử dụng<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells thư viện</a> và thêm TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Vui lòng kiểm tra đoạn mã sau để tìm hiểu cách thêm TextBox.
//ExStepSummary:0: Đoạn mã sau cho biết cách thêm TextBox và đặt văn bản.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Đoạn mã sau cho biết cách thay đổi màu của văn bản.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Đoạn mã sau cho biết cách thay đổi góc xoay của TextBox.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
sử dụng Aspose.Cells;
sử dụng Aspose.Cells.Bản vẽ;

Sổ làm việc của sổ làm việc = Sổ làm việc mới();
Trang tính = bảng tính.Worksheets[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

Hình dạng ShapeCollection = sheet.Shapes;

//Thêm TextBox và đặt văn bản
TextBox textBox = hình dạng.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET là thư viện lớp lập trình cho phép các nhà phát triển phần mềm thao tác và xử lý các tệp bảng tính trong ứng dụng của riêng họ.";

//ExStep:1-
//Thay đổi màu của văn bản
textBox.Font.Color = Color.Blue;

//ExStep:2-
//Thay đổi góc xoay của TextBox
textBox.RotationAngle = 90;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Lắp đặt Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Biên tập viên</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}