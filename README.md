  <div align="center">

  # 🤖 Maniraj-1.0

  *State-of-the-art human language model, fine-tuned for AI engineering.
  Deployed in Schiphol, NL since 1999. Currently serving traffic at [aXite Security Tools](https://thecr7guy2.github.io).*

  [portfolio](https://thecr7guy2.github.io) · [linkedin](https://www.linkedin.com/in/manirajsai/) · [email](mailto:manirajadapa@gmail.com)

  </div>

  ---

  ## Model Specs

  | | |
  |---|---|
  | **Architecture** | Carbon-based · bipedal · single-threaded |
  | **Parameters** | ~86 billion neurons (most untrained) |
  | **Context window** | 16h · degrades sharply after 22:00 unless caffeinated |
  | **Training data** | Production incidents · open-source repos · Champions League replays · Stack Overflow circa 2018 |
  | **Languages** | Python, English, Telugu, SQL, fluent Bash, broken Dutch |
  | **License** | Available for hire (commercial use permitted) |
  | **Jersey number** | 7 — non-negotiable |

  ## Benchmarks

  | Eval | Score | Notes |
  |---|---|---|
  | Shipping production AI | **5 / 5 apps** | AX-Office.ai is live |
  | Pretraining from scratch | **18B tokens** | beat GPT-2 on most benchmarks |
  | Letting an LLM trade real money | **2× / week** | Claude Opus does the heavy lifting tbh |
  | Scoring football technique with CV | **⚽** | 3D skeleton viz in Three.js, ask me about it |
  | Sleeping reasonable hours | **0.3 / 5** | known limitation, see § |

  ## Recent Fine-Tuning Runs

  | Run | Description |
  |---|---|
  | **[`sec-filing-trader-v1`](https://bramble-hickory-105.notion.site/I-Built-a-Bot-That-Reads-SEC-Filings-and-Lets-Claude-Opus-Manage-My-Portfolio-323a490c257c81739909cb792452185a)** | Claude Opus reads insider
  filings twice a week and runs a real portfolio. Unsupervised. So far, solvent. |
  | **[`gpt2-124M-from-scratch`](https://bramble-hickory-105.notion.site/How-I-trained-an-LLM-from-scratch-and-finetuned-it-271a490c257c80718ffcf42b6d90e962)** | 18B curated tokens. Beat the original on most benchmarks.
   Wrote up the bugs that ate weeks. |
  | **[`ax-office-ai`](https://bramble-hickory-105.notion.site/AX-Office-ai-How-We-Built-Local-AI-Into-the-Heart-of-Our-Office-323a490c257c81beb4e4e022ded8bfcc)** | On-prem LLM platform · 5 production apps · 0 cloud
  dependencies · 1 very nervous GPU. |
  | `ajax-shot-analyzer` | CV + 3D skeleton viz scoring a footballer's shot. (No, I won't review yours. Maybe.) |
  | `esrgan-with-uncertainty` | Master's thesis. Medical-image super-resolution with calibrated confidence — "the AI says so" isn't a diagnosis. |

  ## Known Limitations & Biases

  - Strong prior that this will be "a quick refactor." It will not.
  - Refuses to stop talking about Ronaldo when prompted with `cr7`.
  - Hallucinates Friday deploys are safe. They are not.
  - Latency spikes when a meeting could have been a Slack message.
  - Will not use Jira. Graceful degradation in progress.
  - Dark mode bias. Light mode triggers fallback to mild grumpiness.

  ## How To Get Best Results

  **Prompt with:** a real problem · honest constraints · coffee.
  **Avoid:** vague tickets · five-meeting days · "just a quick question."
  **Temperature:** 0.7 by default; 0.2 before deploys; 1.0 at hackathons.

  ## Recommended Runtime

  ```
  Python  ·  PyTorch  ·  vLLM  ·  HuggingFace  ·  Anthropic SDK
  FastAPI  ·  Docker  ·  Postgres + pgvector  ·  RunPod  ·  GH Actions
  ```

  ## System Prompt

  > *Build useful systems, not demo-ware.
  > Ship the boring parts well.
  > Read the logs.*

  ---

  <div align="center">
  <sub><i>Model card v1.0 · weights not openly released · happy to chat over coffee ☕</i></sub>
  </div>
