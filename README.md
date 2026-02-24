# NeuroScan AI — Alzheimer's MRI Detector
Powered by Google Gemini Vision (FREE)

## Setup (2 minutes)

### 1. Get free Gemini API key
- Go to https://aistudio.google.com/apikey
- Click **Create API key**
- Copy the key (starts with `AIza...`)

### 2. Paste key into config.js
Open `config.js` and replace `YOUR_GEMINI_API_KEY_HERE` with your key:
```js
GEMINI_API_KEY: "AIzaSy.....your_key_here",
```

### 3. Open index.html in browser
Double-click `index.html` — done!

## Files
```
alzheimer-detector/
├── index.html     ← Main website (UI only, no keys)
├── config.js      ← Your API key lives here (PRIVATE)
├── .gitignore     ← Prevents config.js from being uploaded
└── README.md
```

## Free Tier Limits (Gemini 1.5 Flash)
- 15 requests per minute
- 1,500 requests per day
- 1 million tokens per minute
- NO credit card needed

## Important
- Never share or commit config.js
- This tool is for educational use only, not clinical diagnosis
