---
title: Java에서 여러 Excel 파일을 단일 파일로 병합
url: /ko/java/merger/
description: Java을(를) 사용하여 Excel 파일을 여러 시트 또는 단일 시트로 병합합니다. Excel 문서를 PDF, 이미지 및 HTML로 병합, 결합 또는 연결합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java을 통한 Microsoft<sup>&reg;</sup> Excel 파일 병합" h2="Java 코드를 사용하여 두 개 이상의 Excel 파일을 단일 스프레드시트에 결합" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java 엑셀 라이브러리](/cells/java/) 수식, 이미지, 데이터, 차트 등과 같은 다양한 유형의 콘텐츠가 포함된 통합 문서를 단일 스프레드시트 문서로 결합하는 여러 방법을 제공합니다. 지원되는 파일 형식에는 XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV 등이 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일을 이미지 및 차트와 결합" %}}
이미지와 차트가 있는 두 개의 Excel 파일을 결합하는 가장 간단한 방법은 [통합 문서.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) 방법. 유사한 유형의 Excel 파일을 단일 스프레드시트로 병합할 수 있습니다.
{{% blocks/products/pf/feature-page-code h3="Java Excel 파일을 결합하는 코드" %}}

```cs
// 첫 번째 Excel 파일 로드
var book1 = new Workbook("with-charts.xlsx");
// 두 번째 Excel 파일을 별도의 인스턴스로 로드
var book2 = new Workbook("with-images.xlsx");

// 두 통합 문서 병합
book1.combine(book2);
// 대상 통합 문서 저장 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="여러 Excel 파일 병합" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) 이 방법은 Excel 파일의 데이터, 스타일 및 공식을 동일한 형식의 새 스프레드시트로 병합하는 것을 지원합니다. 캐싱을 사용하면서 여러 파일을 병합하는 효율적인 방법입니다. 
{{% blocks/products/pf/feature-page-code h3="Java 여러 Excel 파일을 병합하는 코드" %}}

```cs
// 배열 생성(길이=2)
String[] files = new String[2];
// 병합할 파일 경로 지정
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// 결과를 저장하기 위해 파일을 병합
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="워크시트를 복사하여 Excel 파일 병합" %}}
[워크시트.복사](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)데이터 및 서식을 원본 워크시트에서 통합 문서 내 또는 통합 문서 간에 다른 워크시트로 복사하는 데 사용할 수 있습니다. 이 메서드는 원본 워크시트 개체를 매개 변수로 사용합니다.
{{% blocks/products/pf/feature-page-code h3="Java 통합 문서 간에 워크시트를 복사하는 코드" %}}

```cs
// 통합 문서를 만듭니다.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// 다른 통합 문서를 만듭니다.
Workbook excelWorkbook1 = new Workbook();

// 첫 번째 책의 첫 번째 시트를 두 번째 책에 복사합니다.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// 파일을 저장합니다.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}