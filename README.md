# WJD Digital Art Gallery v1.5.2.2 — Login Core Fix

แก้บั๊กที่เลือกบัญชีแล้วกลับไปยังสถานะ "ยังไม่ได้เข้าสู่ระบบ"

## สิ่งที่แก้
- แก้แกนหลักของระบบ login: selectAccount / restoreSession / updateAuthUI
- updateAuthUI ปลอดภัยขึ้น ไม่ให้ element บางตัวที่หาไม่เจอทำให้ login ล้มเหลว
- หลังเลือกบัญชีจะบังคับแสดงหน้า Home และซ่อนหน้า Login
- ระบบสำรองจะตรวจซ้ำ ถ้า login ไม่สำเร็จจะบันทึก session แล้ว reload อัตโนมัติ
- ยังเชื่อม Google Drive Backend โรงเรียนเหมือน v1.5.2

## วิธีอัปเดต
อัปโหลด `index.html`, `README.md`, `vercel.json` ทับใน GitHub แล้วรอ Vercel deploy ใหม่
