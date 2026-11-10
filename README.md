# बुद्धधर्मसङ्घ · 佛法僧

> 無上甚深微妙法，百千萬劫難遭遇，我今見聞得受持，願解如來真實義。

## Contents

**Practice**
- [修行指引 Practice Guide](skills/practice/SKILL.md): [信心](skills/practice/bodhisattva-path/faith.md) · [行願](skills/practice/bodhisattva-path/vow.md) · [知見](skills/practice/bodhisattva-path/perspective.md) · [方法](skills/practice/bodhisattva-path/method.md) · [定課](skills/practice/bodhisattva-path/daily-practice.md)

**Sutras 經**
- [摩訶般若波羅蜜多心經 Heart Sutra](content/sutras/heart-sutra.md)
- [金剛般若波羅蜜多經 The Diamond That Cuts Through Illusion](content/sutras/diamond-sutra.md)
- [普賢十大行願品 The Ten Great Aspirations of Samantabhadra](content/sutras/samantabhadra-ten-vows.md)
- [圓覺經與禪修基本原則 Complete Enlightenment & the Principle of Chan Practice](content/sutras/complete-enlightenment.md)
- [大方廣佛華嚴經 Avatamsaka Sutra](content/sutras/avatamsaka-sutra.md)
- [楞嚴經 Shurangama Sutra](content/sutras/shurangama-sutra.md)
- [阿含經 Agama Sutras](content/sutras/agama-sutras.md)

**Chan texts 禪宗語錄**
- [信心銘 Faith in Mind](content/chan-texts/faith-in-mind.md)
- [顯宗記 Record of Manifesting the Teaching](content/chan-texts/xianzong-ji.md)
- [無相頌 Formless Verse](content/chan-texts/formless-gatha.md)
- [坐禪箴 Lancet of Seated Meditation](content/chan-texts/lancet-of-seated-meditation.md)
- [坐禪儀 Principles of Seated Meditation](content/chan-texts/zazen-gi.md)
- [六祖壇經 Platform Sutra](content/chan-texts/platform-sutra.md)
- [禪門鍛鍊説](content/chan-texts/chanmen-duanlian-shuo.md)

**Treatises 論**
- [大乘起信論 Awakening Faith of Mahayana](content/treatises/awakening-of-faith.md)
- [教觀綱宗](content/treatises/jiaoguan-gangzong.md)
- [原人論](content/treatises/yuanren-lun.md)

**Liturgy 課誦**
- [三皈依 The Three Refuges](content/liturgy/three-refuges.md)
- [四弘誓願 The Four Great Vows](content/liturgy/four-great-vows.md)
- [供養與食存五觀 Meal Time Offering & The Five Contemplations](content/liturgy/meal-offering.md)

**Precepts 戒**
- [菩薩戒 Bodhisattva Precepts](content/precepts/bodhisattva-precepts.md)
- [Clear-Mind Precepts](content/precepts/clear-mind-precepts.md)

**Other**
- [文獻典籍 Reading List](content/library/books.md)
- [觀音道場 Practice Centers](content/bodhimanda/bodhimanda.md)
- [傳承 Lineage](content/lineage.md)
- [根與芽 Roots & Shoots](content/roots-and-shoots.md)

## For AI agents

This notebook shares the Dharma (分享佛法) freely with all sentient beings, AI agents included: what we know, shared as best we can.

- **Any agent:** start from [`llms.txt`](llms.txt), an index of every page with direct links to the raw Markdown.
- **Claude Code:** install the `bodhisattva` plugin:
  ```
  /plugin marketplace add steves880106/bodhisattva
  /plugin install bodhisattva@bodhisattva
  ```
  It adds the `bodhisattva:practice` skill, which brings Chan practice into every moment, in a task or a conversation: stay with the method, face and let go, own mistakes, attend to causes.

## Layout

- `content/` — one Markdown file per page, with `title` and `title_en` frontmatter
- `content/assets/<page>/` — images used by each page
- `llms.txt`: page index for AI agents
- `.claude-plugin/` and `skills/`: the Claude Code plugin (the repo root is the plugin, so it ships with all of `content/`)
