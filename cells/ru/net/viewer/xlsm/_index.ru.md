---
title: Просмотр форматов файлов XLSM через .NET 
weight: 9980
url: /ru/net/viewer/xlsm/ 
description: Исходный код C# для загрузки, обработки и отображения документов XLSM на платформах .NET Framework, .NET Core, Mono или Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Средство просмотра файлов XLSM for .NET" h2="Просматривайте электронные таблицы Excel и OpenOffice, такие как XLSM, без использования Microsoft Excel или Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как просмотреть файл XLSM с помощью C#" %}}

 Для просмотра файла XLSM мы будем использовать
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API — многофункциональная, мощная и простая в использовании платформа API для C#, которую можно использовать с любым средством просмотра. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, поиск
 **Aspose.Cells** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия для просмотра XLSM через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells позволяет разработчикам легко просматривать файл XLSM, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл XLSM в экземпляр Workbook.1. Создайте экземпляр HtmlSaveOptions и установите для свойства ExportHeadings значение true.1. Сохраните файл XLSM в формате HTML, используя метод Workbook.Save.1. Загрузите результирующий HTML в браузере по умолчанию с помощью Process.Start
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Mono или Xamarin.- Среда разработки, такая как Microsoft Visual Studio- Aspose.Cells for .NET упоминается в вашем проекте
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# пример кода для просмотра файла XLSM" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// загрузить файл XLSM в экземпляр Workbook
var book = new Aspose.Cells.Workbook("template.xlsm");
// создайте экземпляр HtmlSaveOptions и установите для свойства ExportHeadings значение true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// сохранить файл XLSM в формате HTML
book.Save(output, options);
// загрузить результирующий HTML в браузере по умолчанию
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в другие форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells является автономным API и не требует никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для просмотра XLSM" sectionDescription="Проверьте наши живые демонстрации, чтобы [Посмотреть XLSM](https://products.aspose.app/cells/viewer/xlsm) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл XLSM и нажмите кнопку «Просмотреть»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Скачать файл XLSM по ссылке, если требуется" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Файлы с расширением XLSM — это тип файлов электронных таблиц, поддерживающих макросы. С точки зрения приложения макрос — это набор инструкций, которые используются для автоматизации процессов. Макрос используется для записи повторяющихся шагов и облегчает выполнение действий путем повторного запуска макроса. Макросы программируются с помощью Microsoft Visual Basic для приложений (VBA) из рабочей книги Excel с помощью редактора Visual Basic, и их можно запускать/отлаживать непосредственно из него.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы просмотра" subTitle="Используя C#, можно также просматривать многие другие форматы файлов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ОРВ" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="ТСВ" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="ТЕКСТ" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="Файл Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Шаблон Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Шаблон Excel с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Шаблон Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}