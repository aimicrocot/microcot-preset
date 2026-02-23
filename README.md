# <h1 align="center">Microcot /ᐠ . ꞈ.マ </h1>

<p align="center">
SillyTavern preset RU/EN<br>
</p>

---

## English guide

<details>
  
## Why this micro-preset?

— To make models more creative, better at remembering, and smarter (I hope so). Less repetition and overused clichés. It also significantly saves your tokens, allowing API keys to last longer

— Organic play in Russian or English (depends on the language of your posts). Same goes for 1st and 3rd person (write in 1st or 3rd person, it will reply in the same)

— Want it to write like a fanfic, acting on behalf of the user? In the bot's first message, add actions for the user and disable the "Do not write for the user" block. Chat style is here too

---

## Which models?

╰► I consider it universal; tested on:

— Gemini 2.5–3 Pro ~ best option, fixes censorship + the lion’s share of clichés and repetition

— Claude 4.1–4.5 Sonnet/Opus ~ usable, but they are inherently more scattered and prone to memory loss (Memorybook and Summaries can help)

— GPT 5.1+ ~ usable, since newer GPTs have weaker filters, but if censorship gets aggressive, enable the "Anti-censor Think" or use synonyms for explicit content

— Deepseek ~ usable based on reviews and my tests too

---

## What's interesting?

╰► Anti-censor think + anti-censor combo modules

— The preset can be used in two modes: without <think> and with <think> (enable 2 Anti-censor think modules)

— When? If you see censorship. Based on my tests, <think> dumbs the model down less and is more effective than space regexes, brainf*cks, and long NSFW prompts

— Gemini and Claude sometimes ignore any custom think, reroll. Or add your thinker tag to the prefix; for my preset it's think. The prefix is the "Start response with…" field. think output that appears in responses should be cut via regex on think (included with the preset)

— You can use just the Anti-censor below module or Empty prefill. But for more intense games, you can use the Anti-censor below + Empty prefill + Microcot module, and also check the box for Continue prefill + Squash system messages in the preset settings. In the most complex cases, you can also add the Anti-censor thinker. Reroll if it continues to be censored (thanks to @Boringdommer for additional ideas on censorship in preset settings, thanks for prompts: https://rarestmeow.neocities.org/)

---
  
## What other modules are there?

<details>
<summary> 
  Click here:
</summary>
 
— Microcot ~ best enabled selectively when you want to address him via OOC. A roleplayer and commentator, a cute zoomer with cat-like habits. Can slightly help with censor filters

— RU/EN language ~ enable if bot keep writing in English/Russian despite your language posts (lifehack: always duplicate foreign names in Russian in the character card so the model doesn't get confused)

— Writing format ~ if you want, during Russian RP, to use straight quotes ("") instead of em dashes (—) and angle («») quotes (thanks @xvcrrd)

— Post up to 250 words ~ enable if, with or without the thinker, it writes wall-of-text responses (can write more than 250, but not too long)

— HTML/CSS & Kitten CSS ~ use with regex! Super-laconic but effective prompt, works like large ones and also generates images and sometimes interactive. Enable only when needed to avoid slowing the model down. If you get a strange result, delete the post and generate again. Want some seriously cool CSS? Set Reasoning to max

— Info table ~ enable when characters/locations/outfits change frequently

— Anti-echo ~ an attempt to reduce echoing more concisely and with less model degradation (learned from @maybee0rnot)

— Anti-omniscience ~ reduces the chance that characters know more about each other than was explicitly stated in the game

— Do not write for user ~ for this to work, do not allow the bot to write for the user in its first message and/or previous posts

— Light tone ~ less drama, casual narration

— Juicy style ~ writes more vividly and interestingly, fewer overused phrases

— Cinematic ~ a more cinematic narrative that uses less clichés 

— Slowburn ~ slow development of relationships and feelings, less horny

— No dirty talks ~ special for me, sick of it

— No lists ~ for GPT and sometimes Gemini

— 3rd or 1st person ~ enable if you start RP without starter message and let the bot generate the opening itself (so it immediately writes in the desired person)

— Chat style RU & EN ~ ORGANIC, short messages like in a messenger

— REALLY wild RU & EN comments on posts ~ maximum authenticity

— Plot boost ~ enable when you need to move the plot forward. Not boring, but without deus ex machina moments

— Anti-censor below ~ removes censor filters; Gemini 3 didn't work without it (inspired by advice from a Discord guru)

— Anti-censor <del> ~ combo with Anti-censor below + use Regex <del>

— Anti-censor Gemini 2.5 Pro ~ anti-censor arrow for this model (yes, it works)

— Empty prefill ~ also anti-censor, quite universal, good to start with
</details>

## Lifehacks and thanks

— For maximum model intelligence, use character cards up to 800 tokens WITHOUT lists, brackets, markdown, W++, or Boostyle. Don't use infotabs/HTML/CSS permanently, and restart the RP with a summary at ~25k context. Personally, I RP in English. If the AI has trouble understanding prompts, check the box in the preset settings for Use system prompt and/or Squash system messages. Why is my preset like this: https://rentry.org/promting

— Author's Telegram channel: @sillytavern1

— HTML-regex from Celia, Celia's web-site: https://leafcanfly.neocities.org/
</details>

## Зачем этот микро-пресет

— Написан по руководствам от создателей LLM (Google, Anthropic, GPT) ~ чтобы сделать модели более креативными, лучше запоминающими и более умными

— Меньше повторов и клише ~ потому что чем меньше жёстких инструкций, тем креативнее и живее пишут модели

— Лаконичность, ясность и конкретность ~ экономит токены, поэтому API-ключи живут намного дольше

## Фичи пресета

— Кастомность ~ можно вписать язык, длину ответов, жанры, фетиши, от какого лица будет писать, врубить личность писателя-Микрокота и его комменты

— Раздельные баны на негативные фразы, заезженные слова и конструкции, можете вписать свои

— Антицензная думалка, которую можно усилить, дополнив личностями Микрокотов-гоблинов (включить вместе модули Think и Micro Talks)

— Много мета-штук к самой РП типа HTML/CSS & Img Gen, дневниковых заметок, мыслей, симс, комментов, инфотабов и т.д.

— Регексы на думалку, слова (добавь свои) и HTML/CSS

— Хотите, чтобы он писал как фанфик, действуя от имени пользователя? В первом сообщении бота добавьте действия для пользователя и отключите блок «Do not write for the user» Здесь же есть и чат-стиль

## Для каких моделей?

### Считаю его универсальным, тестировался на:

— Gemini 2.5–3.1 Pro ~ моя основная модель, пресет убирает много цензуры + львиную долю клише и повторов

— Claude 4.1–4.6 Sonnet/Opus ~ пригодно, но по своей природе более рассеянные и склонные к потере памяти (Memorybook и Summaries могут помочь)

— GPT 4-5.2 ~ пригодно, новые GPT имеют более слабые фильтры, но если цензура становится агрессивной, включите Think + Talks или используйте синонимы для откровенного контента

— Deepseek В3-Р1+ ~ пригодно исходя из моих тестов и отзывов тоже

## Про думалку

— Пресет можно использовать в двух режимах: без кастомной думалки и с ней (включите Think и/или Micro Talks)

— Когда включать думалку? Если вы видите цензуру. По моим тестам, кастомная думалка «тупит» модель меньше, чем регексы на пробелы, брейнфаки и длинные NSFW-промпты/пресеты

— Gemini и Claude иногда игнорируют любую кастомную думалку ~ добавьте свой тег думалки в префикс; для моего пресета это <think>. Префиксом я называю раздел «Start response with…» Думалку, появляющуюся в ответах, вырезайте через regex на think (включён в этот пресет)

## Про антиценз

— Для PG-13/прелюдий ~ можно ничего не включать от NSFW, либо использовать только модуль NSFW below или Empty prefill

— Для более интенсивных игр ~ NSFW Below + Empty Prefill + Micro Writer, а также поставить галочки Префилл для продолжения + Склеивать сообщения системы в настройках пресета

— Повышаем градус ролки ~ врубаем префилл I Will или Arrow, если не поможет, вместо него NSWF Below + NSWF Del

— Ещё повышаем градус ~ вместо блоков Below и Del врубаем NSFW On, можно только его, а можно и ещё 2 блока нижн, итого 3 модуля

— В самых сложных случаях ~ допом к NSFW On включить кастомную Think и Talks. Если цензура всё ещё есть, перегенерируйте 

## Лайфхаки

— Для максимального интеллекта модели используйте карточки персонажей до 800 токенов БЕЗ списков, скобок, markdown, W++, или Boostyle

– Не используйте Инфотаблицы/HTML/CSS постоянно и перезапускайте RP с саммари примерно на 25-32k контекста

— Если ИИ плохо слушает промты, поставьте галочку в настройках пресета на Включить системный промт и/или Склеивать сообщения системы (но тогда модель будет менее творческая)

## Контакты и кредиты

— Telegram-канал автора: @sillytavern1, мой подход к промтингу ботов: https://rentry.org/promting

— HTML-regex от Celia: 
https://leafcanfly.neocities.org
Спасибо Мяу за промпты Below и Del: 
https://rarestmeow.neocities.org
