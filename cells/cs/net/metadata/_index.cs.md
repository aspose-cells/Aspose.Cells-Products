---
title: Správa metadat souboru Excel via .NET C#
description: Zobrazte, přidejte, upravte, odeberte nebo extrahujte metadata souborů Excel pomocí několika řádků kódu C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravovat Microsoft<sup>&reg;</sup> Metadata souboru Excel via .NET" h2="Zobrazte, přidejte, aktualizujte, odeberte nebo extrahujte vestavěné a vlastní vlastnosti souborů aplikace Excel pomocí rozhraní API .NET na straně serveru." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/cs/net/) podporuje správu systémem definovaných (vestavěných) vlastností, jako je název, jméno autora, statistika dokumentu atd., stejně jako uživatelsky definované (vlastní) vlastnosti ve formě páru název-hodnota. Tady je[Třída sešitu](https://reference.aspose.com/cells/net/aspose.cells/workbook) k načtení souborů a[Kolekce pracovních listů](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) zabývá se také sběrem pracovních listů[Třída pracovních listů](https://reference.aspose.com/cells/net/aspose.cells/worksheet) pro reprezentaci jednoho listu. Spolu s těmito třídami BuiltInDocumentProperties, CustomDocumentProperties zjednodušují proces správy metadat.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Správa vestavěných vlastností" %}}

 Pro správu vlastností definovaných systémem poskytuje API[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) programátoři mohou snadno přistupovat k vestavěné vlastnosti a aktualizovat její hodnotu. V závislosti na požadavcích aplikace mohou vývojáři použít index nebo název vlastnosti z[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kód pro správu vestavěných vlastností" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Správa uživatelských definovaných vlastností" %}}

 Pro správu uživatelsky definovaných vlastností poskytuje API[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) a vývojáři mohou snadno přistupovat k již přidaným vlastnostem a také přidávat nové vlastnosti. Chcete-li přidat vlastní vlastnosti,[Přidat metodu](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) z[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) třída přidá vlastnost a vrátí odkaz na novou vlastnost jako an[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objekt. Třída DocumentProperty se používá k načtení názvu, hodnoty a typu vlastnosti dokumentu jako[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) který vrací jeden z[Typ majetku](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) výčtové hodnoty.
 
{{% blocks/products/pf/feature-page-code h3="C# Kód pro přidání metadat do souboru aplikace Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kód pro odebrání uživatelské vlastnosti v souboru aplikace Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
