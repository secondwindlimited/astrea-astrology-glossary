# Astrology Glossary and Free Astrology Course (open data, 7 languages)

**Learn astrology from zero: a 48-term astrology glossary and a free 32-lesson beginner course covering planets, zodiac signs, houses, aspects and how to read a birth chart.** The glossary ships as JSON in English, Chinese, Spanish, French, German, Japanese and Korean.

Maintained by **[Astrea](https://astrea.secondwindltd.xyz/)**, the astrology app with a personal birth chart, daily readings, an AI astrologer you can talk to, and a private journal. [Get Astrea on Google Play](https://play.google.com/store/apps/details?id=app.astrea.astrea).

## What's inside

| File | Contents |
|---|---|
| [`GLOSSARY.md`](GLOSSARY.md) | 48 astrology terms explained in plain English: definition, how to read it, an example, a reflection question and the common misreading |
| [`GLOSSARY.zh.md`](GLOSSARY.zh.md) | 占星术语表(简体中文) |
| [`LESSONS.md`](LESSONS.md) | Outline of the free astrology foundations course, with a link to every lesson |
| [`data/glossary.json`](data/glossary.json) | The full glossary in 7 languages (`en`, `zh`, `es`, `fr`, `de`, `ja`, `ko`) |

## What the glossary covers

- **Planets**: Sun, Moon, Mercury, Venus, Mars, Jupiter, Saturn, Uranus, Neptune, Pluto
- **Zodiac signs**: Aries through Pisces, with element and modality
- **Houses**: the twelve houses and the life areas they point to
- **Aspects**: conjunction, sextile, square, trine, opposition
- **Chart basics**: natal chart, Ascendant (rising sign), tropical zodiac, and more

Each term has the same five parts, so it works as flashcards, tooltips or LLM grounding data:

```json
{
  "id": "planet-sun",
  "category": "planet",
  "copy": {
    "en": {
      "name": "Sun",
      "definition": "A symbolic prompt for self-expression, the direction of effort, and a sense of vitality.",
      "read_with": "…",
      "example": "The Sun in Taurus can open questions about steadiness, sustained effort, and sensory experience.",
      "question": "Where are you most willing to keep investing your effort?",
      "misreading": "The Sun is not an objective measure of a person’s whole personality, career, or life purpose."
    }
  }
}
```

## Free astrology course

Eight modules take you from "what is a birth chart" to completing your first full reading. Start here: **[A Chart Is a Symbolic Map](https://astrea.secondwindltd.xyz/learn/a-chart-is-a-symbolic-map/)**, or see the whole path in [`LESSONS.md`](LESSONS.md) and at [astrea.secondwindltd.xyz/learn](https://astrea.secondwindltd.xyz/learn/).

## Free birth chart calculator

**[Calculate your birth chart free](https://astrea.secondwindltd.xyz/tools/birth-chart-calculator/)**: Sun, Moon, Rising sign and ten planetary placements, computed in your browser. Your birth details are never uploaded or stored.

## Why this glossary

- **Beginner-first.** Every term is explained without jargon and with a worked example.
- **Honest.** Each entry names the common misreading, so you learn what a placement does *not* mean.
- **Seven languages**, one consistent structure.
- **Built for apps and AI.** Stable IDs, clean JSON.

## License

Text and data: [CC BY 4.0](LICENSE.md). Use it anywhere, including commercially, as long as you credit **Astrea** with a link to https://astrea.secondwindltd.xyz/.

Astrology is a traditional interpretive practice for reflection, not scientific prediction.

---

Made by [SECOND WIND LIMITED](https://secondwindltd.xyz/) · More open resources: [github.com/secondwindlimited](https://github.com/secondwindlimited)
