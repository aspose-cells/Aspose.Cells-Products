---
title:  Поиск документа ODS без открытия через C++
weight: 3300
description: C++ пример кода для поиска слов по шаблону в файле ODS в среде выполнения C++ для Windows 32-разрядной версии, Windows 64-разрядной версии и 64-разрядной версии Linux.
keywords: [C++ Aspose.Cells., C++ search words with pattern in ods file., C++ find words with pattern in ods file., C++ search string with pattern in ods file., C++ find words with pattern in ods file., C++ search words in ods file., C++ find words in ods file., C++ search string in ods file., C++ find string in ods file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Поиск форматов ODS в C++" h2="Собственный высокопроизводительный поиск документов ODS с использованием серверных API Aspose.Cells for C++ без использования какого-либо программного обеспечения, такого как Microsoft или Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как выполнить поиск файла ODS с помощью C++" %}}

 Для поиска файла ODS мы будем использовать
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API — это многофункциональная, мощная и простая в использовании платформа для поиска документов. API for C++. Вы можете скачать последнюю версию напрямую, просто откройте
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, найдите
 **Aspose.Cells.Cpp** 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по поиску файлов ODS в C++" %}}

{{% blocks/products/pf/agp/text %}}

 Базовый поиск документов с использованием API Aspose.Cells можно выполнить всего с помощью нескольких строк кода.

{{% /blocks/products/pf/agp/text %}}

+ Загрузите файл ODS, создав экземпляр класса Workbook.
+ Создать экземпляр класса replaceOptions.
+ Установите необходимый шаблон, например SetCaseSensitive(bool value), SetMatchEntireCellContents(bool value) .
Используйте метод Workbook::Replace(...) с соответствующими параметрами.
+ Сохраните файл ODS с помощью метода Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ поддерживает все основные платформы и операционные системы. Пожалуйста, убедитесь, что у вас есть следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с C++ Runtime Environment для Windows 32-разрядной версии, Windows 64-разрядной версии и 64-разрядной версии Linux.
-  Добавьте ссылку на DLL Aspose.Cells for C++ в свой проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Поиск ODS Файлов - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load ODS file
Workbook  wkb(srcDir + u"sourceFile.ods");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as ODS file
wkb.Save(outDir + u"outputFile.ods");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Около Aspose.Cells for C++ API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Онлайн ODS Поиск живых демонстраций" sectionDescription=" Найдите текст, слова, фразы в ODS документах прямо сейчас, посетив наш[Веб-сайт живых демонстраций](https://products.aspose.app/cells/search). Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно скачивать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файлы ODS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Результат поиска появляется мгновенно." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS " readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Файлы с расширением ODS обозначают формат документа электронной таблицы OpenDocument, который может редактировать пользователь. Данные хранятся внутри файла ODF в строках и столбцах. Это формат на основе XML, который является одним из нескольких подтипов семейства форматов открытых документов (ODF). Формат указан как часть спецификаций ODF 1.2, опубликованных и поддерживаемых OASIS. Ряд приложений в Windows, а также в других операционных системах могут открывать файлы ODS для редактирования и манипулирования, включая Microsoft Excel, NeoOffice и LibreOffice. Файлы ODS также можно конвертировать в другие форматы электронных таблиц, например XLS, XLSX и другие, с помощью различных приложений.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые документы поиска" subTitle="Используя C++, можно также искать другие файлы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
