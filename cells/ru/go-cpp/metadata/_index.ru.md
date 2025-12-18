---
title: Управление метаданными файлов Excel с помощью Go через C++
description: Просмотр, добавление, редактирование, удаление или извлечение метаданных файлов Excel с помощью Go через библиотеку C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление метаданными документа Excel Microsoft через Go по адресу C++" h2="Просмотр, вставка, обновление, удаление или извлечение пользовательских и встроенных свойств документов Excel в приложениях C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Метаданные в Excel — как просматривать, вставлять и удалять метаданные из файлов Excel.[Перейти по ссылке C++ Библиотека Excel](/cells/ru/go-cpp/)Библиотека упрощает этот процесс, поддерживая встроенные/системные свойства, такие как имя автора, заголовок, статистика документа и т. д., необходимые, например, для проверки момента последнего изменения или сохранения файла, а также пользовательские свойства в виде пар «имя/значение». Для автоматизации процесса библиотека поддерживает создание и ведение больших файлов метаданных Excel.[Рабочая тетрадь](https://reference.aspose.com/cells/go-cpp/workbook/) Класс открывает рабочую книгу по пути, потоку и специальному типу формата файла. Затем загружает файл с помощью соответствующего метода для дальнейшей обработки. Ниже перечислены некоторые из возможностей, и разработчики могут легко улучшить свой код в соответствии с требованиями приложения.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Чтение и обновление встроенных свойств" %}}

 Для автоматизации встроенных свойств используется компонент API.[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Метод, возвращающий коллекцию DocumentProperties, представляющую все встроенные свойства документа электронной таблицы. После доступа ко всем встроенным свойствам, получите доступ к соответствующим свойствам, используя соответствующие методы, такие как GetTitle(), GetSubject() и т. д. Для обновления свойств в объекте API предусмотрены методы, такие как SetTitle, SetSubject, SetAuthor, SetComments и т. д. См.[встроенная коллекция свойств документа](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) для выполнения требуемой функции.

{{% blocks/products/pf/feature-page-code h3="Перейдите по коду C++ для чтения системно-определяемых свойств." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Для обновления встроенных свойств используйте код C++." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Просмотр и добавление пользовательских свойств." %}}

 Для обработки пользовательских свойств используется компонент API.[Workbook::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Этот метод возвращает всю коллекцию пользовательских свойств документа электронной таблицы. Сначала, получив доступ к пользовательским свойствам через этот метод, разработчики могут использовать соответствующие методы для добавления свойств, такие как AddIDocumentProperty, AddLinkToContentProperty, а также использовать UpdateLinkedPropertyValue и UpdateLinkedRange для обновления значения пользовательского свойства документа, которое ссылается на содержимое и на связанный диапазон соответственно. Разработчики могут использовать соответствующие методы из[набор пользовательских свойств документа](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Перейдите по коду C++ для просмотра пользовательских свойств." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Используйте код C++ для добавления метаданных в файл Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}