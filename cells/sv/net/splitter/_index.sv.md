---
title: Dela upp Excel-kalkylblad i C#
url: /sv/net/splitter/
description: C# källkoder som förklarar hur du delar upp Microsoft Excel-filer i flera filer i Visual C#.NET-program
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fildelning via .NET" h2="Dela upp ett Excel-dokument i olika filer med C#-koden i .NET-baserade applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-bibliotek](/cells/net/) kan dela upp Excel-dokument i flera kalkylblad inom .NET-baserade applikationer. Filformat som stöds inkluderar XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dela upp Excel-dokument i flera filer" %}}
Det enklaste sättet att dela upp Excel-filer arkmässigt är att komma åt alla ark via [Arbetsblad](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Itererar genom varje ark och anropar [Kopiera](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metod. Äntligen sparar du den på en angiven väg. 

+ Ladda Excel-filen med fullständig sökväg med hjälp av [Arbetsbok klass](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterera genom varje ark
+ Skapa ett nytt Workbook-klassobjekt
+ Kopiera arket via [Kopieringsmetod](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Anropa metoden Save() och skicka filnamnet (fullständig sökväg) med relevant SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Koda för att dela Excel-filer" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dela upp Excel-kalkylblad i rutor" %}}

För att dela upp kalkylbladsfönstret i rutor tillhandahåller API [Split metod](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) av kalkylbladsklassen, som ger den delade vyn av kalkylbladet. För att ta bort delad vy tillhandahåller API [RemoveSplit-metoden](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Spara den till sist i en angiven sökväg. 

{{% blocks/products/pf/feature-page-code h3="C# Kod för att dela Excel-kalkylbladsfönster" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kod för att ta bort delad panoreringsvy" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
