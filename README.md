# WJD Digital Art Gallery v1.5.2 — Google Drive Connected

เวอร์ชันนี้เชื่อมเว็บกับ Google Apps Script Backend ของบัญชีโรงเรียนแล้ว

## Backend URL

`https://script.google.com/macros/s/AKfycby9X2q7YZ_q33gdMoDA_6dljZqmdgWg1GMMkfz5_XE1qg7SLs_Fvvdti4j2AhxMxNuUDw/exec`

## สิ่งที่เพิ่มจาก v1.5.0

- ส่งผลงานแล้วพยายามบันทึกไปยัง Google Drive โรงเรียน
- บันทึกข้อมูลผลงานลง Google Sheets ของโรงเรียน
- ถ้าส่ง Drive ไม่สำเร็จ ยังบันทึก localStorage ไว้ก่อน
- เพิ่มสถานะในหน้าผลงานของนักเรียนว่า Google Drive ซิงก์สำเร็จหรือยัง

## สิ่งที่ยังเป็นข้อจำกัด

- ระบบครูในหน้าเว็บยังอ่านจาก localStorage เป็นหลัก
- การดึงรายการจาก Google Sheets กลับมาแสดงในเว็บจะทำในเวอร์ชันถัดไป
- ยังเป็นระบบทดลอง ไม่ใช่ระบบล็อกอินจริง
