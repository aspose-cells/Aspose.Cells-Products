---
title: Создание файлов MS Excel XLSB с помощью C# 
url: /ru/net/create-xlsb/ 
description: C# Пример кода для создания документов XLSB. Используйте этот код для создания файлов MS Excel XLSB в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Создание документов XLSB через C#" h2="Программное создание встроенных и высокопроизводительных электронных таблиц MS Excel XLSB с использованием серверных .NET API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Динамическое создание файла MS Excel XLSB в запущенном приложении очень просто. Чтобы создавать документы XLSB с нуля, не требуя MS Office, мы будем использовать
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, который предлагает различные функции для создания, обработки и преобразования электронных таблиц с помощью платформы .NET. Разработчики могут легко улучшать код для записи данных, создания диаграмм или графиков, а также создания таблиц в электронных таблицах.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Как создать XLSB через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчикам легко создавать, загружать, изменять и преобразовывать электронные таблицы MS Excel XLSB в рамках запуска различных приложений отчетности для обработки данных всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Включите пространство имен в свой файл класса1. Создайте экземпляр класса Workbook.1. Доступ к первому рабочему листу рабочей книги.1. Получите нужную ячейку (ячейки) рабочего листа и введите значение в ячейку (ячейки).1. Используйте метод Сохранить, чтобы сохранить книгу в виде файла XLSB.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Просто убедитесь, что в системе установлена Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin, а также среда разработки, такая как Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Установить из командной строки как <code>nuget install Aspose.Cells</code> или через консоль диспетчера пакетов Visual Studio с <code>Install-Package Aspose.Cells</code>.- В качестве альтернативы можно получить автономный установщик MSI или все библиотеки DLL в ZIP-файле из <a href="https://downloads.aspose.com/cells/net">загрузки</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В следующем исходном коде показано, как создать XLSB-файл MS Excel с помощью C#." offSpacer="" %}}

```cs

// Создайте экземпляр класса Workbook.
Workbook wkb = new Workbook();

// Доступ к первому рабочему листу рабочей книги.
Worksheet sht = wkb.Worksheets[0];

// Получите нужную ячейку (ячейки) рабочего листа.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// введите значение в ячейку (ячейки).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Сохраните книгу как файл .xlsb.
wkb.Save("created_one.xlsb");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека программирования электронных таблиц Excel, способная создавать кроссплатформенные приложения с возможностью создания, изменения, преобразования, рендеринга и печати файлов MS Excel XLSB. .NET Excel API не только выполняет преобразование между форматами электронных таблиц, но и может отображать файлы Excel в виде изображений, PDF, HTML, ODS и других форматов, что делает его идеальным выбором для обмена документами в стандартных отраслевых форматах.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Формат файла XLSB определяет формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Содержимое может включать неструктурированные или частично структурированные таблицы чисел, текста или и чисел, и текста, формул, подключений к внешним данным, диаграмм и изображений. В отличие от XLSX (который основан на формате файлов Open XML), XLSB представляет собой двоичный файл рабочей книги Excel. Файлы XLSB можно читать и записывать быстрее, что делает их полезными для работы с большими файлами. XLSB редко используется для хранения книг, поскольку XLSX (и ранее XLS) являются наиболее распространенными форматами файлов, выбираемыми пользователем для сохранения книг. Его можно открыть в Microsoft Office 2007 и выше.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другое поддерживаемое создание электронных таблиц" subTitle="Вы также можете создавать другие форматы Microsoft Excel, в том числе некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Электронная таблица Microsoft Excel (предыдущая версия)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="Открытая XML-книга" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Двоичная книга Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="Электронная таблица с поддержкой макросов" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Шаблон Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Шаблон Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Шаблон Excel с поддержкой макросов" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="Значения, разделенные запятыми" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="ТСВ" description="Значения, разделенные табуляцией" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="ОРВ" description="Электронная таблица OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
