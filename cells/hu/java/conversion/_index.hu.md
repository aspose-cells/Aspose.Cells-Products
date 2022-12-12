---
title: "Microsoft Excel fájlkonverzió a következőn keresztül: Java "

description: Konvertálja az Excel XLS-t, XLSX-et, ODS-t, CSV-t PDF-, XPS-, HTML-, JPEG-, HTML- és sok más népszerű formátumba mindössze néhány soros Java-kóddal.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájlok konvertálása a következőn keresztül: Java" h2="Mentse a Microsoft Excel dokumentumokat táblázatos, webes, képi és rögzített elrendezésű formátumban" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bármely **Excel-átalakító** alkalmazás vagy megoldás esetén az Java Excel Library felgyorsítja a táblázatkezelő programozási és átalakítási folyamatokat, miközben többféle formátumot kezel, például XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Lehetővé teszi továbbá az Excel fájlok PDF-, XPS, HTML, MHTML, egyszerű szöveg és népszerű képformátumok, például TIFF, JPG, PNG, BMP és SVG formátumok konvertálását is.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel formátumok interkonvertálása" %}}
A táblázatformátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni [Munkafüzet](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) és visszamenti a kívánt formátumba, miközben kiválasztja a megfelelő értéket [SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) felsorolás.
{{% blocks/products/pf/feature-page-code h3="Java Példakód az Excel fájlformátum konvertálásához" %}}

```cs
// töltse be a forrásfájlt
var wkb = new Workbook("sourceFile.xls");
// mentse XLSX, ODS, SXC és FODS formátumban
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása PDF, XPS, HTML és MD formátumba" %}}
Speciális osztályok állnak rendelkezésre az átalakítási folyamat vezérlésére meghatározott kimeneti formátumokhoz, mint pl [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) az Excel fájlok PDF formátumba konvertálásához, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) az Excel exportálása XPS-ként, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) hogy az Excel HTML-ként jelenjen meg és [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) az Excelből Markdown konvertáláshoz. 
{{% blocks/products/pf/feature-page-code h3="Java Mintakód az Excelből PDF-be és webes formátumokba" %}}

```cs
// sablon Excel fájl betöltése a lemezről
var bk = new Workbook("source-file.xlsx");

// konvertálja az Excelt PDF-be a következővel: Java
// PDF-beállítások létrehozása
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// mentse az Excelt XPS-be
bk.save("output.xps", new XpsSaveOptions());
// mentse az Excelt HTML-be
bk.save("output.html", new HtmlSaveOptions());
// az Excel mentése a Markdown (MD) programban
bk.save("output.md", new MarkdownSaveOptions());

// a megfelelő mentési beállításokat tetszés szerint beállíthatja a megfelelő formátumba való mentés előtt

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a JSON-t Excel-be és az Excel-t JSON-ba" %}}
A JSON-adatok a Workbook osztály egy példányába importálhatók a segítségével [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) további feldolgozáshoz vagy egyszerű konvertáláshoz a támogatott formátumok bármelyikére. Hasonlóképpen, a munkalapadatok JSON-ként exportálhatók a [Hatótávolság](https://reference.aspose.com/cells/java/com.aspose.cells/range) vagy sejtek és hívja a [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) módszer.
{{% blocks/products/pf/feature-page-code h3="Java Kód a JSON-ból Excel-be való konvertáláshoz" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Fájl olvasása
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Állítsa be a JsonLayoutOptions-t
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSON-adatok importálása
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Mentse el az Excel fájlt
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Forráskód az Excel JSON-ba konvertálásához" %}}
```cs
// töltse be az XLSX fájlt a munkafüzet egy példányával
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsA konvertálandó adatokat tartalmazó munkalap gyűjteménye
Cells cells = workbook.getWorksheets().get(0).getCells();
// Hozzon létre és állítson be ExportRangeToJsonOptions-t a speciális beállításokhoz
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// hozzon létre egy cellatartományt, amely exportálandó adatokat tartalmaz
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// tartomány exportálása JSON-adatokként
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// írjon adatokat a lemezre JSON formátumban
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel-munkalapok mentése Képek közé" %}}
Minden munkalap konvertálható különböző képformátumokba, például JPG, BMP, PNG és GIF, amelyeket az ImageType tulajdonság állít be. Minden **Excel konvertálása képekké** esethez válassza ki a megfelelő esetet a hivatkozások közül.
{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel képpé konvertálásához" %}}
```cs
// sablon táblázat betöltése
var wkb = new Workbook("template.xlsx");

// Hozzon létre egy objektumot az ImageOptions számára
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Állítsa be a kép típusát
imgOptions.setImageType(ImageType.PNG);

// Szerezd meg az első munkalapot.
Worksheet sheet = wkb.getWorksheets().get(0);

// Hozzon létre egy SheetRender objektumot a céllaphoz
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Képet generál a munkalaphoz
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="A Microsoft Excel konvertálása Word és PowerPoint formátumba" %}}
Lehetőség van bármilyen táblázat betöltésére és Word DOCX és PowerPoint PPTX fájlokká konvertálására használat közben. [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) osztályok alább bemutatott módon.
{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel Word és PowerPoint konvertálásához" %}}
```cs
// töltse be a sablonfájlt
var wkb = new Workbook("template.xlsx");
// mentse a táblázatot DOCX-ként
wkb.save("output.docx", new DocxSaveOptions());
// mentse a táblázatot PPTX-ként
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
