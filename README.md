<!-- microcot README -->

<style>
  .microcot {
    max-width: 900px;
    margin: auto;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
                 "Noto Sans", "Roboto", "Ubuntu", "Cantarell", "Helvetica Neue",
                 Arial, sans-serif;
    line-height: 1.6;
    color: #eaeaea;
  }

  .microcot h1 {
    text-align: center;
    font-size: 2.6em;
    margin-bottom: 0.2em;
  }

  .microcot .subtitle {
    text-align: center;
    opacity: 0.85;
    margin-bottom: 2em;
  }

  .microcot .divider {
    text-align: center;
    margin: 2.5em 0 1.5em;
    font-weight: 600;
    letter-spacing: 0.05em;
  }

  .microcot .divider::before,
  .microcot .divider::after {
    content: "──────────────.ᗢ..─";
    opacity: 0.6;
    display: block;
  }

  .microcot .divider::after {
    content: "╰─..ᗢ.──────────────╯";
  }

  .microcot ul {
    list-style: none;
    padding-left: 0;
  }

  .microcot li {
    margin: 0.6em 0;
  }

  .microcot li::before {
    content: "╰►";
    margin-right: 0.4em;
    opacity: 0.8;
  }

  .microcot .note {
    opacity: 0.9;
    margin-left: 1.2em;
  }

  .microcot .ascii {
    text-align: center;
    white-space: pre;
    font-family: monospace;
    opacity: 0.85;
    margin: 2em 0;
  }

  .microcot .footer {
    opacity: 0.85;
    margin-top: 2em;
  }

  body {
    background: #0e0e11;
  }

  a {
    color: #8bd5ff;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }
</style>

<div class="microcot">

<h1>microcot</h1>
<div class="subtitle">
  preset for SillyTavern  
  <br>
  <a href="https://files.catbox.moe/1kjssb.json">https://files.catbox.moe/1kjssb.json</a>
</div>

<div class="ascii">
꒰ Мяугайд ꒱
 /ᐠ . ꞈ.マ .•°
</div>

<div class="divider">Зачем этот микропресет?</div>

<ul>
  <li>Чтобы модели стали более творческими, помнящими и умными — меньше забывали, повторялись и юзали заезженности</li>
  <li>Сильно экономит токены, позволяя ключам жить дольше</li>
  <li>Супер-органичная игра на русском с возможностью английского (по языку ваших постов)</li>
</ul>

<div class="divider">Для каких моделей?</div>

<p class="note">Считаю универсалом, тестился на:</p>
<ul>
  <li>Gemini 2.5–3 Pro — лучший результат, фиксит ценз и повторюшничество</li>
  <li>Claude 4.1–4.5 Sonnet / Opus — юзабельно, спасают memory book и summaries</li>
  <li>GPT 5.1+ — юзабельно, при агрессивной цензе включайте думалку или синонимы</li>
</ul>

<div class="divider">Что интересного в пресете?</div>

<ul>
  <li>Антиценз думалка
    <div class="note">
      Два режима: с думалкой и без. Эффективнее регексов и длинных NSFW-промтов.
      Есть модуль ограничения длины до ~250 слов.
      Gemini может игнорировать кастомную думалку — это нормально.
    </div>
  </li>
</ul>

<div class="divider">Какие модули есть ещё?</div>

<ul>
  <li>Котячий CSS — милый интерфейс с русскими кнопками и котиками (выключен по умолчанию)</li>
  <li>Киберпанк CSS — консольный интерфейс с кнопками (eng)</li>
  <li>Микрокот + OOC — соролевик и комментатор с кошачьими повадками</li>
  <li>Русский язык — фикс, если боты пишут на английском</li>
  <li>Формат письма — замена «ёлочек» и длинных тире</li>
  <li>Антиэхо Gemini — снижает эхо, особенно с думалкой</li>
  <li>Антивсезнание — персонажи не знают лишнего</li>
  <li>Не пиши за юзера / Пиши за юзера — разные режимы ролки</li>
  <li>3 выбора — варианты развития сюжета</li>
  <li>Сочный стиль, драма-квин, литературный тон</li>
  <li>Слоубёрн / быстрое развитие</li>
  <li>Реалистик хорни / реалистик диалоги</li>
  <li>1 и 3 лицо повествования</li>
  <li>Стиль чата — короткие органичные сообщения</li>
  <li>Дикие RU-комменты, лёгкий тон</li>
  <li>Буст / супер-буст сюжета</li>
  <li>HTML/CSS генерация</li>
  <li>Инфотабличка RU / ENG</li>
  <li>The Stanley Parable Narrator</li>
  <li>Антиценз префилл</li>
</ul>

<div class="divider">Послесловие</div>

<ul>
  <li>Карточки персонажей — до 800 токенов, без списков и markdown</li>
  <li>Ролки тестились от 1 на 1 до 10 персонажей</li>
  <li>Отзывы приветствуются, особенно для больших миров</li>
</ul>

<div class="footer">
  Telegram автора: <b>@sillytavern1</b>  
  <br>
  Чат: <b>@sillytavern2</b>  
  <br><br>
  Спасибо за тесты: @xvcrrd и @maybee0rnot
  <br><br>
  <i>P.S. При публикации указывайте автора — Микрокот</i>
</div>

<div class="ascii">
☆・°。
・゜
°。 ° 。
　　　.・゜
　　゜｡ﾟﾟ･｡･ﾟﾟ。
　　　ﾟ。　 　 ｡ﾟ
　　　　ﾟ･｡･ﾟ
</div>

</div>
