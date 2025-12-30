---
allowed-tools: [Read, Write, WebSearch, WebFetch, TodoWrite]
description: "Content and account performance analysis with actionable insights"
wave-enabled: true
category: "Analytics"
auto-persona: ["strategist", "trend-hunter"]
mcp-servers: ["sequential"]
---

# /cc:analyze - Performance Analysis

## Usage
```bash
/cc:analyze [content/account] --platform <platform> [--<flags>]
```

## Arguments
- `[content/account]` - URL or @username
- `--platform ig|tt|yt|tw` - Platform
- `--depth quick|full` - Analysis level
- `--competitor` - Competitor analysis mode
- `--recommendations` - Include action items

## Auto-Activation
- **strategist**: Strategic insights
- **trend-hunter**: Pattern identification

## Output Structure

```yaml
analysis:
  overview:
    account: "identifier"
    platform: "platform"
    followers: "count"
    engagement_rate: "%"
    frequency: "posting_avg"

  content:
    top_performing:
      - content: "description"
        metrics: {views, likes, comments, shares}
        success_factors: [why_worked]
        pattern: "identified"

    underperforming:
      - content: "description"
        metrics: {views, likes, comments, shares}
        issues: [why_failed]
        fix: "improvement"

  patterns:
    hooks_that_work: [effective]
    optimal_duration: "sweet_spot"
    best_times: [posting_times]
    pillars: [identified]
    engagement_triggers: [drivers]

  audience:
    demographics: "estimated"
    interests: [inferred]
    behavior: "how_they_interact"
    preferences: [what_they_want]

  competitor: # if --competitor
    strengths: [vs_them]
    weaknesses: [vs_them]
    opportunities: [gaps]

  recommendations:
    immediate: # This week
      - action: "specific"
        impact: "expected"
        effort: "low|mid|high"

    strategic: # This month
      - action: "specific"
        impact: "expected"

    experiments:
      - test: "what"
        hypothesis: "expected"
        metrics: [measure]

  projection:
    current: "trajectory"
    optimized: "with_recommendations"
    levers: [biggest_impact]
```

## Key Metrics by Platform

### TikTok
- **Primary**: Watch time %, completion rate
- **Secondary**: Shares, comments
- **Growth**: Follows from video

### Instagram
- **Primary**: Saves, shares
- **Secondary**: Comments, profile visits
- **Growth**: Reach vs followers

### YouTube
- **Primary**: CTR, watch time
- **Secondary**: Session time, subs
- **Growth**: Suggested traffic %

### Twitch
- **Primary**: Concurrent viewers
- **Secondary**: Chat rate, clip creation
- **Growth**: Follower conversion

## Analysis Framework

### Content Analysis
1. Identify top 10% performers
2. Extract common patterns
3. Compare to underperformers
4. Define success formula

### Audience Analysis
1. Engagement timing
2. Content preferences
3. Interaction patterns
4. Growth opportunities

### Competitive Analysis
1. Content gaps
2. Engagement comparison
3. Differentiation opportunities
4. Trend adoption speed
