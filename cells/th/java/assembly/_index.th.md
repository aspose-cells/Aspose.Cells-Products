---
title: สร้างไฟล์ Excel via Java
description: สร้างสเปรดชีต Excel Microsoft จากแผ่นงานเทมเพลตโดยใช้ไลบรารีสเปรดชีต Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การสร้างรายงานตามเทมเพลต Excel via Java" h2="สร้างรายงานไฟล์ Excel จำนวนมากตามเทมเพลตที่กำหนดไว้ล่วงหน้าภายในแอปพลิเคชันที่ใช้ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java คลังเอ็กเซล](/cells/th/java/)รองรับการสร้างไฟล์ Excel ตามเทมเพลตสำหรับการสร้างรายงานจำนวนมาก ซึ่งจำเป็นสำหรับกรณีส่วนใหญ่ เช่น การสร้างคำถามเรื่องค่าธรรมเนียม บัตรผลลัพธ์ และบันทึกผู้ป่วย เป็นต้น เทมเพลตเป็นรูปแบบที่กำหนดไว้ล่วงหน้า รหัสด้านล่าง Java สร้างไฟล์ excel จำนวนมากเหมือนกับเอกสารเทมเพลตที่กรอกข้อมูล รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างรายงานตามเทมเพลต Excel ที่ออกแบบไว้ล่วงหน้า" %}}

 การใช้ Java แอสเซมบลี API นักพัฒนาสามารถตั้งโปรแกรมรหัสการสร้างรายงานจำนวนมากได้อย่างง่ายดายโดยการรวมส่วนย่อยของรหัสด้านล่าง APIจัดให้[นำเข้าข้อมูล](https://docs.aspose.com/cells/java/import-and-export-data/) คุณลักษณะจากแหล่งต่าง ๆ และสร้างเอกสาร Excel ขึ้นอยู่กับข้อมูลนั้น สำหรับรูปแบบตามเทมเพลต API ให้[ชั้นเรียนออกแบบสมุดงาน](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner)เพื่อแสดงแผ่นงานของนักออกแบบ กระบวนการคือสร้างวัตถุและใช้เพื่อเปิดไฟล์เทมเพลต กำหนดแหล่งข้อมูลซึ่งอาจเป็น Array, DataTable, Json เป็นต้น ประมวลผลเพื่อนำเข้าข้อมูลและบันทึกไฟล์ในรูปแบบที่ต้องการ โปรแกรมเมอร์สามารถรวบรวมข้อมูลเป็นรายงานในรูปแบบไฟล์อื่นๆ รวมถึง XLS, XLSX, XLSB, XLSM, ODS ตามลิงค์ด้านล่าง



{{% blocks/products/pf/feature-page-code h3="Java รหัสเพื่อสร้างรายงาน Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}
