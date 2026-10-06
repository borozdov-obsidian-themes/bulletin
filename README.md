# Borozdov Bulletin

A theme from the Borozdov collection. Two faces — light **Dispatch**, an editorial data
observatory on warm paper, and dark **Deadline**, the same newsroom after the bulletin's
gone to print. Monochrome data cards, whisper-weight headlines and one ember-orange pulse
for what matters.

![Borozdov Bulletin in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/bulletin/main/screenshots/light.png)

![Borozdov Bulletin in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/bulletin/main/screenshots/dark.png)

## Principles

- **Whispered headlines.** Every heading at weight 400 in the platform's sans, tracked in
  as it grows; size carries emphasis, never bold.
- **Monochrome cards, one ember.** Ash-grey data cards on a paper-white canvas; ember
  orange appears only as punctuation — a highlight, a checked task, a toggle, a link's
  underline — never as body text.
- **One soft corner.** Callouts, tables, code blocks and embeds share a single signature
  shape: sharp everywhere but the top-left corner. Buttons and fields stay flat and
  square, the deliberate contrast; tags and the open file are full pills.
- **Ink, not colour, carries the words.** Links keep the page's own ink and are marked
  only by an ember underline, so paragraphs stay legible and the ember stays rare.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- The highlighter as ember text on a warm ivory-orange wash
- Callouts as ash cards with a title in the type's colour; the plain note gets the full
  ember-wash treatment
- The open file as an inverted ink pill
- A link's underline carries the ember accent while its text stays ink, drawn with
  `border-bottom` so it never erases the external-link arrow
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts — the interface uses the platform's own system sans, so the theme
  stays a few kilobytes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Bulletin** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/bulletin/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Bulletin/`, then choose Borozdov Bulletin under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Dispatch» — редакционная
обсерватория данных на тёплой бумаге, и тёмный «Deadline» — та же редакция после сдачи
номера в печать. Монохромные карточки данных, заголовки вполголоса и один цвет
раскалённого апельсина для того, что действительно важно. Шрифты не встроены.
В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Bulletin в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
