---
title:  Найдите и замените текст в документе XLSM via .NET.
weight: 2370
description: Исходный код C# для редактирования конфиденциальной информации в файле XLSM на платформах .NET Framework, .NET Core, Mono или Xamarin.
keywords: [C# Aspose.Cells., c# Search and replace text in XLSM file., c# redact XLSM file., c# edit XLSM file., c# XLSM file redaction., c# Search and replace string in XLSM file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Редактировать XLSM Форматы в C#" h2="Встроенная и высокопроизводительная XLSM конфиденциальная информация о редактировании документов с использованием серверных API Aspose.Cells for .NET без использования какого-либо программного обеспечения, такого как Microsoft или Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как отредактировать файл XLSM с помощью C#" %}}

 Чтобы отредактировать файл XLSM, мы будем использовать[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API — многофункциональное, мощное и простое в использовании средство для работы с документами API для платформы C#. Открыть[NuGet](https://www.nuget.org/packages/aspose.cells) менеджер пакетов, найдите**Aspose.Cells** и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по удалению файлов XLSM в C#" %}}

{{% blocks/products/pf/agp/text %}}

 Базовый поиск документов и замена текста в содержании, комментариях или метаданных на[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API можно создать с помощью всего нескольких строк кода.

{{% /blocks/products/pf/agp/text %}}

+ Загрузите файл XLSM.
+ Выберите лист.
+ Создать объект FindOptions.
Установить параметры поиска
+ Пройдите по каждой ячейке и используйте метод Find.
+ Сохраните книгу.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Наши API поддерживаются на всех основных платформах и операционных системах. Прежде чем выполнять приведенный ниже код, убедитесь, что в вашей системе имеются следующие необходимые условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono или платформами Xamarin
-  Среда разработки, например Microsoft Visual Studio.
-  Добавьте ссылку на DLL Aspose.Cells for .NET в свой проект. Установите из NuGet, используя кнопку «Загрузить» выше.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Редактировать XLSM Файлы - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.xlsm");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //find only whole word and not part of any word.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.xlsm");

// Find/Replace in whole workbook.

Workbook wb = new Workbook("e:\test2\Input.xlsm");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Около Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Онлайн XLSM Редакция Live Demos" sectionDescription=" Найдите и замените текст в содержании, комментариях или метаданных в документах с номером XLSM прямо сейчас, посетив наш[Веб-сайт живых демонстраций](https://products.aspose.app/cells/redaction). Живая демонстрация имеет следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно скачивать Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файлы XLSM." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Оно будет мгновенно отредактировано." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Файлы с расширением XLSM представляют собой тип файлов электронных таблиц, поддерживающих макросы. С точки зрения приложения макрос — это набор инструкций, которые используются для автоматизации процессов. Макрос используется для записи шагов, которые выполняются повторно, и облегчает выполнение действий путем повторного запуска макроса. Макросы программируются с помощью Visual Basic для приложений (VBA) Microsoft из книги Excel с помощью редактора Visual Basic и могут запускаться/отлаживаться непосредственно оттуда.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы редактирования" subTitle="Используя C#, можно легко редактировать различные форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsx/" name="XLSX" description="OOXML-файл Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
