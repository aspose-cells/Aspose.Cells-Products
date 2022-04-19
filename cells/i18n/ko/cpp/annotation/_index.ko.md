---
title: C++을 통한 Excel 파일 주석
url: /ko/cpp/annotation/
description: C++ 라이브러리를 사용하여 Excel 및 OpenOffice 스프레드시트의 데이터 주석 주석을 추가하거나 제거합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++을(를) 통해 Microsoft<sup>&reg;</sup> Excel 파일 주석 관리" h2="C++ 기반 애플리케이션 내에서 주석 또는 주석에 대한 간단한 메모를 추가하거나 제거합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ 엑셀 API](/cells/cpp/) 주석을 추가, 액세스 및 제거하여 셀 수준에서 주석을 관리하기 위한 지원을 제공합니다. API 제공 [I코멘트](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) 그리고 [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) 만큼 잘 [GetIComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) 모든 측면에서 의견을 처리합니다. 지원되는 Excel 형식에는 ODS, XLS, XLSX, XLSB 및 XLSM이 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일 데이터 주석" %}}
워크시트에서 주석 조작하기 - MS Excel에서 시트의 주석 수에는 제한이 없습니다. 응용 프로그램에 필요한 만큼 삽입할 수 있습니다. 주석을 삽입하는 과정은 생성 [아이워크북](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스 개체를 사용하여 기존 파일을 로드하고 주석을 추가할 워크시트를 선택합니다. getComments()를 사용하여 모든 주석을 가져옵니다. 다음을 사용하여 주석 추가 [추가하다](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) 메서드. 셀 인덱스 가져오기 및 사용 [세트노트](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) 주석을 삽입하기 위한 것입니다. 또한 API은(는) 모든 주석을 제거할 수 있습니다. 몇 가지 방법은 다음과 같습니다. [ClearComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) 디자이너 스프레드시트의 모든 주석을 지웁니다. 더구나, [제거 위치](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) 메서드를 사용하여 지정된 인덱스 또는 지정된 이름의 요소를 제거합니다.

{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일 내에 주석을 추가하는 코드" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}