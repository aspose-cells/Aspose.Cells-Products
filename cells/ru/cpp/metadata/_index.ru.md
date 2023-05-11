---
title: Управление метаданными файла Excel по телефону C++
description: Просмотр, добавление, редактирование, удаление или извлечение метаданных файлов Excel с помощью библиотеки C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление метаданными документа Excel Microsoft<sup>&reg;</sup> по телефону C++" h2="Просмотр, вставка, обновление, удаление или извлечение пользовательских и встроенных свойств документа Excel в приложениях C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Метаданные в Excel — как просматривать, вставлять и удалять метаданные файла Excel.[C++ Библиотека Excel](/cells/ru/cpp/) упрощается, поддерживая встроенные / определенные системой свойства, такие как имя автора, заголовок, статистика документа и т. д., необходимые иногда, например, для проверки, когда последний файл был изменен или сохранен вместе с пользовательскими / определяемыми пользователем свойствами в виде пары имя/значение. Для автоматизации процесса библиотека поддерживает создание и поддержку больших файлов метаданных Excel.[Метод CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) из[Заводской класс](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Откройте книгу по пути, по потоку и по специальному FileFormatType. Поэтому загрузите файл соответствующим методом для дальнейшей обработки. Некоторые из возможностей, перечисленных ниже, и разработчики могут легко улучшить свой код в соответствии с требованиями приложения.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Чтение и обновление встроенных свойств" %}}

 Для автоматизации встроенных свойств API предоставляет[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) метод, который возвращает коллекцию DocumentProperties, представляющую все встроенные свойства документа электронной таблицы. После доступа ко всем встроенным свойствам откройте соответствующие свойства с помощью соответствующего метода, такого как GetTitle(), GetSubject() и т. д. Для обновления свойств API предоставляет такие методы, как SetTitle, SetSubject, SetAuthor, SetComments и т. д. Просмотрите[встроенная коллекция свойств документа](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) для требуемой функции.

{{% blocks/products/pf/feature-page-code h3="C++ Код для чтения системных свойств" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Код для обновления встроенных свойств" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Просмотр и добавление настраиваемых свойств" %}}

Для обработки пользовательских свойств API предоставляет[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) который возвращает всю коллекцию пользовательских свойств документа электронной таблицы. Во-первых, получая доступ к пользовательским свойствам с помощью этого метода, разработчики могут использовать соответствующие методы для добавления свойств, таких как AddIDocumentProperty, AddLinkToContentProperty, и аналогичным образом использовать UpdateLinkedPropertyValue, UpdateLinkedRange для обновления значения пользовательского свойства документа, которое ссылается на содержимое и на связанный диапазон соответственно. Разработчики могут использовать соответствующий метод из[коллекция пользовательских свойств документа](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Код для просмотра пользовательских свойств" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Код для добавления метаданных в файл Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
