# WJD Digital Art Gallery v1.6.6.2 — My Room Tab Hard Override Fix

## แก้ปัญหา
- กดแท็บเมนู “ห้องของฉัน” แล้วยังขึ้น Cannot set properties of null (setting 'hidden')
- โค้ดเก่าเปิดห้องยังทำงานซ้อนอยู่

## สิ่งที่แก้
- ดักแท็บ/เมนู “ห้องของฉัน” โดยตรง
- ลบ onclick เก่าที่เกี่ยวกับห้องของฉัน แล้วผูก handler ใหม่
- เปิดห้องจากข้อมูลนักเรียนในเครื่องก่อน
- ซิงก์ Google Sheets แบบเงียบทีหลัง
- ถ้า element บางตัวไม่มีอยู่ ให้ข้าม ไม่ error

## Backend
ไม่ต้องอัปเดต Apps Script ใช้ Backend v1.6.5 ต่อได้
