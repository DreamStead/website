# DreamStead

A small studio building a software factory for one developer, and the game that factory is used on. This repository will hold the DreamStead website; for now this page is the landing page.

## DreamFlow

**A software factory that assembles itself from its own failures.**

DreamFlow takes one developer's vague idea to low-bug code that matches intent, in small test-first pull requests that a gate merges only when the proof holds. It treats model output as a guess, never as proof.

- **Live** (measured 21 Nov 2026): 340 merged pull requests since 15 Nov 2026, 312 of them shipped by DreamFlow's own Shipper, every one at 5 files or fewer. Over the last 20 merges, a ready spec reached `main` in a median 61.9 minutes. The last 50 CI runs were green, and an audit on 20 Nov found 0 clear escaped bugs in 60 merges.
- **Queued, not shipped:** a queue doctor that checks, repairs and reorders the queue on its own; a usage preflight before each model call; two competing build variants after a failed build; and an adversarial review of design specs.
- **Vision:** a parts shelf where each part carries its lineage and fitness, a rebuild of nektos/act from one intake statement with no human stops, and a full feature driven from the phone.

Every change, including changes to DreamFlow itself, follows ten steps: define, question, delete, simplify, bound, measure, accelerate, wire, automate, evolve.

## Also at DreamStead

- **HomeWorld:** an Unreal Engine 5.8 game built with DreamFlow: a homestead in the sky, a descent to the planet, and the loop between them.
- **MCPTestBridge:** a UE 5.8 editor plugin, intended for Fab, that adds a test-and-safety loop for agent-driven editor work. Version 0.1.0 is a skeleton.
- **Tether:** a phone console for status, holds and approvals on the desktop pump.

The DreamFlow, HomeWorld, MCPTestBridge and Tether repositories are private; walkthroughs on request. More on the organization profile: [github.com/DreamStead](https://github.com/DreamStead).
