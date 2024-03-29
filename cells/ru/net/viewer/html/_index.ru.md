---
title:  Просмотр HTML Форматы файлов via .NET
description: C# исходный код для загрузки, обработки и отображения HTML документов на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
keywords: [C# Aspose.Cells., c# view HTML files., c# how to render HTML document., c# load and display HTML files., HTML File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="HTML Средство просмотра файлов for .NET" h2="Просматривайте электронные таблицы Excel и OpenOffice, такие как HTML, не требуя Microsoft Excel или Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как просмотреть файл HTML с помощью C#" %}}

 Чтобы просмотреть файл HTML, мы будем использовать<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API — это многофункциональная, мощная и простая в использовании платформа API для C#, которую можно использовать с любым средством просмотра. Открыть<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> менеджер пакетов, найдите<b>Aspose.Cells</b> и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Консольная команда диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия для просмотра HTML через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells позволяет разработчикам легко просмотреть файл HTML с помощью всего лишь нескольких строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл HTML в экземпляр рабочей книги.
1. Создайте экземпляр HtmlSaveOptions и установите для свойства ExportHeadings значение true.
1. Сохраните файл HTML в формате HTML, используя метод Workbook.Save.
1. Загрузите результат HTML в браузер по умолчанию с помощью Process.Start.


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin Platforms.
-  Среда разработки, например Microsoft Visual Studio.
-  Добавьте ссылку на DLL Aspose.Cells for .NET в свой проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# пример кода для просмотра файла HTML" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the HTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.html");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the HTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для просмотра: HTML" sectionDescription=" Посмотрите наши живые демонстрации, чтобы[Посмотреть HTML](https://products.aspose.app/cells/viewer/html) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл HTML и нажмите кнопку «Просмотреть»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" При необходимости скачайте файл HTML по ссылке." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (язык гипертекстовой разметки) — это расширение для веб-страниц, созданное для отображения в браузерах. Известный как язык Интернета, HTML развился в соответствии с новыми требованиями к информации, которая должна отображаться как часть веб-страниц. Последний вариант известен как HTML 5, что дает большую гибкость при работе с языком. Страницы HTML либо получены с сервера, на котором они размещены, либо также могут быть загружены из локальной системы. Каждая страница HTML состоит из HTML элементов, таких как формы, текст, изображения, анимация, ссылки и т. д. Эти элементы представлены такими тегами, как img, a, p и некоторыми другими, где каждый тег имеет начало и конец. Он также может встраивать приложения, написанные на языках сценариев, таких как JavaScript и таблицы стилей (CSS), для общего представления макета.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
