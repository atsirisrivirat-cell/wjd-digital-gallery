# WJD Digital Art Gallery v1.5.3 — Student/Teacher PIN Profile System

## สิ่งที่เพิ่ม
- ไม่มีเมนูสมัครสมาชิก
- นักเรียนสร้างโปรไฟล์จากการเข้าใช้งานครั้งแรกด้วย ชื่อ / ชั้น / ห้อง / เลขที่ / PIN
- ครั้งต่อไปนักเรียนใช้ข้อมูลเดิม + PIN เดิม
- ครูตั้ง PIN ครั้งแรก แล้วใช้ PIN เข้าเมนูครู
- ผู้เยี่ยมชมเข้าได้โดยไม่ต้องใช้ PIN
- ยังเชื่อม Google Drive Backend โรงเรียนเหมือนเดิม

## สำคัญ
ควรอัปเดต Google Apps Script Backend เป็น v1.5.3 ด้วย เพื่อให้ PIN เก็บใน Google Sheets กลาง
ถ้ายังไม่ได้อัปเดต backend หน้าเว็บจะ fallback เป็น local profile ชั่วคราว
