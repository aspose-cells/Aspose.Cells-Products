---
title: Převod souborů Microsoft Excel prostřednictvím Java 
url: /cs/java/conversion/
description: Převeďte Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG, HTML a mnoha dalších oblíbených formátů pomocí pouhých několika řádků kódu Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převod souborů Microsoft<sup>&reg;</sup> Excel prostřednictvím Java" h2="Ukládejte dokumenty Microsoft Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozvržením" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pro libovolnou aplikaci nebo řešení **převaděče Excelu** urychluje Knihovna Excelu Java proces programování a převodu tabulek a zároveň zpracovává různé formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umožňuje také **převádět soubory Excelu do PDF**, XPS, HTML, MHTML, prostého textu a populárních obrazových formátů, jako jsou TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vzájemná konverze formátů Microsoft Excel" %}}
Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí [pracovní sešit](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z [UložitFormát](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) výčet.
{{% blocks/products/pf/feature-page-code h3="Java Příklad kódu pro převod formátu souboru aplikace Excel" %}}

```cs
// načíst zdrojový soubor
var wkb = new Workbook("sourceFile.xls");
// uložit jako formáty XLSX, ODS, SXC a FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do PDF, XPS, HTML a MD" %}}
K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např [Možnosti PdfSave](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) převádět soubory aplikace Excel do formátu PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) exportovat Excel jako XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) vykreslit Excel jako HTML a [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) pro převod Excel na Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Ukázkový kód pro formáty Excel do PDF a webové" %}}

```cs
// načíst soubor šablony Excel z disku
var bk = new Workbook("source-file.xlsx");

// převést Excel do PDF pomocí Java
// Vytvořte možnosti PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// uložit Excel v XPS
bk.save("output.xps", new XpsSaveOptions());
// uložit Excel v HTML
bk.save("output.html", new HtmlSaveOptions());
// uložit Excel v Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// před uložením do příslušného formátu lze nastavit příslušné možnosti uložení podle své volby

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte JSON na Excel a Excel na JSON" %}}
Data JSON lze importovat do instance třídy Workbook pomocí [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) pro další zpracování nebo jednoduchý převod do některého z podporovaných formátů. Podobně lze data listu exportovat jako JSON vytvořením a [Rozsah](https://apireference.aspose.com/cells/java/com.aspose.cells/range) nebo buňky a volání [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) metoda.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro převod JSON do Excelu" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Přečtěte si soubor
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Nastavte JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importujte data JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Uložit soubor Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Konverze zdrojového kódu Excelu na JSON" %}}
```cs
// načíst soubor XLSX s instancí sešitu
Workbook workbook = new Workbook("sourceFile.xlsx");
// přístup k CellsCollection listu obsahujícího data, která mají být převedena
Cells cells = workbook.getWorksheets().get(0).getCells();
// vytvořit a nastavit ExportRangeToJsonOptions pro pokročilé možnosti
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// vytvořit oblast buněk obsahujících data k exportu
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// exportovat rozsah jako data JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// zapisovat data na disk ve formátu JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Uložit sešity Excelu do obrázků" %}}
Každý list lze převést do různých obrazových formátů včetně JPG, BMP, PNG a GIF, nastavených vlastností ImageType. Pro jakýkoli případ **Převést Excel na obrázky** vyberte příslušný případ z odkazů.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro převod Excelu na obrázek" %}}
```cs
// načíst šablonu tabulky
var wkb = new Workbook("template.xlsx");

// Vytvořte objekt pro ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Nastavte typ obrázku
imgOptions.setImageType(ImageType.PNG);

// Získejte první pracovní list.
Worksheet sheet = wkb.getWorksheets().get(0);

// Vytvořte objekt SheetRender pro cílový list
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Vygenerujte obrázek pro pracovní list
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Microsoft Excel do Wordu a PowerPointu" %}}
Při používání je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX & PowerPoint PPTX [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Možnosti PptxSave](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro převod Excelu na Word a PowerPoint" %}}
```cs
// načtěte soubor šablony
var wkb = new Workbook("template.xlsx");
// uložit tabulku jako DOCX
wkb.save("output.docx", new DocxSaveOptions());
// uložit tabulku jako PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}