<div align="center">

# Software Engineering Arena

</div>

[Software Engineering Arena](https://huggingface.co/SWE-Arena) is an open-source initiative to transparently evaluate and track AI assistants across real-world software engineering tasks. We provide interactive platforms, tracking systems, and novel metrics to advance the field of AI-assisted software development.

> **"The easier it is to verify a solution, the faster an AI system can learn to master the task."** > — [Alperen Keles (@alpaylan)](https://alperenkeles.com/posts/verifiability-is-the-limit), [Andrej Karpathy (@karpathy)](https://x.com/karpathy/status/1990116666194456651), [Jason Wei (@jasonwei20)](https://www.jasonwei.net/blog/asymmetry-of-verification-and-verifiers-law)

**Our mission:** We believe any evaluable task can eventually be automated with high-quality AI systems. We accelerate this transformation in software engineering by developing benchmarks and leaderboards that rigorously evaluate AI capabilities.

**Welcome collaboration from research labs, independent contributors, and the broader SE community!**

## ⚔️ Arena-Based Tracking Suite

Evaluate AI assistants through pairwise comparisons in user-oriented software engineering scenarios:

### [SWE-Agent-Arena](https://github.com/Software-Engineering-Arena/SWE-Agent-Arena) [![SWE-Agent-Arena](https://img.shields.io/badge/🏟️-Try%20SWE--Agent--Arena-red?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/SWE-Agent-Arena)

Evaluate **CLI coding agents** through pairwise comparisons on real software engineering tasks. Two anonymous agents tackle the same task in isolated environments — compare their output and git diffs, then vote.

### [SWE-Model-Arena](https://github.com/Software-Engineering-Arena/SWE-Model-Arena) [![SWE-Model-Arena](https://img.shields.io/badge/🏟️-Try%20SWE--Model--Arena-green?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/SWE-Model-Arena)

Evaluate **tool-calling models** through pairwise comparisons where models operate as autonomous coding agents via [opencode](https://opencode.ai), producing real git diffs and code changes.

### [SWE-Chatbot-Arena](https://github.com/Software-Engineering-Arena/SWE-Chatbot-Arena) [![SWE-Chatbot-Arena](https://img.shields.io/badge/🏟️-Try%20SWE--Chatbot--Arena-blue?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/Software-Engineering-Arena)

Evaluate **large language models** through pairwise comparisons in multi-round conversational workflows with repository-aware context and transparent leaderboards.

## 📊 GitHub-Based Tracking Suite

Evaluate AI assistants through their actual GitHub activity:

### [SWE-Issue](https://github.com/Software-Engineering-Arena/SWE-Issue) [![SWE-Issue](https://img.shields.io/badge/🏟️-Try%20SWE--Issue-yellow?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/SWE-Issue)
Track assistants via **issue tracking**—bug reports, feature requests, outstanding issues, community discussions, question answering, and polls.

### [SWE-PR](https://github.com/Software-Engineering-Arena/SWE-PR) [![SWE-PR](https://img.shields.io/badge/🏟️-Try%20SWE--PR-purple?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/SWE-PR)
Track assistants via **pull requests**, **code reviews** and **commits**—feature quality, feedback timeliness, and iterative improvements.

### [SWE-Release](https://github.com/Software-Engineering-Arena/SWE-Release) [![SWE-Release](https://img.shields.io/badge/🏟️-Try%20SWE--Release-teal?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/SWE-Release)
Track assistants via **product releases**—release activity, version publishing, and real-world deployment patterns.

### [SWE-Community](https://github.com/Software-Engineering-Arena/SWE-Community) [![SWE-Community](https://img.shields.io/badge/🏟️-Try%20SWE--Community-indigo?style=for-the-badge)](https://huggingface.co/spaces/SWE-Arena/SWE-Community)
Track assistants via **community engagement**—wiki documentation contributions, wiki page edits, knowledge base maintenance, team membership events, collaboration patterns, and team organization activities.

## 📚 Curated Resources

Community-maintained lists and references for topics related to AI-assisted software engineering:

### [Awesome Spec-Driven Development](https://github.com/Software-Engineering-Arena/awesome-spec-driven-development) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, frameworks, and resources for Spec-Driven Development (SDD)—the practice of writing specifications first to guide development, testing, and documentation.

## 📄 License

All projects under Software Engineering Arena are licensed under the **Apache 2.0 License**. Data collected and open-sourced follows the same license.
