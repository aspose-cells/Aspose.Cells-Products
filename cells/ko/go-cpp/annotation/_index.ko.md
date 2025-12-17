---
title: Go 앱을 사용하여 Excel 파일에 주석을 추가하거나 제거하려면 C++로 문의하세요.
description: Go 소프트웨어(C++ 라이브러리 사용)를 이용하여 Excel 및 OpenOffice 스프레드시트의 데이터 주석을 추가하거나 제거할 수 있습니다.
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Go를 통해 C++로 Excel 파일 주석을 관리하세요." h2="C++ 기반 애플리케이션을 통해 Go 내에서 주석이나 댓글을 위한 간단한 메모를 추가하거나 삭제할 수 있습니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++번으로 전화하거나 API번으로 전화하세요.](/cells/ko/go-cpp/) 셀 수준에서 주석을 추가, 액세스 및 삭제하여 주석을 관리할 수 있도록 지원합니다. API 제공[논평](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) 그리고[댓글 모음](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)게다가[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) 모든 측면에서 댓글을 처리합니다. 지원되는 Excel 형식은 ODS, XLS, XLSX, XLSB 및 XLSM입니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="엑셀 파일 데이터 주석" %}}
 워크시트의 주석 조작 - MS Excel에서는 시트에 주석을 몇 개나 넣을 수 있는지에 제한이 없습니다. 필요한 만큼 주석을 삽입할 수 있습니다. 주석 삽입 과정은 다음과 같습니다. 주석을 생성하고,[학습장](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) 클래스 객체를 사용하여 기존 파일을 불러오고 주석을 추가할 워크시트를 선택합니다. getComments()를 사용하여 해당 워크시트의 모든 주석을 가져옵니다. 그런 다음 주석을 추가합니다.[Add(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) 메서드입니다. 셀 인덱스를 가져와서 사용합니다.[SetNote](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) 댓글을 삽입하는 데 사용됩니다. 또한 API은 모든 댓글을 삭제할 수 있습니다. 몇 가지 방법은 다음과 같습니다.[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) 디자이너 스프레드시트의 모든 댓글을 지웁니다. 또한,***제거*** 지정된 인덱스 또는 지정된 이름을 가진 요소를 제거하는 메서드입니다.

{{% blocks/products/pf/feature-page-code h3="C++ 코드를 사용하여 엑셀 파일에 주석을 추가하세요." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
