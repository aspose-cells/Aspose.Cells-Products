---
title: Преобразование SXC в JPEG через Java 
url: /ru/java/conversion/sxc-to-jpeg/ 
description: Пример кода преобразования Java для формата SXC в файл JPEG. Программисты могут использовать этот пример кода для экспорта электронных таблиц Excel и OpenOffice в формат JPEG в любом веб- или настольном Java приложении.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование SXC в JPEG через Java" h2="Преобразование SXC в JPEG Java для преобразования одной или нескольких страниц в JPEG с использованием локальной библиотеки Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SXC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать SXC в JPEG с помощью Java" %}}

 Чтобы преобразовать SXC в JPEG, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию SXC в JPEG через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики Java могут легко преобразовать файл SXC в JPEG, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл SXC с экземпляром Workbook1. Выберите по умолчанию или любой рабочий лист из коллекции1. Создайте и установите объект ImageOrPrintOptions1. Создайте SheetRender с объектами Worksheet и ImageOrPrintOptions1. Вызов метода SheetRender.toImage для сохранения результата в формате JPEG

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Прежде чем запускать исходный код преобразования Java, убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.Cells for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования SXC в JPEG Java" offSpacer="" %}}

```cs
// загрузить файл SXC для рендеринга
Workbook workbook = new Workbook("sourceFile.sxc");
// получить доступ к рабочему листу по умолчанию из коллекции
Worksheet worksheet = workbook.getWorksheets().get(0);
// определить параметры результирующего изображения
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.JPEG);
// преобразовать рабочий лист в изображение в формате JPEG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.jpeg");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование SXC в JPEG в реальном времени" sectionDescription="[Конвертировать SXC в JPEG](https://products.aspose.app/cells/conversion/sxc-to-jpeg) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл SXC, и он будет мгновенно преобразован в JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java Библиотека для работы с электронными таблицами" %}}

 Excel API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в различные форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный API, и для него не требуется никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SXC" readMoreLink="https://docs.fileformat.com/spreadsheet/sxc/" >}}

Формат файла SXC (Sun XML Calc) принадлежит офисному пакету OpenOffice.org. Этот формат обычно отвечает потребностям пользователей в электронных таблицах, поскольку он представляет собой формат файла электронной таблицы на основе XML. Формат SXC поддерживает формулы, функции, макросы и диаграммы, а также DataPilot, что является невероятной функцией, поскольку она автоматически индивидуализирует и предоставляет сводки необработанных импортированных данных. Файлы, созданные с помощью этого программного обеспечения, сохраняются с расширением .sxc.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Выходное изображение в результате сжатия представляет собой компромисс между размером хранилища и качеством изображения. Пользователи могут настроить уровень сжатия для достижения желаемого уровня качества и в то же время уменьшить размер хранилища. Качество изображения незначительно ухудшается, если к изображению применяется сжатие 10:1. Чем выше значение сжатия, тем выше ухудшение качества изображения. Формат файла изображения JPEG был стандартизирован Объединенной группой экспертов по фотографии, отсюда и название JPEG. Формат был выбран для хранения и передачи фотографических изображений в Интернете. Почти все операционные системы теперь имеют средства просмотра, поддерживающие визуализацию изображений JPEG, которые также часто хранятся с расширением JPG. Даже веб-браузеры поддерживают визуализацию изображений JPEG.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}