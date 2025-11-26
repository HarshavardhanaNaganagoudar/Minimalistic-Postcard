
# 🌫️ Minimalistic Postcards
---
## A tiny atmospheric postcard generator — built from weather, time, mood, pulse, and poetry.
## Minimalistic Postcards transforms any place into a calm, aesthetic snapshot.
## Powered by OpenAI + real-time weather + location-aware time + cultural pulse signatures.
## Each postcard is a blend of:
* Weather Glyph → minimal symbolic sky
* Time Glyph → sunrise / golden hour / night
* City Pulse → location-based waveform art
* Atmospheric Quote → a tiny poetic moment
* Clean Summary → formatted like a miniature postcard
### Perfect for: creative dashboards, travel apps, mood boards, daily inspiration snippets, journaling companions, ambient UIs.
---
## ✨ Features
* ✔ Real-time weather (Open-Meteo API)
* ✔ Local time & timezone detection
* ✔ Weather + time → expressive glyphs
* ✔ Cultural + geographic → city pulse waveform
* ✔ OpenAI-powered micro-poetry
* ✔ Full combined “Minimalistic Postcard” output
* ✔ HTML postcard rendering
---

## 📺 Demo Video

🎥 [Watch the Demo on YouTube](https://youtu.be/-gaDxKcdHTA?si=vNube7Th1W_4KmQW)

---

## How to use it

* Edit the claude config file to add the below and save it.
```
{
  "mcpServers": {
    "gradio": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "https://mcp-1st-birthday-minimalistic-postcard.hf.space/gradio_api/mcp/sse"
      ]
    }
  }
}

```

* Once the MCP server is integrated into the Claude, then in the Claude UI enable the tools.
* **Example prompt to use on MCP client claude**: I am in tokyo, eating sushi near tokyo tower, generate a beautiful minimalistic postcard with tangerine font html file

---

![output](./summary_postcard.html)

---
