---
title: สร้างไฟล์ Excel ผ่าน Java

description: สร้างสเปรดชีต Microsoft Excel จากแผ่นเทมเพลตโดยใช้ Java ไลบรารีสเปรดชีต
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การสร้างรายงานตามเทมเพลต Excel ผ่าน Java" h2="สร้างรายงานไฟล์ Excel จำนวนมากตามเทมเพลตที่กำหนดไว้ล่วงหน้าภายในแอปพลิเคชันที่ใช้ Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java ไลบรารี Excel](/cells/java/) รองรับการสร้างไฟล์ Excel ที่ใช้เทมเพลตสำหรับการสร้างรายงานจำนวนมาก จำเป็นสำหรับกรณีส่วนใหญ่ เช่น การสร้างค่าธรรมเนียมท้าทาย บัตรผลลัพธ์ และบันทึกผู้ป่วย เป็นต้น แม่แบบคือรูปแบบที่กำหนดไว้ล่วงหน้า โค้ดด้านล่าง Java จะสร้างไฟล์ excel จำนวนมากเหมือนกับเอกสารเทมเพลตที่มีการกรอกข้อมูล รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLSM, ODS
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างรายงานตามเทมเพลต Excel ที่ออกแบบไว้ล่วงหน้า" %}}

การใช้ Java แอสเซมบลี API นักพัฒนาซอฟต์แวร์สามารถตั้งโปรแกรมโค้ดการสร้างรายงานจำนวนมากได้อย่างง่ายดาย โดยรวมข้อมูลโค้ดด้านล่าง API ให้ [นำเข้าข้อมูล](https://docs.aspose.com/cells/java/import-and-export-data/) จากแหล่งต่าง ๆ และสร้างเอกสาร Excel ขึ้นอยู่กับข้อมูลนั้น สำหรับรูปแบบตามเทมเพลต API ให้ a [เวิร์กบุคคลาสนักออกแบบ](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) เพื่อแสดงเวิร์กชีตของนักออกแบบ กระบวนการคือ สร้างวัตถุและใช้เพื่อเปิดไฟล์เทมเพลต ตั้งค่าแหล่งข้อมูลที่อาจเป็น Array, DataTable, Json เป็นต้น ประมวลผลเพื่อนำเข้าข้อมูลและบันทึกไฟล์ในรูปแบบที่ต้องการ โปรแกรมเมอร์สามารถรวบรวมข้อมูลลงในรายงานในรูปแบบไฟล์อื่น ๆ รวมถึง XLS, XLSX, XLSB, XLSM, ODS ตามลิงค์ด้านล่าง



{{% blocks/products/pf/feature-page-code h3="Java รหัสสำหรับสร้างรายงาน Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}
