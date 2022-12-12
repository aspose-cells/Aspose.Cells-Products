---
title: Управление метаданными файла Excel через Java

description: Просматривайте, добавляйте, редактируйте, удаляйте или извлекайте метаданные файлов Excel с помощью всего нескольких строк кода Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление метаданными файла Microsoft<sup>&reg;</sup> Excel через Java" h2="Просматривайте, добавляйте, обновляйте, удаляйте или извлекайте настраиваемые и встроенные свойства файлов Excel с помощью Java API на стороне сервера." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) поддерживает управление встроенными (определенными системой) свойствами, такими как заголовок, имя автора, статистика документа и т. д., а также пользовательскими (определенными пользователем) свойствами в виде пары имя/значение. Там есть [Класс рабочей тетради](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) загрузить файлы и [Рабочий листКоллекция](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) занимается сбором рабочих листов, а также [Класс рабочего листа](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) для представления одного рабочего листа. Для доступа к встроенным и пользовательским свойствам BuiltInDocumentProperties, CustomDocumentProperties упрощает процесс управления метаданными. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Управление системными свойствами" %}}

Для управления встроенными свойствами API предоставляет [Буилтиндокументпропертиес](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), и программисты могут легко получить доступ к встроенному свойству и обновить его значение. В зависимости от требований приложения разработчики могут использовать индекс или имя свойства из [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Код для управления системными свойствами" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Добавить и удалить пользовательские метаданные" %}}

Для обработки настраиваемых свойств API предоставляет [CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), и разработчики могут легко получить доступ к существующим свойствам, а также добавить новые свойства, используя [добавить метод](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) из [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) класс добавляет свойство и возвращает ссылку на новое свойство в виде [Свойства.ДокументПроперти](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) объект. Класс DocumentProperty используется для получения имени, значения и типа свойства документа в виде [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) который возвращает один из [Тип свойства](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) значения перечисления. 
 
{{% blocks/products/pf/feature-page-code h3="Java Код для добавления метаданных в файл Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Код для удаления пользовательского свойства в файле Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
