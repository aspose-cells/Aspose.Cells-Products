---
title: C++을(를) 통해 Excel 파일 메타데이터 관리

description: C++ 라이브러리를 사용하여 Excel 파일 메타데이터 보기, 추가, 편집, 제거 또는 추출
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++을(를) 통해 Microsoft<sup>&reg;</sup> Excel 문서 메타데이터 관리" h2="C++ 애플리케이션 내에서 사용자 정의 및 기본 제공 Excel 문서 속성 보기, 삽입, 업데이트, 제거 또는 추출" >}}
{{% blocks/products/pf/feature-page-summary %}}
Excel의 메타데이터 - Excel 파일 메타데이터를 보고, 삽입하고, 제거하는 방법. [C++ 엑셀 라이브러리](/cells/cpp/) 사용자 정의/사용자 정의 속성과 함께 마지막으로 파일이 수정되거나 저장되는 시점을 확인하는 것처럼 언젠가 필요한 작성자 이름, 제목, 문서 통계 등과 같은 내장/시스템 정의 속성을 지원하여 용이하게 합니다. 이름/값 쌍. 프로세스를 자동화하기 위해 라이브러리는 대용량 메타데이터 Excel 파일 생성 및 유지 관리를 지원합니다. [CreateIWorkbook 메서드](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) ~의 [팩토리 클래스](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) 경로, 스트림 및 특수 FileFormatType별로 통합 문서를 엽니다. 따라서 추가 처리를 위해 적절한 방법으로 파일을 로드하십시오. 아래 나열된 가능성은 거의 없으며 개발자는 응용 프로그램 요구 사항에 따라 코드를 쉽게 향상시킬 수 있습니다. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="내장 속성 읽기 및 업데이트" %}}

기본 제공 속성을 자동화하기 위해 API는 다음을 제공합니다. [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) 스프레드시트의 모든 기본 제공 문서 속성을 나타내는 DocumentProperties 컬렉션을 반환하는 메서드입니다. 모든 기본 제공 속성에 액세스한 후 GetTitle(), GetSubject() 등과 같은 관련 메서드를 사용하여 관련 속성에 액세스합니다. 속성을 업데이트하기 위해 API은 SetTitle, SetSubject, SetAuthor, SetComments 등과 같은 메서드를 제공합니다. 보기 [내장 문서 속성 컬렉션](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) 필요한 기능을 위해.

{{% blocks/products/pf/feature-page-code h3="C++ 시스템 정의 속성을 읽는 코드" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ 내장 속성을 업데이트하는 코드" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="사용자 정의 속성 보기 및 추가" %}}

사용자 정의 속성을 처리하기 위해 API는 다음을 제공합니다. [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) 스프레드시트의 모든 사용자 지정 문서 속성 컬렉션을 반환합니다. 먼저 이 메서드를 통해 사용자 지정 속성에 액세스하면 개발자는 관련 메서드를 사용하여 AddIDocumentProperty, AddLinkToContentProperty와 같은 속성을 추가하고 마찬가지로 UpdateLinkedPropertyValue, UpdateLinkedRange를 사용하여 콘텐츠 및 연결된 범위에 각각 연결되는 사용자 지정 문서 속성 값을 업데이트할 수 있습니다. 개발자는 다음에서 관련 방법을 사용할 수 있습니다. [사용자 정의 문서 속성 모음](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ 맞춤 속성을 보기 위한 코드" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일에 메타데이터를 추가하는 코드" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
