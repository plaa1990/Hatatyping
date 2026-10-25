# Polyglot Typing Studio

แอปฝึกพิมพ์ 5 ภาษา (อังกฤษ ไทย จีน เกาหลี ญี่ปุ่น) เป็นเว็บแอปแบบ static ไม่ต้อง build ติดตั้งลงมือถือ/คอมได้ (PWA) และใช้ออฟไลน์ได้หลังเปิดครั้งแรก

## ขึ้น GitHub Pages
1. สร้าง repository ใหม่บน GitHub (Public)
2. กด Add file → Upload files แล้วลากไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, sw.js, manifest.webmanifest, โฟลเดอร์ icons, .nojekyll) ขึ้นไปที่รากของ repo แล้ว Commit
3. ไปที่ Settings → Pages → Source เลือก Deploy from a branch → Branch: main / (root) → Save
4. รอ 1–2 นาที จะได้ลิงก์ `https://ชื่อผู้ใช้.github.io/ชื่อrepo/`

## ติดตั้งลงเครื่อง
- Android (Chrome): เปิดลิงก์ → เมนู ⋮ → ติดตั้งแอป
- iPhone (Safari): ปุ่มแชร์ → เพิ่มไปยังหน้าจอโฮม
- คอมพิวเตอร์ (Chrome/Edge): ไอคอนติดตั้งที่แถบที่อยู่

ต้องเปิดผ่านลิงก์ https (เช่น GitHub Pages) ถึงจะติดตั้งและใช้ออฟไลน์ได้ ถ้าเปิดไฟล์ index.html ตรง ๆ จะใช้งานได้แต่ติดตั้งไม่ได้

## อัปเดตแอป
อัปโหลดไฟล์ใหม่ทับ แล้วแก้เลขเวอร์ชันแคชใน sw.js (`polyglot-typing-v2` → `v3`) เพื่อให้เครื่องที่ติดตั้งไว้โหลดของใหม่
