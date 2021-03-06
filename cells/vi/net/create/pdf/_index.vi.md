---
title: Tạo Tệp PDF qua C# 
url: /vi/net/create-pdf/ 
description: C# Mã mẫu để tạo tài liệu PDF. Sử dụng mã này để tạo tệp PDF trong VB .NET, Asp .NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Tạo Tài liệu PDF qua C#" h2="Tạo tệp PDF gốc và hiệu suất cao (Định dạng tài liệu di động) theo chương trình bằng cách sử dụng .NET API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Dễ dàng tạo tệp PDF động trong ứng dụng đang chạy. Để tạo tài liệu PDF từ đầu mà không yêu cầu MS Office, chúng tôi sẽ sử dụng
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API cung cấp các tính năng khác nhau để tạo, thao tác và chuyển đổi bảng tính bằng cách sử dụng nền tảng .NET. Các nhà phát triển có thể dễ dàng nâng cao mã để viết dữ liệu, tạo biểu đồ hoặc đồ thị cũng như tạo bảng trong bảng tính.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo PDF qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Các nhà phát triển có thể dễ dàng tạo, tải, sửa đổi và chuyển đổi PDF (Định dạng Tài liệu Di động) trong khi chạy các ứng dụng báo cáo khác nhau để xử lý dữ liệu chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Bao gồm không gian tên trong tệp lớp của bạn1. Tạo cá thể lớp Workbook.1. Truy cập trang tính đầu tiên của sổ làm việc.1. Lấy (các) ô mong muốn của trang tính và nhập giá trị vào (các) ô đó.1. Sử dụng phương pháp Lưu để lưu sổ làm việc dưới dạng tệp PDF.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Chỉ cần đảm bảo rằng hệ thống đó có Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platform cũng như môi trường phát triển như Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Cài đặt từ dòng lệnh dưới dạng <code>nuget install Aspose.Cells</code> hoặc thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với <code>Install-Package Aspose.Cells</code>.- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc tất cả DLL trong tệp ZIP từ <a href="https://downloads.aspose.com/cells/net">tải xuống</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã nguồn sau đây cho biết cách tạo tệp PDF bằng C#." offSpacer="" %}}

```cs

// Tạo cá thể lớp Workbook.
Workbook wkb = new Workbook();

// Truy cập trang tính đầu tiên của sổ làm việc.
Worksheet sht = wkb.Worksheets[0];

// Nhận (các) ô mong muốn của trang tính.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// nhập giá trị vào (các) ô.
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Lưu Sổ làm việc dưới dạng tệp .pdf.
wkb.Save("created_one.pdf");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Thư viện Lập trình Bảng tính Excel có khả năng xây dựng các ứng dụng đa nền tảng với khả năng tạo, sửa đổi, chuyển đổi, hiển thị và in các tệp PDF. .NET Excel API không chỉ chuyển đổi giữa các định dạng bảng tính, nó còn có thể hiển thị các tệp Excel dưới dạng hình ảnh, PDF, HTML, ODS và hơn thế nữa, do đó, nó trở thành lựa chọn hoàn hảo để trao đổi tài liệu ở các định dạng tiêu chuẩn của ngành.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" >}}
Định dạng tài liệu di động (PDF) là một loại tài liệu được tạo bởi Adobe vào những năm 1990. Mục đích của định dạng tệp này là giới thiệu một tiêu chuẩn để trình bày tài liệu và tài liệu tham khảo khác ở định dạng độc lập với phần mềm ứng dụng, phần cứng cũng như Hệ điều hành. Định dạng tệp PDF có đầy đủ khả năng chứa thông tin như văn bản, hình ảnh, siêu liên kết, trường biểu mẫu, đa phương tiện, chữ ký số, tệp đính kèm, siêu dữ liệu, các tính năng không gian địa lý và các đối tượng 3D trong đó có thể trở thành một phần của tài liệu nguồn.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Tạo bảng tính được hỗ trợ khác" subTitle="Bạn cũng có thể tạo các định dạng Microsoft Excel khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Bảng tính Microsoft Excel (Kế thừa)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="Mở sổ làm việc XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Sổ làm việc Nhị phân Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="Bảng tính hỗ trợ macro" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Mẫu Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Mẫu Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Mẫu được bật macro trong Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="Các giá trị được phân tách bằng dấu phẩy" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="TSV" description="Các giá trị được phân tách bằng tab" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="ODS" description="Bảng tính OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
