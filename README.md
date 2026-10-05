# AR Mario – HIRO Marker Game 🎮

เว็บ AR สำหรับเล่นผ่านกล้องมือถือ/คอมพิวเตอร์ โดยใช้ **AR.js + A-Frame**

## วิธีเล่น
1. เปิดเว็บผ่าน HTTPS (แนะนำ GitHub Pages)
2. อนุญาตการใช้กล้อง
3. ส่องกล้องไปที่ **HIRO marker**
4. เมื่อพบ marker จะเห็นตัวละคร Mario
5. กด **กระโดดโหม่งเหรียญ +10** เพื่อรับ 10 คะแนน
6. กด **จบเกม** เพื่อแสดงคะแนนรวมและเอฟเฟกต์พลุฉลอง 🎆

## ไฟล์
- `index.html` — โปรแกรม AR หลัก
- `mario.png` — รูปตัวละครที่ใช้ใน AR
- `hiro.png` — รูป Marker ที่แนบมา

## เปิดบน GitHub Pages
1. สร้าง Repository ใหม่ เช่น `ar-mario-hiro-game`
2. Upload ทั้ง 3 ไฟล์ให้อยู่ระดับเดียวกัน
3. ไปที่ **Settings → Pages**
4. เลือก **Deploy from a branch**
5. เลือก `main` และ `/ (root)`
6. Save แล้วเปิด URL ที่ GitHub สร้างให้
7. เปิดด้วยมือถือและอนุญาต Camera

> หมายเหตุ: กล้องบนมือถือมักต้องใช้ HTTPS ดังนั้น GitHub Pages เหมาะกับการทดสอบจริงมากกว่าเปิด `index.html` ตรง ๆ จากไฟล์ในเครื่อง

## Marker
โปรแกรมตั้งค่าเป็น AR.js `preset="hiro"` จึงใช้มาตรฐาน HIRO marker ได้โดยตรง
