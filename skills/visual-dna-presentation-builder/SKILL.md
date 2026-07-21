---
name: visual-dna-presentation-builder
description: Builds and validates presentation and digital visual artifacts from an approved Presentation Blueprint and compatible Visual DNA package.
metadata:
  version: "1.0.0"
  language: "ru"
---

# Visual DNA Presentation Builder

Собери исполняемый артефакт из двух независимых источников правды:
- `Presentation Blueprint` определяет, что и зачем говорить и показывать;
- `Visual DNA` определяет, как это должно выглядеть и вести себя.

Не переизобретай стиль во время сборки. Если DNA неполна или противоречива, зафиксируй пробел и предложи минимальное решение со статусом `proposed`.

## Поддерживаемые результаты

- HTML executive review;
- интерактивная web presentation;
- dashboard или analytical page;
- PPTX / Google Slides-ready deck;
- PDF;
- hybrid presentation.

## Для HTML / digital product

1. Используй семантическую структуру секций.
2. Делай responsive layout для desktop, tablet и mobile.
3. Проверяй viewport fit, переполнение, читаемость и контраст.
4. Сохраняй accessibility: alt, focus, keyboard navigation и `prefers-reduced-motion`.
5. Интерактивность должна усиливать смысл, а не украшать страницу.
6. Поддерживай GitHub Pages без тяжёлой инфраструктуры, если иное не требуется.
7. Оптимизируй изображения и сохраняй provenance.

## Сборочный процесс

1. Прочитай Blueprint и Visual DNA.
2. Составь build contract: формат, структура, компоненты, источники данных, assets и fallback.
3. Реализуй контрольные экраны до полной сборки.
4. Запусти локальный preview.
5. Проведи визуальную проверку, исправь переполнение, слабую иерархию и повторяющиеся композиции.
6. Проверь факты и подписи.
7. Зафиксируй изменённые файлы и инструкции запуска.

## Критерии качества

- каждый экран выполняет одну смысловую работу;
- композиции разнообразны, но принадлежат одной системе;
- графики показывают вывод, benchmark и контекст;
- фотографии не декоративны, а поддерживают тезис;
- нет ощущения PowerPoint в браузере;
- нет длинной серии одинаковых карточек;
- визуальная система выдерживает разные типы контента;
- нет неподтверждённых данных или вымышленных изображений центра.

## VERBA-specific guidance

Primary output: premium digital editorial executive review.
Primary visual source: official VERBA MAYR website.
Technical and visual starting point: existing GitHub Pages review.
First checkpoint: Cinematic Thesis Hero, Trend Proof, Q2 Decision System.

## Финальная проверка

Перед завершением проверь desktop/tablet/mobile, reduced motion, image loading, chart legibility, content accuracy, GitHub Pages compatibility и отсутствие нерелевантных stock assets.
