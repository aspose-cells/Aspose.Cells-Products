---
title: Excel 파일 메타데이터 관리 via .NET C#
description: 단 몇 줄의 C# 코드만으로 Excel 파일 메타데이터 보기, 추가, 편집, 제거 또는 추출
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 파일 메타데이터 관리 via .NET" h2="서버측 .NET API를 사용하여 기본 제공 및 사용자 정의 Excel 파일 속성을 확인, 추가, 업데이트, 제거 또는 추출합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET 엑셀 API](/cells/ko/net/) 제목, 작성자 이름, 문서 통계 등과 같은 시스템 정의(내장) 속성과 이름-값 쌍 형태의 사용자 정의(사용자 정의) 속성 관리를 지원합니다. 있다[워크북 수업](https://reference.aspose.com/cells/net/aspose.cells/workbook) 파일을 로드하고[워크시트수집](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) 워크시트 모음을 처리합니다.[워크시트 수업](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 단일 워크시트를 표현하기 위한 것입니다. 이러한 클래스와 함께 BuildInDocumentProperties, CustomDocumentProperties는 메타데이터 관리 프로세스를 단순화합니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="내장 속성 관리" %}}

 시스템 정의 속성을 관리하기 위해 API은 다음을 제공합니다.[내장문서속성](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) 프로그래머는 내장 속성에 쉽게 액세스하고 해당 값을 업데이트할 수 있습니다. 애플리케이션 요구 사항에 따라 개발자는[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# 내장 속성을 관리하는 코드" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="사용자 정의 속성 관리" %}}

 사용자 정의 속성을 관리하기 위해 API은 다음을 제공합니다.[사용자 정의 문서 속성](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , 개발자는 이미 추가된 속성에 쉽게 액세스하고 새 속성을 추가할 수 있습니다. 사용자 정의 속성을 추가하려면,[메소드 추가](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ~의[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) 클래스는 속성을 추가하고 새 속성에 대한 참조를 반환합니다.[속성.문서속성](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) 물체. DocumentProperty 클래스는 문서 속성의 이름, 값 및 유형을 다음과 같이 검색하는 데 사용됩니다.[문서속성.이름](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.값](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [문서속성.유형](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) 다음 중 하나를 반환합니다.[속성 유형](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) 열거 값.
 
{{% blocks/products/pf/feature-page-code h3="C# Excel 파일에 메타데이터를 추가하는 코드" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Excel 파일에서 사용자 정의 속성을 제거하는 코드" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
