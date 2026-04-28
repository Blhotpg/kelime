# 🗡️ Kelime Savaşı — Kurulum Rehberi

## Nasıl Oynanır?
- 2 oyuncu bir odada buluşur
- Sırayla harf eklerler (aklında Türkçe bir kelime olmalı!)
- Kelimeyi **tamamlamak zorunda kalan** oyuncu o turu kaybeder
- Rakibinin aklında kelime yoksa **İtiraz Et** butonuna bas

---

## 📦 Kurulum (Adım Adım)

### 1. Node.js kur
https://nodejs.org sitesinden LTS sürümü indir ve kur.

### 2. Dosyaları bir klasöre koy
```
kelime-savasi/
├── server.js
├── package.json
└── public/
    ├── index.html
    ├── style.css
    └── client.js
```

### 3. Terminali aç, klasöre git
```bash
cd kelime-savasi
```

### 4. Kütüphaneleri yükle
```bash
npm install
```

### 5. Sunucuyu başlat
```bash
npm start
```

### 6. Tarayıcıda aç
```
http://localhost:3000
```

---

## 🌐 İnternetten Oynamak İçin (Ücretsiz Yayın)

### Railway ile Deploy (En Kolay)

1. https://railway.app adresine git
2. GitHub hesabınla giriş yap
3. Projeyi GitHub'a yükle
4. Railway'de "New Project → Deploy from GitHub" seç
5. Railway sana bir URL verir — arkadaşınla bu URL'i paylaş!

### Render ile Deploy (Alternatif)
1. https://render.com adresine git
2. "New Web Service" oluştur
3. GitHub reponuzu bağla
4. Start Command: `npm start`
5. Ücretsiz tier ile çalışır!

---

## 🛠️ Geliştirme Modu (otomatik yenileme)
```bash
npm run dev
```

---

## 📝 Kelime Listesini Genişletmek
`server.js` içindeki `turkceKelimeler` dizisine kelimeler ekleyebilirsin.
Daha kapsamlı liste için: https://github.com/mertemin/turkish-word-list

---

## Sorun Çıkarsa
- Port 3000 meşgulse: `PORT=3001 npm start`
- `npm install` hatası: Node.js versiyonunu kontrol et (v16+)
