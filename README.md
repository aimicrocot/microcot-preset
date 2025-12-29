# <h1 align="center">microcot /ᐠ . ꞈ.マ</h1>

<p align="center">
  <b>SillyTavern</b> preset NEW (RU & EN) <br>
  <a href="https://files.catbox.moe/4k13xq.json">
  https://files.catbox.moe/4k13xq.json
  </a>
</p>

---

## Why this micro-preset?

— To make models more creative, better at remembering, and smarter. Less repetition and overused clichés. It also significantly saves your tokens, allowing API keys to last longer

— Organic play in Russian or English (depends on the language of your posts). Same goes for 1st and 3rd person (write in 1st or 3rd person, it will reply in the same)

— Want it to write like a fanfic, acting on behalf of the user? In the bot's first message, add actions for the user and disable the "Do not write for the user" block. Chat style is here too

---

## Which models?

— I consider it universal; tested on:

╰►Gemini 2.5–3 Pro ~ best option, fixes censorship + the lion’s share of clichés and repetition

╰►Claude 4.1–4.5 Sonnet/Opus ~ usable, but they are inherently more scattered and prone to memory loss (Memorybook and Summaries can help)

╰►GPT 5.1+ ~ usable, since newer GPTs have weaker filters, but if censorship gets aggressive, enable the "Anti-censor Think" or use synonyms for explicit content

---

## What's interesting?

╰►Anti-censor think

— The preset can be used in two modes: without <think> and with <think> (enable 2 Anti-censor think modules)

— When? If you see censorship. Based on my tests, <think> dumbs the model down less and is more effective than space regexes, brainf*cks, and long NSFW prompts

— Gemini and Claude sometimes ignore any custom think, reroll. Or add your thinker tag to the prefix; for my preset it's think. The prefix is the "Start response with…" field. think output that appears in responses should be cut via regex on think (included with the preset)

— 2 CSS styles up to 150 tokens long (instead of common CSS styles of 500-1000+ tokens). Kitten CSS and Universal CSS with interactive buttons, glasses, and sliders

---
  
## What other modules are there?

<details>
<summary> 
  Click here:
</summary>
 
╰►Microcot ~ best enabled selectively when you want to address him via OOC. A roleplayer and commentator, a cute zoomer with cat-like habits. Can slightly help with censor filters. Currently consists of 2 modules: one funny-cringe style, one more assistant-like

╰►Russian language ~ enable if bots keep writing in English despite your Russian posts (lifehack: always duplicate foreign names in Russian in the character card so the model doesn't get confused)

╰►Writing format ~ if you want, during Russian RP, to use straight quotes ("") instead of em dashes (—) and angle («») quotes (thanks @xvcrrd)

╰►Post up to 250 words ~ enable if, with or without the thinker, it writes wall-of-text responses (can write more than 250, but not too long)

╰►HTML/CSS & Kitten CSS ~ use with regex! Super-laconic but effective prompt, works like large ones and also generates images and sometimes interactive. Enable only when needed to avoid slowing the model down. If you get a strange result, delete the post and generate again. Want some seriously cool CSS? Set Reasoning to max

╰►Info table RU & EN ~ enable when characters/locations/outfits change frequently

╰►Anti-echo OOC ~ an attempt to reduce echoing more concisely and with less model degradation (learned from @maybee0rnot)

╰►Anti-omniscience ~ reduces the chance that characters know more about each other than was explicitly stated in the game

╰►Do not write for user + mini anti-echo ~ for this to work, do not allow the bot to write for the user in its first message and/or previous posts

╰►Juicy style ~ writes more vividly and interestingly, fewer overused phrases

╰►Cinematic ~ a more cinematic narrative that uses less clichés (slop)

╰►Slowburn ~ slow development of relationships and feelings

╰►Realistic horny ~ enable when realism is needed in horny content for male characters, so they don't walk around permanently horny without breaks

╰►3rd or 1st person ~ enable if you start RP without starter message and let the bot generate the opening itself (so it immediately writes in the desired person)

╰►Chat style RU & EN ~ ORGANIC, short messages like in a messenger

╰►REALLY wild RU & EN comments on posts ~ maximum Russian authenticity

╰►Light tone ~ tones down drama, casual narration

╰►Plot boost ~ enable when you need to move the plot forward. Not boring, but without deus ex machina moments

╰►Anti-censorship Gemini 3 ~ removes censor filters; Gemini 3 didn't work without it (inspired by advice from a Discord guru)

╰►Anti-censor Gemini 2.5 Pro ~ anti-censor arrow for this model (yes, it works)

╰►Empty prefill ~ also anti-censor, quite universal, good to start with
</details>

## Lifehacks and thanks

— For maximum model intelligence, use character cards up to 800 tokens WITHOUT lists, brackets, markdown, W++, or Boostyle. Don't use infotabs/HTML/CSS permanently, and restart the RP with a summary at ~25k context. Personally, I RP in English and keep Reasoning to a minimum

— If you have super-large worlds and many characters and aren't satisfied with the results using the preset, you can enable Empty prefill and set Reasoning to maximum (idea and tests by @Boringdommer)

— Author’s Telegram channel: @sillytavern1 and Telegram chat: @sillytavern2. Special thanks for testing to @xvcrrd, @Boringdommer, and @maybee0rnot

> <p>P.S. If you repost my idea/preset somewhere, you may credit my Telegram channel and/or me as the author (Microcot), thank you
</p>
