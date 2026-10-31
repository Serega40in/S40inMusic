# S40in Music — Art Direction & Image Generation Prompts

Рабочее ТЗ для Grok, ChatGPT Image, Midjourney, Flux или другой модели. Цель — создать самостоятельную библиотеку оригинальных изображений для музыкального лейбла **S40in Music**. Сайт: https://serega40in.github.io/S40inMusic/

## 1. Как работать с документом

1. Генерируй каждое изображение отдельно. Не делай коллаж, мудборд, сетку из вариантов или скриншот сайта.
2. Сохраняй файлы с точными именами и в папку assets/art/, указанными ниже. Если генератор выдаёт PNG/JPEG/WebP, используй WebP или JPEG и сообщи об этом — расширения в index.html нужно будет согласованно обновить.
3. Для фоновых артов используй RGB/sRGB без прозрачности. Ориентир 300–800 KB на файл, максимум около 1.5 MB.
4. Не вставляй надписи, логотипы, псевдотекст, водяные знаки, рамки интерфейса или кнопки внутрь изображения. Текст сайта накладывается отдельно.
5. Не меняй названия композиций и не придумывай факты о содержании треков. Не утверждай, что прослушал Suno-треки, если доступа к аудио нет.
6. Не используй платные функции или сервисы. Ничего не покупай.

## 2. Единый художественный язык

S40in — фантазийный музыкальный лейбл о бесконечности творчества. Это не мрачный киберпанк и не детский мультфильм. Направление: **премиальная кинематографическая фантастика, магический реализм, космическая поэзия, архитектура будущего, живая природа и яркая энергия**.

- Палитра: сапфирово-синий, изумрудный, бирюзовый, алый, солнечно-золотой, фиолетовый и жемчужный.
- Драматичный, но доброжелательный свет; объёмный туман, отражения, прозрачные материалы, тонкие световые нити.
- Один ясный главный визуальный образ, понятный даже на экране телефона.
- Детализированные материалы, глубина, чувство масштаба и настоящий кино-арт; чистый силуэт и визуальная дисциплина.
- Магическое — естественная часть мира. Природа и технологии взаимодействуют и растут вместе.
- Избегай дешёвого sci-fi: кислотных HUD-интерфейсов, случайных шестигранников, чрезмерного lens flare, пластиковой игрушечности, плоских стоковых картинок, перегруза и мрачного хоррора.
- Не копируй конкретные фильмы, игры, художников или чужие обложки. Создавай оригинальный мир.

### Общий стиль-блок — добавляй к каждому промпту

Original premium cinematic fantasy concept art for an ambitious independent music label. Sophisticated art direction, exceptional composition, rich luminous colour, believable material detail, atmospheric depth, carefully controlled highlights, emotional resonance, striking silhouette, beautiful at small mobile sizes, professional film-poster quality. No text, no letters, no typography, no logos, no watermark, no UI, no collage, no borders, no mockup, no stock-photo look, no childish cartoon style, no gloomy horror mood, no oversaturated visual clutter. Create a unique image, not a variation of an existing copyrighted poster.

## 3. Список файлов и размеры

Сейчас на сайте используются временные SVG-иллюстрации. Финальные изображения должны заменить их по назначению. Если сохраняешь в WebP, используй такие имена:

| Файл в assets/art/ | Назначение | Рекомендуемый размер |
|---|---|---|
| s40in-universe.webp | Главная вселенная лейбла | 1600×1200, 4:3 |
| qun.webp | Вселенная QUN | 1200×1400, вертикаль |
| lkm.webp | ЛКМ — модульная архитектура | 1200×1400, вертикаль |
| tft-home.webp | TFT Home — дом будущего | 1200×1400, вертикаль |
| eira.webp | Эйра — живые дома и природа | 1200×1400, вертикаль |
| musical-cosmos.webp | Космическая музыка | 1200×1200, квадрат |
| leni.webp | Лени — музыкальный персонаж / танцевальная история | 1200×1200, квадрат |
| omny-galaxy.webp | Omny galaxy | 1200×1200, квадрат |
| album-opening.webp | Стартовая композиция альбома S40in Music | 1200×1200, квадрат |
| eira-first-meeting.webp | «Эйра — первая встреча» | 1200×1200, квадрат |
| musical-fragment.webp | Фрагмент первого мюзикла | 1200×1200, квадрат |
| s40in-contact.webp | Финальный блок «Музыка находит своих людей» | 1600×1000, 16:10 |
| new-track-v1.webp | Обложка версии 1 новой композиции Suno | 1200×1200, квадрат |
| new-track-v2.webp | Обложка версии 2 новой композиции Suno — предпочтительная | 1200×1200, квадрат |

**Логотип:** исходный файл photo_2026-10-31_21-44-50.jpg используется в шапке и главном блоке. Не заменяй его случайным новым логотипом и не встраивай его в другие арты. Если требуется улучшить исходник, создай отдельный файл s40in-logo-polished.webp, сохранив оригинал; не меняй буквы и сам фирменный знак.

## 4. Промпты для изображений сайта

### A. S40in Universe — assets/art/s40in-universe.webp

Create the key visual for S40in Music, a boundless universe of original music, imagination and emotion. A majestic luminous cosmic horizon opens around a radiant pearl-gold star, surrounded by flowing sapphire, emerald, violet and ruby nebulae. Elegant orbital ribbons of light curve like musical phrases through a deep celestial atmosphere. Tiny distant worlds suggest infinite creative possibilities without becoming a generic solar-system diagram. The composition feels uplifting, powerful, grateful to life, spacious and refined. Main luminous subject slightly to the right; left side calmer and darker so website text can remain readable. Deep cinematic perspective, exquisite glow, subtle particles, luxury editorial art direction. No typography. Add the common style block.

### B. QUN — assets/art/qun.webp

Depict QUN as a beautiful living network connecting people, creativity, knowledge and nature. A luminous emerald-and-sapphire crystalline core floats in a vast atmospheric space, connected to distant glowing habitats by delicate organic light paths. Geometry feels elegant and meaningful, part sacred architecture and part advanced living technology, without literal religious symbols. Turquoise, emerald, deep blue, pearl and small warm-gold highlights. A sense of cooperation, trust, clarity and growth. No letters, no logo, no blockchain clichés, no floating UI panels. Vertical cinematic composition, clear central focal point. Add the common style block.

### C. ЛКМ — assets/art/lkm.webp

A visionary but believable modular timber house in a northern landscape near Saint Petersburg, reimagined as exceptional contemporary architecture. Warm natural wood, precise structural rhythm, expansive glass, a sculptural roofline and beautifully integrated terraces. The building sits among mature trees, meadow grasses and reflective water; distant forest and soft northern evening light. Celebrate real craftsmanship, flexible modular construction and the possibility of extraordinarily beautiful homes. Premium architectural photography blended with cinematic concept art, natural wood grain and credible construction details, rich but restrained colour, no people in foreground, no text, no logos. Vertical composition. Add the common style block.

### D. TFT Home — assets/art/tft-home.webp

An advanced timber-frame eco home of the near future, designed with the warmth and elegance of a premium architectural magazine. Expressive timber structure, layered natural materials, generous glazing, soft golden interior light and a roof that flows naturally with the surrounding landscape. Show the intelligence of construction through visible design, not diagrams or text. Forest edge, calm water, grasses and a luminous dusk sky with blue and amber tones. Plausible architecture, no impossible floating structure, no labels, no text. Vertical cinematic architectural image. Add the common style block.

### E. Эйра — assets/art/eira.webp

A breathtaking living home that has grown together with an enormous ancient tree. This is not a house built on top of a tree: its architecture emerges organically from trunk, branches, roots and living wood, as if tree and home had always been one organism. Huge graceful boughs form sheltered rooms and curved balconies; warm lights glow softly inside, vines and leaves shimmer with dew, water and wind move through the scene. The home feels conscious in a gentle, welcoming way, a co-creator with its inhabitants. Magical eco-village in the distance, subtle luminous plants, emerald, jade, deep teal, moonlit sapphire and liquid gold. Wonder, intimacy, safety, beauty and belonging; not horror, not a game screenshot. Vertical cinematic key art. Add the common style block.

### F. Космическая инструментальная музыка — assets/art/musical-cosmos.webp

A visual expression of instrumental music as the joy and force of being alive. A radiant cosmic pearl emerges from a vast dark-blue and violet nebula; concentric waves of light expand outward like sound made visible, joined by fine golden arcs and luminous turquoise currents. The universe feels weightless, powerful, grateful, ecstatic and serene at once. Sophisticated abstract cosmic art, not a literal musical instrument, not generic galaxy wallpaper. Strong simple central form that reads at thumbnail size, exquisite highlights, depth and premium cinematic album-cover finish. Square composition, no text. Add the common style block.

### G. Лени — assets/art/leni.webp

Original music-cover art for a playful, rhythm-driven story about a character named Leni and a modular home. A beautifully designed small modern timber house becomes a charming expressive protagonist through lighting, silhouette and motion, without becoming a childish toy. Warm wood, dark-green framing, amber window-light and bold accents of magenta and electric blue. Dynamic sweeping movement, polished cinematic lighting, a hint of playful dance and urban rhythm. Distinctive and memorable, balancing humour and craftsmanship. Do not depict or imitate any existing cartoon character. Square album-cover composition, no text. Add the common style block.

### H. Omny galaxy — assets/art/omny-galaxy.webp

An original vision of an Omny galaxy: an immense spiral of many luminous worlds, each with a different colour and atmosphere, revolving around a calm bright centre. Sapphire, emerald, violet, coral-red and warm gold merge into elegant cosmic ribbons. The galaxy feels alive, plural, interconnected and full of discovery. Beautiful deep-space scale, luminous nebula clouds, restrained star detail and a striking silhouette. Not a generic spiral-galaxy photograph. Square composition, no text. Add the common style block.

### I. Стартовая композиция альбома — assets/art/album-opening.webp

The opening image of the first S40in Music album: the first dawn of an infinite creative universe. A single brilliant golden-white pulse ignites in a deep sapphire void; rings of emerald, cyan, violet and scarlet light unfold like the first breath of existence. Communicate a powerful beginning, movement, gratitude for life, boundless possibility and joyful energy. Epic orchestral scale suggested visually, but keep the image elegant and uncluttered. One unforgettable central symbol, cinematic volumetric light, premium album artwork. Square composition, no text. Add the common style block.

### J. Эйра — первая встреча — assets/art/eira-first-meeting.webp

A tender, awe-filled first encounter with Eira, the living tree-home. In a vast twilight forest, an enormous ancient tree opens a softly glowing natural chamber among its roots and branches. A small distant human silhouette may establish scale, looking toward the welcoming warm light. The tree feels wise and gentle, not anthropomorphic or frightening. Luminous leaves, mist, moss, reflections on water, emerald and jade with delicate gold and moonlit blue. A sense of recognition, homecoming and a beautiful future shared by humans and nature. Square cinematic album cover, no text. Add the common style block.

### K. Фрагмент первого мюзикла — assets/art/musical-fragment.webp

Original cinematic musical-theatre artwork: a grand mysterious theatre suspended between a dreamlike city and the cosmos. A monumental stage glows with amber footlights; rich velvet-red shadows, midnight blue, gold dust and shafts of celestial light create emotional scale and anticipation. Suggest the power of a great original musical soundtrack through sweeping curtains, architectural depth and a distant radiant stage, without depicting any known musical, performer or copyrighted character. Elegant, operatic, emotionally intense, timeless and premium rather than pop-concert-like. Square composition, no text. Add the common style block.

### L. Музыка находит своих людей — assets/art/s40in-contact.webp

A poetic image about music connecting people across a boundless universe. Several distant luminous landscapes are connected by fine flowing ribbons of coloured light, like melodies travelling from one heart to another. Small human silhouettes may appear as subtle scale cues, looking toward the same radiant horizon. Warm gold, sapphire, emerald, violet and coral highlights; spacious, hopeful, elegant, inclusive and emotionally sincere. Premium closing image for an independent music label, with calm negative space for a website heading. Wide 16:10 cinematic composition, no text. Add the common style block.

## 5. Две новые композиции Suno

Версия 1: https://suno.com/s/XHuPtg06MeO3CWp4  
Версия 2 — сейчас нравится больше: https://suno.com/s/GmW2CBFiVoI2aOYy

Сделай две отдельные обложки, чтобы их можно было сравнить. Не утверждай, что прослушал треки, если модель не имеет доступа к аудио. Если известны только ссылки, используй концепцию первой музыкальной главы S40in: бескрайний космос, сила, радость жизни, благодарность, лёгкость и эпический размах.

### Версия 1 — assets/art/new-track-v1.webp

Create a premium original square cover for the first new S40in Music composition. Visualize a luminous wave of cosmic energy travelling through a deep sapphire universe, with elegant golden and emerald filaments, soft violet nebulae and a bright horizon. The feeling is powerful yet light, ecstatic yet peaceful, a celebration of life and creative freedom. Bold clear focal point, cinematic orchestral scale, refined material detail, no typography, no logo. Add the common style block.

### Версия 2 — предпочтительная — assets/art/new-track-v2.webp

Create a stronger, more emotionally arresting alternative cover for a new S40in Music composition. A radiant living star bursts into a graceful expanding aurora of emerald, electric blue, gold, violet and a restrained scarlet accent; sweeping ribbons curve like a symphony moving through infinite space. The composition should feel like the instant life recognises its own wonder: immense power, joy, gratitude, freedom, weightlessness and transcendence. Sophisticated and iconic, not aggressive, not dark, not cluttered. One unforgettable centre of light, exceptionally beautiful cinematic atmosphere, premium original album art. Square composition, no text. Add the common style block.

После выбора обложки добавь её в каталог отдельным файлом. Сами аудио и права на композиции эта инструкция не изменяет.

## 6. Идеи для будущих релизов — генерировать только когда они появятся на сайте

- **«Без всего»** — минимальная жемчужная точка света в почти бесконечном тихом пространстве, чувство глубины и присутствия.
- **«Древо Энтов»** — древний лес как величественное разумное сообщество; придуманные оригинальные деревья, без копирования известных персонажей.
- **«Послание Нага»** — таинственный водный космос, изящные спирали, бирюза и золото; не копировать узнаваемый дизайн чужих существ.
- **«Квантовая симфония»** — несколько цветовых волн, складывающихся в гармоничную структуру, ощущение музыки и материи.
- **«Дом на колёсах»** — мобильный дом как красивое архитектурное путешествие через открытый ландшафт.

## 7. Проверка перед загрузкой

- [ ] Каждый файл — отдельная полноценная картинка, не коллаж.
- [ ] Имя файла совпадает с таблицей.
- [ ] Картинка читается в маленьком размере и не теряет главный объект при обрезке.
- [ ] Нет текста, случайных букв, логотипов и водяных знаков.
- [ ] Нет артефактов, деформированной архитектуры или неестественных деталей.
- [ ] Цвета согласуются с сайтом, но изображения не выглядят одинаковыми.
- [ ] Для сайта создан оптимизированный файл, исходник высокого качества сохранён.
- [ ] Исходный логотип и исходные изображения не удалены и не перезаписаны.

## 8. Что вернуть после генерации

Верни папку assets/art/ с готовыми файлами и краткий список: имя файла, раздел сайта, фактическое разрешение, расширение и файлы, которые не удалось сгенерировать. Не меняй код сайта, ссылки Suno или названия композиций. После загрузки изображений в репозиторий их можно подключить отдельным коммитом.
