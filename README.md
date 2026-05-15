# Nyx Éléonore Vautrain - Educational Bot 🎓

Prototype de bot Telegram pédagogique utilisant une architecture hybride **Mistral AI** et **Google Gemini**.

## 🚀 Concept
Développé par **Damien Vautrain**, Nyx est une version professionnelle conçue pour accompagner l'apprentissage du développement Web et Mobile. Elle démontre l'intégration d'IA génératives dans un flux de travail serverless.

## 🛠 Stack Technique
- **Runtime** : Node.js 20
- **Framework Bot** : Telegraf.js
- **IA (Raisonnement)** : Mistral AI (Model Medium)
- **IA (Connaissances)** : Google Gemini (Model 1.5 Flash)
- **Hébergement** : Vercel (Functions Serverless)

## 📌 Installation
1. Configurer les variables d'environnement : `TELEGRAM_TOKEN`, `MISTRAL_API_KEY`, `GEMINI_API_KEY`.
2. Déployer sur Vercel.
3. Définir le webhook : `https://api.telegram.org/bot<TOKEN>/setWebhook?url=<URL_VERCEL>/api/webhook`

## ⚖️ Licence
MIT - Damien Vautrain
