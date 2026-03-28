# Aegis.AI — Complete Presentation: Script + Step-by-Step Guide (Merged)
> **FM** = Farhana Minhas | **AAK** = Ahmed Abdullah Khan | **MH** = Muhammad Haris
> **Zabaan:** Roman Urdu maa English technical terms | **Duration:** ~30 min total

---

## 🎬 Recording Se Pehle Checklist
- [ ] Services chal rahe hon: backend `:3000`, frontend `:5173`, EvalServer `:8000`
- [ ] Browser par `http://localhost:5173/register` khula ho (registration page nazar aaye)
- [ ] Database **fresh/empty** ho (ya previous demo data delete ho chuki ho)
- [ ] VS Code par `d:\aegis-develop` khula ho (Explorer sidebar open)
- [ ] `Final Aegis-develop.docx` VS Code mein khula ho
- [ ] Figma link ready: `figma.com/design/35gFjjYXV4dOuEBV08LCg6/Aegis.AI`
- [ ] Zoom Focus Assist ON — Display names: Full Name + Roll Number
- [ ] GitHub repo tab khula ho: `github.com/muhammadharis356/aegis-develop`
- [ ] PowerPoint Slide 1 par ready ho

---

## ⏱ Speaker Time Table (30 Min)

| Part | Section | Speaker | Waqt |
|------|---------|---------|------|
| 1 | Taaruf + Problem + Objectives | MH | 5 min |
| 2 | Domain Analysis + Architecture | AAK | 5 min |
| 3 | Backlog, Scrum, aur Figma | FM | 3 min |
| 4 | VS Code Walkthrough | AAK | 3 min |
| 5 | Live Demo (Registration + all modules) | MH | 8 min |
| 6 | Algorithms + Data Dictionary | MH | 4 min |
| 7 | Sprints + Results + Conclusion | FM+AAK | 3 min |
| **Total** | | | **~30 min** |

---
---

# ═══════════════════════════════════════════════════
# PART 1 — Taaruf, Masla, aur Maqasid
# Speaker: Muhammad Haris (MH) | ⏱ ~5 min
# ═══════════════════════════════════════════════════

---

## Step 1.1 — Introduction (~45 sec)

### 🖥️ Screen Action
- Make sure **PowerPoint Slide 1 (Title Slide)** is displayed

### 🎤 Script — MH says:

> "Assalam-o-Alaikum. Hamara project ka naam hai Aegis.AI — yeh ek AI Governance Platform hai."

> "Mera naam hai Muhammad Haris, meri student ID hai F2022376040. Mere saath hain Ahmed Abdullah Khan, ID F2022376096, aur Farhana Minhas, ID F2022376126."

> "Hum Department of Artificial Intelligence and Data Science, UMT Lahore se hain. Hamara supervisor hai Sir Usama Ahmad."

> "Phase 1 ki development November 2025 mein shuru hui, aur nau sprints mein March 2026 tak mukammal hui."

### 👆 While saying this:
1. Stay on title slide
2. Speak calmly — this is the first impression

---

## Step 1.2 — Agenda (~15 sec)

### 🖥️ Screen Action
- Advance to **Slide 2 (Agenda)**

### 🎤 MH says:

> "Aaj hum yeh cover karein ge — Problem, Architecture, Backlog, VS Code walkthrough, live demo, algorithms, sprint highlights, aur results."

> "Toh shuru karte hain."

### 👆 While saying this:
- Point to each agenda item on the slide as you name them

---

## Step 1.3 — The Problem (~1 min 30 sec)

### 🖥️ Screen Action
- Advance to **Slide 3 (The Problem)**

### 🎤 MH says:

> "Problem yeh hai ke AI systems tezi se phail rahe hain — lekin governance abhi tak peeche hai."

> "EU (European Union) AI Act 2024 mein enforceable ho chuka hai. Is ke mutabiq high-risk AI ke liye risk assessments, documentation, aur human oversight laazmi hain. ISO (International Organization for Standardization) 42001, ISO 27001, aur NIST (National Institute of Standards and Technology) AI RMF (Risk Management Framework) mazeed compliance layers add karte hain."

> "Ek real-world example dekhein — hospital mein ek AI cancer diagnosis system galat nataij de raha hai. Koi audit trail nahin, koi governance nahin — patient ki jaan daao par, aur regulatory violation bhi."

### 👆 While saying this:
1. Point to the problem statement on the slide
2. Pause briefly after the hospital example — let it sink in

### 🎤 MH continues:

> "Humne paanch major problems identify ki hain:"

> "**Pehli** — Regulatory complexity. Chaar compliance frameworks ko ek saath spreadsheets se manage karna na-mumkin hai."

> "**Doosri** — Centralized oversight ki kami. Models, risks, vendors — sab alag alag disconnected tools mein hain."

> "**Teesri** — Koi self-hostable alternative nahin. Credo AI, IBM OpenScale, OneTrust — sab cloud-only SaaS (Software as a Service) hain. Government bodies legally apna governance data bahar nahin bhej saktin."

> "**Chauthi** — Manual audits jo error-prone hain."

> "**Paanchvi** — Built-in AI safety evaluation tools ka na hona."

### 👆 While saying this:
- Count on fingers or point to numbered points if visible on slide

---

## Step 1.4 — Objectives / Our Solution (~1 min 30 sec)

### 🖥️ Screen Action
- Advance to **Slide 4 (Objectives)**

### 🎤 MH says:

> "Hamara hal hai Aegis.AI — ek comprehensive, self-hostable platform jo das maqasid deliver karta hai:"

> "**Ek** — Chaaron compliance frameworks ek hi interface se manage karein — EU AI Act, ISO 42001, ISO 27001, aur NIST AI RMF."

> "**Do** — AI Model Inventory maa risk assessment."

> "**Teen** — Vendor Management."

> "**Chaar** — Policy Manager."

> "**Paanch** — AI Advisor — yeh ek LLM (Large Language Model)-powered chatbot hai."

> "**Chhay** — LLM Evaluations aur Arena, DeepEval framework ke zariye."

> "**Saat** — AI Detection Module — GitHub scanning ke saath."

> "**Aath** — Schema-per-tenant multi-tenancy."

> "**Nau** — Docker aur Kubernetes deployment."

> "**Dus** — PDF (Portable Document Format) aur DOCX report generation."

> "Yeh das maqasid hamari 20 EPICs aur 58 user stories se directly map hote hain."

### 👆 While saying this:
1. Count each objective — hold up fingers or point to slide
2. Pause slightly after "das maqasid" to let the number register

---

## ✅ Part 1 Handoff

**MH says:**
> *"Ahmed, domain analysis aur architecture explain karo."*

### Checklist before moving on:
- [ ] Title slide shown — names, IDs, department, supervisor introduced
- [ ] Agenda slide shown
- [ ] Problem explained — EU AI Act, ISO, NIST mentioned, hospital example given
- [ ] 5 problems clearly listed
- [ ] 10 objectives clearly listed
- [ ] Connection to 20 EPICs and 58 user stories mentioned

---
---

# ═══════════════════════════════════════════════════
# PART 2 — Domain Analysis aur Architecture
# Speaker: Ahmed Abdullah Khan (AAK) | ⏱ ~5 min
# ═══════════════════════════════════════════════════

---

## Step 2.1 — Customers & Stakeholders (~45 sec)

### 🖥️ Screen Action
- Advance to **Slide 5 (Customers & Stakeholders)**

### 🎤 Script — AAK says:

> "Shukriya Haris. Main Ahmed Abdullah Khan hoon."

> "Aegis.AI chaar customer segments ko target karta hai. Pehla — tech companies jo AI products build kar rahi hain. Doosra — regulated industries jaise banking, healthcare, aur public sector. Teesra — government bodies. Aur chautha — sectoral industries jahan AI oversight laazmi hai."

> "Hamare system mein das actor types hain — Admin, Editor jo AI Governance Officer bhi hai, Reviewer, Auditor, End Users, External Vendors, Regulatory Bodies, LLM Providers, IT/DevOps, aur System background workers."

### 👆 While saying this:
1. Point to each customer segment on the slide
2. Point to actor types list if visible

---

## Step 2.2 — Competitor Comparison (~30 sec)

### 🖥️ Screen Action
- Advance to **Slide 6 (Feature Comparison)**

### 🎤 AAK says:

> "Hamare competitors hain — IBM OpenScale, Credo AI, Holistic AI, aur OneTrust. Yeh sab cloud-only SaaS hain, aur inmein partial framework support hai."

> "Aegis.AI wahid platform hai jo complete EU AI Act, ISO 42001, ISO 27001, aur NIST AI RMF — chaaron frameworks deliver karta hai. Yeh fully self-hosted hai, LLM Evaluation aur AI Detection shamil hain — aur yeh bilkul muft hai."

### 👆 While saying this:
1. Point to the comparison table/chart on the slide
2. Emphasize "wahid platform" and "bilkul muft"

---

## Step 2.3 — Architecture (~2 min)

### 🖥️ Screen Action
- **Alt+Tab** → Switch to `Final Aegis-develop.docx` → Navigate to **Section 5.1–5.4** (C4 Diagrams + Clean Architecture)

### 🎤 AAK says:

> "Ab architecture ki baat karte hain. Hamari application teen independently deployable services par mushtamil hai."

> "Pehla hai React SPA (Single Page Application) — yeh port 5173 par chalta hai, Vite ke saath. Doosra hai Node.js TypeScript backend — port 3000 par, jismein 60 se zyada active route modules hain, aur JWT (JSON Web Token) plus RBAC (Role-Based Access Control) middleware hai."

> "Teesra hai PostgreSQL database — port 5432 par, jismein schema-per-tenant isolation hai. Aur Redis port 6379 par hai — BullMQ (Bull Message Queue) job queues aur SSE (Server-Sent Events) Pub/Sub (Publish/Subscribe) ke liye."

### 👆 While saying this:
1. Point to C4 diagrams in the document
2. Point to each service as you name it

### 🎤 AAK continues:

> "Hamari Clean Architecture chaar layers mein divide hai:"

> "**Presentation Layer** — 60 route files. **Application Layer** — Controllers, SSE Service, PMM Scheduler, PDF Generator. **Domain Layer** — Sequelize ORM (Object-Relational Mapping) models aur business rules, jaise risk scoring formula L guna 1 plus S guna 3. **Infrastructure Layer** — PostgreSQL, Redis, LLM APIs (Application Programming Interfaces), aur email services."

> "Important baat yeh hai ke dependencies sirf inward point karti hain. Is ka matlab hai ke — agar kal PostgreSQL ki jagah koi aur database lagana ho, toh business logic ko touch nahin karna parega."

### 👆 While saying this:
1. Point to Clean Architecture diagram layers
2. Emphasize "dependencies sirf inward" — this is a strong architectural selling point

---

## Step 2.4 — ERD & Multi-Tenancy (~1 min)

### 🖥️ Screen Action
- Scroll to **Section 5.4 ERD** in the document

### 🎤 AAK says:

> "ERD (Entity Relationship Diagram) mein 15 major table groups hain. Hierarchy aise hai — Organizations se Users, Users se Projects, Projects se ProjectRisks — aur saath mein RiskHistory aur audit tables hain."

> "Projects ke saath aur bhi linked hain — VendorRisks, ModelInventories, ApprovalRequests, Tasks, Incidents, aur PMM (Post-Market Monitoring) configurations."

### 👆 While saying this:
1. Point to the ERD diagram
2. Trace the hierarchy: Organizations → Users → Projects → linked tables

### 🎤 AAK continues:

> "Multi-tenancy ka system aise kaam karta hai — jab koi organization register hoti hai, toh system us ke liye ek dedicated database schema banata hai. Is schema ka naam ek 10-character cryptographically random hash hota hai."

> "Yeh isolation database engine level par enforce hota hai. Humne 15 cross-tenant access tests kiye — aur tamam 15 correctly block hue. Koi bhi organization doosri organization ka data access nahin kar sakti."

### 👆 While saying this:
1. Point to multi-tenancy diagram if visible
2. Emphasize "15 tests — tamam 15 blocked" — this is a strong security proof

---

## ✅ Part 2 Handoff

**AAK says:**
> *"Farhana, backlog aur Figma designs dikha do."*

### Checklist before moving on:
- [ ] 4 customer segments named
- [ ] 10 actor types listed
- [ ] Competitor comparison shown — "wahid platform" emphasized
- [ ] 3 services explained (React, Node.js, PostgreSQL + Redis)
- [ ] Clean Architecture 4 layers explained
- [ ] ERD hierarchy shown — 15 table groups
- [ ] Multi-tenancy explained — schema-per-tenant, 15 tests blocked

---
---

# ═══════════════════════════════════════════════════
# PART 3 — Product Backlog, Scrum, aur Figma
# Speaker: Farhana Minhas (FM) | ⏱ ~3 min
# ═══════════════════════════════════════════════════

---

## Step 3.1 — Backlog Summary (~45 sec)

### 🖥️ Screen Action
- **Alt+Tab** → **PowerPoint** → navigate to **Slide 9 (Backlog Summary)**
- Make sure the slide showing EPICs & user story count is fully visible

### 🎤 Script — FM says:

> "Shukriya Ahmed. Main Farhana Minhas hoon, meri student ID hai F2022376126."

> "Hamara poora backlog 20 EPICs aur 58 user stories par mushtamil hai. Har user story ek standard format mein likhi gayi hai — 'As a role, I can do something, so that benefit.' Har story ke saath Priority, Acceptance Criteria, Story Points, aur Status defined hain."

### 👆 While saying this:
1. **Point to** the 20 EPICs count on the slide
2. **Point to** the user story format example if shown

### 🎤 Continue:

> "Phase 1 ke key EPICs yeh hain: User Management, Multi-Tenancy, Approval Workflows, chaaron compliance Frameworks, Risk Management, Vendor Management, Policy Manager, Model Inventory, Incident Management, PMM (Post-Market Monitoring), aur WatchTower."

### 👆 While saying this:
- **Run your cursor** down the list of EPICs on the slide as you name them

### 🎤 Continue:

> "Kuch EPICs Phase 2 ke liye defer ki gayi hain — jaise LLM (Large Language Model) Evaluations, AI Advisor ki live connections, aur AI Detection Module. In sab ki UIs ban chuki hain — agar backend connect na ho, toh yeh features gracefully degrade karte hain."

---

## Step 3.2 — Sprint Timeline (~30 sec)

### 🖥️ Screen Action
- Advance to **Slide 10 (Sprint Timeline)**

### 🎤 Script — FM says:

> "Hamari development nau sprints mein hui — har sprint do hafte ka tha. Yeh November 15 se shuru hua aur March 20 tak mukammal hua."

> "Scrum Master ka role har sprint mein rotate hota raha. Hamne poori Scrum ceremonies follow ki — Planning, Daily Standups, Sprint Review jahan Sir Usama Ahmad Product Owner ke taur par shamil hote the, aur Retrospective."

> "Phase 1 mein kull 43 user stories complete hui — 230 story points ke saath — aur tamam stories live browser par user acceptance testing se verify ki gayi hain."

### 👆 While saying this:
1. **Point to** the Sprint 1 → Sprint 9 (nine sprints) timeline on the slide
2. **Emphasize** "43 user stories — 230 story points" — pause for half a beat to let the number land

---

## Step 3.3 — Individual Contributions (~30 sec)

### 🖥️ Screen Action
- Stay on same slide (or advance to contributions slide if one exists)

### 🎤 Script — FM says:

> "Individual contributions ki baat karein toh — Muhammad Haris ne authentication system, approval workflows engine, risk scoring algorithm, PDF (Portable Document Format) report generation, aur global search implement kiya."

> "Ahmed Abdullah Khan ne Docker aur Kubernetes setup, RBAC (Role-Based Access Control) system, chaaron frameworks ki seedings, aur SSE (Server-Sent Events) notification system banaya."

> "Aur maine poora React frontend design aur develop kiya — 50 se zyada pages — aur Figma par tamam 20 prototype designs banaye."

### 👆 While saying this:
- Read this as a **rapid-fire list** — don't pause between names

---

## Step 3.4 — Figma Designs (~45 sec)

### 🖥️ Screen Action
- **Option A** (preferred): Open **Figma** in browser → `figma.com/design/35gFjjYXV4dOuEBV08LCg6/Aegis.AI`
- **Option B** (backup): Open `Final Aegis-develop.docx` → **Section 3.4** screenshots

### 🎤 Script — FM says:

> "Ab main Figma designs dikhati hoon. Hamara design system dark navy theme par based hai, teal accent colors ke saath, aur Inter font family use ki gayi hai."

> "Yahan aap dekh sakte hain — Login page, Dashboard, Risk Management registry, Policy Manager lifecycle, AI Trust Center, LLM Evaluations, WatchTower, aur Approval Workflows."

> "Tamam 20 screens development se pehle design ki gayi thi — taake yeh implementation ke liye guide ka kaam karein."

### 👆 While saying this:
1. **Scroll slowly** through Figma screens, pausing ~2 seconds on each major screen:
   - Login Page → Dashboard → Risk Management → Policy Manager → AI Trust Center → LLM Evaluations → WatchTower → Approval Workflows
2. Let viewers **see the dark navy + teal aesthetic** on each screen

---

## ✅ Part 3 Handoff

**FM says:**
> *"Ahmed, ab VS Code walkthrough dikha do."*

### Checklist before moving on:
- [ ] Backlog summary shown — 20 EPICs, 58 stories mentioned
- [ ] Sprint timeline shown — nine sprints, 43 stories, 230 story points
- [ ] Individual contributions mentioned
- [ ] Figma screens scrolled through (at least 5–6 visible)

---
---

# ═══════════════════════════════════════════════════
# PART 4 — VS Code: Codebase Walkthrough
# Speaker: Ahmed Abdullah Khan (AAK) | ⏱ ~3 min
# ═══════════════════════════════════════════════════

---

## Step 4.1 — Root Folder Structure (~30 sec)

### 🖥️ Screen Action
- **Alt+Tab** → switch to **VS Code** — must be open at `d:\aegis-develop`
- Press **Ctrl+Shift+E** to make sure **Explorer sidebar** is visible
- Click on root `d:\aegis-develop` to expand

### 🎤 Script — AAK says:

> "Ab hum VS Code mein aate hain. Root folder mein teen main applications hain."

> "Pehla hai `Clients` — yeh hamara React TypeScript frontend hai. Doosra hai `Servers` — yeh Node.js TypeScript backend hai. Aur teesra hai `EvalServer` — yeh Python FastAPI evaluation server hai."

> "In ke ilawa `kubernetes` folder hai — jismein Kubernetes deployment ke manifests hain, `docker-compose.yml` hai, aur `Final-Documentation` hai."

### 👆 While saying this:
1. **Point/hover cursor** on `Clients/` when saying "React TypeScript"
2. **Point/hover cursor** on `Servers/` when saying "Node.js TypeScript"
3. **Point/hover cursor** on `EvalServer/` when saying "Python FastAPI"
4. **Point/hover cursor** on `kubernetes/` and `docker-compose.yml` when naming them
5. Don't open any files yet — just show the tree

---

## Step 4.2 — Routes Folder: 67 Route Files (~45 sec)

### 🖥️ Screen Action
- In Explorer: **Expand** `Servers/` → **Expand** `routes/`
- **Scroll slowly** through all 67 files — let the volume register visually

### 🎤 Script — AAK says:

> "Servers folder hamari Clean Architecture ki layers reflect karta hai. Sab se pehle dekhte hain `routes` folder — yahan 60 se zyada route files hain. Har feature ki apni alag route file hai."

### 👆 While saying this:
- Scroll slowly and **call out key route files** as they appear:

| As file scrolls into view | Say |
|---|---|
| `eu.route.ts` | *"EU AI Act ke liye"* |
| `iso42001.route.ts` | *"ISO 42001 ke liye"* |
| `iso27001.route.ts` | *"ISO 27001 ke liye"* |
| `nist_ai_rmf.route.ts` | *"NIST AI RMF ke liye"* |
| `risks.route.ts` | *"Risk Management"* |
| `vendor.route.ts` | *"Vendor Management"* |
| `policy.route.ts` | *"Policy Manager"* |
| `modelInventory.route.ts` | *"Model Inventory"* |
| `approvalWorkflow.route.ts` | *"Approval Workflows"* |
| `automation.route.ts` | *"Automations"* |
| `aiDetection.route.ts` | *"AI Detection"* |
| `search.route.ts` | *"Global Search — Command Palette Ctrl+K"* |
| `advisor.route.ts` | *"AI Advisor — aur bahut saari aur bhi"* |

### 🎤 AAK continues:

> "Total 67 route files hain — har feature ka apna dedicated module hai. Yeh hamari Clean Architecture ki Presentation Layer hai."

> 💡 **This is the most impressive visual moment** — the sheer volume of files. Scroll slowly.

---

## Step 4.3 — Middleware: 3-Layer Security Chain (~45 sec)

### 🖥️ Screen Action
- **Collapse** `routes/`
- **Expand** `middleware/`
- Open these **three files one by one** (click each):

### File 1: Open `auth.middleware.ts`

### 🎤 AAK says:

> "Ab middleware folder dekhte hain. Yahan teen important security files hain. Pehli file hai `auth.middleware` — yeh har incoming request par JWT (JSON Web Token) verify karti hai. Agar token valid nahin, toh request yahan ruk jaati hai."

### 👆 While saying this:
1. Click `auth.middleware.ts` to open in editor
2. **Point to** where JWT token is extracted from `Authorization` header
3. **Point to** `jwt.verify()` call

### File 2: Open `multiTenancy.middleware.ts`

### 🎤 AAK continues:

> "Doosri file hai `multiTenancy.middleware` — yeh PostgreSQL mein `SET search_path` command chalati hai. Is se tamam database queries sirf us organization ki private schema tak scope ho jaati hain. Koi doosri organization ka data access nahin ho sakta."

### 👆 While saying this:
1. Click `multiTenancy.middleware.ts` to open
2. **Point to** the `SET search_path TO` SQL command — this is the key line

### File 3: Open `accessControl.middleware.ts`

### 🎤 AAK continues:

> "Aur teesri file hai `accessControl.middleware` — yeh RBAC check karti hai. Agar user ke paas required permission nahin hai, toh fauran 403 Forbidden return hota hai."

> "Yeh teen-layer security chain har ek request par chalti hai — pehle JWT, phir tenant scope, phir RBAC."

### 👆 While saying this:
1. Click `accessControl.middleware.ts` to open
2. **Point to** the role check logic and the **403 return**
3. **Emphasize** "teen-layer" — hold up 3 fingers if on camera

---

## Step 4.4 — Docker Compose + Kubernetes (~30 sec)

### 🖥️ Screen Action (Docker)
- **Collapse** `Servers/`
- Click **`docker-compose.yml`** at root to open it in editor

### 🎤 AAK says:

> "Ab Docker Compose dekhte hain. Is ek file mein chhay services defined hain — sab ke saath health checks. PostgreSQL, Redis, Node.js backend, React Nginx frontend, BullMQ (Bull Message Queue) worker, aur Python EvalServer."

> "Ek single command — `docker-compose up -d` — aur poori platform start ho jaati hai."

### 👆 While saying this:
1. **Scroll through** `docker-compose.yml` — point to each service block:
   - `postgresdb:` → health check visible
   - `redis:` → health check visible
   - `backend:` → depends_on postgres + redis
   - `frontend:`
   - `worker:` → BullMQ background jobs
   - `eval_server:`

### 🖥️ Screen Action (Kubernetes)
- In Explorer: **Expand** `kubernetes/.k8s/` — just show the file list

### 🎤 AAK continues:

> "Aur yeh hai hamara Kubernetes folder. Yahan aath deployment manifests hain — backend, frontend, EvalServer, BullMQ worker, PostgreSQL StatefulSet, Redis, Nginx Ingress maa SSL (Secure Sockets Layer) termination, aur Horizontal Pod Autoscaler."

> "Is ka matlab hai ke Aegis.AI ko AWS EKS (Elastic Kubernetes Service), Azure AKS (Azure Kubernetes Service), ya kisi bhi self-hosted Kubernetes cluster par horizontally scale kiya ja sakta hai."

### 👆 While saying this:
1. **Point to files** in `.k8s/` as you name them:
   - `backend-deployment.yaml`
   - `frontend-deployment.yaml`
   - `eval-server-deployment.yaml`
   - `worker-deployment.yaml`
   - `postgres-deployment.yaml`
   - `redis-deployment.yaml`
   - `ingress-tls.yaml` → "SSL termination"
2. Don't open any k8s files — just point in the Explorer tree

---

## ✅ Part 4 Handoff

**AAK says:**
> *"Haris, ab live application dikhao."*

### Checklist before moving on:
- [ ] Root folder shown (Clients, Servers, EvalServer, kubernetes, docker-compose)
- [ ] `routes/` expanded — 67 files scrolled through, key routes named
- [ ] `middleware/` — 3 security files opened (auth, multiTenancy, accessControl)
- [ ] `docker-compose.yml` opened — services pointed out
- [ ] `kubernetes/.k8s/` folder shown — manifest names visible

> **If running late:** Skip opening individual middleware files — just point to their names in Explorer and explain verbally.

---
---

# ═══════════════════════════════════════════════════
# PART 5 — Live Demo: Running Application
# Speaker: Muhammad Haris (MH) | ⏱ ~8 min
# ═══════════════════════════════════════════════════

> ⚠️ **IMPORTANT:** Before starting this part, make sure the database is **fresh/empty**. The demo starts from registration.

---

## Step 5.1 — Registration Flow (~1 min)

### 🖥️ Screen Action
- **Alt+Tab** → switch to **Browser**
- Navigate to `http://localhost:5173/register`

### 🎤 Script — MH says:

> "Ab hum live application dekhte hain. Sab se pehle hum fresh registration karein ge — taake aap dekh sakein ke multi-tenant onboarding kaise kaam karta hai."

> "Yeh hamara registration page hai. Yahan Admin apna Name, Surname, Email, aur Password fill karta hai."

### 📝 Demo Data — Type these exact values:

| Field | Value to Type |
|-------|---------------|
| **Name** | `Haris` |
| **Surname** | `Ahmed` |
| **Email** | `haris@aegisai.com` |
| **Password** | `Aegis@2026` |
| **Confirm Password** | `Aegis@2026` |

### 👆 While saying this:
1. Type each field **slowly** so viewers can see the values
2. **Point to** the live password validation checklist as it turns green:
   - ✅ Must be at least 8 characters
   - ✅ Must contain one special character
   - ✅ Must contain at least one uppercase letter
   - ✅ Must contain at least one number
3. Say: *"Notice karo — real-time password validation chal raha hai."*

### 🖥️ Screen Action
- Click **"Get started"** button → wait for processing toast → auto-redirect to Dashboard

### 🎤 MH continues:

> "Registration hote hi system ne background mein teen cheezein ki — ek naya organization bana, us ke liye ek dedicated PostgreSQL schema bana 10-character random hash ke saath, aur Admin user us schema mein register hua. Ab hum directly Dashboard par hain."

---

## Step 5.2 — Onboarding + Generate Demo Data (~30 sec)

### 🖥️ Screen Action
- After registration, the **Onboarding Setup Modal** appears automatically → click **Skip** or complete it

### 🎤 MH says:

> "Pehli baar login par yeh onboarding modal aata hai — platform ki key features guide karta hai."

### 🖥️ Screen Action
- In the sidebar, click **"Create Demo Data"** button
- Confirm in the modal → wait for toast notification

### 🎤 MH continues:

> "Platform mein built-in demo data generator hai. Ek click mein yeh ek sample use case banata hai — 'AI Recruitment Screening Platform' — EU AI Act framework, sample risks, aur vendors ke saath. Taake fauran explore kar sakein."

### 👆 While saying this:
1. Show the **demo data modal** — point to "What will be created"
2. Click **"Create demo data"** → wait for reload

---

## Step 5.3 — Dashboard Overview (~30 sec)

### 🖥️ Screen Action
- Dashboard is now populated with demo data

### 🎤 MH says:

> "Yeh hamara Dashboard hai. Total use cases, risk score distribution chart, har compliance framework ka progress, vendor count, aur recent activity feed — sab nazar aa raha hai."

> "Yeh sab data sirf isi organization ke PostgreSQL schema se aa raha hai — doosri organizations ka data yahan bilkul nazar nahin aayega."

### 👆 While saying this:
1. **Point to** each card/chart: Use Cases → Risk Distribution → Compliance Progress → Vendors → Activity
2. **Emphasize** tenant isolation

---

## Step 5.4 — Use Cases + EU AI Act Controls (~1 min)

### 🖥️ Screen Action
- Click **Overview** in the left sidebar

### 🎤 MH says:

> "Yeh Overview page hai. 'AI Recruitment Screening Platform' — High Risk categorized hai. Har use case ko auto-generated UC-ID milta hai."

### 🖥️ Screen Action
- **Click the Use Case** → click the **EU AI Act** tab

### 🎤 MH continues:

> "EU AI Act ke 13 control categories hain — Data Governance, Technical Documentation, Human Oversight, Accuracy, Cybersecurity, Conformity Assessment, waghaira."

### 🖥️ Screen Action
- **Click one category** → expand → **click a control** → **change its status live**

### 🎤 MH continues:

> "Har control Waiting se In Progress, Under Review, Done ya N/A mein move karta hai. Status change hone par timestamp aur user automatically log hota hai."

### 👆 While saying this:
1. **Change status** of a control from **Waiting** → **In Progress** live — impressive visual moment

---

## Step 5.5 — Risk Management (~45 sec)

### 🖥️ Screen Action
- Click **Risk Management** in sidebar

### 🎤 MH says:

> "Risk Registry mein sample risks hain. Har risk mein Likelihood 1 se 5, aur Severity 1 se 5 define hoti hai."

### 👆 While saying this:
1. **Point to** table columns: Name, Owner, Likelihood, Severity, Risk Level
2. **Click any risk** to open detail view

### 🎤 MH continues:

> "Risk Score formula — Likelihood guna 1, plus Severity guna 3. Main Severity change karta hoon — dekhein badge fauran update hoga."

### 👆 While saying this:
1. *(Live demo)* — **Change Severity** → watch Risk Level badge update automatically
2. Pause to let it register

### 🖥️ Screen Action
- Click **View History** button

### 🎤 MH continues:

> "View History mein purani value, nayi value, timestamp, aur kisne change kiya — complete audit trail."

---

## Step 5.6 — Approval Workflows (~30 sec)

### 🖥️ Screen Action
- Click **Approval Workflows** in sidebar

### 🎤 MH says:

> "Approval Workflows — Editor submit for review karta hai, Admin ke multi-step template ke mutabiq workflow chalta hai. Maximum 5 steps."

> "Bell icon 🔔 par real-time SSE notification aati hai — 100 milliseconds se kam mein. Approve, reject with comment, ya withdraw — sab possible."

### 👆 While saying this:
1. Show **template list** + **bell icon** + **Approve/Reject** buttons

---

## Step 5.7 — Policy Manager (~20 sec)

### 🖥️ Screen Action
- Click **Policies** in sidebar

### 🎤 MH says:

> "Policy Manager — lifecycle Draft se Archived tak. Har policy compliance controls se linked hai — full traceability."

### 👆 While saying this:
1. Show list + **status badges**
2. Click one policy → **Linked Objects**

---

## Step 5.8 — Vendors + Model Inventory (~30 sec)

### 🖥️ Screen Action
- Click **Vendors** in sidebar

### 🎤 MH says:

> "Vendors module — AI vendors ke saath Vendor Risks bhi manage hote hain — same auto-calculation formula."

### 👆 While saying this:
1. Show vendor list → click **Risks tab**

### 🖥️ Screen Action
- Click **Model Inventory** in sidebar

### 🎤 MH continues:

> "Model Inventory — AI models registered, risk classification, owner, Model Risks tab ke saath."

### 👆 While saying this:
1. Show models → click **Model Risks** tab

---

## Step 5.9 — PMM + Automations (~30 sec)

### 🖥️ Screen Action
- Navigate to **Post-Market Monitoring** (via Framework sidebar)

### 🎤 MH says:

> "Post-Market Monitoring — EU AI Act Articles 9 aur 72 ke aligned. Frequency, reminder days, escalation days set hote hain — aur cycle submit par Playwright se automatic PDF report banta hai."

### 👆 While saying this:
1. Show PMM config — frequency/reminder/escalation fields

### 🖥️ Screen Action
- Click **Automations** in sidebar

### 🎤 MH continues:

> "Automation Engine — no-code rules. Trigger jaise RISK_CREATED, condition jaise Very High, actions — SEND_SLACK, SEND_EMAIL, CREATE_TASK, CALL_WEBHOOK."

### 👆 While saying this:
1. Click any rule — show Trigger → Condition → Actions

---

## Step 5.10 — Incident Management + Tasks (~15 sec)

### 🖥️ Screen Action
- Click **Incident Management** in sidebar

### 🎤 MH says:

> "Incident Management — AI-related incidents track hote hain — severity, status, resolution ke saath."

### 🖥️ Screen Action
- Click **Tasks** in sidebar

### 🎤 MH continues:

> "Tasks — manually ya Automation Engine se auto-created governance tasks."

---

## Step 5.11 — WatchTower + AI Trust Center (~30 sec)

### 🖥️ Screen Action
- Click **WatchTower** in sidebar

### 🎤 MH says:

> "WatchTower — audit log. Abhi tak jo bhi actions liye — registration, status change, risk edit — sab yahan recorded hai. Actor, action, entity, ISO 8601 timestamp."

### 👆 While saying this:
1. Show audit log — **scroll through and point out your own recent actions** (registration, status change, risk edit)

### 🖥️ Screen Action
- Click **AI Trust Center** in sidebar

### 🎤 MH continues:

> "AI Trust Center — public-facing transparency page. Unique hash URL se external stakeholders ko bina login ke read-only access milta hai."

---

## Step 5.12 — LLM Evaluations + AI Detection (UI-first) (~20 sec)

### 🖥️ Screen Action
- Click **LLM Evaluations** in sidebar

### 🎤 MH says:

> "LLM Evaluations — Correctness, Faithfulness, Hallucination Rate, Bias metrics. Arena mode mein do models side-by-side compare hote hain. Phase 2 mein live LLM connection se fully functional hoga."

### 🖥️ Screen Action
- Click **AI Detection** in sidebar

### 🎤 MH continues:

> "AI Detection — GitHub repos scan karke AI usage detect karta hai. Scan, History, Settings tabs. Phase 2 mein complete hoga — UI ready hai."

---

## Step 5.13 — Command Palette + Settings (~30 sec)

### 🖥️ Screen Action
- Press **Ctrl+K** to open **Command Palette**

### 🎤 MH says:

> "Command Palette — Ctrl+K — global search. 14 entity types mein search hota hai — Use Cases, Risks, Vendors, Policies, Models, Tasks, Incidents. Supervisor ne is feature ki khas tarif ki."

### 📝 Demo: Type `risk` → show instant results

### 👆 While saying this:
1. Type **"risk"** → show results with entity type badges
2. Press **Escape** to close

### 🖥️ Screen Action
- Click **Settings** in sidebar

### 🎤 MH continues:

> "Settings — LLM API keys OpenAI, Anthropic, OpenRouter. Email provider — SMTP, SES, Azure, Resend. Slack webhook. API tokens."

> "Sab se important — platform bagair kisi LLM key ke fully functional hai. AI features gracefully degrade karte hain."

### 👆 While saying this:
1. Show **LLM Keys** → **Email** → **Slack** → **API Tokens** tabs quickly

---

## ✅ Part 5 Handoff

**MH says:**
> *"Ab main algorithms explain karta hoon…"* (continues directly into Part 6)

### Checklist before moving on:
- [ ] Registration shown live — Organization + Admin created
- [ ] Onboarding modal → Demo data generated
- [ ] Dashboard — metrics, charts, compliance progress, activity
- [ ] Use Cases — UC-ID, risk classification, framework tabs
- [ ] EU AI Act — 13 categories, control status changed live
- [ ] Risk Management — auto-calculated badge changed live, View History
- [ ] Approval Workflows — templates, bell icon, approve/reject
- [ ] Policy Manager — lifecycle badges, linked objects
- [ ] Vendors + Vendor Risks
- [ ] Model Inventory + Model Risks
- [ ] PMM — frequency, reminders, escalation, PDF
- [ ] Automations — trigger/condition/action rules
- [ ] Incident Management — shown
- [ ] Tasks — shown
- [ ] WatchTower — audit log with own actions visible
- [ ] AI Trust Center — public page
- [ ] LLM Evaluations — dashboard + Arena
- [ ] AI Detection — scan interface
- [ ] Command Palette — Ctrl+K search
- [ ] Settings — LLM, email, slack, API tokens

> **If running late — what to cut:**
> - Skip Incident Management + Tasks (one verbal sentence)
> - Skip AI Trust Center (mention verbally)
> - Skip LLM Evals + AI Detection ("Phase 2 mein live, UI ready")
> - Skip Settings tabs — just show LLM Keys
> - Compress Vendors + Model Inventory to one sentence each

---

# ═══════════════════════════════════════════════════
# PART 6 — Algorithms + Data Dictionary
# Speaker: Muhammad Haris (MH) | ⏱ ~4 min
# ═══════════════════════════════════════════════════

---

## Step 6.0 — Transition

### 🖥️ Screen Action
- **Alt+Tab** → switch to **VS Code** (or Word) with `Final Aegis-develop.docx` open
- Navigate to **Section 6.3** in the document

### 🎤 MH says:

> "Ab hamare paanch core algorithms dekhte hain — yeh sab Section 6.3 mein documented hain."

---

## Step 6.1 — Algorithm 1: Risk Level Auto-Calculation (~45 sec)

### 🖥️ Screen Action
- Scroll to **Algorithm 1** in Section 6.3
- **Zoom in** or **highlight** the decision table (25 L×S combinations)

### 🎤 MH says:

> "**Pehla Algorithm hai Risk Level Auto-Calculation.**"

> "Formula simple hai — Risk Score barabar hota hai Likelihood guna 1, plus Severity guna 3. Severity ko teen guna weight di gayi hai kyun ke AI governance mein impact zyada critical hota hai."

> "Score ke mutabiq paanch levels hain — 4 ya kam ho toh Very Low, 5 se 8 tak Low, 9 se 12 tak Medium, 13 se 16 tak High, aur 17 ya zyada ho toh Very High."

> "Yeh same formula project risks, vendor risks, aur model risks — teeno par apply hota hai. Humne 25 different risk entries test ki — sab mein 100 percent correct result aaya."

### 👆 While saying this:
1. **Point to** the formula in the doc: `L×1 + S×3`
2. **Point to** the threshold table showing the 5 risk levels
3. **Point to** the Severity column — emphasize 3× weight visually
4. Reference back: *"abhi aap ne live dekha Part 5 mein"* (no need to switch to browser)

---

## Step 6.2 — Algorithm 2: AI Advisor Context Injection (~40 sec)

### 🖥️ Screen Action
- Scroll to **Algorithm 2** in Section 6.3
- Show the **6-step process diagram** or numbered list

### 🎤 MH says:

> "**Doosra Algorithm hai AI Advisor Context Injection — yeh chhay steps mein kaam karta hai.**"

> "Step 1 — system live use case ka data fetch karta hai. Step 2 — us data ko ek structured system prompt mein inject karta hai. Step 3 — conversation history append hoti hai. Step 4 — configured LLM ko call kiya jaata hai — chahe OpenAI ho, Anthropic ho, ya OpenRouter."

> "Step 5 — response SSE ke zariye real-time stream hota hai. Aur Step 6 — sab se interesting — agar LLM koi tool call kare, jaise `getRisksByProject`, toh backend us function ko execute karta hai aur result wapas inject karta hai."

> "Matlab Advisor se aap pooch sakte hain — 'is hafte mere kaun se risks Critical hain?' — aur yeh live data se jawab dega."

### 👆 While saying this:
1. **Point to** each of the 6 steps as you name them
2. **Highlight Step 6** (tool calling) — this is the most impressive part
3. The `getRisksByProject` function call example makes it tangible

---

## Step 6.3 — Algorithm 3: LLM Evaluation Scoring Pipeline (~30 sec)

### 🖥️ Screen Action
- Scroll to **Algorithm 3**
- Show the **pipeline diagram**

### 🎤 MH says:

> "**Teesra Algorithm hai LLM Evaluation Scoring Pipeline.**"

> "Yeh aise kaam karta hai — pehle test dataset load hota hai, phir target LLM ko bheja jaata hai, phir chaar metrics se score hota hai — Correctness, Faithfulness, Hallucination Rate, aur Bias. Phir results aggregate ho kar store hote hain."

> "Arena mode mein do models ek saath evaluate hote hain — side-by-side comparison."

### 👆 While saying this:
1. **Point to** the pipeline flow in the diagram
2. **Call out** the 4 metrics: Correctness, Faithfulness, Hallucination Rate, Bias
3. Mention "Arena mode" — point to side-by-side comparison visual if in the doc

> ⏱ Keep this brief — 30 seconds max

---

## Step 6.4 — Algorithm 4: PMM Scheduler (~30 sec)

### 🖥️ Screen Action
- Scroll to **Algorithm 4**
- Show the **BullMQ cron flowchart**

### 🎤 MH says:

> "**Chautha Algorithm hai PMM Scheduler.** Yeh BullMQ cron job hai jo har ghante chalti hai — cron expression `0 * * * *`."

> "Kaam aise hota hai — pehle active PMM configs query hoti hain. Agar koi active cycle nahin hai, toh naya cycle create hota hai aur questionnaire email bheji jaati hai. Reminder days ka threshold aane par reminder jaata hai. Escalation days guzarne par escalation alert jaata hai. Aur jab cycle submit ho, toh Playwright se PDF report automatically generate hoti hai."

### 👆 While saying this:
1. **Point to** cron expression `0 * * * *` — "har ghante"
2. **Trace the flowchart** with cursor: query → create cycle → email → reminder → escalation → PDF
3. Mention EU AI Act Articles 9 & 72 if referenced in the diagram

---

## Step 6.5 — Algorithm 5: Automation Rule Engine (~30 sec)

### 🖥️ Screen Action
- Scroll to **Algorithm 5**
- Show the **event-flow diagram**

### 🎤 MH says:

> "**Paanchwa aur aakhri Algorithm hai Automation Rule Engine.**"

> "Jab koi event fire hota hai — toh system us tenant ke rules query karta hai. Phir conditions evaluate hoti hain. Jo rules match karein — un ki actions execute hoti hain — jaise SLACK message, EMAIL, TASK create, ya WEBHOOK call. Aur har execution ki history log hoti hai."

### 👆 While saying this:
1. **Trace the flow** in the diagram: trigger → query → evaluate → execute → log
2. **Point to** the 4 action types: SLACK, EMAIL, TASK, WEBHOOK

---

## Step 6.6 — Data Dictionary Key Points (~30 sec)

### 🖥️ Screen Action
- Navigate to **Section 5.8 Data Dictionary** in the doc
- Show the table definitions briefly

### 🎤 MH says:

> "Data Dictionary se chand key points batata hoon."

> "`projects` table mein `uc_id` column hai — yeh auto-generated VARCHAR UNIQUE hai. `ai_risk_classification` ek ENUM (Enumeration) hai — Prohibited, High Risk, Limited Risk, Minimal Risk — yeh directly EU AI Act ki terminology se map hota hai."

> "`project_risks` table mein `risk_level_autocalculated` ENUM hai — yeh backend ne formula se compute ki hai."

> "`post_market_monitoring_configs` mein `frequency_value`, `reminder_days`, `escalation_days`, aur `escalation_contact_id` — yeh FK (Foreign Key) hai jo user se link karti hai."

> "Constraints ki baat karein toh — PostgreSQL 14 ya usse zyada chahiye. Redis required hai. JWT ki expiry 24 ghante hai. Bcrypt mein 10 hashing rounds hain. Rate limiting 100 requests per 15 minutes per IP hai. Aur file upload ki maximum size 10 MB hai."

### 👆 While saying this:
1. **Point to** `projects` table → `uc_id` column
2. **Point to** `ai_risk_classification` ENUM values
3. **Point to** `project_risks` table → `risk_level_autocalculated`
4. **Point to** `post_market_monitoring_configs` → frequency/reminder/escalation fields
5. Don't linger — just highlight and move forward

---

## ✅ Part 6 Handoff

**MH says:**
> *"Farhana, ab sprints aur results summarize karo."*

### Checklist before moving on:
- [ ] Algorithm 1 (Risk Scoring) — formula, thresholds, decision table shown
- [ ] Algorithm 2 (AI Advisor) — 6 steps, tool calling highlighted
- [ ] Algorithm 3 (LLM Eval) — pipeline, 4 metrics, Arena mentioned
- [ ] Algorithm 4 (PMM Scheduler) — cron, 5-step loop, PDF report
- [ ] Algorithm 5 (Automation Engine) — event flow, 4 action types
- [ ] Data Dictionary — key tables and constraints mentioned

> **If running late:** Compress Algorithms 3 and 5 to one sentence each. Prioritize Algorithms 1 (most visual) and 4 (most complex).

---
---

# ═══════════════════════════════════════════════════
# PART 7 — Sprints, Results, aur Conclusion
# Speaker: Farhana Minhas + Ahmed Abdullah Khan | ⏱ ~3 min
# ═══════════════════════════════════════════════════

---

## Step 7.1 — Sprint Highlights — FM speaks (~1 min 15 sec)

### 🖥️ Screen Action
- **Alt+Tab** → switch to **PowerPoint** → navigate to **Slide 12 (Sprint Summary)**

### 🎤 Script — FM says:

> "Ab nau sprints ke key highlights bataati hoon."

### 👆 Then read these — one by one, brisk but clear:

> "Sprint 1 mein humne monorepo setup kiya, Docker configure kiya, JWT (JSON Web Token) authentication aur RBAC implement kiya, aur Sequelize ORM (Object-Relational Mapping) integrate kiya."

> "Sprint 2 mein schema-per-tenant multi-tenancy bani, aur poora Approval Workflow engine bana — SSE real-time notifications ke saath, jo 100 milliseconds se bhi kam mein deliver hoti hain."

> "Sprint 3 mein EU AI Act ka seeder implement hua."

> "Sprint 4 mein ISO 42001 aur ISO 27001 add hue."

> "Sprint 5 mein Risk Management aaya — auto-calculation formula ke saath, aur RiskHistory tracking."

> "Sprint 6 mein Vendor Management, Policy Manager, aur Policy Templates banay."

> "Sprint 7 mein Model Inventory aaya, aur NIST AI RMF ke chaaron functions implement hue — GOVERN, MAP, MEASURE, aur MANAGE."

> "Sprint 8 mein LLM Evaluations aur AI Advisor ki UIs banayi gayi — UI-first strategy ke tahat."

> "Sprint 9 mein Playwright se PDF reporting implement hui, Command Palette Ctrl+K bana jo 14 entity types mein search karta hai — is par supervisor ne khas tarif ki."

### 🎤 Then mention the bug:

> "Ek bug bhi aaya — Sprint 9 mein PDF formatting mein race condition thi. Humne retry mechanism lagaya aur usi sprint mein fix kar diya."

### 👆 While saying this:
- **Point to each sprint** on the slide as you name it
- Read it like a **news ticker** — brisk, confident, no unnecessary pauses

---

## Step 7.2 — Test Results & UAT (User Acceptance Testing) — FM continues (~45 sec)

### 🖥️ Screen Action
- Advance to **Slide 15 (UAT Table)**

### 🎤 Script — FM says:

> "Ab results ki baat karte hain. Kull 258 test cases the — 45 Jest unit tests, 32 frontend component tests, 28 API integration tests, 90 sprint extended tests, 8 security tests, 10 PMM tests, aur 15 PDF tests."

> "258 mein se 258 pass hue — zero fail — 100 percent correctness."

### 👆 Pause briefly to let "258 pass, 0 fail" sink in — then continue:

> "UAT mein 43 user stories test hui — 100 percent pass. Multi-tenancy ke 15 cross-tenant access attempts kiye — 100 percent correctly block hue. RBAC ke 30 unauthorized attempts kiye — 100 percent block hue. SSE ke 50 tests mein se 49 hundred milliseconds se kam mein deliver hue."

> "Overall Phase 1 accuracy approximately 99 percent hai."

### 👆 While saying this:
1. **Point to** each stat on the UAT table as you read it
2. **Emphasize** "100 percent blocked" for multi-tenancy and RBAC — these are security proof
3. Deliver "99 percent" with confidence — this is the strongest closing stat

---

## Step 7.3 — Tech Stack + Phase 2 + Closing — AAK speaks (~1 min)

### 🖥️ Screen Action
- Advance to **Slide 18 (Conclusion)**

### 🎤 Script — AAK says:

> "Aegis.AI koi prototype nahin hai — yeh ek mukammal, operational, enterprise-grade platform hai."

> "Is mein lagbhag 60 hazaar lines of code hain — TypeScript aur Python mila kar. 60 route modules hain, aur 40 se zyada database tables hain."

### 👆 Pause half a beat — then read tech stack:

> "Hamara tech stack hai: Frontend mein React 18, Vite 6, Material UI, Redux Toolkit, aur React Query version 5. Backend mein Node.js 22, Express 4, TypeScript 5, aur Sequelize 6. Evaluation server Python FastAPI par hai, DeepEval framework ke saath."

> "Database PostgreSQL 15 hai. Background jobs Redis BullMQ se chalti hain. Authentication mein JWT plus bcrypt plus Google OAuth2 (Open Authorization 2.0) hai. PDF generation Playwright se hoti hai."

> "Deployment ke liye Docker Compose hai aur Kubernetes ke 8 manifests hain, HPA (Horizontal Pod Autoscaler) ke saath. Documentation Swagger OpenAPI 3.0 par hai. Testing mein Jest, Supertest, RTL (React Testing Library), aur MSW (Mock Service Worker) use hue. License Business Source License 1.1 hai."

### 🎤 Phase 2 plans:

> "Phase 2 mein 15 planned user stories hain — 114 story points ke saath. Key items hain — live LLM connections, full DeepEval benchmarking, GitHub AI Detection scan, Bias aur Fairness ki complete scoring, SMTP aur SES emails, Slack integration, MLflow sync, aur AWS EKS ya Azure AKS par deployment."

### 🎤 Long-term roadmap (one breath):

> "Long-term roadmap mein shamil hain — granular permissions, AI risk assessment ki auto-generation, mobile app, Jira integration, Compliance Template Marketplace, aur OSCAL (Open Security Controls Assessment Language) export."

### 🎤 Closing — say with sincerity:

> "Hum dil ki gehrayyion se Sir Usama Ahmad ka shukriya ada karte hain un ki rahnumayi ke liye."

> "Source code, documentation, aur test cases — sab kuch github.com/muhammadharis356/aegis-develop par available hain."

> "Jazakallah Khair."

### 👆 While saying the closing:
- Look at camera / maintain composure
- Small nod at the end
- **Wait 3 seconds** of silence before stopping the recording

---

## ✅ Part 7 End — Presentation Complete! 🎉

### Final Checklist:
- [ ] Nine sprint highlights delivered (one by one, clear)
- [ ] Bug mention (Sprint 9 PDF race condition)
- [ ] 258 test cases — 100% stat delivered with impact
- [ ] UAT, multi-tenancy, RBAC, SSE stats delivered
- [ ] "~99% accuracy" stat landed
- [ ] Tech stack delivered clearly
- [ ] Phase 2 + roadmap mentioned
- [ ] Closing thanks to Sir Usama Ahmad
- [ ] GitHub link given
- [ ] "Jazakallah Khair" — **END**

---
---

# 🎯 Master Quick-Reference Card

| Part | Speaker | Duration | Screen | Key Actions |
|------|---------|----------|--------|-------------|
| **1** | MH | 5 min | PowerPoint | Title → Agenda → Problem (5 problems) → Objectives (10 goals) |
| **2** | AAK | 5 min | PowerPoint → Doc | Customers → Competitors → Architecture (C4 + Clean Arch) → ERD → Multi-tenancy |
| **3** | FM | 3 min | PowerPoint → Figma | Slides 9–10 → Figma screens scroll |
| **4** | AAK | 3 min | VS Code | root tree → `routes/` scroll → 3 middleware files → docker-compose → k8s |
| **5** | MH | 8 min | Browser | Registration → Onboarding → Demo Data → Dashboard → Use Cases → EU AI Act → Risks → Approvals → Policy → Vendors → Models → PMM → Automations → Incidents → Tasks → WatchTower → AI Trust → Evals → AI Detection → Ctrl+K → Settings |
| **6** | MH | 4 min | Doc (Section 6.3) | 5 algorithms + Section 5.8 Data Dictionary |
| **7** | FM+AAK | 3 min | PowerPoint | Sprint highlights → Test results → Tech stack → Phase 2 → Jazakallah Khair |

> 🔑 **If running behind schedule — what to cut:**
> - **Part 4:** Skip opening middleware files, just name them while pointing in Explorer
> - **Part 5:** Skip Settings Email/Slack/API tabs, just show LLM Keys tab
> - **Part 6:** Compress Algorithms 3 & 5 to one sentence each
> - **Part 7:** Skip long-term roadmap sentence
