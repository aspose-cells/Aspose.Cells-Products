---
title: Управление метаданными файла Excel via Java
description: Просматривайте, добавляйте, редактируйте, удаляйте или извлекайте метаданные файлов Excel с помощью всего нескольких строк кода Java.
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Управление Microsoft<sup>&reg;</sup> метаданными файла Excel via Java" h2="Просматривайте, добавляйте, обновляйте, удаляйте или извлекайте пользовательские и встроенные свойства файлов Excel с помощью API-интерфейсов Java на стороне сервера." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Эксель API](/cells/ru/java/) поддерживает управление встроенными (определяемыми системой) свойствами, такими как заголовок, имя автора, статистика документа и т. д., а также пользовательскими (определяемыми пользователем) свойствами в форме пары имя/значение. Есть[Класс рабочей тетради](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) для загрузки файлов и[Рабочий ЛистКоллекция](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) занимается сбором рабочих листов, а также[Класс рабочего листа](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) для представления одного рабочего листа. Для доступа к встроенным и настраиваемым свойствам PurchaseInDocumentProperties CustomDocumentProperties упрощает процесс управления метаданными.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Управление свойствами, определяемыми системой" %}}

 Для управления встроенными свойствами API предоставляет[Встроенные свойства документа](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) и программисты могут легко получить доступ к встроенному свойству и обновить его значение. В зависимости от требований приложения разработчики могут использовать индекс или имя свойства из[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Код для управления свойствами, определяемыми системой" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Добавление и удаление пользовательских метаданных" %}}

Для обработки пользовательских свойств API предоставляет[Пользовательские свойства документа](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) и разработчики могут легко получить доступ к существующим свойствам, а также добавлять новые свойства, используя[добавить метод](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) из[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) класс добавляет свойство и возвращает ссылку на новое свойство в виде[Свойства.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) объект. Класс DocumentProperty используется для получения имени, значения и типа свойства документа как[ДокументСвойство.Имя](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [ДокументСвойство.Значение](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [ДокументСвойство.Тип](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) который возвращает один из[Тип собственности](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) значения перечисления.
 
{{% blocks/products/pf/feature-page-code h3="Java Код для добавления метаданных в файл Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Код для удаления пользовательского свойства в файле Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
