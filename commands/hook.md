---
allowed-tools: [Read, Write, TodoWrite]
description: "High-retention hook creation with psychological triggers"
wave-enabled: false
category: "Retention"
auto-persona: ["hook-master"]
mcp-servers: []
---

# /cc:hook - Hook Creation

## Usage
```bash
/cc:hook [topic/context] [--style <style>] [--<flags>]
```

## Arguments
- `[topic/context]` - Subject or context
- `--platform ig|tt|yt|tw` - Target platform
- `--style question|statement|controversial|story|shock` - Hook type
- `--count [n]` - Number of hooks (default: 5)
- `--test` - Include A/B variants

## Auto-Activation
- **hook-master**: All hook generation

## Output Structure

```yaml
hooks:
  primary:
    - hook: "Exact hook text"
      pattern: "pattern_name"
      psychology: "trigger_used"
      platform_fit: "score/10"
      visual_cue: "visual_suggestion"
      duration: "2-4s"

  variants: # A/B testing
    hook_1_variants: [3_alternatives]
    hook_2_variants: [3_alternatives]

  ranking:
    viral_potential: [ranked]
    engagement_potential: [ranked]
    controversy_safe: [ranked]
```

## Hook Patterns Available

### Curiosity Gap (Power: 9/10)
- "Ce que personne ne vous dit sur..."
- "Le secret que [authority] cache"
- "J'ai découvert pourquoi [problem]"

### Controversial (Power: 9/10)
- "[Opinion impopulaire] et je m'en excuse pas"
- "Arrêtez de [popular advice]"
- "[Common belief] est un mensonge"

### Story Tease (Power: 9/10)
- "J'ai tout perdu quand..."
- "Ce matin, j'ai reçu un message qui..."
- "La pire erreur de ma vie"

### Value Promise (Power: 7/10)
- "3 façons de [benefit] en [time]"
- "Le framework que j'utilise pour [result]"
- "[Number] erreurs qui [consequence]"

### Pattern Interrupt (Power: 8/10)
- "STOP. Avant de scroller..."
- "[Action inattendue] + maintenant que j'ai ton attention"

### Identity Call-Out (Power: 8/10)
- "Si tu es [identity], tu dois savoir"
- "Les [group] vont comprendre"
- "POV: tu es [situation]"

## Psychology Triggers

| Trigger | Mechanism | Power |
|---------|-----------|-------|
| Curiosity | Information gap | 9/10 |
| Fear | Loss aversion | 8/10 |
| Controversy | Cognitive dissonance | 9/10 |
| Identity | Group belonging | 8/10 |
| Scarcity | FOMO | 8/10 |
| Story | Narrative investment | 9/10 |
