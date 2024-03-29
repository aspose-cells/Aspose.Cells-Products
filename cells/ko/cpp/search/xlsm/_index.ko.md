---
title:  C++을 통해 열지 않고 XLSM 문서 검색
weight: 9280
description: C++ Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경의 XLSM 파일에서 패턴이 있는 단어를 검색하는 예제 코드입니다.
keywords: [C++ Aspose.Cells., C++ search words with pattern in xlsm file., C++ find words with pattern in xlsm file., C++ search string with pattern in xlsm file., C++ find words with pattern in xlsm file., C++ search words in xlsm file., C++ find words in xlsm file., C++ search string in xlsm file., C++ find string in xlsm file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++에서 XLSM 형식 검색" h2="Microsoft 또는 Adobe PDF과 같은 소프트웨어를 사용하지 않고 서버 측 Aspose.Cells for C++ API를 사용하는 기본 및 고성능 XLSM 문서 검색." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++을 사용하여 XLSM 파일을 검색하는 방법" %}}

 XLSM 파일을 검색하기 위해 다음을 사용합니다.
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API은 기능이 풍부하고 강력하며 사용하기 쉬운 문서 검색 API for C++ 플랫폼입니다. 최신 버전을 직접 다운로드할 수 있습니다. 열기만 하면 됩니다.
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 패키지 관리자, 검색
 **Aspose.Cells.Cpp** 
 그리고 설치하세요. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++에서 XLSM 파일을 검색하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells API를 사용한 기본 문서 검색은 단 몇 줄의 코드만으로 수행할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ 통합 문서 클래스를 인스턴스화하여 XLSM 파일을 로드합니다.
+ 바꾸기 옵션 클래스를 인스턴스화합니다.
+ SetCaseSensitive(bool value), SetMatchEntireCellContents(bool value) 와 같은 필수 패턴을 설정합니다.
관련 옵션과 함께 Workbook::Replace(...) 메서드를 사용하세요.
+ Workbook::Save(...) 메소드를 사용하여 XLSM 파일을 저장합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++은 모든 주요 플랫폼 및 운영 체제를 지원합니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 또는 Windows 32비트, Windows 64비트 및 Linux 64비트용 C++ 런타임 환경과 호환되는 OS.
-  프로젝트에 Aspose.Cells for C++ DLL에 대한 참조를 추가합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="검색 XLSM 파일 - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load XLSM file
Workbook  wkb(srcDir + u"sourceFile.xlsm");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as XLSM file
wkb.Save(outDir + u"outputFile.xlsm");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="약 Aspose.Cells for C++ API" %}}

 Aspose.Cells API은 Microsoft Excel 형식을 다른 형식으로 생성, 편집, 변환 및 렌더링하는 데 사용할 수 있습니다. 또한 소프트웨어 애플리케이션 내에서 포괄적인 차트 작성, 확장 가능한 보고 및 신뢰할 수 있는 계산에 사용할 수 있습니다. Aspose.Cells은 독립형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어가 필요하지 않습니다.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="온라인 XLSM 라이브 데모 검색" sectionDescription=" 지금 바로 당사를 방문하여 XLSM 문서 내의 텍스트, 단어, 문구를 검색하세요.[라이브 데모 웹사이트](https://products.aspose.app/cells/search). 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="XLSM 파일을 업로드하세요." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 검색 결과가 즉시 나타납니다." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
확장자가 XLSM인 파일은 매크로를 지원하는 스프레드시트 파일 유형입니다. 응용 프로그램의 관점에서 매크로는 프로세스 자동화에 사용되는 명령 집합입니다. 매크로는 반복적으로 수행되는 단계를 기록하는 데 사용되며 매크로를 다시 실행하여 작업 수행을 용이하게 합니다. 매크로는 Visual Basic Editor를 사용하여 Excel 통합 문서 내에서 Microsoft의 VBA(Visual Basic for Application)로 프로그래밍되며 거기에서 직접 실행/디버그할 수 있습니다.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 검색 문서" subTitle="C++을 사용하면 다음을 포함한 다른 파일도 검색할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="쉼표로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="OpenDocument 스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="탭으로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="텍스트 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Excel 바이너리 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="바이너리 Excel 통합 문서 파일" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
