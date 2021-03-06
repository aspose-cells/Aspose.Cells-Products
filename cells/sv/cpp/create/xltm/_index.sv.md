---
title: Skapa MS Excel XLTM-filer via C++ 
url: /sv/cpp/create-xltm/ 
description: C++ Exempelkod för att generera MS Excel XLTM-filer. Använd den här koden för att skapa MS Excel XLTM-filer i en C++-baserad applikation.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Skapa XLTM-fil via C++" h2="Inbyggt och högpresterande MS Excel XLTM-kalkylark skapade programmatiskt utan Micorsoft Office med hjälp av C++-biblioteket." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Det är enkelt att generera MS Excel XLTM-fil dynamiskt i ett program som körs. För att skapa XLTM-dokument från grunden utan att behöva MS Office kommer vi att använda
 [Aspose.Cells för C++](https://products.aspose.com/cells/cpp) 
 API som erbjuder olika funktioner för att skapa, manipulera och konvertera dokument med C++-plattformen. Utvecklare kan enkelt förbättra kod för att uppdatera celldata, generera diagram eller grafer samt skapa pivottabeller, lägga till formler på cellnivå och mer i kalkylblad.
{{% /blocks/products/pf/agp/content %}}                                                                             

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du XLTM via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Det är enkelt för utvecklarna att skapa, ladda, modifiera och konvertera XLTM-filer inom körande rapporteringsapplikationer för databehandling på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Skapa ett objekt av klassen IWorkbook.1. Hämta det första arket i ett IWorksheet-objekt.1. Använd metoden IWorksheet->GetICells() för att få cellerna i kalkylbladet till ett ICells-objekt.1. Använd metoden ICells->GetObjectByIndex() för att komma åt önskad cell i kalkylbladet till ett ICell-objekt.1. Använd metoden ICell->PutValue() för att mata in värde i cellen.1. Spara arbetsboken som .xltm-fil med hjälp av metoden Save().
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

Innan du kör källkoden för C++ omvandlingsexempel, se till att du har följande förutsättningar. 

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med C++ Runtime Environment för Windows 32-bitars, Windows 64-bitars och Linux 64-bitars.- Aspose.Cells för C++ DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Följande källkod visar hur du skapar en MS Excel XLTM-fil med C++." offSpacer="" %}}

```cs

// Skapa ett objekt av klassen IWorkbook.
intrusive_ptr<IWorkbook> wkb = Factory::CreateIWorkbook();

// Hämta det första arket i ett IWorksheet-objekt.
intrusive_ptr<IWorksheetCollection> wsc = wkb->GetIWorksheets();
intrusive_ptr<IWorksheet> ws = wsc->GetObjectByIndex(0);

// Använd metoden IWorksheet->GetICells() för att få cellerna i kalkylbladet till ett ICells-objekt.
intrusive_ptr<ICells> cells = ws->GetICells();

// Använd metoden ICells->GetObjectByIndex() för att komma åt önskad cell i kalkylbladet till ett ICell-objekt.
intrusive_ptr<ICell> cell00 = cells->GetObjectByIndex(0, 0);
intrusive_ptr<ICell> cell01 = cells->GetObjectByIndex(0, 1);
intrusive_ptr<ICell> cell10 = cells->GetObjectByIndex(1, 0);
intrusive_ptr<ICell> cell11 = cells->GetObjectByIndex(1, 1);

// Använd metoden ICell->PutValue() för att mata in värde i cellen.
cell00->PutValue(new String("ColumnA"));
cell01->PutValue(new String("ColumnB"));
cell10->PutValue(new String("ValueA"));
cell11->PutValue(new String("ValueB"));

// Spara arbetsboken i mappen resultFile
wkb->Save(new String("created_one.xltm"));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

Ett Excel Spreadsheet Programming Library som kan bygga plattformsoberoende applikationer med förmågan att generera, modifiera, konvertera, rendera och skriva ut MS Excel XLTM-filer. C++ Excel API konverterar inte bara mellan kalkylarksformat, det kan också återge Excel-filer som bilder, PDF, HTML, ODS och mer, vilket gör det till ett perfekt val för att utbyta dokument i branschstandardformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTM" readMoreLink="https://docs.fileformat.com/spreadsheet/xltm/" >}}

       {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Generering av andra ark som stöds" subTitle="Du kan också skapa andra Microsoft Excel-filer, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xls/" name="XLS" description="Microsoft Excel-kalkylblad (legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlsx/" name="XLSX" description="Öppna XML-arbetsbok" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlsb/" name="XLSB" description="Excel binär arbetsbok" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlsm/" name="XLSM" description="Makroaktiverat kalkylblad" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xlt/" name="XLT" description="Excel 97 - 2003 mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xltx/" name="XLTX" description="Excel-mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-xltm/" name="XLTM" description="Excel-makroaktiverad mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-csv/" name="CSV" description="Kommaseparerade värden" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-tsv/" name="TSV" description="Flikseparerade värden" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/create-ods/" name="ODS" description="OpenDocument Kalkylblad" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
