# WJD Digital Art Gallery v1.6.7.3 — Core Avatar Choices Patch

## แก้ปัญหา
- หน้า Private Avatar ยังเห็นแค่ Avatar เดิม 7 รูป
- Pixel Avatar 15 รูปใหม่ไม่แสดง

## สาเหตุ
หน้าต่าง Profile Editor ใช้ตัวแปรหลัก `profileAvatarChoices` ที่ล็อกไว้แค่ 7 รูปเดิม และวาดทับทุกครั้งที่เปิดหน้าต่าง

## สิ่งที่แก้
- แก้ `profileAvatarChoices` ตัวหลักโดยตรง
- รวม Avatar เดิม 7 รูป + Pixel Avatar ใหม่ 15 รูป = 22 ตัวเลือก
- ซ่อนส่วนอัปโหลดรูปจากมือถือ
- บันทึก Avatar ลง local และส่งไป Backend `setStudentAvatar`

## Backend
ต้องใช้ Backend v1.6.7.3 และเปิดลิงก์ setup:
https://script.google.com/macros/s/AKfycby9X2q7YZ_q33gdMoDA_6dljZqmdgWg1GMMkfz5_XE1qg7SLs_Fvvdti4j2AhxMxNuUDw/exec?action=setup
