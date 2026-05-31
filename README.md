# 💼 Job Board

Piattaforma full stack per la ricerca e pubblicazione di offerte di lavoro, con ruoli distinti per **Candidati** e **Aziende**. 
Progetto di gruppo sviluppato come esercitazione full stack con autenticazione, dashboard personalizzate e gestione delle candidature.

---

## Screen

<img width="1897" height="858" alt="loginpage" src="https://github.com/user-attachments/assets/e0d426fb-8a19-447b-b621-580f917e85c4" />
<img width="1897" height="865" alt="dashboardUtente2" src="https://github.com/user-attachments/assets/5e0c9b23-417b-477f-86f4-d4a470ea3d54" />
<img width="1895" height="862" alt="dashboardUtente3" src="https://github.com/user-attachments/assets/b97701a1-f01f-4a9a-ba3c-b2da975a04f2" />
<img width="1896" height="863" alt="dashboardUtente4" src="https://github.com/user-attachments/assets/2fbec7d6-c406-454b-aad5-3160750e2d23" />
<img width="1898" height="863" alt="homepageUtente1" src="https://github.com/user-attachments/assets/b6cfdeda-8ce2-489f-af4d-e4d29f1ec21b" />
<img width="1897" height="863" alt="homepageUtente2" src="https://github.com/user-attachments/assets/c030f063-4c0a-4107-a417-3494e3f29fe2" />
<img width="1897" height="863" alt="homepageUtente3" src="https://github.com/user-attachments/assets/7208800c-0ca2-4fd6-b116-440aa8c06690" />
<img width="1895" height="862" alt="homepageUtente4" src="https://github.com/user-attachments/assets/2cbd86c1-5fb1-4220-8a12-345e92c6fa43" />
<img width="1900" height="863" alt="dashboardAdienza1" src="https://github.com/user-attachments/assets/3eea7bd8-30dc-4596-b67c-d21b70e14e5b" />
<img width="1897" height="855" alt="dashboardAzienda2" src="https://github.com/user-attachments/assets/d983fb6e-8e56-44be-9a42-514de5eb2568" />
<img width="1897" height="865" alt="dashboardAzienda3" src="https://github.com/user-attachments/assets/38ed5cc3-9b99-4295-8741-94d441c19b1b" />







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
