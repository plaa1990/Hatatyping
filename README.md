# CodeQuest Academy - Ultimate Offline Edition (React 19 + TypeScript)

แพลตฟอร์มเกมเรียนรู้การเขียนโค้ดและพัฒนาทักษะ Full-Stack Developer แบบออฟไลน์ 100% ปราศจาก AI และ API ภายนอก

## 🌟 จุดเด่นของโปรเจกต์
- **100% Client-side Offline First**: ข้อมูลทั้งหมดประมวลผลบนเครื่องของผู้ใช้ และบันทึกสถานะผ่าน LocalStorage ไม่ต้องเชื่อมต่อเน็ตหรือ API
- **8 อาณาจักรแห่งการเรียนรู้ (Full-Stack Kingdoms & Boss Fights)**: Excel, HTML/CSS, JavaScript ES6+, Python & Pandas, SQL, React 19, Node.js REST APIs, Git & DevOps
- **ผังสายสกิล (Visual Skill Tree)**: แสดงลำดับวิชาบังคับก่อน (Prerequisites) เช่น HTML -> CSS -> JS -> React
- **ศูนย์รวมเครื่องมือฝึกฝน (Offline Dev Toolkit)**:
  - Interactive Sorting Visualizer (Bubble, Selection, Insertion Sort)
  - CSS Flexbox & Grid Interactive Lab (พร้อมสร้างโค้ด CSS)
  - Offline Live Code Sandbox (HTML/CSS/JS Runner พร้อม Virtual Console)
  - Regex Tester & Explainer (ทดสอบ Regular Expression แบบเรียลไทม์)
  - Keyboard Ninja Shortcut Drills (ฝึกคีย์ลัดโปรแกรมเมอร์)
  - Code Memory Match (เกมจับคู่การ์ดโค้ดและความหมาย)
  - Code Vault & Personal Notes (คลังบันทึกโค้ดและสูตรส่วนตัว)
- **Bug Smasher Arcade Game**: มินิเกมทุบแมลง 30 วินาที พร้อมระบบคอมโบ
- **Tech Office Simulator**: จำลองสถานการณ์การตัดสินใจจริงในสายงานวิศวกรซอฟต์แวร์
- **Web Audio API Sound Synthesizer**: ระบบสังเคราะห์เสียง SFX ออฟไลน์ ไม่ต้องดาวน์โหลดไฟล์เสียง mp3

---

## 🚀 วิธีการรันโปรเจกต์ (Installation & Development)

### 1. ติดตั้ง Dependencies
```bash
npm install
```

### 2. รันโหมด Development (เปิดใน Browser ที่ http://localhost:3000)
```bash
npm run dev
```

### 3. ตรวจสอบ Type และ Lint
```bash
npm run lint
```

### 4. Build สำหรับ Production
```bash
npm run build
```

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)
```
├── src/
│   ├── components/          # คอมโพเนนต์ทั้งหมด (โฟลเดอร์เดียว ไม่ซ้อน)
│   │   ├── Navbar.tsx             # Navbar ด้านบนและ Bottom Nav บนมือถือ
│   │   ├── WorldMap.tsx           # แผนที่ 8 อาณาจักร
│   │   ├── QuestScreen.tsx        # ระบบทำโจทย์คำถามและบอสไฟนอล
│   │   ├── SkillTree.tsx          # ผังสายสกิล
│   │   ├── DailyPlanView.tsx      # ตารางเรียน 7 วัน
│   │   ├── TrophyRoom.tsx         # ห้องถ้วยรางวัล
│   │   ├── ProfileView.tsx        # สมุดทักษะ บันทึกข้อผิดพลาด ใบประกาศนียบัตร
│   │   ├── CheatSheetHub.tsx      # คลังสูตรลัดและพจนานุกรม
│   │   ├── OfficeSimulator.tsx    # Tech Office Simulator
│   │   ├── BugSmasherArcade.tsx   # มินิเกม Bug Smasher
│   │   ├── OfflineToolsHub.tsx    # ศูนย์รวมเครื่องมือออฟไลน์
│   │   └── SortingVisualizer / FlexboxPlayground / CodeSandbox /
│   │       RegexTester / KeyboardDrills / MemoryMatch / CodeVault .tsx
│   ├── App.tsx              # คอมโพเนนต์หลักและ State Management
│   ├── main.tsx             # Entry point ของ React
│   ├── index.css            # Tailwind CSS & Fonts
│   ├── gameData.ts          # ข้อมูลโจทย์ เนื้อหาบทเรียน และผังสายสกิล
│   ├── sound.ts             # ระบบเสียงสังเคราะห์ Web Audio API (Offline)
│   └── types.ts             # TypeScript Interfaces
├── index.html               # HTML Entry Point
├── package.json             # NPM dependencies & scripts
├── tsconfig.json            # การตั้งค่า TypeScript
└── vite.config.ts           # การตั้งค่า Vite
```
