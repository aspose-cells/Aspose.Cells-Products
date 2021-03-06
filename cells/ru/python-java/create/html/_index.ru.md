---
title: Создание файлов HTML с помощью Python 
url: /ru/python-java/create-html/ 
description: Python Пример кода для создания HTML-документов. Используйте этот код для создания файлов HTML в приложении Python.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Создавайте HTML-документы с помощью Python" h2="Создание собственного и высокопроизводительного HTML (языка гипертекстовой разметки) программным путем с использованием Python API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Динамическое создание HTML-файла в запущенном приложении очень просто. Чтобы создавать HTML-документы с нуля, не требуя MS Office, мы будем использовать
 [Aspose.Cells для Python](https://pypi.org/project/aspose-cells) 
 API, который предлагает различные функции для создания, обработки и преобразования электронных таблиц с помощью платформы Python. Разработчики могут легко улучшать код для записи данных, создания диаграмм или графиков, а также создания таблиц в электронных таблицах.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать HTML с помощью Python" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики могут легко создавать, загружать, изменять и преобразовывать HTML (язык гипертекстовой разметки) в рамках запуска различных приложений отчетности для обработки данных всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Импортируйте asposecells в файл кода.1. Создайте экземпляр класса Workbook.1. Доступ к первому рабочему листу рабочей книги.1. Получите нужную ячейку (ячейки) рабочего листа и введите значение в ячейку (ячейки).1. Используйте метод Сохранить, чтобы сохранить книгу в виде HTML-файла.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells для Python через Java не зависит от платформы API и может использоваться на любой платформе (Windows, Linux и MacOS), просто убедитесь, что в системе установлена Java 1.8 или выше, [Python](https://www.python.org/downloads/) 3,5 или выше. 

{{% /blocks/products/pf/agp/text %}}

- Установите Java и добавьте его в переменную среды PATH, например: <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- Установите Aspose.Cells для Python через Java из <a href="https://pypi.org/project/aspose-cells/">пипи</a>, используйте команду как: <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В следующем исходном коде показано, как создать файл HTML с помощью Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Создать объект «Книга».
workbook = Workbook(FileFormatType.HTML)

// Доступ к первому рабочему листу рабочей книги.
worksheet = workbook.getWorksheets().get(0)

// Получите нужную ячейку (ячейки) рабочего листа и введите значение в ячейку (ячейки).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Сохраните книгу как файл HTML.
workbook.save("output.html")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека программирования электронных таблиц Excel, способная создавать кроссплатформенные приложения с возможностью создания, изменения, преобразования, рендеринга и печати HTML-файлов. Python API не только преобразует форматы электронных таблиц, но и может отображать файлы Excel в виде изображений, PDF, HTML, ODS и других форматов, что делает его идеальным выбором для обмена документами в стандартных отраслевых форматах.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) — это расширение для веб-страниц, созданных для отображения в браузерах. HTML, известный как язык Интернета, развивался с учетом новых требований к информации, которая должна отображаться как часть веб-страниц. Последний вариант известен как HTML 5, что дает большую гибкость для работы с языком. HTML-страницы либо принимаются с сервера, на котором они размещены, либо также могут быть загружены из локальной системы. Каждая HTML-страница состоит из HTML-элементов, таких как формы, текст, изображения, анимация, ссылки и т. д. Эти элементы представлены тегами и несколькими другими, где каждый тег имеет начало и конец. Он также может встраивать приложения, написанные на языках сценариев, таких как JavaScript и таблицы стилей (CSS), для общего представления макета.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другое поддерживаемое создание электронных таблиц" subTitle="Вы также можете создавать другие форматы Microsoft Excel, в том числе некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Электронная таблица Microsoft Excel (предыдущая версия)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="Открытая XML-книга" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Двоичная книга Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="Электронная таблица с поддержкой макросов" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Шаблон Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Шаблон Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Шаблон Excel с поддержкой макросов" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="Значения, разделенные запятыми" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="ТСВ" description="Значения, разделенные табуляцией" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ОРВ" description="Электронная таблица OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
