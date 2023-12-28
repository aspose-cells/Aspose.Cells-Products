---
title: Excel via .NET에 주석 삽입
description:  C# .NET 라이브러리를 사용하여 Microsoft Excel 파일에 주석을 삽입하는 방법에 대한 소스 코드입니다.
keywords: [C# Aspose.Cells., add excel comments., insert excel comments., access excel comments., remove excel comments., delete excel comments., add comments in excel., insert comments in excel., access comments in excel., remove comments in excel., delete comments in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 주석 삽입 via .NET" h2=".NET 기반 애플리케이션에서 서버 측 API를 사용하여 Excel 문서를 작성하고 주석을 삽입합니다." >}}
{{% blocks/products/pf/feature-page-summary %}}

 셀에 설명을 추가할 수 있습니다. 셀에 메모가 있으면 셀 모서리에 표시기가 나타납니다. 셀 위로 커서를 가져가면 설명이 나타납니다. 이러한 설명은 토론, 특별 지침 또는 문서 내용의 마크업에 사용될 수 있습니다.[.NET 엑셀 라이브러리](/cells/ko/net/)Excel 파일에 주석 삽입을 지원합니다. 이를 위해 API은[논평](https://reference.aspose.com/cells/net/aspose.cells/comment) 주석 빌딩 블록을 위한 클래스입니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 파일에 주석 삽입" %}}

 Excel API을 사용하여 주석을 삽입하는 것은 간단합니다. 프로세스는 생성[워크북 수업](https://reference.aspose.com/cells/net/aspose.cells/workbook)개체를 선택하고 첫 번째 워크시트 또는 색인을 제공하여 관련 시트를 선택합니다. 다음을 사용하여 필요한 셀 데이터를 삽입하십시오.[PutValue 메서드](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . 다음을 사용하여 워크시트에 설명을 추가합니다.[댓글수집](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) '에스[메소드 추가](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Excel에 주석을 삽입하는 코드" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
