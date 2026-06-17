# WJD Digital Art Gallery v1.6.7.2 — Avatar Picker Merge Fix

## แก้ปัญหา
- หน้า Private Avatar ยังแสดงแค่ Avatar เก่า 7 แบบ
- Avatar ใหม่ 15 แบบไม่แสดงในหน้าสมัคร/ตั้งค่าโปรไฟล์

## สิ่งที่แก้
- รวม Avatar เก่า 7 แบบ + Pixel Avatar ใหม่ 15 แบบ = 22 ตัวเลือก
- ใช้ picker เดียวกันในหน้า Private Avatar / สมัครโปรไฟล์ / แก้ไขโปรไฟล์
- ตัดและซ่อนเครื่องมืออัปโหลดรูปตัวเอง
- ฝัง Pixel Avatar ในแอปแบบ base64
- บันทึก Avatar เป็นรหัส เช่น pixel-01 ถึง pixel-15 หรือ old-01 ถึง old-07

## Backend
แนะนำใช้งานคู่กับ Backend v1.6.7.2 แล้วเปิด ?action=setup
