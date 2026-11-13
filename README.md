# คู่มือบริการ กฟภ. (เว็บไซต์ภาพประกอบ)

เว็บไซต์ไฟล์เดียว (`index.html`) ไม่ต้องติดตั้งอะไร ใช้ฟรีบน GitHub Pages

## วิธีขึ้นเว็บฟรี
1. สร้าง repository ใหม่บน GitHub (Public) เช่น `pea-guide`
2. กด **Add file → Upload files** แล้วลากไฟล์ `index.html`, `spk-letter.pdf`, `.nojekyll`, `README.md` ไปวาง (ต้องมี `spk-letter.pdf` ด้วย ไม่งั้นปุ่มเปิด PDF ในหน้า ส.ป.ก. จะเปิดไม่ได้) → **Commit**
3. ไปที่ **Settings → Pages** → Source เลือก **Deploy from a branch** → Branch **main** / **(root)** → **Save**
4. รอ 1–2 นาที เปิดที่ `https://ชื่อบัญชี.github.io/pea-guide/`

## แก้ไขข้อมูล
เปิด `index.html` หาตัวแปร `const S=[` แล้วแก้ข้อความของแต่ละบริการได้โดยตรง
