# Nepali & Sinhala to English Translator

This project provides an OCR-based translator for Nepali and Sinhala to English built with Vite, React, TypeScript and Tailwind.

## Local development

Requirements: Node.js and npm.

```powershell
cd "path\to\project"
npm install
npm run dev
```

Open `http://localhost:8080` in your browser.

## AI provider configuration

This project calls an external AI API from `supabase/functions/translate/index.ts`. Provide the following environment variables for the function runtime:

- `AI_API_KEY` — your provider API key
- `AI_API_URL` — (optional) the full endpoint to POST chat completions to; if not provided a placeholder default is used in the function

Adjust the function code to match your AI provider's request format and models.

## About

If you need help wiring a specific AI provider (OpenAI, Anthropic, Google, etc.), tell me which provider you want and I can adapt the function for that API.
