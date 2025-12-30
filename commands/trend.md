---
allowed-tools: [Read, Write, WebSearch, WebFetch, TodoWrite]
description: "Trend research and opportunity identification"
wave-enabled: false
category: "Research"
auto-persona: ["trend-hunter", "strategist"]
mcp-servers: ["context7"]
---

# /cc:trend - Trend Research

## Usage
```bash
/cc:trend [niche/topic] [--platform <platform>] [--<flags>]
```

## Arguments
- `[niche/topic]` - Niche to monitor
- `--platform ig|tt|yt|tw|all` - Platform focus
- `--depth quick|deep` - Analysis level
- `--actionable` - Focus on exploitable opportunities

## Auto-Activation
- **trend-hunter**: Trend identification
- **strategist**: Opportunity assessment

## Output Structure

```yaml
trends:
  current:
    - trend: "Description"
      platform: "origin"
      lifecycle: "emerging|peak|declining"
      relevance: "fit/10"
      window: "time_to_act"
      examples: [creators]

  audio: # TikTok/Reels
    - sound: "Name/description"
      uses: "popularity"
      stage: "lifecycle"
      angle: "how_to_use"

  formats:
    - format: "Description"
      platforms: [popular_on]
      adaptation: "how_to_adapt"

  hashtags:
    rising: [emerging]
    peak: [current_top]
    niche: [niche_specific]

  opportunities:
    - opportunity: "Description"
      urgency: "high|mid|low"
      effort: "required"
      potential: "viral_score"
      angle: "unique_approach"

  competitors:
    - creator: "name"
      hit: "recent_success"
      pattern: "what_worked"
      adaptation: "how_to_adapt"

  actions:
    immediate: [this_week]
    short_term: [this_month]
    watch: [monitor]
```

## Trend Lifecycle

| Stage | Window | Opportunity | Risk |
|-------|--------|-------------|------|
| Emerging | 1-3 days | First mover | May not take off |
| Rising | 3-7 days | High visibility | Competition |
| Peak | 7-14 days | Guaranteed views | Oversaturated |
| Declining | 14-30 days | Low | Looks dated |

## Trend Scoring

```yaml
scoring:
  relevance: "Niche fit (0-10)"
  timing: "Window opportunity (0-10)"
  competition: "Saturation inverse (0-10)"
  adaptability: "Ease of adaptation (0-10)"
  brand_fit: "Brand coherence (0-10)"
```

## Monitoring Sources

### TikTok
- For You page (fresh account)
- Creative Center trends
- Trending sounds

### Instagram
- Reels trending audio
- Explore patterns

### YouTube
- Trending tab
- Shorts feed

### Cross-Platform
- Twitter/X viral
- Reddit emerging
- Google Trends
