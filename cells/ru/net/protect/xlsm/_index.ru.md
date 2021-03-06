---
title: Защитите и заблокируйте документ XLSM через .NET 
weight: 7530
url: /ru/net/protect/xlsm/ 
description: Исходный код C# для блокировки файла XLSM с помощью пароля на платформах .NET Framework, .NET Core, Mono или Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Шифровать файлы XLSM с помощью C#" h2="Защищайте паролем электронные таблицы Excel, включая формат XLSM, с помощью библиотеки .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как защитить файл XLSM с помощью C#" %}}

 Чтобы защитить файл XLSM, мы будем использовать
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API — многофункциональное, мощное и простое в использовании средство защиты документов API для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, поиск
 **Aspose.Cells** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Защитите XLSM через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Тебе нужно
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 ссылки в вашем проекте для выполнения следующего рабочего процесса.

{{% /blocks/products/pf/agp/text %}}

1. Создать экземпляр класса Workbook с путем к файлу XLSM1. Получите стандартный или любой рабочий лист, чтобы добавить защиту1. Защитите рабочий лист с помощью метода Worksheet.Protect1. Защитите книгу с помощью метода Workbook.Protect1. Сохранить результат в формате XLSM
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Mono или Xamarin.- Среда разработки, такая как Microsoft Visual Studio- Aspose.Cells for .NET упоминается в вашем проекте
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="" %}}

```cs

// загрузить файл XLSM Excel 
var book = new Aspose.Cells.Workbook("unlocked.xlsm");

// получить доступ к первому рабочему листу
var worksheet = book.Worksheets[0];

// защитить лист паролем
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// защитить всю книгу паролем
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// сохранить измененный файл в формате по умолчанию
book.Save("protected.xlsm");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в другие форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells является автономным API и не требует никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для защиты XLSM" sectionDescription="Проверьте наши живые демонстрации, чтобы [шифровать файлы XLSM](https://products.aspose.app/cells/protect/xlsm) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл XLSM и нажмите кнопку «Разблокировать»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Загрузите полученный файл XLSM по ссылке" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Файлы с расширением XLSM — это тип файлов электронных таблиц, поддерживающих макросы. С точки зрения приложения макрос — это набор инструкций, которые используются для автоматизации процессов. Макрос используется для записи повторяющихся шагов и облегчает выполнение действий путем повторного запуска макроса. Макросы программируются с помощью Microsoft Visual Basic для приложений (VBA) из рабочей книги Excel с помощью редактора Visual Basic, и их можно запускать/отлаживать непосредственно из него.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы защиты" subTitle="Используя C#, можно легко защитить другие форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ОРВ" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="Файл Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}