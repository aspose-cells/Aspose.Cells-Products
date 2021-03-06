---
title: Chuyển đổi XLTX sang Mảng Byte qua C# 
weight: 7690
url: /vi/net/conversion/xltx-to-byte-array/ 
description: C# Mã mẫu để chuyển đổi XLTX sang Mảng Byte. Sử dụng mã này để chuyển đổi Excel XLTX sang Mảng Byte trong VB .NET, Asp .NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển XLTX thành mảng byte qua C#" h2="Chuyển đổi Microsoft Excel XLTX sang mảng byte gốc và hiệu suất cao hoặc ngược lại để xử lý dữ liệu bảng tính bằng cách sử dụng .NET API phía máy chủ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array rất hữu ích cho việc xử lý hoặc lưu trữ dữ liệu. Bạn có thể chuyển đổi tệp XLTX thành Mảng Byte cũng như tài liệu ** Mảng Byte sang XLTX ** bằng ngôn ngữ C#. Để chuyển XLTX sang mảng byte, chúng tôi sẽ sử dụng
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API cung cấp các tính năng khác nhau để thao tác và chuyển đổi tài liệu bằng nền tảng .NET. 
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển XLTX sang Mảng Byte qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Các nhà phát triển có thể dễ dàng tải và chuyển đổi các tệp XLTX sang mảng byte cho các tác vụ thao tác tiếp theo chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Bao gồm không gian tên trong tệp lớp của bạn1. Tải tệp XLTX đầu vào bằng Workbook1. Khởi tạo đối tượng MemoryStream1. Chuyển đổi dữ liệu luồng thành mảng byte1. Xử lý dữ liệu theo yêu cầu của bạn
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Chỉ cần đảm bảo rằng hệ thống đó có Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Windows Azure, Mono hoặc Xamarin Platform cũng như môi trường phát triển như Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Cài đặt từ dòng lệnh dưới dạng <code>nuget install Aspose.Cells</code> hoặc thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với <code>Install-Package Aspose.Cells</code>.- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc tất cả DLL trong tệp ZIP từ <a href="https://downloads.aspose.com/cells/net">tải xuống</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị XLTX sang mảng byte C# Chuyển đổi" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xltx");

//Lưu sổ làm việc trong luồng bộ nhớ
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xltx);

//Đọc byte từ luồng bộ nhớ
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Xử lý dữ liệu mảng byte luồng bộ nhớ theo yêu cầu của bạn 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

Thư viện lập trình bảng tính Excel có khả năng xây dựng các ứng dụng đa nền tảng với khả năng tạo, sửa đổi, chuyển đổi, kết xuất và in tất cả các tệp Excel. .NET Excel API không chỉ chuyển đổi giữa các định dạng bảng tính, nó còn có thể hiển thị các tệp Excel bao gồm XLTX dưới dạng hình ảnh, PDF, HTML, ODS và hơn thế nữa, do đó nó trở thành lựa chọn hoàn hảo để trao đổi tài liệu ở các định dạng tiêu chuẩn của ngành.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}
Tệp có phần mở rộng .xltx đại diện cho tệp Mẫu Microsoft Excel dựa trên đặc điểm định dạng tệp Office OpenXML. Nó được sử dụng để tạo tệp mẫu tiêu chuẩn có thể được sử dụng để tạo tệp XLSX có cùng cài đặt như được chỉ định trong tệp XLTX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}


<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi các định dạng tệp khác thành mảng byte hoặc ngược lại, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS sang mảng Byte" description="Bảng tính Microsoft Excel (Kế thừa)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX sang mảng Byte" description="Mở sổ làm việc XML" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB sang mảng Byte" description="Sổ làm việc Nhị phân Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM sang mảng Byte" description="Bảng tính hỗ trợ macro" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT sang mảng Byte" description="Mẫu Excel 97 - 2003" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX sang mảng Byte" description="Mẫu Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM sang mảng Byte" description="Mẫu được bật macro trong Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV sang mảng Byte" description="Các giá trị được phân tách bằng dấu phẩy" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV sang mảng Byte" description="Các giá trị được phân tách bằng tab" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS sang mảng Byte" description="Bảng tính OpenDocument" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS sang PDF" description="Định dạng tài liệu di động" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS sang HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX đến XPS" description="Tệp Microsoft Excel OOXML Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX sang HTML" description="Tệp Excel OOXML" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX đến SVG" description="Đồ họa vector có thể mở rộng" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS sang JPEG" description="Hình ảnh JPEG" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}