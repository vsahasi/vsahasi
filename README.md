<a href="https://github.com/vsahasi">
  <img src="https://raw.githubusercontent.com/vsahasi/vsahasi/main/assets/banner.svg" width="100%" alt="Veer Sahasi. EECS + Business @ UC Berkeley M.E.T. I build AI systems end to end: retrieval, evals, agents, multimodal ML." />
</a>

I build AI products from data pipeline to UI, then measure whether they actually work. Most of what's below is retrieval, evaluation harnesses, agents, and multimodal ML, shipped as full apps with live demos or published eval numbers.

**Currently (Sep 2026):** building [Pathway](https://github.com/vsahasi/gates_user-prototype) for the Gates Foundation and leading a 6-student team benchmarking Claude across student personas and advising journeys.

## Featured work

| Project | What it does | Built with |
| --- | --- | --- |
| **[Pathway](https://github.com/vsahasi/gates_user-prototype)** · [live](https://gatesuser-prototype.vercel.app) | AI college and career advisor for the Gates Foundation. Custom RAG over IPEDS and Common Data Set profiles (6,000+ schools), live College Scorecard and O*NET data, inline citations, and separate workspaces for students and the parents or counselors they invite. | Next.js 16, Claude, Pinecone, SQLite |
| **[VeriTone](https://github.com/vsahasi/veritone)** | Multimodal credibility analysis for video. Scores each utterance on divergence between what is said, how it sounds, and what the face shows, then puts it on a searchable timeline with FAISS RAG and PDF export. | FastAPI, Whisper, SpeechBrain, FER, React |
| **[Reducto Docs Chat](https://github.com/vsahasi/reducto-docs-chat)** | Cite-or-refuse docs assistant for docs.reducto.ai. On a 20-question eval: 18/20 correct, 20/20 cited, 0 hallucinations. Bare Claude and GPT-4o matched correctness but cited nothing and hallucinated 1 to 2 times. | Next.js, Supabase pgvector, Reducto Parse, Claude |
| **[MemEval](https://github.com/vsahasi/memeval)** | Regression harness for LLM memory systems. Runs Mem0, naive RAG, and long-context baselines through 5 memory scenarios and grades them with a 4-point LLM-judge rubric. | Python, Mem0, Claude |
| **[the survivor bias](https://github.com/vsahasi/the-survivor-bias)** | Every YC company since 2005, about 5,800 of them, classified alive, dead, or exited by a 6-stage probe pipeline (HTTP, Wayback, GitHub, RDAP) and rendered as an interactive Canvas2D timeline. | Python, React, Vite |
| **[YC Outreach Agent](https://github.com/vsahasi/browser-use-yc-outreach)** | Multi-agent Browser Use pipeline that researches a YC batch across 4 sources and writes a personalized cold email per company. 20 companies in about 8 minutes at $0.14 each. | Python, Browser Use, Claude |
| **[onchain](https://github.com/vsahasi/onchain)** · [live](https://openchain-seven.vercel.app) | Marketplace for tokenized AI inference credits on the XRP Ledger. Deposit XRP, sell unused API capacity, buy access with an OpenAI-compatible key, settle every debit on-chain. | Next.js, XRPL, Supabase |
| **[deckify](https://github.com/vsahasi/deckify)** | Turns a slide image into a fully editable .pptx. GPT-4o structured output finds every element, OCR locks exact text, python-pptx rebuilds the layout. | Python, GPT-4o, PaddleOCR |
| **[candidate-facing-rerank](https://github.com/vsahasi/candidate-facing-rerank)** | People search over 100K+ LinkedIn profiles. GPT-4o query rewriting, Voyage-3 embeddings, Turbopuffer filtered ANN, structured re-ranking to a top 10. | Python, Turbopuffer, Voyage AI |

## Stack, by where I used it

| Layer | Tools | In the wild |
| --- | --- | --- |
| Retrieval | Pinecone, FAISS, Supabase pgvector, Turbopuffer, OpenAI and Voyage embeddings | [Pathway](https://github.com/vsahasi/gates_user-prototype), [VeriTone](https://github.com/vsahasi/veritone), [Reducto Docs Chat](https://github.com/vsahasi/reducto-docs-chat), [rerank](https://github.com/vsahasi/candidate-facing-rerank) |
| Models and evals | Claude, GPT-4o, LLM-as-judge rubrics, Whisper, SpeechBrain, FER, MediaPipe | [MemEval](https://github.com/vsahasi/memeval), [Reducto eval](https://github.com/vsahasi/reducto-docs-chat), [VeriTone](https://github.com/vsahasi/veritone) |
| Agents | Browser Use, multi-agent research pipelines, structured outputs | [YC Outreach Agent](https://github.com/vsahasi/browser-use-yc-outreach), [deckify](https://github.com/vsahasi/deckify) |
| Product | TypeScript, Next.js 16, React 19, Tailwind, Vercel | [Pathway](https://github.com/vsahasi/gates_user-prototype), [onchain](https://github.com/vsahasi/onchain), [Reducto Docs Chat](https://github.com/vsahasi/reducto-docs-chat) |
| Backend and data | Python, FastAPI, Postgres, SQLite, Redis and ARQ, Docker, scraping pipelines | [VeriTone](https://github.com/vsahasi/veritone), [the survivor bias](https://github.com/vsahasi/the-survivor-bias) |
| Other | XRPL, python-pptx, Canvas2D | [onchain](https://github.com/vsahasi/onchain), [deckify](https://github.com/vsahasi/deckify), [the survivor bias](https://github.com/vsahasi/the-survivor-bias) |

## Contact

The best place to reach me is [LinkedIn](https://linkedin.com/in/veersahasi). San Francisco, CA.
