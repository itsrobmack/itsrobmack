# Rob McElvenny

**AI systems and platform engineer focused on agent infrastructure, realtime voice AI, governed tool access, evals, workflow orchestration, and production reliability.**

I build the infrastructure layer between AI ideas and systems that real teams can operate.

My background spans defense, autonomous vehicle, cybersecurity, and production software environments where secure delivery, traceability, uptime, and operational clarity mattered.

Current focus: production shaped AI infrastructure, realtime voice agents, human reviewed automation, governed tool access, evals, retrieval flows, agent workflow systems, and platform tooling that makes AI useful outside of demos.

Public proof index: [skewuo.com/proof](https://skewuo.com/proof)

## What I build

* **AI workflow infrastructure:** intent intake, tool execution, context handling, review gates, approval paths, eval hooks, recoverable automation, and audit friendly run state.
* **Realtime voice AI:** WebSocket voice APIs, Deepgram streaming STT, ElevenLabs TTS, OpenAI TTS, Coqui TTS, Twilio MediaStreams, turn control, interruption handling, response locks, speech queues, tool confirmation guards, and latency aware session state.
* **Governed agent systems:** connector boundaries, role checks, scope checks, approval gates, run logs, policy reasons, and human review before high risk actions.
* **Cloud native platforms:** Kubernetes, GitOps, CI and CD, Terraform, Ansible, container delivery, secure operational workflows, and production support.
* **Operator grade product surfaces:** dashboards, workflow builders, control rooms, execution ledgers, and interfaces that show what the system is doing.

## Featured proof

These are public proof repos. They are meant to show how I think about AI systems, control layers, runtime state, review gates, evals, and operational visibility.

### [agent-runner-control-plane](https://github.com/itsrobmack/agent-runner-control-plane)

[![CI](https://github.com/itsrobmack/agent-runner-control-plane/actions/workflows/ci.yml/badge.svg)](https://github.com/itsrobmack/agent-runner-control-plane/actions/workflows/ci.yml)

A Bun and TypeScript control plane skeleton for AI agent runs, tool calls, approval checkpoints, policy checks, run state, and audit logs.

It models the infrastructure layer AI workflows need before touching real systems: tool registries, policy checks, high risk approval gates, auditable transitions, and reviewable execution.

Runtime proof is documented in the repo and covers low risk execution, high risk approval pause, approval grant, and audit trail behavior.

It also includes an operational eval harness that checks low risk execution, medium risk planning, high risk approval pauses, approved execution, approval metadata, and required audit events.

### [realtime-voice-agent-gateway](https://github.com/itsrobmack/realtime-voice-agent-gateway)

[![CI](https://github.com/itsrobmack/realtime-voice-agent-gateway/actions/workflows/ci.yml/badge.svg)](https://github.com/itsrobmack/realtime-voice-agent-gateway/actions/workflows/ci.yml)

A Bun and TypeScript realtime voice agent gateway skeleton for streaming turn state, interruption handling, provider adapters, audit events, and runtime evals.

It models the control layer around realtime voice AI: partial and final transcripts, agent response boundaries, streamed text to speech, user barge in, swappable STT and TTS providers, observable session state, and evals for voice runtime behavior.

Runtime proof covers final transcript to speech, interruption during active speech, partial transcript behavior, multi-partial finalization, clean session ending, API health, and eval endpoint behavior.

### [mcp-ops-gateway](https://github.com/itsrobmack/mcp-ops-gateway)

[![CI](https://github.com/itsrobmack/mcp-ops-gateway/actions/workflows/ci.yml/badge.svg)](https://github.com/itsrobmack/mcp-ops-gateway/actions/workflows/ci.yml)

A governed tool access gateway skeleton for AI agent tools, role and scope policy, approval gates, audit logs, and enterprise connector boundaries.

It shows the layer between agent tool use and real company systems: connector ownership, access checks, high risk review, policy reasons, and auditable execution.

Runtime proof is documented in the repo and covers allowed connector requests, approval required connector requests, role checks, scope checks, policy reasons, audit trails, duplicate approval prevention, denied request handling, and unknown connector safety.

### [retrieval-context-gateway](https://github.com/itsrobmack/retrieval-context-gateway)

[![CI](https://github.com/itsrobmack/retrieval-context-gateway/actions/workflows/ci.yml/badge.svg)](https://github.com/itsrobmack/retrieval-context-gateway/actions/workflows/ci.yml)

A Bun and TypeScript retrieval context gateway skeleton for permission aware context assembly, citations, freshness labels, audit events, and runtime evals.

It models the retrieval layer production agents need before company knowledge enters a prompt: actor scopes, document policy, citation output, stale context warnings, no-context fallback, and audit events for filtered sources.

Runtime evals cover scope filtering, allowed citation retrieval, stale context labels, answer safety, no-context fallback, result caps, citation output, and audit trail behavior.

### Realtime voice AI systems

I have built custom realtime voice systems with provider flexible STT, LLM, and TTS stacks.

Relevant pieces include Deepgram streaming STT, ElevenLabs TTS, OpenAI TTS, Coqui TTS, native device speech modes, WebSocket sessions, Twilio MediaStreams, SIP experiments, turn control, interruption handling, response locks, speech queues, confirmation guards, and latency aware session state.

## Current direction

* Remote Senior or Staff AI platform engineering.
* Agent infrastructure and workflow systems.
* Retrieval and context engineering for production agents.
* Realtime AI and voice infrastructure.
* Internal AI platforms with human review and auditability.
* Platform, SRE, and developer infrastructure for AI products.
* AI workflow automation for real business operations.

## Strong fit

* AI Platform Engineer
* AI Infrastructure Engineer
* Agent Infrastructure Engineer
* Realtime AI Infrastructure Engineer
* Platform Engineer for AI products
* Forward Deployed Engineer for AI infrastructure or developer tooling
* SRE or DevOps Engineer for remote AI teams
* Internal platform, automation, and reliability engineering roles

## Tools and systems

`Kubernetes` · `GitOps` · `CI and CD` · `Linux` · `Terraform` · `Ansible` · `AWS` · `Bash` · `Python` · `Go` · `TypeScript` · `Bun` · `Bazel` · `Jenkins` · `Docker` · `PostgreSQL` · `Redis` · `WebSockets` · `Retrieval` · `Context engineering` · `AI workflow orchestration` · `Realtime voice APIs` · `Deepgram` · `ElevenLabs` · `OpenAI TTS` · `Coqui TTS` · `Twilio MediaStreams`

## Operating principles

* Ship the smallest useful system first.
* Keep human approval visible when AI touches real work.
* Prefer boring reliability over fragile cleverness.
* Make state, ownership, failure, and recovery obvious.
* Use proof to earn trust.

## Links

* Proof index: [skewuo.com/proof](https://skewuo.com/proof)
* Portfolio: [skewuo.com](https://skewuo.com)
* LinkedIn: [linkedin.com/in/heyrobbb](https://www.linkedin.com/in/heyrobbb)
* X: [@skewuo](https://x.com/skewuo)
* Email: [robert.mcelvenny@gmail.com](mailto:robert.mcelvenny@gmail.com)
