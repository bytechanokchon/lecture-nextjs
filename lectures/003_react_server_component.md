# React Server Component
เป็นสถาปัตยกรรมที่่ถูกแนะนำโดย react team โดยแบ่งออกเป็น 2 แบบ
- **Server component**
- **Client component**

### Server component
เป็นค่าเริ่มต้นของแอพพลิเคชัน โดยการเรนเดอร์จะทำงานที่ฝั่ง server ไม่ว่าจะเป็นการอ่านไฟล์, การดึงข้อมูล แต่มีข้อเสียคือจะไม่สามารถใช้งาน react hook เพื่อจัดการ state ได้

### Client component
เป็นการตั้งค่าการเรนเดอร์ให้ทำที่ฝั่งเครื่องของผู้ใช้ โดยใช้คำสั่ง `"use client"` 