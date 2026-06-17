# WJD Digital Art Gallery v1.6.8.1 — Profile Menu Avatar Direct Fix

## แก้ปัญหา
- กดเมนู “แก้ไข Avatar โปรไฟล์” แล้วเมนูหาย แต่ไม่มีหน้าต่างขึ้นมา
- มีปัญหาแจ้ง “กรุณาเข้าสู่ระบบนักเรียนก่อน”

## สิ่งที่แก้
- ไม่ใช้หน้าต่างแก้ไขโปรไฟล์เก่าที่มีปัญหา
- ทำหน้าต่าง Avatar แบบตรง ๆ แยกออกมา
- ดักการกดตั้งแต่ pointerdown / mousedown / click ก่อนเมนูปิดตัวเอง
- เปิดหน้าต่างได้โดยไม่เช็ก login ก่อน
- ใช้ Avatar เดิม 7 ภาพเท่านั้น
- ซ่อนอัปโหลดรูปโปรไฟล์

## Backend
ไม่ต้องอัปเดต Backend เพิ่ม ถ้าใช้ Backend v1.6.7.3 อยู่แล้ว

ถ้าในอนาคตมีการอัป Backend ให้เปิด:
https://script.google.com/macros/s/AKfycby9X2q7YZ_q33gdMoDA_6dljZqmdgWg1GMMkfz5_XE1qg7SLs_Fvvdti4j2AhxMxNuUDw/exec?action=setup
