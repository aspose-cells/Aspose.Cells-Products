---
title:  Водяной знак XLSB документ via Java
weight: 5900
description: Пример кода Java для добавления или удаления водяного знака в файле XLSB в среде выполнения Java для приложений JSP/JSF и настольных приложений.
keywords: [Java Aspose.Cells., Java add watermark to xlsb file., Java insert watermark to xlsb file., Java create watermark in xlsb file., remove watermark from xlsb file using Java., Java operate watermark in xlsb file., Java access watermark in xlsb file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Добавьте текстовый водяной знак на номер XLSB via Java." h2="Создавайте свои собственные приложения Java, добавляя водяные знаки в файлы XLSB, используя серверные API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Как поставить водяной знак XLSB на файл с помощью Java" %}}

 Чтобы поставить водяной знак на файл XLSB, мы будем использовать[Aspose.Cells for Java](https://products.aspose.com/cells/java) API — многофункциональная, мощная и простая в использовании платформа для нанесения водяных знаков. API for Java. Вы можете скачать последнюю версию прямо с сайта[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) и установите его в свой проект на основе Maven, добавив следующие конфигурации в pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по добавлению водяного знака на номер XLSB via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Создайте новый объект книги.
1.  Выберите рабочий лист по его индексу.
1.  Создайте фигуру и используйте ее функцию addTextEffect.
1.  Установите цвета, прозрачность и многое другое.
1.  Сохраните книгу в формате XLSB.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java поддерживает все основные платформы и операционные системы. Пожалуйста, убедитесь, что у вас есть следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java Среда выполнения для приложений JSP/JSF и настольных приложений.
- Получите последнюю версию Aspose.Cells for Java непосредственно с телефона Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Добавьте водяной знак на номера XLSB - Java." offSpacer="" %}}

```cs

// Instantiate a new Workbook
Workbook workbook = new Workbook();

// Get the first default sheet
Worksheet sheet = workbook.getWorksheets().get(0);

// Add Watermark
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Get the fill format of the word art
FillFormat wordArtFormat = wordart.getFill();

// Set the color
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Set the transparency
wordArtFormat.setTransparency(0.9);

// Make the line invisible
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Save the file
workbook.save(dataDir + "AWArtWToWorksheet_out.xlsb");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Около Aspose.Cells for Java API" %}}

 Aspose.Cells API можно использовать для создания, редактирования, преобразования и преобразования Microsoft форматов Excel в различные форматы. Более того, его можно использовать для составления комплексных диаграмм, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный номер API, который не требует какого-либо программного обеспечения, такого как Microsoft или OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Водяной знак XLSB через онлайн-приложение" sectionDescription=" Добавьте водяной знак в документы XLSB, посетив наш[Веб-сайт живых демонстраций](https://products.aspose.app/cells/watermark). Живая демонстрация имеет следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файл XLSB, установите водяной знак и нажмите кнопку «Добавить»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Мгновенно получите ссылку для скачивания полученного файла." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Формат файла XLSB определяет формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Содержимое может включать неструктурированные или полуструктурированные таблицы чисел, текста или чисел и текста, формулы, подключения к внешним данным, диаграммы и изображения. В отличие от XLSX (который основан на формате файла Open XML), XLSB представляет собой двоичный файл книги Excel. Файлы XLSB можно читать и записывать быстрее, что делает их полезными для работы с большими файлами. XLSB редко используется для хранения книг, поскольку XLSX (а ранее XLS) — это наиболее распространенные форматы файлов, выбираемые пользователем для сохранения книг. Его можно открыть с помощью Microsoft Office 2007 и выше.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы водяных знаков" subTitle="Используя номер Java, можно легко поставить водяные знаки в различных форматах, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsx/" name="XLSX" description="OOXML-файл Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
