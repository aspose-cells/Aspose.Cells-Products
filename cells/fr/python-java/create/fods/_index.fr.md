---
title: Créer FODS - Créer un fichier FODS dans Python
description: Aspose Exceller. Python Exceller. Python Créez un fichier FODS rapidement et facilement avec Aspose.Cells. Générez un fichier FODS à l'aide de la bibliothèque Excel Python. Créez FODS dans la bibliothèque Excel Python. Python FODS Créateur.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create FODS file., Generate FODS file in Python Excel Library., Create FODS file using Python Excel Library., Write data to FODS file via Python Excel Library., Create a FODS file in Python Excel Library., Python Generate a FODS file., Python FODS Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créer un fichier FODS dans la bibliothèque Excel Python" h2="Bibliothèque Excel Python haute vitesse pour créer le fichier FODS. Il s\'agit d\'une solution logicielle professionnelle pour importer et exporter XLSX, PDF et de nombreux autres formats utilisant Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="FODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Créer un fichier FODS à l\'aide de la bibliothèque Excel Python" %}}

 Comment créer le fichier FODS ? Avec la bibliothèque Excel Aspose.Cells for Python via Java, vous pouvez facilement créer un fichier FODS par programme avec quelques lignes de code.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)est capable de créer des applications multiplateformes avec la possibilité de générer, modifier, convertir, restituer et imprimer tous les fichiers Excel. Python Excel API convertit non seulement entre les formats de feuilles de calcul, il peut également restituer des fichiers Excel sous forme d'images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT et plus, ce qui en fait un choix parfait pour échanger des documents dans des formats standard de l'industrie.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Comment créer FODS dans la bibliothèque Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de créer, charger, modifier et convertir des fichiers FODS en exécutant différentes applications de reporting pour le traitement des données en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1.  Importez des asposecells dans votre fichier de code.
1.  Créez une instance de classe Workbook.
1.  Accédez à la première feuille de calcul du classeur.
1. Obtenez la ou les cellules souhaitées de la feuille de calcul et saisissez la valeur dans la ou les cellules.
1.  Utilisez la méthode Save pour enregistrer le classeur en tant que fichier FODS.

{{% blocks/products/pf/agp/code-block title="Un exemple de code montre comment créer le fichier FODS dans la bibliothèque Excel Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.FODS)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as FODS file.
workbook.save("output.fods")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Bibliothèque Excel Python pour créer un fichier FODS" %}}

{{% blocks/products/pf/agp/text %}}

Il existe trois options pour installer « Aspose.Cells for Python via Java » sur votre système. Veuillez en choisir un qui correspond à vos besoins et suivre les instructions étape par étape :

{{% /blocks/products/pf/agp/text %}}

1.  Installez Aspose.Cells for Python via Java dans Windows. Voir[Documentation](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Installez Aspose.Cells for Python via Java sous Linux. Voir[Documentation](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  Installez Aspose.Cells for Python via Java sous macOS. Voir[Documentation](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java est indépendant de la plate-forme API et peut être utilisé sur n'importe quelle plate-forme (Windows, Linux et MacOS), assurez-vous simplement que le système dispose de Java 1.8 ou supérieur,[Python](https://www.python.org/downloads/) 3,5 ou supérieur.

{{% /blocks/products/pf/agp/text %}}

-  Installez Java et ajoutez-le à la variable d'environnement PATH, par exemple :<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Installez Aspose.Cells for Python via Java à partir de<a href="https://pypi.org/project/aspose-cells/">pypi</a> , utilisez la commande comme :<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FODS" readMoreLink="https://docs.fileformat.com/spreadsheet/fods/" >}}Un fichier avec l'extension .fods est un type de format de document OpenDocument Spreadsheet qui stocke les données dans des lignes et des colonnes. Le format est spécifié dans le cadre des spécifications ODF 1.2 publiées et maintenues par OASIS. Les fichiers FODS ne peuvent pas être ouverts avec Excel, un autre logiciel de feuille de calcul de Microsoft. Les fichiers FODS peuvent être enregistrés sous le nom ODS à l'aide de LibreOffice et peuvent être convertis dans d'autres formats tels que XLS et XLSX.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres générations de feuilles de calcul prises en charge" subTitle="Vous pouvez également créer d’autres formats Excel Microsoft, dont quelques-uns répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Feuille de calcul Excel (ancienne version)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="Classeur XML ouvert" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Classeur binaire Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="Feuille de calcul prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Modèle Excel 97-2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Modèle Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Modèle Excel prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="Valeurs séparées par des virgules" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="Valeurs séparées par des tabulations" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="Feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="Portable Document Format" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="Langage Signalétique Hyper Text" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
