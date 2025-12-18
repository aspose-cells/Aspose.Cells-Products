---
title: Microsoft Chuyển đổi tệp Excel bằng Go qua C++
description: Sử dụng thư viện C++ cho Go. Chuyển đổi các định dạng EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG và nhiều định dạng khác chỉ với vài dòng mã Go thông qua thư viện C++.
keywords: [Go via C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Chuyển đổi tài liệu Excel với Go qua C++" h2="Lưu các tệp Excel có mã số Microsoft dưới dạng bảng tính, định dạng web, hình ảnh và định dạng bố cục cố định." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Đối với bất kỳ ứng dụng hoặc giải pháp chuyển đổi bảng tính nào,**Truy cập qua số C++ Thư viện Excel**Công cụ này giúp tăng tốc quá trình lập trình, tự động hóa và chuyển đổi khi xử lý nhiều tệp tin, bao gồm các định dạng XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép *chuyển đổi Excel sang các định dạng PDF*, XPS, HTML, MHTML, văn bản thuần túy và các hình ảnh phổ biến như JPG, TIFF, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi qua lại giữa các định dạng Excel Microsoft" %}}
 Việc chuyển đổi giữa các định dạng bảng tính chỉ cần tải bảng tính lên bằng cách sử dụng...[Sách bài tập](https://reference.aspose.com/cells/go-cpp/workbook/) lớp và lưu lại nó ở định dạng yêu cầu bằng cách sử dụng[Cứu](https://reference.aspose.com/cells/go-cpp/workbook/save_string/) phương pháp của[Sách bài tập](https://reference.aspose.com/cells/go-cpp//workbook/) lớp học.
{{% blocks/products/pf/feature-page-code h3="Truy cập mã ví dụ C++ để chuyển đổi định dạng tệp Excel." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)
// Load the source excel format.
workbook,_:= NewWorkbook_String("src_excel_file.xlsx")
// Save in required output format.
workbook.Save_String("output_excel_format.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi định dạng Excel sang PDF với cài đặt mức độ tuân thủ." %}}
 Truy cập qua C++ Excel Automation API hỗ trợ chuyển đổi Sổ làm việc sang PDF cũng như hỗ trợ thiết lập mức độ tuân thủ và ngày tạo. Các nhà phát triển có thể sử dụng[Tùy chọn lưu Pdf](https://reference.aspose.com/cells/go-cpp/pdfsaveoptions/)Để thiết lập tuân thủ PDF. Đối với chuyển đổi, phương thức lưu API có tham số PdfSaveOptions và đường dẫn tệp đầu ra được chỉ định.
{{% blocks/products/pf/feature-page-code h3="Truy cập mã mẫu C++ để chuyển đổi dữ liệu từ Excel sang PDF." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

workbook, _ := NewWorkbook()
worksheets, _ := workbook.GetWorksheets()
worksheet, _ := worksheets.Get_Int(0)
cells, _ := worksheet.GetCells()
cell, _ := cells.Get_String("A1")
cell.PutValue_Int(5)
cell, _ = cells.Get_String("A2")
cell.PutValue_Int(15)
cell, _ = cells.Get_String("A3")
cell.PutValue_Int(25)
workbook.Save_String("HELLO_Convert.pdf")
println("Finish to convert to PDF , check .pdf file in output folder.")


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Lưu Excel vào ảnh" %}}
**Truy cập qua số C++ Excel Parser** Có khả năng xuất dữ liệu dưới dạng hình ảnh. Mỗi bảng tính có thể được chuyển đổi sang các định dạng hình ảnh khác nhau, bao gồm BMP, JPEG, PNG và GIF, được thiết lập bởi...[Rendering::ImageOrPrintOptions](https://reference.aspose.com/cells/go-cpp/sheetrender/toimage_int_string/) Đối với bất kỳ**Chuyển đổi Excel thành hình ảnh** Chọn trường hợp phù hợp từ các liên kết.
{{% blocks/products/pf/feature-page-code h3="Vui lòng sử dụng mã C++ để chuyển đổi Excel sang hình ảnh." %}}

```go

package main

import (
    . "github.com/Aspose-Cells/aspose-cells-go-cpp/v25"
)

 // Load the XLSX.
    workbook, _ := NewWorkbook("source-excel-file.xlsx")

// Access first worksheet.
    worksheets, _ := workbook.GetWorksheets()
    worksheet, _ := worksheets.Get_Int(0)

// Create image or print options object.
    imgOptions, _ := NewImageOrPrintOptions()

// Specify the image format. Below code is for JPEG
    imgOptions.SetImageType(ImageType_Jpeg)

// Specify horizontal and vertical resolution
    imgOptions.SetHorizontalResolution(200)
    imgOptions.SetVerticalResolution(200)

// Render the sheet with respect to specified image or print options.
    sheetRender, _ := NewSheetRender(worksheet, imgOptions)

// Get page count.
    pageCount, _ := sheetRender.GetPageCount()

// Render each page to jpeg image one by one.
    for i := int32(0); i < pageCount; i++ {
        data, _ := sheetRender.ToImage_Int(i)
        filename := "Image" + string(i) + ".jpg"
        file, _ := os.OpenFile(filename, os.O_WRONLY|os.O_CREATE|os.O_APPEND, 0644)
        defer file.Close()
        file.Write(data)
    }

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
