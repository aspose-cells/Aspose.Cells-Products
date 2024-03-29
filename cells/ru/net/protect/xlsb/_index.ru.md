---
title:  Защитить и заблокировать XLSB документ via .NET
weight: 5920
description: Исходный код C# для блокировки файла XLSB с помощью пароля на платформах .NET Framework, .NET Core, Mono или Xamarin.
keywords: [C# Aspose.Cells., c# Lock XLSB files., c# How to Protect and lock XLSB document., c# Protect XLSB files., Encrypt XLSB Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Зашифровать файлы XLSB через C#" h2="Защитите паролем электронные таблицы Excel, включая формат XLSB, с помощью библиотеки .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как защитить файл XLSB с помощью C#" %}}

 Чтобы защитить файл XLSB, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Защитите XLSB через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Тебе нужно
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 указан в вашем проекте для выполнения следующего рабочего процесса.

{{% /blocks/products/pf/agp/text %}}

1.  Создать экземпляр класса рабочей книги с путем к файлу XLSB.
1.  Получите стандартный или любой рабочий лист, чтобы добавить защиту.
1.  Защитите рабочий лист с помощью метода Worksheet.Protect
1.  Защитите книгу с помощью метода Workbook.Protect
1.  Сохранить результат в формате XLSB

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

// load the XLSB Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsb");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Около Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для защиты: XLSB" sectionDescription=" Посмотрите наши живые демонстрации, чтобы[зашифровать XLSB файлы](https://products.aspose.app/cells/protect/xlsb) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл XLSB и нажмите кнопку «Разблокировать»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Скачайте полученный файл XLSB по ссылке" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Формат файла XLSB определяет формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Содержимое может включать неструктурированные или полуструктурированные таблицы чисел, текста или чисел и текста, формулы, подключения к внешним данным, диаграммы и изображения. В отличие от XLSX (который основан на формате файла Open XML), XLSB представляет собой двоичный файл книги Excel. Файлы XLSB можно читать и записывать быстрее, что делает их полезными для работы с большими файлами. XLSB редко используется для хранения книг, поскольку XLSX (а ранее XLS) — это наиболее распространенные форматы файлов, выбираемые пользователем для сохранения книг. Его можно открыть с помощью Microsoft Office 2007 и выше.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы защиты" subTitle="Используя C#, можно легко защитить другие форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="OOXML-файл Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
