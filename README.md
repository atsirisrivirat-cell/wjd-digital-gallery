# WJD Digital Art Gallery v1.5.0 — Online Ready

เวอร์ชันนี้เตรียมจาก v1.4.4.12 ที่แก้ระบบเทมเพลตห้องผ่านแล้ว

## เป้าหมาย
ขึ้นออนไลน์ให้เปิดผ่านลิงก์ได้จากมือถือ แท็บเล็ต และคอมพิวเตอร์

## ขอบเขตของ v1.5.0
- ยังไม่เชื่อม Google Drive
- ยังไม่ซิงก์ข้อมูลข้ามเครื่อง
- ข้อมูลยังเก็บใน localStorage ของแต่ละอุปกรณ์
- ใช้สำหรับทดสอบการแสดงผลออนไลน์และ Responsive ก่อน

## วิธี Deploy บน Vercel
1. แตกไฟล์ zip
2. อัปโหลดโฟลเดอร์นี้ขึ้น GitHub repository
3. เข้า Vercel แล้ว Import repository
4. เลือก Static / Other
5. Build Command ปล่อยว่าง
6. Output Directory ใช้ `.`
7. กด Deploy

## วิธี Deploy บน GitHub Pages
1. อัปโหลดไฟล์ทั้งหมดไว้ที่ root ของ repository
2. เปิด Settings → Pages
3. เลือก Deploy from a branch
4. เลือก branch หลักและ root folder
5. Save แล้วรอลิงก์ Pages
