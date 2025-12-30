---
allowed-tools: [Read, Write, Edit, Grep, Glob, TodoWrite]
description: "Optimized script creation with retention patterns and timestamps"
wave-enabled: true
category: "Production"
auto-persona: ["scriptwriter", "hook-master", "platform-expert"]
mcp-servers: ["sequential"]
---

# /cc:script - Script Creation

## Usage
```bash
/cc:script [idea/topic] --platform <platform> [--<flags>]
```

## Arguments
- `[idea/topic]` - Subject to script
- `--platform ig|tt|yt|tw` - Target platform (required)
- `--duration 15s|30s|60s|3m|10m|long` - Target duration
- `--style talking|voiceover|cinematic|raw` - Visual style
- `--tone edu|fun|pro|story|controversial` - Content tone
- `--cta follow|comment|share|link|none` - Primary CTA

## Auto-Activation
- **scriptwriter**: Story structure, pacing
- **hook-master**: Opening hook, retention
- **platform-expert**: Platform optimization

## Output Structure

```yaml
script:
  metadata:
    platform: "target"
    duration: "estimated"
    retention_patterns: [patterns_used]

  hook: # 0-3s CRITICAL
    text: "Exact hook text"
    visual: "Visual description"
    pattern: "pattern_used"
    alternatives: [2_other_hooks]

  body:
    segments:
      - timestamp: "0:03-0:15"
        content: "Segment content"
        visual: "Visual cue"
        retention_technique: "technique"
        energy: "high|mid|low"

    open_loops: [loop_points]
    pattern_interrupts: [interrupt_timing]

  climax:
    timestamp: "peak_moment"
    content: "Climax content"
    emotional_trigger: "target_emotion"

  cta:
    primary: "Main CTA"
    secondary: "Backup CTA"
    placement: "optimal_timing"

  production_notes:
    b_roll: [visual_suggestions]
    music_mood: "recommendation"
    text_overlays: [key_moments]

  caption:
    text: "SEO-optimized caption"
    hashtags: [relevant_tags]
```

## Retention Techniques Applied

### Opening (0-3s)
- Curiosity gap or story tease
- Pattern interrupt if needed
- Direct value promise

### Mid-Content
- Open loops every 15-30s
- Pattern interrupts every 7-15s
- Value stacking progression

### Closing
- Payoff delivery (hook promise)
- Embedded CTA
- Loop to next content (if series)
