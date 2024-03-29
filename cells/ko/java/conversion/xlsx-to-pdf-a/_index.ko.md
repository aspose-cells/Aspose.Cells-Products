---
title:  XLSX을 PDF/A 컴파일 파일 via Java로 변환
weight: 3200
description: XLSX 형식의 샘플 Java 변환 코드를 PDF A 컴파일 파일로 변환합니다. 프로그래머는 이 예제 코드를 사용하여 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 Excel 및 OpenOffice 스프레드시트를 PDFA 호환 파일로 내보낼 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSX을 PDF/A via Java로 변환" h2="XLSX에서 PDF/A Java 변환은 온프레미스 Java 라이브러리를 사용하여 단일 또는 여러 페이지를 PDF/A로 변환합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF/A" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF/A" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java을 사용하여 XLSX을 PDF/A로 변환하는 방법" %}}

XLSX을 PDF/A로 렌더링하기 위해 다음을 사용합니다.
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API은 기능이 풍부하고 강력하며 사용하기 쉬운 변환 API for Java 플랫폼입니다. 최신 버전은 다음에서 직접 다운로드할 수 있습니다.
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 pom.xml에 다음 구성을 추가하여 Maven 기반 프로젝트 내에 설치하세요.

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

{{% blocks/products/pf/agp/feature-section-col title="XLSX을 PDF/A via Java로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 개발자는 단 몇 줄의 코드만으로 XLSX 파일을 PDF/A로 쉽게 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1.  Workbook 클래스의 인스턴스로 XLSX 파일 로드
1.  PdfSaveOptions 클래스 객체 생성
1.  규정 준수 유형 설정 PdfCompliance.PdfA1b
1.  Workbook.save 메서드 호출
1.  PDF 확장명 및 PdfSaveOptions 개체를 매개변수로 사용하여 출력 경로 전달
1.  결과 PDF/A 파일의 지정된 경로를 확인하세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 소스 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하세요.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 런타임 환경 Java과 호환되는 OS.
- Maven에서 직접 Aspose.Cells for Java의 최신 버전을 받으세요.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX ~ PDF/A Java 변환 소스 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "fb3baba8d2c3daf5bfb9d6d52bfabe1a" "convert-xlsx-to-pdf-a.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSX ~ PDF 변환 라이브 데모" sectionDescription="[XLSX을 PDF로 변환](https://products.aspose.app/cells/conversion/xlsx-to-pdf) 지금 바로 라이브 데모 웹사이트를 방문하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API을 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="XLSX 파일을 업로드하면 즉시 PDF로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크를 받게 됩니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 스프레드시트 조작 라이브러리" %}}

 Excel API은 Microsoft Excel 형식을 다른 형식으로 생성, 편집, 변환 및 렌더링하는 데 사용할 수 있습니다. 또한 소프트웨어 애플리케이션 내에서 포괄적인 차트 작성, 확장 가능한 보고 및 신뢰할 수 있는 계산에 사용할 수 있습니다. Aspose.Cells은 독립형 API이며 Microsoft 또는 OpenOffice와 같은 소프트웨어가 필요하지 않습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX은 Microsoft Office 2007 릴리스와 함께 Microsoft에 의해 도입된 Microsoft Excel 문서의 잘 알려진 형식입니다. OOXML 표준 ECMA-376의 2부에 요약된 개방형 패키징 규칙에 따라 구성된 구조를 기반으로 하는 새로운 형식은 다음과 같습니다. 다수의 XML 파일을 포함하는 zip 패키지입니다. .xlsx 파일의 압축을 풀면 기본 구조와 파일을 검사할 수 있습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Portable Document Format(PDF)은 Adobe가 1990년대에 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제에 독립적인 형식으로 문서 및 기타 참조 자료를 표현하기 위한 표준을 도입하는 것이었습니다. PDF 파일은 확장/플러그인을 통해 Adobe Acrobat Reader/Writer는 물론 Chrome, Safari, Firefox와 같은 대부분의 최신 브라우저에서 열 수 있습니다. 시중에서 판매되는 대부분의 소프트웨어 제품군은 추가 소프트웨어 구성 요소 없이도 문서를 PDF 파일 형식으로 변환하는 기능도 제공합니다. 따라서 PDF 파일 형식은 소스 문서의 일부가 될 수 있는 텍스트, 이미지, 하이퍼링크, 양식 필드, 리치 미디어, 디지털 서명, 첨부 파일, 메타데이터, 지리 공간 기능 및 3D 개체와 같은 정보를 포함할 수 있는 모든 기능을 갖추고 있습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="또한 XLSX을 아래 나열된 몇 가지 파일 형식을 포함하여 다양한 다른 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-bmp/" name="XLSX ~ BMP" description="비트맵 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-csv/" name="XLSX ~ CSV" description="쉼표로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-dif/" name="XLSX ~ DIF" description="데이터 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-emf/" name="XLSX ~ EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-gif/" name="XLSX ~ GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-html/" name="XLSX ~ HTML" description="하이퍼텍스트 마크업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-jpeg/" name="XLSX ~ JPEG" description="JPEG 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-mhtml/" name="XLSX ~ MHTML" description="웹페이지 아카이브 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-ods/" name="XLSX ~ ODS" description="OpenDocument 스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-png/" name="XLSX ~ PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-pdf/" name="XLSX ~ PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-svg/" name="XLSX ~ SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-tiff/" name="XLSX ~ TIFF" description="태그된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-tsv/" name="XLSX ~ TSV" description="탭으로 구분된 값" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-txt/" name="XLSX ~ TXT" description="텍스트 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xls/" name="XLSX ~ XLS" description="Excel 바이너리 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xlsb/" name="XLSX ~ XLSB" description="바이너리 Excel 통합 문서 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xlsm/" name="XLSX ~ XLSM" description="스프레드시트 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xlt/" name="XLSX ~ XLT" description="Microsoft 엑셀 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xltm/" name="XLSX ~ XLTM" description="Excel 매크로 지원 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xltx/" name="XLSX ~ XLTX" description="Office OpenXML 엑셀 템플릿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-xps/" name="XLSX ~ XPS" description="XML 용지 사양" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsx-to-json/" name="XLSX ~ JSON" description="자바스크립트 객체 표기법" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
