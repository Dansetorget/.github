# Eksamen check-list

- [x] Minst 2 typer entiteter i databasen (f.eks. quiz og question) og databaseoperasjoner (CRUD) må implementeres på minst én av dem. Entitet for autentisering teller ikke (f.eks. user)
- [x] Conditional rendering (rendrer komponenter bare når visse kriterier er oppfylt)
- [ ] Content filtering (filtrere eksisterende data på klienten)
- [x] Skjemaer (client-side)
- [ ] Input-validering (server og klient)
- [x] Feilhåndtering og logging (server og klient)
- [x] Repository pattern og DAL (server-side) - egne klasser som håndterer databaseoperasjoner
- [x] Asynchronous database access (server-side) - serveren håndterer andre forespørsler mens den venter på at databasen skal svare (async/await)
- [ ] API service layer (separat håndtering av HTTP forespørsler, ikke sammen med logikk på klientsiden)
- [x] Enhetstesting (server) - minst 8 tester, rettet mot én entitet/tabell (f.eks. Quiz). Testene skal dekke positiv og negativ flyt (velykket operasjon og feilhåndtering) for hver CRUD-operasjon
- [x] Autentisering (innlogging) og  Autorisasjon (tilgangsbegrensning) på server: API-et sjekker tokens/roller før det utfører handlinger.
- [x] Autentisering (innlogging) og autorisasjon på klient: Koble til endepunktene til backedn, skjule/viser komponenter og sider basert på innlogget bruker, f.eks. viser «Rediger» bare hvis bruker eier quizen.

Rapport: https://docs.google.com/document/d/13I-VXsyBAfF1ve-2WmJ13u_63t8FgOHZO00kx_e32mc/edit?usp=sharing


# 🌐 Dansetorget

Velkommen til **Dansetorget** — en samling av utviklere, designere og teknikere som samarbeider for å bygge åpne, moderne og pålitelige digitale løsninger.  
Vi tror på **åpen kildekode**, **kvalitet**, og **samarbeid**.

---

## 🚀 Vårt mål

Vi utvikler programvare som:

- Forenkler komplekse prosesser
- Bygger bro mellom teknologi og mennesker
- Følger prinsipper for bærekraftig og etisk utvikling

---

## 🧠 Teknologier vi bruker

- **Backend:** Node.js, Python, Go
- **Frontend:** React, TypeScript, Next.js
- **DevOps:** Docker, GitHub Actions, Kubernetes
- **Data:** PostgreSQL, Redis, MongoDB

---

## 🛡️ Retningslinjer og etikk

- Vi følger en streng [Code of Conduct](./CODE_OF_CONDUCT.md).
- All kode skal være dokumentert og testet.
- Vi respekterer hverandre og verdsetter mangfold.

---

© [2025] Dansetorget. Alle rettigheter reservert.
