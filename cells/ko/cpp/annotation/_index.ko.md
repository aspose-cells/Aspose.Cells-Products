---
title: C++을 통해 Excel 파일 주석 추가 또는 제거
description: C++ 라이브러리를 사용하여 Excel 및 OpenOffice 스프레드시트의 데이터 주석 주석을 추가하거나 제거합니다.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++을 통해 Excel 파일 주석 관리" h2="C++ 기반 애플리케이션 내에서 주석이나 설명에 대한 간단한 메모를 추가하거나 제거합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ 엑셀 API](/cells/ko/cpp/) 주석을 추가, 액세스 및 제거하여 셀 수준에서 주석을 관리할 수 있는 지원을 제공합니다. API 제공[논평](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) 그리고[댓글수집](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) 게다가[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)모든 측면에서 의견을 처리합니다. 지원되는 Excel 형식에는 ODS, XLS, XLSX, XLSB 및 XLSM이 포함됩니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일 데이터 주석" %}}
 워크시트에서 주석 조작 - MS Excel에서 시트에 있는 주석 수에는 제한이 없습니다. 응용프로그램에 필요한 만큼 삽입할 수 있습니다. 코멘트를 삽입하는 과정은 다음과 같습니다.[학습장](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) 클래스 개체를 사용하여 기존 파일을 로드하고 주석을 추가하려는 워크시트를 선택합니다. getComments()를 사용하여 모든 주석을 가져옵니다. 다음을 사용하여 주석을 추가합니다.[추가(const char16_t* 셀이름)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) 방법. 셀 인덱스를 가져와 사용[세트노트](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) 코멘트를 삽입하기 위한 것입니다. 게다가 API은 모든 댓글을 삭제할 수 있습니다. 몇 가지 방법은 다음과 같습니다.[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) 디자이너 스프레드시트의 모든 주석을 지웁니다. 게다가,***제거 위치*** 지정된 인덱스 또는 지정된 이름을 가진 요소를 제거하는 방법입니다.

{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일 내에 주석을 추가하는 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
