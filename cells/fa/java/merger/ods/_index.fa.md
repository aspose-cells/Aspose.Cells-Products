---
title:  ادغام ODS فایل via Java
weight: 6270
description: Java کد نمونه برای ترکیب اسناد ODS در Java Runtime Environment برای JSP/JSF Application و Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ادغام فرمت های ODS در Java" h2="ادغام سند بومی ODS با استفاده از APIهای سمت سرور Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="نحوه ادغام فایل های ODS با استفاده از Java" %}}

 برای ادغام فایل ODS، از آن استفاده خواهیم کرد[Aspose.Cells for Java](https://products.aspose.com/cells/java) API که یک پلتفرم ادغام با ویژگی های غنی، قدرتمند و آسان برای استفاده است API for Java. آخرین نسخه آن را می توانید مستقیماً از اینجا دانلود کنید[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) و با افزودن تنظیمات زیر به pom.xml آن را در پروژه مبتنی بر Maven خود نصب کنید.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="وابستگی" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="مراحل ادغام فایل های ODS در Java" %}}

{{% blocks/products/pf/agp/text %}}

 یک سند اساسی ادغام و الحاق با[Aspose.Cells for Java](https://products.aspose.com/cells/java) API ها را می توان تنها با چند خط کد انجام داد.

{{% /blocks/products/pf/agp/text %}}

+ اولین فایل ODS را با نمونه ای از کلاس Workbook بارگیری کنید.
+ دومین سند ODS را با نمونه ای از کلاس Workbook بارگیری کنید.
+ ادغام فایل ها با استفاده از متد ()combinate.
+ فایل ادغام شده ODS را در مسیر مشخص شده ذخیره کنید

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سیستم مورد نیاز" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می کند. لطفا مطمئن شوید که پیش نیازهای زیر را دارید.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows یا یک سیستم عامل سازگار با Java Runtime Environment برای برنامه های کاربردی JSP/JSF و برنامه های دسکتاپ.
-  آخرین نسخه Aspose.Cells for Java را مستقیماً از
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ادغام فایل های ODS - Java" offSpacer="" %}}

```cs
// Open the first ODS file.
Workbook odsFile1 = new Workbook("chartsFileWithPath.ods");

// Define the second source book.
// Open the second ODS file.
Workbook odsFile2 = new Workbook("pictureFileWithPath.ods");

// Combining the two workbooks
odsFile1.combine(odsFile2);

// Save the target book file.
odsFile1.save("combinedFileWithPath.ods");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="آنلاین ODS Merger Live Demos" sectionDescription=" اسناد ODS را همین حالا با مراجعه به ما ادغام کنید[وب سایت Live Demos](https://products.aspose.app/cells/merger). نسخه ی نمایشی زنده دارای مزایای زیر است" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" بدون نیاز به دانلود Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" نیازی به نوشتن هیچ کدی نیست." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="فقط فایل های ODS خود را آپلود کنید." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" فوراً ادغام و الحاق خواهد شد." >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="درباره Aspose.Cells for Java API" %}}

 Aspose.Cells API می تواند برای ایجاد، ویرایش، تبدیل و رندر فرمت های اکسل Microsoft به فرمت های مختلف استفاده شود. علاوه بر این، می توان از آن برای نمودارهای جامع، گزارش مقیاس پذیر و محاسبات قابل اعتماد در برنامه های نرم افزاری استفاده کرد. Aspose.Cells یک API مستقل است و به هیچ نرم افزاری مانند Microsoft یا OpenOffice نیاز ندارد.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
فایل هایی با پسوند ODS مخفف فرمت OpenDocument Spreadsheet Document هستند که توسط کاربر قابل ویرایش هستند. داده ها در فایل ODF در ردیف ها و ستون ها ذخیره می شوند. این فرمت مبتنی بر XML است و یکی از چندین زیرگروه در خانواده فرمت‌های سند باز (ODF) است. این قالب به عنوان بخشی از مشخصات ODF 1.2 منتشر شده و نگهداری شده توسط OASIS مشخص شده است. تعدادی از برنامه ها در Windows و همچنین سایر سیستم عامل ها می توانند فایل های ODS را برای ویرایش و دستکاری باز کنند، از جمله Microsoft Excel، NeoOffice و LibreOffice. فایل‌های ODS همچنین می‌توانند توسط برنامه‌های مختلف به فرمت‌های صفحه‌گسترده دیگر و همچنین مانند XLS، XLSX و موارد دیگر تبدیل شوند.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="سایر فرمت های ادغام پشتیبانی شده" subTitle="با استفاده از Java، One می تواند بسیاری از فرمت های فایل دیگر از جمله ..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="مقادیر جدا شده با کاما" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="زبان نشانه گذاری فرا متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="فرمت آرشیو صفحه وب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="مقادیر جدا شده از تب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="سند متنی" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="فرمت باینری اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="فایل باینری کتاب کار اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="فایل صفحه گسترده" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="فایل OOXML اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft قالب اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="قالب ماکرو فعال اکسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="قالب Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
