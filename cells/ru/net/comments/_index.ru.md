---
title: Вставка комментариев в Excel через .NET

description: Исходные коды C# о том, как вставлять комментарии в файлы Microsoft Excel с помощью библиотеки .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Вставка комментариев Microsoft<sup>&reg;</sup> Excel через .NET" h2="Создавайте документы Excel и вставляйте комментарии с помощью серверных API в .NETприложениях." >}}
{{% blocks/products/pf/feature-page-summary %}}

Вы можете добавлять комментарии к ячейкам. Когда в ячейке есть комментарий, в углу ячейки появляется индикатор. Комментарии появляются при наведении курсора на ячейку. Эти комментарии можно использовать для обсуждения, специальных инструкций или разметки содержимого документа. [.NET Библиотека Excel](/cells/net/) поддерживает вставку комментариев в файлы Excel. Для этого API предоставляет [Комментарий](https://reference.aspose.com/cells/net/aspose.cells/comment) класс для блока комментариев.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Вставить комментарии в файл Excel" %}}

Вставка комментариев с помощью Excel API проста. Процесс, Создай [Класс рабочей тетради](https://reference.aspose.com/cells/net/aspose.cells/workbook) объект и выберите первый рабочий лист или соответствующий лист, указав его индекс. Вставьте необходимые данные ячеек, используя [Метод PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Добавьте комментарий к рабочему листу, используя [КомментарийКоллекция](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)х [Добавить метод](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Код для вставки комментария в Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
