# CLAUDE.md

**Metrology Digest** — новостной дайджест по промышленной метрологии.

## Стек

Astro 6 · TypeScript · MDX · Vercel

## Структура

```
src/content/blog/  — статьи (.md/.mdx)
src/pages/         — маршруты
prompts/           — промпты генерации
public/            — статики
```

## Ключевые правила

- Контент: русский, терминология ГОСТ (не кальки)
- Статьи: 300-500 слов, markdown, без эмодзи и маркетинга
- Только Astro-компоненты, без React/Vue
- Подробные правила в `.claude/rules/`
