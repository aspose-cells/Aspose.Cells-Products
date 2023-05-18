---
title: حاشیه نویسی فایل اکسل از طریق C++
description: نظرات حاشیه نویسی داده های صفحات گسترده Excel و OpenOffice را با کتابخانه C++ اضافه یا حذف کنید.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="مدیریت Microsoft<sup>&reg;</sup> حاشیه نویسی فایل اکسل از طریق C++" h2="یادداشت های ساده را برای حاشیه نویسی یا نظرات در برنامه های مبتنی بر C++ اضافه یا حذف کنید." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ اکسل API](/cells/fa/cpp/) با افزودن، دسترسی و حذف نظرات، از مدیریت حاشیه نویسی در سطح سلول پشتیبانی می کند. API فراهم می کند[IComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) و[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) همچنین[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)برای رسیدگی به نظرات در همه جنبه ها. فرمت های اکسل پشتیبانی شده شامل ODS، XLS، XLSX، XLSB و XLSM می باشد.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="حاشیه نویسی داده های فایل های اکسل" %}}
 دستکاری نظرات در کاربرگ ها - تعداد نظرات یک برگه در MS Excel محدود نمی شود. می توان به اندازه نیاز برنامه درج کرد. فرآیند درج نظرات، ایجاد[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) شی کلاس برای بارگذاری یک فایل موجود و برگه ای که می خواهید نظر را در آن اضافه کنید انتخاب کنید. تمام نظرات آن را با استفاده از getComments() دریافت کنید. اضافه کردن نظر با استفاده از[اضافه کردن](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > cellName) روش. شاخص سلول را دریافت کنید و استفاده کنید[setNote](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) برای درج نظرات همچنین API قابلیت حذف تمامی نظرات را دارد. تعداد کمی از روش ها هستند[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) به پاک کردن همه نظرات در صفحه گسترده طراح. علاوه بر این،[RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) روشی برای حذف عنصر در یک شاخص مشخص یا با نام مشخص شده است.

{{% blocks/products/pf/feature-page-code h3="C++ کد برای افزودن نظرات در فایل اکسل" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
