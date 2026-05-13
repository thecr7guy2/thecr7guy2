<div align="center">
  <img src="./assets/terminal-header.svg" alt="Terminal-style banner for Maniraj Sai" width="100%" />
</div>

```bash
maniraj@github:~$ ./boot
[ok] production llm systems
[ok] agent workflows
[ok] evaluation harnesses
[ok] training pipelines
[ok] on-prem deployments for teams that do not want their data leaving the building
```

<div align="center">

[portfolio](https://thecr7guy2.github.io) | [linkedin](https://www.linkedin.com/in/manirajsai/) | [email](mailto:manirajadapa@gmail.com)

<img src="https://img.shields.io/badge/location-schiphol,_nl-08110c?style=for-the-badge&labelColor=05080a&color=123122" />
<img src="https://img.shields.io/badge/company-aXite_security_tools-08110c?style=for-the-badge&labelColor=05080a&color=123122" />
<img src="https://img.shields.io/badge/status-open_to_opportunities-08110c?style=for-the-badge&labelColor=05080a&color=1f8f4e" />

</div>

---

## `cat about.txt`

I build LLM systems for real environments, not demo environments.

That means latency budgets, evaluation gates, messy data, retrieval that fails in interesting ways, models that need to run locally, and enough observability to explain what broke at 2 a.m.

The work I like most sits in the unglamorous layer between research and production: the part where ideas either become reliable systems or quietly die.

## `tail -f now.log`

```text
> building AX-Office.ai
  on-prem LLM platform currently powering 5 production apps

> designing an agent eval framework
  so model swaps do not turn into Friday-night incidents

> benchmarking 10+ open-source models
  for privacy-sensitive and security-heavy workflows
```

## `ls selected_systems/`

```text
AX-Office.ai/
sec-filing-trader/
gpt2-124M-from-scratch/
ajax-shot-analyzer/
esrgan-with-uncertainty/
```

### `./selected_systems/AX-Office.ai`
Local-first LLM platform for a security company that cannot rely on outside APIs. Shared infra, five production apps, one evaluation layer, zero external calls.

`vLLM` `RAG` `ASR` `OCR` `FastAPI`  
[read write-up](https://bramble-hickory-105.notion.site/AX-Office-ai-How-We-Built-Local-AI-Into-the-Heart-of-Our-Office-323a490c257c81beb4e4e022ded8bfcc)

### `./selected_systems/sec-filing-trader`
Agent that reads insider SEC filings twice a week and manages a live portfolio with minimal supervision. Slightly unhinged, still solvent.

`Anthropic SDK` `agents` `Python` `Postgres`  
[read write-up](https://bramble-hickory-105.notion.site/I-Built-a-Bot-That-Reads-SEC-Filings-and-Lets-Claude-Opus-Manage-My-Portfolio-323a490c257c81739909cb792452185a)

### `./selected_systems/gpt2-124M-from-scratch`
Pretrained a 124M GPT-2 on 18B curated tokens, beat the original model on most benchmarks, then instruction-tuned it on top.

`PyTorch` `pretraining` `SFT` `distributed training`  
[read write-up](https://bramble-hickory-105.notion.site/How-I-trained-an-LLM-from-scratch-and-finetuned-it-271a490c257c80718ffcf42b6d90e962)

### `./selected_systems/ajax-shot-analyzer`
Computer-vision pipeline that scores a footballer's shooting technique and visualizes 3D skeleton reconstruction in the browser.

`MediaPipe` `OpenCV` `Three.js`

### `./selected_systems/esrgan-with-uncertainty`
Master's thesis on medical-image super-resolution with calibrated uncertainty, because "the model says so" is not a clinical standard.

`PyTorch` `ESRGAN` `Bayesian deep learning`

## `grep -R "writing" ./notes`

- [How I trained an LLM from scratch and fine-tuned it](https://bramble-hickory-105.notion.site/How-I-trained-an-LLM-from-scratch-and-finetuned-it-271a490c257c80718ffcf42b6d90e962)
- [AX-Office.ai: building local AI into the heart of an office](https://bramble-hickory-105.notion.site/AX-Office-ai-How-We-Built-Local-AI-Into-the-Heart-of-Our-Office-323a490c257c81beb4e4e022ded8bfcc)
- [A trading bot that reads SEC filings, run by Claude Opus](https://bramble-hickory-105.notion.site/I-Built-a-Bot-That-Reads-SEC-Filings-and-Lets-Claude-Opus-Manage-My-Portfolio-323a490c257c81739909cb792452185a)

## `env | grep TOOLBOX`

```text
LLM_SYSTEMS=Python, vLLM, HuggingFace, Anthropic SDK, RAG
TRAINING=PyTorch, SFT, distributed training
BACKEND=FastAPI, Docker, Linux
DATA=PostgreSQL, pgvector
CLOUD=AWS, GCP, GitHub Actions
```

---

```bash
maniraj@github:~$ echo "Build useful systems. Ship the boring parts well. Read the logs."
Build useful systems. Ship the boring parts well. Read the logs.
```
