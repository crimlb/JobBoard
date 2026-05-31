# 💼 Job Board

Piattaforma full stack per la ricerca e pubblicazione di offerte di lavoro, con ruoli distinti per **Candidati** e **Aziende**. 
Progetto di gruppo sviluppato come esercitazione full stack con autenticazione, dashboard personalizzate e gestione delle candidature.

---

## Screen

<img width="1897" height="858" alt="loginpage" src="https://github.com/user-attachments/assets/e0d426fb-8a19-447b-b621-580f917e85c4" />
<img width="1897" height="865" alt="dashboardUtente2" src="https://github.com/user-attachments/assets/5e0c9b23-417b-477f-86f4-d4a470ea3d54" />
<img width="1900" height="863" alt="dashboardAdienza1" src="https://github.com/user-attachments/assets/3eea7bd8-30dc-4596-b67c-d21b70e14e5b" />
<img width="1897" height="855" alt="dashboardAzienda2" src="https://github.com/user-attachments/assets/d983fb6e-8e56-44be-9a42-514de5eb2568" />

---

## ✨ Funzionalità

- Autenticazione con ruoli distinti (Candidato / Azienda)
- Pubblicazione e gestione offerte di lavoro
- Invio candidatura
- Dashboard personalizzata per ogni ruolo
- Ricerca e filtro offerte di lavoro
- Route protette in base al ruolo

---

## 🛠️ Tecnologie

**Frontend**
- React
- Bootstrap

**Backend**
- Node.js
- Express

**Database**
- PostgreSQL

**Autenticazione**
- JWT (JSON Web Token)

---

## 🚀 Installazione

```bash
# Clona il repository
git clone https://github.com/crimlb/JobBoard.git
cd JobBoard

# Installa le dipendenze del backend
cd backend
npm install

# Installa le dipendenze del frontend
cd ../frontend
npm install
```

### Variabili d'ambiente

Crea un file `.env` nella cartella `backend` con le seguenti variabili:

```env
PORT=3000
DB_HOST=localhost
DB_PORT=5432
DB_NAME=jobboard
DB_USER=tuo_utente
DB_PASSWORD=tua_password
JWT_SECRET=tua_chiave_segreta
```

### Avvio

```bash
# Backend
cd backend
npm start

# Frontend (in un altro terminale)
cd frontend
npm run dev
```

---

## 👥 Team

Progetto sviluppato in gruppo come esercitazione universitaria full stack.

---

## 👩‍💻 Autori
[Cristina Buffone] , GitHub: @crimlb

LinkedIn: linkedin.com/in/cristina-buffone-576893316/

Email: crimlb87@gmail.com

[Agostino Schiattarella] , GitHub: https://github.com/SchiAgo

[Mattia Formicola] , GitHub: https://github.com/ShioNoSparkly

[Israel Docarmo] , GitHub: https://github.com/rael83

## 📄 Licenza
Questo progetto è a scopo didattico e di portfolio. Non è consentito il riutilizzo del codice senza autorizzazione.
