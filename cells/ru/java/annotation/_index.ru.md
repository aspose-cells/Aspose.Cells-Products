---
title: Аннотации файлов Excel через Java

description: Добавляйте или удаляйте аннотации к данным электронных таблиц Excel и OpenOffice с библиотекой Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление аннотациями к файлам Microsoft<sup>&reg;</sup> Excel через Java" h2="Вставляйте простые примечания для аннотаций или удаляйте комментарии на уровне ячеек электронной таблицы Excel в приложениях на основе Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) обеспечивает поддержку управления аннотациями на уровне ячеек путем добавления, доступа и удаления комментариев. API обеспечивает [Комментарий](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [КомментарийКоллекция](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) и [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) для обработки комментариев во всех аспектах.
Поддерживаемые форматы файлов включают ODS, XLS, XLSX, XLSB и XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Аннотации к данным в файлах Excel" %}}
Управление комментариями на листах. В MS Excel нет ограничений на количество комментариев на листе. Можно добавить столько, сколько требует приложение. Процесс добавления комментариев, создать [Рабочая тетрадь](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) объект класса или загрузите существующий файл с помощью класса Workbook. Доступ ко всем его комментариям с помощью getComments(). Получите индекс ячейки и используйте [setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) для вставки комментариев. Кроме того, API может удалять все комментарии. 

{{% blocks/products/pf/feature-page-code h3="Java Код для добавления комментариев в файл Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Код для удаления комментариев в файле Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
