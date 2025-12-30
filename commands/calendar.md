---
allowed-tools: [Read, Write, Edit, TodoWrite, Task]
description: "Strategic editorial planning with content pillars and batch production"
wave-enabled: true
category: "Strategy"
auto-persona: ["strategist", "trend-hunter"]
mcp-servers: ["sequential"]
---

# /cc:calendar - Editorial Calendar

## Usage
```bash
/cc:calendar [period] [--platforms <platforms>] [--<flags>]
```

## Arguments
- `[period]` - week | month | quarter
- `--platforms ig,tt,yt,tw` - Target platforms
- `--niche [niche]` - Content niche
- `--frequency daily|3x|5x|custom` - Posting frequency
- `--pillars p1,p2,p3` - Content pillars
- `--events` - Include key dates
- `--series` - Plan in series format

## Auto-Activation
- **strategist**: Content strategy, pillars
- **trend-hunter**: Trend opportunities

## Output Structure

```yaml
calendar:
  strategy:
    pillars: [defined_pillars]
    frequency: "rhythm"
    platform_split: {platform: percentage}
    goals: [monthly_goals]

  themes:
    week_1: "Theme + focus"
    week_2: "Theme + focus"
    week_3: "Theme + focus"
    week_4: "Theme + focus"

  schedule:
    - date: "YYYY-MM-DD"
      platform: "target"
      pillar: "content_pillar"
      idea: "content_idea"
      format: "type"
      hook_angle: "approach"
      series: "series_name"

  key_dates:
    - date: "event_date"
      event: "name"
      opportunity: "how_to_leverage"

  series:
    - name: "Series name"
      episodes: [titles]
      frequency: "cadence"

  batch_production:
    week_1: [contents_to_produce]
    week_2: [contents_to_produce]

  metrics:
    views: "target"
    engagement: "target_%"
    growth: "follower_target"
```

## Content Pillars Framework

Recommended split:
- **Pillar 1** (40%): Core expertise
- **Pillar 2** (30%): Related topics
- **Pillar 3** (20%): Personal/lifestyle
- **Pillar 4** (10%): Experimental

## Platform Frequency Guide

| Platform | Minimum | Optimal | Max |
|----------|---------|---------|-----|
| TikTok | 1x/day | 2-3x/day | 4x |
| Instagram | 1x/day | 1-2x + stories | 3x |
| YouTube Shorts | 1x/day | 1-2x/day | 3x |
| YouTube Long | 1x/week | 2x/week | 3x |
| Twitch | 3x/week | 5x/week | Daily |

## Batch Production Strategy

Group by:
1. **Location** - Same background
2. **Outfit** - Same look
3. **Topic** - Related content
4. **Energy** - Similar vibe
