---
allowed-tools: [Read, Write, Edit, TodoWrite]
description: "Cross-platform content adaptation with platform-specific optimization"
wave-enabled: true
category: "Optimization"
auto-persona: ["platform-expert", "scriptwriter"]
mcp-servers: []
---

# /cc:repurpose - Cross-Platform Adaptation

## Usage
```bash
/cc:repurpose [content] --from <platform> --to <platforms> [--<flags>]
```

## Arguments
- `[content]` - Source content (URL, description, or @file)
- `--from ig|tt|yt|tw` - Source platform
- `--to ig,tt,yt,tw|all` - Target platforms
- `--preserve hook|story|value` - Element to keep

## Auto-Activation
- **platform-expert**: Platform specs, algorithms
- **scriptwriter**: Content adaptation

## Output Structure

```yaml
repurpose:
  source:
    platform: "original"
    format: "type"
    duration: "length"
    strengths: [what_works]
    core_message: "main_value"

  adaptations:
    tiktok:
      format: "optimal"
      duration: "adapted"
      hook: "platform_hook"
      modifications: [changes]
      caption: "optimized"
      hashtags: [tags]
      sound: "suggestion"

    instagram_reels:
      format: "optimal"
      duration: "adapted"
      hook: "platform_hook"
      modifications: [changes]
      caption: "optimized"
      cover: "thumbnail_idea"

    instagram_carousel:
      slides: [contents]
      hook_slide: "first_slide"
      cta_slide: "last_slide"
      caption: "carousel_caption"

    youtube_shorts:
      format: "optimal"
      duration: "adapted"
      hook: "platform_hook"
      title: "seo_title"
      description: "seo_desc"

    youtube_long:
      expansion: [points_to_add]
      structure: "video_structure"
      chapters: [breakdown]
      thumbnail: "concept"
      titles: [options]

  priority:
    quick_wins: [easy_adaptations]
    high_impact: [worth_effort]

  efficiency:
    batch: "how_to_batch"
    tools: [suggested]
```

## Platform Adaptation Rules

### TikTok → Others
- **To Reels**: Direct, remove watermark
- **To Shorts**: Direct, add SEO title
- **To Carousel**: Extract key points

### YouTube Long → Short-Form
- Best 60s moments
- Add hook if missing
- Standalone value required

### Carousel → Video
- Animate slides
- Add voiceover
- Expand on points

## Technical Specs Quick Reference

| Platform | Aspect | Duration | Key |
|----------|--------|----------|-----|
| TikTok | 9:16 | 15s-10min | Watch time |
| Reels | 9:16 | 15-90s | Saves |
| Shorts | 9:16 | 15-60s | CTR |
| YT Long | 16:9 | 8min+ | Session time |
