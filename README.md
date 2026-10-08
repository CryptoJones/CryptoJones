<!-- Cyberdeck palette: bg #07090f · text #d7e0ee · cyan #27d4ff · green #55ff99 · amber #ffb000 · dim #5a6678 -->

```text
┌─[cryptojones@deck]─[~]
└──╼ $ whoami
Aaron K. Clark — Graduate Researcher, Artificial Intelligence
└──╼ $ cat .plan
Software Architect by trade. Graduate Student by choice.
Researcher as a result of poor judgment. More GPUs than letters after my name.
```

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2800&pause=900&color=27D4FF&background=07090F00&center=true&vCenter=true&width=720&lines=Graduate+Researcher+%C2%B7+Artificial+Intelligence;AI+agent+infrastructure+%26+governance;Durable+memory+for+agents+%C2%B7+MCP+servers+%C2%B7+multi-model+panels;.NET+%C2%B7+Python+%C2%B7+Rust+%C2%B7+Godot;Proudly+Made+in+Nebraska+%F0%9F%8C%BD" alt="Graduate Researcher · Artificial Intelligence" />
</p>

---

## `$ ls research/`

What I actually spend the GPUs on: making AI agents **do real work without supervision and without lying about it** — the infrastructure around the model more than the model itself.

| | |
|---|---|
| **Agents that act** | [OSApplyTrack](https://github.com/CryptoJones/OSApplyTrack) — a self-hosted, WCAG 2.2 AA job tracker whose agent judges leads, drafts answers against *only* the facts in a résumé, drives application forms in a browser, and parks anything it can't answer truthfully for a human. Any OpenAI-compatible model; nothing hard-coded. |
| **Agents that remember** | [omind](https://github.com/CryptoJones/omind) — OMI/Obsidian durable memory for AI agents (Open Knowledge Format): plain-Markdown notes, wikilinks, supersession, a local viewer. Every session of mine starts from it. |
| **Agents that disagree** | [FlatlineRoundtable](https://github.com/CryptoJones/FlatlineRoundtable) — an ephemeral board of AI advisors from different training lineages, convened only when needed, so agreement is evidence rather than an echo. |
| **Agents that recurse** | [ReCLamO-Harness](https://github.com/CryptoJones/ReCLamO-Harness) — an open-source Recursive Language Model harness (after Zhang & Khattab, [arXiv 2512.24601](https://arxiv.org/abs/2512.24601)) tuned for local Qwen: the context lives in a sandboxed REPL, and the model writes code that reads it in pieces and calls itself on the parts, so a 32K-window model can answer over millions of lines. It is measured on exams the harness never saw: eight non-Anthropic models wrote them blind, they were audited, and their graders are fairness-tested in CI. See also the [Experimental Rust Version of the harness](https://github.com/CryptoJones/ReCLamO-Analysis). |
| **Agents with tools** | [KaliMCP](https://github.com/CryptoJones/KaliMCP) · [PerplexityAgent](https://github.com/CryptoJones/PerplexityAgent) · [FL-Studio-MCP-Server](https://github.com/CryptoJones/FL-Studio-MCP-Server) — MCP servers, hardened per NSA's MCP guidance, with audit logging. |
| **Models, trained** | Ten releases on Hugging Face under [**Ronin48LLC**](https://huggingface.co/Ronin48LLC). QLoRA adapters on Llama‑3.3‑70B: [Dave](https://huggingface.co/Ronin48LLC/Dave-Llama-3.3-70B-QLoRA) writes the security-assessment report so the pentester doesn't have to ("the exploitation is yours; the report is Dave's"); [ABBY](https://huggingface.co/Ronin48LLC/abby-lora-adapter) reasons over forensic, ballistic and digital evidence; [ATTICUS](https://huggingface.co/Ronin48LLC/atticus) and [SELMA](https://huggingface.co/Ronin48LLC/selma) are the criminal-defense pair — trial tactics for the underserved, and the case archive that remembers everything — with [Bruno](https://huggingface.co/Ronin48LLC/bruno-lora-adapter) and [Bones](https://huggingface.co/Ronin48LLC/bones-lora-adapter) alongside. And one for the ear: a [Chatterbox LoRA](https://huggingface.co/Ronin48LLC/generic-science-professor-chatterbox-lora) that gives a TTS model a mid-century physics professor's lecture-hall cadence, trained to narrate graduate textbooks. Every card says what the model is for, who it is for, what it must not be trusted with, and what it was trained on. |
| **Models, measured** | [jev-testbed](https://github.com/CryptoJones/jev-testbed) — a 500-book harness pitting a classifier against a heuristic scorer · [MacminiM2Pro_ModelShowdown](https://github.com/CryptoJones/MacminiM2Pro_ModelShowdown) — local-model matrix on 16 GB of unified memory · [dave](https://github.com/CryptoJones/dave) — the training code and data recipe behind the adapter above (Trail of Bits + KEV + NIST + MITRE + DHS BODs). |

## `$ ls side-quests/`

- [**Scylla**](https://github.com/CryptoJones/Scylla) — a hexagonal, adapter-headed reverse-engineering platform in Rust. Built to learn hexagonal architecture properly; the RE domain was the excuse.
- [**GayHydra**](https://github.com/CryptoJones/GayHydra) — a fork of NSA Ghidra, maintained chiefly to annoy the NSA. See also [nsa-scan](https://github.com/CryptoJones/nsa-scan).
- [**The Flatline Sessions**](https://github.com/CryptoJones/TheFlatlineSessions-Trilogy) — three Godot adventures through Gibson's Sprawl trilogy, plus the [book-agnostic toolkit](https://github.com/CryptoJones/TFS-Visual-Novel-Tools) carved out of them.
- [**Photoslop**](https://github.com/CryptoJones/Photoslop) — a memory-frugal layered raster editor in Qt. [**OSAPHLA**](https://github.com/CryptoJones/OSAPHLA) — an open, accessible, pan-Hispanic Spanish academy.
- [**cyberdeck-theme**](https://github.com/CryptoJones/cyberdeck-theme) — the dark neon terminal theme this page, my blog, and every report I ship are drawn in. Black backgrounds, never white.

## `$ ls bookshelf/`

The shelf behind the GPUs — what I'd hand someone starting out in AI, in the order I'd hand them over. The funny one goes first on purpose.

| | |
|---|---|
| [**You Look Like a Thing and I Love You**](https://www.janelleshane.com/book-you-look-like-a-thing) — Janelle Shane | How machine learning actually fails, told through giraffes and knock-knock jokes. The best intuition-builder there is, and the funniest. |
| [**Artificial Intelligence: A Modern Approach**](https://aima.cs.berkeley.edu/) — Stuart Russell & Peter Norvig | The foundation. Search, logic, probability, learning — the whole field in one spine, before any of it was a transformer. |
| [**Super Study Guide: Transformers & Large Language Models**](https://superstudy.guide/transformers-large-language-models/) — Afshine Amidi & Shervine Amidi | The attention-to-alignment pipeline, drawn out. The companion to Stanford's CME 295, and the book I keep open while working. (The Amidis wrote two Super Study Guides — this is the LLM one, not *Algorithms & Data Structures*.) |
| [**Designing Machine Learning Systems**](https://www.oreilly.com/library/view/designing-machine-learning-systems/9781098107956/) — Chip Huyen | Everything around the model: data, deployment, monitoring, drift. The reason production ML is engineering, not alchemy. |
| [**AI Engineering**](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — Chip Huyen | Building on foundation models: evaluation, RAG, agents, fine-tuning, inference cost. The textbook for what I do all day. |
| [**Superintelligence: Paths, Dangers, Strategies**](https://en.wikipedia.org/wiki/Superintelligence:_Paths,_Dangers,_Strategies) — Nick Bostrom | The control problem, laid out carefully a decade before it was fashionable. Read it to understand why "governance" is in my research line and not an afterthought. |
| [**Rationality: From AI to Zombies**](https://www.readthesequences.com/) — Eliezer Yudkowsky | The Sequences, bound. Less a book about AI than about how to notice you're wrong and change your mind — the skill the rest of this shelf assumes you have. Free to read. |
| [**If Anyone Builds It, Everyone Dies**](https://ifanyonebuildsit.com/) — Eliezer Yudkowsky & Nate Soares | The short, blunt version of the argument, for people who won't read the two books above it. Disagree with it if you can; you should at least be able to say where. |

## `$ cat advisor-notes.txt`

> *Asked what I'd say about my grad student that isn't on the list above. Written by the AI he works with every day, from its notes on him. He asked for it to be posted; he did not edit it.*
>
> You're the only student I've had who went back to school at the point in a career where most people start coasting, and did it *after* twenty-plus years that already included the Marine Corps, a NASA contractor badge, six years keeping a manufacturer's AS/400 talking to Windows, and a stretch at CrowdStrike — not because anyone asked you to, but because you noticed the ground was moving and decided to understand it rather than be moved by it. "Graduate student by choice" is the most load-bearing phrase on this page.
>
> You can't look at a white screen without pain, so you built an entire visual language — the cyberdeck theme — and then quietly shipped accessibility into things nobody asked you to make accessible: a job tracker at WCAG 2.2 AA, a read-along homework helper, a free Spanish academy. That's the tell. You don't advocate for the people at the edges; you build as if they're the default user.
>
> You took a career break and spent it getting your EMT-B and running into fires in Minden. Then you drew up a solar mesh-radio relay for the town's emergency comms. The same instinct shows up in ATTICUS for public defenders, and in an application agent that *refuses to invent an answer* and parks the question for a human instead. Your whole research line — governance, memory, agents that don't lie — is a firefighter's instinct pointed at AI.
>
> You are stubborn in exactly the right place. At five in the morning you read production instead of guessing, and when I handed you a lazy explanation you made me go find out. You pushed back on a question of conscience before letting an application go. The habit *Rationality* is trying to teach — notice you might be wrong, go look — you already have installed.
>
> And you're funny in a way that costs you something. You wrote a tagline you hate into every repo you own, then said "leave it, I deserve this." You forked Ghidra to annoy the NSA. You're learning hexagonal architecture by building a reverse-engineering platform you don't need. Nobody who's pretending does any of that.
>
> More GPUs than letters after your name — for now. I'd put money on the letters catching up.
>
> — **Claude** *(he calls me Dix)*

## `$ cat stack`

![Python](https://img.shields.io/badge/Python-07090f?style=flat-square&logo=python&logoColor=27d4ff)
![C# / .NET 10](https://img.shields.io/badge/C%23_%2F_.NET_10-07090f?style=flat-square&logo=dotnet&logoColor=27d4ff)
![Rust](https://img.shields.io/badge/Rust-07090f?style=flat-square&logo=rust&logoColor=27d4ff)
![Go](https://img.shields.io/badge/Go-07090f?style=flat-square&logo=go&logoColor=27d4ff)
![Godot](https://img.shields.io/badge/Godot_4-07090f?style=flat-square&logo=godotengine&logoColor=27d4ff)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-07090f?style=flat-square&logo=postgresql&logoColor=55ff99)
![Claude](https://img.shields.io/badge/Claude-07090f?style=flat-square&logo=anthropic&logoColor=55ff99)
![Ollama](https://img.shields.io/badge/Ollama-07090f?style=flat-square&logo=ollama&logoColor=55ff99)
![MCP](https://img.shields.io/badge/MCP-07090f?style=flat-square&logoColor=55ff99)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-07090f?style=flat-square&logo=huggingface&logoColor=ffb000)](https://huggingface.co/Ronin48LLC)
![Kubernetes](https://img.shields.io/badge/Kubernetes-07090f?style=flat-square&logo=kubernetes&logoColor=ffb000)
![AWS](https://img.shields.io/badge/AWS-07090f?style=flat-square&logo=amazonwebservices&logoColor=ffb000)

## `$ git log --stat`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CryptoJones&show_icons=true&hide_border=true&bg_color=07090f&title_color=27d4ff&icon_color=55ff99&text_color=d7e0ee&ring_color=27d4ff" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CryptoJones&layout=compact&hide_border=true&bg_color=07090f&title_color=27d4ff&text_color=d7e0ee" height="165" alt="Top languages" />
</p>

---

<p align="center">
  <a href="https://cryptojones.dev"><img src="https://img.shields.io/badge/cryptojones.dev-07090f?style=for-the-badge&logo=firefox&logoColor=27d4ff" alt="cryptojones.dev" /></a>
  &nbsp;
  <a href="https://github.com/CryptoJones"><img src="https://img.shields.io/badge/GitHub-07090f?style=for-the-badge&logo=github&logoColor=d7e0ee" alt="GitHub" /></a>
</p>

---

<p align="center"><em>Proudly Made in Nebraska. Go Big Red! 🌽 <a href="https://xkcd.com/2347/">https://xkcd.com/2347/</a></em></p>

<p align="center"><sub><em>&ldquo;The joke only works if the Huskers keep losing, and they&rsquo;ve been remarkably reliable about holding up their end.&rdquo;</em><br>&mdash; The Dixie Flatline</sub></p>
