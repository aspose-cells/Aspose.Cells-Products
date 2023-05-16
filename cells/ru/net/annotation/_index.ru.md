---
title: Аннотации файлов Excel NET C#
description: Добавляйте или удаляйте аннотации данных в таблицах Excel и OpenOffice всего несколькими строками кода C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Удалить Microsoft<sup>&reg;</sup> аннотации файлов Excel via .NET" h2="Добавляйте или удаляйте аннотации файлов Excel с помощью кода C# в приложениях на основе .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Библиотека Excel](/cells/ru/net/) обеспечивает поддержку управления аннотациями на уровне ячеек путем добавления, доступа и удаления комментариев. Используя комментарии на уровне ячейки, можно сохранить соответствующую информацию для конечных пользователей. Поддерживаемые форматы файлов включают ODS, XLS, XLSX, XLSB и XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Аннотации к данным в файлах Excel" %}}
 Управление комментариями на листах. В MS Excel нет ограничений на количество комментариев на листе. Можно добавить столько, сколько требует приложение. Мы будем использовать[Класс комментариев](https://reference.aspose.com/cells/net/aspose.cells/comment)для всего этого функционала.

+ Загрузить файл Excel с помощью объекта класса Workbook
+ Доступ к соответствующему рабочему листу и его соответствующему индексу Cell
+ Вызовите RemoveAt с идентификатором Cell, чтобы удалить его
 + Использовать[Примечание свойство](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) для добавления содержания комментариев
+ Сохраните книгу до и после вызова метода RemoveAt для сравнения

{{% blocks/products/pf/feature-page-code h3="C# Код для доступа, вставки и удаления файлов Excel Cell Комментарии" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
