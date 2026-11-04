# Derek Ciula

Hands-on software architect with 15+ years in .NET and Azure. I find the real constraint in AI systems already under way, from agent workflows down to GPU dispatch, and leave evidence your team can rerun.

I make complicated systems tell the truth about how they work. Before I change one, I walk the land: find the real constraint, build the smallest probe that can prove or falsify the story, complete the circuit, and leave evidence for the people who will own it.

## Work with me

Through [Steppe Integrations](https://steppeintegrations.com/), I take selected hands-on engagements with small, fast-moving teams where the lead still ships: getting AI work that has already started through to production, and leaving the people who own it with evidence they can use.

[derek@steppeintegrations.com](mailto:derek@steppeintegrations.com) · [Writing](https://steppeintegrations.com/articles/) · [LinkedIn](https://www.linkedin.com/in/derekciula/)

## What you can check here

| Capability | Public proof |
|---|---|
| Microsoft Agent Framework, .NET 10 | [steppewise](https://github.com/djcdevelopment/steppewise): MAF workflows inside deterministic rails, with human review bound to a hash and an append-only ledger |
| C#/.NET platform work, CI | [planning](https://github.com/djcdevelopment/planning): .NET control plane with a MAF retrospective agent, NATS, ADRs and tests in CI |
| GPU compute dispatch and runtime performance | [vulkancliff](https://github.com/djcdevelopment/vulkancliff), [denning](https://github.com/djcdevelopment/denning), [memsplice](https://github.com/djcdevelopment/memsplice), [b70tools](https://github.com/djcdevelopment/b70tools) |
| Identity and CIAM | Career experience rather than public code: [Auth0 externalization and CIAM consolidation](https://steppeintegrations.com/about/) at production scale |

## Selected evidence

- **[steppewise](https://github.com/djcdevelopment/steppewise)**: Deterministic rails for agentic workflows on .NET 10 and Microsoft Agent Framework. It states what it doesn't do yet: the runtime uses fixtures, not live inference.
- **[vulkancliff](https://github.com/djcdevelopment/vulkancliff)**: A llama.cpp Vulkan throughput cliff traced to a compute-dispatch threshold and moved by dose-response, packaged with the patch, data and harnesses.
- **[denning](https://github.com/djcdevelopment/denning)**: Preregistered local-inference experiments on consumer GPUs, including admission control, cache restoration and corrected results.
- **[memsplice](https://github.com/djcdevelopment/memsplice)**: Moving saved llama.cpp inference state between NVIDIA and Intel GPUs, including a plain account of what doesn't work yet.
- **[b70tools](https://github.com/djcdevelopment/b70tools)**: A Windows workbench for checking GPU telemetry when different layers report different things.

## Upstream work

Status as of 2026-11-04:

- **[ggml-org/llama.cpp #27652](https://github.com/ggml-org/llama.cpp/pull/27652)**: Vulkan dispatch override. Open, not merged.
- **[NousResearch/autoreason #2](https://github.com/NousResearch/autoreason/pull/2)**: Bilevel outer loop. Open, not merged.
- **[thedavidmurray/edgeless-souls](https://github.com/thedavidmurray/edgeless-souls/pulls?q=is%3Apr+author%3Adjcdevelopment)**: Four merged feature PRs.

## Game and community systems

Much of my public work here is Valheim tooling and multiplayer infrastructure: distributed state, netcode and operations for active player communities.

- **[lumberjacks-platform](https://github.com/djcdevelopment/lumberjacks-platform)**: Server-authoritative game transport, gateway services and deployment.
- **[baseline](https://github.com/djcdevelopment/baseline)**: The evidence hub for the Comfy Valheim toolkit.
- **[comfy-quest](https://github.com/djcdevelopment/comfy-quest)**: A Valheim quest system with explicit contracts, rehearsal and release paths.

More at [Community Projects](https://steppeintegrations.com/community-projects/).

## The line through the work

`CAD automation → interactive simulation → factory operations → resource scheduling → identity and platform systems → local AI and agent infrastructure`

The tools have changed. The questions have not: where is the real constraint, what does the system actually know, and what will let the next person run it?
