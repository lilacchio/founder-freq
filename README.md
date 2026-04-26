# founder-freq

A Claude Code skill that builds a complete personal brand strategy for Solana founders on X. Identifies your founder archetype, writes your style guide, and generates 10 posts in your actual voice — not fill-in-the-blank templates.

**[Live demo](https://lilacchio.github.io/launch-signal/)**

![founder-freq demo](https://lilacchio.github.io/launch-signal/screenshots/output-section.png)

## Install

```bash
npx skills add sagapad/founder-freq
```

## The problem

Most founders either repost their project account or post nothing at all. A project account talks about the product. A founder account talks about the person: their thinking, their POV, their journey. These are completely different.

`founder-freq` figures out which of 5 proven Solana founder archetypes fits you, then builds everything around that — content pillars, voice, rhythm, engagement tactics, and 10 posts written to sound like you.

## Output

- **Archetype identification** — primary + secondary blend with specific reasoning tied to your background
- **Unique POV** — the one angle you should consistently own on X, not a category, an actual position
- **Content pillars** — 3-4 recurring topics with posting frequency per pillar
- **Writing style guide** — tone, sentence structure, jargon rules, phrases to use and avoid
- **Weekly posting rhythm** — number of posts, types (threads vs short takes vs replies), best times
- **Engagement playbook** — who to follow first, how to reply to large accounts, cold-start tactics for founders under 1,000 followers
- **10 fully written posts** — across all content pillars, all formats, ready to post with no editing

![archetype output](https://lilacchio.github.io/launch-signal/screenshots/tweets-section.png)

## How to use

After installing, trigger the skill:

```
/founder-freq
```

Claude will ask for:
- Your name or handle
- What you're building
- Your background (technical / non-technical / operator / researcher)
- What you care most about (DeFi, AI, consumer crypto, infrastructure, etc.)
- Your natural communication style (analytical / contrarian / storyteller / etc.)
- Your X handle (optional — paste 5-10 recent posts to calibrate voice)
- Current follower count (optional — shapes the cold-start strategy)

## The Five Founder Archetypes

| Archetype | Signature | Growth Mechanism |
|---|---|---|
| **Technical Oracle** | Posts rarely, but with high density. Each post carries weight. | Reputation compound interest |
| **Ecosystem Builder** | Connective tissue. Celebrates, amplifies, connects. | Reciprocity loops |
| **Contrarian** | Takes strong positions, debates publicly. | Controversy is distribution |
| **Builder-in-Public** | Documents everything. Ships constantly. Failures included. | Progress loops — people root for the journey |
| **Strategist** | Reads trends early, builds a prediction track record. | Authority compounds when you're right before consensus |

Most founders are a blend of two. The skill identifies your primary (roughly 70%) and secondary (roughly 30%) and explains why in terms of your actual background — not generic archetype descriptions.

## Example

**Input:**
```
Founder: Rishi Anand
Building: AutoDeFi — AI agent managing Solana DeFi positions
Background: Technical, ex-Google ML, 3 years Solana
Focus: DeFi + AI
Style: Analytical, data-driven, slightly contrarian
Followers: ~800
```

**Output (excerpt):**

> **Archetype:** Strategist (65%) + Contrarian (35%)
>
> Rishi's ML background gives him a genuinely rare lens on DeFi. He understands both protocol mechanism design and the behavior of AI systems being built on top of them. Most DeFi commentators know one or the other. He can see what's coming before it becomes consensus.
>
> **Unique POV:**
> "AI agents don't fail in DeFi because the AI is bad. They fail because on-chain state moves faster than any agent can reason about it. The real bottleneck isn't intelligence, it's latency. And Solana is the only chain fast enough to close that gap."
>
> **Post 3 (short take):**
> Every "AI agent for DeFi" project that launched in the last 6 months is using the same architecture.
> None of them have published performance data.
> That's not a coincidence.
>
> **Post 7 (contrarian take):**
> Hot take: most "AI agent" projects in crypto are just cron jobs with a ChatGPT wrapper.
> A real agent: observes state, forms a belief, takes an action, observes the result, updates the belief.
> That loop requires sub-second state reads and transaction finality. That's not possible on most chains.
> On Solana it is. That's the actual moat, not the model.

## What makes it different

Most personal brand playbooks assume you already have an audience and tell you what to post. `founder-freq` starts with who you are and works forward from there — which means two founders using the same skill get completely different outputs.

It also includes a cold-start strategy built specifically for founders under 1,000 followers: 5 specific tactics for building genuine early followers, not vanity metrics. Most tools skip this because they assume an existing base. This one doesn't.

## Pair with launch-signal

If you just submitted a hackathon project, use [launch-signal](https://sagapad.com/skills/launch-signal) first to build the project's social playbook, then use `founder-freq` to build your personal voice alongside it.

## Built for

Colosseum Hackathon · SagaPad Skill Marketplace · Superteam Frontier Track
