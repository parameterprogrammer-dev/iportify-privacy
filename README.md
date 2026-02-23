# iPortify — Privacy Policy & Terms of Service

เว็บไซต์สำหรับ Privacy Policy และ Terms of Service ของแอป iPortify  
รองรับ 2 ภาษา (ไทย/อังกฤษ) พร้อมสลับภาษาได้ทันที

## 📁 ไฟล์

| ไฟล์ | หน้าที่ |
|------|--------|
| `index.html` | Privacy Policy (นโยบายความเป็นส่วนตัว) |
| `terms.html` | Terms of Service (เงื่อนไขการใช้บริการ) |

## 🚀 วิธี Deploy บน GitHub Pages (ฟรี)

### ขั้นตอนที่ 1: สร้าง Repository

1. ไปที่ [github.com/new](https://github.com/new)
2. ตั้งชื่อ Repository: `iportify-privacy`
3. เลือก **Public**
4. กด **Create repository**

### ขั้นตอนที่ 2: อัปโหลดไฟล์

**วิธี A: ผ่านเว็บ (ง่ายสุด)**
1. กด **"uploading an existing file"** ในหน้า repo
2. ลากไฟล์ `index.html` และ `terms.html` เข้าไป
3. กด **Commit changes**

**วิธี B: ผ่าน Git CLI**
```bash
git clone https://github.com/YOUR_USERNAME/iportify-privacy.git
cd iportify-privacy
# คัดลอกไฟล์ index.html และ terms.html มาวางที่นี่
git add .
git commit -m "Add privacy policy and terms of service"
git push origin main
```

### ขั้นตอนที่ 3: เปิด GitHub Pages

1. ไปที่ Repository → **Settings** → **Pages**
2. Source: เลือก **Deploy from a branch**
3. Branch: เลือก **main** → โฟลเดอร์ **/ (root)**
4. กด **Save**
5. รอ 1-2 นาที จะได้ URL:

```
https://YOUR_USERNAME.github.io/iportify-privacy/          ← Privacy Policy
https://YOUR_USERNAME.github.io/iportify-privacy/terms.html ← Terms of Service
```

### ขั้นตอนที่ 4: ใช้ URL ใน App Store / Play Store

| ช่อง | URL |
|------|-----|
| Privacy Policy URL | `https://YOUR_USERNAME.github.io/iportify-privacy/` |
| Terms of Service URL | `https://YOUR_USERNAME.github.io/iportify-privacy/terms.html` |

## ✏️ สิ่งที่ต้องแก้ไขก่อน Deploy

1. **อีเมล** — แทนที่ `privacy@iportify.app` และ `support@iportify.app` ด้วยอีเมลจริง
2. **วันที่มีผลบังคับใช้** — เปลี่ยนจาก "1 มีนาคม 2026" เป็นวันจริงที่ deploy
3. **(ถ้ามี)** เพิ่มชื่อบริษัท/นิติบุคคลแทน "iPortify"

## 🌐 (ทางเลือก) ใช้ Custom Domain

ถ้าต้องการ URL สวยๆ เช่น `privacy.iportify.app`:

1. ซื้อโดเมน `iportify.app` (ประมาณ ฿500/ปี จาก Namecheap, Cloudflare)
2. ตั้ง CNAME record: `privacy` → `YOUR_USERNAME.github.io`
3. ใน GitHub Pages Settings → Custom domain: `privacy.iportify.app`
4. เปิด **Enforce HTTPS** ✅
