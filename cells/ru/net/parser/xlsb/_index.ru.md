---
title: Извлечение текста и изображений из документа XLSB через .NET 
weight: 2200
url: /ru/net/parser/xlsb/ 
description: Исходный код C# для извлечения текста и изображений из файла XLSB на платформах .NET Framework, .NET Core, Mono или Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Анализ форматов XLSB в C#" h2="Встроенный и высокопроизводительный анализ документов XLSB с использованием серверных Aspose.Cells for .NET API без использования какого-либо программного обеспечения, такого как Microsoft или Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как анализировать файл XLSB с помощью C#" %}}

 Чтобы разобрать файл XLSB, мы будем использовать
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, многофункциональное, мощное и простое в использовании средство для работы с документами API для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, поиск
 **Aspose.Cells** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по анализу файлов XLSB в C#" %}}

{{% blocks/products/pf/agp/text %}}

 Базовый разбор документа с
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API можно реализовать всего несколькими строками кода. Анализируйте текст и изображения из файлов Microsoft Excel XLS, XLSX, XLSM, XLSB и OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ Загрузить документ XLSB.
+ Выберите лист.
+ Получить изображение и тип изображения.
+ Сохраните изображение.
+ Сохранить документ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Наши API поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Mono или Xamarin.- Среда разработки, такая как Microsoft Visual Studio- Aspose.Cells for .NET DLL, на которые есть ссылка в вашем проекте. Установите из NuGet с помощью кнопки «Загрузить» выше.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Разобрать файлы XLSB — C#" offSpacer="" %}}

```cs
    // извлекать изображения из рабочих листов 
    // открыть файл шаблона Excel
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.xlsb");
    
    // получить первый рабочий лист
    Worksheet worksheet = workbook.Worksheets[0];
    
    // получить первое изображение на первом листе
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // установить путь к файлу выходного изображения
    string picformat = pic.ImageType.ToString();
                
    // Примечание: вы можете оценить формат изображения, прежде чем указывать путь к изображению.
    // определить ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // указать формат изображения
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // сохранить изображение
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.Cells for .NET API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в другие форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells является автономным API и не требует никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-демонстрации парсера XLSB" sectionDescription="Извлекайте текст и изображения из документов XLSB прямо сейчас, посетив наш [Веб-сайт живых демонстраций](https://products.aspose.app/cells/parser). Живая демонстрация имеет следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файлы XLSB." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Он будет проанализирован мгновенно." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Формат файла XLSB определяет формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Содержимое может включать неструктурированные или частично структурированные таблицы чисел, текста или и чисел, и текста, формул, подключений к внешним данным, диаграмм и изображений. В отличие от XLSX (который основан на формате файлов Open XML), XLSB представляет собой двоичный файл рабочей книги Excel. Файлы XLSB можно читать и записывать быстрее, что делает их полезными для работы с большими файлами. XLSB редко используется для хранения книг, поскольку XLSX (и ранее XLS) являются наиболее распространенными форматами файлов, выбираемыми пользователем для сохранения книг. Его можно открыть в Microsoft Office 2007 и выше. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы синтаксического анализа" subTitle="Используя C#, можно легко анализировать другие форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/ods/" name="ОРВ" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}