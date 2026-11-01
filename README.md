### Tony Tong · Applied AI, Singapore

Applied AI work for businesses: find the real problem, prototype the risky assumption, measure it, then take it to production.
CTO of [Mindreader](https://tonytonggg.com/work/mindreader), an AI sales intelligence platform used by teams at AIA, CIMB and Manulife, and of [The Modern Shrine](https://www.themodernshrine.com).
Past work with Rakuten, Google Crowdsource × Explore ML and Omdena.

**Site:** [tonytonggg.com](https://tonytonggg.com) · **LinkedIn:** [tonytongtszhin](https://www.linkedin.com/in/tonytongtszhin)

#### Selected work

| Work | What was measured | Code | Stack |
|---|---|---|---|
| [GraphRAG vs hybrid RAG on 13,000 private notes](https://tonytonggg.com/writing/graphrag-vs-hybrid-rag-on-private-notes) | Graph alone lost to hybrid search (p = 0.04); graph on top of hybrid helped time-based questions | [graphrag-vs-hybrid-rag-eval](https://github.com/s0yabean/graphrag-vs-hybrid-rag-eval) | Python · Neo4j 5.26 · Claude Haiku 5.5 · bge-m3 on Ollama · BM25 + RRF |
| [Evals for an AI web-research step](https://tonytonggg.com/writing/evals-ai-web-research-crm) | Wrong matches cut from 12 in 60 to 2 in 60, and 0 in 23 on a fresh holdout | [llm-research-eval-harness](https://github.com/s0yabean/llm-research-eval-harness) | Python · pytest · JSONL fixtures · Claude Haiku, Sonnet, Opus and Fable |
| [Benchmarking The Modern Shrine's AI agent](https://tonytonggg.com/writing/benchmarking-the-modern-shrine-agent) | 36.7% against a 25% random baseline, with a ranked list of fixes | [mingli-bench-harness](https://github.com/s0yabean/mingli-bench-harness) | TypeScript · Vercel AI SDK · Vercel AI Gateway · Zod · YAML agent configs |
| Gated LLM pipeline | Code owns the flow; a cheap classifier gates each step and only unsure items reach the LLM | [gated-llm-pipeline](https://github.com/s0yabean/gated-llm-pipeline) | Python · Jev 1.13.0 · Claude Opus 5.5 |
| Agent approval queue | Agents submit drafts; a human approves, edits or rejects before anything is sent | [agent-approval-queue](https://github.com/s0yabean/agent-approval-queue) | Next.js 16 · TypeScript · Supabase · Postgres RLS · Vitest |
| LLM provider resilience | Fallback chains, credential pools and circuit breakers, with outage runbooks | [llm-provider-resilience](https://github.com/s0yabean/llm-provider-resilience) | Python standard library · OpenAI-compatible APIs · Ruff |
| [From a moving brief to 20 years of trusted macro data](https://tonytonggg.com/writing/macro-indicator-pipeline-from-a-moving-brief) | 192,971 rows from a client brief that kept moving; monthly data found 29.4 days early, and the health check that now catches it | [macro-regime-data-pipeline](https://github.com/s0yabean/macro-regime-data-pipeline) | Python · SQLite · FRED API · yfinance · CoinGecko API |
| [Scheduled AI jobs for cents](https://tonytonggg.com/writing/scheduled-ai-jobs-for-cents) | Jobs moved off a US$99-a-month service; each run now costs cents | [scheduled-claude-jobs](https://github.com/s0yabean/scheduled-claude-jobs) | Bash · launchd · Claude Code CLI · ShellCheck |
| [An AI quality gate for every article](https://tonytonggg.com/writing/an-ai-quality-gate-for-every-article) | A gate measured against the author's own verdicts, with a ledger that forces re-scoring after edits | [article-quality-gate](https://github.com/s0yabean/article-quality-gate) | TypeScript · TypeSafe SDK · Jev 1.13.0 · gray-matter · Git hooks |
| Sayura voice app | Shipped to the App Store: speech-to-text, a fast LLM with a strong fallback | [sayura-app](https://github.com/s0yabean/sayura-app) | Expo / React Native · Groq llama-3.1-8b-instant · Azure OpenAI gpt-4o · AssemblyAI · Firebase |
| Persona sales copilot | Mindreader demo for bank relationship managers, on synthetic data | [persona-sales-copilot](https://github.com/s0yabean/persona-sales-copilot) | React · Vite · Tailwind CSS · TypeScript · gpt-4o-mini |
| BERT serving API | A 2021 Mindreader serving stack, reviewed: tokenizer reload cut from 12.3 ms to 0.11 ms per request | [bert-tfserving-api](https://github.com/s0yabean/bert-tfserving-api) | Flask · Gunicorn · TensorFlow Serving 2.15 · Docker · Hugging Face tokenizers |
| [Fully private AI for a 50-person firm](https://tonytonggg.com/writing/fully-private-ai-knowledge-base) | Service levels and a phased study before building the app | — | RAGFlow · Ollama · qwen3.5 · bge-m3 · Docker |
| [Live UAT with insurance advisers](https://tonytonggg.com/work/forward-deployed-ai) | Generic AI insight turned into a role-specific coaching workflow | — | Live UAT · adviser interviews · AI role-play · Gamma Slides · onboarding workshops |
| [Google Crowdsource × Explore ML](https://tonytonggg.com/work/google-crowdsource-explore-ml) | Machine learning taught to 900 non-technical learners across Asia | — | TensorFlow Playground · Teachable Machine · Quick, Draw! |

**Earlier work:** [twitter_mbti_ml](https://github.com/s0yabean/twitter_mbti_ml) (2017, predicting personality type from social posts) and [mbti_classifier_streamlit](https://github.com/s0yabean/mbti_classifier_streamlit) (2024), the text-classification thread that led to Mindreader · [footprint](https://github.com/s0yabean/footprint) (Berkeley hackathon, 2017).

#### Stack

Python · TypeScript · Next.js · LLM evals · RAG and GraphRAG (Neo4j) · Claude and OpenAI APIs · MCP · local models
