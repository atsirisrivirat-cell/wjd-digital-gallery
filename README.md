# WJD Digital Art Gallery v1.5.6.3 — Direct Drive Upload & Visible User Admin Fix

## แก้ปัญหา
- ไม่เห็นส่วน “จัดการยูสเซอร์นักเรียน” ในหน้าครู
- นักเรียนจากอีกเครื่องส่งรูปแล้วไม่เข้า Google Drive / Google Sheets

## สิ่งที่แก้ในเว็บ
- ย้ายแผงจัดการยูสเซอร์นักเรียนมาไว้ด้านบนของหน้าครู เห็นชัดขึ้น
- เพิ่มปุ่มรีเฟรชรายชื่อนักเรียนตรงหน้าครู
- เพิ่ม Direct Drive Upload Sync หลังนักเรียนกดส่งงาน
- งานที่ค้างในเครื่องจะถูกส่งซ้ำขึ้น Google Drive อัตโนมัติ
- ตรวจว่าต้องมี fileId + fileUrl จริง จึงถือว่าส่งเข้า Drive สำเร็จ

## ต้องอัปเดต Backend ด้วย
ใช้ `wjd-v1.5.6.3-backend-direct-upload-user-admin.zip`
