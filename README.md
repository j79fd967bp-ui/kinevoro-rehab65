
<!doctype html>
<html lang="ru">
 
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#101211">
  <meta name="description"
    content="KINEVORO Rehab — индивидуальные занятия ЛФК и физическая реабилитация в Южно-Сахалинске, Долинске и Аниве.">
  <title>KINEVORO Rehab — движение к самостоятельности</title>
  <style>
    :root {
      --bg: #0c0f0e;
      --panel: #141917;
      --panel2: #1b211e;
      --text: #f3f5f2;
      --muted: #aab4ad;
      --accent: #59ff4a;
      --line: #3013b14d;
      --radius: 22px
    }
 
    * {
      box-sizing: border-box
    }
 
    html {
      scroll-behavior: smooth
    }
 
    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6
    }
 
    a {
      color: inherit;
      text-decoration: none
    }
 
    .wrap {
      width: min(1120px, calc(100% - 40px));
      margin: auto
    }
 
    header {
      position: sticky;
      top: 0;
      z-index: 5;
      background: rgba(12, 15, 14, .9);
      backdrop-filter: blur(14px);
      border-bottom: 1px solid rgba(255, 255, 255, .07)
    }
 
    .nav {
      min-height: 76px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px
    }
 
    .brand {
      font-size: 1.2rem;
      font-weight: 900;
      letter-spacing: .13em
    }
 
    .brand span {
      color: var(--accent)
    }
 
    .navlinks {
      display: flex;
      gap: 24px;
      color: var(--muted);
      font-size: .92rem
    }
 
    .navlinks a:hover {
      color: var(--accent)
    }
 
    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 13px 19px;
      border-radius: 999px;
      background: var(--accent);
      color: #11170b;
      font-weight: 800;
      border: 1px solid var(--accent);
      transition: transform .2s, filter .2s
    }
 
    .button:hover {
      transform: translateY(-2px);
      filter: brightness(1.05)
    }
 
    .button.secondary {
      background: transparent;
      color: var(--text);
      border-color: #566159
    }
 
    .hero {
      padding: 78px 0 58px;
      overflow: hidden
    }
 
    .hero-grid {
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 42px;
      align-items: center
    }
 
    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 9px;
      color: var(--accent);
      text-transform: uppercase;
      letter-spacing: .13em;
      font-size: .76rem;
      font-weight: 800
    }
 
    .dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: var(--accent);
      box-shadow: 0 0 18px #c7ff4a88
    }
 
    h1 {
      font-size: clamp(2.7rem, 6vw, 5.4rem);
      line-height: .99;
      letter-spacing: -.055em;
      margin: 20px 0
    }
 
    h1 em {
      font-style: normal;
      color: var(--accent)
    }
 
    .lead {
      font-size: 1.12rem;
      color: #c2cbc4;
      max-width: 620px
    }
 
    .actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 28px
    }
 
    .small-note {
      font-size: .83rem;
      color: var(--muted);
      margin-top: 18px
    }
 
    .hero-card {
      min-height: 430px;
      position: relative;
      overflow: hidden;
      border-radius: 30px;
      background: radial-gradient(circle at 80% 15%, #c7ff4a2b, transparent 36%), linear-gradient(145deg, #222a25, #111512 65%);
      border: 1px solid #303a33;
      padding: 30px;
      display: flex;
      flex-direction: column;
      justify-content: space-between
    }
 
    .hero-card:after {
      content: "K";
      position: absolute;
      font-size: 25rem;
      line-height: 1;
      font-weight: 950;
      letter-spacing: -.12em;
      color: #c7ff4a0c;
      right: -18px;
      bottom: -100px;
      pointer-events: none
    }
 
    .card-tag {
      position: relative;
      z-index: 1;
      display: inline-block;
      width: max-content;
      padding: 8px 12px;
      border: 1px solid #566159;
      border-radius: 999px;
      color: #e3e9e4;
      font-size: .78rem
    }
 
    .card-bottom {
      position: relative;
      z-index: 1
    }
 
    .card-bottom strong {
      font-size: 1.7rem;
      display: block;
      max-width: 340px;
      line-height: 1.15
    }
 
    .card-bottom p {
      color: var(--muted);
      margin-bottom: 0
    }
 
    section {
      padding: 66px 0
    }
 
    .section-head {
      max-width: 700px;
      margin-bottom: 30px
    }
 
    .kicker {
      color: var(--accent);
      font-size: .78rem;
      font-weight: 850;
      text-transform: uppercase;
      letter-spacing: .12em
    }
 
    h2 {
      font-size: clamp(2rem, 4vw, 3.2rem);
      line-height: 1.08;
      letter-spacing: -.04em;
      margin: 10px 0 14px
    }
 
    .section-head p {
      color: var(--muted);
      margin: 0
    }
 
    .grid3 {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 16px
    }
 
    .tile {
      background: var(--panel);
      border: 1px solid var(--line);
      border-radius: var(--radius);
      padding: 24px
    }
 
    .tile .num {
      color: var(--accent);
      font-weight: 900;
      letter-spacing: .08em;
      font-size: .8rem
    }
 
    .tile h3 {
      font-size: 1.2rem;
      margin: 13px 0 8px
    }
 
    .tile p {
      color: var(--muted);
      margin: 0;
      font-size: .96rem
    }
 
    .services {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 14px
    }
 
    .service {
      display: flex;
      gap: 16px;
      background: var(--panel);
      border: 1px solid var(--line);
      border-radius: 18px;
      padding: 21px
    }
 
    .icon {
      flex: 0 0 44px;
      width: 44px;
      height: 44px;
      border-radius: 14px;
      background: #c7ff4a18;
      color: var(--accent);
      display: grid;
      place-items: center;
      font-size: 1.25rem;
      font-weight: 900
    }
 
    .service h3 {
      margin: 0 0 5px;
      font-size: 1.05rem
    }
 
    .service p {
      margin: 0;
      color: var(--muted);
      font-size: .92rem
    }
 
    .price-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 16px
    }
 
    .price {
      background: var(--panel);
      border: 1px solid var(--line);
      border-radius: var(--radius);
      padding: 25px
    }
 
    .price.featured {
      border-color: var(--accent);
      box-shadow: 0 0 0 1px #c7ff4a25 inset
    }
 
    .price .place {
      font-weight: 800;
      color: var(--accent);
      font-size: .85rem;
      text-transform: uppercase;
      letter-spacing: .08em
    }
 
    .price h3 {
      font-size: 1.12rem;
      margin: 12px 0 4px
    }
 
    .price .amount {
      font-size: 2rem;
      font-weight: 900;
      letter-spacing: -.04em
    }
 
    .price p {
      color: var(--muted);
      font-size: .9rem
    }
 
    .price small {
      color: var(--muted)
    }
 
    .steps {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 12px;
      counter-reset: step
    }
 
    .step {
      border-top: 1px solid #4b574e;
      padding: 18px 10px 0 0
    }
 
    .step:before {
      counter-increment: step;
      content: "0" counter(step);
      color: var(--accent);
      font-weight: 900;
      letter-spacing: .1em
    }
 
    .step h3 {
      margin: 10px 0 5px;
      font-size: 1.05rem
    }
 
    .step p {
      margin: 0;
      color: var(--muted);
      font-size: .9rem
    }
 
    .cta {
      background: linear-gradient(120deg, #1d261f, #111512);
      border: 1px solid #344037;
      border-radius: 28px;
      padding: clamp(24px, 5vw, 48px);
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 24px;
      align-items: center
    }
 
    .cta p {
      color: var(--muted);
      max-width: 640px;
      margin-bottom: 0
    }
 
    .contact-list {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-top: 22px
    }
 
    footer {
      padding: 28px 0 40px;
      color: var(--muted);
      font-size: .85rem
    }
 
    .foot {
      border-top: 1px solid var(--line);
      padding-top: 22px;
      display: flex;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap
    }
 
    .disclaimer {
      font-size: .78rem;
      color: #89958c;
      max-width: 900px;
      margin-top: 16px
    }
 
    .mobile-menu {
      display: none
    }
 
    @media(max-width:800px) {
      .navlinks {
        display: none
      }
 
      .hero {
        padding-top: 50px
      }
 
      .hero-grid {
        grid-template-columns: 1fr
      }
 
      .hero-card {
        min-height: 300px
      }
 
      .grid3,
      .price-grid {
        grid-template-columns: 1fr
      }
 
      .services {
        grid-template-columns: 1fr
      }
 
      .steps {
        grid-template-columns: repeat(2, 1fr)
      }
 
      .cta {
        grid-template-columns: 1fr
      }
 
      .nav {
        min-height: 66px
      }
    }
 
    @media(max-width:480px) {
      .wrap {
        width: min(100% - 28px, 1120px)
      }
 
      .hero-card {
        padding: 22px
      }
 
      .actions .button {
        width: 100%
      }
 
      .steps {
        grid-template-columns: 1fr
      }
 
      .service {
        padding: 17px
      }
 
      section {
        padding: 48px 0
      }
    }
  </style>
</head>
 
<body>
  <header>
    <div class="wrap nav">
      <a class="brand" href="#top" aria-label="KINEVORO Rehab — главная">KINEVORO<span>.</span></a>
      <nav class="navlinks" aria-label="Основная навигация">
        <a href="#services">Услуги</a><a href="#prices">Цены</a><a href="#process">Как проходит</a><a
          href="#contacts">Контакты</a>
      </nav>
      <a class="button" href="#contacts">Записаться <span aria-hidden="true">↗</span></a>
    </div>
  </header>
  <main id="top">
    <section class="hero">
      <div class="wrap hero-grid">
        <div>
          <div class="eyebrow"><span class="dot"></span> Физическая реабилитация · Сахалин</div>
          <h1>Возвращаю<br>уверенность<br><em>в движении.</em></h1>
          <p class="lead">Индивидуальные занятия ЛФК и работа над двигательными навыками после инсульта и других
            неврологических заболеваний — с учётом возможностей и целей человека.</p>
          <div class="actions">
            <a class="button" href="#contacts">Обсудить занятие <span aria-hidden="true">→</span></a>
            <a class="button secondary" href="#services">Посмотреть услуги</a>
          </div>
          <p class="small-note">Южно-Сахалинск · Долинск · Анива<br>Приём в кабинете и выезд на дом по предварительной
            договорённости.</p>
        </div>
        <div class="hero-card">
          <span class="card-tag">KINEVORO REHAB<br>Толстов Александр Алексеевич</span>
          <div class="card-bottom">
            <strong><em>План.<em> Движение. </em> <em>Повторная оценка</em>.</strong>
            <p>Работаю над функциональными задачами шаг за шагом.</p>
          </div>
        </div>
      </div>
    </section>
 
    <section id="services">
      <div class="wrap">
        <div class="section-head">
          <div class="kicker">Направления</div>
          <h2>Работа над тем,<br>что важно в жизни.</h2>
          <p>Содержание занятия определяется после оценки состояния, целей пациента и доступных медицинских
            рекомендаций.</p>
        </div>
        <div class="services">
          <article class="service">
            <div class="icon">↗</div>
            <div>
              <h3>После инсульта,травм и операций</h3>
              <p>Тренировка контроля туловища, равновесия, перемещений и ходьбы — если это безопасно и соответствует
                состоянию пациента.</p>
            </div>
          </article>
          <article class="service">
            <div class="icon">◎</div>
            <div>
              <h3>Неврологические заболевания</h3>
              <p>Индивидуальная двигательная практика с учётом утомляемости, ограничений и функциональных целей.</p>
            </div>
          </article>
          <article class="service">
            <div class="icon">↔</div>
            <div>
              <h3>Функциональные навыки</h3>
              <p>Практика вставания, пересаживания, переноса веса и других повседневных движений.</p>
            </div>
          </article>
          <article class="service">
            <div class="icon">⌂</div>
            <div>
              <h3>Занятия на дому</h3>
              <p>Работа в привычной среде и рекомендации по организации безопасного пространства для движения.</p>
            </div>
          </article>
        </div>
      </div>
    </section>
 
    <section id="prices">
      <div class="wrap">
        <div class="section-head">
          <div class="kicker">Стоимость</div>
          <h2>Понятные условия<br>до начала занятий.</h2>
          <p>Предварительные цены. Итоговая стоимость домашнего визита подтверждается при согласовании адреса и времени.
          </p>
        </div>
        <div class="price-grid">
          <article class="price">
            <div class="place">В кабинете</div>
            <h3>Индивидуальное занятие</h3>
            <div class="amount">2 500 ₽</div>
            <p>60 минут</p><small>Первичная оценка — 2 500 ₽</small>
          </article>
          <article class="price featured">
            <div class="place">Южно-Сахалинск</div>
            <h3>Выезд на дом</h3>
            <div class="amount">3 500 ₽</div>
            <p>До 60 минут занятия</p><small>Адрес и возможность визита согласуются заранее</small>
          </article>
          <article class="price">
            <div class="place">Долинск · Анива</div>
            <h3>Выезд на дом</h3>
            <div class="amount">от 5 000 ₽</div>
            <p>До 60 минут занятия</p><small>Стоимость зависит от адреса и организации выезда</small>
          </article>
        </div>
      </div>
    </section>
 
    <section id="process">
      <div class="wrap">
        <div class="section-head">
          <div class="kicker">Как я выполняю свою работу.</div>
          <h2>Последовательно,<br>с учётом состояния.</h2>
        </div>
        <div class="steps">
          <article class="step">
            <h3>Первичное знакомство</h3>
            <p>Обсудим историю состояния, цели и доступные рекомендации.</p>
          </article>
          <article class="step">
            <h3>Оценка функций</h3>
            <p>Определяем исходные возможности и ограничения в рамках профессиональной компетенции.</p>
          </article>
          <article class="step">
            <h3>Индивидуальный план</h3>
            <p>Подбираем подходящие двигательные задачи и дозировку нагрузки.</p>
          </article>
          <article class="step">
            <h3>Отслеживание динамики</h3>
            <p>Сравниваю результаты повторной оценки и при необходимости меняю план.</p>
          </article>
        </div>
      </div>
    </section>
 
    <section id="contacts">
      <div class="wrap">
        <div class="cta">
          <div>
            <div class="kicker">Запись на занятие</div>
            <h2>Обсудим Вашу задачу?</h2>
            <p>Напишите или позвоните, чтобы уточнить формат занятий, доступность выезда и стоимость по Вашему адресу.
            </p>
          </div>
          <div class="contact-list">
            <!-- Перед публикацией замените номер в двух ссылках ниже на свой номер в международном формате. -->
            <a class="button" href="tel:+79147473335">Позвонить</a>
            <a class="button secondary"
              href="https://max.ru/u/f9LHodD0cOKcsuuchvXoMqATMh6fItBxLEZUUDxUhzHqiBYsjB7jGjw1N34" target="_blank"
              rel="noopener noreferrer">MAX</a>
          </div>
        </div>
        <p class="disclaimer">Информация на сайте носит ознакомительный характер и не заменяет консультацию врача.
          Услуги, методы и объём занятий определяются с учётом квалификации специалиста, состояния пациента и применимых
          требований. При внезапном появлении слабости, асимметрии лица, нарушения речи или других острых симптомов
          необходимо немедленно вызвать экстренную помощь.</p>
      </div>
    </section>
  </main>
  <footer>
    <div class="wrap foot">
      <div><strong>KINEVORO<span style="color:var(--accent)">.</span></strong><br>Физическая реабилитация и ЛФК</div>
      <div>Южно-Сахалинск · Долинск · Анива</div>
      <div>© <span id="year"></span> KINEVORO Rehab</div>
    </div>
  </footer>
  <script>document.getElementById("year").textContent = new Date().getFullYear();</script>
</body>
 
</html>
 
 