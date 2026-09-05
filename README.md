# iFix Pattaya

เว็บไซต์ร้านซ่อมมือถือและรับซื้อซาก iPhone — พัทยา / ห้วยใหญ่

เว็บไซต์หน้าเดียว (one-page site) สร้างด้วย HTML/CSS/JavaScript ล้วน ไม่ต้อง build:

- 3D interactive teardown scene (Three.js / WebGL)
- Scroll-driven image-sequence story section
- Care package tiers, service marquee, contact CTA

## Deploy

ไฟล์นี้เป็น static site ล้วนๆ ไม่ต้อง build step ใดๆ — deploy บน [Vercel](https://vercel.com) ได้ทันทีโดยเลือก Framework Preset เป็น **Other**

## Local preview

เปิดไฟล์ `index.html` ในเบราว์เซอร์ได้เลย หรือรันเซิร์ฟเวอร์เล็กๆ:

```bash
python3 -m http.server 8000
```

แล้วเปิด http://localhost:8000

## หมายเหตุ

ภาพประกอบ AI บางส่วนในเว็บใช้ลิงก์ชั่วคราวจาก Hugging Face — ควรแทนที่ด้วยไฟล์ภาพถาวรก่อนใช้งานจริงระยะยาว
