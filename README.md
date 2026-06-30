<h1 align="center">Hi, I'm technikky 👋</h1>

<p align="center">
  <strong>Senior Full-Stack Engineer</strong> — I ship production-grade SaaS & AI products.
</p>

<p align="center">
  <a href="https://github.com/technikky/pulseboard"><img alt="PulseBoard" src="https://img.shields.io/badge/Live_Demo-PulseBoard-7c5cff?style=flat-square"></a>
  <a href="mailto:ixayle@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-ixayle@gmail.com-22d3ee?style=flat-square"></a>
</p>

---

### 🛠️ What I work with

```ts
const technikky = {
  languages: ["TypeScript", "JavaScript", "C#", "SQL", "Python"],
  frontend:  ["React", "Next.js (App Router)", "Vite", "Tailwind CSS", "Recharts"],
  backend:   ["Node.js", "Express", "Server Actions", "REST", "Streaming APIs"],
  data:      ["Supabase", "Postgres", "Row-Level Security", "Firebase"],
  payments:  ["Stripe"],
  ai:        ["Anthropic Claude API", "token streaming", "graceful fallbacks"],
  principles: {
    typeSafety: "non-negotiable",
    tenancy:    "DB-enforced (RLS)",
    failures:   "degrade gracefully",
    scope:      "schema → API → pixels",
  },
};
```

---

### 🚀 Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| **[Lumina Analytics](https://github.com/technikky/lumina-analytics)** | AI analytics SaaS — token-streamed Claude insights over your metrics, with a stub fallback for every external service | `Next.js 16` · `Supabase` · `Stripe` · `Claude` |
| **[PulseBoard](https://github.com/technikky/pulseboard)** ⟶ [live](https://pulseboard-silk.vercel.app) | Multi-tenant feedback & feature-voting SaaS — tenants isolated at the DB layer with Postgres **Row-Level Security** | `Next.js` · `Supabase` · `Stripe` |
| **[Workforce Ops Dashboard](https://github.com/technikky/workforce-ops-dashboard)** | Enterprise KPI & project-management dashboard — typed Context state, Recharts data-viz | `React` · `TypeScript` · `Vite` · `Recharts` |
| **[AI Resume Builder](https://github.com/technikky/AIResume)** | SaaS resume builder — AI generation, Firebase Auth, Stripe billing on a Node backend | `React` · `Node` · `Firebase` · `Stripe` |
| **[LLM Chatbot](https://github.com/technikky/LLM-ChatBot)** | From-scratch streaming chat over an LLM API — built to own the full request/stream/render loop | `Next.js` · `Express` |

---

### 📊 A pattern across my repos

Every external dependency — database, payments, AI — ships with a **graceful stub fallback**, so the
app still runs and demos cleanly with zero keys configured. I treat type-safety and clear boundaries
as features, not overhead.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=technikky&show_icons=true&hide_border=true&theme=tokyonight&hide=contribs" height="160" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=technikky&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" height="160" alt="Top languages" />
</p>

<p align="center"><sub>📫 Reach me at <b>ixayle@gmail.com</b></sub></p>
