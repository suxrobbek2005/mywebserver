# Web-server yaratish vazifasi

## Vazifa tavsifi
Sizning vazifangiz — Python yordamida oddiy web-server yaratish. Web-server uchta HTML sahifadan iborat bo'lishi kerak: `index.html`, `about.html` va `contact.html`. 
- `about.html` sahifasida `myimage.jpg` rasmi bo'lishi kerak.
- `index.html` sahifasida `welcome.jpg` rasmi bo'lishi kerak.
- `contact.html` sahifasida barcha kontakt ma'lumotlari jadval ko‘rinishida bo‘lishi kerak.
- Har bir sahifaga oddiy dizayn (style) qo'shish kerak.

## Talablar
1. **Web-serverni sozlash**
   - Python’ning o‘rnatilgan HTTP serveridan foydalaning.
   - Serverni ishga tushirish uchun quyidagi buyruqni bajaring:
     ```bash
     python -m http.server
     ```
   - Standart port `8000`, agar kerak bo'lsa, boshqa portni ko'rsating (masalan, `python -m http.server 8080`).

2. **Kerakli fayllarni yaratish**
   - `index.html` (Bosh sahifa)
   - `about.html` (`myimage.jpg` rasmini o‘z ichiga oladi)
   - `contact.html` (Aloqa sahifasi, kontaktlar jadval ko‘rinishida)
   - `styles.css` (Sahifalar uchun asosiy uslub)
   - Rasmlar: `myimage.jpg` va `welcome.jpg`

## Loyihaning tuzilishi
```
project_folder/
│-- index.html
│-- about.html
│-- contact.html
│-- styles.css
│-- images/
│   │-- myimage.jpg
│   │-- welcome.jpg
```

## Ko'rsatmalar
1. **Loyiha papkasini yarating** va unga kiring.
2. **HTML sahifalarni yarating** (`index.html`, `about.html`, `contact.html`) va ularga kontent qo‘shing.
3. **`styles.css` faylini yarating** va sahifalarga dizayn qo‘shing.
4. **Rasmlarni** (`myimage.jpg` va `welcome.jpg`) `images/` papkasiga joylashtiring.
5. **Web-serverni ishga tushiring** `python -m http.server` buyrug‘i yordamida.
6. **Brauzeringizda oching** va `http://localhost:8000/index.html` sahifasiga kiring.

## Web-serverni ishga tushirish
1. Terminal yoki buyruq qatorini (`cmd` yoki `bash`) oching va `project_folder` papkasiga o'ting.
2. Quyidagi buyruqni bajaring:
   ```bash
   python -m http.server
   ```
3. Brauzeringizda quyidagi manzillarni oching:
   - `http://localhost:8000/index.html`
   - `http://localhost:8000/about.html`
   - `http://localhost:8000/contact.html`

## Vazifani topshirish
- Barcha fayllar to‘g‘ri joylashganligini tekshiring.
- Ishlayotgan server va ochilgan sahifalarning skrinshotini oling.
- Loyihangizni GitHub-ga yuklab, `git push` qiling va havolasini taqdim eting.

Omad!
