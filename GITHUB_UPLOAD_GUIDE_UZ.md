# GitHub’ga yuklash — IELTS Boost Stage 57 (`final-sss`)

Bu ko‘rsatma ZIP’ni GitHub Pages’da to‘g‘ri ishlaydigan qilib joylash uchun.

## 1. ZIP’ni ochish

1. `IELTS_Boost_Stage57_Final_Release_final-sss_GITHUB_READY.zip` faylini telefon yoki kompyuteringga yuklab ol.
2. Arxivni **Extract / Извлечь** qil. Ochilgan papkaning ichida `index.html`, `sw.js`, `manifest.webmanifest` va `assets`, `data`, `audio`, `icons` papkalari bevosita ko‘rinishi kerak.
3. GitHub’ga ZIP faylning o‘zini yuklama. Arxiv ichidagi fayllarni va papkalarni yukla. ZIP ichida ortiqcha bitta loyiha papkasi yo‘q; Android arxiv ochgichi nomli papka yaratishi mumkin — uning ichidagi narsalarni yuklash kerak.

## 2. Repository

1. GitHub’da `davronegamberdiyev42-svg` hisobiga kir.
2. `final-sss` nomli repository mavjud bo‘lmasa, aynan shu nom bilan yangi repository yarat. `final-sss ` (oxirida bo‘sh joy bilan) deb yozma; to‘g‘ri nom `final-sss`.
3. Default branch `main` bo‘lsin.
4. Repository root’iga quyidagi fayllarni yukla: `index.html`, `sw.js`, `manifest.webmanifest`, `release-check.html`, `favicon.svg`, `.nojekyll`, hujjatlar va `assets/`, `data/`, `audio/`, `icons/`, `docs/`, `tests/` papkalari. Papkalar ichidagi ichki yo‘llarni o‘zgartirma.

## 3. GitHub Pages

1. Repository → **Settings** → **Pages** ga kir.
2. **Build and deployment** bo‘limida **Deploy from a branch** tanla.
3. Branch: `main`; folder: `/(root)`; **Save** bos.
4. Deploy tugagach, asosiy sayt manzili:

   `https://davronegamberdiyev42-svg.github.io/final-sss/`

5. Birinchi marta aynan shu HTTPS manzilni och. Kirish sahifasi `index.html` bo‘lishi kerak.

## 4. Yakuniy tekshiruv

1. Sayt sarlavhasida **IELTS Boost · Stage 57 · Final Release** ko‘rinishi kerak.
2. Dashboard to‘liq dizayn bilan ochilishi, menyular ishlashi kerak. Oddiy qora matn ko‘rinishi yoki `Stage 56 yuklanmoqda…` yozuvi qolishi — eski yoki noto‘g‘ri deploy belgisi.
3. Keyin quyidagi sahifani och:

   `https://davronegamberdiyev42-svg.github.io/final-sss/release-check.html`

4. **Full production preflight** tugmasini bos. Hisobotda `FAIL = 0`, barcha 84 MP3 endpoint `PASS`, `App-data SHA-256 PASS` va `19,000 vocabulary PASS` bo‘lishi kerak. Fizik Android/mikrofon/offline cold-start tekshiruvlari qurilmada alohida bajariladi.

## 5. Juda muhim eslatmalar

- **Faqat `index.html` — Stage 57 asosiy kirish sahifasi.** `standalone.html` eski Stage 52 fallback bo‘lib, uni asosiy sahifa sifatida ochma.
- `assets/`, `data/`, `audio/`, `icons/` papkalarini root ichiga ko‘chirib yuborma; ular o‘z nomli papkalarida qolishi shart.
- ZIP’ni GitHub’ga arxiv sifatida joylash saytni ishga tushirmaydi. ZIP’ni ochib, tarkibini yuklash kerak.
- Sayt eski progressni ko‘rsatsa, avval Settings ichidan **COMPLETE backup** eksport qil. Backup qilmasdan Chrome site data’ni tozalama.

## Hozircha tasdiqlanmagan holat

Paket GitHub Pages’ga oldindan deploy qilinmagan. `final-sss` repository’ni yaratish/yuklash va yuqoridagi live preflight’ni bajarish GitHub hisobida amalga oshiriladi. ZIP esa `/final-sss/` project path va `main/(root)` uchun tayyorlangan.
