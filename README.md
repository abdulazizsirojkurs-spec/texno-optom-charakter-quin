# Texno Optom Gaming — Quiz Konfigurator

Gaming PC konfigurator quiz sayti. Direct response marketing prinsiplari asosida.

## 📁 Loyiha tarkibi

- `index.html` — to'liq sayt (HTML + CSS + JS bitta faylda)
- `vercel.json` — Vercel deploy sozlamalari

## 🚀 Vercel'ga deploy qilish

### 1-usul: Eng oson (drag-and-drop)

1. https://vercel.com ga kiring va ro'yxatdan o'ting (GitHub yoki email orqali)
2. "Add New..." → "Project"
3. "Import Git Repository" emas, balki **"Browse all templates"** ostidagi havolaga bosing
4. Ekran pastida **"Deploy without Git"** ni qidiring yoki to'g'ridan-to'g'ri https://vercel.com/new ga kiring
5. Loyiha papkasini ZIP qilib drag-and-drop qiling

### 2-usul: GitHub orqali (TAVSIYA QILINGAN)

```bash
# 1. GitHub'da yangi repository yarating: texno-optom-quiz
# 2. Loyihani upload qiling:

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/texno-optom-quiz.git
git push -u origin main

# 3. https://vercel.com/new ga kiring
# 4. GitHub bilan ulang
# 5. texno-optom-quiz repository ni tanlang
# 6. "Deploy" tugmasini bosing
# 7. 30 soniya kuting — sayt tayyor!
```

### 3-usul: Vercel CLI (texnik foydalanuvchilar uchun)

```bash
npm install -g vercel
cd deploy/
vercel
# Savollarga javob bering:
#   - Set up and deploy: Y
#   - Which scope: o'z hisobingiz
#   - Link to existing project: N
#   - Project name: texno-optom-quiz
#   - In which directory: ./
#   - Override settings: N
```

## 🌐 Sayt manzili

Deploy bo'lgandan keyin: `https://texno-optom-quiz.vercel.app`

Vercel sizga avtomatik HTTPS, CDN va global hosting beradi — bepul.

## ⚙️ Sozlamalar

### Dollar kursi
Saytda **Ctrl+Shift+A** tugmalarini bossangiz, admin panel ochiladi va kursni o'zgartirishingiz mumkin. Yangi kurs `localStorage` da saqlanadi.

### Telegram bot
Token va Chat ID HTML faylda. Agar o'zgartirishingiz kerak bo'lsa:
- `TELEGRAM_BOT_TOKEN` — bot tokeni
- `TELEGRAM_CHAT_ID` — chat ID

### Facebook Pixel (keyinroq qo'shiladi)
- `FB_PIXEL_ID` — pixel ID

## 📞 Kontaktlar
- Telegram: @texnoptom_support
- Tel: +998 99 465 64 60, +998 50 151 88 11

## 🔧 Sayt yangilash

Agar narxlar, mahsulotlar yoki dizayn o'zgarsa:
1. Yangi `index.html` faylini oling
2. GitHub'da `index.html` ni almashtiring (yangi commit + push)
3. Vercel avtomatik 30 soniyada yangilaydi

---

**Yaratuvchi:** Claude AI yordamida
**Versiya:** 1.0 (2026 May)
