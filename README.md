# OKING — Vercel Deployment Guide

## ♛ Project Ready! 

Yeh 3 files hain:
- `index.html` — Website
- `api/chat.js` — Backend (OpenRouter se baat karta hai)
- `vercel.json` — Vercel config

## ⚡ Step 1 — Vercel mein upload karo

1. vercel.com/dashboard kholo
2. "Add New Project" click karo
3. "Upload" select karo
4. **Ye 3 files select karo:**
   - index.html
   - api folder (pure folder ko)
   - vercel.json
5. "Upload Project" click karo
6. Project name likho: `oking-app`
7. "Deploy" click karo — 2-3 minute wait karo

## 🔑 Step 2 — Environment Variable add karo

Jab deploy complete ho:

1. Dashboard mein project kholo
2. "Settings" click karo
3. Left mein "Environment Variables" click karo
4. "Add New" click karo
5. Yeh dal:
   - **Name:** `OPENROUTER_KEY`
   - **Value:** `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`
6. "Save" click karo

## 🔄 Step 3 — Redeploy

1. "Deployments" tab par jao
2. Latest deployment par hover karo
3. "..." click karo
4. "Redeploy" click karo
5. Wait karo — 2 minute

## ✅ Step 4 — Test karo!

Jab "Ready" show ho:

1. "Visit" button click karo — website khul jayegi!
2. Mode select karo (Free/Premium/King)
3. Message likho
4. "Bhej" button click karo
5. AI jawab aayega! 🎉

## 🚨 Agar error aaye:

**404 Error:**
- vercel.json check karo
- Redeploy karo

**API Error:**
- Environment variable check karo
- Spelling sahi hai OPENROUTER_KEY?

**Network Error:**
- Internet check karo
- API key check karo

## 📊 Models kaunse:

Mode | AI Model | Cost
---|---|---
🆓 Free | Llama 3.1 8B | FREE
⭐ Premium | Claude Sonnet | Sasta
♛ King | Claude Opus | Premium

**Jab users aayenge → fees se cost cover hoga!**

---

**Ab live ho gaya! Share karo logon ko!** 👑
