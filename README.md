# WJD Digital Art Gallery v1.5.9.3 — Gift Submit Override Fix

## แก้ปัญหา
- ส่งของขวัญไม่สำเร็จ: Cannot read properties of null (reading 'reset')
- ส่งของแลกไม่สำเร็จ: Cannot read properties of null (reading 'reset')

## สาเหตุ
หน้าเว็บยังมี submit listener เก่าซ้อนอยู่ ทำให้ listener เก่าเรียก event.currentTarget.reset() หลัง async แล้ว error

## สิ่งที่แก้
- เพิ่ม submit handler ชั้น capture ที่หยุด listener เก่าอย่างเด็ดขาด
- ใช้ handler ใหม่ส่งของขวัญ/แลกของเพียงชุดเดียว
- reset ฟอร์มแบบปลอดภัย
- แลกของใช้ระบบง่าย: ส่งของไปก่อน ผู้ส่งได้ +1 แต้ม

## Backend
ใช้ Backend v1.5.9.1 ต่อได้ ไม่ต้องอัปเดต Apps Script
