---
title: ادغام فایل های مختلف اکسل در یک واحد در Java
description: فایل های اکسل را با استفاده از Java در چندین برگه یا یک برگه ادغام کنید. اسناد اکسل را به PDF، Images و HTML ادغام، ترکیب یا الحاق کنید.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> ادغام فایل اکسل via Java" h2="دو یا چند فایل اکسل را با استفاده از کد Java در یک صفحه گسترده ترکیب کنید" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java کتابخانه اکسل](/cells/fa/java/)راه های متعددی برای ترکیب کتاب های کار با انواع مختلف محتوا مانند فرمول ها، تصاویر، داده ها، نمودارها و غیره در یک سند صفحه گسترده ارائه می دهد. فرمت های فایل پشتیبانی شده شامل XLS، XLSX، XLSB، XLT، XLTX، XLTM، ODS، CSV، CSV، CSV، CSV،
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="فایل های اکسل را با تصاویر و نمودارها ترکیب کنید" %}}
 ساده ترین راه برای ترکیب دو فایل اکسل دارای تصاویر و نمودارها، تماس با آن است[کتاب کار.ترکیب](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) روش. این اجازه می دهد تا فایل های اکسل از نوع مشابه را در یک صفحه گسترده ادغام کنید.
{{% blocks/products/pf/feature-page-code h3="Java کد برای ترکیب فایل های اکسل" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ادغام چندین فایل اکسل" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) روش از ادغام داده‌ها، سبک و فرمول‌های یک فایل اکسل در یک صفحه گسترده جدید با همان فرمت پشتیبانی می‌کند. این یک راه کارآمد برای ادغام چندین فایل در حین استفاده از کش است.
{{% blocks/products/pf/feature-page-code h3="Java کد برای ادغام چندین فایل اکسل" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ادغام فایل های اکسل با کپی کردن کاربرگ ها" %}}
[کاربرگ.کپی](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)می تواند برای کپی داده ها و قالب بندی از یک کاربرگ منبع به کاربرگ دیگر در داخل یا بین کتاب های کار استفاده شود. متد شیء کاربرگ منبع را به عنوان پارامتر می گیرد.
{{% blocks/products/pf/feature-page-code h3="Java کد برای کپی کاربرگ ها بین کتاب های کار" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های ادغام پشتیبانی شده" subTitle="با استفاده از Java، One می تواند بسیاری از فرمت های فایل دیگر از جمله ..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="مقادیر جدا شده با کاما" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="فرمت آرشیو صفحه وب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="فایل صفحه گسترده OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="مقادیر جدا شده از تب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="سند متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="فایل باینری کتاب کار اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="فایل OOXML اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft قالب اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="قالب ماکرو فعال اکسل" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
