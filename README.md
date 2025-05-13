# Accessibility Fixer Bot 🛠️♿

A lightweight AI-powered CLI tool to detect and suggest accessibility improvements in your frontend codebase.

---

## Features

✅ Detects:
- Missing `alt` on images
- Input fields without labels
- Heading level inconsistencies

✨ AI Suggestions:
- Alt text descriptions using GPT
- Label hints and ARIA role tips

---

## Getting Started

```bash
git clone https://github.com/your-username/accessibility-fixer-bot.git
cd accessibility-fixer-bot
npm install
cp .env.example .env # Add your OpenAI API key
npx ts-node src/cli.ts test/sample.tsx
