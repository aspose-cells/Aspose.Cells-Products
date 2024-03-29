---
title:  Просмотр TSV Форматы файлов via .NET
weight: 3090
description: C# исходный код для загрузки, рендеринга и отображения TSV документов на платформах .NET Framework, .NET Core, Mono или Xamarin.
keywords: [C# Aspose.Cells., c# view TSV files., c# how to render TSV document., c# load and display TSV files., TSV File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TSV Средство просмотра файлов for .NET" h2="Просматривайте электронные таблицы Excel и OpenOffice, такие как TSV, не требуя Microsoft Excel или Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как просмотреть файл TSV с помощью C#" %}}

 Чтобы просмотреть файл TSV, мы будем использовать
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API — это многофункциональная, мощная и простая в использовании платформа API для C#, которую можно использовать с любым средством просмотра. Открыть
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, найдите
 **Aspose.Cells** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Консольная команда диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия для просмотра TSV через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells позволяет разработчикам легко просмотреть файл TSV с помощью всего лишь нескольких строк кода.

{{% /blocks/products/pf/agp/text %}}

1.  Загрузите файл TSV в экземпляр рабочей книги.
1.  Создайте экземпляр HtmlSaveOptions и установите для свойства ExportHeadings значение true.
1. Сохраните файл TSV в формате HTML, используя метод Workbook.Save.
1.  Загрузите результат HTML в браузер по умолчанию с помощью Process.Start.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono или платформами Xamarin
-  Среда разработки, например Microsoft Visual Studio.
-  Добавьте ссылку на DLL Aspose.Cells for .NET в свой проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# пример кода для просмотра файла TSV" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the TSV file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.tsv");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the TSV file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Около Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для просмотра: TSV" sectionDescription=" Посмотрите наши живые демонстрации, чтобы[Посмотреть TSV](https://products.aspose.app/cells/viewer/tsv) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл TSV и нажмите кнопку «Просмотреть»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" При необходимости скачайте файл TSV по ссылке." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Формат файла «Значения, разделенные табуляцией» (TSV) представляет данные, разделенные табуляцией, в обычном текстовом формате. Формат файла, аналогичный CSV, используется для структурированной организации данных для импорта и экспорта между различными приложениями. Этот формат в основном используется для импорта/экспорта данных и обмена ими в приложениях и базах данных электронных таблиц. Каждая запись в файле TSV содержится в одной строке текстового файла, где каждое значение поля разделено символом табуляции. Тип носителя для формата файла TSV — текст/значения, разделенные табуляцией.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы просмотра" subTitle="Используя C#, можно также просматривать файлы многих других форматов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXML-файл Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft Шаблон Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Шаблон Excel с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Шаблон Excel для Office OpenXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
