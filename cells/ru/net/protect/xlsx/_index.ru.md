---
title:  Защитить и заблокировать XLSX документ via .NET
weight: 90
description: Исходный код C# для блокировки файла XLSX с помощью пароля на платформах .NET Framework, .NET Core, Mono или Xamarin.
keywords: [C# Aspose.Cells., c# Lock XLSX files., c# How to Protect and lock XLSX document., c# Protect XLSX files., Encrypt XLSX Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Зашифровать файлы XLSX через C#" h2="Защитите паролем электронные таблицы Excel, включая формат XLSX, с помощью библиотеки .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как защитить файл XLSX с помощью C#" %}}

 Чтобы защитить файл XLSX, мы будем использовать
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API — многофункциональная, мощная и простая в использовании программа защиты документов API для платформы C#. Открыть
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, найдите
 **Aspose.Cells** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Защитите XLSX через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Тебе нужно
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 указан в вашем проекте для выполнения следующего рабочего процесса.

{{% /blocks/products/pf/agp/text %}}

1.  Создать экземпляр класса рабочей книги с путем к файлу XLSX.
1.  Получите стандартный или любой рабочий лист, чтобы добавить защиту.
1.  Защитите рабочий лист с помощью метода Worksheet.Protect
1.  Защитите книгу с помощью метода Workbook.Protect
1.  Сохранить результат в формате XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono или платформами Xamarin
-  Среда разработки, например Microsoft Visual Studio.
-  Добавьте ссылку на DLL Aspose.Cells for .NET в свой проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="" %}}

```cs

// load the XLSX Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsx");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsx");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Около Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для защиты: XLSX" sectionDescription=" Посмотрите наши живые демонстрации, чтобы[зашифровать XLSX файлы](https://products.aspose.app/cells/protect/xlsx) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл XLSX и нажмите кнопку «Разблокировать»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Скачайте полученный файл XLSX по ссылке" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX — это хорошо известный формат для документов Excel Microsoft, который был представлен Microsoft с выпуском Microsoft Office 2007. Новый формат основан на структуре, организованной в соответствии с соглашениями об открытой упаковке, как указано в части 2 стандарта OOXML ECMA-376. zip-пакет, содержащий несколько файлов XML. Базовую структуру и файлы можно изучить, просто разархивировав файл .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы защиты" subTitle="Используя C#, можно легко защитить другие форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
