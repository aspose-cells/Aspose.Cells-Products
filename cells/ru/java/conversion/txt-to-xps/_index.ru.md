---
title: Преобразование TXT в XPS через Java 
weight: 5270
url: /ru/java/conversion/txt-to-xps/ 
description: Пример кода преобразования Java для формата TXT в файл XPS. Программисты могут использовать этот пример кода для экспорта электронных таблиц Excel и OpenOffice в формат XPS в любом веб- или настольном Java приложении.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование TXT в XPS через Java" h2="Преобразование TXT в XPS Java для преобразования одной или нескольких страниц в XPS с использованием локальной библиотеки Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать TXT в XPS с помощью Java" %}}

 Чтобы преобразовать TXT в XPS, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию TXT в XPS через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики Java могут легко преобразовать файл TXT в XPS, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл TXT с экземпляром класса Workbook1. Вызов метода Workbook.save1. Передайте выходной путь с расширением XPS и SaveFormat в качестве параметров1. Проверить указанный путь для результирующего XPS-файла
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Прежде чем запускать исходный код преобразования Java, убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.Cells for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования TXT в XPS Java" offSpacer="" %}}

```cs
// загрузить файл TXT в экземпляр Workbook
Workbook book = new Workbook("template.txt");
// сохранить TXT как XPS
book.save("output.xps", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование TXT в XPS в реальном времени" sectionDescription="[Конвертировать TXT в XPS](https://products.aspose.app/cells/conversion/txt-to-xps) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл TXT, и он будет мгновенно преобразован в XPS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java Библиотека для работы с электронными таблицами" %}}

 Excel API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в различные форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный API, и для него не требуется никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

Файл с расширением .TXT представляет собой текстовый документ, содержащий обычный текст в виде строк. Абзацы в текстовом документе распознаются возвратом каретки и используются для лучшего расположения содержимого файла. Стандартный текстовый документ можно открыть в любом текстовом редакторе или текстовом редакторе в разных операционных системах. Весь текст, содержащийся в таком файле, имеет удобочитаемый формат и представлен последовательностью символов.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XPS" readMoreLink="https://docs.fileformat.com/page-description-language/xps/" >}}

Файл XPS представляет собой файлы макета страницы, основанные на спецификациях XML Paper, созданных Microsoft. Этот формат был разработан Microsoft в качестве замены формата файла EMF и похож на формат файла PDF, но использует XML в макете, внешнем виде и информации о печати документа. На самом деле более оправданно будет сказать, что XPS является попыткой PDF, но не может получить достаточную популярность как принадлежащий PDF по ряду причин. Microsoft предоставляет XPS Document Writer по умолчанию, начиная с Windows 7, для создания файлов XPS. Файлы XPS можно создать, выбрав «Microsoft XPS Document Writer» в качестве принтера при печати документа.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать TXT во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-bmp/" name="TXT В BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-csv/" name="TXT В CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-dif/" name="TXT В DIF" description="Формат обмена данными" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-emf/" name="TXT В EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-gif/" name="TXT В GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-html/" name="ТЕКСТ В HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-jpeg/" name="TXT В JPEG" description="Изображение в формате JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-mhtml/" name="ОТПРАВИТЬ В MHTML" description="Формат архива веб-страницы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-ods/" name="ОТПРАВИТЬ В ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-pdf/" name="TXT В PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-png/" name="TXT В PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-svg/" name="TXT В SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-tiff/" name="TXT В TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-tsv/" name="TXT В TSV" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlm/" name="TXT В XLM" description="Файл макроса Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xls/" name="TXT В XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlsb/" name="TXT В XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlsx/" name="TXT В XLSX" description="Файл Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlt/" name="TXT В XLT" description="Шаблон Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xltm/" name="TXT В XLTM" description="Шаблон Excel с поддержкой макросов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xltx/" name="TXT В XLTX" description="Шаблон Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-json/" name="ОТПРАВИТЬ В JSON" description="Обозначение объектов JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}