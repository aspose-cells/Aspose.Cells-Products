---
title: Управляйте метаданными файла Excel по телефону C++.
description: Просмотр, добавление, редактирование, удаление или извлечение метаданных файлов Excel с помощью библиотеки C++.
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управляйте метаданными документа Excel Microsoft<sup>&reg;</sup> с помощью номера C++." h2="Просматривайте, вставляйте, обновляйте, удаляйте или извлекайте пользовательские и встроенные свойства документов Excel в приложениях C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Метаданные в Excel — Как просмотреть, вставить и удалить метаданные файла Excel.[C++ Библиотека Excel](/cells/ru/cpp/) упрощает процесс, поддерживая встроенные/определяемые системой свойства, такие как имя автора, заголовок, статистика документа и т. д., необходимые когда-либо, например, для проверки того, когда последний раз файл был изменен или сохранен вместе с пользовательскими/определяемыми пользователем свойствами в виде пары имя/значение. Для автоматизации процесса библиотека поддерживает создание и поддержку больших файлов метаданных Excel.[Рабочая тетрадь](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Открывает книгу по пути, по потоку и по специальному типу FileFormatType. Поэтому загрузите файл подходящим методом для дальнейшей обработки. Ниже перечислены некоторые из возможностей, и разработчики могут легко улучшить свой код в соответствии с требованиями приложения.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Чтение и обновление встроенных свойств" %}}

 Для автоматизации встроенных свойств API предоставляет[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) метод, который возвращает коллекцию DocumentProperties, представляющую все встроенные свойства документа электронной таблицы. После доступа ко всем встроенным свойствам получите доступ к соответствующим свойствам, используя соответствующий метод, такой как GetTitle(), GetSubject() и т. д. Для обновления свойств API предоставляет такие методы, как SetTitle, SetSubject, SetAuthor, SetComments и т. д. Просмотрите[встроенная коллекция свойств документа](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) для требуемой функции.

{{% blocks/products/pf/feature-page-code h3="C++ Код для чтения системных свойств" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Код для обновления встроенных свойств" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Просмотр и добавление настраиваемых свойств" %}}

Для обработки пользовательских свойств API предоставляет[Рабочая книга::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) который возвращает всю коллекцию пользовательских свойств документа электронной таблицы. Во-первых, получив доступ к настраиваемым свойствам с помощью этого метода, разработчики могут использовать соответствующие методы для добавления таких свойств, как AddIDocumentProperty, AddLinkToContentProperty, и аналогичным образом использовать UpdateLinkedPropertyValue, UpdateLinkedRange для обновления значения настраиваемого свойства документа, которое ссылается на контент и на связанный диапазон соответственно. Разработчики могут использовать соответствующий метод из[коллекция пользовательских свойств документа](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Код для просмотра пользовательских свойств" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Код для добавления метаданных в файл Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
