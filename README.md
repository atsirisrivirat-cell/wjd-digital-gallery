# WJD Digital Art Gallery v1.5.2.3 — Navigation & Session Fix

แก้อาการหลัง v1.5.2.2:
- เมนูด้านบนกดไม่ได้
- ปุ่มต่าง ๆ ในเว็บไม่ตอบสนอง
- กด F5 แล้วหลุด login

## วิธีแก้ในเวอร์ชันนี้
- สร้างจาก v1.5.2 เดิม แล้วแก้เฉพาะแกน login/session อย่างปลอดภัย
- ยกเลิกระบบดักคลิกแบบครอบทั้งหน้า
- ทำให้ event listener ปลอดภัยขึ้น ถ้ามี element บางตัวหาย จะไม่ทำให้สคริปต์ทั้งเว็บหยุด
- กู้ session จาก localStorage หลัง Refresh
- ยังเชื่อม Google Drive Backend โรงเรียนเหมือนเดิม

## วิธีอัปเดต
อัปโหลด `index.html`, `README.md`, `vercel.json` ทับใน GitHub แล้วรอ Vercel deploy ใหม่
