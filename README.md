# 🌍 Viatge Ètic

Eina per viatjar amb consciència. Analitza l'ètica del teu viatge en 3 passos:
1. D'on a on — compara opcions de transport per impacte
2. Analitza el destí — conflictes actius, pobles vulnerats, veredicte honest
3. Com viatjar-hi — cultura local, allotjaments ètics, consells pràctics

---

## 🚀 Com llançar-la (10 minuts)

### 1. Aconsegueix una API key d'Anthropic
Ves a https://console.anthropic.com → API Keys → Create Key

### 2. Puja el projecte a GitHub
```bash
git init
git add .
git commit -m "primer commit"
git remote add origin https://github.com/el-teu-usuari/viatgeetic.git
git push -u origin main
```

### 3. Despliega a Netlify (gratuït)
1. Ves a https://netlify.com i crea un compte gratuït
2. "Add new site" → "Import an existing project" → connecta GitHub
3. Selecciona el repositori → "Deploy site"

### 4. Afegeix la teva API key
A Netlify: Site configuration → Environment variables → Add variable
- Key: `ANTHROPIC_API_KEY`
- Value: la teva API key d'Anthropic

### 5. Redespliega
A Netlify: Deploys → "Trigger deploy" → "Deploy site"

✅ Ja tens la teva web funcionant!

---

## 💰 Com monetitzar-la

**Versió gratuïta:** 3 consultes/dia (implementa amb cookies o localStorage)
**Versió Pro (9€/mes):** consultes il·limitades + informe PDF + recomanacions d'allotjaments verificats

Plataformes de pagament: Stripe, LemonSqueezy, Gumroad

---

## 📁 Estructura del projecte

```
viatgeetic/
├── index.html              # Frontend complet
├── netlify.toml            # Configuració de Netlify
├── netlify/functions/
│   └── ai.js              # Proxy segur per a l'API d'Anthropic
└── README.md
```

---

Fet amb ❤️ a Barcelona
