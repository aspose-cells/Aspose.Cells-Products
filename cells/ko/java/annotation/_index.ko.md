---
title: Java을 통한 Excel 파일 주석
url: /ko/java/annotation/
description: Java 라이브러리를 사용하여 Excel 및 OpenOffice 스프레드시트의 데이터 주석을 추가하거나 제거합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java을(를) 통해 Microsoft<sup>&reg;</sup> Excel 파일 주석 관리" h2="주석에 대한 간단한 메모를 삽입하거나 Java 기반 애플리케이션 내에서 Excel 스프레드시트 셀 수준 메모를 삭제합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java 엑셀 API](/cells/java/) 주석을 추가, 액세스 및 삭제하여 셀 수준에서 주석을 관리하기 위한 지원을 제공합니다. API 제공 [논평](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [댓글수집](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) 그리고 [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) 모든 측면에서 의견을 처리합니다.
지원되는 파일 형식에는 ODS, XLS, XLSX, XLSB 및 XLSM이 있습니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일 데이터 주석" %}}
워크시트의 주석 관리 - MS Excel에서 시트의 주석 수에는 제한이 없습니다. 애플리케이션 요구 사항만큼 추가할 수 있습니다. 코멘트를 추가하는 과정은 생성 [학습장](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스 개체를 만들거나 Workbook 클래스를 사용하여 기존 파일을 로드합니다. getComments()를 사용하여 모든 주석에 액세스합니다. 셀 인덱스 가져오기 및 사용 [세트노트](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) 주석을 삽입하기 위한 것입니다. 또한 API은(는) 모든 주석을 제거할 수 있습니다. 

{{% blocks/products/pf/feature-page-code h3="Java Excel 파일 내에 주석을 추가하는 코드" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel 파일 내에서 주석을 제거하는 코드" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}