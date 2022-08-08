---
title: Аннотации файлов Excel через C++
url: /ru/cpp/annotation/
description: Добавляйте или удаляйте комментарии к данным электронных таблиц Excel и OpenOffice с библиотекой C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление аннотациями к файлам Microsoft<sup>&reg;</sup> Excel через C++" h2="Добавляйте или удаляйте простые примечания для аннотаций или комментариев в приложениях на основе C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) обеспечивает поддержку управления аннотациями на уровне ячеек путем добавления, доступа и удаления комментариев. API обеспечивает [IКомментарий](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) и [ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) также как и [ПолучитьКомментарии()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) для обработки комментариев во всех аспектах. Поддерживаемые форматы Excel включают ODS, XLS, XLSX, XLSB и XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Аннотации к данным в файлах Excel" %}}
Манипулирование комментариями в рабочих листах. Количество комментариев на листе в MS Excel не ограничено. Можно вставить столько, сколько нужно для приложения. Процесс вставки комментариев, создать [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) объект класса, чтобы загрузить существующий файл и выбрать рабочий лист, на который вы хотите добавить комментарий. Получите все его комментарии с помощью getComments(). Добавьте комментарий, используя [Добавлять](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > имя_ячейки). Получите индекс ячейки и используйте [setNote](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) для вставки комментариев. Кроме того, API может удалять все комментарии. Немногие из методов [ОчиститьКомментарии()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to Удаляет все комментарии в электронной таблице дизайнера. Более того, [RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) для удаления элемента по указанному индексу или с указанным именем.

{{% blocks/products/pf/feature-page-code h3="C++ Код для добавления комментариев в файл Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}