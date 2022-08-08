---
title: Kommentare in Excel über .NET einfügen
url: /de/net/comment/
description: C#-Quellcodes zum Einfügen von Kommentaren in Microsoft Excel-Dateien mithilfe der .NET-Bibliothek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Einfügen von Microsoft<sup>&reg;</sup> Excel-Kommentaren über .NET" h2="Erstellen Sie Excel-Dokumente und fügen Sie Kommentare mit serverseitigen APIs in .NET-basierten Anwendungen ein." >}}
{{% blocks/products/pf/feature-page-summary %}}

Sie können Zellen Kommentare hinzufügen. Wenn eine Zelle einen Kommentar enthält, erscheint eine Anzeige in der Ecke der Zelle. Kommentare werden angezeigt, wenn Sie den Mauszeiger über eine Zelle bewegen. Diese Kommentare können für Diskussionen, spezielle Anweisungen oder Markierungen von Dokumentinhalten verwendet werden [.NET Excel-Bibliothek](/cells/net/) unterstützt das Einfügen von Kommentaren in Excel-Dateien. Dafür bietet die API eine [Kommentar](https://reference.aspose.com/cells/net/aspose.cells/comment) Klasse für den Kommentarbaustein.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kommentare in Excel-Datei einfügen" %}}

Das Einfügen von Kommentaren mit Excel API ist einfach. Prozess ist, erstellen [Klasse Arbeitsbuch](https://reference.aspose.com/cells/net/aspose.cells/workbook) Objekt und wählen Sie das erste Arbeitsblatt oder das relevante Blatt aus, indem Sie seinen Index angeben. Fügen Sie die erforderlichen Zellendaten mit ein [PutValue-Methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Fügen Sie dem Arbeitsblatt einen Kommentar hinzu, indem Sie verwenden [Kommentarsammlung](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Methode hinzufügen](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Code zum Einfügen eines Kommentars in Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
