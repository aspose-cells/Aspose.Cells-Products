---
title: Преобразование TXT в PNG с помощью приложения C++ 
url: /ru/cpp/conversion/txt-to-png/ 
description: Пример C++ кода преобразования документа TXT в формат PNG. Программисты могут использовать этот исходный код для пакетного преобразования TXT в PNG в любом приложении C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование TXT в PNG через C++" h2="Высокопроизводительное преобразование TXT в PNG с использованием библиотеки C++ без установки Microsoft Excel, OpenOffice или Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать TXT в PNG с помощью C++" %}}

 Чтобы преобразовать TXT в PNG, мы будем использовать
 [Aspose.Cells для C++](https://products.aspose.com/cells/cpp) 
 API — многофункциональное, мощное и простое в использовании средство обработки и преобразования документов API для платформы C++. Вы можете загрузить его последнюю версию напрямую, просто открыв
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 менеджер пакетов, поиск
 Aspose.Cells.CPP 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию TXT в PNG с помощью C++" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики C++ могут легко преобразовать файл TXT в PNG, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл TXT с помощью Factory::CreateIWorkbook.1. Выберите первый рабочий лист.1. Установите параметры (PNG).1. Итерация по каждой странице листа и визуализации.1. Откройте файл PNG в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском примера кода преобразования C++ убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с C++ средой выполнения для 32-разрядной, 64-разрядной Windows и 64-разрядной версии Linux.- Aspose.Cells для C++ DLL, на которую ссылается ваш проект.
- Microsoft Windows или совместимая ОС с C++ средой выполнения для 32-разрядной, 64-разрядной Windows и 64-разрядной версии Linux.- Aspose.Cells для C++ DLL, на которую ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TXT в PNG Исходный код преобразования C++" offSpacer="" %}}

```cs
// Выходной путь к каталогу.
StringPtr outDir = new String("OutputDirectoryPath");

// Загрузите ТХТ.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.txt");

// Доступ к первому рабочему листу.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Создайте изображение или объект опций печати.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Укажите формат изображения.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetPng());

// Укажите горизонтальное и вертикальное разрешение
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Рендеринг листа в соответствии с указанным изображением или параметрами печати.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Получить количество страниц.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Создайте объект построителя строк для конкатенации строк.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Рендеринг каждой страницы в изображение png один за другим.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImagePNG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".png"));

	// Получите путь к выходному изображению.
	StringPtr outputPNG = sb->ToString();

	// Преобразование рабочего листа в изображение png.
	sr->ToImage(i, outputPNG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование TXT в PNG в реальном времени" sectionDescription="[Конвертировать TXT в PNG](https://products.aspose.app/cells/conversion/txt-to-png) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл TXT, и он будет мгновенно преобразован в PNG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="C++ Библиотека для работы с файлами Excel" %}}

 Excel API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в различные форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный API, и для него не требуется никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

Файл с расширением .TXT представляет собой текстовый документ, содержащий обычный текст в виде строк. Абзацы в текстовом документе распознаются возвратом каретки и используются для лучшего расположения содержимого файла. Стандартный текстовый документ можно открыть в любом текстовом редакторе или текстовом редакторе в разных операционных системах. Весь текст, содержащийся в таком файле, имеет удобочитаемый формат и представлен последовательностью символов.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG, переносимая сетевая графика, относится к типу формата файла растрового изображения, в котором используется сжатие без потерь. Этот формат файла был создан в качестве замены формата обмена графикой (GIF) и не имеет ограничений авторского права. Однако формат файла PNG не поддерживает анимацию. Формат файлов PNG поддерживает сжатие изображений без потерь, что делает его популярным среди пользователей. С течением времени PNG превратился в один из наиболее часто используемых форматов файлов изображений. Почти все операционные системы поддерживают открытие файлов PNG. Например, средство просмотра Microsoft Windows имеет возможность открывать файлы PNG, так как ОС по умолчанию имеет поддержку, доступную как часть установки.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}