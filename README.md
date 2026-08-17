# Discord Timestamp Generator

Generate Discord timestamp codes that display correctly in everyone's own timezone — no more "is that your 3pm or mine?"

**[Try it live →](https://garnservo.github.io/Discord-Timestamp-Generator/)**

## What it does

Pick a date and time, choose a display format, and copy a `<t:1786954860:D>`-style code. Discord renders that code locally for every reader, in their own timezone and language, instead of showing whatever time you typed.

A live message preview shows exactly how it'll look before you copy it.

## Formats

- Short Time / Long Time
- Short Date / Long Date
- Long Date + Time / Full Date + Time
- Relative ("in 2 hours", "3 days ago")

## Tech

Single self-contained `index.html` — no framework, no runtime dependencies, nothing tracked. A GitHub Actions workflow minifies it on deploy.

## License

MIT — see [LICENSE](LICENSE).