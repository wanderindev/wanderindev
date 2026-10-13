<p align="center">
  <img src="https://github.com/wanderindev/wanderindev/blob/master/assets/about-cover.png" />
</p>
<p align="center"><b>Building AI-native systems where agents own the work, and I stay the editor.</b></p>

# Hi, I'm Javier Feliu 👋

**Engineering Manager & Senior Full-Stack Engineer** based in Panama City. I lead a 10-person engineering team at a private ad tech company, splitting my time between hands-on building and leadership. I've shipped high-performance, scalable systems for years, and increasingly I build the AI systems that let a small team deliver like a much larger one.

The thread through my whole career is simpler than any stack:

> **If we're doing something manually, that's a bug, so fix it.**

A mentor framed it that way years ago, and it stuck. I spent over a year leading process-automation efforts: Airflow pipelines and Chrome extensions that wired internal systems into platforms like Notion, Salesforce, and Linear, turning manual toil into software that ran itself. Back then, LLMs were too early to lean on. Now they're genuinely capable and expert at tool use, which makes that principle *more* true than ever: a far larger share of real work can be owned by software, with far less effort. That's what I build now.

## 🏭 What I'm building on the side

**[Managed Agents](https://github.com/wanderindev/managed-agents): agents that work while I sleep.**
A durable-log orchestrator that runs Claude Code in disposable Docker sandboxes on a DigitalOcean droplet. It picks up production Sentry issues, investigates them against the real code, writes a test that fails before the fix and passes after, and opens a draft PR. Every fix is then attacked by a fresh-context adversarial reviewer that has to fail to refute it before the PR leaves draft. A nightly job audits each repo's memory file against what the week's runs actually established, and a weekly driver works a content-pipeline task queue. Nothing merges without me. Python · PostgreSQL · Docker · GitHub App · Sentry.

**[Panama in Context](https://github.com/wanderindev/ai-powered-content-generation-engine): an AI content factory.**
A bilingual educational platform where one topic suggestion fans out through parallel AI pipelines into published articles, narrated lesson videos, study guides, and social posts. Agents do the work; a human approves at every gate. Claude Opus 5, Sonnet 5 and Haiku 4.5 routed by task, Gemini for image generation, claims-level fact-checking, DeepL translation, ElevenLabs narration, and a from-scratch narrated-video pipeline (Chromium to ffmpeg). FastAPI · React · PostgreSQL.

**[Agent Ready](https://github.com/wanderindev/agent-ready): making an existing codebase safe to hand to agents.**
A Claude Code plugin marketplace that walks a project through the whole pipeline: bootstrap the repo for agent work, audit it area by area into a labeled and agent-classified backlog, then resolve that backlog autonomously where the audit proved the work tractable and in pair-mode where judgment is load-bearing. A companion guardrails plugin installs the safety floor: destructive actions denied, production gated, secrets protected. Extracted from a real audit-to-autonomy run that took a stalled, vibe-coded site to 138 issues closed and 165 PRs merged.

**[PIC Companion](https://github.com/wanderindev/research-companion-extension): an API around a tool that doesn't have one.**
A Chrome extension that drives Claude's deep-research mode unattended, turning a browser UI into an automation surface that feeds the content factory.

## 🤖 How I work with AI

I don't treat AI as a helper bolted onto a human-paced process. I build the **leverage** that lets agents own whole workflows: the skills, context, guardrails, and self-verifying checks. I keep humans in the loop where judgment matters, and nothing ships open-loop.

I'm currently leading my team's AI-adoption effort: moving us from "AI writes code faster" to AI woven across the core workflows we run every day, safely and with shared tooling and guardrails, so the whole team's ceiling rises, not just mine. In practice that means wiring models into the systems the work already lives in, over MCP and APIs: Sentry, Linear, Notion, Bitbucket, Google Ad Manager, and our own services, so an agent can pick up a ticket, root-cause it against the codebase, and open the PR without a human relaying context between tools.

## 🧰 Areas of Expertise

- **AI-Native Engineering**  
  Agentic pipelines, MCP, orchestrating Claude models (Opus 5, Sonnet 5, Haiku 4.5) routed by task alongside Gemini for image work, closed-loop verification with adversarial review, durable run logs that survive a killed sandbox, and prompt / context / skill design. I build the tooling that lets agents own end-to-end work.

- **Distributed Systems & Performance**  
  Ultra-low-latency APIs with sub-50ms response times across multiple AWS regions, using intelligent caching and cross-region deployment for fraud-detection and ad-tech workloads.

- **Edge Computing & CDN**  
  CloudFront edge functions and KeyValueStore solutions for real-time request filtering and access control, at sub-millisecond performance across thousands of domains.

- **Process Automation & Orchestration**  
  Airflow workflows automating business processes, onboarding, and infrastructure updates; Chrome extensions with distributed task execution across third-party platforms.

- **Full-Stack Development**  
  FastAPI, Flask, Django, React, Express, PostgreSQL, and Redis, plus Docker and cloud infrastructure (AWS, DigitalOcean, CloudFront). I stand it up, ship it, and run it.

- **Infrastructure & DevOps**  
  Self-hosted Sentry for production monitoring, major Jenkins CI/CD overhauls, declarative pipelines, and build optimization.

## 👋 Let's connect

🌐 [feliu.dev](https://feliu.dev) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/javierfeliu/)
