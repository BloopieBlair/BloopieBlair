# Blair (BloopieBlair)

Independent software developer focused on local AI architectures, media automation, data visualization, and game tooling. I build self-contained, high-performance applications designed to run locally on consumer hardware without subscription tiers, telemetry, or external API lock-in.
ko_fi: bloopieblair
---

## Featured Projects

### [LocAi-Search](https://github.com/BloopieBlair/LocAi-Search)
**Local-first autonomous deep research and intelligence studio**

LocAi Search is a desktop research workstation that runs small, open-weight language models locally on consumer hardware while performing live web research and source extraction.

- **Local Inference**: Directly interfaces with llama.cpp and Ollama to run GGUF quantized models (such as Qwen2.5-7B-Instruct) with CUDA acceleration and zero external AI telemetry.
- **Neural Semantic Re-Ranking**: Embedded FlashRank cross-encoder (`ms-marco-MiniLM-L-12-v2`) scoring and ranking extracted web documents against queries using semantic relevance and domain authority.
- **Epistemic Anti-Hallucination Guardrails**: Deterministic code-level gates enforce factual grounding, including a claim-to-source digit token linter, symmetric entity coverage requirements for comparison queries, and extraction validity filters.
- **Desktop Architecture**: Native desktop GUI built on PyWebView, FastAPI, and WebSockets for real-time token streaming and tool execution tracking.

*Stack: Python, llama.cpp, FlashRank, Playwright, FastAPI, PyWebView, Hugging Face Hub*

---

### [RedditReadingApp](https://github.com/BloopieBlair/RedditReadingApp)
**Automated YouTube Shorts generator and video production pipeline**

An end-to-end media automation pipeline and web studio that extracts top Reddit discussions and renders fully composited 9:16 vertical video Shorts for YouTube.

- **Content & Card Extraction**: Dual-engine Reddit scraper that renders pixel-perfect Reddit card UI components into transparent PNGs using headless Chromium (Playwright) or fallback Pillow graphics.
- **Speech Synthesis**: Converts story text to voiceover using Microsoft Edge neural TTS, with pre-flight sanitization for spoiler tags, links, and pronunciation anomalies.
- **Hardware-Accelerated Compositing**: Three-tier rendering engine with native FFmpeg hardware encoding (NVIDIA NVENC, AMD AMF, Intel QSV) and automated fallback to MoviePy and OpenCV.
- **Dynamic Captions & Publishing**: Synchronizes word-level animated subtitles with voiceover timestamps, crops background gameplay to 9:16 vertical orientation, mixes procedural lofi audio, and automates uploads via YouTube Data API v3 OAuth.

*Stack: Python, FastAPI, Playwright, Edge-TTS, FFmpeg / NVENC, MoviePy, OpenCV, YouTube Data API v3*

---

### [MTG-Deck-Relation-Visualizer](https://github.com/BloopieBlair/MTG-Deck-Relation-Visualizer)
**Interactive synergy graph and deck analysis suite for Magic: The Gathering**

A browser-based analytical toolkit and visualization engine for Commander / EDH deckbuilders to inspect card mechanics and simulate early-game consistency.

- **Synergy Network Graph**: Renders decklists as interactive D3.js force-directed graphs, mapping mechanical relationships (ramp, card draw, removal, tutors) with colored multi-link paths and isolated node detection.
- **BFS Goldfish Simulator**: Simulates opening turns using a breadth-first search pathfinder across branching game states to evaluate play lines and commander cast timing.
- **Statistical Dashboard**: Interactive converted mana cost distributions, land production vs. pip requirement ratios, and hypergeometric probability calculators for opening hands.
- **Scryfall & Arena Integration**: Live Scryfall card data resolution, high-resolution card artwork, and MTG Arena collection log synchronization.

*Stack: TypeScript, React 18, Vite, D3.js, Scryfall API, TailwindCSS*

---

## Technical Focus & Tools

- **Languages**: Python, TypeScript, JavaScript, SQL, HTML/CSS, Bash, PowerShell
- **Backend & Systems**: FastAPI, Uvicorn, WebSockets, REST APIs, Pytest, Pydantic
- **AI & Local Inference**: llama.cpp, Ollama, GGUF quantization, FlashRank, Hugging Face
- **Frontend & Data Visualization**: React, Vite, D3.js, TailwindCSS, PyWebView
- **Media & Browser Automation**: FFmpeg (NVENC/AMF/QSV), MoviePy, OpenCV, Playwright, Pillow, Edge-TTS
- **Platforms & Tooling**: Git, Linux, Windows, Docker

---

## Links & Contact

- GitHub: [@BloopieBlair](https://github.com/BloopieBlair)
- Repositories: [github.com/BloopieBlair?tab=repositories](https://github.com/BloopieBlair?tab=repositories)
