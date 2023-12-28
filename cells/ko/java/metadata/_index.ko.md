---
title: Excel 파일 메타데이터 관리 via Java
description: 단 몇 줄의 Java 코드만으로 Excel 파일 메타데이터 보기, 추가, 편집, 제거 또는 추출
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 메타데이터 관리 via Java" h2="서버측 Java API를 사용하여 사용자 정의 및 기본 제공 Excel 파일 속성을 확인, 추가, 업데이트, 삭제 또는 추출합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java 엑셀 API](/cells/ko/java/) 제목, 작성자 이름, 문서 통계 등과 같은 내장(시스템 정의) 속성과 이름/값 쌍 형태의 사용자 정의(사용자 정의) 속성의 관리를 지원합니다. 있다[워크북 수업](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 파일을 로드하고[워크시트수집](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) 워크시트 모음을 처리합니다.[워크시트 수업](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) 단일 워크시트를 표현하기 위한 것입니다. 내장 및 사용자 정의 속성에 액세스하기 위해 BuildInDocumentProperties, CustomDocumentProperties를 사용하면 메타데이터 관리 프로세스가 간단해집니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="시스템 정의 속성 관리" %}}

 내장 속성 관리를 위해 API은 다음을 제공합니다.[내장문서속성](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) 프로그래머는 내장 속성에 쉽게 액세스하고 해당 값을 업데이트할 수 있습니다. 애플리케이션 요구 사항에 따라 개발자는[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java 시스템 정의 속성을 관리하는 코드" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="사용자 정의 메타데이터 추가 및 제거" %}}

사용자 정의 속성을 처리하기 위해 API은 다음을 제공합니다.[사용자 정의 문서 속성](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , 개발자는 기존 속성에 쉽게 액세스하고 다음을 사용하여 새 속성을 추가할 수 있습니다.[메소드 추가](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) 의[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) 클래스는 속성을 추가하고 새 속성에 대한 참조를 반환합니다.[속성.문서속성](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) 물체. DocumentProperty 클래스는 문서 속성의 이름, 값 및 유형을 다음과 같이 검색하는 데 사용됩니다.[문서속성.이름](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.값](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [문서속성.유형](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) 다음 중 하나를 반환합니다.[속성 유형](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) 열거 값.
 
{{% blocks/products/pf/feature-page-code h3="Java Excel 파일에 메타데이터를 추가하는 코드" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Excel 파일에서 사용자 정의 속성을 삭제하는 코드" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
