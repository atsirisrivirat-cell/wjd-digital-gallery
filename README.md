# WJD Digital Art Gallery v1.5.8 — Clean Room Reset & Room Sync

## สิ่งที่เพิ่ม
- รีเซ็ตข้อมูลตกแต่งห้องเดิมในเครื่องให้ห้องเริ่มโล่ง
- ไม่รีเซ็ตโปรไฟล์ / ผลงาน / แต้ม
- เพิ่ม Room Sync กับ Google Sheets แท็บ `Rooms`
- เจ้าของห้องแต่งห้องแล้วระบบบันทึกไป Google Sheets
- เพื่อนไปเยี่ยมห้อง จะดึงห้องล่าสุดจาก Google Sheets ก่อนแสดง
- คนที่ไม่ใช่เจ้าของห้องดูได้อย่างเดียว แก้ไม่ได้

## ต้องอัปเดต Backend ก่อน
ใช้ชุด `wjd-v1.5.8-backend-room-sync.zip`
แล้วเปิด Web App URL ต่อท้าย `?action=setup` เพื่อสร้างแท็บ Rooms
