# Gavita Harshit 

**AI systems, agents and developer tooling.** 19, B.Tech CSE (AI & Data Science) student in Pune, India. Open to work.

I fix real bugs in AI-agent and developer tooling, then write down what I verified and what I did not.

[LinkedIn](https://www.linkedin.com/in/harshit-gavita-bb90b3202) | [Email](mailto:Harshit.gavita@gmail.com) | [GitHub](https://github.com/harshitgavita-07)

---

## Projects

| Project | What it is | Honest status |
|---|---|---|
| [**AIOS**](https://github.com/harshitgavita-07/Aios) | Python core that turns a goal into a plan, runs it, and verifies the result. File and directory checks look at the real disk instead of trusting the agent's report. Run `python examples/verified_delegation.py` to see an agent's false "done" get caught. | Early beta. Real execution covers terminal steps only. No CI yet. The desktop app is not fully tested. |
| [**Anthropic performance take-home**](https://github.com/harshitgavita-07/Anthropic_challenge-my-solution-) | My solution to Anthropic's public kernel-optimization take-home: about 147K down to about 14.4K simulated cycles (10.2x) | Did not reach the benchmark's tighter cycle thresholds; the repo says so |
| [**micrograd-JAX**](https://github.com/harshitgavita-07/micrograd_JAX) | Karpathy's micrograd idea rebuilt with JAX transforms (`grad`, `jit`, `vmap`) as a learning project | Fork of the original, my JAX version is in the notebook |
| [**ML Fundamentals**](https://github.com/harshitgavita-07/ML_fundamentals) | 19 notebooks on core ML algorithms | Learning notes, not a library |
| [**agent-canvas**](https://github.com/harshitgavita-07/agent-canvas) | Typed Python DSL for visual lessons, with a test suite (312 tests passed in local verification; requires Python 3.12+) | Locally verified; not a deployment claim |

---

## Open source contributions

**Merged**

- [E2B #1912](https://github.com/e2b-dev/E2B/pull/1912): stopping a filesystem watch surfaced as a timeout error
- [Meta Muse gadget SDK #3](https://github.com/facebookincubator/muse-gadget-sdk/pull/3): a command could hang after its timeout because a detached process held the output pipes open
- [AgentPhone MCP #74](https://github.com/AgentPhone-AI/agentphone-mcp/pull/74): the documented `--port` flag was ignored
- [tester-army/e2e #734](https://github.com/tester-army/e2e/pull/734): migration docs said `toContain` matched Playwright when it did not

**Fixes adopted or credited by maintainers**

- [gstack #3001](https://github.com/garrytan/gstack/pull/3001) and [#2997](https://github.com/garrytan/gstack/pull/2997): incorporated into the maintainer's merged [PR #3013](https://github.com/garrytan/gstack/pull/3013)
- [AlphaFold 3](https://github.com/google-deepmind/alphafold3/commit/f43dfb8c8b872539c5eb37103ee85f67969c97d8): invalid chain IDs passed validation and failed later; the maintainer commit credits the report

**Open for review**

- [Hugging Face tau #762](https://github.com/huggingface/tau/pull/762), [Composio #4700](https://github.com/ComposioHQ/composio/pull/4700), [llama-cookbook #1081](https://github.com/meta-llama/llama-cookbook/pull/1081), [fvcore #159](https://github.com/facebookresearch/fvcore/pull/159), [TensorDict #1839](https://github.com/pytorch/tensordict/pull/1839), [Ollama #18745](https://github.com/ollama/ollama/pull/18745), [AgentPhone MCP #79](https://github.com/AgentPhone-AI/agentphone-mcp/pull/79)

**Tally:** 34 pull requests opened in other people's repositories as of 6 Oct 2026 ([full list](https://github.com/search?q=author%3Aharshitgavita-07+type%3Apr+-user%3Aharshitgavita-07&type=pullrequests)): 4 merged, 20 open, 10 closed without merge (including the 2 gstack PRs whose fixes were incorporated). Forks and my own repos are not counted. Snapshot updated by hand.

---

## Research

**PTF: Protection Toward Future.** An empirical incident study of autonomous AI agent behaviour on a personal workstation, with a proposal for infrastructure-level safety architecture. [Read it on SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6472278).

---

## Activity

[![Contribution graph](https://ghchart.rshah.org/2ea043/harshitgavita-07)](https://github.com/harshitgavita-07)

---

## Let's talk

I'm looking for full-time or internship roles in AI systems, agents and developer tooling, remote or India-based. I'm a student, and I'm flexible about how the right role fits around my degree.

Reach me on [LinkedIn](https://www.linkedin.com/in/harshit-gavita-bb90b3202) or [email](mailto:Harshit.gavita@gmail.com).
