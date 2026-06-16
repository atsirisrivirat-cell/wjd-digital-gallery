# WJD Digital Art Gallery v1.5.6.4 — Direct Upload Submit Fix

## แก้ปัญหา
- ส่งรูปแล้วขึ้นว่า “บันทึกในเว็บแล้ว แต่ซิงก์ Google Drive ไม่สำเร็จ”
- สคริปต์ submit/sync หลายชุดทำงานซ้อนกัน ทำให้การส่งขึ้น Drive ไม่แน่นอน

## สิ่งที่แก้
- เปลี่ยนจังหวะส่งงานให้เป็น Direct Submit ทางเดียว
- กดส่งงานแล้วบันทึกในเว็บก่อน จากนั้นส่งเข้า Google Drive ทันที
- ต้องได้ `fileId` และ `fileUrl` ถึงจะถือว่าส่ง Drive สำเร็จ
- ถ้าล้มเหลว จะแสดง error จริงจาก Apps Script ให้ชัดกว่าเดิม
- ลดการชนกับ submit handler เก่าในจังหวะส่งงาน

## Backend
ใช้ Backend v1.5.6.3 ได้ ไม่ต้องอัปเดต Apps Script เพิ่ม
