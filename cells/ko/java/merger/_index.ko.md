---
title: Java에서 다른 Excel 파일을 단일 파일로 병합
description: Java을 사용하여 Excel 파일을 여러 시트 또는 단일 시트로 병합합니다. Excel 문서를 PDF, 이미지 및 HTML에도 병합, 결합 또는 연결합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 병합 via Java" h2="Java 코드를 사용하여 두 개 이상의 Excel 파일을 단일 스프레드시트에 결합" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java 엑셀 라이브러리](/cells/ko/java/) 수식, 이미지, 데이터, 차트 등과 같은 다양한 유형의 콘텐츠가 포함된 통합 문서를 단일 스프레드시트 문서로 결합하는 여러 가지 방법을 제공합니다. 지원되는 파일 형식에는 XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV 등이 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일을 이미지 및 차트와 결합" %}}
 이미지와 차트가 있는 두 개의 Excel 파일을 결합하는 가장 간단한 방법은[통합 문서.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) 방법. 유사한 유형의 Excel 파일을 단일 스프레드시트로 병합할 수 있습니다.
{{% blocks/products/pf/feature-page-code h3="Java Excel 파일을 결합하는 코드" %}}

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

{{% blocks/products/pf/feature-page-section h2="여러 Excel 파일 병합" %}}
[CellsHelper.merge파일](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) 방법은 Excel 파일의 데이터, 스타일 및 수식을 동일한 형식의 새 스프레드시트로 병합하는 것을 지원합니다. 캐싱을 사용하면서 여러 파일을 병합하는 효율적인 방법입니다.
{{% blocks/products/pf/feature-page-code h3="Java 여러 Excel 파일을 병합하는 코드" %}}

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

{{% blocks/products/pf/feature-page-section h2="워크시트를 복사하여 Excel 파일 병합" %}}
[워크시트.복사](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) 통합 문서 내에서 또는 통합 문서 간에 원본 워크시트에서 다른 워크시트로 데이터 및 서식을 복사하는 데 사용할 수 있습니다. 이 메서드는 원본 워크시트 개체를 매개 변수로 사용합니다.
{{% blocks/products/pf/feature-page-code h3="Java 통합 문서 간에 워크시트를 복사하는 코드" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 병합 형식" subTitle="Java을 사용하면 .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="쉼표로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="웹 페이지 아카이브 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument 스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="탭으로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="텍스트 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="엑셀 이진 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="이진 Excel 통합 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML 엑셀 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft 엑셀 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel 매크로 사용 템플릿" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
