# Maxfiylik siyosati — So'z va Akustika

**Oxirgi yangilanish:** 2026-yil 14-avgust

Bu hujjat "So'z va Akustika" mobil ilovasi (`com.jking0130.sozakustika`) qanday
ma'lumot yig'ishini, undan qanday foydalanishini va foydalanuvchi qanday huquqlarga
ega ekanini tushuntiradi.

**Ma'lumot nazoratchisi (data controller):** Jasurbek — `jollyking.0130@gmail.com`

---

## 1. Qisqacha

Ilova **internetsiz ishlaydi**. So'zlar, o'rganish tarixi va sozlamalar
**telefoningizda** saqlanadi. Ma'lumot serverga faqat siz **o'zingiz xohlab**
Google bilan kirganingizda yuboriladi.

**Bolalar uchun:** ilovadan 13 yoshgacha bolalar ham foydalanadi. Ular uchun
hisobga kirish taklif qilinmaydi, **hech qanday shaxsiy ma'lumot yig'ilmaydi**,
reklama esa faqat kichik banner shaklida va shaxsiylashtirilmagan holda
ko'rsatiladi. Batafsil — 5-bo'lim.

---

## 2. Qanday ma'lumot yig'iladi

### 2.1 Kirmasangiz (anonim foydalanish)

Serverga hech qanday shaxsiy ma'lumot yuborilmaydi. Quyidagilar faqat telefoningizda:

- o'rganilgan so'zlar va takrorlash jadvali
- kunlik maqsad, seriya, ball (XP), nishonlar
- sozlamalar (ko'rinish, matn o'lchami, ovoz, tungi rejim)

### 2.2 Google bilan kirsangiz (ixtiyoriy, faqat kattalar rejimida)

Global reytingga qo'shilish va tarifni hisobingizga bog'lash uchun:

| Ma'lumot | Nima uchun | Huquqiy asos |
|----------|-----------|--------------|
| Elektron pochta manzili | hisobni aniqlash, tarifni bog'lash | shartnoma ijrosi |
| Ism (Google profilidagi) | reytingda ko'rsatish | roziligingiz |
| Ball, seriya, o'rganilgan so'zlar soni | reyting jadvali | roziligingiz |
| Tarif va uning muddati | pullik imkoniyatlarni ochish | shartnoma ijrosi |

Ma'lumot **Supabase** (PostgreSQL) xizmatida saqlanadi.
Parolingiz ilovaga **hech qachon kiritilmaydi** — kirish Google orqali amalga oshadi.

### 2.3 Reklama (faqat kattalar rejimida, faqat bepul tarifda)

Bepul tarifda **Google AdMob** reklamasi ko'rsatiladi. AdMob qurilma reklama
identifikatorini (Advertising ID) va taxminiy joylashuvni reklama ko'rsatish uchun
ishlatishi mumkin.

- Reklama darajasi **"G" (hamma uchun)** bilan cheklangan.
- Shaxsiylashtirilmagan reklama so'raladi.
- Pullik tariflarda (Mini, O'rta, VIP) va 14 kunlik demo davrida **reklama yo'q**.
- **Bolalar rejimida** to'liq ekranli reklama ko'rsatilmaydi va reklama
  identifikatori uzatilmaydi — 5.2-bo'limga qarang.

AdMob maxfiylik siyosati: https://policies.google.com/technologies/ads

---

## 3. Ma'lumot kimga beriladi

**Hech kimga sotilmaydi.** Faqat ilovaning ishlashi uchun zarur xizmatlar:

| Xizmat | Maqsad | Joylashuvi |
|--------|--------|-----------|
| Google (kirish) | hisobni tasdiqlash | global |
| Supabase | ma'lumotni saqlash | EU serverlari |
| Google AdMob | reklama (faqat kattalar, bepul tarif) | global |
| Google Play Billing | to'lovni qayta ishlash | global |

Ma'lumot O'zbekistondan tashqariga uzatilishi mumkin. Bunda xizmat
provayderlarining standart shartnoma shartlariga tayanamiz.

**Saqlash muddati:** hisob faol bo'lgan davrda. Hisobni o'chirsangiz — 30 kun
ichida o'chiriladi.

---

## 4. Sizning huquqlaringiz

- **Ko'rish:** hisobingizdagi ma'lumotni so'rashingiz mumkin.
- **Tuzatish:** noto'g'ri ma'lumotni tuzatishni so'rashingiz mumkin.
- **O'chirish:** hisobni va unga bog'liq barcha ma'lumotni o'chirishni so'rashingiz mumkin.
- **Ko'chirish:** ma'lumotingizni mashina o'qiy oladigan shaklda olishingiz mumkin.
- **Rozilikni qaytarish:** hisobdan chiqsangiz, ilova anonim rejimda ishlayveradi.
- **Telefondagi ma'lumot:** ilovani o'chirsangiz, u ham o'chadi.

Agar javobdan qoniqmasangiz, o'z davlatingizdagi ma'lumotlarni himoya qilish
organiga murojaat qilish huquqingiz bor.

---

<a id="hisobni-ochirish"></a>

## 4-A. Hisobni o'chirish — qadamma-qadam

> Bu bo'lim **"So'z va Akustika"** ilovasi (ishlab chiquvchi: Jasurbek,
> `com.jking0130.sozakustika`) foydalanuvchilari uchun.

**Hisobingizni va ma'lumotlaringizni o'chirish uchun:**

1. **jollyking.0130@gmail.com** manziliga xat yuboring.
2. Mavzu qatoriga yozing: **"Hisobni o'chirish"**.
3. Xat matnida ilovaga kirgan **elektron pochta manzilingizni** ko'rsating —
   bu hisobni aniqlash uchun kerak. Boshqa hech qanday ma'lumot so'ralmaydi.
4. Tasdiqlash uchun sizga javob xati keladi.
5. Hisob va unga bog'liq ma'lumot **30 kun ichida** o'chiriladi.

**Qaysi ma'lumot o'chiriladi:**

| Ma'lumot | Holati |
|----------|--------|
| Elektron pochta manzili | **O'chiriladi** |
| Ism (Google profilidan) | **O'chiriladi** |
| Reyting yozuvi: ball, seriya, o'rganilgan so'zlar soni | **O'chiriladi** |
| Tarif (obuna) yozuvi | **O'chiriladi** |
| Telefoningizdagi o'rganish tarixi va sozlamalar | Serverda saqlanmaydi — ilovani o'chirsangiz yo'qoladi |

**Qaysi ma'lumot saqlanib qolishi mumkin:**

| Ma'lumot | Muddat | Sabab |
|----------|--------|-------|
| Google Play to'lov yozuvi | Google belgilagan muddat | Buxgalteriya va soliq talabi — bu yozuv **Google'da**, bizda emas |

Boshqa hech narsa saqlanmaydi.

**Hisobni o'chirmasdan faqat ma'lumotni o'chirish** ham mumkin — xatda shuni
yozing (masalan: "reytingdan chiqaring, hisob qolsin").

**Ilovaga kirmagan bo'lsangiz** — o'chiradigan narsa yo'q. Kirmasdan
foydalanganda hech qanday ma'lumot serverga yuborilmaydi.

---

Boshqa so'rovlar uchun ham: **jollyking.0130@gmail.com** · javob **30 kun** ichida.

---

## 5. Bolalar va ota-onalar

Ilova **aralash auditoriya** uchun: undan kattalar ham, 13 yoshgacha bolalar ham
foydalanadi. Bolalarni himoya qilish uchun quyidagilar amal qiladi.

### 5.1 Yoshni aniqlash

Ilova birinchi ochilganda **tug'ilgan yil** so'raladi. Savol neytral beriladi —
ya'ni qaysi javob qanday natija berishi oldindan ko'rsatilmaydi, shunday qilib
bola javobni "to'g'rilashga" undalmaydi. Javob faqat telefonda saqlanadi,
serverga yuborilmaydi.

### 5.2 Bolalar rejimida nima o'zgaradi

13 yoshgacha deb belgilangan foydalanuvchi uchun:

| Nima | Holati |
|------|--------|
| Reklama formati | Faqat **banner** (kichik, ekran chetida). To'liq ekranli reklama **ko'rsatilmaydi** |
| Reklama mazmuni | Faqat **"G" — hamma uchun**. Alkogol, qimor, tanishuv, kattalar mazmuni bloklangan |
| Shaxsiylashtirilgan reklama | **Yo'q**. Qiziqishga asoslangan reklama va remarketing o'chirilgan |
| Reklama identifikatori (Advertising ID) | **Uzatilmaydi** |
| Google bilan kirish | **Ko'rsatilmaydi** |
| Global reyting (ism, ball serverga) | **Ishlamaydi** |
| Serverga yuboriladigan shaxsiy ma'lumot | **Yo'q** |
| Lug'atdagi kattalarga oid so'zlar | **Filtrlangan** (alkogol, tamaki, qurol, jinsiy mavzu) |

Ya'ni bolalar rejimida biz bola haqida **hech qanday shaxsiy ma'lumot bilmaymiz**.
Reklama ko'rsatiladi, lekin u shaxsiylashtirilmagan va o'quv jarayonini uzmaydi.

Bolalar rejimida reklamani butunlay yo'qotish uchun istalgan pullik tarifni
(Mini, O'rta, VIP) olish kifoya — ota-ona o'z hisobidan amalga oshiradi.

### 5.3 Obuna va to'lov

Obunani faqat **kattalar rejimida** va faqat Google Play hisobi orqali sotib
olish mumkin. Bola to'lov oynasiga kira olmaydi. Ota-ona farzandiga tarif
bermoqchi bo'lsa, o'z qurilmasida yoki o'z hisobi bilan kirib amalga oshiradi.

Google Play'da xaridni ota-ona nazorati (Family Link) bilan cheklash mumkin.

### 5.4 Ota-onaning huquqlari

Bolalar rejimida biz hech qanday ma'lumot yig'maganimiz uchun o'chirish uchun
narsa qolmaydi. Agar bolangiz kattalar rejimida hisob ochib qo'ygan deb
gumon qilsangiz — **jollyking.0130@gmail.com** ga yozing, hisobni va barcha
ma'lumotni o'chirib beramiz. Tasdiqlash uchun hisob elektron pochtasini
so'raymiz.

### 5.5 Qo'llanadigan qoidalar

Bu bo'lim quyidagilarga muvofiq tuzilgan:

- **Google Play Families siyosati** (aralash auditoriya talablari)
- **COPPA** (AQSh, 13 yoshgacha bolalar) — biz bolalardan shaxsiy ma'lumot
  yig'maymiz, shu sababli ota-ona roziligi talab qilinmaydi
- **GDPR** 8-modda (EU, "bolaning roziligi") — xuddi shu asos

---

## 6. Xavfsizlik

- Barcha aloqa **HTTPS** orqali shifrlangan.
- Ma'lumotga kirish **Row Level Security** bilan chegaralangan: har foydalanuvchi
  faqat o'z ma'lumotini ko'radi.
- Tarif yozuvini foydalanuvchi **o'zgartira olmaydi** — faqat server yangilaydi.
- Ma'lumot buzilishi (data breach) yuz bersa, ta'sirlangan foydalanuvchilarga
  va zarur bo'lsa nazorat organiga xabar beramiz.

---

## 7. O'zgarishlar

Siyosat o'zgarsa, shu sahifadagi sana yangilanadi va muhim o'zgarish bo'lsa
ilovada xabar beriladi.

---

## 8. Aloqa

**jollyking.0130@gmail.com** · Telegram: **@sozakustika**
