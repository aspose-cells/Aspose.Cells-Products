---
title: C++ 애플리케이션을 통해 ODS를 XLSB로 변환 
weight: 4080
url: /ko/cpp/conversion/ods-to-xlsb/ 
description: ODS 문서를 XLSB 형식으로 변환하는 샘플 C++ 변환 코드. 프로그래머는 모든 C++ 애플리케이션 내에서 일괄 ODS에서 XLSB로의 변환을 위해 이 소스 코드를 사용할 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 ODS를 XLSB로 변환" h2="Microsoft Excel, OpenOffice 또는 Adobe Acrobat을 설치할 필요 없이 C++ 라이브러리를 사용하여 고성능 ODS에서 XLSB로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++을 사용하여 ODS를 XLSB로 변환하는 방법" %}}

 ODS를 XLSB로 변환하려면 다음을 사용합니다.
 [C++에 대한 Aspose.Cells](https://products.aspose.com/cells/cpp) 
 API은(는) C++ 플랫폼용으로 기능이 풍부하고 강력하며 사용하기 쉬운 문서 조작 및 변환API입니다. 최신 버전을 직접 다운로드할 수 있습니다.
 [누겟](https://www.nuget.org/packages/aspose.cells) 
 패키지 관리자, 검색
 Aspose.Cells.Cpp 
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++를 통해 ODS를 XLSB로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 개발자는 몇 줄의 코드로 ODS 파일을 XLSB로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbook을 사용하여 ODS 파일을 로드합니다.1. Save() 메서드를 호출합니다.1. 파일 확장자가 (XLSB)인 출력 파일 경로를 전달합니다.1. XLSB 파일은 지정된 경로에 저장됩니다.1. 호환되는 프로그램에서 XLSB 파일을 엽니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 변환 샘플 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하세요.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ Runtime Environment와 호환되는 OS.- 프로젝트에서 참조하는 C++ DLL에 대한 Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS에서 XLSB C++로의 변환 소스 코드" offSpacer="" %}}

```cs
// ODS를 로드합니다.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");

// XLSB 형식으로 저장합니다.
wkb->Save(u"convertedFile.xlsb", SaveFormat_Xlsb);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ODS에서 XLSB로의 변환 라이브 데모" sectionDescription="[ODS를 XLSB로 변환](https://products.aspose.app/cells/conversion/ods-to-xlsb) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을(를) 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ODS 파일을 업로드하기만 하면 즉시 XLSB로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크가 나옵니다." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 파일 조작 라이브러리" %}}

 Excel API은(는) Microsoft Excel 형식을 다른 형식으로 생성, 편집, 변환 및 렌더링하는 데 사용할 수 있습니다. 또한 소프트웨어 응용 프로그램 내에서 포괄적인 차트 작성, 확장 가능한 보고 및 신뢰할 수 있는 계산에 사용할 수 있습니다. Aspose.Cells은(는) 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어가 필요하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

ODS 확장자를 가진 파일은 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 나타냅니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. XML 기반 형식이며 ODF(Open Document Formats) 제품군의 여러 하위 유형 중 하나입니다. 형식은 OASIS에서 게시 및 유지 관리하는 ODF 1.2 사양의 일부로 지정됩니다. Microsoft Excel, NeoOffice 및 LibreOffice를 비롯한 Windows 및 기타 운영 체제의 여러 응용 프로그램에서 편집 및 조작을 위해 ODS 파일을 열 수 있습니다. ODS 파일은 다른 응용 프로그램에서 XLS, XLSX 및 기타와 같은 다른 스프레드시트 형식으로 변환할 수도 있습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

XLSB 파일 형식은 Excel 통합 문서 콘텐츠를 지정하는 레코드 및 구조의 모음인 Excel 이진 파일 형식을 지정합니다. 콘텐츠에는 숫자, 텍스트 또는 숫자와 텍스트, 공식, 외부 데이터 연결, 차트 및 이미지 모두의 비정형 또는 반정형 표가 포함될 수 있습니다. Open XML 파일 형식을 기반으로 하는 XLSX와 달리 XLSB는 이진 Excel 통합 문서 파일을 나타냅니다. XLSB 파일은 더 빠르게 읽고 쓸 수 있어 대용량 파일 작업에 유용합니다. XLSB는 통합 문서를 저장하는 데 거의 사용되지 않습니다. XLSX(및 이전 XLS)는 통합 문서를 저장하기 위해 가장 일반적으로 사용자가 선택한 파일 형식입니다. Microsoft Office 2007 이상에서 열 수 있습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 ODS를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-bmp/" name="ODS에서 BMP로" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-csv/" name="ODS에서 CSV로" description="쉼표로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-dif/" name="ODS에서 DIF로" description="데이터 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-emf/" name="EMF에 대한 ODS" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-gif/" name="GIF에 ODS" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-html/" name="HTML에 ODS" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-jpeg/" name="ODS에서 JPEG로" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-mhtml/" name="MHTML에 대한 ODS" description="웹 페이지 아카이브 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-pdf/" name="PDF로 ODS" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-png/" name="PNG에 대한 확률" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-svg/" name="SVG에 대한 ODS" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tiff/" name="TIFF에 대한 확률" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tsv/" name="ODS에서 TSV로" description="탭으로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xls/" name="ODS에서 XLS로" description="Excel 이진 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsm/" name="XLSM에 대한 확률" description="스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsx/" name="XLSX에 ODS" description="OOXML 엑셀 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltm/" name="ODS에서 XLTM으로" description="Excel 매크로 사용 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltx/" name="ODS에서 XLTX로" description="Office OpenXML 엑셀 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xps/" name="XPS에 대한 확률" description="XML 용지 사양" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}