# WJD Digital Art Gallery v1.6.7.4 — Edit Profile Button Restore Fix

## แก้ปัญหา
- กดเมนู “แก้ไขรูปโปรไฟล์” แล้วไม่มีอะไรเกิดขึ้น
- หน้าต่าง Avatar ตัวเก่าถูกแก้จนปุ่มเปิดไม่ทำงาน

## สิ่งที่แก้
- เพิ่มหน้าต่างแก้ไข Avatar แบบปลอดภัยแยกจากระบบเก่า
- ดักเมนู “แก้ไขรูปโปรไฟล์ / แก้ไข Avatar / รูปโปรไฟล์”
- เปิดหน้าต่าง Avatar รวม 22 ตัวเลือกได้แน่นอน
- ซ่อนเครื่องมืออัปโหลดรูปตัวเอง
- บันทึก Avatar ลง localStorage และส่งไป Backend `setStudentAvatar`

## Backend
ไม่ต้องอัปเดตเพิ่ม ถ้าใช้ Backend v1.6.7.3 อยู่แล้ว

ถ้ายังไม่ได้อัปเดต Backend v1.6.7.3 ให้ใช้ไฟล์:
wjd-v1.6.7.3-backend-core-avatar-patch.zip

หลังอัป Backend ต้องเปิด:
https://script.google.com/macros/s/AKfycby9X2q7YZ_q33gdMoDA_6dljZqmdgWg1GMMkfz5_XE1qg7SLs_Fvvdti4j2AhxMxNuUDw/exec?action=setup
