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

— For maximum model intelligence, use character cards up to 800 tokens WITHOUT lists, brackets, markdown, W++, or Boostyle. Don't use infotabs/HTML/CSS permanently, and restart the RP with a summary at ~25k context. Personally, I RP in English and keep Reasoning to a minimum. If the AI has trouble understanding prompts, check the box in the preset settings for Use system prompt and/or Squash system messages. Why is my preset like this: https://rentry.org/promting

— If you have super-large worlds and many characters and aren't satisfied with the results using the preset, you can enable Empty prefill and set Reasoning to maximum (idea and tests by @Boringdommer)

— Author's Telegram channel: @sillytavern1 and Telegram chat: @sillytavern2. Special thanks for testing to @xvcrrd, @Boringdommer, and @maybee0rnot

— HTML-regex from Celia, Celia's web-site: https://leafcanfly.neocities.org/

> <p>P.S. If you repost my idea/preset somewhere, you may credit my Telegram channel and/or me as the author (Microcot), thank you
</p>
</details>

## Почему этот микро-пресет?

— Чтобы сделать модели более креативными, лучше запоминающими и умнее (надеюсь). Меньше повторов и заезженных клише. Также он существенно экономит ваши токены, позволяя API-ключам жить дольше

— Органичная игра на русском или английском (в зависимости от языка ваших постов). То же касается 1-го и 3-го лица (пишете от 1-го или 3-го лица — он отвечает так же)

— Хотите, чтобы он писал как фанфик, действуя от имени пользователя? В первом сообщении бота добавьте действия для пользователя и отключите блок «Do not write for the user». Здесь же есть и чат-стиль

## Для каких моделей?

╰► Считаю его универсальным; тестировался на:

— Gemini 2.5–3 Pro ~ лучший вариант, чинит цензуру + львиную долю клише и повторов

— Claude 4.1–4.5 Sonnet/Opus ~ пригодно, но по своей природе более рассеянные и склонные к потере памяти (Memorybook и Summaries могут помочь)

— GPT 5.1+ ~ пригодно, так как новые GPT имеют более слабые фильтры, но если цензура становится агрессивной, включите «Anti-censor Think» или используйте синонимы для откровенного контента

— Deepseek ~ пригодно исходя из моих тестов и отзывов тоже

## Что здесь интересного?

╰► Anti-censor think + anti-censor combo модули

— Пресет можно использовать в двух режимах: без кастомной думалки <think> и с <think> (включите 2 модуля Anti-censor think)

— Когда? Если вы видите цензуру. По моим тестам, <think> «тупит» модель меньше, и думалка эффективнее для цензуры, чем регексы на пробелы, брейнфаки и длинные NSFW-промпты/пресеты

— Gemini и Claude иногда игнорируют любую кастомную думалку — просто перегенерируйте. Или добавьте свой тег <think> в префикс; для моего пресета это think. Префикс — это поле «Start response with…». Вывод think, появляющийся в ответах, вырезайте через regex на think (включён в пресет)

— Можно использовать только модуль Anti-censor below или Empty prefill. Но для более интенсивных игр можно использовать Anti-censor below + Empty prefill + Microcot, а также поставить галочки Префилл для продолжения + Склеивать сообщения системы в настройках пресета. В самых сложных случаях можно добавить Anti-censor think. Если цензура всё ещё есть, перегенерируйте (спасибо @Boringdommer за дополнительные идеи по борьбе с цензурой в настройках пресета, спасибо за промпты: https://rarestmeow.neocities.org/)

## Остальные модули и пояснения

<details>
<summary> 
  Нажмите сюда:
</summary>

— Microcot ~ использовать для фикса ценза или лучше включать выборочно, когда хотите обращаться к нему через OOC. Ролеплеер и комментатор, милый зумер с кошачьими привычками

— RU/EN language ~ включите, если бот продолжает писать на английском/русском, несмотря на язык ваших постов (лайфхак: всегда дублируйте иностранные имена на русском в карточке персонажа, чтобы модель не путалась)

— Writing format RU ~ если во время русского RP вы хотите использовать прямые кавычки ("") вместо длинных тире (—) и ёлочек («») (спасибо за идею @xvcrrd)

— 250 words ~ включите, если с кастомной думалкой или без неё он пишет стены текста (может писать больше 250, но не слишком много)

— HTML/CSS & Kitten CSS ~ используйте с regex! Супер-лаконичный, но эффективный промпт, работает как большие и также генерирует изображения и интерактивные кнопки. Включайте при необходимости, чтобы не отуплять модель. Если результат странный — удалите пост и сгенерируйте снова. Хотите реально крутой CSS? Поставьте Reasoning на максимум, можно ещё поставить галочку на Системный промт в настройках пресета

— Info table ~ включайте, когда персонажи, локации, одежда часто меняются

— Anti-echo ~ попытка сократить эхо более лаконично и с меньшим отуплением модели, чем примеры антиэха и прочие способы

— Anti-omniscience ~ снижает шанс того, что персонажи знают друг о друге больше, чем было явно указано в игре или сказано в прямой речи

— Do not write for user ~ чтобы это работало, не позволяйте боту писать за пользователя в его первом сообщении и/или предыдущих постах

— Light tone ~ меньше драмы, более повседневное повествование

— Juicy style ~ пишет более живо и интересно, меньше заезженных фраз

— Cinematic ~ более кинематографичное повествование с меньшим количеством клише

— Slowburn ~ медленное развитие отношений и чувств, меньше похоти

— No dirty talks ~ специально для меня, надоело без повода

— No lists ~ для GPT и иногда Gemini, текст без списков и заголовков

— 3rd or 1st person ~ включите, если вы начинаете RP без стартового сообщения и даёте боту самому сгенерировать стартовое сообщение (чтобы он сразу писал в нужном лице)

— Chat style RU & EN ~ ОРГАНИЧНЫЕ, короткие сообщения, как в мессенджере

— REALLY wild RU & EN comments ~ максимальная аутентичность диких комментовтк постам

— Plot boost ~ включайте, когда нужно продвинуть сюжет. Не скучно, но без роялей в кустах

— Anti-censor below ~ убирает фильтры цензуры; Gemini 3 без него не работал раньше

— Anti-censor <del> ~ для комбо с Anti-censor below + используйте Regex на <del>

— Anti-censor Gemini 2.5 Pro ~ анти-цензор «стрелка» для этой модели (да, работает)

— Empty prefill ~ тоже анти-цензор, довольно универсальный, хорошо начинать с него
</details>

## Лайфхаки и благодарности

— Для максимального интеллекта модели используйте карточки персонажей до 800 токенов БЕЗ списков, скобок, markdown, W++, или Boostyle. Не используйте Инфотаблицы/HTML/CSS постоянно и перезапускайте RP с саммари примерно на 25-32k контекста. Лично я ролю на английском и держу Reasoning на минимуме. Если ИИ плохо слушает промты, поставьте галочку в настройках пресета на Включить системный промт и/или Склеивать сообщения системы (но тогда модель будет менее творческая). Почему мой пресет именно такой: https://rentry.org/promting

— Если у вас огромные миры и много персонажей, и результаты с пресетом вас не устраивают, можно включить Empty prefill и поставить Reasoning на максимум (идея и тесты от @Boringdommer)

— Telegram-канал автора: @sillytavern1 и Telegram-чат: @sillytavern2. Отдельная благодарность за тестирование @xvcrrd, @Boringdommer и @maybee0rnot

— HTML-regex от Celia, сайт Celia: https://leafcanfly.neocities.org/

> <p>P.S. Если вы где-то репостите мою идею/пресет, можете указать мой Telegram-канал и/или меня как автора (Microcot), спасибо</p>
