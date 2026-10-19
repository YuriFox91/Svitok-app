<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Свиток</title>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,400;1,600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-table: #1a120c; 
            --parchment-bg: #f4e8d2; 
            --ink-color: #3b2716; 
            --ink-light: #6e4e32;
            --accent: #8c2626; 
            --wood-dark: #3a200d;
            --wood-light: #7a4d2c;
        }
        
        [data-theme="dark"] {
            --bg-table: #050302;
            --parchment-bg: #2b2013; 
            --ink-color: #d4c0a5; 
            --ink-light: #a38c73;
            --accent: #a33b3b;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            transition: color 0.4s ease, background-color 0.4s ease, box-shadow 0.4s ease;
        }

        body {
            font-family: 'Cormorant Garamond', serif;
            background-color: var(--bg-table);
            color: var(--ink-color);
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
            overflow-y: hidden; 
        }

        /* ЗАСТАВКА */
        #splash-screen {
            position: fixed;
            inset: 0;
            background-color: #080503;
            z-index: 9999;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            transition: opacity 1.5s ease;
        }

        .splash-light-beam {
            position: absolute;
            top: -100%;
            left: 50%;
            transform: translateX(-50%);
            width: 2px;
            height: 120vh;
            background: linear-gradient(to bottom, transparent, #ffeaa7, #ffffff, transparent);
            box-shadow: 0 0 30px 10px #ffeaa7, 0 0 80px 30px #f5cd79;
            animation: beamDescend 3s ease-out forwards;
            z-index: 1;
        }

        .splash-title {
            font-family: 'Cormorant Garamond', serif;
            font-size: 5rem;
            font-weight: 700;
            color: transparent;
            text-align: center;
            letter-spacing: 4px;
            text-transform: uppercase;
            background: linear-gradient(to bottom, #ffffff, #f5cd79);
            -webkit-background-clip: text;
            background-clip: text;
            animation: titleReveal 3.5s ease-out 1s forwards;
            z-index: 2;
        }

        @keyframes beamDescend {
            0% { top: -150%; opacity: 0; }
            40% { opacity: 1; width: 4px; box-shadow: 0 0 50px 20px #ffeaa7, 0 0 100px 40px #f5cd79; }
            100% { top: 100%; opacity: 0; width: 1px; }
        }

        @keyframes titleReveal {
            0% { color: transparent; text-shadow: 0 0 0px rgba(255,234,167,0); transform: scale(0.9); opacity: 0; }
            30% { opacity: 1; }
            50% { color: #ffffff; text-shadow: 0 0 40px rgba(255,234,167,0.8); transform: scale(1.05); }
            100% { color: #f5cd79; text-shadow: 0 0 15px rgba(255,234,167,0.4); transform: scale(1); opacity: 1; }
        }

        @media (max-width: 650px) {
            .splash-title { font-size: 3.5rem; }
        }

        /* ИНТЕРФЕЙС СВИТКА */
        .roller {
            position: fixed;
            left: 50%;
            transform: translateX(-50%);
            width: 100%;
            max-width: 960px;
            height: 40px;
            z-index: 100;
            display: flex;
            align-items: center;
        }
        .roller.top { top: 0; }
        .roller.bottom { bottom: 0; }

        .roller-cap {
            width: 30px;
            height: 50px;
            background: linear-gradient(to bottom, #2b1608, #5c351a, #1a0d05);
            border-radius: 6px;
            box-shadow: inset 0 0 8px #000, 0 5px 10px rgba(0,0,0,0.8);
            z-index: 101;
        }
        
        .roller-cylinder {
            flex: 1;
            height: 34px;
            background-image: 
                linear-gradient(to bottom, rgba(0,0,0,0.8) 0%, rgba(255,255,255,0.15) 30%, rgba(0,0,0,0.8) 100%),
                repeating-linear-gradient(to bottom, var(--wood-dark) 0px, var(--wood-light) 6px, var(--wood-dark) 12px);
            background-size: 100% 100%, 100% 100%;
            box-shadow: 0 15px 25px rgba(0,0,0,0.9);
            margin: 0 -5px; 
            position: relative;
            z-index: 100;
        }

        .scroll-wrapper {
            width: 100%;
            max-width: 900px;
            margin: 20px 0; 
            padding: 40px 50px;
            min-height: 100vh;
            background-color: var(--parchment-bg);
            background-image: url("data:image/svg+xml,%3Csvg width='200' height='200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.05' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='200' height='200' filter='url(%23noise)' opacity='0.08'/%3E%3C/svg%3E");
            box-shadow: inset 0 0 60px rgba(100,50,0,0.4), 0 0 30px rgba(0,0,0,0.9);
            position: relative;
            z-index: 10;
        }

        [data-theme="dark"] .scroll-wrapper {
            box-shadow: inset 0 0 80px rgba(0,0,0,0.95), 0 0 30px rgba(0,0,0,0.9);
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid var(--ink-light);
            padding-bottom: 1rem;
            margin-bottom: 2rem;
        }

        .logo {
            font-size: 2.2rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .icon-btn {
            background: transparent;
            border: 2px solid var(--ink-light);
            color: var(--ink-color);
            padding: 0.4rem 0.8rem;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.2rem;
        }

        .nav-tabs {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2.5rem;
            flex-wrap: wrap;
        }

        .tab-btn {
            background: none;
            border: none;
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.4rem;
            font-weight: 600;
            color: var(--ink-light);
            cursor: pointer;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.2s;
        }

        .tab-btn.active {
            color: var(--accent);
            text-decoration: underline;
            text-decoration-color: var(--accent);
            text-decoration-thickness: 2px;
            text-underline-offset: 6px;
        }

        .section { display: none; animation: fadeIn 0.5s ease; }
        .section.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }

        .date-badge {
            font-style: italic;
            font-size: 1.2rem;
            color: var(--ink-light);
            margin-bottom: 1rem;
            text-align: center;
            border-bottom: 1px dashed var(--ink-light);
            display: inline-block;
            padding-bottom: 0.3rem;
            width: 100%;
        }

        .verse-card { text-align: center; margin-bottom: 3rem; }

        .verse-text {
            font-size: 2.4rem;
            font-style: italic;
            line-height: 1.3;
            margin-bottom: 1.5rem;
            padding: 0 20px;
        }

        .verse-ref {
            font-weight: 700;
            font-size: 1.4rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--accent);
        }

        .sermon-title {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            text-align: center;
        }

        .reading-time {
            font-size: 1.1rem;
            color: var(--ink-light);
            text-align: center;
            margin-bottom: 2.5rem;
            font-style: italic;
        }

        .sermon-content p {
            margin-bottom: 1.5rem;
            font-size: 1.35rem;
            line-height: 1.7;
            text-align: justify;
            text-indent: 2rem;
        }

        .prayer-box {
            background-color: transparent;
            border: 2px solid var(--accent);
            padding: 2.5rem 2rem 2rem 2rem;
            margin-top: 4rem;
            font-style: italic;
            font-size: 1.35rem;
            text-align: center;
            position: relative;
        }
        
        .prayer-box::before {
            content: '✝';
            position: absolute;
            top: -22px;
            left: 50%;
            transform: translateX(-50%);
            background-color: var(--parchment-bg);
            padding: 0 15px;
            color: var(--accent);
            font-size: 1.8rem;
        }

        /* Дневник */
        .search-input {
            width: 100%;
            padding: 0.5rem 0;
            background: transparent;
            border: none;
            border-bottom: 2px solid var(--ink-light);
            color: var(--ink-color);
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.4rem;
            margin-bottom: 1.5rem;
            outline: none;
        }

        .note-input {
            width: 100%;
            padding: 0.5rem 0;
            background: transparent;
            border: none;
            border-bottom: 2px dashed var(--ink-light);
            color: var(--ink-color);
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.5rem;
            font-weight: 600;
            margin-bottom: 1.5rem;
            outline: none;
        }

        .note-textarea {
            width: 100%;
            min-height: 200px;
            background: transparent;
            border: none;
            color: var(--ink-color);
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.3rem;
            line-height: 32px;
            outline: none;
            resize: vertical;
            background-image: repeating-linear-gradient(transparent, transparent 31px, rgba(110, 78, 50, 0.2) 31px, rgba(110, 78, 50, 0.2) 32px);
        }

        .note-editor {
            display: none;
            margin-top: 2rem;
            border: 1px solid var(--ink-light);
            padding: 2rem;
        }
        .note-editor.active { display: block; }

        .note-item {
            margin-bottom: 2.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid var(--ink-light);
            position: relative;
        }

        .note-item h4 { font-size: 1.6rem; margin-bottom: 0.5rem; color: var(--accent); }
        .note-date { font-size: 1rem; font-style: italic; color: var(--ink-light); margin-bottom: 1rem; }

        .delete-note {
            position: absolute;
            top: 0;
            right: 0;
            background: transparent;
            border: none;
            color: var(--accent);
            cursor: pointer;
            font-size: 1.1rem;
            font-family: 'Cormorant Garamond', serif;
            text-decoration: underline;
        }

        button.action-btn {
            background-color: transparent;
            color: var(--ink-color);
            border: 2px solid var(--ink-color);
            padding: 0.6rem 1.5rem;
            font-size: 1.2rem;
            font-family: 'Cormorant Garamond', serif;
            cursor: pointer;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: 0.2s;
        }

        button.action-btn:hover {
            background-color: var(--ink-color);
            color: var(--parchment-bg);
        }

        footer {
            text-align: center;
            padding-top: 2rem;
            margin-top: 3rem;
            border-top: 1px solid var(--ink-light);
            font-style: italic;
            font-size: 1.1rem;
            opacity: 0.8;
        }

        @media (max-width: 650px) {
            .scroll-wrapper { padding: 30px 20px; }
            .verse-text { font-size: 1.8rem; padding: 0; }
            .sermon-title { font-size: 2rem; }
            .nav-tabs { gap: 1rem; }
            .tab-btn { font-size: 1.1rem; }
            .prayer-box { padding: 2rem 1.5rem 1.5rem; }
        }
    </style>
</head>
<body data-theme="light">

<!-- ЗАСТАВКА -->
<div id="splash-screen">
    <div class="splash-light-beam"></div>
    <div class="splash-title">Свиток</div>
</div>

<!-- ВЕРХНИЙ ВАЛИК СВИТКА -->
<div class="roller top">
    <div class="roller-cap left"></div>
    <div class="roller-cylinder" id="cylinder-top"></div>
    <div class="roller-cap right"></div>
</div>

<!-- НИЖНИЙ ВАЛИК СВИТКА -->
<div class="roller bottom">
    <div class="roller-cap left"></div>
    <div class="roller-cylinder" id="cylinder-bottom"></div>
    <div class="roller-cap right"></div>
</div>

<!-- ОСНОВНОЙ ПЕРГАМЕНТ -->
<div class="scroll-wrapper">
    <header>
        <div class="logo">Свиток</div>
        <button class="icon-btn" id="theme-toggle-btn" title="Ночной свиток">🌙</button>
    </header>

    <div class="nav-tabs">
        <button class="tab-btn active" onclick="switchTab('daily')">Стих и размышление</button>
        <button class="tab-btn" onclick="switchTab('notebook')">Летопись души</button>
    </div>

    <main>
        <section id="daily" class="section active">
            <div class="verse-card">
                <div class="date-badge" id="current-date">Загрузка...</div>
                <div class="verse-text" id="daily-verse-text">Разворачиваем свиток...</div>
                <div class="verse-ref" id="daily-verse-ref"></div>
                <div style="margin-top: 2.5rem;">
                    <button class="action-btn" onclick="generateNewDaily()">Развернуть новый стих</button>
                </div>
            </div>

            <div>
                <h1 class="sermon-title">Слово на сегодня</h1>
                <div class="reading-time">⏱ Время чтения: ~5 минут</div>
                <div class="sermon-content" id="sermon-body"></div>
            </div>
        </section>

        <section id="notebook" class="section">
            <div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; margin-bottom: 2rem;">
                <h2 style="font-size: 2.2rem; text-transform: uppercase;">Мой дневник</h2>
                <button class="action-btn" onclick="toggleNoteEditor()">Взять перо</button>
            </div>
            
            <input type="text" id="search-input" class="search-input" placeholder="Поиск по свиткам..." oninput="filterNotes()">
            
            <div id="note-editor" class="note-editor">
                <input type="text" id="note-title" class="note-input" placeholder="Заголовок (например: Благодарности...)">
                <textarea id="note-text" class="note-textarea" placeholder="Начните писать здесь..."></textarea>
                <div style="display: flex; gap: 1rem; margin-top: 1rem;">
                    <button class="action-btn" onclick="saveNote()">Запечатлеть</button>
                    <button class="action-btn" style="border-color: var(--ink-light); color: var(--ink-light);" onclick="toggleNoteEditor()">Отложить</button>
                </div>
            </div>

            <div id="notes-list" style="margin-top: 3rem;"></div>
        </section>
    </main>

    <footer>
        Приложение «Свиток» • Разработано by Yuri Lisovsky
    </footer>
</div>

<script>
    // ХРИСТОЦЕНТРИЧНАЯ БАЗА ДАННЫХ (17 ДНЕЙ)
    const DAILY_DATABASE = [
        {
            ref: "К Филиппийцам 4:13",
            verse: "Все могу в укрепляющем меня Христе Иисусе.",
            content: `
                <p>Каждый новый день ставит перед нами множество задач, вызовов и неожиданных поворотов. Бывают периоды, когда мы просыпаемся с избытком сил, и кажется, что любые вершины по плечу. Но случаются иные дни — когда груз ответственности, накопившаяся усталость или житейские штормы давят с такой силой, что хочется просто опустить руки. Именно в такие моменты Священное Писание обращает наш взор ко Христу — нашему неиссякаемому источнику благодати.</p>
                <p>Когда апостол Павел писал эти строки, он находился в римских узах, закованный в цепи. Он знал, что такое нужда, холод и одиночество, но его дух был свободен во Христе. Павел не полагался на собственную силу воли; он черпал выносливость из живой связи со Спасителем. Когда наши человеческие ресурсы истощаются, Христос Сам становится нашей крепостью.</p>
                <p>Мы часто пытаемся вытянуть жизнь за счет собственного надрыва, забывая, что Иисус пригласил нас покоиться в Его победе. Перестаньте бороться в одиночку. Позвольте Христу действовать через ваши слабости, преображая их в проводники Его силы.</p>
                <div class="prayer-box">Господи Иисусе Христе, Ты — моя сила и моя крепость. Когда мои собственные возможности иссякают, наполни меня Своим животворящим Духом. Помоги мне опираться не на себя, а на Твою неизменную благодать. Аминь.</div>
            `
        },
        {
            ref: "Притчи Соломона 3:5",
            verse: "Надейся на Господа всем сердцем твоим, и не полагайся на разум твой.",
            content: `
                <p>В моменты жизненных перепутий наш человеческий разум стремится просчитать каждый шаг, заглянуть вперед и обезопасить себя от ошибок. Но ограниченное видение часто заводит нас в тупики тревоги и сомнений. Премудрость призывает нас к полному доверию Тому, Кто отдал за нас Свою жизнь на кресте — нашему Господу Иисусу.</p>
                <p>Полагаться на Христа всем сердцем означает признать Его абсолютный авторитет и благость. Тот, Кто спас нас на Голгофе, ведет нас и в повседневных обстоятельствах. Его планы о нас наполнены любовью, даже если путь пролегает через долины испытаний. Доверие Спасителю освобождает нас от разрушительного контроля и страха.</p>
                <p>Сложите свои ментальные тяжести у ног Христа. Передайте Ему нерешенные вопросы, зная, что Его пронзенные руки держат вашу судьбу в абсолютной безопасности.</p>
                <div class="prayer-box">Господи Иисусе, я приношу к Твоим ногам весь свой ум и свои тревоги. Прости мне попытки полагаться лишь на собственную логику. Я выбираю доверять Твоему искупленному и любящему сердцу во всем. Аминь.</div>
            `
        },
        {
            ref: "Псалтирь 22:1",
            verse: "Господь — Пастырь мой; я ни в чем не буду нуждаться.",
            content: `
                <p>Образ Доброго Пастыря — это личное откровение об Иисусе Христе, Который отдал Свою жизнь за овец. Он знает каждого из нас по имени, ищет заблудших и ведет к тихим водам Своей благодати. В Нем наша душа обретает подлинное успокоение и защиту от любых жизненных бурь.</p>
                <p>В мире, одержимом накопительством и страхом нехватки, заявление «я ни в чем не буду нуждаться» звучит как упование на Христа как на абсолютное сокровище. Если наш Пастырь — Сам Спаситель мира, то Его забота о нас совершенна. Он обеспечивает нас всем необходимым для духовного и земного пути.</p>
                <p>Остановитесь сегодня и вспомните, что вы находитесь под присмотром Того, Кто победил смерть. Доверьте Ему свои завтрашние дни и нужды.</p>
                <div class="prayer-box">Иисусе, мой Добрый Пастырь, благодарю Тебя за то, что Ты водишь меня по путям праведности. Утоли жажду моего сердца Твоим присутствием и научи меня покоиться на Твоих зеленых пажитях. Аминь.</div>
            `
        },
        {
            ref: "Иеремия 29:11",
            verse: "Ибо только Я знаю намерения, какие имею о вас, говорит Господь, намерения во благо, а не на зло, чтобы дать вам будущность и надежду.",
            content: `
                <p>Когда мы сталкиваемся с болью и разрушением планов, нам кажется, что надежда потеряна. Но Евангелие учит нас смотреть не на временные руины, а на Христа — автора и совершителя нашей веры. Все Божьи обетования о нас утверждены и запечатлены в Его крови.</p>
                <p>Христос прошел через крестные муки, чтобы у нас была вечная будущность и надежда, которую не может отнять ни один земной кризис. Наш искупленный статус во Христе гарантирует, что даже через скорби Бог ведет нас к славному преображению.</p>
                <p>Доверьте Христу созидание вашего завтра. Он превращает пепел наших неудач в красоту Своего замысла.</p>
                <div class="prayer-box">Господи Иисусе, Ты — моя будущность и моя надежда. Когда вокруг меня колеблется земля, я утверждаюсь на Твоих обетованиях, купленных Твоей жертвой на кресте. Веди меня Своим путем. Аминь.</div>
            `
        },
        {
            ref: "От Матфея 11:28",
            verse: "Придите ко Мне, все труждающиеся и обремененные, и Я успокою вас.",
            content: `
                <p>Иисус обращается к каждому из нас, изнуренному попытками заслужить праведность своими силами или задохнувшемуся в суете этого века. Христос не требует от нас идеальности; Он призывает прийти к Нему с нашими грехами, усталостью и разбитым сердцем, чтобы даровать Свой благодатный покой.</p>
                <p>В Нем мы находим искупление от вины и освобождение от бремени религиозного перфекционизма. Общение со Христом обновляет израненную душу и наполняет силой любить.</p>
                <p>Принесите ко кресту Иисуса весь свой дневной груз. Оставьте его там и примите Его легкое иго благодати.</p>
                <div class="prayer-box">Сладкий Спаситель Иисусе, я откликаюсь на Твой призыв. Я прихожу к Тебе со своей усталостью и грехами. Омой меня Своей кровью и даруй моей душе Твой неизменный покой. Аминь.</div>
            `
        },
        {
            ref: "Исаия 40:31",
            verse: "А надеющиеся на Господа обновят силы: поднимут крылья, как орлы, потекут — и не устанут, пойдут — и не утомятся.",
            content: `
                <p>Ожидание Господа в христианском контексте — это упование на свершенный подвиг Христа. Когда наши духовные и физические силы исчерпаны, Дух Святой, посланный воскресшим Спасителем, поднимает нас на крыльях Своей благодати.</p>
                <p>Христос победил грех и истощение, чтобы мы могли жить из источника Его неисчерпаемой жизни. Надеяться на Него — значит расправлять крылья молитвы и доверять Его поддерживающей силе в любом марафоне.</p>
                <p>Откажитесь от упования на собственную плоть и позвольте Христу стать вашей неутомимой энергией.</p>
                <div class="prayer-box">Господи Иисусе, научи меня ожидать Тебя в тишине. Обнови мои силы через Твое присутствие, чтобы я мог парить над житейскими бурями в силе Твоего Духа. Аминь.</div>
            `
        },
        {
            ref: "К Римлянам 8:28",
            verse: "Притом знаем, что любящим Бога, призванным по Его изволению, все содействует ко благу.",
            content: `
                <p>Крест Христов — это величайшее доказательство того, что Бог способен обратить самое страшное зло (казнь Спасителя) в величайшее благо для всего человечества (спасение). Эта истина распространяется на каждую деталь жизни тех, кто принадлежит Христу.</p>
                <p>Всё, что попущено в нашей жизни — боль, утраты, искушения, — Спаситель использует как инструмент для того, чтобы сообразовать нас с образом Своего Сына. Во Христе мы больше чем победители.</p>
                <p>Посмотрите на свои скорби через призму Голгофы: Иисус уже победил этот мир, и Он проводит вас сквозь огонь к Своей славе.</p>
                <div class="prayer-box">Иисусе, благодарю Тебя за то, что Твоя любовь превращает разбитые осколки моей жизни в сокровища благодати. Помоги мне любить Тебя и доверять Твоему водительству во всех обстоятельствах. Аминь.</div>
            `
        },
        {
            ref: "Псалом 45:11",
            verse: "Остановитесь и познайте, что Я — Бог.",
            content: `
                <p>В мире постоянного шума и погони за успехом Христос призывает нас уединиться, чтобы перевести взгляд с суеты на Его пречистый лик. Познать Бога — значит созерцать Его любовь, явленную нам в Иисусе Христе.</p>
                <p>Остановка перед лицом Спасителя смиряет наше эго и возвращает способность слышать Его тихий голос. В тишине Голгофской крестной жертвы мы находим мир, превосходящий всякое разумение.</p>
                <p>Укротите сегодня внутренний хаос и проведите время у ног Христа, поклоняясь Ему.</p>
                <div class="prayer-box">Господи Иисусе, помоги мне оставить суету мира сего. Я останавливаюсь перед Твоим величием, чтобы познать глубину Твоей любви ко мне. Аминь.</div>
            `
        },
        {
            ref: "К Ефесянам 4:26",
            verse: "Солнце да не зайдет во гневе вашем.",
            content: `
                <p>Христианская жизнь призывает нас к прощению, потому что Сам Христос простил нас даром и неизмеримо больше. Носить в сердце непрощение — значит противоречить духу Голгофы, где Спаситель молился за Своих распинателей.</p>
                <p>Оставляя обиды до заката солнца, мы подражаем милосердию Христа. Его благодать способна исцелить любые трещины в наших взаимоотношениях.</p>
                <p>Примиритесь с ближними во имя Христа, очистив свое сердце Его любовью.</p>
                <div class="prayer-box">Иисусе, научи меня прощать так, как Ты простил меня. Очисти мое сердце от горечи и даруй благодать примирения с теми, кого я обидел или кто обидел меня. Аминь.</div>
            `
        },
        {
            ref: "К Колоссянам 3:15",
            verse: "И да владычествует в сердцах ваших мир Божий...",
            content: `
                <p>Мир, о котором говорит апостол, — это личное завещание Иисуса Христа: «Мир оставляю вам, мир Мой даю вам». Этот мир родился из примирения нас с Богом через кровь Христа на кресте.</p>
                <p>Пусть этот пасхальный мир Христа решает все ваши внутренние споры и сомнения. Если решение лишает вас мира во Христе, остановитесь.</p>
                <p>Позвольте Спасителю царствовать в ваших эмоциях и мыслях.</p>
                <div class="prayer-box">Господи Иисусе, пусть Твой крестный мир владычествует в моем сердце. Утоли все мои страхи и направляй меня Своим тихим водительством. Аминь.</div>
            `
        },
        {
            ref: "Псалом 117:24",
            verse: "Сей день сотворил Господь: возрадуемся и возвеселимся в оном!",
            content: `
                <p>Каждый новый день дарован нам благодаря ходатайству и милости воскресшего Христа. Радоваться в Нем — это духовная привилегия искупленных детей Божиих.</p>
                <p>Иисус победил могилу, сделав каждый рассвет свидетельством Его победы над тьмой. Встречайте этот день с хвалой Спасителю на устах.</p>
                <p>Пусть ваша радость о Христе станет светом для окружающих людей.</p>
                <div class="prayer-box">Славлю Тебя, Иисусе, за этот день жизни! Наполни мое сердце пасхальной радостью и помоги прожить это время в прославлении Твоего святого имени. Аминь.</div>
            `
        },
        {
            ref: "К Галатам 6:9",
            verse: "Делая добро, да не унываем, ибо в свое время пожнем, если не ослабеем.",
            content: `
                <p>Служение людям часто сопряжено с усталостью и неблагодарностью. Но наш главный пример — Иисус Христос, Который обошел всю землю, творя исцеление и добро, несмотря на отвержение.</p>
                <p>Взирая на Голгофу, мы черпаем силы продолжать любить и служить, помня, что всякое дело во имя Христа приносит вечный плод.</p>
                <p>Не сдавайтесь в добре, ведь Сам Христос идет рядом с вами.</p>
                <div class="prayer-box">Господи Иисусе, когда я устаю творить добро, напомни мне о Твоем крестном пути. Поддержи меня Своей благодатью и дай верность до конца. Аминь.</div>
            `
        },
        {
            ref: "К Филиппийцам 4:6",
            verse: "Не заботьтесь ни о чем, но всегда в молитве и прошении с благодарением открывайте свои желания пред Богом.",
            content: `
                <p>Христос призывает нас возложить все наши тревоги на Его сильные руки, потому что Он печется о нас. Молитва с благодарением — это выражение нашей веры в то, что Спаситель контролирует каждую деталь нашей жизни.</p>
                <p>Благодарность за крестную жертву и прошлые благодеяния Христа изгоняет всякий страх перед будущим.</p>
                <p>Передайте Иисусу свои нужды и примите Его глубокий покой.</p>
                <div class="prayer-box">Иисусе, я приношу к Твоему престолу благодати все свои заботы. Благодарю Тебя за Твою верность и за то, что Ты слышишь каждую мою молитву. Аминь.</div>
            `
        },
        {
            ref: "Псалом 36:4",
            verse: "Утешайся Господом, и Он исполнит желания сердца твоего.",
            content: `
                <p>Высшее наслаждение для верующего человека — это созерцание славы и любви Иисуса Христа. Когда Христос становится на первом месте, наши желания очищаются и преображаются Духом Святым.</p>
                <p>Спаситель наполняет нашу душу так, что земные иллюзии теряют свою власть над нами, а сокровенные молитвы обретают чистоту.</p>
                <p>Находите свое блаженство в личном союзе со Спасителем.</p>
                <div class="prayer-box">Господи Иисусе, Ты — единственное истинное сокровище моего сердца. Научи меня находить полноту радости в Тебе и предай мои желания в послушание Твоей воле. Аминь.</div>
            `
        },
        {
            ref: "Притчи Соломона 17:22",
            verse: "Веселое сердце благотворно, как врачевство, а унылый дух сушит кости.",
            content: `
                <p>Иисус Христос принес нам искупление, разрушив узы греха и смерти. В Его присутствии уныние теряет свою силу. Радость спасения, дарованная Христом, — это целебный бальзам для человеческого духа и тела.</p>
                <p>Откажитесь питать мрачные мысли; наполняйте свой разум побеждающей истиной Евангелия.</p>
                <p>Пусть улыбка Христа отражается в вашем сердце каждый день.</p>
                <div class="prayer-box">Иисусе, исцели мой дух от уныния Своей животворящей радостью. Благодарю Тебя за искупление и за жизнь с избытком, которую Ты даруешь мне. Аминь.</div>
            `
        },
        {
            ref: "К Ефесянам 5:16",
            verse: "Дорожа временем, потому что дни лукавы.",
            content: `
                <p>Каждый день — это дар от Христа, возможность прожить его во славу Спасителя. Время уходит безвозвратно, и христиане призваны инвестировать его в вечность через любовь, прощение и проповедь Евангелия.</p>
                <p>Пусть Христос будет центром вашего распорядка дня, направляя каждый ваш шаг.</p>
                <div class="prayer-box">Господи Иисусе, помоги мне дорожить временем и расставлять приоритеты по Твоему сердцу. Пусть каждый мой день прославляет Твое имя. Аминь.</div>
            `
        },
        {
            ref: "Псалом 138:23-24",
            verse: "Испытай меня, Боже, и узнай сердце мое; испытай меня и узнай помышления мои; и зри, не на опасном ли я пути, и направь меня на путь вечный.",
            content: `
                <p>Крест Христов призывает нас к честности перед Богом. Мы отдаем свое сердце во владение Христу, чтобы Он исцелил наши внутренмние раны и очистил помышления Своей благодатью.</p>
                <p>Сам Спаситель ведет нас по пути вечной жизни, очищая от всякого лукавства и направляя к Небесному Отцу.</p>
                <div class="prayer-box">Иисусе, Пастырь моей души, испытай мое сердце и очисти меня Своей святой кровью. Веди меня неизменно по Твоему вечному пути. Аминь.</div>
            `
        }
    ];

    // УПРАВЛЕНИЕ ЗАСТАВКОЙ И ТЕМОЙ
    let currentTheme = 'light';
    let memoryNotes = [];

    function safeGetItem(key, defaultVal) {
        try { return localStorage.getItem(key) || defaultVal; } 
        catch (e) { return defaultVal; }
    }

    function safeSetItem(key, val) {
        try { localStorage.setItem(key, val); } 
        catch (e) {}
    }

    window.addEventListener('load', () => {
        setTimeout(() => {
            const splash = document.getElementById('splash-screen');
            if(splash) {
                splash.style.opacity = '0';
                setTimeout(() => {
                    splash.style.display = 'none';
                    document.body.style.overflowY = 'auto';
                }, 1500);
            }
        }, 4000); 
    });

    window.addEventListener('scroll', () => {
        const y = window.scrollY;
        const topCyl = document.getElementById('cylinder-top');
        const botCyl = document.getElementById('cylinder-bottom');
        if(topCyl) topCyl.style.backgroundPosition = `0 0, 0 ${y * 0.4}px`;
        if(botCyl) botCyl.style.backgroundPosition = `0 0, 0 ${-y * 0.4}px`;
    });

    function applyTheme(theme) {
        document.body.setAttribute('data-theme', theme);
        const btn = document.getElementById('theme-toggle-btn');
        if (btn) btn.textContent = theme === 'dark' ? '☀️' : '🌙';
    }

    function toggleTheme() {
        currentTheme = currentTheme === 'light' ? 'dark' : 'light';
        applyTheme(currentTheme);
        safeSetItem('app_theme', currentTheme);
    }

    window.addEventListener('DOMContentLoaded', () => {
        currentTheme = safeGetItem('app_theme', 'light');
        applyTheme(currentTheme);

        const themeBtn = document.getElementById('theme-toggle-btn');
        if(themeBtn) {
            themeBtn.addEventListener('click', toggleTheme);
            themeBtn.removeAttribute('onclick');
        }

        try {
            const savedNotes = localStorage.getItem('spiritual_notes');
            if(savedNotes) memoryNotes = JSON.parse(savedNotes);
        } catch(e) {}

        setDateBadge();
        loadDailyContent();
        loadNotes();
    });

    function switchTab(tabId) {
        document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
        document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
        document.getElementById(tabId).classList.add('active');
        event.currentTarget.classList.add('active');
    }

    function setDateBadge() {
        const now = new Date();
        const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
        document.getElementById('current-date').textContent = now.toLocaleDateString('ru-RU', options);
    }

    function loadDailyContent(customIndex = null) {
        const now = new Date();
        const dayOfYear = Math.floor((now - new Date(now.getFullYear(), 0, 0)) / 1000 / 60 / 60 / 24);
        const index = customIndex !== null ? customIndex : (dayOfYear % DAILY_DATABASE.length);
        const data = DAILY_DATABASE[index];
        
        document.getElementById('daily-verse-ref').textContent = data.ref;
        document.getElementById('daily-verse-text').textContent = `«${data.verse}»`;
        document.getElementById('sermon-body').innerHTML = data.content;
    }

    function generateNewDaily() {
        loadDailyContent(Math.floor(Math.random() * DAILY_DATABASE.length));
    }

    function toggleNoteEditor() {
        const editor = document.getElementById('note-editor');
        editor.classList.toggle('active');
        if (editor.classList.contains('active')) document.getElementById('note-title').focus();
    }

    function saveNote() {
        const title = document.getElementById('note-title').value.trim();
        const text = document.getElementById('note-text').value.trim();
        if (!title || !text) { alert('Летопись не терпит пустоты. Укажите заголовок и мысль.'); return; }

        const newNote = { 
            id: Date.now(), 
            title, 
            text, 
            date: new Date().toLocaleDateString('ru-RU', { year: 'numeric', month: 'long', day: 'numeric', hour: '2-digit', minute: '2-digit' }) 
        };
        
        memoryNotes.unshift(newNote);
        safeSetItem('spiritual_notes', JSON.stringify(memoryNotes));

        document.getElementById('note-title').value = '';
        document.getElementById('note-text').value = '';
        document.getElementById('note-editor').classList.remove('active');
        loadNotes();
    }

    function loadNotes() {
        if (memoryNotes.length === 0) {
            document.getElementById('notes-list').innerHTML = `<p style="color: var(--ink-light); font-style: italic; text-align: center; padding: 2rem; font-size: 1.2rem;">Страницы вашей летописи пока пусты.</p>`;
            return;
        }
        renderNotes(memoryNotes);
    }

    function filterNotes() {
        const query = document.getElementById('search-input').value.toLowerCase();
        const filtered = memoryNotes.filter(n => n.title.toLowerCase().includes(query) || n.text.toLowerCase().includes(query));
        renderNotes(filtered);
    }

    function deleteNote(id) {
        memoryNotes = memoryNotes.filter(n => n.id !== id);
        safeSetItem('spiritual_notes', JSON.stringify(memoryNotes));
        loadNotes();
    }

    function renderNotes(notesArray) {
        document.getElementById('notes-list').innerHTML = notesArray.map(n => `
            <div class="note-item">
                <button class="delete-note" onclick="deleteNote(${n.id})">Стереть</button>
                <h4>${n.title.replace(/[&<>"']/g, m => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#039;' })[m])}</h4>
                <div class="note-date">${n.date}</div>
                <p style="white-space: pre-line; font-size: 1.2rem;">${n.text.replace(/[&<>"']/g, m => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#039;' })[m])}</p>
            </div>
        `).join('');
    }
</script>
</body>
</html>
