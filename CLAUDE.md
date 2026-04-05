# Workshop: Arabic

## Purpose

Language workshop for learning Arabic — the most important words and phrases for daily interaction.

## Target Audience

- **Level**: Absolute beginner
- **Native languages**: German, English, or Arabic (for heritage speakers)
- **Goal**: Basic Arabic vocabulary and phrases, reading Arabic script

## Structure

- **10 lessons** covering core vocabulary
- **Interface languages**: Deutsch, English, Arabic
- **Teaching language**: Arabic (ar-SA) — right-to-left script
- **Features**: audio pronunciation, RTL text rendering

## Labels

`Language`

## Conventions

- `q` = Arabic example (teaching language, RTL)
- `a` = translation in interface language
- Arabic script must render correctly (RTL)

## Development

```bash
# Generate audio (Edge TTS) for each interface language
bash generate-audio.sh deutsch/arabic
bash generate-audio.sh english/arabic
bash generate-audio.sh arabic/arabic
```

## See Also

- [Open Learn Platform](https://github.com/openlearnapp/openlearnapp.github.io)
- [Workshop Guide](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/workshop-guide.md)
- [Lesson Schema](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/lesson-schema.md)
- [Workshop Creator Plugin](https://github.com/openlearnapp/plugin-workshop-creator)
