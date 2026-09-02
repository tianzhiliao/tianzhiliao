# Hi, I'm Tianzhi 👋

**AI product builder** — I turn practical ideas into working learning and data products, end to end: product decisions, data pipelines, backend services, and the web and mobile surfaces on top.

📍 Coquitlam, BC (Greater Vancouver) · open to remote roles across Canada
🔗 [LinkedIn](https://www.linkedin.com/in/tianzhiliao) · ✉️ tianzhi.liao@gmail.com

## What I'm building

**[Math Kangaroo Prep](https://github.com/tianzhiliao/math-kangaroo)** — Full-stack contest practice platform (Next.js 14 + FastAPI).
A Python pipeline turns 20+ contest PDFs into ~600 structured questions with verified answer keys. AI explanations run through strict JSON schema output with **answer-contradiction detection** — the model's stated answer is checked against the verified key before anything reaches a student — plus a retry-with-constraint loop and a safe fallback.

**[Words App](https://github.com/tianzhiliao/words-app)** — Mobile vocabulary learning for Chinese speakers (Expo / React Native + FastAPI).
AI-generated definitions, example sentences, stories, and speech. Filesystem TTS caching keyed on voice and text takes repeat playback from a 1–2s API round trip to a **sub-50ms local read**.

**[aichatbot](https://github.com/tianzhiliao/aichatbot)** — Multi-model chat app (React 18 + TypeScript).
One abstraction layer over multiple model backends (Kimi K2 ⇄ DeepSeek R1), streaming responses, conversation memory, error boundaries with retry, and an accessible responsive UI.

**[Wirecutter Dashboard](https://github.com/tianzhiliao/wirecutter-dashboard)** — Product-recommendation data pipeline (Python).
JSON-LD structured extraction with multithreaded fetching, retry handling, and JSON/Excel export.

## How I work

Coding agents (Claude Code, Cursor, Codex) are my primary interface — I own architecture, review, debugging, and root-cause fixes. Most of what I ship has a deterministic check wrapped around the model: schema validation, contradiction detection, cache keys that include the prompt version.

**Focus:** AI-native products · LLM reliability · Data pipelines · Next.js · React Native · FastAPI · Python

---

### 你好，我是 Tianzhi

一名 AI 产品 Builder，坐标加拿大温哥华地区，开放全加拿大远程机会。

我借助 coding agents 把真实需求做成可用的学习与数据产品——从产品判断、数据管线，到 Web 与移动端体验完整落地。做 LLM 产品时习惯在模型外面套一层确定性校验：schema 校验、答案矛盾检测、带 prompt 版本的缓存键。
