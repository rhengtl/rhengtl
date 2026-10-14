## Hi, I'm Rhenier Gustilo

**Software Engineer: Machine Learning & Backend** · Philippines · open to on-site roles in the Philippines and remote roles

I build AI-powered software end to end: real-time speech pipelines on a Raspberry Pi, LLM services at the edge, and offline-first apps that keep working without a signal.

The part I enjoy most comes after the model works in a notebook: making it answer in real time on constrained hardware, putting an LLM behind an API that can't be misused, and keeping an app useful with no connection. Internships in systems deployment and technical support taught me how things fail in the field, so my projects ship with tests, validation logs and fallbacks.

[rhengtl.tech](https://rhengtl.tech) · [LinkedIn](https://www.linkedin.com/in/rhengtl/) · rheniergustilo06@gmail.com

---

### Featured work

| Project | What it is | Highlights | Stack |
|---|---|---|---|
| **[EarPrompt](https://github.com/rhengtl/earprompt)** · [case study](https://rhengtl.tech/projects/earprompt) · thesis, team of 4 | Raspberry Pi 5 wearable that listens to a conversation and whispers one short Taglish tip on how to respond | Lead developer of the audio/AI pipeline, device API and most of the Flutter app · **3.8 s** avg end-to-end latency (4.2 s P95) · **$0.02–0.07** LLM cost per 30-min session | Python, PyTorch, SpeechBrain, Silero VAD, LLM APIs, Flask, Flutter |
| **[ConTeX](https://github.com/rhengtl/contex)** · [live](https://contex.rhengtl.tech) · [case study](https://rhengtl.tech/projects/contex) | Photograph handwriting or drop in a PDF and get LaTeX back, compiled to a PDF preview in the browser | Ported from Flask to Cloudflare's edge · **1,197** automated checks across 10 suites · **34 ms** warm in-browser LaTeX compile · security audit that closed a prompt-injection hole | JavaScript, Cloudflare Workers, Gemini API, WebAssembly, ONNX, Firebase |
| **[TindaBot](https://github.com/rhengtl/tindabot)** · [live](https://tindabot.rhengtl.tech) · [case study](https://rhengtl.tech/projects/tindabot) | Offline-first PWA that tells sari-sari store owners what to buy, how many, and how much cash to bring, in Taglish | Solo · event-sourced data model with Supabase sync under row-level security · **456** tests checked against an independent Python reference model · **8×** faster recompute on two years of data | TypeScript, React, IndexedDB, PostgreSQL, Gemini API |
| **[TomatoSense](https://github.com/rhengtl/tomatosense)** · [live](https://tomato-sense.rhengtl.tech) | Classifies tomato photos as ripe or unripe, one image or a batch of 20 | OpenCV preprocessing + PCA + SVM served by FastAPI · **96.25%** accuracy on an 80-image held-out test | Python, scikit-learn, OpenCV, FastAPI |
| **[TextSnip](https://github.com/rhengtl/textsnip)** | Drag a box over text in any Android app and get an editable copy | On-device OCR with Google ML Kit; captures are deleted right away and nothing is uploaded | Flutter, Kotlin, ML Kit |
| **[ClickMap](https://github.com/rhengtl/clickmap)** | Windows tray widget that turns keyboard keys into mouse clicks at saved screen points | Low-level keyboard hook, per-monitor DPI awareness, atomic config writes with corrupt-file recovery | C#, .NET 10, WPF, Win32 |

Case studies with architecture, trade-offs and results: **[rhengtl.tech](https://rhengtl.tech)** · [source](https://github.com/rhengtl/portfolio)

---

### Toolbox

**Machine learning & AI** — PyTorch (speech models), scikit-learn, OpenCV, TensorFlow/Keras, NumPy, pandas, SpeechBrain, Silero VAD, ONNX Runtime Web, Tesseract / ML Kit OCR, LLM APIs (OpenAI, Gemini), prompt design and output guardrails

**Backend & APIs** — FastAPI, Flask, REST API design, WebSockets and streaming, Cloudflare Workers (Durable Objects, KV), Vercel serverless, Firebase Auth / Google OAuth / JWT, rate limiting

**Data** — PostgreSQL with row-level security (Supabase), SQL, Firestore and security rules, IndexedDB (Dexie), event-sourced data models

**Languages** — Python, TypeScript, JavaScript, SQL, Dart, C#, Kotlin, C++, R, Verilog HDL

**Frontend & mobile** — React, Vite, Zustand, PWAs, Flutter, Android, WPF/.NET, WebAssembly

**DevOps & quality** — Git, GitHub Actions CI/CD, Vitest, Playwright, Python unit tests, Docker, Linux, Vercel, Render, Cloudflare, Firebase

**Embedded** — Raspberry Pi 5 (GPIO, I²C sensors, audio I/O), Arduino / ESP

---

### Background

- **BS Computer Engineering, Machine Learning specialization** — Polytechnic University of the Philippines, Sta. Mesa, Manila (2026) · President's Lister
- **Internships** — IT & Security Systems Intern, WJS Inc. (2025) · Technical Support Intern, RVCom Computer Trading (2024) · Web Design Intern, DOST – Philippine Nuclear Research Institute (2022)
- **Certifications** — Machine Learning with Python (freeCodeCamp) · Hugging Face Agents Course · AWS Cloud Practitioner Essentials · Kaggle Learn: Intro to ML, Intermediate ML, Intro to Deep Learning, Computer Vision · Cisco CCNA: Switching, Routing, and Wireless Essentials

---

I'm looking for **software engineering, machine learning and backend** roles. Email is the fastest way to reach me: **rheniergustilo06@gmail.com**
