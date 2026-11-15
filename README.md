# Astrology Glossary and Free Astrology Course (open data, 7 languages)

🌐 **English** · [中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) <!-- languages -->

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

<!-- faq -->
## Frequently asked questions

### What are the "big three" in astrology?

Your [Sun](terms/planet-sun.md) sign, [Moon](terms/planet-moon.md) sign and Rising sign, also called the [Ascendant](terms/term-ascendant.md). You need your birth time to know your Rising sign.

### What do I need to calculate my birth chart?

Your birth date, birth time and birth place. Without a birth time you can still see where the Sun, Moon and planets were, but not your Rising sign or exact degrees. Try the [free birth chart calculator](https://astrea.secondwindltd.xyz/tools/birth-chart-calculator/).

### What is the difference between a zodiac sign and a house?

A sign describes the style in which a planet's theme is expressed. A house points to the area of life where it shows up. A reading combines planet, sign, house and aspects.

### Where can I look up a single astrology term?

Every term has its own page: **[browse all 48 terms](terms/index.md)**, also in [中文](terms/zh/index.md), [日本語](terms/ja/index.md), [한국어](terms/ko/index.md), [Español](terms/es/index.md), [Français](terms/fr/index.md) and [Deutsch](terms/de/index.md).

### Is astrology scientific?

No. Astrology is a traditional interpretive practice. Astrea treats it as a prompt for reflection, not as scientific proof or prediction.

### How can I learn astrology for free?

Start with the [free 32-lesson course](LESSONS.md), or learn inside the [Astrea app](https://play.google.com/store/apps/details?id=app.astrea.astrea) with quizzes and your own chart.
<!-- /faq -->

## License

Text and data: [CC BY 4.0](LICENSE.md). Use it anywhere, including commercially, as long as you credit **Astrea** with a link to https://astrea.secondwindltd.xyz/.

Astrology is a traditional interpretive practice for reflection, not scientific prediction.

---

Made by [SECOND WIND LIMITED](https://secondwindltd.xyz/) · More open resources: [github.com/secondwindlimited](https://github.com/secondwindlimited)
