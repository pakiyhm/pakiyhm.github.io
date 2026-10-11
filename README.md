# 🌟 IYHM Portfolio Website
> **Narongsak Buangam (Pak)** — Full-Stack Developer • IoT Innovator • Creative Technologist  
> Royal Award Recipient 2020 • 1st Runner-Up Thailand Innovator Award (TIA 2019)

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```
iyhm-portfolio/
├── index.html                  # ไฟล์หน้าเว็บหลัก (Single Page Application)
├── assets/
│   ├── css/
│   │   └── style.css           # สไตล์ Glassmorphism, Badge, Animation เสริม
│   ├── js/
│   │   └── main.js             # ตัวควบคุม Interactive Tabs, Modals, Theme, Toast
│   └── images/                 # รูปภาพจริงความละเอียดสูงทั้งหมด
│       ├── hero_portrait.png   # รูปหน้าปกชุดสูททางการ (Hi-Res)
│       ├── avatar_formal.jpg   # รูปโปรไฟล์ชุดนักศึกษา
│       ├── award_*.jpg         # รูปรางวัลนวัตกรรมแห่งประเทศไทย, สิทธิบัตร, แผนธุรกิจ
│       ├── royal_award_*.jpg   # รูปพิธีรับรางวัลพระราชทาน
│       └── project_*.jpg       # รูปผลงานจริง (บอร์ดเกม, เว็บ, การตลาด)
└── README.md                   # เอกสารแนะนำการใช้งาน
```

---

## 🚀 วิธีเปิดใช้งาน (How to Run)

### วิธีที่ 1: เปิดไฟล์โดยตรง (Direct Open)
- สามารถดับเบิลคลิกเปิดไฟล์ `index.html` บนเบราว์เซอร์ (Chrome, Safari, Edge, Firefox) ได้ทันที

### วิธีที่ 2: รันผ่าน Local Server
เปิด Terminal เข้ามาที่โฟลเดอร์นี้ แล้วรันคำสั่ง:

```bash
# ใช้ Python
python3 -m http.server 3000

# หรือใช้ Node.js npx serve
npx serve .
```
แล้วเปิดเบราว์เซอร์ไปที่: `http://localhost:3000`

---

## 🌐 การนำขึ้นออนไลน์ (Deployment Options)

1. **Cloudflare Pages (แนะนำ - ฟรี & เร็วที่สุด):**
   - ลากโฟลเดอร์ `iyhm-portfolio` อัปโหลดผ่านหน้า Cloudflare Pages Direct Upload
   - ผูกโดเมน `www.iyhm.online` ได้ทันทีแบบฟรี SSL

2. **GitHub Pages (pakiyhm.github.io):**
   - Repository: `https://github.com/pakiyhm/pakiyhm.github.io`
   - Push to `main` branch: `git push -u origin main`
   - Live URL: `https://pakiyhm.github.io/`

3. **Vercel / Netlify:**
   - นำเข้า Repo ผ่าน Vercel / Netlify เพื่อเปิดใช้งานทันที
