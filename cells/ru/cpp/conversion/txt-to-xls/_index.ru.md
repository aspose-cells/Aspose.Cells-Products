---
title: Преобразование TXT в XLS с помощью приложения C++ 
url: /ru/cpp/conversion/txt-to-xls/ 
description: Пример кода преобразования C++ для документа TXT в формат XLS. Программисты могут использовать этот исходный код для пакетного преобразования TXT в XLS в любом приложении C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование TXT в XLS через C++" h2="Высокопроизводительное преобразование TXT в XLS с использованием библиотеки C++ без необходимости установки Microsoft Excel, OpenOffice или Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать TXT в XLS с помощью C++" %}}

 Чтобы преобразовать TXT в XLS, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию TXT в XLS через C++" %}}

{{% blocks/products/pf/agp/text %}}

 Разработчики C++ могут легко преобразовать файл TXT в XLS, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл TXT с помощью Factory::CreateIWorkbook.1. Вызовите метод Сохранить().1. Передайте путь к выходному файлу с расширением (XLS).1. XLS-файл будет сохранен по указанному пути.1. Откройте файл XLS в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском примера кода преобразования C++ убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с C++ средой выполнения для 32-разрядной, 64-разрядной Windows и 64-разрядной версии Linux.- Aspose.Cells для C++ DLL, на которую ссылается ваш проект.
- Microsoft Windows или совместимая ОС с C++ средой выполнения для 32-разрядной, 64-разрядной Windows и 64-разрядной версии Linux.- Aspose.Cells для C++ DLL, на которую ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Исходный код преобразования TXT в XLS C++" offSpacer="" %}}

```cs
// Загрузите ТХТ.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.txt");

// Сохранить в формате XLS.
wkb->Save(u"convertedFile.xls", SaveFormat_Xls);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование TXT в XLS в реальном времени" sectionDescription="[Конвертировать TXT в XLS](https://products.aspose.app/cells/conversion/txt-to-xls) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл TXT, и он будет мгновенно преобразован в XLS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="C++ Библиотека для работы с файлами Excel" %}}

 Excel API можно использовать для создания, редактирования, преобразования и преобразования форматов Microsoft Excel в различные форматы. Кроме того, его можно использовать для комплексных графиков, масштабируемых отчетов и надежных расчетов в программных приложениях. Aspose.Cells — это автономный API, и для него не требуется никакого программного обеспечения, такого как Microsoft или OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

Файл с расширением .TXT представляет собой текстовый документ, содержащий обычный текст в виде строк. Абзацы в текстовом документе распознаются возвратом каретки и используются для лучшего расположения содержимого файла. Стандартный текстовый документ можно открыть в любом текстовом редакторе или текстовом редакторе в разных операционных системах. Весь текст, содержащийся в таком файле, имеет удобочитаемый формат и представлен последовательностью символов.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Файлы с расширением XLS представляют собой формат двоичных файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Файл, сохраненный Excel, известен как рабочая книга, где каждая рабочая книга может иметь один или несколько рабочих листов. Данные хранятся и отображаются для пользователей в формате таблицы на листе и могут включать числовые значения, текстовые данные, формулы, подключения к внешним данным, изображения и диаграммы. Такие приложения, как Microsoft Excel, позволяют экспортировать данные рабочей книги в несколько различных форматов, включая PDF, CSV, XLSX, TXT, HTML, XPS и некоторые другие. Формат файла XLS был заменен более открытым и структурированным форматом XLSX с выпуском Microsoft Excel 2007. В последних версиях по-прежнему поддерживается создание и чтение файлов XLS, хотя XLSX сейчас используется в первую очередь.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}