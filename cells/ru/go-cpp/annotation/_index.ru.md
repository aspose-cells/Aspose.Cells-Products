---
title: Добавление или удаление аннотаций в файлах Excel с помощью Go через C++
description: Добавление или удаление комментариев к данным в электронных таблицах Excel и OpenOffice с помощью Go через библиотеку C++.
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Управление аннотациями в файле Excel Microsoft с помощью Go через C++" h2="Добавляйте или удаляйте простые заметки для аннотаций или комментариев в Go с помощью приложений на основе C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Перейти по адресу C++ Excel API](/cells/ru/go-cpp/) Предоставляет поддержку для управления аннотациями на уровне ячеек путем добавления, доступа и удаления комментариев. API предоставляет[Комментарий](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) и[CommentCollection](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)а также[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) Для обработки комментариев по всем аспектам. Поддерживаемые форматы Excel: ODS, XLS, XLSX, XLSB и XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Аннотации данных в файлах Excel" %}}
 Редактирование комментариев в таблицах — В MS Excel количество комментариев на листе не ограничено. Можно вставить столько комментариев, сколько необходимо приложению. Процесс вставки комментариев заключается в создании[Рабочая тетрадь](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) Для загрузки существующего файла выберите лист, куда хотите добавить комментарий. Получите все комментарии с помощью метода `getComments()`. Добавьте комментарий, используя следующий код:[Добавить(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) метод. Получите индекс ячейки и используйте[SetNote](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) для добавления комментариев. Кроме того, код API позволяет удалять все комментарии. Вот несколько способов:[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) Удаляет все комментарии в электронной таблице дизайнера. Кроме того,***УдалитьВ*** Метод для удаления элемента по указанному индексу или с указанным именем.

{{% blocks/products/pf/feature-page-code h3="Используйте код C++ для добавления комментариев в файл Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
