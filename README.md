# 🚀 Getstarter Kit

Getstarter Kit คือชุดเริ่มต้น (starter template) สำหรับสร้างเว็บแอปพลิเคชันด้วยเทคโนโลยีทันสมัย  
ประกอบด้วย **React.js**, **Bun.js**, **Tailwind CSS**, **Framer Motion**, และ **Luxe UI**  
ช่วยให้คุณเริ่มโปรเจคได้รวดเร็ว พร้อมระบบ UI และ animation ที่สวยงามและปรับแต่งง่าย

---

## 🛠 Tech Stack

- **[React.js](https://react.dev/)** – JavaScript library สำหรับสร้าง UI แบบ component-based
- **[Bun.js](https://bun.sh/)** – JavaScript runtime ความเร็วสูง ใช้แทน Node.js
- **[Tailwind CSS](https://tailwindcss.com/)** – Utility-first CSS framework สำหรับสร้าง UI ได้เร็ว
- **[Framer Motion](https://www.framer.com/motion/)** – ไลบรารีสำหรับสร้าง animation ใน React
- **[Luxe UI](https://luxeui.dev/)** – Component UI ที่สวยงามและพร้อมใช้งาน

---

## 📦 การติดตั้ง

> **Prerequisite:** ติดตั้ง [Bun](https://bun.sh/) ก่อนเริ่มใช้งาน

```bash
# macOS / Linux
curl -fsSL https://bun.sh/install | bash

# Windows (PowerShell)
powershell -c "irm bun.sh/install.ps1 | iex"
```

---

## 🚀 เริ่มต้นใช้งาน

1. **โคลนโปรเจค**
```bash
git clone https://github.com/your-username/getstarter-kit.git
cd getstarter-kit
```

2. **ติดตั้ง dependencies ทั้งหมด**
```bash
bun install
bun add tailwindcss framer-motion @luxe-ui/react
```

3. **ติดตั้งและตั้งค่า Tailwind CSS**
```bash
bunx tailwindcss init -p
```
เพิ่มในไฟล์ `tailwind.config.js`:
```js
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}"
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
และเพิ่มในไฟล์ `src/index.css`:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

4. **รันโหมดพัฒนา**
```bash
bun dev
```

5. **สร้างไฟล์สำหรับ production**
```bash
bun run build
```

6. **รัน production**
```bash
bun start
```

---

## 📂 โครงสร้างโปรเจค

```
getstarter-kit/
├── src/
│   ├── components/      # UI Components
│   ├── pages/           # หน้าเพจหลัก
│   ├── styles/          # ไฟล์ CSS/Tailwind config
│   ├── App.jsx          # Root component
│   └── main.jsx         # Entry point
├── public/              # Static assets
├── package.json
├── bun.lockb
└── tailwind.config.js
```

---

## 🎨 ฟีเจอร์เด่น

- ✅ พร้อม Tailwind CSS config และ theme
- ✅ Animation ลื่นไหลด้วย Framer Motion
- ✅ Component UI จาก Luxe UI
- ✅ รันเร็วด้วย Bun.js
- ✅ โครงสร้างโปรเจคชัดเจน พร้อมต่อยอด

---

## 📄 License
MIT License © 2025 [Wutthipong-06]
