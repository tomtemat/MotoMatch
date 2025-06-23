# MCMatch 🏍️

En app för att hitta MC-kompisar och handledare. Tänk Tinder – fast för hojåkare.

---

## 📱 Funktioner
- Skapa profil: MC-typ, körstil, erfarenhet, intressen
- Matcha med likasinnade inom en vald radie
- Filtrera på t.ex. "handledare", erfarenhet, MC-typ
- Inbyggd chatt efter match
- Swipe-funktion likt Tinder

---

## 🧱 Teknikstack (förslag)
**Frontend:** React Native (Expo)  
**Backend:** Node.js + Express  
**Databas:** Firebase eller PostgreSQL  
**Autentisering:** Firebase Auth (eller BankID)  
**Geolocation:** Google Maps API

---

## 🗂️ Struktur (förslag)
```
/mcmatch-app
├── frontend/         # React Native-app
│   └── screens/
│   └── components/
│   └── App.js
│
├── backend/          # Node.js + Express backend
│   └── routes/
│   └── controllers/
│   └── server.js
│
├── database/         # SQL eller Firestore struktur
├── README.md
└── .gitignore
```

---

## 🚀 Kom igång i Replit (utan terminal)
1. Gå till [https://replit.com](https://replit.com)
2. Välj "Import from GitHub" och klistra in repo-länken
3. Välj Node.js som projekt om du börjar med backend
4. Klicka på "Run"

Vill du köra frontend direkt också? Då kan vi sätta upp Expo-web via Replit eller StackBlitz.

---

## 🧠 AI-assistent
All kod skrivs med hjälp av Claude och ChatGPT – du behöver inte kunna programmera.

Fråga om du vill att AI:n sätter upp första filer automatiskt!
