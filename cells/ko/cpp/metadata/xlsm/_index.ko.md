---
title: C++을(를) 통해 XLSM 문서 메타데이터 편집 또는 보기 
weight: 1300
url: /ko/cpp/metadata/xlsm/ 
description: C++ Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ Runtime Environment에서 XLSM 파일 메타데이터를 편집하거나 보기 위한 예제 코드.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 XLSM 메타데이터 추출" h2="서버 측 API를 사용하여 XLSM 파일에서 메타데이터를 추가, 편집, 제거 또는 추출하는 고유한 C++ 앱을 빌드합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++을 사용하여 XLSM 메타데이터를 가져오는 방법" %}}

 XLSM 메타데이터를 추출하기 위해
 [C++에 대한 Aspose.Cells](https://products.aspose.com/cells/cpp) 
 API은(는) C++ 플랫폼용으로 기능이 풍부하고 강력하며 사용하기 쉬운 문서 메타데이터 추출API입니다. 최신 버전을 직접 다운로드할 수 있습니다.
 [누겟](https://www.nuget.org/packages/aspose.cells) 
 패키지 관리자, 검색
 **Aspose.Cells.Cpp** 
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++을 통해 XLSM의 메타데이터를 추출하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 XLSM 파일 수신, 처리, 타임스탬프 등을 포함하여 XLSM 파일에 저장된 유용한 정보에 액세스합니다.

{{% /blocks/products/pf/agp/text %}}

+ CreateIWorkbookMetadata를 사용하여 XLSM 파일 로드
+ CreateIMetadataOptions를 사용하여 옵션 만들기
+ GetICustomDocumentProperties() 및 AddIDocumentProperty로 새 속성 추가
+ XLSM 문서 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 모든 주요 플랫폼 및 운영 체제에서 C++ 지원을 위한 Aspose.Cells. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ Runtime Environment와 호환되는 OS.- 프로젝트에서 참조하는 C++ DLL에 대한 Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM의 메타데이터 추출 - C++" offSpacer="" %}}

```cs

intrusive_ptr<IMetadataOptions> options = Factory::CreateIMetadataOptions(MetadataType_DocumentProperties);
intrusive_ptr<IWorkbookMetadata> meta = Factory::CreateIWorkbookMetadata(new String("c:\\book1.xlsm"), options);
meta->GetICustomDocumentProperties()->AddIDocumentProperty(new String("test"), (StringPtr)new String("test"));
meta->Save(new String("c:\\book2.xlsm"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="C++ API에 대한 Aspose.Cells 정보" %}}

 Aspose.Cells API은(는) Microsoft Excel 형식을 다른 형식으로 생성, 편집, 변환 및 렌더링하는 데 사용할 수 있습니다. 또한 소프트웨어 응용 프로그램 내에서 포괄적인 차트 작성, 확장 가능한 보고 및 신뢰할 수 있는 계산에 사용할 수 있습니다. Aspose.Cells는 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어가 필요하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="온라인 앱을 통해 XLSM의 메타데이터 추출" sectionDescription="당사를 사용하여 XLSM 문서에 대한 메타데이터 보기 및 편집 [라이브 데모](https://products.aspose.app/cells/metadata) 다음과 같은 혜택이 있습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLSM 파일을 업로드하고 문서 속성을 편집하기만 하면 됩니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 결과 파일에 대한 다운로드 링크를 즉시 가져옵니다." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
확장자가 XLSM인 파일은 매크로를 지원하는 스프레드시트 파일 유형입니다. 응용 프로그램의 관점에서 매크로는 프로세스 자동화에 사용되는 일련의 지침입니다. 매크로는 반복적으로 수행되는 단계를 기록하는 데 사용되며 매크로를 다시 실행하여 작업을 쉽게 수행할 수 있습니다. 매크로는 Visual Basic Editor를 사용하여 Excel 통합 문서 내에서 Microsoft의 VBA(Visual Basic for Applications)로 프로그래밍되며 여기에서 직접 실행/디버그할 수 있습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 메타데이터 형식" subTitle="C++를 사용하면 다음을 포함한 많은 다른 형식의 메타데이터도 조작할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="OpenDocument 스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="Excel 이진 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="이진 Excel 통합 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="OOXML 엑셀 파일" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}