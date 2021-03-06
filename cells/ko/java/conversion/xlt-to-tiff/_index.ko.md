---
title: Java를 통해 XLT를 TIFF로 변환 
weight: 1530
url: /ko/java/conversion/xlt-to-tiff/ 
description: XLT 형식을 TIFF 파일로 변환하는 샘플 Java 변환 코드. 프로그래머는 이 예제 코드를 사용하여 Excel 및 OpenOffice 스프레드시트를 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 TIFF로 내보낼 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java를 통해 XLT를 TIFF로 변환" h2="XLT에서 TIFF로의 Java 변환은 온프레미스 Java 라이브러리를 사용하여 단일 또는 여러 페이지를 TIFF로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java을 사용하여 XLT를 TIFF로 변환하는 방법" %}}

 XLT를 TIFF로 렌더링하려면 다음을 사용합니다.
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API는 기능이 풍부하고 강력하며 사용하기 쉬운 전환 API for Java 플랫폼입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

{{% blocks/products/pf/agp/code-block title="저장소" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="의존" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 XLT를 TIFF로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 개발자는 몇 줄의 코드로 XLT 파일을 TIFF로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. 통합 문서의 인스턴스와 함께 XLT 파일 로드1. 컬렉션에서 기본 또는 워크시트 선택1. ImageOrPrintOptions 개체 생성 및 설정1. Worksheet 및 ImageOrPrintOptions 개체로 SheetRender 만들기1. SheetRender.toImage 메서드를 호출하여 결과를 TIFF 형식으로 저장
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 소스 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크톱 애플리케이션용 Java Runtime Environment와 호환되는 OS.- Maven에서 직접 최신 버전의 Aspose.Cells for Java을(를) 받으십시오.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT에서 TIFF로 Java 변환 소스 코드" offSpacer="" %}}

```cs
// 렌더링할 XLT 파일 로드
Workbook workbook = new Workbook("sourceFile.xlt");
// 컬렉션에서 기본 워크시트에 액세스
Worksheet worksheet = workbook.getWorksheets().get(0);
// 결과 이미지에 대한 매개변수 정의
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.TIFF);
// 워크시트를 TIFF 형식의 이미지로 변환
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.tiff");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLT에서 TIFF로의 변환 라이브 데모" sectionDescription="[XLT를 TIFF로 변환](https://products.aspose.app/cells/conversion/xlt-to-tiff) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을(를) 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" XLT 파일을 업로드하기만 하면 즉시 TIFF로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크가 나옵니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 스프레드시트 조작 라이브러리" %}}

 Excel API은(는) Microsoft Excel 형식을 다른 형식으로 생성, 편집, 변환 및 렌더링하는 데 사용할 수 있습니다. 또한 소프트웨어 응용 프로그램 내에서 포괄적인 차트 작성, 확장 가능한 보고 및 신뢰할 수 있는 계산에 사용할 수 있습니다. Aspose.Cells은(는) 독립 실행형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어가 필요하지 않습니다.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

확장자가 .XLT인 파일은 Microsoft Office 제품군의 일부로 제공되는 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새 XLT 파일 생성 및 열기를 지원했습니다. 최신 버전의 Excel은 여전히 이 이전 형식 템플릿 파일을 열 수 있습니다. 이러한 템플릿 파일은 페이지 형식, 글꼴 크기, 여백, 차트 등과 같은 기본 데이터 및 설정을 사용하여 새 Excel 파일을 빠르게 생성하는 데 사용되며 새 .XLS 파일로 추가로 저장할 수 있습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" >}}

TIFF 또는 TIF(Tagged Image File Format)는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색상 공간에서 이중 레벨, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 형식을 사용하는 응용 프로그램에 대해 공간과 시간 사이에서 선택하기 위해 손실 및 무손실 압축 체계를 지원합니다. 이 형식은 확장 가능하며 개인 또는 특수 목적 정보를 무제한으로 포함할 수 있도록 여러 번 수정되었습니다. 형식은 시스템에 종속되지 않으며 프로세서, 운영 체제 또는 파일 시스템과 같은 범위에서 자유롭습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="아래에 나열된 몇 가지를 포함하여 XLT를 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-bmp/" name="XLT에서 BMP로" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-csv/" name="XLT에서 CSV로" description="쉼표로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-dif/" name="XLT에서 DIF로" description="데이터 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-emf/" name="XLT에서 EMF로" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-gif/" name="GIF로 XLT" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-html/" name="HTML로 XLT" description="하이퍼 텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-jpeg/" name="XLT에서 JPEG로" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-mhtml/" name="XLT에서 MHTML로" description="웹 페이지 아카이브 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-ods/" name="XLT에서 ODS로" description="OpenDocument 스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-pdf/" name="PDF로 XLT" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-png/" name="XLT에서 PNG로" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-svg/" name="XLT에서 SVG로" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-tsv/" name="XLT에서 TSV로" description="탭으로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-txt/" name="XLT에서 TXT로" description="텍스트 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlm/" name="XLT에서 XLM으로" description="엑셀 매크로 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xls/" name="XLT에서 XLS로" description="Excel 이진 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlsb/" name="XLT에서 XLSB로" description="이진 Excel 통합 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xlsx/" name="XLT에서 XLSX로" description="OOXML 엑셀 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xltm/" name="XLT에서 XLTM으로" description="Excel 매크로 사용 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xltx/" name="XLT에서 XLTX로" description="Office OpenXML 엑셀 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-xps/" name="XLT에서 XPS로" description="XML 용지 사양" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlt-to-json/" name="XLT에서 JSON으로" description="자바스크립트 객체 표기법" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}