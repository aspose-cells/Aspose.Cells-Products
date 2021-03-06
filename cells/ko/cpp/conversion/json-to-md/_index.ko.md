---
title: C++ 애플리케이션을 통해 JSON을 MD로 변환 
url: /ko/cpp/conversion/json-to-md/ 
description: JSON 문서를 MD 형식으로 변환하는 샘플 C++ 변환 코드. 프로그래머는 모든 C++ 애플리케이션 내에서 JSON에서 MD로의 일괄 변환에 이 소스 코드를 사용할 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++를 통해 JSON을 MD로 변환" h2="Microsoft Excel, OpenOffice 또는 Adobe Acrobat을 설치할 필요 없이 C++ 라이브러리를 사용하여 고성능 JSON에서 MD로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MD" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++을 사용하여 JSON을 MD로 변환하는 방법" %}}

 JSON을 MD로 변환하려면 다음을 사용합니다.
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

{{% blocks/products/pf/agp/feature-section-col title="C++을 통해 JSON을 MD로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 개발자는 몇 줄의 코드로 JSON 파일을 MD로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbook을 사용하여 JSON 파일을 로드합니다.1. Save() 메서드를 호출합니다.1. 파일 확장자가 (MD)인 출력 파일 경로를 전달합니다.1. MD 파일은 지정된 경로에 저장됩니다.1. 호환 프로그램에서 MD 파일을 엽니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 변환 샘플 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하세요.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ Runtime Environment와 호환되는 OS.- 프로젝트에서 참조하는 C++ DLL에 대한 Aspose.Cells.
- Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ Runtime Environment와 호환되는 OS.- 프로젝트에서 참조하는 C++ DLL에 대한 Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JSON에서 MD C++로의 변환 소스 코드" offSpacer="" %}}

```cs
// JSON을 로드합니다.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.json");

// MD 형식으로 저장합니다.
wkb->Save(u"convertedFile.md", SaveFormat_Md);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="JSON에서 MD로의 변환 라이브 데모" sectionDescription="[JSON을 MD로 변환](https://products.aspose.app/cells/conversion/json-to-md) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을(를) 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" JSON 파일을 업로드하기만 하면 즉시 MD로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크가 나옵니다." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 파일 조작 라이브러리" %}}

 Excel API은(는) Microsoft Excel 형식을 다른 형식으로 생성, 편집, 변환 및 렌더링하는 데 사용할 수 있습니다. 또한 소프트웨어 응용 프로그램 내에서 포괄적인 차트 작성, 확장 가능한 보고 및 신뢰할 수 있는 계산에 사용할 수 있습니다. Aspose.Cells은(는) 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어가 필요하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON(JavaScript Object Notation)은 사람이 읽을 수 있는 텍스트를 사용하여 데이터를 저장하고 전송하는 데이터 공유를 위한 개방형 표준 파일 형식입니다. JSON 파일은 .json 확장자로 저장됩니다. JSON은 형식 지정이 덜 필요하며 XML에 대한 좋은 대안입니다. JSON은 JavaScript에서 파생되었지만 언어 독립적인 데이터 형식입니다. JSON의 생성 및 구문 분석은 많은 최신 프로그래밍 언어에서 지원됩니다. application/json은 JSON에 사용되는 미디어 유형입니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MD" readMoreLink="https://docs.fileformat.com/word-processing/md/" >}}

Markdown 언어로 만든 텍스트 파일은 .MD 또는 .MARKDOWN 파일 확장자로 저장됩니다. MD 파일은 인라인 텍스트 기호도 포함하는 Markdown 언어를 사용하는 일반 텍스트 형식으로 저장되어 들여쓰기, 표 형식, 글꼴 및 머리글과 같은 텍스트 형식을 정의하는 방법을 정의합니다. MD 파일은 Markdown이라는 프로그램을 사용하여 HTML로 변환할 수 있습니다. Markdown 언어는 John Gruber가 발표했습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}