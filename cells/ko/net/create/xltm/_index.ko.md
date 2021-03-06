---
title: C#을(를) 통해 MS Excel XLTM 파일 만들기 
url: /ko/net/create-xltm/ 
description: C# XLTM 문서 생성을 위한 샘플 코드. VB.NET, Asp.NET 또는 모든 .NET 기반 애플리케이션 내에서 MS Excel XLTM 파일을 생성하려면 이 코드를 사용하십시오.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#을(를) 통해 XLTM 문서 만들기" h2="서버 측 .NET API를 사용하여 프로그래밍 방식으로 네이티브 및 고성능 MS Excel XLTM 스프레드시트 생성." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 실행 중인 응용 프로그램 내에서 MS Excel XLTM 파일을 동적으로 생성하는 것은 쉽습니다. MS Office 없이 처음부터 XLTM 문서를 생성하려면 다음을 사용합니다.
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API은(는) .NET 플랫폼을 사용하여 스프레드시트 생성, 조작 및 변환을 위한 다양한 기능을 제공합니다. 개발자는 데이터 작성, 차트 또는 그래프 생성, 스프레드시트에 테이블 생성을 위한 코드를 쉽게 개선할 수 있습니다.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#을(를) 통해 XLTM을 만드는 방법" %}}

{{% blocks/products/pf/agp/text %}}

 개발자는 단 몇 줄의 코드로 데이터 처리를 위해 다양한 보고 응용 프로그램을 실행하여 MS Excel XLTM 스프레드시트를 쉽게 생성, 로드, 수정 및 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. 클래스 파일에 네임스페이스 포함1. 통합 문서 클래스 인스턴스를 만듭니다.1. 통합 문서의 첫 번째 워크시트에 액세스합니다.1. 워크시트의 원하는 셀을 가져오고 값을 셀에 입력합니다.1. 저장 방법을 사용하여 통합 문서를 XLTM 파일로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 시스템에 Microsoft Windows 또는 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼과 호환되는 OS 및 Microsoft Visual Studio와 같은 개발 환경이 있는지 확인하십시오. 

{{% /blocks/products/pf/agp/text %}}

- 다음과 같이 명령줄에서 설치 <code>nuget install Aspose.Cells</code> 또는 Visual Studio의 패키지 관리자 콘솔을 통해 <code>Install-Package Aspose.Cells</code>.- 또는 오프라인 MSI 설치 프로그램 또는 ZIP 파일의 모든 DLL을 <a href="https://downloads.aspose.com/cells/net">다운로드</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="다음 소스 코드는 C#을 사용하여 MS Excel XLTM 파일을 만드는 방법을 보여줍니다." offSpacer="" %}}

```cs

// 통합 문서 클래스 인스턴스를 만듭니다.
Workbook wkb = new Workbook();

// 통합 문서의 첫 번째 워크시트에 액세스합니다.
Worksheet sht = wkb.Worksheets[0];

// 워크시트의 원하는 셀을 가져옵니다.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// 셀에 값을 입력합니다.
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// 통합 문서를 .xltm 파일로 저장합니다.
wkb.Save("created_one.xltm");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 MS Excel XLTM 파일을 생성, 수정, 변환, 렌더링 및 인쇄할 수 있는 기능으로 크로스 플랫폼 응용 프로그램을 구축할 수 있는 Excel 스프레드시트 프로그래밍 라이브러리입니다. .NET ExcelAPI은 스프레드시트 형식 간에 변환할 수 있을 뿐만 아니라 Excel 파일을 이미지, PDF, HTML, ODS 등으로 렌더링할 수 있으므로 업계 표준 형식의 문서를 교환하기에 완벽한 선택입니다.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTM" readMoreLink="https://docs.fileformat.com/spreadsheet/xltm/" >}}
XLTM 파일 확장자는 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. XLTM 파일은 나중에 매크로가 있는 템플릿 파일 생성을 지원하지 않는다는 점을 제외하고는 구조가 XLTX와 유사합니다. 이러한 템플릿 파일은 유사한 XLSX 파일을 쉽게 생성할 수 있도록 매크로와 함께 레이아웃, 서식 및 기타 설정을 생성하고 설정하는 데 사용됩니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 스프레드시트 생성" subTitle="아래 나열된 몇 가지를 포함하여 다른 Microsoft Excel 형식을 만들 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Microsoft Excel 스프레드시트(기존)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="XML 통합 문서 열기" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Excel 바이너리 통합 문서" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="매크로 사용 스프레드시트" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="엑셀 97 - 2003 템플릿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="엑셀 템플릿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Excel 매크로 사용 템플릿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="쉼표로 구분된 값" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="TSV" description="탭으로 구분된 값" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="ODS" description="OpenDocument 스프레드시트" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
