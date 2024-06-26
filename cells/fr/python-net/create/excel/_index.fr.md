---
title: Créer EXCEL - Créer un fichier EXCEL dans Python
description: Aspose Exceller. Python Exceller. Python Créez un fichier EXCEL rapidement et facilement avec Aspose.Cells. Générez un fichier EXCEL à l'aide de la bibliothèque Excel Python. Créez EXCEL dans la bibliothèque Excel Python. Python Créateur EXCEL.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create EXCEL file., Generate EXCEL file in Python Excel Library., Create EXCEL file using Python Excel Library., Write data to EXCEL file via Python Excel Library., Create a EXCEL file in Python Excel Library., Python Generate a EXCEL file., Python EXCEL Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créer un fichier EXCEL dans la bibliothèque Excel Python" h2="Bibliothèque Excel Python haute vitesse pour créer un fichier EXCEL. Utilisez notre conversion Excel API pour développer un logiciel de haut niveau indépendant de la plate-forme en Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="EXCEL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-net/" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Créer un fichier EXCEL à l\'aide de la bibliothèque Excel Python" %}}

 Comment créer un fichier EXCEL ? Avec la bibliothèque Excel Aspose.Cells for Python via NET, vous pouvez facilement créer un fichier EXCEL par programme avec quelques lignes de code.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells-python/)est capable de créer des applications multiplateformes avec la possibilité de générer, modifier, convertir, restituer et imprimer tous les fichiers Excel. Python Excel API convertit non seulement entre les formats de feuilles de calcul, il peut également restituer des fichiers Excel sous forme d'images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT et plus, ce qui en fait un choix parfait pour échanger des documents dans des formats standard de l'industrie.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Comment créer EXCEL dans la bibliothèque Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de créer, charger, modifier et convertir des fichiers EXCEL en exécutant différentes applications de reporting pour le traitement des données en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1.  Créez une instance de classe Workbook.
1.  Accédez à la première feuille de calcul du classeur.
1. Obtenez la ou les cellules souhaitées de la feuille de calcul et saisissez la valeur dans la ou les cellules.
1.  Utilisez la méthode Save pour enregistrer le classeur en tant que fichier EXCEL.

{{% blocks/products/pf/agp/code-block title="Un exemple de code montre comment créer un fichier EXCEL dans la bibliothèque Excel Python." offSpacer="" %}}

```cs

from aspose import pycore
from aspose.cells import Workbook, SaveFormat, FileFormatType

# Create Workbook object.
workbook = Workbook()

# Access the first worksheet of the workbook.
worksheet = workbook.worksheets[0]

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.cells.get("A1").put_value("ColumnA")
worksheet.cells.get("B1").put_value("ColumnB")
worksheet.cells.get("A2").put_value("ValueA")
worksheet.cells.get("B2").put_value("ValueB")

# Save the workbook as EXCEL file.
workbook.save("output.xlsx")

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Bibliothèque Excel pour créer un fichier EXCEL" %}}

Nous hébergeons nos packages Python dans des référentiels PyPi.

{{% blocks/products/pf/agp/text %}}
 Installez Aspose.Cells for Python à partir de<a href="https://pypi.org/project/aspose-cells-python/">pypi</a> , utilisez la commande comme :<code>$ pip install aspose-cells-python</code>.
{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/text %}}
 Et vous pouvez également suivre le[instructions étape par étape](https://docs.aspose.com/cells/python-net/getting-started/) sur la façon d'installer "Aspose.Cells for Python via .NET" dans votre environnement de développeur.
{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python est indépendant de la plate-forme API et peut être utilisé sur n'importe quelle plate-forme (Windows, Linux), assurez-vous simplement que le système dispose[Python](https://www.python.org/downloads/) 3.7 ou supérieur.
 
{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EXCEL" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}XLSX est un format bien connu pour les documents Excel Microsoft qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. Basé sur une structure organisée selon les conventions d'emballage ouvertes telles que décrites dans la partie 2 de la norme OOXML ECMA-376, le nouveau format est un package zip contenant un certain nombre de fichiers XML. La structure et les fichiers sous-jacents peuvent être examinés en décompressant simplement le fichier .xlsx.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres générations de feuilles de calcul prises en charge" subTitle="Vous pouvez également créer d’autres formats Excel Microsoft, dont quelques-uns répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xls/" name="XLS" description="Microsoft Feuille de calcul Excel (ancienne version)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsx/" name="XLSX" description="Classeur XML ouvert" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsb/" name="XLSB" description="Classeur binaire Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlsm/" name="XLSM" description="Feuille de calcul prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xlt/" name="XLT" description="Modèle Excel 97-2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltx/" name="XLTX" description="Modèle Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/xltm/" name="XLTM" description="Modèle Excel prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/csv/" name="CSV" description="Valeurs séparées par des virgules" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/tsv/" name="TSV" description="Valeurs séparées par des tabulations" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/ods/" name="ODS" description="Feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/pdf/" name="PDF" description="Portable Document Format" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create/html/" name="HTML" description="Langage Signalétique Hyper Text" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
