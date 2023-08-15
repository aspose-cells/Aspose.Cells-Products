---
title: Создание файлов Excel via Java
description: Создание электронных таблиц Excel Microsoft из листа шаблона с использованием библиотеки электронных таблиц Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Создание отчетов на основе шаблонов Excel via Java" h2="Создавайте массовые отчеты в виде файлов Excel на основе предопределенного шаблона в приложениях на основе Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Библиотека Excel](/cells/ru/java/)поддерживает создание файлов Excel на основе шаблонов для массового создания отчетов. Это необходимо для большинства случаев, таких как создание квитанций об оплате, карт результатов, записей пациентов и т. д. Шаблоны — это предопределенные шаблоны. Код ниже Java генерирует объемные файлы Excel, такие же, как шаблон документа, заполненного данными. Поддерживаемые форматы файлов включают XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Создание отчетов на основе предварительно разработанного шаблона Excel" %}}

 Используя сборку Java API, разработчики могут легко запрограммировать код создания массового отчета, включив приведенные ниже фрагменты кода. API обеспечивает[импортировать данные](https://docs.aspose.com/cells/java/import-and-export-data/) функции из разных источников и создавать документы Excel в зависимости от этих данных. Для шаблонов на основе шаблонов API предоставляет[Класс WorkbookDesigner](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner)для представления рабочего листа дизайнера. Процесс заключается в том, чтобы создать свой объект и использовать его для открытия файла шаблона. Установите источник данных, который может быть Array, DataTable, Json и т. д. Обработайте его, чтобы импортировать данные и сохранить файл в нужном формате. Программисты могут собирать данные в отчеты в других форматах файлов, включая XLS, XLSX, XLSB, XLSM, ODS, по указанным ниже ссылкам.



{{% blocks/products/pf/feature-page-code h3="Java Код для создания отчетов Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}
