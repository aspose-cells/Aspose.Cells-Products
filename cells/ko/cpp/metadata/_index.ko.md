---
title: C++을 통해 Excel 파일 메타데이터 관리
description: C++ 라이브러리를 사용하여 Excel 파일 메타데이터 보기, 추가, 편집, 제거 또는 추출
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++을 통해 Microsoft<sup>&reg;</sup> Excel 문서 메타데이터 관리" h2="C++ 애플리케이션 내에서 사용자 정의 및 기본 제공 Excel 문서 속성을 보고, 삽입하고, 업데이트하고, 제거하거나 추출합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel의 메타데이터 - Excel 파일 메타데이터를 보고, 삽입하고, 제거하는 방법입니다.[C++ 엑셀 라이브러리](/cells/ko/cpp/) 작성자 이름, 제목, 문서 통계 등과 같은 내장/시스템 정의 속성을 지원하여 마지막으로 파일이 수정되거나 저장되는 시기를 다음과 같은 형식의 사용자 정의/사용자 정의 속성과 함께 확인하는 등의 작업을 쉽게 수행할 수 있습니다. 이름/값 쌍. 프로세스를 자동화하기 위해 라이브러리는 대규모 메타데이터 Excel 파일 생성 및 유지 관리를 지원합니다.[학습장](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class 경로, 스트림 및 특수 FileFormatType별로 통합 문서를 엽니다. 따라서 추가 처리를 위해 적절한 방법으로 파일을 로드하십시오. 아래 나열된 가능성은 거의 없으며 개발자는 애플리케이션 요구 사항에 따라 코드를 쉽게 향상시킬 수 있습니다.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="내장 속성 읽기 및 업데이트" %}}

 내장 속성을 자동화하기 위해 API은 다음을 제공합니다.[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) 스프레드시트의 모든 내장 문서 속성을 나타내는 DocumentProperties 컬렉션을 반환하는 메서드입니다. 모든 내장 속성에 접근한 후 GetTitle(), GetSubject() 등의 해당 메소드를 사용하여 해당 속성에 접근합니다. 속성을 업데이트하기 위해 API에서는 SetTitle, SetSubject, SetAuthor, SetComments 등의 메소드를 제공합니다.[내장 문서 속성 컬렉션](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) 필요한 기능을 위해.

{{% blocks/products/pf/feature-page-code h3="C++ 시스템 정의 속성을 읽는 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ 내장 속성을 업데이트하는 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="사용자 정의 속성 보기 및 추가" %}}

사용자 정의 속성을 처리하기 위해 API은 다음을 제공합니다.[통합 문서::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) 스프레드시트의 모든 사용자 정의 문서 속성 컬렉션을 반환합니다. 먼저 이 메서드를 통해 사용자 정의 속성에 액세스하면 개발자는 관련 메서드를 사용하여 AddIDocumentProperty, AddLinkToContentProperty와 같은 속성을 추가할 수 있으며 마찬가지로 UpdateLinkedPropertyValue, UpdateLinkedRange를 사용하여 각각 콘텐츠 및 연결된 범위에 연결되는 사용자 정의 문서 속성 값을 업데이트할 수 있습니다. 개발자는 다음의 관련 방법을 사용할 수 있습니다.[사용자 정의 문서 속성 컬렉션](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ 사용자 정의 속성을 보기 위한 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Excel 파일에 메타데이터를 추가하는 코드" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
