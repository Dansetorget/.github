<img width="1920" height="949" alt="image" src="https://github.com/user-attachments/assets/0e3f25e0-787c-48c5-a1b1-27b78f7474b7" />

# Quizzlybear 🐻❓

**Quizzlybear** er en fullstack webapplikasjon utviklet i et team på 5 dataingeniørstudenter ved OsloMet. 

Applikasjonen gjør det enkelt for brukere å opprette, tilpasse og besvare interaktive quizer med poengberegning og poengtavler (leaderboards). Systemet er bygget med en oppdelt arkitektur for å sikre klar ansvarsfordeling mellom klient og server.

---

## 🏗️ Arkitektur & Repositorier

Kildekoden er organisert i to hovedkomponenter:

* **[Dansetorget/API](https://github.com/Dansetorget/API)**: Backend RESTful API skrevet i **ASP.NET Core (C#)** for håndtering av forretningslogikk, databasemodellering og autentisering.
* **[Dansetorget/Client](https://github.com/Dansetorget/Client)**: Responsiv og brukervennlig frontend utviklet i **React** og **TailwindCSS**.

---

## 🛠️ Teknologistakk

* **Backend:** C#, .NET / ASP.NET Core, Entity Framework Core, SQL
* **Frontend:** JavaScript / TypeScript, React, TailwindCSS
* **Verktøy & Metodikk:** Git, GitHub, REST API, Agile teamarbeid (5 personer)

---

## 🚀 Slik kjører du prosjektet lokalt

For å kjøre hele applikasjonen lokalt må du starte både backend-tjenesten og frontend-klienten.

### Forutsetninger
* [.NET 8 SDK](https://dotnet.microsoft.com/download) eller nyere
* [Node.js](https://nodejs.org/) (v18+) og `npm`

### 1. Kjøre Backend (API)
```bash
# Klone backend-repoet
git clone https://github.com/Dansetorget/API.git
cd API

# Gjenopprett avhengigheter og start API-et
dotnet restore
dotnet run
```

### 2. Kjøre frontent (Client)
```bash
# Klone frontend-repoet
git clone https://github.com/Dansetorget/Client.git
cd Client
```
For at clienten skal kunne snakke med API-et må filen `.env.development` opprettes og legge til:
```
VITE_PORT=3000 
VITE_API_URL=http://localhost:5110
```

Clienten kan nå startes med
```bash
npm install
npm run dev
```


© [2025] Dansetorget. Alle rettigheter reservert.
