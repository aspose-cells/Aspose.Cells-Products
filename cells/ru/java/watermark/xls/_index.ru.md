---
title: Документ XLS с водяным знаком через Java 
weight: 2210
url: /ru/java/watermark/xls/ 
description: Пример кода Java для добавления или удаления водяного знака в файле XLS в Java среде выполнения для приложений JSP/JSF и настольных приложений.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Добавить текстовый водяной знак в XLS через Java" h2="Создавайте собственные приложения Java для водяных знаков XLS-файлов с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Как поставить водяной знак на файл XLS с помощью Java" %}}

 Чтобы поставить водяной знак на файл XLS, мы будем использовать
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API — многофункциональная, мощная и простая в использовании платформа для создания водяных знаков API for Java. Вы можете скачать его последнюю версию прямо с
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по добавлению водяного знака в XLS через Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Создайте новый объект рабочей книги1. Выберите рабочий лист через его индекс1. Создайте фигуру и используйте ее функцию addTextEffect.1. Установите цвета, прозрачность и многое другое1. Сохранить книгу в формате XLS
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java поддерживается на всех основных платформах и операционных системах. Пожалуйста, убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.Cells for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Добавить водяной знак в XLS – Java" offSpacer="" %}}

```cs

// Создание новой книги
Workbook workbook = new Workbook();

// Получить первый лист по умолчанию
Worksheet sheet = workbook.getWorksheets().get(0);

// Добавить водяной знак
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Получить формат заполнения слова art
FillFormat wordArtFormat = wordart.getFill();

// Установите цвет
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Установите прозрачность
wordArtFormat.setTransparency(0.9);

// Сделать линию невидимой
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Сохраните файл
workbook.save(dataDir + "AWArtWToWorksheet_out.xls");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.Cells for Java API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в другие форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells является автономным API и не требует никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Водяной знак XLS через онлайн-приложение" sectionDescription="Добавьте водяной знак в документы XLS, посетив наш [Веб-сайт живых демонстраций](https://products.aspose.app/cells/watermark). Живая демонстрация имеет следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файл XLS, установите водяной знак и нажмите кнопку «Добавить»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Мгновенно получить ссылку для скачивания результирующего файла" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Файлы с расширением XLS представляют собой формат двоичных файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Файл, сохраненный Excel, известен как рабочая книга, где каждая рабочая книга может иметь один или несколько рабочих листов. Данные хранятся и отображаются для пользователей в формате таблицы на листе и могут включать числовые значения, текстовые данные, формулы, подключения к внешним данным, изображения и диаграммы. Такие приложения, как Microsoft Excel, позволяют экспортировать данные рабочей книги в несколько различных форматов, включая PDF, CSV, XLSX, TXT, HTML, XPS и некоторые другие. Формат файла XLS был заменен более открытым и структурированным форматом XLSX с выпуском Microsoft Excel 2007. В последних версиях по-прежнему поддерживается создание и чтение файлов XLS, хотя XLSX сейчас используется в первую очередь.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы водяных знаков" subTitle="Используя Java, можно легко наносить водяные знаки на различные форматы, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ОРВ" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}