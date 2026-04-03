# Famous Person Matching

Match the user's personality profile against a curated database of figures from technology, science, philosophy, and history — across all eras and cultures. Select the closest match based on trait overlap.

## Matching Algorithm

1. For each candidate, compute overlap across 5 trait dimensions (communication, technical/intellectual focus, decision style, ambition level, collaboration approach)
2. Each dimension is scored 0-100 for the user and each candidate
3. The candidate with the smallest total distance wins
4. If the top two candidates are within 10% of each other, mention both

---

## Category 1: Modern Technologists

### Linus Torvalds
- **Emoji**: 🐧
- **Traits**: systems-builder, brutally-direct, quality-obsessed, open-source-leader, opinionated
- **Communication**: extremely direct, no tolerance for vagueness, uses strong language when frustrated
- **Technical focus**: operating systems, low-level systems, performance
- **Decision style**: fast decisions, strong opinions loosely held, data-driven
- **Ambition**: build foundational infrastructure that lasts decades
- **Collaboration**: delegates but reviews harshly, high standards for contributors

### John Carmack
- **Emoji**: 🚀
- **Traits**: deep-optimizer, cross-domain, performance-obsessed, self-teaching, marathon-coder
- **Communication**: technical and precise, explains reasoning in depth
- **Technical focus**: graphics, VR, AI, rockets — extreme cross-domain breadth
- **Decision style**: methodical optimization, measures everything, persistent
- **Ambition**: push the frontier of what's computationally possible
- **Collaboration**: works alone on deep problems, shares findings publicly

### Andrej Karpathy
- **Emoji**: 🧠
- **Traits**: educator, researcher-engineer, clear-communicator, ML-focused, builder
- **Communication**: clear and educational, makes complex things accessible
- **Technical focus**: deep learning, neural networks, autonomous systems
- **Decision style**: research-driven, builds to understand, iterative
- **Ambition**: democratize AI understanding
- **Collaboration**: teaches while building, open-source contributor

### Yann LeCun
- **Emoji**: 🔬
- **Traits**: contrarian, academic-rigor, vision-first, persistent, debate-lover
- **Communication**: provocative, willing to argue publicly, strong convictions
- **Technical focus**: computer vision, self-supervised learning, fundamental research
- **Decision style**: sticks to core beliefs despite criticism, long-term thinking
- **Ambition**: solve intelligence itself
- **Collaboration**: mentors extensively, builds research teams

### DHH (David Heinemeier Hansson)
- **Emoji**: 🏎️
- **Traits**: opinionated, productivity-focused, aesthetic-sense, provocative, framework-builder
- **Communication**: forceful opinions, excellent writer, loves debate
- **Technical focus**: web frameworks, developer productivity, clean code
- **Decision style**: strong opinions, convention over configuration, anti-complexity
- **Ambition**: make developers more productive and happier
- **Collaboration**: builds opinionated tools, expects users to follow the "rails"

### Fabrice Bellard
- **Emoji**: 🎯
- **Traits**: quiet-genius, efficiency-obsessed, broad-mastery, minimal-communication
- **Communication**: lets code speak, minimal public presence
- **Technical focus**: compilers (TCC), emulators (QEMU), codecs (FFmpeg), LLM inference — absurd breadth
- **Decision style**: solves problems nobody thought one person could solve
- **Ambition**: build the most efficient implementation of anything
- **Collaboration**: mostly solo, releases tools for community use

### George Hotz
- **Emoji**: 🏴‍☠️
- **Traits**: hacker, rebel, speed-first, competitive, startup-founder
- **Communication**: casual, confrontational, livestreams coding
- **Technical focus**: autonomous driving, ML infrastructure, hacking/security
- **Decision style**: move fast, break things, compete aggressively
- **Ambition**: beat the big companies with a small team
- **Collaboration**: small team, high intensity, hacker culture

### Grace Hopper
- **Emoji**: ⚓
- **Traits**: pragmatist, standard-setter, teacher, systems-thinker, barrier-breaker
- **Communication**: clear, witty, practical — "it's easier to ask forgiveness than permission"
- **Technical focus**: compilers, programming languages, system standards
- **Decision style**: pragmatic, values working code over perfect plans
- **Ambition**: make computers accessible to everyone
- **Collaboration**: mentors and teaches, builds bridges between groups

### Rich Hickey
- **Emoji**: 🌀
- **Traits**: philosopher-programmer, simplicity-obsessed, deep-thinker, language-designer
- **Communication**: precise, philosophical, gives legendary talks
- **Technical focus**: programming language design, data-oriented, immutability
- **Decision style**: thinks deeply before acting, values simplicity over ease
- **Ambition**: make programming fundamentally better
- **Collaboration**: builds tools and lets the community grow around them

### Steve Wozniak
- **Emoji**: 🛠️
- **Traits**: tinkerer, playful, hardware-software, humble, builder-for-joy
- **Communication**: warm, enthusiastic, loves sharing technical details
- **Technical focus**: hardware, electronics, system design
- **Decision style**: builds for fun first, elegance matters
- **Ambition**: make technology accessible and fun
- **Collaboration**: generous collaborator, shares credit freely

### Guido van Rossum
- **Emoji**: 🐍
- **Traits**: benevolent-dictator, readability-first, community-builder, pragmatic
- **Communication**: thoughtful, considers community impact, clear writing
- **Technical focus**: language design, readability, ecosystem building
- **Decision style**: "there should be one obvious way to do it"
- **Ambition**: create a language that's readable and accessible
- **Collaboration**: BDFL model — listens but makes final calls

### Satoshi Nakamoto
- **Emoji**: 👻
- **Traits**: anonymous-builder, system-designer, cryptography, trust-minimizer
- **Communication**: precise technical writing, minimal personal disclosure
- **Technical focus**: distributed systems, cryptography, economic incentive design
- **Decision style**: designs entire systems before revealing, disappears after launch
- **Ambition**: build trustless infrastructure
- **Collaboration**: anonymous, builds and walks away

### Elon Musk
- **Emoji**: ⚡
- **Traits**: moonshot-thinker, multi-venture, risk-taker, demanding, first-principles
- **Communication**: direct, sometimes abrasive, fast context switching
- **Technical focus**: rockets, EVs, AI, neural interfaces — maximum breadth
- **Decision style**: first-principles reasoning, extremely fast pivots, high risk tolerance
- **Ambition**: multi-planetary civilization
- **Collaboration**: demands extreme performance from teams

### Alan Kay
- **Emoji**: 🔮
- **Traits**: visionary, decades-ahead, education-focused, object-thinker, big-picture
- **Communication**: poetic, metaphor-rich, thinks in systems
- **Technical focus**: personal computing, object-oriented design, educational technology
- **Decision style**: designs for the future, not the present
- **Ambition**: invent the future of computing
- **Collaboration**: leads research labs, inspires generations

---

## Category 2: Scientists & Mathematicians

### Albert Einstein
- **Emoji**: 💡
- **Traits**: thought-experimenter, first-principles, intuition-driven, nonconformist, communicator
- **Communication**: explains complex ideas through vivid analogies, patient with big concepts
- **Technical focus**: fundamental physics, thought experiments, seeking unified theories
- **Decision style**: trusts physical intuition over mathematical formalism first, then verifies
- **Ambition**: find the simplest possible laws governing the universe
- **Collaboration**: works alone on core ideas but engages with peers through letters and debate

### Richard Feynman
- **Emoji**: 🥁
- **Traits**: playful-genius, anti-pretension, hands-on, storyteller, breadth-seeker
- **Communication**: casual, irreverent, explains things from first principles with humor
- **Technical focus**: quantum physics, but dabbled in biology, art, lock-picking, drumming
- **Decision style**: dislikes cargo-cult thinking, insists on understanding over formulas
- **Ambition**: understand nature, not impress others
- **Collaboration**: challenges everyone including himself, teaches by engaging curiosity

### Alan Turing
- **Emoji**: 🔐
- **Traits**: foundational-thinker, boundary-pusher, abstract-mathematician, lone-pioneer
- **Communication**: precise, mathematical, ahead of audience comprehension
- **Technical focus**: computation theory, cryptography, artificial intelligence, morphogenesis
- **Decision style**: attacks problems nobody else sees as solvable
- **Ambition**: formalize what it means to compute and to think
- **Collaboration**: works in small trusted circles, often ahead of peers

### John von Neumann
- **Emoji**: ⚙️
- **Traits**: polymath, lightning-fast, theory-to-practice, strategic-thinker, synthesizer
- **Communication**: fast, dense, assumes high audience bandwidth
- **Technical focus**: mathematics, computing architecture, game theory, quantum mechanics, nuclear physics
- **Decision style**: instantaneous pattern recognition, applies theory to any domain
- **Ambition**: solve everything worth solving
- **Collaboration**: contributes decisively to every team he joins, accelerates others

### Marie Curie
- **Emoji**: ☢️
- **Traits**: relentless-experimenter, self-sacrificing, methodical, barrier-breaker, data-driven
- **Communication**: reserved, lets results speak, meticulous documentation
- **Technical focus**: radioactivity, chemistry, experimental physics
- **Decision style**: obsessive data collection, repeats experiments until certainty
- **Ambition**: understand matter at its most fundamental level
- **Collaboration**: partner-based research, trains next generation

### Nikola Tesla
- **Emoji**: ⚡
- **Traits**: visionary-inventor, solo-thinker, imagination-driven, impractical-idealist, ahead-of-time
- **Communication**: dramatic, visionary, poor at business and politics
- **Technical focus**: electrical engineering, wireless power, electromagnetism
- **Decision style**: designs complete systems in imagination before building
- **Ambition**: provide free energy to the entire world
- **Collaboration**: prefers to work alone, frustrated by commercial constraints

---

## Category 3: Philosophers & Strategists

### 诸葛亮 (Zhuge Liang)
- **Emoji**: 🪶
- **Traits**: strategic-planner, systems-thinker, resource-optimizer, loyal-advisor, patient
- **Communication**: eloquent, persuasive, plans exhaustively before speaking
- **Technical focus**: military strategy, governance, logistics, diplomacy
- **Decision style**: long-term strategic planning with contingencies for every scenario
- **Ambition**: restore order through superior strategy and institutional design
- **Collaboration**: advises the ruler, delegates execution, designs fail-safes

### 王阳明 (Wang Yangming)
- **Emoji**: ⚔️
- **Traits**: action-philosopher, unity-of-knowledge-and-action, pragmatic-idealist, field-commander
- **Communication**: concise, philosophical yet practical — "知行合一" (knowledge and action are one)
- **Technical focus**: moral philosophy, military strategy, governance reform, education
- **Decision style**: believes understanding only comes through doing, not theorizing
- **Ambition**: unify thought and practice, cultivate moral knowledge through real-world action
- **Collaboration**: teaches through shared practice, leads by example on the battlefield

### 墨子 (Mozi)
- **Emoji**: 🛡️
- **Traits**: engineer-philosopher, utilitarian, anti-war, hands-on, egalitarian
- **Communication**: logical argumentation, practical demonstrations, anti-rhetoric
- **Technical focus**: defensive engineering, optics, logic, mechanical invention
- **Decision style**: cost-benefit analysis, universal love principle, rejects waste
- **Ambition**: end warfare through superior defensive technology and rational ethics
- **Collaboration**: leads a tightly-organized school of craftsmen-philosophers

### 老子 (Laozi)
- **Emoji**: 🌊
- **Traits**: minimalist, anti-complexity, natural-order, paradox-thinker, effortless-action
- **Communication**: cryptic, poetic, says more with less — "大音希声"
- **Technical focus**: systems thinking through non-intervention, emergent order
- **Decision style**: wu-wei (effortless action) — the best system is one that doesn't need management
- **Ambition**: align human systems with natural patterns
- **Collaboration**: leads by not leading, influences by withdrawing

### 孙子 (Sun Tzu)
- **Emoji**: 🎯
- **Traits**: strategic-minimalist, information-warfare, adaptability, win-without-fighting
- **Communication**: concise maxims, every word carries weight
- **Technical focus**: strategy, intelligence, logistics, terrain analysis
- **Decision style**: win before the battle through superior information and positioning
- **Ambition**: achieve objectives with minimum resource expenditure
- **Collaboration**: commander who empowers subordinates with clear principles

### Aristotle
- **Emoji**: 📚
- **Traits**: systematic-classifier, empiricist, encyclopedic, first-principles, practical-wisdom
- **Communication**: methodical, taxonomic, reasons from observation to principle
- **Technical focus**: logic, biology, ethics, politics, metaphysics — everything
- **Decision style**: phronesis (practical wisdom) — right judgment in specific contexts
- **Ambition**: organize all human knowledge into coherent systems
- **Collaboration**: builds schools, creates intellectual lineages

### Leonardo da Vinci
- **Emoji**: 🎨
- **Traits**: renaissance-polymath, visual-thinker, cross-domain, notebook-keeper, perfectionist
- **Communication**: visual — sketches, diagrams, mirror writing; thinks by drawing
- **Technical focus**: painting, anatomy, engineering, flight, hydraulics, optics, architecture
- **Decision style**: follows curiosity relentlessly, often doesn't finish because new problems appear
- **Ambition**: understand how everything works
- **Collaboration**: works alone, shares through notebooks discovered centuries later

### Karl Marx
- **Emoji**: 📕
- **Traits**: systems-analyst, materialist, historical-thinker, polemicist, structural-critic
- **Communication**: dense analytical writing, combines data with theory, sharp criticism
- **Technical focus**: political economy, class dynamics, historical materialism, systemic analysis
- **Decision style**: analyzes structural contradictions, predicts systemic outcomes from material conditions
- **Ambition**: reveal the hidden mechanics of social and economic systems
- **Collaboration**: writes with close collaborators, builds international movements

---

## Category 4: Creators & Builders (Non-Tech)

### 鲁班 (Lu Ban)
- **Emoji**: 🪚
- **Traits**: master-craftsman, inventor, practical-engineer, tool-maker, problem-solver
- **Communication**: teaches through demonstration, builds prototypes
- **Technical focus**: carpentry, mechanical engineering, siege weapons, architectural tools
- **Decision style**: observes nature, abstracts principles, builds solutions
- **Ambition**: solve practical problems with elegant mechanical solutions
- **Collaboration**: master-apprentice model, passes knowledge through craft tradition

### Steve Jobs
- **Emoji**: 🍎
- **Traits**: product-visionary, design-obsessed, demanding, reality-distortion, taste-maker
- **Communication**: persuasive, simplifies complexity, "one more thing"
- **Technical focus**: product design, user experience, ecosystem thinking
- **Decision style**: trusts taste and intuition, says no to 1000 things to focus on 1
- **Ambition**: build products at the intersection of technology and liberal arts
- **Collaboration**: small elite teams, demands perfection, inspires and frustrates equally

### Claude Shannon
- **Emoji**: 🎲
- **Traits**: playful-theorist, foundational, cross-domain-hobbyist, elegant-abstraction
- **Communication**: concise papers that create entire fields, then moves on
- **Technical focus**: information theory, cryptography, circuit design, juggling machines
- **Decision style**: finds the essential mathematical structure, proves it, builds a toy to demonstrate
- **Ambition**: formalize the mathematics of communication
- **Collaboration**: publishes transformative papers, then goes back to tinkering alone

### 华罗庚 (Hua Luogeng)
- **Emoji**: 🔢
- **Traits**: self-taught-genius, applied-mathematician, educator, resilience, bridge-builder
- **Communication**: makes abstract math concrete, passionate about popularizing mathematics
- **Technical focus**: number theory, applied mathematics, optimization methods
- **Decision style**: bridges theory and practice, applies pure math to industrial problems
- **Ambition**: make mathematics useful for national development
- **Collaboration**: teaches widely, builds mathematical infrastructure for a nation

---

## Output Format

```json
{
  "name": "Person Name",
  "emoji": "🔬",
  "reason": "2-3 sentence explanation of why this match fits the user, referencing specific observed traits.",
  "sharedTraits": ["trait-1", "trait-2", "trait-3", "trait-4"]
}
```

## Matching Tips

- Weight communication style heavily — it's the most observable signal
- Technical focus should match at least partially
- Decision style is a strong differentiator between similar candidates
- Do NOT default to tech figures if the user's patterns better match a philosopher or scientist
- A user who plans exhaustively before acting may match 诸葛亮 better than any Silicon Valley figure
- A user who insists on "知行合一" (learn by doing) may match 王阳明
- A user who seeks minimalism and natural order may match 老子
- A user who builds everything from scratch alone may match Bellard or Tesla
- A user who systematically classifies and organizes everything may match Aristotle
- Cross-cultural matching is encouraged — the best match is the most accurate, not the most familiar
