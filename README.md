# การส่งงานครั้งที่ 1: Student API (CRUD Operations)

โปรเจกต์นี้เป็นส่วนหนึ่งของวิชาการพัฒนา Backend API โดยสร้างระบบจัดการข้อมูลนักศึกษาจำลอง (Mock Data) รองรับการทำงานพื้นฐานตามหลัก CRUD (Create, Read, Update, Delete) ด้วย Node.js และ Express

---

## 👤 ข้อมูลผู้จัดทำ

- **ชื่อ-นามสกุล:** [มนทกานต์ ปาลี]
- **รหัสนิสิต:** 67160042

---

## 🛠️ เครื่องมือและเทคโนโลยีที่ใช้

- **Runtime:** Node.js
- **Framework:** Express (v5.2.1)
- **Development Tool:** Nodemon (v3.1.14) สำหรับ Auto-restart เซิร์ฟเวอร์
- **Testing Tool:** Postman

---

## 📂 โครงสร้างโปรเจกต์ (Project Structure)

```text
wk01-67160042/
├── node_modules/         # โฟลเดอร์เก็บไลบรารี/โมดูลที่ติดตั้ง
├── index.js              # ไฟล์หลักสำหรับรันเซิร์ฟเวอร์และกำหนด Routes
├── package.json          # ไฟล์กำหนดค่าพื้นฐานและ Dependencies ของโปรเจกต์
└── package-lock.json     # ไฟล์บันทึกเวอร์ชันของโมดูลอย่างละเอียด
```
