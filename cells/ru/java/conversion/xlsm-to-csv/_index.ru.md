---
title: Преобразование XLSM в CSV через Java 
weight: 9910
url: /ru/java/conversion/xlsm-to-csv/ 
description: Пример кода преобразования Java для формата XLSM в файл CSV. Программисты могут использовать этот пример кода для экспорта электронных таблиц Excel и OpenOffice в CSV в любом веб-или настольном Java приложении.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование XLSM в CSV через Java" h2="Преобразование XLSM в CSV Java для преобразования одной или нескольких страниц в CSV с использованием локальной библиотеки Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="CSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать XLSM в CSV с помощью Java" %}}

 Чтобы преобразовать XLSM в CSV, мы будем использовать
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API – это многофункциональная, мощная и простая в использовании платформа преобразования API for Java. Вы можете скачать его последнюю версию прямо с
 [Мавен](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://репозиторий.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Зависимость" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию XLSM в CSV через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики Java могут легко преобразовать файл XLSM в CSV, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл XLSM с экземпляром класса Workbook1. Вызов метода Workbook.save1. Передайте выходной путь с расширением CSV и SaveFormat в качестве параметров1. Проверить указанный путь для результирующего CSV-файла
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Прежде чем запускать исходный код преобразования Java, убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.Cells for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования XLSM в CSV Java" offSpacer="" %}}

```cs
// загрузить файл XLSM в экземпляр Workbook
Workbook book = new Workbook("template.xlsm");
// сохранить XLSM как CSV
book.save("output.csv", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование XLSM в CSV в реальном времени" sectionDescription="[Конвертировать XLSM в CSV](https://products.aspose.app/cells/conversion/xlsm-to-csv) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл XLSM, и он будет мгновенно преобразован в CSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java Библиотека для работы с электронными таблицами" %}}

 Excel API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в различные форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный API, и для него не требуется никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

Файлы с расширением XLSM — это тип файлов электронных таблиц, поддерживающих макросы. С точки зрения приложения макрос — это набор инструкций, которые используются для автоматизации процессов. Макрос используется для записи повторяющихся шагов и облегчает выполнение действий путем повторного запуска макроса. Макросы программируются с помощью Microsoft Visual Basic для приложений (VBA) из рабочей книги Excel с помощью редактора Visual Basic, и их можно запускать/отлаживать непосредственно из него.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Файлы с расширением CSV (значения, разделенные запятыми) представляют собой простые текстовые файлы, которые содержат записи данных со значениями, разделенными запятыми. Каждая строка в CSV-файле — это новая запись из набора записей, содержащихся в файле. Такие файлы формируются, когда предполагается перенос данных из одной системы хранения в другую. Поскольку все приложения умеют распознавать записи через запятую, импорт таких файлов данных в базу данных осуществляется очень удобно. Почти все приложения для работы с электронными таблицами, такие как Microsoft Excel или OpenOffice Calc, могут импортировать CSV без особых усилий. Данные, импортированные из таких файлов, располагаются в ячейках электронной таблицы для представления пользователю.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать XLSM во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-bmp/" name="XLSM В БМП" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-dif/" name="XLSM В ДИФ" description="Формат обмена данными" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-emf/" name="XLSM В ЭДС" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-gif/" name="XLSM в GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-html/" name="XLSM В HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-jpeg/" name="XLSM В JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-mhtml/" name="XLSM В MHTML" description="Формат архива веб-страницы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-ods/" name="XLSM в ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-pdf/" name="XLSM В PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-png/" name="XLSM В PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-svg/" name="XLSM В SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-tiff/" name="XLSM В TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-tsv/" name="XLSM В ТСВ" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-txt/" name="XLSM В TXT" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xls/" name="XLSM В XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlsb/" name="XLSM В XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlsx/" name="XLSM В XLSX" description="Файл Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlt/" name="XLSM В XLT" description="Шаблон Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xltm/" name="XLSM В XLTM" description="Шаблон Excel с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xltx/" name="XLSM В XLTX" description="Шаблон Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xps/" name="XLSM В XPS" description="Спецификации XML-бумаги" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-json/" name="XLSM В JSON" description="Обозначение объектов JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}