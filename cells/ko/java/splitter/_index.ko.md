---
title: Java에서 Excel 스프레드시트를 워크시트로 분할
description: Java Java Excel 라이브러리를 사용하여 Microsoft Excel 파일을 여러 문서로 분할하는 방법을 설명하는 소스 코드
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 분할 via Java" h2="Java 기반 애플리케이션 내에서 Excel 스프레드시트를 워크시트로 분할" >}}
{{% blocks/products/pf/feature-page-summary %}}
각 학생에게 단일 시트를 할당하여 학생 데이터가 포함된 스프레드시트와 같이 Excel 파일을 분할해야 하는 경우 다양한 시나리오가 있습니다. 그리고 각 시트를 학생별로 별도의 파일로 분할해야 합니다. via Java 애플리케이션을 자동화하려면,[Java 엑셀 API](/cells/ko/java/) Excel 문서를 시트 단위로 분할하는 방법이 있습니다. 지원되는 형식에는 XLS, XLSX, XLSB, XLSM, ODS이 포함됩니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 문서를 여러 파일로 분할" %}}

 Excel 파일을 시트로 분할하는 가장 간단한 방법은 모든 시트에 액세스하여 각 시트를 반복하고 원하는 형식으로 하나씩 저장하는 것입니다. 워크시트를 로드하기 위해 API은 다음을 제공합니다.[학습장](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 수업.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) 메소드는 총 시트 수를 가져옵니다. 각 시트를 반복하고 사용[getWorksheets().get(시트 인덱스)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) 특정 시트에 접근하기 위해 다음을 사용하여 선택한 시트 데이터를 새로 생성된 통합 문서 클래스 개체로 이동합니다.[복사 방법](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). 마지막으로 필요한 형식으로 저장하십시오.

{{% blocks/products/pf/feature-page-code h3="Java Excel 파일을 분할하는 코드" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel 워크시트를 창으로 분할" %}}

API은 Excel 워크시트를 여러 창으로 분할하는 기능도 제공합니다. 프로세스는 Workbook 클래스를 사용하여 파일을 로드하는 것입니다. 색인을 제공하여 첫 번째 워크시트 또는 필요한 시트를 선택합니다. 해당 셀 인덱스를 가지는 setActiveCell을 파라미터로 호출합니다. 마지막으로 분할() 메서드를 호출하여 워크시트 창을 여러 창으로 분할합니다.

{{% blocks/products/pf/feature-page-code h3="Java Excel 시트를 창 보기로 분할하는 코드" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
