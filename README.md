<div align="center">

<a href="https://github.com/vsahasi">
  <img src="https://raw.githubusercontent.com/vsahasi/vsahasi/main/assets/banner.svg" width="100%" alt="Veer Sahasi" />
</a>

<a href="https://github.com/vsahasi">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=900&color=10B981&center=true&vCenter=true&width=640&lines=EECS+%2B+Business+%40+UC+Berkeley+M.E.T.;I+build+AI+systems+end+to+end;retrieval+%C2%B7+evals+%C2%B7+agents+%C2%B7+multimodal+ML" alt="EECS + Business @ UC Berkeley M.E.T. I build AI systems end to end: retrieval, evals, agents, multimodal ML." />
</a>

</div>

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

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,ts,nextjs,react,fastapi,pytorch,postgres,supabase,docker,vercel,tailwind,git&perline=12" alt="Python, TypeScript, Next.js, React, FastAPI, PyTorch, Postgres, Supabase, Docker, Vercel, Tailwind, Git" />
</p>

Also: Anthropic and OpenAI APIs · Pinecone · FAISS · pgvector · Turbopuffer · Whisper · Browser Use · XRPL

## Contact

The best place to reach me is [LinkedIn](https://linkedin.com/in/veersahasi). San Francisco, CA.
