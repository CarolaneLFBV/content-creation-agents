# CC-COMMANDS.md - Content Creator Command Reference

Commandes complètes pour création de contenu multi-plateforme.

## Command Architecture

```yaml
prefix: "/cc:"
auto-agents: true
pattern-integration: CC-PATTERNS.md
platform-awareness: CC-PLATFORMS.md
token-optimization: aggressive
```

---

## `/cc:ideate [niche/topic] [flags]`

**Purpose**: Génération d'idées de contenu complètes avec hooks et angles

```yaml
command: "/cc:ideate"
category: "Ideation"
auto-agents: [cc-strategist, cc-hook-master, cc-trend-hunter]
output-format: structured-ideas
```

**Arguments**:
- `[niche/topic]`: Thématique ou niche cible
- `--platform [ig|tt|yt|tw|all]`: Plateforme(s) cible
- `--count [n]`: Nombre d'idées (default: 10)
- `--trend`: Inclure tendances actuelles
- `--evergreen`: Focus contenu intemporel
- `--viral`: Optimiser potentiel viral
- `--series`: Idées en format série

**Output Structure**:
```yaml
idea_output:
  for_each_idea:
    title: "Titre accrocheur"
    hook: "Accroche 3-5s"
    angle: "Angle unique/différenciant"
    format: "Type de contenu optimal"
    platforms: [best_fit_platforms]
    viral_score: "1-10"
    effort: "low|mid|high"
    content_pillars: [relevant_pillars]
    cta: "Call-to-action suggéré"

  summary:
    top_3_viral: [best_ideas]
    quick_wins: [low_effort_high_impact]
    series_potential: [ideas_for_series]
```

**Example**:
```bash
/cc:ideate fitness --platform tt --count 10 --viral
```

---

## `/cc:script [idea/topic] [flags]`

**Purpose**: Script complet optimisé pour la rétention

```yaml
command: "/cc:script"
category: "Production"
auto-agents: [cc-scriptwriter, cc-hook-master, cc-platform-expert]
patterns: [open-loop, story-peaks, pattern-interrupt]
```

**Arguments**:
- `[idea/topic]`: Sujet ou idée à scripter
- `--platform [ig|tt|yt|tw]`: Plateforme cible (requis)
- `--duration [15s|30s|60s|3m|10m|long]`: Durée cible
- `--style [talking|voiceover|cinematic|raw]`: Style
- `--tone [edu|fun|pro|story|controversial]`: Tonalité
- `--cta [follow|comment|share|link|none]`: CTA principal

**Output Structure**:
```yaml
script_output:
  metadata:
    platform: "target_platform"
    duration: "estimated_duration"
    retention_patterns: [patterns_used]

  hook: # 0-3s
    text: "Accroche exacte"
    visual: "Description visuelle"
    pattern: "pattern_used"
    alternatives: [2_alternative_hooks]

  body:
    segments:
      - timestamp: "0:03-0:15"
        content: "Contenu segment"
        visual: "Description visuelle"
        retention_technique: "technique_used"
        energy: "high|mid|low"

    open_loops: [loop_points]
    pattern_interrupts: [interrupt_points]
    story_peaks: [peak_moments]

  climax: # Point culminant
    timestamp: "peak_moment"
    content: "Contenu climax"
    emotional_trigger: "emotion_target"

  cta:
    primary: "CTA principal"
    secondary: "CTA secondaire"
    placement: "optimal_timing"

  production_notes:
    b_roll_suggestions: [visuals_needed]
    music_mood: "mood_recommendation"
    text_overlays: [key_text_moments]
    transitions: [transition_suggestions]

  caption:
    text: "Caption optimisée SEO"
    hashtags: [relevant_hashtags]
    emojis: "strategic_emoji_use"
```

**Retention Techniques Auto-Applied**:
- Hook pattern (curiosité immédiate)
- Open loops (maintien attention)
- Pattern interrupts (every 7-15s)
- Story peaks (pics émotionnels)
- Payoff delivery (satisfaction)

---

## `/cc:hook [topic/context] [flags]`

**Purpose**: Création d'accroches haute rétention

```yaml
command: "/cc:hook"
category: "Retention"
auto-agents: [cc-hook-master]
patterns: [all-hook-patterns]
```

**Arguments**:
- `[topic/context]`: Sujet ou contexte
- `--platform [ig|tt|yt|tw]`: Plateforme
- `--style [question|statement|controversial|story|shock]`: Type
- `--count [n]`: Nombre de hooks (default: 5)
- `--test`: Inclure variantes A/B

**Output Structure**:
```yaml
hooks_output:
  primary_hooks:
    - hook: "Texte exact du hook"
      pattern: "pattern_used"
      psychology: "trigger_psychologique"
      platform_fit: "score/10"
      visual_cue: "suggestion_visuelle"
      duration: "2-4s"

  variants: # Pour A/B testing
    hook_1_variants: [3_alternatives]
    hook_2_variants: [3_alternatives]

  patterns_explained:
    - pattern: "Curiosity Gap"
      example: "Ce que personne ne vous dit sur..."
      why_works: "Crée un vide d'information"

  ranking:
    viral_potential: [ranked_hooks]
    engagement_potential: [ranked_hooks]
    controversy_safe: [ranked_hooks]
```

**Hook Patterns Available**:
| Pattern | Trigger | Example |
|---------|---------|---------|
| Curiosity Gap | FOMO | "Ce que 99% ignorent..." |
| Controversial | Debate | "Arrêtez de [popular thing]" |
| Story Open | Investment | "J'ai tout perdu quand..." |
| Direct Value | Utility | "3 façons de [benefit] en 30s" |
| Shock | Surprise | "[Stat choquante] et voilà pourquoi" |
| Authority Challenge | Doubt | "Les experts ont tort sur..." |
| Personal Attack | Defense | "Si tu fais ça, tu [negative]" |
| Secret Reveal | Exclusivity | "La méthode secrète des..." |

---

## `/cc:calendar [period] [flags]`

**Purpose**: Planning éditorial stratégique

```yaml
command: "/cc:calendar"
category: "Strategy"
auto-agents: [cc-strategist, cc-trend-hunter]
output: structured-calendar
```

**Arguments**:
- `[period]`: week | month | quarter
- `--platforms [ig,tt,yt,tw]`: Plateformes à planifier
- `--niche [niche]`: Niche/thématique
- `--frequency [daily|3x|5x|custom]`: Fréquence publication
- `--pillars [p1,p2,p3]`: Content pillars
- `--events`: Inclure événements/dates clés
- `--series`: Planifier en séries

**Output Structure**:
```yaml
calendar_output:
  strategy:
    pillars: [content_pillars_defined]
    frequency: "publication_rhythm"
    platform_split: {platform: percentage}
    goals: [monthly_goals]

  monthly_themes:
    week_1: "Theme + focus"
    week_2: "Theme + focus"
    week_3: "Theme + focus"
    week_4: "Theme + focus"

  content_schedule:
    - date: "YYYY-MM-DD"
      platform: "target"
      pillar: "content_pillar"
      idea: "content_idea"
      format: "content_type"
      hook_angle: "approach"
      status: "draft|scheduled|posted"
      series: "series_name_if_applicable"

  key_dates:
    - date: "event_date"
      event: "event_name"
      content_opportunity: "how_to_leverage"

  series_planning:
    - series_name: "Nom de la série"
      episodes: [episode_titles]
      frequency: "release_cadence"
      platform: "primary_platform"

  batch_production:
    week_1_batch: [contents_to_produce]
    week_2_batch: [contents_to_produce]

  metrics_targets:
    views: "target"
    engagement: "target_%"
    followers: "growth_target"
```

---

## `/cc:trend [niche/topic] [flags]`

**Purpose**: Veille tendances et opportunités

```yaml
command: "/cc:trend"
category: "Research"
auto-agents: [cc-trend-hunter, cc-strategist]
tools: [WebSearch, WebFetch]
```

**Arguments**:
- `[niche/topic]`: Niche à surveiller
- `--platform [ig|tt|yt|tw|all]`: Plateforme focus
- `--depth [quick|deep]`: Niveau analyse
- `--actionable`: Focus opportunités exploitables

**Output Structure**:
```yaml
trend_output:
  current_trends:
    - trend: "Description tendance"
      platform: "origin_platform"
      lifecycle: "emerging|peak|declining"
      relevance: "fit_score/10"
      window: "time_to_act"
      example_creators: [references]

  audio_trends: # TikTok/Reels specific
    - sound: "Sound name/description"
      uses: "popularity_indicator"
      trend_stage: "stage"
      content_angle: "how_to_use"

  format_trends:
    - format: "Format description"
      platforms: [where_popular]
      adaptation: "how_to_adapt"

  hashtag_trends:
    rising: [emerging_hashtags]
    peak: [current_top]
    niche_specific: [niche_hashtags]

  content_opportunities:
    - opportunity: "Description"
      urgency: "high|mid|low"
      effort: "required_effort"
      potential: "viral_potential"
      angle: "unique_angle"

  competitor_insights:
    - creator: "competitor_name"
      recent_hit: "best_performing_content"
      pattern: "what_worked"
      adaptation: "how_to_adapt"

  recommended_actions:
    immediate: [do_this_week]
    short_term: [do_this_month]
    watch: [monitor_these]
```

---

## `/cc:repurpose [content] [flags]`

**Purpose**: Adaptation cross-plateforme

```yaml
command: "/cc:repurpose"
category: "Optimization"
auto-agents: [cc-platform-expert, cc-scriptwriter]
reference: CC-PLATFORMS.md
```

**Arguments**:
- `[content]`: Contenu source (URL, description, ou @file)
- `--from [ig|tt|yt|tw]`: Plateforme source
- `--to [ig,tt,yt,tw|all]`: Plateformes cibles
- `--preserve [hook|story|value]`: Élément à préserver

**Output Structure**:
```yaml
repurpose_output:
  source_analysis:
    platform: "original_platform"
    format: "original_format"
    duration: "original_duration"
    strengths: [what_works]
    core_message: "main_value"

  adaptations:
    tiktok:
      format: "optimal_format"
      duration: "adapted_duration"
      hook: "platform_optimized_hook"
      modifications: [changes_needed]
      caption: "optimized_caption"
      hashtags: [platform_hashtags]
      sound_suggestion: "audio_recommendation"

    instagram_reels:
      format: "optimal_format"
      duration: "adapted_duration"
      hook: "platform_optimized_hook"
      modifications: [changes_needed]
      caption: "optimized_caption"
      hashtags: [platform_hashtags]
      cover_image: "thumbnail_suggestion"

    instagram_carousel:
      slides: [slide_contents]
      hook_slide: "first_slide_content"
      cta_slide: "last_slide_content"
      caption: "carousel_caption"

    youtube_shorts:
      format: "optimal_format"
      duration: "adapted_duration"
      hook: "platform_optimized_hook"
      modifications: [changes_needed]
      title: "seo_title"
      description: "seo_description"

    youtube_long:
      expansion_points: [content_to_add]
      structure: "video_structure"
      chapters: [chapter_breakdown]
      thumbnail_concept: "thumbnail_idea"
      title_options: [seo_titles]

    twitch_clip:
      clip_moment: "best_moment_to_clip"
      context_needed: "setup_required"

  production_priority:
    quick_wins: [easy_adaptations]
    high_impact: [worth_the_effort]

  efficiency_tips:
    batch_approach: "how_to_batch"
    tools_suggested: [production_tools]
```

---

## `/cc:series [theme/concept] [flags]`

**Purpose**: Création de séries de contenu

```yaml
command: "/cc:series"
category: "Strategy"
auto-agents: [cc-strategist, cc-scriptwriter, cc-hook-master]
patterns: [narrative-arc, episodic-hooks]
```

**Arguments**:
- `[theme/concept]`: Thème de la série
- `--platform [ig|tt|yt|tw]`: Plateforme principale
- `--episodes [n]`: Nombre d'épisodes (default: 5)
- `--format [daily|weekly|mini]`: Cadence
- `--style [educational|story|challenge|transformation]`: Type

**Output Structure**:
```yaml
series_output:
  concept:
    title: "Nom de la série"
    premise: "Concept en 1 phrase"
    unique_angle: "Ce qui la différencie"
    audience_promise: "Ce qu'ils vont obtenir"

  narrative_arc:
    setup: "Introduction du concept"
    rising_action: [escalation_points]
    climax: "Point culminant"
    resolution: "Conclusion satisfaisante"

  branding:
    visual_identity: "Éléments visuels récurrents"
    intro_template: "Format d'intro reconnaissable"
    outro_template: "Format de fin + tease"
    hashtag: "#SeriesHashtag"

  episodes:
    - episode: 1
      title: "Titre épisode"
      hook: "Accroche spécifique"
      content_summary: "Ce qui est couvert"
      cliffhanger: "Tease pour le suivant"
      duration: "target_duration"

  cross_episode_hooks:
    episode_1_to_2: "Transition hook"
    episode_2_to_3: "Transition hook"
    # ...

  engagement_strategy:
    community_prompts: [questions_to_ask]
    user_participation: "how_to_involve_audience"
    callback_opportunities: [reference_previous]

  production_batch:
    batch_1: [episodes_to_film_together]
    shared_assets: [reusable_elements]

  success_metrics:
    per_episode: [metrics_to_track]
    series_overall: [aggregate_metrics]
    pivot_triggers: [when_to_adjust]
```

---

## `/cc:analyze [content/account] [flags]`

**Purpose**: Analyse de performance et insights

```yaml
command: "/cc:analyze"
category: "Analytics"
auto-agents: [cc-strategist, cc-trend-hunter]
tools: [WebFetch, WebSearch]
```

**Arguments**:
- `[content/account]`: URL ou @username à analyser
- `--platform [ig|tt|yt|tw]`: Plateforme
- `--depth [quick|full]`: Niveau d'analyse
- `--competitor`: Mode analyse concurrentielle
- `--recommendations`: Inclure recommandations actionnables

**Output Structure**:
```yaml
analysis_output:
  overview:
    account: "account_identifier"
    platform: "platform"
    followers: "count"
    engagement_rate: "percentage"
    posting_frequency: "average"

  content_analysis:
    top_performing:
      - content: "description"
        metrics: {views, likes, comments, shares}
        success_factors: [why_it_worked]
        pattern: "identified_pattern"

    underperforming:
      - content: "description"
        metrics: {views, likes, comments, shares}
        issues: [why_it_failed]
        fix: "improvement_suggestion"

  patterns_identified:
    hooks_that_work: [effective_patterns]
    optimal_duration: "sweet_spot"
    best_posting_times: [times]
    content_pillars: [identified_pillars]
    engagement_triggers: [what_drives_engagement]

  audience_insights:
    demographics: "estimated_demo"
    interests: [inferred_interests]
    engagement_behavior: "how_they_interact"
    content_preferences: [what_they_want]

  competitor_comparison: # if --competitor
    strengths: [vs_competitor]
    weaknesses: [vs_competitor]
    opportunities: [gaps_to_exploit]

  recommendations:
    immediate: # Do this week
      - action: "specific_action"
        expected_impact: "outcome"
        effort: "low|mid|high"

    strategic: # Do this month
      - action: "specific_action"
        expected_impact: "outcome"

    experiments:
      - test: "what_to_test"
        hypothesis: "expected_result"
        metrics: [how_to_measure]

  growth_projection:
    current_trajectory: "where_you're_heading"
    optimized_trajectory: "with_recommendations"
    key_levers: [biggest_impact_actions]
```

---

## Flag Reference

### Global Flags
| Flag | Values | Description |
|------|--------|-------------|
| `--platform` | ig, tt, yt, tw, all | Plateforme cible |
| `--niche` | string | Contexte niche |
| `--tone` | edu, fun, pro, raw, story | Tonalité |
| `--duration` | 15s, 30s, 60s, 3m, 10m, long | Durée |
| `--viral` | - | Optimise viralité |
| `--evergreen` | - | Contenu intemporel |
| `--batch` | - | Output pour batch production |

### Output Flags
| Flag | Description |
|------|-------------|
| `--json` | Output JSON structuré |
| `--markdown` | Output Markdown formaté |
| `--minimal` | Output condensé |
| `--export [path]` | Export vers fichier |

### Agent Control
| Flag | Description |
|------|-------------|
| `--agent [name]` | Force agent spécifique |
| `--no-agent` | Désactive auto-agents |
