---
allowed-tools: [Read, Write, Grep, Glob, TodoWrite, Task, WebSearch]
description: "Content idea generation with hooks, angles, and viral scoring"
wave-enabled: true
category: "Ideation"
auto-persona: ["strategist", "hook-master", "trend-hunter"]
mcp-servers: ["context7", "sequential"]
---

# /cc:ideate - Content Idea Generation

## Usage
```bash
/cc:ideate [niche/topic] [--platform <platform>] [--<flags>]
```

## Arguments
- `[niche/topic]` - Target niche or topic
- `--platform ig|tt|yt|tw|all` - Target platform (default: all)
- `--count [n]` - Number of ideas (default: 10)
- `--trend` - Include current trends
- `--evergreen` - Focus on timeless content
- `--viral` - Optimize for viral potential
- `--series` - Generate series-format ideas

## Auto-Activation
- **strategist**: Content pillars, positioning
- **hook-master**: Hooks for each idea
- **trend-hunter**: Trending opportunities

## Output Structure

For each idea:
```yaml
idea:
  title: "Catchy title"
  hook: "3-5s hook text"
  angle: "Unique differentiator"
  format: "Optimal content type"
  platforms: [best_fit]
  viral_score: "1-10"
  effort: "low|mid|high"
  cta: "Suggested call-to-action"
```

Summary:
```yaml
summary:
  top_3_viral: [highest_potential]
  quick_wins: [low_effort_high_impact]
  series_potential: [ideas_for_series]
```

## Execution Workflow

### 1. Context Analysis
- Parse niche/topic keywords
- Identify target audience
- Assess platform requirements

### 2. Idea Generation
- Generate ideas based on content pillars
- Apply hook patterns from CC-PATTERNS.md
- Score viral potential
- Match to optimal platforms

### 3. Optimization
- Rank by viral score
- Identify quick wins
- Group series-potential ideas
- Add CTAs and engagement hooks
