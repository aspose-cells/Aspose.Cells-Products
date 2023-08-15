---
title: C++을 통한 Excel 파일 주석
description: C++ 라이브러리를 사용하여 Excel 및 OpenOffice 스프레드시트의 데이터 주석 주석을 추가하거나 제거합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++을 통해 Excel 파일 주석 관리" h2="C++ 기반 애플리케이션 내에서 주석 또는 주석에 대한 간단한 메모를 추가하거나 제거합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ 엑셀 API](/cells/ko/cpp/) 주석을 추가, 액세스 및 제거하여 셀 수준에서 주석을 관리하는 지원을 제공합니다. API 제공[IComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) 그리고[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) 게다가[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)모든 측면에서 댓글을 처리합니다. 지원되는 Excel 형식에는 ODS, XLS, XLSX, XLSB 및 XLSM이 포함됩니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일 데이터 주석" %}}
 워크시트의 주석 조작 - MS Excel에서 시트의 주석 수에는 제한이 없습니다. 신청에 필요한 만큼 삽입할 수 있습니다. 댓글을 입력하는 과정은 생성입니다.[아이워크북](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스 개체를 사용하여 기존 파일을 로드하고 설명을 추가할 워크시트를 선택합니다. getComments()를 사용하여 모든 주석을 가져옵니다. 다음을 사용하여 주석을 추가하십시오.[추가하다](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > cellName) 메서드를 사용합니다. 셀 인덱스 가져오기 및 사용[setNote](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) 주석을 삽입합니다. 또한 API은 모든 댓글을 제거할 수 있습니다. 몇 가지 방법은 다음과 같습니다.[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to 디자이너 스프레드시트의 모든 주석을 지웁니다. 게다가,[제거시](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) 메서드를 사용하여 지정된 인덱스 또는 지정된 이름을 가진 요소를 제거합니다.

{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일 내에 주석을 추가하는 코드" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
