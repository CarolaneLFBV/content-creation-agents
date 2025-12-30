# Content Creator Framework

Framework de création de contenu multi-plateforme pour Claude Code.

**Optimisé tokens** | **Rétention-focused** | **Marketing-driven**

## Installation

```bash
# Via Claude Code CLI
claude plugins install content-creation-agents
```

## Plateformes Supportées

| Platform | Optimisation |
|----------|--------------|
| 📱 TikTok | Discovery, trends, watch time |
| 📸 Instagram | Community, saves, Reels |
| ▶️ YouTube | SEO, retention, Shorts |
| 🎮 Twitch | Live, engagement, clips |

## Commandes

### Idéation & Stratégie

```bash
/cc:ideate [niche] --platform tt --viral
```
Génère 10+ idées avec hooks, angles uniques et scores de viralité.

```bash
/cc:calendar --month --platforms ig,tt
```
Planning éditorial 30 jours avec thèmes et batch production.

```bash
/cc:trend [niche] --actionable
```
Veille tendances avec opportunités scorées et timing.

### Production

```bash
/cc:script [topic] --platform tt --duration 60s
```
Script complet avec timestamps, hooks, pattern interrupts et CTA.

```bash
/cc:hook [topic] --style controversial --test
```
5 accroches haute rétention avec variantes A/B.

```bash
/cc:series [theme] --episodes 5 --format weekly
```
Série complète avec arc narratif et cliffhangers.

### Optimisation

```bash
/cc:repurpose [content] --from yt --to ig,tt
```
Adaptation cross-plateforme avec specs optimisées.

```bash
/cc:analyze [@account] --recommendations
```
Analyse de performance avec insights actionnables.

## Agents Spécialisés

Les agents s'activent automatiquement selon le contexte :

| Agent | Expertise | Auto-Activation |
|-------|-----------|-----------------|
| `cc-strategist` | Vision globale, positionnement | Planning, stratégie |
| `cc-hook-master` | Rétention, psychologie attention | Scripts, hooks |
| `cc-scriptwriter` | Storytelling, pacing | Écriture contenu |
| `cc-trend-hunter` | Veille, timing | Trends, opportunités |
| `cc-platform-expert` | Algos, formats, specs | Adaptation |

## Patterns de Rétention

### Hook Patterns (0-3s)
- **Curiosity Gap** → "Ce que personne ne vous dit sur..."
- **Controversial** → "Arrêtez de [popular advice]"
- **Story Tease** → "J'ai tout perdu quand..."
- **Value Promise** → "3 façons de [benefit] en 30s"
- **Identity Call-Out** → "Si tu es [group], tu dois savoir..."

### Retention Patterns (Mid)
- **Open Loops** → Maintien de curiosité
- **Pattern Interrupts** → Reset attention (every 7-15s)
- **Value Stacking** → Escalation de valeur
- **Story Peaks** → Pics émotionnels

### Engagement Patterns
- **Comment Bait** → "Team A ou Team B ?"
- **Save Trigger** → Contenu à haute utilité
- **Share Trigger** → Contenu identitaire/émotionnel

## Flags Globaux

```bash
--platform [ig|tt|yt|tw|all]  # Plateforme cible
--niche [niche]               # Contexte niche
--tone [edu|fun|pro|raw]      # Tonalité
--duration [15s|30s|60s|3m]   # Format durée
--viral                       # Optimise viralité
--evergreen                   # Contenu intemporel
--batch                       # Output batch production
```

## Exemples d'Usage

### Workflow Création Rapide
```bash
/cc:trend fitness                    # Identifier tendances
/cc:ideate fitness --trend --viral   # Idées basées tendances
/cc:script [idea] --platform tt      # Script adapté
```

### Workflow Stratégique
```bash
/cc:calendar --month --niche tech    # Plan mensuel
/cc:series "Side Hustle" --episodes 5  # Créer série
/cc:repurpose [content] --to all     # Multiplier reach
```

### Workflow Analyse
```bash
/cc:analyze @competitor --competitor  # Analyse concurrence
/cc:trend [niche] --deep             # Veille approfondie
```

## Structure des Fichiers

```
📁 content-creation-agents/
├── CONTENT-CREATOR.md    # Entry point + quick reference
├── CC-COMMANDS.md        # 8 commandes détaillées
├── CC-AGENTS.md          # 5 agents + coordination
├── CC-PATTERNS.md        # 30+ patterns rétention
└── CC-PLATFORMS.md       # Specs TikTok/IG/YT/Twitch
```

## Token Optimization

Le framework utilise une architecture optimisée :
- Symboles standardisés (📱 TikTok, 📸 IG, ▶️ YT, 🎮 Twitch)
- YAML compact pour les outputs structurés
- Agents auto-activés (pas de config manuelle)
- Patterns pré-intégrés (pas de re-explanation)

## Roadmap

- [ ] Templates visuels (Canva/Figma specs)
- [ ] Analytics integration
- [ ] A/B testing automation
- [ ] Scheduling integration
- [ ] Multi-language support

## License

MIT

---

Made with Claude Code
