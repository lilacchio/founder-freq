# founder-freq

A Claude Code skill that builds a complete personal brand strategy for Solana founders on X. Includes a founder archetype system, writing style guide, and 10 ready-to-post example posts written in your actual voice.

## Install

```bash
npx skills add sagapad/founder-freq
```

## What it does

A project account talks about the product. A founder account talks about the person: their thinking, their POV, their journey. Most founders either copy their project's tone or post nothing at all. Both are missed opportunities.

`founder-freq` identifies which of 5 proven Solana founder archetypes fits you, then builds a complete playbook calibrated to your background, style, and what you're building.

**Output includes:**
- Founder archetype analysis (primary + secondary blend, with reasoning)
- Unique POV: the specific angle you should own on X
- 3-4 content pillars with posting frequency per pillar
- Writing style guide: tone, sentence structure, jargon rules, phrases to use and avoid
- Weekly posting rhythm and best times for the Solana audience
- Engagement playbook with cold-start tactics (for founders under 1,000 followers)
- 10 fully written example posts across all formats, ready to post

## How to use

After installing, trigger the skill in Claude Code:

```
/founder-freq
```

Claude will ask for:
- Your name / handle
- What you're building
- Your background (technical / non-technical / operator / researcher)
- What you care most about (DeFi, AI, consumer crypto, etc.)
- Your natural communication style
- Current X handle (optional, paste in 5-10 recent posts to calibrate voice)
- Current follower count (optional, shapes the cold-start strategy)

## The Five Founder Archetypes

| Archetype | Voice | Growth Mechanism |
|---|---|---|
| Technical Oracle | Dense, rare, high-signal | Reputation compound interest |
| Ecosystem Builder | Generous, connective | Reciprocity loops |
| Contrarian | Direct, position-taking | Controversy is distribution |
| Builder-in-Public | Authentic, daily progress | Progress loops |
| Strategist | Analytical, predictive | Track record |

Most founders are a blend of two. The skill identifies your primary (dominant) and secondary (complement) and explains why.

## Example

**Input:**
```
Founder: Rishi Anand
Building: AutoDeFi, an AI agent that manages Solana DeFi positions autonomously
Background: Technical, ex-Google ML, 3 years Solana dev
Focus: DeFi + AI
Style: Analytical, data-driven, slightly contrarian
Followers: ~800
```

**Output (excerpt):**

> **Archetype:** Strategist (primary) + Contrarian (secondary)
>
> **Unique POV:** "AI agents don't fail in DeFi because the AI is bad. They fail because on-chain state moves faster than any agent can reason about it. The real bottleneck isn't intelligence, it's latency. And Solana is the only chain fast enough to close that gap."
>
> **Post 3:**
> Every "AI agent for DeFi" project that launched in the last 6 months is using the same architecture.
> None of them have published performance data.
> That's not a coincidence.
>
> **Post 7:**
> Hot take: most "AI agent" projects in crypto are just cron jobs with a ChatGPT wrapper.
> A real agent: observes state, forms a belief, takes an action, observes the result, updates the belief.
> That loop requires sub-second state reads and transaction finality. That's not possible on most chains.
> On Solana it is. That's the actual moat, not the model.

## What makes it different

Most personal brand guides assume you already have an audience. `founder-freq` includes a **cold-start strategy** specifically for founders under 1,000 followers: 5 specific tactics for getting to 2,000 genuine followers, not vanity metrics. It also generates example posts written in your voice based on your actual inputs, not fill-in-the-blank templates.

## Built for

Colosseum Hackathon | SagaPad Skill Marketplace | Superteam Frontier Track
