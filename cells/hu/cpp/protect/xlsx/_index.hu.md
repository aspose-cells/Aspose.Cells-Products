---
title:  A XLSX dokumentum védelme és zárolása a C++ számon keresztül
weight: 1140
description: C++ példakód a XLSX fájl zárolásához jelszóval a C++ futásidejű környezet Windows 32 bites, Windows 64 bites és 64 bites Linux esetén.
keywords: [C++ Aspose.Cells., C++ Lock XLSX files., C++ How to Protect and lock XLSX document., C++ Protect XLSX files., Encrypt XLSX Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSX fájlok titkosítása a C++ számon keresztül" h2="Jelszóvédett Excel-táblázatok, beleértve a XLSX formátumot a .NET könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="A XLSX fájl biztonságossá tétele a C++ használatával" %}}

 A XLSX fájl védelme érdekében használjuk
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumtitkosító API for C++ platform. A legújabb verziót közvetlenül letöltheti, csak nyissa meg
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 csomagkezelő, keressen
 **Aspose.Cells.Cpp** 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="A XLSX fájlok védelmének lépései a C++ számon keresztül" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.Cells API-k használatával történő dokumentumvédelem néhány sornyi kóddal elvégezhető.

{{% /blocks/products/pf/agp/text %}}

1.  Töltse be a XLSX fájlt a munkafüzet osztály használatával
1.  Használja a Protect(..) metódust a ProtectionType-val és a jelszóval
1.  Mentse a védett XLSX fájlt a Mentés() metódussal

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ támogatja az összes főbb platformot és operációs rendszert. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows vagy kompatibilis operációs rendszer C++ futásidejű környezettel a Windows 32 bites, Windows 64 bites és Linux 64 bites verziókhoz.
-  Adjon hivatkozást a Aspose.Cells for C++ DLL-re a projektben.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// load the ODS Excel file 
Workbook book(u"unlocked.xlsx");

// access the first worksheet
Worksheet worksheet = book.GetWorksheets().Get(0);

// protect the worksheet with password
worksheet.Protect(ProtectionType::All, u"password", nullptr);

// protect the whole workbook with password
book.Protect(ProtectionType::All, u"password");

// save the modified file in default format
book.Save(u"protected.xlsx");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for C++ API" %}}

 Aspose.Cells API használható Microsoft Excel formátumok létrehozására, szerkesztésére, konvertálására és renderelésére különböző formátumokba. Ezen túlmenően használható átfogó diagramok készítésére, skálázható jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Ingyenes alkalmazás a védelemhez XLSX" sectionDescription=" Tekintse meg élő bemutatóinkat[XLSX fájl titkosítása](https://products.aspose.app/cells/protect/xlsx) a következő előnyökkel." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni vagy fordítani" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a XLSX fájlt, és nyomja meg a \"Feloldás\" gombot" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Töltse le a kapott XLSX fájlt a hivatkozásról" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX a Microsoft Excel dokumentumok jól ismert formátuma, amelyet a Microsoft vezetett be a Microsoft Office 2007 kiadásával. Az OOXML szabvány 2. részében leírt nyílt csomagolási egyezmények szerint szervezett szerkezet alapján az új ECMA-376 formátum egy zip-csomag, amely számos XML-fájlt tartalmaz. Az alapul szolgáló struktúra és fájlok az .xlsx fájl egyszerű kicsomagolásával vizsgálhatók.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott védelmi dokumentumok" subTitle="A C++ használatával védhet más fájlokat, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="Táblázatfájl" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
