# github

wraiths-org / Project WRAITHS                                                          
https://img.shields.io/badge/Status-Active-brightgreen https://img.shields.io/badge/License-AGPL--3.0-important https://img.shields.io/badge/Architecture-Microservices%2520%252B%2520Events-blue

Orchestrating the future of autonomous cybersecurity.
Project WRAITHS (Weaponized, Responsive, Adaptive, Intelligent Threat-Hunting System) is an open-source framework that lets you build and orchestrate powerful, automated security operations. We turn isolated tools into a collaborative, AI-driven team.

🚀 What is this?
Imagine if you could command a full team of cybersecurity experts—a recon specialist, a wireless hacker, a forensics analyst—all at once, with a single instruction. That's the power of WRAITHS.

It's a modular, event-driven platform where every security tool (like nmap or aircrack-ng) is wrapped in a consistent microservice that communicates through a central nervous system. This allows humans and AI agents to compose complex workflows on the fly, from reconnaissance to penetration testing to incident response.

✨ What does WRAITHS stand for?
Weaponized: Built for real-world operational effectiveness.

Responsive: Reacts in real-time to events and findings.

Adaptive: Changes tactics based on feedback and results.

Intelligent: Powered by AI agents that plan and make decisions.

Threat-Hunting: Proactively seeks out vulnerabilities and threats.

System: It’s not a single tool, but an integrated ecosystem.

🧩 How it works (The Big Ideas)
Modular & Pluggable: Every tool is a Dockerized microservice. Found a new cool tool? Wrap it in a service, plug it in, and it instantly becomes part of the team.

Event-Driven: Services communicate by publishing and subscribing to events on a high-speed message bus (NATS). This makes the system incredibly resilient and scalable.

AI-Native: The framework is built for AI orchestration from the ground up. Auto-GPT-style agents can discover tools, chain them together, and execute multi-step operations autonomously.

One API to Rule Them All: A central gateway provides a unified API for every tool in the system, making integration simple for both humans and machines.

🗂️ What's here?
This organization contains a family of repositories that make up the WRAITHS ecosystem:

wraiths-core: The brain and nervous system. Contains the API gateway, event bus config, and AI orchestrator.

Framework Repos: Specialized modules for different security domains:

wraiths-recon - Scanning & discovery

wraiths-bluetooth - Bluetooth offensive security

wraiths-sdr - Software-Defined Radio operations

wraiths-forensics - Digital forensics & incident response

...and more to come!

🚀 Get Started
Ready to orchestrate your security tools?

Clone the core repo: git clone --recurse-submodules https://github.com/wraiths-org/wraiths-core.git

Start the stack: docker compose up

Run your first operation: Use the API gateway to invoke a tool and watch the events flow!

Check out our Getting Started guide for a full tutorial.

🤝 How to Contribute
We are building the future of automated security in the open, and we need your help!

Build a Wrapper: See a tool we're missing? Wrap it in a microservice and submit a PR!

Improve the Core: Help us enhance the orchestrator, gateway, or documentation.

Start a Discussion: Have an idea? Open a Discussion thread to design it with the community.

Please read our Contributing Guidelines for details.

Let's build the future of autonomous security, together.

Disclaimer: This project is intended for legal security research, authorized testing, and educational purposes only. Always operate within your applicable laws and have explicit permission before testing any system.
