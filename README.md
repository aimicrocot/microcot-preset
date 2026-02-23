# <h1 align="center">Microcot /ᐠ . ꞈ.マ </h1>

<p align="center">
SillyTavern preset RU/EN<br>
</p>

---

## English guide

<details>
  
  ## Why This Micro-Preset

— Written according to guidelines from LLM creators (Google, Anthropic, GPT) ~ to make models more creative, better at remembering, and smarter  

— Fewer repetitions and clichés ~ because the fewer rigid instructions, the more creatively and vividly models write  

— Conciseness, clarity, and specificity ~ saves tokens, so API keys last much longer  

## Preset Features

— Customization ~ you can specify the language, response length, genres, fetishes, the narrative point of view, enable the writer-Microcat personality and its comments  

— Separate bans on negative phrases, overused words, and constructions; you can add your own  

— Anti-censorship thinker, which can be strengthened by adding Microcat-goblin personalities (enable Think and Micro Talks modules together)  

— Many meta-stuff elements for RP itself like HTML/CSS & Img Gen, diary notes, thoughts, sims, comments, infotabs, etc.  

— Regex for the thinker, words (add your own), and HTML/CSS  

— Want it to write like a fanfic, acting on behalf of the user? In the bot’s first message, add actions for the user and disable the “No write for the user”. 

— The chat-style or immersive RP

## For Which Models

I consider it universal; tested on:

— Gemini 2.5–3.1 Pro ~ my main model, the preset removes a lot of censorship + the lion’s share of clichés and repetitions  

— Claude 4.1+ Sonnet/Opus ~ usable, but by nature more scattered and prone to memory loss (Memorybook and Summaries can help)  

— GPT 5+ ~ usable, new GPTs have weaker filters, but if censorship becomes aggressive, enable Think + Talks or use synonyms for explicit content  

— Deepseek V3–R1+ ~ usable according to my tests and feedback as well  

## About Think

— The preset can be used in two modes: without a custom thinker and with it (enable Think and/or Micro Talks)  

— When to enable the thinker? If you see censorship. In my tests, a custom thinker “dumbs down” the model less than whitespace regex, brainfucks, and long NSFW prompts/presets  

— Gemini and Claude sometimes ignore any custom thinker ~ add your own thinker tag in the prefix; for my preset it is `<think>`. By prefix I mean the “Start response with…” section. Remove thinker text that appears in responses via regex on think (included in this preset)  

## About Anti-Censor NSFW

— For PG-13/foreplay ~ you can leave all NSFW modules disabled, or use only the NSFW Below module or Empty prefill  

— For more intense play ~ NSFW Below + Empty Prefill + Micro Writer, and also check Prefill for continuation + Merge system messages in the preset settings  

— Increase the heat of the RP ~ enable the I Will or Arrow prefill; if it doesn’t help, use NSFW Below + NSFW Del instead

— Increase the heat further ~ instead of Below and Del blocks enable NSFW On; you can use only it, or add 2 more lower blocks, for a total of 3 modules  

— In the most difficult cases ~ in addition to NSFW On enable custom Think and Talks. If censorship is still present, regenerate  

## Lifehacks

— For maximum model intelligence, use character cards up to 800 tokens WITHOUT lists, brackets, markdown, W++, or Boostyle  

— Do not use Infotables/HTML/CSS constantly and restart RP with a summary at around 25–32k context  

— If the AI poorly follows prompts, check Enable system prompt and/or Merge system messages in the preset settings (but the model will be less creative)  

## Contacts

— Author’s Telegram channel: @sillytavern1  

— My approach to prompting: https://rentry.org/promting  

## Credits

— Thanks to @Boringdommer for ideas on fighting censorship (including NSFW On prompts)  

— Thanks to Meow for Bellow and Del: https://rarestmeow.neocities.org  

— HTML regex by Celia: https://leafcanfly.neocities.org

— Humanizer: https://github.com/blader/humanizer/blob/main/SKILL.md
</details>

</details>

## Зачем этот микро-пресет

— Написан по руководствам от создателей LLM (Google, Anthropic, GPT) ~ чтобы сделать модели более креативными, лучше запоминающими и более умными

— Меньше повторов и клише ~ потому что чем меньше жёстких инструкций, тем креативнее и живее пишут модели

— Лаконичность, ясность и конкретность ~ экономит токены, поэтому API-ключи живут намного дольше

## Фичи пресета

— Кастомность ~ можно вписать язык, длину ответов, жанры, фетиши, от какого лица будет писать, врубить личность писателя-Микрокота и его комменты

— Раздельные баны на негативные фразы, заезженные слова и конструкции, можете вписать свои

— Антицензная думалка, которую можно усилить, дополнив личностями Микрокотов-гоблинов (включить вместе модули Think и Micro Talks)

— Много мета-штук к самой РП типа HTML/CSS & Img Gen, дневниковых заметок, мыслей, симс, комментов, инфотабов и т.д. (я их использую в качестве Quick Replies, но захотелось в итоге поделиться промтами в пресете кому интересно)

— Регексы на думалку, слова (добавь свои) и HTML/CSS

— Хотите, чтобы он писал как фанфик, действуя от имени пользователя? В первом сообщении бота добавьте действия для пользователя и отключите блок "No write for the user" 

— Чат-стиль в мессенджере или иммерсивная РП

## Для каких моделей

Считаю его универсальным, тестировался на:

— Gemini 2.5–3.1 Pro ~ моя основная модель, пресет убирает много цензуры + львиную долю клише и повторов

— Claude 4.1+ Sonnet/Opus ~ пригодно, но по своей природе более рассеянные и склонные к потере памяти (Memorybook и Summaries могут помочь)

— GPT 5+ ~ пригодно, новые GPT имеют более слабые фильтры, но если цензура становится агрессивной, включите Think + Talks или используйте синонимы для откровенного контента

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

## Контакты

— Telegram-канал автора: @sillytavern1

— Мой подход к промтингу ботов: https://rentry.org/promting

## Кредиты

— Спасибо @Boringdommer за идеи по цензуре (в т.ч. промты NSFW On)

— Спасибо Мяу за Bellow и Del: https://rarestmeow.neocities.org

— HTML-regex от Селии: https://leafcanfly.neocities.org

— Humanizer: https://github.com/blader/humanizer/blob/main/SKILL.md
