---
title: Управление метаданными файлов Excel через .NET C#
url: /ru/net/metadata/
description: Просматривайте, добавляйте, редактируйте, удаляйте или извлекайте метаданные файлов Excel с помощью всего нескольких строк кода C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление метаданными файла Microsoft<sup>&reg;</sup> Excel через .NET" h2="Просматривайте, добавляйте, обновляйте, удаляйте или извлекайте встроенные и настраиваемые свойства файлов Excel с помощью .NET API на стороне сервера." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) поддерживает управление определенными системой (встроенными) свойствами, такими как заголовок, имя автора, статистика документа и т. д., а также определяемыми пользователем (настраиваемыми) свойствами в виде пары имя-значение. Там есть [Класс рабочей тетради](https://apireference.aspose.com/cells/net/aspose.cells/workbook) загрузить файлы и [Рабочий листКоллекция](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) занимается сбором рабочих листов, а также [Класс рабочего листа](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) для представления одного рабочего листа. Наряду с этими классами, BuiltInDocumentProperties, CustomDocumentProperties упрощают процесс управления метаданными. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Управление встроенными свойствами" %}}

Для управления определенными системой свойствами API предоставляет [Буилтиндокументпропертиес](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), и программисты могут легко получить доступ к встроенному свойству и обновить его значение. В зависимости от требований приложения разработчики могут использовать индекс или имя свойства из [DocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Код для управления встроенными свойствами" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Управление пользовательскими свойствами" %}}

Для управления определяемыми пользователем свойствами API предоставляет [CustomDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), и разработчики могут легко получить доступ к уже добавленным свойствам, а также добавить новые свойства. Чтобы добавить пользовательские свойства, [Добавить метод](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) из [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) класс добавляет свойство и возвращает ссылку на новое свойство в виде [Свойства.ДокументПроперти](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) объект. Класс DocumentProperty используется для получения имени, значения и типа свойства документа в виде [DocumentProperty.Name](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) который возвращает один из [Тип свойства](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) значения перечисления. 
 
{{% blocks/products/pf/feature-page-code h3="C# Код для добавления метаданных в файл Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Код для удаления пользовательского свойства в файле Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
