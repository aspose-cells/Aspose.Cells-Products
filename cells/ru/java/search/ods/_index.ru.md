---
title: Поиск документа ODS без открытия через Java 
weight: 8140
url: /ru/java/search/ods/ 
description: Пример кода Java для поиска слов с шаблоном в файле ODS в Java среде выполнения для приложений JSP/JSF и настольных приложений.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Поиск форматов ODS в Java" h2="Собственный и высокопроизводительный поиск документов ODS с использованием серверных Aspose.Cells for Java API без использования какого-либо программного обеспечения, такого как Microsoft или Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Как искать файл ODS с помощью Java" %}}

 Для поиска файла ODS мы будем использовать
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API — многофункциональная, мощная и простая в использовании поисковая API for Java платформа. Вы можете скачать его последнюю версию прямо с
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по поиску файлов ODS в Java" %}}

{{% blocks/products/pf/agp/text %}}

 Базовый поиск документов с помощью Aspose.Cells API можно выполнить всего несколькими строками кода.

{{% /blocks/products/pf/agp/text %}}

+ Загрузить файл ODS, создав экземпляр объекта Workbook.
+ Доступ к первому рабочему листу в файле ODS.
+ Найти ячейку, содержащую указанную формулу.
+ Создать FindOptions.
+ Найти ячейку, содержащую строковое значение
+ Распечатать найденные ячейки после результата поиска

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java поддерживается на всех основных платформах и операционных системах. Пожалуйста, убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.Cells for Java непосредственно из [Мавен](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Поиск файлов ODS – Java" offSpacer="" %}}

```cs
// Создание экземпляра объекта Workbook
Workbook workbook = new Workbook(dataDir + "book1.ods");

// Доступ к первому рабочему листу в файле ODS
Worksheet worksheet = workbook.getWorksheets().get(0);

// Поиск ячейки, содержащей указанную формулу
Cells cells = worksheet.getCells();

// Создать экземпляр FindOptions
FindOptions findOptions = new FindOptions();

// Поиск ячейки, содержащей строковое значение, начинающееся с Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Печать имени ячейки, найденной после поиска 
System.out.println("Name of the cell containing String: " + cell.getName());  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="О Aspose.Cells for Java API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в другие форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells является автономным API и не требует никакого программного обеспечения, такого как Microsoft или OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-поиск ODS Онлайн-демонстрации" sectionDescription="Ищите текст, слова, фразы в документах ODS прямо сейчас, посетив наш [Веб-сайт живых демонстраций](https://products.aspose.app/cells/search). Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файлы ODS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Результат поиска появляется мгновенно." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS " readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Файлы с расширением ODS обозначают формат документа электронной таблицы OpenDocument, который может редактировать пользователь. Данные хранятся внутри файла ODF в строках и столбцах. Этот формат основан на XML и является одним из нескольких подтипов в семействе форматов открытых документов (ODF). Формат указан как часть спецификаций ODF 1.2, опубликованных и поддерживаемых OASIS. Ряд приложений в Windows, а также в других операционных системах могут открывать файлы ODS для редактирования и обработки, включая Microsoft Excel, NeoOffice и LibreOffice. Файлы ODS также могут быть преобразованы в другие форматы электронных таблиц, такие как XLS, XLSX и другие, с помощью различных приложений. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые поисковые документы" subTitle="Используя Java, можно также искать другие файлы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="ТСВ" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="ТЕКСТ" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}