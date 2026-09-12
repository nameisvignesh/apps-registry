# model-metrics-inspector

Rowboat-க்கான Model Metrics & Cost Tracker. ஒரு model எவ்வளவு cost, latency, tokens consume பண்ணுதுனு live-ஆ measure பண்ற App.

> **Registry Note:** இந்த App-ன் package name `model-metrics-inspector`. இது தான் Rowboat catalog-லும், registry-லும் வரும். Repo பேர் வேற-ஆ இருந்தாலும், `rowboat-app.json`-ல் இருக்கும் `name` தான் final.

## Features

- **Token Usage:** Input / Output / Total tokens per request
- **Cost Calculation:** Model-wise cost tracking (GPT-4, Claude, Gemini etc.)
- **Latency Measurement:** TTFT, total duration, avg latency
- **Model Comparison:** ஒரே prompt-ஐ பல model-ல் run பண்ணி compare பண்ணலாம்
- **Session History:** எல்லா metrics-ம் local-ல save ஆகும்

## Rowboat-ல் Install பண்ணுவது எப்படி?

Rowboat Catalog-ல் `model-metrics-inspector` என்று தேடி Install பண்ணவும்.

## Development

```bash
npm install
npm run dev
npm run build # dist/ folder உருவாகும்
