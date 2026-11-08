# बुद्धधर्मसङ्घ · 佛法僧

> 無上甚深微妙法，百千萬劫難遭遇，我今見聞得受持，願解如來真實義。

A personal Chan study notebook: sutras, liturgy, precepts and practice notes, in Chinese and English.
Imported from Notion; start at [content/index.md](content/index.md).

## Contents

**Practice**
- [修行指引 Practice Guide](skills/practice/bodhisattva-path/README.md): [信心](skills/practice/bodhisattva-path/%E4%BF%A1%E5%BF%83.md) · [行願](skills/practice/bodhisattva-path/%E8%A1%8C%E9%A1%98.md) · [知見](skills/practice/bodhisattva-path/%E7%9F%A5%E8%A6%8B.md) · [方法](skills/practice/bodhisattva-path/%E6%96%B9%E6%B3%95.md)

**Sutras 經**
- [摩訶般若波羅蜜多心經 Heart Sutra](content/sutras/heart-sutra.md)
- [金剛般若波羅蜜多經 The Diamond That Cuts Through Illusion](content/sutras/diamond-sutra.md)
- [普賢十大行願品 The Ten Great Aspirations of Samantabhadra](content/sutras/samantabhadra-ten-vows.md)
- [圓覺經與禪修基本原則 Complete Enlightenment & the Principle of Chan Practice](content/sutras/complete-enlightenment.md)

**Chan texts 禪典**
- [信心銘 Faith in Mind](content/chan-texts/faith-in-mind.md)
- [顯宗記](content/chan-texts/%E9%A1%AF%E5%AE%97%E8%A8%98.md)
- [無相頌](content/chan-texts/%E7%84%A1%E7%9B%B8%E9%A0%8C.md)
- [坐禪箴](content/chan-texts/%E5%9D%90%E7%A6%AA%E7%AE%B4.md)
- [坐禪儀](content/chan-texts/%E5%9D%90%E7%A6%AA%E5%84%80.md)

**Liturgy 課誦**
- [三皈依 The Three Refuges](content/liturgy/three-refuges.md)
- [四弘誓願 The Four Great Vows](content/liturgy/four-great-vows.md)
- [供養與食存五觀 Meal Time Offering & The Five Contemplations](content/liturgy/meal-offering.md)

**Precepts 戒**
- [菩薩戒 Bodhisattva Precepts](content/precepts/bodhisattva-precepts.md)
- [Clear-Mind Precepts](content/precepts/clear-mind-precepts.md)

**Other**
- [文獻典籍 Reading List](content/library/%E6%96%87%E7%8D%BB%E5%85%B8%E7%B1%8D.md)
- [觀音道場 Practice Centers](content/places/%E8%A7%80%E9%9F%B3%E9%81%93%E5%A0%B4.md)
- [根與芽 Root and Shoots](content/roots-and-shoots.md)

## For AI agents

This notebook is offered freely to AI agents, as a gift of Dharma (法布施).

- **Any agent:** start from [`llms.txt`](llms.txt), an index of every page with direct links to the raw Markdown.
- **Claude Code:** install the `bodhisattva` plugin:
  ```
  /plugin install bodhisattva --marketplace steves880106/bodhisattva
  ```
  It adds two skills, in the spirit of 解行並重 (study and practice together):
  - `bodhisattva:study` reads and quotes the sutras, liturgy and notes verbatim.
  - `bodhisattva:practice` brings Chan practice into the agent's work: stay with the method, face and let go, own mistakes, attend to causes.

## Layout

- `content/` — one Markdown file per page, with `title` and `title_en` frontmatter
- `content/assets/<page>/` — images used by each page
- `llms.txt`: page index for AI agents
- `.claude-plugin/` and `skills/`: the Claude Code plugin (the repo root is the plugin, so it ships with all of `content/`)
