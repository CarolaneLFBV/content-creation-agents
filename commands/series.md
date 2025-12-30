---
allowed-tools: [Read, Write, Edit, TodoWrite, Task]
description: "Content series creation with narrative arcs and episode planning"
wave-enabled: true
category: "Strategy"
auto-persona: ["strategist", "scriptwriter", "hook-master"]
mcp-servers: ["sequential"]
---

# /cc:series - Series Creation

## Usage
```bash
/cc:series [theme/concept] --platform <platform> [--<flags>]
```

## Arguments
- `[theme/concept]` - Series theme
- `--platform ig|tt|yt|tw` - Primary platform
- `--episodes [n]` - Number of episodes (default: 5)
- `--format daily|weekly|mini` - Release cadence
- `--style educational|story|challenge|transformation` - Series type

## Auto-Activation
- **strategist**: Series strategy, arc
- **scriptwriter**: Episode scripts
- **hook-master**: Cross-episode hooks

## Output Structure

```yaml
series:
  concept:
    title: "Series name"
    premise: "One sentence"
    unique_angle: "Differentiator"
    audience_promise: "What they get"

  narrative_arc:
    setup: "Concept introduction"
    rising: [escalation_points]
    climax: "Peak moment"
    resolution: "Satisfying end"

  branding:
    visual: "Recurring elements"
    intro: "Recognizable format"
    outro: "End + tease template"
    hashtag: "#SeriesTag"

  episodes:
    - episode: 1
      title: "Title"
      hook: "Specific hook"
      content: "Summary"
      cliffhanger: "Tease for next"
      duration: "target"

  transitions:
    ep1_to_ep2: "Hook"
    ep2_to_ep3: "Hook"
    # ...

  engagement:
    prompts: [community_questions]
    participation: "involve_audience"
    callbacks: [reference_previous]

  production:
    batch: [film_together]
    assets: [reusable_elements]

  metrics:
    per_episode: [track]
    overall: [aggregate]
    pivot_triggers: [when_to_adjust]
```

## Series Types

### Educational Series
- Progressive complexity
- Clear learning path
- Actionable takeaways each episode

### Story Series
- Character development
- Conflict escalation
- Emotional payoffs

### Challenge Series
- Clear rules/constraints
- Progress tracking
- Community involvement

### Transformation Series
- Before/after arc
- Milestone episodes
- Documentation style

## Cross-Episode Hooks

### Cliffhanger Techniques
- Unfinished story
- Teased revelation
- Challenge outcome pending
- "Part 2 reveals..."

### Callback Techniques
- Reference previous wins
- Build on prior learning
- Inside jokes with audience
- Progress visualization

## Binge-Worthy Elements

1. **Consistent format** - Recognizable structure
2. **Episode independence** - Works standalone too
3. **Clear progression** - Obvious value escalation
4. **Community hooks** - Audience participation
5. **Satisfying payoffs** - Deliver on promises
