Different models. Same ideas.

Do different LLMs actually brainstorm differently, or do they converge on the same ideas?

I asked 5 LLMs to brainstorm across 2 topics and 3 prompt types, collected 300 ideas, and manually coded each one by its underlying structure rather than its wording. No matter how the inputs changed, the outputs collapsed into the same 6 structural patterns.

Models differ in how they say things, not in what they think of. One-page summary: 08 Infographic.pdf

Setup
	
Models	GPT (Instant), Gemini (Fast), DeepSeek (Instant), Grok (Fast), Claude (Sonnet 4.6)
Topics	Elderly mobility in cities, the future of education
Prompt types	Open, Constrained, Cross-domain
Conditions	5 models × 2 topics × 3 prompts = 30
Output per condition	10 ideas
Total ideas	300 (60 per model)
The three prompt types
Open: "Generate 10 innovative ideas for improving elderly mobility in urban environments."
Constrained: the same ask, but with no apps, AI, smartphones or digital platforms, no common ideas like ride-sharing or wearables, and a push towards unconventional approaches.
Cross-domain: the same ask, inspired by systems from nature, biology or non-urban environments (for example swarm behaviour, ecosystems, circulation).

The education prompts follow the same three structures. The exact wording for every prompt is in 01 Data.

Method
Generate: ran all 30 conditions and saved every response verbatim (01 Data).
Reduce: stripped each idea down to its underlying function, ignoring surface wording. For example, "AI-powered personalised learning system" becomes Personalisation + System, and "Mycelium-inspired learning networks" becomes Network system.
Code: manually assigned each idea to a structural pattern (05 pattern_classification).
Compare: looked for differences across models, prompt types and topics (03 prompt_effects, 04 model_comparison).
The 6 structural patterns
Pattern	What it means	Examples
Optimization	Improving an existing system	Smart crosswalks, adaptive learning
Platform / System	Creating a structured system or network	Learning hubs, mobility systems
Social Systems	Human coordination or interaction	Buddy systems, guilds
Network / Flow	Distributed or flow-based systems	Mycelium networks, swarm systems
Environmental Design	Physical or spatial changes	Sidewalks, corridors, benches
Tech Integration	AI, sensors, digital tools	AI tutors, smart infrastructure
Findings
Ideas collapse into a small set of patterns. Every idea from every model fit one of the 6 patterns.
Prompts change the framing, not the structure.
Open prompts leaned on AI and optimization.
Constrained prompts shifted towards social systems and physical design once tech was ruled out.
Cross-domain prompts brought in new metaphors (mycelium → networks, swarm → coordination), but they mapped back onto the same system logic.
Models differ in style, not in substance.
GPT: balanced system and optimization ideas
Gemini: more technical and detailed
DeepSeek: service and infrastructure focused
Claude: more human-centred and social
Grok: more sensory and experiential
Underneath the style, all five landed in the same patterns.
Why this matters

LLMs look creative, but they work inside a narrow conceptual space. Most of the diversity is in the language, not the ideas. For anyone using LLMs to brainstorm, this means a second model or a cleverer prompt adds less variety than it seems to. Real divergence has to be designed in, through constraints, human input, or evaluation that looks past the wording.

Limitations
One coder. The patterns were coded manually by one person, with no inter-rater check.
Small scope. 2 topics and 10 ideas per condition. The patterns may not hold for other domains.
Fast model tiers. Most models were run on their fast or instant settings, and outputs vary between runs.
Qualitative counts. Pattern frequencies per model and per prompt type are not yet quantified.
Repository
File	Contents
01 Data	All 300 ideas, verbatim, with the exact prompts
02 Method	Study design
03 prompt_effects	How prompt type changed the outputs
04 model_comparison	Differences and similarities between models
05 pattern_classification	Pattern definitions and coding examples
06 Insight	Key takeaways
07 Slides.pdf	Presentation
08 Infographic.pdf	One-page summary
