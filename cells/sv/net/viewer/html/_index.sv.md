---
title:  Visa HTML Filformat via .NET
description: C# källkod för att ladda, rendera och visa HTML dokument på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin Platforms.
keywords: [C# Aspose.Cells., c# view HTML files., c# how to render HTML document., c# load and display HTML files., HTML File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="HTML Filvisare for .NET" h2="Visa Excel- och OpenOffice-kalkylblad som HTML utan att behöva Microsoft Excel eller Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man visar HTML-fil med C#" %}}

 För att se filen HTML kommer vi att använda<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API som är en funktionsrik, kraftfull och lättanvänd API för C#-plattform som ska användas med vilken Viewer som helst. Öppen<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> pakethanterare, sök efter<b>Aspose.Cells</b> och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att visa HTML via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells gör det enkelt för utvecklarna att se filen HTML med bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda filen HTML i en instans av Workbook
1. Skapa en instans av HtmlSaveOptions och ställ in ExportHeadings-egenskapen till true
1. Spara HTML-filen i HTML-format med Workbook.Save-metoden
1. Ladda resultant HTML i standardwebbläsaren med Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET stöds på alla större operativsystem. Se bara till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin Platforms
-  Utvecklingsmiljö som Microsoft Visual Studio
-  Lägg till referens till Aspose.Cells for .NET DLL i ditt projekt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# exempelkod för att visa filen HTML" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the HTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.html");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the HTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API kan användas för att skapa, redigera, konvertera och rendera Microsoft Excel-format till olika format. Dessutom kan den användas för omfattande kartläggning, skalbar rapportering och tillförlitliga beräkningar inom mjukvaruapplikationer. Aspose.Cells är en fristående API och den kräver ingen programvara som Microsoft eller OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Gratis app att visa HTML" sectionDescription=" Kolla våra livedemos för att[Visa HTML](https://products.aspose.app/cells/viewer/html) med följande förmåner." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Inget behov av att skriva eller kompilera kod" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp filen HTML och tryck på knappen \"Visa\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ladda ner HTML-filen från länken om det behövs" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) är tillägget för webbsidor som skapats för visning i webbläsare. Känt som webbens språk, HTML har utvecklats med krav på nya informationskrav som ska visas som en del av webbsidor. Den senaste varianten är känd som HTML 5 som ger mycket flexibilitet för att arbeta med språket. HTML sidor tas antingen emot från servern, där dessa är värd, eller kan också laddas från det lokala systemet. Varje HTML sida består av HTML element som formulär, text, bilder, animationer, länkar etc. Dessa element representeras av taggar som img, a, p och flera andra där varje tagg har start och slut. Den kan också bädda in applikationer skrivna i skriptspråk som JavaScript och Style Sheets (CSS) för övergripande layoutrepresentation.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
