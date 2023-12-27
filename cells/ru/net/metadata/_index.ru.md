---
title: Управление метаданными файла Excel via .NET C#
description: Просматривайте, добавляйте, редактируйте, удаляйте или извлекайте метаданные файлов Excel с помощью всего нескольких строк кода C#.
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление Microsoft<sup>&reg;</sup> метаданными файла Excel via .NET" h2="Просматривайте, добавляйте, обновляйте, удаляйте или извлекайте встроенные и настраиваемые свойства файлов Excel с помощью API-интерфейсов .NET на стороне сервера." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Эксель API](/cells/ru/net/) поддерживает управление определяемыми системой (встроенными) свойствами, такими как заголовок, имя автора, статистика документа и т. д., а также пользовательскими (настраиваемыми) свойствами в форме пары имя-значение. Есть[Класс рабочей тетради](https://reference.aspose.com/cells/net/aspose.cells/workbook) для загрузки файлов и[Рабочий ЛистКоллекция](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) занимается сбором рабочих листов, а также[Класс рабочего листа](https://reference.aspose.com/cells/net/aspose.cells/worksheet) для представления одного рабочего листа. Наряду с этими классами, InternalDocumentProperties, CustomDocumentProperties упрощает процесс управления метаданными.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Управление встроенными свойствами" %}}

 Для управления свойствами, определяемыми системой, API предоставляет[Встроенные свойства документа](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) и программисты могут легко получить доступ к встроенному свойству и обновить его значение. В зависимости от требований приложения разработчики могут использовать индекс или имя свойства из[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Код для управления встроенными свойствами" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Управление пользовательскими свойствами" %}}

 Для управления пользовательскими свойствами API предоставляет[Пользовательские свойства документа](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , и разработчики могут легко получать доступ к уже добавленным свойствам, а также добавлять новые свойства. Чтобы добавить пользовательские свойства,[Добавить метод](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) из[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) класс добавляет свойство и возвращает ссылку на новое свойство в виде[Свойства.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) объект. Класс DocumentProperty используется для получения имени, значения и типа свойства документа как[ДокументСвойство.Имя](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [ДокументСвойство.Значение](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [ДокументСвойство.Тип](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) который возвращает один из[Тип собственности](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) значения перечисления.
 
{{% blocks/products/pf/feature-page-code h3="C# Код для добавления метаданных в файл Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Код для удаления пользовательского свойства в файле Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
