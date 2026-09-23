<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Carnet de vocabulaire</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --paper: #F1EFE4;
    --paper-raised: #FBFAF4;
    --ink: #21261F;
    --ink-soft: #565A4E;
    --rule: #CFC9B4;
    --accent: #35564A;
    --accent-soft: #E4E9E0;
    --warm: #B9792A;
    --warm-soft: #F3E4CC;
    --correct: #35564A;
    --correct-soft: #DCE7DF;
    --wrong: #A13D2D;
    --wrong-soft: #F3DCD4;
    --shadow: rgba(33, 38, 29, 0.12);
    color-scheme: light;
  }
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) {
      --paper: #1B1E18;
      --paper-raised: #24281F;
      --ink: #EDEAE0;
      --ink-soft: #A9AC9D;
      --rule: #3C4136;
      --accent: #7FA893;
      --accent-soft: #2B362E;
      --warm: #E0A75B;
      --warm-soft: #3A2E1B;
      --correct: #7FA893;
      --correct-soft: #263229;
      --wrong: #E08E7C;
      --wrong-soft: #3A2521;
      --shadow: rgba(0, 0, 0, 0.4);
    }
  }
  :root[data-theme="dark"] {
    --paper: #1B1E18;
    --paper-raised: #24281F;
    --ink: #EDEAE0;
    --ink-soft: #A9AC9D;
    --rule: #3C4136;
    --accent: #7FA893;
    --accent-soft: #2B362E;
    --warm: #E0A75B;
    --warm-soft: #3A2E1B;
    --correct: #7FA893;
    --correct-soft: #263229;
    --wrong: #E08E7C;
    --wrong-soft: #3A2521;
    --shadow: rgba(0, 0, 0, 0.4);
  }

  * { box-sizing: border-box; }
  html, body { margin: 0; padding: 0; }
  body {
    background: var(--paper);
    color: var(--ink);
    font-family: 'IBM Plex Sans', system-ui, sans-serif;
    min-height: 100vh;
    padding: 32px 16px 64px;
    transition: background 0.2s ease, color 0.2s ease;
  }
  .wrap {
    max-width: 620px;
    margin: 0 auto;
  }
  .serif { font-family: 'Fraunces', Georgia, serif; }

  header.top {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    border-bottom: 1px solid var(--rule);
    padding-bottom: 14px;
    margin-bottom: 28px;
  }
  header.top .title {
    font-family: 'Fraunces', Georgia, serif;
    font-size: 22px;
    font-weight: 600;
    letter-spacing: 0.01em;
  }
  header.top .sub {
    font-size: 13px;
    color: var(--ink-soft);
  }

  .card {
    background: var(--paper-raised);
    border: 1px solid var(--rule);
    border-radius: 4px;
    padding: 28px 24px;
    box-shadow: 0 2px 10px var(--shadow);
  }

  .intro p {
    color: var(--ink-soft);
    line-height: 1.6;
    font-size: 15.5px;
    margin: 0 0 22px;
  }

  fieldset {
    border: none;
    padding: 0;
    margin: 0 0 24px;
  }
  legend {
    font-size: 12.5px;
    color: var(--ink-soft);
    margin-bottom: 10px;
    padding: 0;
  }
  .pool-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 8px;
  }
  .pool-opt {
    border: 1px solid var(--rule);
    border-radius: 3px;
    padding: 10px 12px;
    font-size: 14px;
    cursor: pointer;
    background: var(--paper);
    color: var(--ink);
    text-align: left;
    transition: border-color 0.15s ease, background 0.15s ease;
  }
  .pool-opt small { display: block; color: var(--ink-soft); font-size: 11.5px; margin-top: 2px; }
  .pool-opt.selected {
    border-color: var(--accent);
    background: var(--accent-soft);
  }
  .pool-opt:focus-visible, .mode-btn:focus-visible, button:focus-visible, .opt:focus-visible {
    outline: 2px solid var(--accent);
    outline-offset: 2px;
  }

  .mode-row {
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  .mode-btn {
    border: 1px solid var(--rule);
    background: var(--paper);
    border-radius: 4px;
    padding: 16px 18px;
    text-align: left;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 12px;
  }
  .mode-btn:hover { border-color: var(--accent); }
  .mode-btn .m-title {
    font-family: 'Fraunces', Georgia, serif;
    font-size: 17px;
    font-weight: 600;
  }
  .mode-btn .m-desc {
    font-size: 13px;
    color: var(--ink-soft);
    margin-top: 3px;
  }
  .mode-btn .arrow { font-size: 18px; color: var(--accent); flex-shrink: 0; }

  .stat-line {
    margin-top: 22px;
    padding-top: 16px;
    border-top: 1px solid var(--rule);
    font-size: 13px;
    color: var(--ink-soft);
    display: flex;
    justify-content: space-between;
  }
  .stat-line b { color: var(--ink); font-weight: 600; }

  /* --- quiz / flashcard screen --- */
  .session-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 18px;
    font-size: 13px;
    color: var(--ink-soft);
  }
  .back-link {
    background: none; border: none; color: var(--ink-soft);
    font-size: 13px; cursor: pointer; padding: 4px 0;
    text-decoration: underline;
    text-underline-offset: 3px;
  }
  .progress-track {
    height: 3px; background: var(--rule); border-radius: 2px; margin-bottom: 24px; overflow: hidden;
  }
  .progress-fill { height: 100%; background: var(--accent); transition: width 0.25s ease; }

  .word-display {
    text-align: center;
    padding: 30px 10px 34px;
  }
  .word-display .en {
    font-family: 'Fraunces', Georgia, serif;
    font-size: clamp(28px, 7vw, 38px);
    font-weight: 600;
  }
  .word-display .tag {
    font-size: 12px;
    color: var(--ink-soft);
    margin-top: 8px;
  }

  .options { display: flex; flex-direction: column; gap: 9px; }
  .opt {
    display: flex; align-items: baseline; gap: 10px;
    border: 1px solid var(--rule);
    background: var(--paper);
    border-radius: 3px;
    padding: 13px 14px;
    font-size: 15px;
    text-align: left;
    cursor: pointer;
    color: var(--ink);
  }
  .opt .letter {
    font-family: 'Fraunces', Georgia, serif;
    color: var(--ink-soft);
    font-size: 13px;
    flex-shrink: 0;
  }
  .opt:hover:not(:disabled) { border-color: var(--accent); }
  .opt:disabled { cursor: default; }
  .opt.correct { background: var(--correct-soft); border-color: var(--correct); }
  .opt.wrong { background: var(--wrong-soft); border-color: var(--wrong); }
  .opt.correct .letter, .opt.wrong .letter { color: inherit; }

  .next-row { margin-top: 20px; display: flex; justify-content: flex-end; }
  .btn {
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 14px;
    font-weight: 500;
    padding: 10px 20px;
    border-radius: 3px;
    border: 1px solid var(--accent);
    background: var(--accent);
    color: var(--paper-raised);
    cursor: pointer;
  }
  .btn.ghost {
    background: transparent;
    color: var(--accent);
  }
  .btn:disabled { opacity: 0.4; cursor: default; }

  /* flashcards */
  .flash-card {
    border: 1px solid var(--rule);
    background: var(--paper);
    border-radius: 4px;
    min-height: 180px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    cursor: pointer;
    padding: 24px;
    user-select: none;
  }
  .flash-card .front { font-family: 'Fraunces', Georgia, serif; font-size: clamp(26px, 7vw, 34px); font-weight: 600; }
  .flash-card .back .fr { font-family: 'Fraunces', Georgia, serif; font-size: 24px; color: var(--accent); font-weight: 600; }
  .flash-card .hint { font-size: 12.5px; color: var(--ink-soft); margin-top: 14px; }

  .flash-actions {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
    margin-top: 18px;
  }
  .flash-actions button {
    padding: 13px;
    border-radius: 3px;
    font-size: 14px;
    font-weight: 500;
    cursor: pointer;
    border: 1px solid var(--rule);
    background: var(--paper);
    color: var(--ink);
  }
  .flash-actions .know { border-color: var(--correct); color: var(--correct); }
  .flash-actions .dontknow { border-color: var(--wrong); color: var(--wrong); }
  .flash-actions button:disabled { opacity: 0.35; }

  /* results */
  .results .score {
    text-align: center;
    padding: 10px 0 24px;
  }
  .results .score .big {
    font-family: 'Fraunces', Georgia, serif;
    font-size: 46px;
    font-weight: 700;
  }
  .results .score .lbl { color: var(--ink-soft); font-size: 13.5px; margin-top: 4px; }
  .miss-list { list-style: none; padding: 0; margin: 0; }
  .miss-list li {
    display: flex; justify-content: space-between; gap: 10px;
    padding: 10px 0;
    border-bottom: 1px solid var(--rule);
    font-size: 14.5px;
  }
  .miss-list li:last-child { border-bottom: none; }
  .miss-list .w { font-weight: 500; }
  .miss-list .t { color: var(--ink-soft); }
  .empty-note { color: var(--ink-soft); font-size: 14px; text-align: center; padding: 10px 0; }

  .result-actions { display: flex; flex-direction: column; gap: 8px; margin-top: 22px; }

  .theme-toggle {
    background: none; border: 1px solid var(--rule); color: var(--ink-soft);
    font-size: 12px; border-radius: 3px; padding: 5px 10px; cursor: pointer;
  }

  .screen { display: none; }
  .screen.active { display: block; }

  /* --- word of the day --- */
  .wotd {
    border: 1px solid var(--rule);
    background: linear-gradient(135deg, var(--accent-soft), var(--paper-raised));
    border-radius: 4px;
    padding: 20px 22px;
    margin-bottom: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 14px;
  }
  .wotd .eyebrow { font-size: 11.5px; letter-spacing: 0.06em; text-transform: uppercase; color: var(--ink-soft); margin-bottom: 4px; }
  .wotd .en { font-family: 'Fraunces', Georgia, serif; font-size: 22px; font-weight: 600; }
  .wotd .fr { font-size: 13.5px; color: var(--ink-soft); margin-top: 3px; }
  .wotd .mark { font-size: 26px; flex-shrink: 0; opacity: 0.8; }

  /* --- stat grid --- */
  .stat-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 8px;
    margin-top: 22px;
    padding-top: 18px;
    border-top: 1px solid var(--rule);
  }
  .stat-box { text-align: center; }
  .stat-box .num { font-family: 'Fraunces', Georgia, serif; font-size: 22px; font-weight: 600; color: var(--ink); }
  .stat-box .lbl { font-size: 10.5px; color: var(--ink-soft); margin-top: 2px; line-height: 1.3; }
  @media (max-width: 420px) {
    .stat-grid { grid-template-columns: repeat(2, 1fr); row-gap: 14px; }
  }

  /* --- mode buttons with icon --- */
  .mode-btn .m-icon {
    width: 38px; height: 38px; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px; flex-shrink: 0;
    background: var(--warm-soft);
  }
  .mode-btn { transition: border-color 0.15s ease, transform 0.1s ease; }
  .mode-btn:active { transform: scale(0.99); }
  .mode-btn .m-left { display: flex; align-items: center; gap: 13px; }

  /* --- explorer / browse --- */
  .browse-search {
    width: 100%;
    padding: 11px 14px;
    border: 1px solid var(--rule);
    border-radius: 3px;
    background: var(--paper);
    color: var(--ink);
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 14.5px;
    margin-bottom: 14px;
  }
  .browse-list { list-style: none; padding: 0; margin: 0; max-height: 60vh; overflow-y: auto; }
  .browse-list li {
    display: flex; justify-content: space-between; align-items: baseline; gap: 12px;
    padding: 11px 2px;
    border-bottom: 1px solid var(--rule);
  }
  .browse-list li:last-child { border-bottom: none; }
  .browse-list .en { font-family: 'Fraunces', Georgia, serif; font-size: 15.5px; font-weight: 600; flex-shrink: 0; }
  .browse-list .fr { font-size: 13.5px; color: var(--ink-soft); text-align: right; }
  .browse-count { font-size: 12.5px; color: var(--ink-soft); margin-bottom: 10px; }

  /* --- flashcard 3D flip --- */
  .flash-flip-outer { perspective: 1200px; }
  .flash-card {
    position: relative;
    transform-style: preserve-3d;
    transition: transform 0.45s cubic-bezier(0.4, 0.2, 0.2, 1);
  }
  .flash-card.flipped { transform: rotateY(180deg); }
  .flash-card .front, .flash-card .back {
    backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
    width: 100%;
  }
  .flash-card .back {
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    display: flex; flex-direction: column; align-items: center; justify-content: center;
    transform: rotateY(180deg);
  }


  @media (max-width: 420px) {
    .pool-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <div>
      <div class="title">Carnet de vocabulaire</div>
      <div class="sub">Anglais &middot; révision espacée</div>
    </div>
    <button class="theme-toggle" id="themeToggle" type="button">Mode sombre</button>
  </header>

  <!-- HOME -->
  <section class="screen active" id="screen-home">
    <div class="wotd" id="wotdCard">
      <div>
        <div class="eyebrow">Mot du jour</div>
        <div class="en" id="wotdEn">word</div>
        <div class="fr" id="wotdFr">mot</div>
      </div>
      <div class="mark">✎</div>
    </div>

    <div class="card intro">
      <p>Choisis un lot de mots et un mode pour te tester. Ta progression reste enregistrée sur cet appareil.</p>

      <fieldset>
        <legend>Lot de mots</legend>
        <div class="pool-grid" id="poolGrid"></div>
      </fieldset>

      <fieldset>
        <legend>Mode</legend>
        <div class="mode-row">
          <button class="mode-btn" id="startQuiz" type="button">
            <div class="m-left">
              <div class="m-icon">✓</div>
              <div>
                <div class="m-title">Questionnaire</div>
                <div class="m-desc">10 mots, 4 choix, un score à la fin</div>
              </div>
            </div>
            <span class="arrow">›</span>
          </button>
          <button class="mode-btn" id="startFlash" type="button">
            <div class="m-left">
              <div class="m-icon">⟳</div>
              <div>
                <div class="m-title">Cartes mémo</div>
                <div class="m-desc">Retourne la carte, juge toi-même</div>
              </div>
            </div>
            <span class="arrow">›</span>
          </button>
          <button class="mode-btn" id="startWrite" type="button">
            <div class="m-left">
              <div class="m-icon">✍</div>
              <div>
                <div class="m-title">Traduction du jour</div>
                <div class="m-desc">Une phrase en français, à toi de la traduire</div>
              </div>
            </div>
            <span class="arrow">›</span>
          </button>
          <button class="mode-btn" id="startBrowse" type="button">
            <div class="m-left">
              <div class="m-icon">🔍</div>
              <div>
                <div class="m-title">Explorer</div>
                <div class="m-desc">Parcourir et rechercher tous les mots</div>
              </div>
            </div>
            <span class="arrow">›</span>
          </button>
        </div>
      </fieldset>

      <div class="stat-grid">
        <div class="stat-box"><div class="num" id="statTotal">0</div><div class="lbl">mots suivis</div></div>
        <div class="stat-box"><div class="num" id="statReview">0</div><div class="lbl">à revoir</div></div>
        <div class="stat-box"><div class="num" id="statMastered">0</div><div class="lbl">maîtrisés</div></div>
        <div class="stat-box"><div class="num" id="statStreak">0</div><div class="lbl">jours d'affilée 🔥</div></div>
      </div>
    </div>
  </section>

  <!-- EXPLORER -->
  <section class="screen" id="screen-browse">
    <div class="session-top">
      <button class="back-link" id="browseBack" type="button">&larr; Retour</button>
      <span>Explorer</span>
    </div>
    <div class="card">
      <input type="text" class="browse-search" id="browseSearch" placeholder="Rechercher un mot, en anglais ou en français...">
      <div class="browse-count" id="browseCount"></div>
      <ul class="browse-list" id="browseList"></ul>
    </div>
  </section>

  <!-- QUIZ -->
  <section class="screen" id="screen-quiz">
    <div class="session-top">
      <button class="back-link" id="quizBack" type="button">&larr; Retour</button>
      <span id="quizCounter">Question 1/10</span>
    </div>
    <div class="progress-track"><div class="progress-fill" id="quizProgress" style="width:0%"></div></div>
    <div class="card">
      <div class="word-display">
        <div class="en" id="quizWord">word</div>
        <div class="tag" id="quizTag">semaine 1</div>
      </div>
      <div class="options" id="quizOptions"></div>
      <div class="next-row">
        <button class="btn" id="quizNext" disabled>Suivant</button>
      </div>
    </div>
  </section>

  <!-- FLASHCARDS -->
  <section class="screen" id="screen-flash">
    <div class="session-top">
      <button class="back-link" id="flashBack" type="button">&larr; Retour</button>
      <span id="flashCounter">Carte 1/10</span>
    </div>
    <div class="progress-track"><div class="progress-fill" id="flashProgress" style="width:0%"></div></div>
    <div class="card">
      <div class="flash-flip-outer">
        <div class="flash-card" id="flashCard">
          <div class="front" id="flashFront">word</div>
          <div class="back">
            <div class="fr" id="flashBackText">mot</div>
            <div class="hint">Anglais &rarr; Français</div>
          </div>
        </div>
      </div>
      <div class="hint" style="text-align:center; margin-top:12px;" id="flashHint">Touche la carte pour révéler la traduction</div>
      <div class="flash-actions">
        <button class="dontknow" id="flashNo" type="button" disabled>À revoir</button>
        <button class="know" id="flashYes" type="button" disabled>Je savais</button>
      </div>
    </div>
  </section>

  <!-- WRITE (traduction du jour) -->
  <section class="screen" id="screen-write">
    <div class="session-top">
      <button class="back-link" id="writeBack" type="button">&larr; Retour</button>
      <span>Traduction du jour</span>
    </div>
    <div class="card">
      <fieldset>
        <legend>Traduis cette phrase en anglais</legend>
        <div id="writeFrSentence" class="serif" style="font-size:19px; line-height:1.5; padding:14px 16px; border:1px solid var(--rule); border-radius:3px; background:var(--warm-soft); margin-bottom:16px;"></div>
      </fieldset>
      <textarea id="writeArea" rows="3" placeholder="Ta traduction en anglais..." style="width:100%; font-family:'IBM Plex Sans', sans-serif; font-size:15px; padding:12px; border:1px solid var(--rule); border-radius:3px; background:var(--paper); color:var(--ink); resize:vertical;"></textarea>

      <div id="writeCorrection" style="display:none; margin-top:16px; padding:14px 16px; border:1px solid var(--correct); border-radius:3px; background:var(--correct-soft);">
        <div style="font-size:12px; color:var(--ink-soft); margin-bottom:4px;">Traduction proposée</div>
        <div id="writeRefText" class="serif" style="font-size:17px;"></div>
      </div>

      <div class="next-row" style="justify-content:space-between;">
        <button class="btn ghost" id="writeShuffle" type="button">Phrase suivante</button>
        <button class="btn" id="writeSave" type="button" disabled>Voir la correction</button>
      </div>

      <div id="writeHistoryWrap" style="margin-top:26px; padding-top:18px; border-top:1px solid var(--rule); display:none;">
        <fieldset>
          <legend>Historique récent</legend>
          <ul class="miss-list" id="writeHistoryList"></ul>
        </fieldset>
      </div>
    </div>
  </section>

  <!-- RESULTS -->
  <section class="screen" id="screen-results">
    <div class="card results">
      <div class="score">
        <div class="big" id="resScore">0/10</div>
        <div class="lbl" id="resLabel">bonnes réponses</div>
      </div>
      <div id="resMissWrap">
        <fieldset>
          <legend>À revoir</legend>
          <ul class="miss-list" id="resMissList"></ul>
        </fieldset>
      </div>
      <div class="result-actions">
        <button class="btn" id="resRetry">Recommencer avec les mêmes mots</button>
        <button class="btn ghost" id="resHome">Retour à l'accueil</button>
      </div>
    </div>
  </section>
</div>

<script>
/* ---------------- DATA ---------------- */
const VOCAB = [
 {en:"to procrastinate", fr:"remettre à plus tard", week:1},
 {en:"blunt", fr:"direct, sans filtre", week:1},
 {en:"to overwhelm", fr:"submerger, accabler", week:1},
 {en:"eventually", fr:"finalement, au bout du compte", week:1},
 {en:"to figure out", fr:"comprendre, trouver la solution", week:1},
 {en:"stubborn", fr:"têtu", week:1},
 {en:"to bring up", fr:"évoquer / élever (un enfant)", week:1},
 {en:"relief", fr:"soulagement", week:1},
 {en:"sensible", fr:"raisonnable, sensé", week:1},
 {en:"to catch up", fr:"rattraper son retard", week:1},
 {en:"worth it", fr:"qui en vaut la peine", week:1},
 {en:"blurry", fr:"flou", week:1},
 {en:"to put off", fr:"reporter, repousser", week:1},
 {en:"awkward", fr:"gênant, maladroit", week:1},
 {en:"to rely on", fr:"compter sur, dépendre de", week:1},
 {en:"straightforward", fr:"simple, direct", week:1},
 {en:"to sneak in/out", fr:"entrer/sortir discrètement", week:1},
 {en:"to point out", fr:"souligner, faire remarquer", week:1},
 {en:"stern", fr:"sévère, strict", week:1},
 {en:"to end up", fr:"finir par", week:1},
 {en:"thorough", fr:"minutieux, approfondi", week:1},
 {en:"overrated", fr:"surestimé, surcoté", week:1},
 {en:"to hold off", fr:"attendre avant de faire qqch", week:1},
 {en:"shallow", fr:"superficiel", week:1},
 {en:"to make up for", fr:"compenser", week:1},
 {en:"reckless", fr:"imprudent, inconscient", week:1},
 {en:"to dwell on", fr:"ressasser, s'attarder sur", week:1},
 {en:"to come up with", fr:"trouver une idée, une solution", week:1},
 {en:"gullible", fr:"crédule, naïf", week:1},
 {en:"to wear off", fr:"s'estomper, se dissiper", week:1},
 {en:"overwhelmed", fr:"submergé", week:1},
 {en:"to nag", fr:"harceler, embêter qqn", week:1},

 {en:"to hold up", fr:"tenir bon / retarder qqn", week:2},
 {en:"spineless", fr:"sans caractère, lâche", week:2},
 {en:"to give in", fr:"céder, capituler", week:2},
 {en:"tedious", fr:"fastidieux, ennuyeux", week:2},
 {en:"to look down on", fr:"mépriser, regarder de haut", week:2},
 {en:"to back down", fr:"reculer, abandonner une position", week:2},
 {en:"petty", fr:"mesquin, insignifiant", week:2},
 {en:"to get over", fr:"surmonter, tourner la page", week:2},
 {en:"far-fetched", fr:"tiré par les cheveux", week:2},
 {en:"to hang out", fr:"traîner, passer du temps avec qqn", week:2},
 {en:"to let down", fr:"décevoir", week:2},
 {en:"fickle", fr:"versatile, inconstant", week:2},
 {en:"to take after", fr:"tenir de qqn, ressembler à", week:2},
 {en:"outspoken", fr:"franc, qui ne mâche pas ses mots", week:2},
 {en:"to drift apart", fr:"s'éloigner (d'une relation)", week:2},
 {en:"to look forward to", fr:"attendre avec impatience", week:2},
 {en:"naive", fr:"naïf", week:2},
 {en:"to make ends meet", fr:"joindre les deux bouts", week:2},
 {en:"blatant", fr:"flagrant, évident", week:2},
 {en:"to take for granted", fr:"considérer comme acquis", week:2},
 {en:"to call off", fr:"annuler", week:2},
 {en:"fluke", fr:"coup de chance, hasard", week:2},
 {en:"to stand out", fr:"se démarquer", week:2},
 {en:"subtle", fr:"subtil", week:2},
 {en:"to talk (someone) into", fr:"convaincre qqn de faire qqch", week:2},
 {en:"to put up with", fr:"supporter, tolérer", week:2},
 {en:"cunning", fr:"rusé, malin", week:2},
 {en:"to slip up", fr:"faire une erreur, gaffer", week:2},
 {en:"on the fence", fr:"indécis, hésitant", week:2},
 {en:"to burn out", fr:"s'épuiser, faire un burn-out", week:2},

 {en:"to negotiate", fr:"négocier", week:3},
 {en:"to delegate", fr:"déléguer", week:3},
 {en:"workload", fr:"charge de travail", week:3},
 {en:"to streamline", fr:"simplifier, optimiser", week:3},
 {en:"milestone", fr:"étape clé", week:3},
 {en:"to prioritize", fr:"prioriser", week:3},
 {en:"turnover", fr:"chiffre d'affaires / rotation du personnel", week:3},
 {en:"to onboard", fr:"intégrer un employé", week:3},
 {en:"stakeholder", fr:"partie prenante", week:3},
 {en:"to leverage", fr:"tirer parti de", week:3},
 {en:"accountability", fr:"responsabilité, obligation de rendre des comptes", week:3},
 {en:"to escalate", fr:"faire remonter un problème", week:3},
 {en:"bottleneck", fr:"goulot d'étranglement", week:3},
 {en:"to outsource", fr:"externaliser", week:3},
 {en:"proactive", fr:"proactif", week:3},
 {en:"versatile", fr:"polyvalent", week:3},
 {en:"overhead", fr:"frais généraux", week:3},
 {en:"feedback", fr:"retour, avis", week:3},
 {en:"to network", fr:"réseauter", week:3},
 {en:"deadline", fr:"échéance", week:3},
 {en:"to follow up", fr:"relancer, faire un suivi", week:3},
 {en:"to brief (someone)", fr:"briefer qqn", week:3},
 {en:"in the pipeline", fr:"en cours, à venir", week:3},

 {en:"resilient", fr:"résilient", week:4},
 {en:"compassionate", fr:"compatissant", week:4},
 {en:"arrogant", fr:"arrogant", week:4},
 {en:"humble", fr:"humble", week:4},
 {en:"easygoing", fr:"facile à vivre", week:4},
 {en:"moody", fr:"lunatique", week:4},
 {en:"assertive", fr:"affirmé, qui s'impose", week:4},
 {en:"insecure", fr:"peu sûr de soi", week:4},
 {en:"thoughtful", fr:"attentionné", week:4},
 {en:"ruthless", fr:"impitoyable", week:4},
 {en:"empathetic", fr:"empathique", week:4},
 {en:"self-conscious", fr:"mal à l'aise avec son image", week:4},
 {en:"considerate", fr:"prévenant", week:4},
 {en:"temperamental", fr:"capricieux, instable", week:4},
 {en:"vindictive", fr:"rancunier", week:4},
 {en:"gracious", fr:"courtois, bienveillant", week:4},
 {en:"condescending", fr:"condescendant", week:4},
 {en:"tactless", fr:"sans tact", week:4},
 {en:"forgiving", fr:"indulgent, clément", week:4},
 {en:"resentful", fr:"plein de rancœur", week:4},
 {en:"to snap at (someone)", fr:"s'énerver contre qqn brusquement", week:4},
 {en:"touchy", fr:"susceptible", week:4},
 {en:"to hold a grudge", fr:"garder rancune", week:4},

 {en:"to hit the nail on the head", fr:"mettre le doigt dessus", week:5},
 {en:"to beat around the bush", fr:"tourner autour du pot", week:5},
 {en:"to bite the bullet", fr:"se résigner, prendre son courage à deux mains", week:5},
 {en:"to cut corners", fr:"bâcler, rogner sur la qualité", week:5},
 {en:"to spill the beans", fr:"vendre la mèche", week:5},
 {en:"to go the extra mile", fr:"se donner à fond", week:5},
 {en:"to be under the weather", fr:"être patraque", week:5},
 {en:"to kill two birds with one stone", fr:"faire d'une pierre deux coups", week:5},
 {en:"once in a blue moon", fr:"très rarement", week:5},
 {en:"to break the ice", fr:"briser la glace", week:5},
 {en:"to see eye to eye", fr:"être sur la même longueur d'onde", week:5},
 {en:"to be on the same page", fr:"être d'accord, sur la même page", week:5},
 {en:"a blessing in disguise", fr:"un mal pour un bien", week:5},
 {en:"to bite off more than you can chew", fr:"avoir les yeux plus gros que le ventre", week:5},
 {en:"out of the blue", fr:"sans prévenir, soudainement", week:5},
 {en:"to cost an arm and a leg", fr:"coûter les yeux de la tête", week:5},
 {en:"to jump on the bandwagon", fr:"suivre la tendance", week:5},
 {en:"to let the cat out of the bag", fr:"vendre la mèche", week:5},
 {en:"to call it a day", fr:"s'arrêter là pour aujourd'hui", week:5},
 {en:"to ring a bell", fr:"rappeler un souvenir", week:5},
 {en:"to get the ball rolling", fr:"lancer les choses", week:5},
 {en:"to read between the lines", fr:"lire entre les lignes", week:5},
 {en:"to have a lot on your plate", fr:"avoir beaucoup de choses à gérer", week:5},

 {en:"actually", fr:"en fait (≠ actuellement)", week:6},
 {en:"to attend", fr:"assister à (≠ attendre)", week:6},
 {en:"to assist", fr:"aider (≠ assister à)", week:6},
 {en:"deception", fr:"tromperie (≠ déception)", week:6},
 {en:"library", fr:"bibliothèque (≠ librairie)", week:6},
 {en:"to pretend", fr:"faire semblant (≠ prétendre)", week:6},
 {en:"to ignore", fr:"ignorer délibérément", week:6},
 {en:"physician", fr:"médecin (≠ physicien)", week:6},
 {en:"to demand", fr:"exiger (≠ demander)", week:6},
 {en:"college", fr:"lycée/fac selon contexte US (≠ collège)", week:6},
 {en:"coin", fr:"pièce de monnaie (≠ coin/corner)", week:6},
 {en:"cave", fr:"grotte (≠ cave/cellar)", week:6},
 {en:"large", fr:"grand, gros", week:6},
 {en:"to support", fr:"soutenir (≠ supporter qqch)", week:6},
 {en:"to realize", fr:"se rendre compte (≠ réaliser)", week:6},
 {en:"advertisement", fr:"publicité (≠ avertissement)", week:6},
 {en:"to injure", fr:"blesser physiquement", week:6},
 {en:"rest", fr:"repos", week:6},
 {en:"to affect", fr:"affecter, influencer", week:6},
 {en:"to reveal", fr:"révéler", week:6},
 {en:"character", fr:"personnage (livre/film)", week:6},

 {en:"itinerary", fr:"itinéraire", week:7},
 {en:"layover", fr:"escale", week:7},
 {en:"to check in", fr:"s'enregistrer", week:7},
 {en:"baggage claim", fr:"retrait des bagages", week:7},
 {en:"customs", fr:"la douane", week:7},
 {en:"to board", fr:"embarquer", week:7},
 {en:"jet lag", fr:"décalage horaire", week:7},
 {en:"accommodation", fr:"logement, hébergement", week:7},
 {en:"to commute", fr:"faire un trajet domicile-travail", week:7},
 {en:"fare", fr:"tarif (transport)", week:7},
 {en:"to reroute", fr:"dérouter, changer d'itinéraire", week:7},
 {en:"currency exchange", fr:"bureau de change", week:7},
 {en:"to haggle", fr:"marchander", week:7},
 {en:"remote", fr:"isolé, reculé", week:7},
 {en:"scenic", fr:"pittoresque, avec de beaux paysages", week:7},
 {en:"off the beaten path", fr:"hors des sentiers battus", week:7},
 {en:"to wander", fr:"errer, flâner", week:7},
 {en:"landmark", fr:"monument, point de repère", week:7},
 {en:"budget-friendly", fr:"économique, abordable", week:7},
 {en:"to pack light", fr:"voyager léger", week:7},
 {en:"to miss (a flight)", fr:"rater un vol", week:7},
 {en:"connecting flight", fr:"vol de correspondance", week:7},
 {en:"to wing it", fr:"improviser", week:7},

 {en:"standpoint", fr:"point de vue", week:8},
 {en:"to concede", fr:"concéder", week:8},
 {en:"counterargument", fr:"contre-argument", week:8},
 {en:"compelling", fr:"convaincant", week:8},
 {en:"biased", fr:"partial, biaisé", week:8},
 {en:"to undermine", fr:"saper, affaiblir", week:8},
 {en:"plausible", fr:"plausible", week:8},
 {en:"to substantiate", fr:"étayer, prouver", week:8},
 {en:"contradictory", fr:"contradictoire", week:8},
 {en:"nuanced", fr:"nuancé", week:8},
 {en:"to refute", fr:"réfuter", week:8},
 {en:"viewpoint", fr:"point de vue", week:8},
 {en:"to elaborate", fr:"développer une idée", week:8},
 {en:"ambiguous", fr:"ambigu", week:8},
 {en:"to acknowledge", fr:"reconnaître un fait", week:8},
 {en:"skeptical", fr:"sceptique", week:8},
 {en:"to contend", fr:"soutenir, affirmer", week:8},
 {en:"credible", fr:"crédible", week:8},
 {en:"valid", fr:"valable, fondé", week:8},
 {en:"to bring up a point", fr:"soulever un point", week:8},
 {en:"to play devil's advocate", fr:"jouer l'avocat du diable", week:8},
 {en:"to back up (an argument)", fr:"étayer un argument", week:8},
 {en:"far-reaching", fr:"d'une grande portée", week:8},

 {en:"meticulous", fr:"méticuleux", week:9},
 {en:"mundane", fr:"banal, routinier", week:9},
 {en:"quaint", fr:"pittoresque, charme désuet", week:9},
 {en:"eerie", fr:"inquiétant, étrange", week:9},
 {en:"bland", fr:"fade, sans saveur", week:9},
 {en:"vibrant", fr:"vivant, éclatant", week:9},
 {en:"pristine", fr:"impeccable, immaculé", week:9},
 {en:"gritty", fr:"réaliste et brut", week:9},
 {en:"whimsical", fr:"fantaisiste", week:9},
 {en:"austere", fr:"austère", week:9},
 {en:"lavish", fr:"luxueux, somptueux", week:9},
 {en:"cluttered", fr:"encombré, en désordre", week:9},
 {en:"cozy", fr:"douillet, confortable", week:9},
 {en:"dreary", fr:"morne, triste", week:9},
 {en:"immaculate", fr:"impeccable", week:9},
 {en:"chaotic", fr:"chaotique", week:9},
 {en:"serene", fr:"serein, paisible", week:9},
 {en:"dingy", fr:"miteux, sale", week:9},
 {en:"bustling", fr:"animé, grouillant de monde", week:9},
 {en:"off-putting", fr:"repoussant, rebutant", week:9},
 {en:"run-down", fr:"délabré", week:9},
 {en:"picturesque", fr:"pittoresque", week:9},
 {en:"underwhelming", fr:"décevant, pas à la hauteur", week:9},

 {en:"to hang in there", fr:"tenir bon", week:10},
 {en:"no biggie", fr:"c'est pas grave", week:10},
 {en:"to crash", fr:"s'effondrer de fatigue / dormir chez qqn", week:10},
 {en:"to chill out", fr:"se détendre", week:10},
 {en:"to freak out", fr:"paniquer", week:10},
 {en:"low-key", fr:"discret, pas grand-chose", week:10},
 {en:"to be into (something)", fr:"kiffer, être fan de", week:10},
 {en:"to bail", fr:"se désister, annuler au dernier moment", week:10},
 {en:"sketchy", fr:"louche, pas net", week:10},
 {en:"to ghost (someone)", fr:"ignorer qqn du jour au lendemain", week:10},
 {en:"a big deal", fr:"un gros truc, qqch d'important", week:10},
 {en:"to zone out", fr:"décrocher, avoir l'esprit ailleurs", week:10},
 {en:"to crack up", fr:"éclater de rire", week:10},
 {en:"a long shot", fr:"un pari risqué, peu probable", week:10},
 {en:"to be all ears", fr:"être tout ouïe", week:10},
 {en:"to psych (oneself) up", fr:"se motiver mentalement", week:10},
 {en:"to flake (on someone)", fr:"se désister, lâcher qqn", week:10},
 {en:"to nail it", fr:"réussir parfaitement", week:10},
 {en:"to geek out", fr:"s'emballer sur un sujet qu'on adore", week:10},
 {en:"vibe", fr:"ambiance, feeling", week:10},
 {en:"to bounce", fr:"partir, filer (familier)", week:10},
 {en:"sus", fr:"suspect, louche (abrégé)", week:10},
 {en:"to vibe with (someone)", fr:"bien s'entendre avec qqn", week:10},

 {en:"inequality", fr:"inégalité", week:11},
 {en:"sustainability", fr:"durabilité", week:11},
 {en:"to advocate for", fr:"militer pour, défendre", week:11},
 {en:"mindset", fr:"état d'esprit", week:11},
 {en:"controversy", fr:"controverse", week:11},
 {en:"to tackle (an issue)", fr:"s'attaquer à un problème", week:11},
 {en:"awareness", fr:"prise de conscience", week:11},
 {en:"to address (an issue)", fr:"traiter, aborder un problème", week:11},
 {en:"empowerment", fr:"autonomisation", week:11},
 {en:"backlash", fr:"retour de bâton, contrecoup négatif", week:11},
 {en:"stereotype", fr:"stéréotype", week:11},
 {en:"discrimination", fr:"discrimination", week:11},
 {en:"to foster", fr:"favoriser, encourager", week:11},
 {en:"grassroots", fr:"de terrain, populaire (mouvement)", week:11},
 {en:"to implement", fr:"mettre en œuvre", week:11},
 {en:"transparency", fr:"transparence", week:11},
 {en:"to scrutinize", fr:"scruter, examiner de près", week:11},
 {en:"to overhaul", fr:"réformer en profondeur", week:11},
 {en:"to spark (debate)", fr:"déclencher un débat", week:11},
 {en:"polarizing", fr:"clivant", week:11},
 {en:"to marginalize", fr:"marginaliser", week:11},
 {en:"to bridge the gap", fr:"combler l'écart", week:11},
 {en:"systemic", fr:"systémique", week:11},

 {en:"ubiquitous", fr:"omniprésent", week:12},
 {en:"to reconcile", fr:"réconcilier, concilier", week:12},
 {en:"discrepancy", fr:"écart, divergence", week:12},
 {en:"relentless", fr:"implacable, incessant", week:12},
 {en:"to defy", fr:"défier", week:12},

 {en:"him", fr:"le, lui (complément) — ex. I saw him", week:"G", cat:"pronoun"},
 {en:"his", fr:"son, sa, ses (à lui) — ex. this is his car", week:"G", cat:"pronoun"},
 {en:"his (pronom)", fr:"le sien (à lui) — ex. this car is his", week:"G", cat:"pronoun"},
 {en:"himself", fr:"lui-même", week:"G", cat:"pronoun"},
 {en:"her (complément)", fr:"la, lui — ex. I saw her", week:"G", cat:"pronoun"},
 {en:"her (possessif)", fr:"son, sa, ses (à elle)", week:"G", cat:"pronoun"},
 {en:"hers", fr:"le sien, la sienne (à elle)", week:"G", cat:"pronoun"},
 {en:"herself", fr:"elle-même", week:"G", cat:"pronoun"},
 {en:"its", fr:"son, sa, ses (objet/animal) — ≠ it's = it is", week:"G", cat:"pronoun"},
 {en:"their", fr:"leur, leurs", week:"G", cat:"pronoun"},
 {en:"theirs", fr:"le/la leur", week:"G", cat:"pronoun"},
 {en:"themselves", fr:"eux-mêmes, elles-mêmes", week:"G", cat:"pronoun"},
 {en:"each other / one another", fr:"l'un l'autre", week:"G", cat:"pronoun"},
 {en:"whose", fr:"dont, à qui (possessif)", week:"G", cat:"pronoun"},
 {en:"whom", fr:"qui (complément, formel)", week:"G", cat:"pronoun"},

 {en:"however", fr:"cependant", week:"G", cat:"connector"},
 {en:"nevertheless", fr:"néanmoins", week:"G", cat:"connector"},
 {en:"although", fr:"bien que, même si", week:"G", cat:"connector"},
 {en:"even though", fr:"même si (plus fort)", week:"G", cat:"connector"},
 {en:"whereas", fr:"alors que, tandis que", week:"G", cat:"connector"},
 {en:"on the other hand", fr:"d'un autre côté", week:"G", cat:"connector"},
 {en:"in contrast", fr:"en revanche", week:"G", cat:"connector"},
 {en:"despite / in spite of", fr:"malgré", week:"G", cat:"connector"},
 {en:"moreover", fr:"de plus, en outre", week:"G", cat:"connector"},
 {en:"furthermore", fr:"de plus, qui plus est", week:"G", cat:"connector"},
 {en:"in addition", fr:"en plus, par ailleurs", week:"G", cat:"connector"},
 {en:"besides", fr:"en plus, d'ailleurs", week:"G", cat:"connector"},
 {en:"as a result", fr:"par conséquent", week:"G", cat:"connector"},
 {en:"therefore", fr:"donc, par conséquent", week:"G", cat:"connector"},
 {en:"thus", fr:"ainsi, donc", week:"G", cat:"connector"},
 {en:"hence", fr:"d'où, par conséquent (soutenu)", week:"G", cat:"connector"},
 {en:"consequently", fr:"en conséquence", week:"G", cat:"connector"},
 {en:"for this reason", fr:"pour cette raison", week:"G", cat:"connector"},
 {en:"meanwhile", fr:"pendant ce temps", week:"G", cat:"connector"},
 {en:"otherwise", fr:"sinon, autrement", week:"G", cat:"connector"},
 {en:"likewise", fr:"de même", week:"G", cat:"connector"},
 {en:"similarly", fr:"de la même manière", week:"G", cat:"connector"},
 {en:"in other words", fr:"en d'autres termes", week:"G", cat:"connector"},
 {en:"that being said", fr:"cela étant dit", week:"G", cat:"connector"},
 {en:"all things considered", fr:"tout bien considéré", week:"G", cat:"connector"},
];

/* ---------------- SENTENCE BANK (traduction FR -> EN) ---------------- */
const SENTENCES = [
 {week:1, fr:"Il remet toujours tout à plus tard, mais il finit par tout comprendre au dernier moment.", en:"He always procrastinates, but he ends up figuring everything out at the last minute."},
 {week:1, fr:"Son explication était simple et directe, donc facile à suivre.", en:"His explanation was straightforward, so it was easy to follow."},
 {week:1, fr:"Il est un peu trop crédule avec les inconnus.", en:"He's a bit too gullible with strangers."},
 {week:1, fr:"Ce restaurant est vraiment surestimé, je ne comprends pas le succès.", en:"This restaurant is really overrated, I don't get the hype."},
 {week:1, fr:"Elle a essayé de compenser son retard en travaillant le week-end.", en:"She tried to make up for being late by working on the weekend."},
 {week:2, fr:"J'ai hâte de te revoir ce week-end.", en:"I'm looking forward to seeing you this weekend."},
 {week:2, fr:"Il a du mal à joindre les deux bouts depuis qu'il a perdu son emploi.", en:"He's struggling to make ends meet since he lost his job."},
 {week:2, fr:"Ne le laisse pas te convaincre de faire quelque chose que tu ne veux pas.", en:"Don't let him talk you into doing something you don't want to do."},
 {week:2, fr:"Ils se sont éloignés petit à petit après le lycée.", en:"They gradually drifted apart after high school."},
 {week:2, fr:"Elle n'a jamais cédé, même sous la pression.", en:"She never gave in, even under pressure."},
 {week:3, fr:"Nous devons prioriser ce projet avant la date limite.", en:"We need to prioritize this project before the deadline."},
 {week:3, fr:"Elle a délégué la plupart des tâches pour réduire sa charge de travail.", en:"She delegated most of the tasks to reduce her workload."},
 {week:3, fr:"Le manque de personnel est devenu un vrai goulot d'étranglement pour l'équipe.", en:"The lack of staff has become a real bottleneck for the team."},
 {week:3, fr:"Il faut relancer le client, on n'a pas eu de nouvelles depuis une semaine.", en:"We need to follow up with the client, we haven't heard back in a week."},
 {week:3, fr:"Cette entreprise a externalisé une grande partie de sa production.", en:"This company outsourced a large part of its production."},
 {week:4, fr:"Elle reste toujours calme et résiliente face aux difficultés.", en:"She always stays calm and resilient in the face of difficulties."},
 {week:4, fr:"Il peut être condescendant quand il parle à des débutants.", en:"He can be condescending when he talks to beginners."},
 {week:4, fr:"Ne lui en veux pas, elle a juste eu une réaction excessive parce qu'elle est un peu susceptible.", en:"Don't hold it against her, she just overreacted because she's a bit touchy."},
 {week:4, fr:"Il est resté humble malgré son succès.", en:"He stayed humble despite his success."},
 {week:4, fr:"Elle garde encore rancune contre son ancien collègue.", en:"She still holds a grudge against her former colleague."},
 {week:5, fr:"Arrête de tourner autour du pot et dis-moi ce qui s'est passé.", en:"Stop beating around the bush and tell me what happened."},
 {week:5, fr:"On dirait bien qu'on n'est pas sur la même longueur d'onde à ce sujet.", en:"It seems like we don't see eye to eye on this."},
 {week:5, fr:"Il a fini par se résigner et accepter la situation.", en:"He finally bit the bullet and accepted the situation."},
 {week:5, fr:"Perdre ce poste s'est finalement révélé être un mal pour un bien.", en:"Losing that job turned out to be a blessing in disguise."},
 {week:5, fr:"Ce voyage m'a coûté les yeux de la tête.", en:"That trip cost me an arm and a leg."},
 {week:6, fr:"En fait, je n'ai pas pu assister à la réunion hier.", en:"Actually, I couldn't attend the meeting yesterday."},
 {week:6, fr:"Il fait semblant de ne pas comprendre pour éviter le sujet.", en:"He's pretending not to understand to avoid the topic."},
 {week:6, fr:"Elle s'est rendu compte de son erreur trop tard.", en:"She realized her mistake too late."},
 {week:6, fr:"Le médecin a exigé qu'il se repose une semaine complète.", en:"The physician demanded that he rest for a full week."},
 {week:6, fr:"Cette publicité a beaucoup marqué les esprits.", en:"This advertisement really stuck in people's minds."},
 {week:7, fr:"Nous avons raté notre vol de correspondance à cause de l'escale trop courte.", en:"We missed our connecting flight because the layover was too short."},
 {week:7, fr:"Ce village hors des sentiers battus vaut vraiment le détour.", en:"This off-the-beaten-path village is really worth the detour."},
 {week:7, fr:"Je préfère voyager léger et improviser un peu.", en:"I prefer to pack light and wing it a little."},
 {week:7, fr:"On a marchandé le prix au marché local.", en:"We haggled over the price at the local market."},
 {week:7, fr:"Le décalage horaire m'a complètement épuisé pendant deux jours.", en:"The jet lag completely wore me out for two days."},
 {week:8, fr:"Son argument était convaincant, mais un peu biaisé.", en:"His argument was compelling, but a bit biased."},
 {week:8, fr:"Je vais jouer l'avocat du diable un instant.", en:"I'm going to play devil's advocate for a moment."},
 {week:8, fr:"Elle a reconnu que son point de vue n'était pas totalement crédible.", en:"She acknowledged that her viewpoint wasn't entirely credible."},
 {week:8, fr:"Cette décision aura des conséquences d'une grande portée.", en:"This decision will have far-reaching consequences."},
 {week:8, fr:"Il a essayé de réfuter chacun de mes arguments.", en:"He tried to refute every single one of my arguments."},
 {week:9, fr:"Le quartier était animé, coloré et un peu chaotique.", en:"The neighborhood was bustling, vibrant, and a bit chaotic."},
 {week:9, fr:"Cette petite maison de campagne a un charme désuet et pittoresque.", en:"This little country house has a quaint, picturesque charm."},
 {week:9, fr:"Le film était franchement décevant par rapport aux critiques.", en:"The movie was frankly underwhelming compared to the reviews."},
 {week:9, fr:"L'appartement était impeccable et parfaitement rangé.", en:"The apartment was immaculate and perfectly tidy."},
 {week:9, fr:"Cette ruelle sombre avait quelque chose d'inquiétant.", en:"That dark alley had something eerie about it."},
 {week:10, fr:"Détends-toi, ce n'est pas grand-chose.", en:"Chill out, it's no biggie."},
 {week:10, fr:"Il a complètement disparu sans donner de nouvelles.", en:"He totally ghosted me."},
 {week:10, fr:"Cet endroit a une super ambiance, je kiffe.", en:"This place has a great vibe, I'm really into it."},
 {week:10, fr:"J'ai décroché pendant toute la réunion.", en:"I completely zoned out during the whole meeting."},
 {week:10, fr:"Elle a vraiment assuré à son entretien.", en:"She really nailed her interview."},
 {week:11, fr:"Cette décision politique risque de provoquer un vrai retour de bâton.", en:"This political decision is likely to cause a real backlash."},
 {week:11, fr:"L'entreprise a mis en œuvre de nouvelles mesures pour plus de transparence.", en:"The company implemented new measures for more transparency."},
 {week:11, fr:"Ce sujet est assez clivant, il divise l'opinion publique.", en:"This topic is quite polarizing, it divides public opinion."},
 {week:11, fr:"Ce mouvement citoyen est né d'une initiative de terrain.", en:"This movement started as a grassroots initiative."},
 {week:11, fr:"Le problème est systémique, pas seulement individuel.", en:"The problem is systemic, not just individual."},
 {week:12, fr:"Les smartphones sont devenus omniprésents dans notre quotidien.", en:"Smartphones have become ubiquitous in our daily lives."},
 {week:12, fr:"Il y a un écart important entre les deux rapports.", en:"There's a significant discrepancy between the two reports."},
 {week:12, fr:"Elle a fini par se réconcilier avec sa sœur.", en:"She finally reconciled with her sister."},
 {week:"G", cat:"pronoun", fr:"C'est sa voiture à lui, pas la sienne à elle.", en:"It's his car, not hers."},
 {week:"G", cat:"pronoun", fr:"Le chien a remué la queue.", en:"The dog wagged its tail."},
 {week:"G", cat:"pronoun", fr:"L'homme dont la voiture est tombée en panne attend le dépanneur.", en:"The man whose car broke down is waiting for the tow truck."},
 {week:"G", cat:"pronoun", fr:"Ils s'aident toujours l'un l'autre.", en:"They always help each other."},
 {week:"G", cat:"pronoun", fr:"C'est leur maison, pas la nôtre.", en:"It's their house, not ours."},
 {week:"G", cat:"connector", fr:"Il pleuvait, cependant nous sommes quand même sortis.", en:"It was raining, however we still went out."},
 {week:"G", cat:"connector", fr:"Malgré la fatigue, elle a terminé le marathon.", en:"Despite being tired, she finished the marathon."},
 {week:"G", cat:"connector", fr:"Le projet a pris du retard ; par conséquent, la date de lancement a été repoussée.", en:"The project fell behind schedule; therefore, the launch date was pushed back."},
 {week:"G", cat:"connector", fr:"Elle est timide ; il est, en revanche, très à l'aise en public.", en:"She is shy; he is, in contrast, very comfortable in public."},
 {week:"G", cat:"connector", fr:"Dépêche-toi, sinon on va rater le train.", en:"Hurry up, otherwise we'll miss the train."},
];

/* ---------------- STATE / STORAGE ---------------- */
const STORAGE_KEY = "vocab-progress-v1";
let progress = {};
try {
  const raw = localStorage.getItem(STORAGE_KEY);
  progress = raw ? JSON.parse(raw) : {};
} catch (e) { progress = {}; }

function saveProgress() {
  try { localStorage.setItem(STORAGE_KEY, JSON.stringify(progress)); }
  catch (e) { /* storage unavailable, fail silently */ }
}
function getEntry(word) {
  if (!progress[word]) progress[word] = { correct: 0, wrong: 0 };
  return progress[word];
}
function markResult(word, ok) {
  const e = getEntry(word);
  if (ok) { e.correct++; } else { e.wrong++; }
  saveProgress();
}

const POOLS = [
  { id: "all", label: "Tout", sub: "12 semaines + grammaire", filter: () => true },
  { id: "w1-3", label: "Semaines 1–3", sub: "quotidien & pro", filter: v => typeof v.week === "number" && v.week <= 3 },
  { id: "w4-6", label: "Semaines 4–6", sub: "caractère & pièges", filter: v => typeof v.week === "number" && v.week >= 4 && v.week <= 6 },
  { id: "w7-9", label: "Semaines 7–9", sub: "voyage & débat", filter: v => typeof v.week === "number" && v.week >= 7 && v.week <= 9 },
  { id: "w10-12", label: "Semaines 10–12", sub: "familier & société", filter: v => typeof v.week === "number" && v.week >= 10 },
  { id: "pronouns", label: "Pronoms", sub: "him / his / hers...", filter: v => v.cat === "pronoun" },
  { id: "connectors", label: "Connecteurs", sub: "however, therefore...", filter: v => v.cat === "connector" },
  { id: "review", label: "Mes mots à revoir", sub: "d'après tes erreurs", filter: null },
];
let selectedPool = "all";

/* ---------------- HOME RENDER ---------------- */
const poolGrid = document.getElementById("poolGrid");
function reviewWords() {
  return VOCAB.filter(v => {
    const e = progress[v.en];
    return e && e.wrong > 0 && e.wrong >= e.correct;
  });
}
function renderHome() {
  poolGrid.innerHTML = "";
  POOLS.forEach(p => {
    const btn = document.createElement("button");
    btn.type = "button";
    btn.className = "pool-opt" + (selectedPool === p.id ? " selected" : "");
    const count = p.id === "review" ? reviewWords().length : VOCAB.filter(p.filter).length;
    btn.innerHTML = `${p.label}<small>${p.sub} · ${count} mots</small>`;
    btn.addEventListener("click", () => { selectedPool = p.id; renderHome(); });
    poolGrid.appendChild(btn);
  });

  const total = Object.keys(progress).length;
  let mastered = 0;
  Object.values(progress).forEach(e => { if (e.correct >= 2 && e.wrong === 0) mastered++; });
  document.getElementById("statTotal").textContent = total;
  document.getElementById("statReview").textContent = reviewWords().length;
  document.getElementById("statMastered").textContent = mastered;
  document.getElementById("statStreak").textContent = computeStreak();
  renderWotd();
}
function currentPoolWords() {
  if (selectedPool === "review") {
    const rw = reviewWords();
    return rw.length ? rw : VOCAB.slice();
  }
  const p = POOLS.find(x => x.id === selectedPool);
  return VOCAB.filter(p.filter);
}
function pickSessionWords(n) {
  const pool = currentPoolWords().slice();
  for (let i = pool.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [pool[i], pool[j]] = [pool[j], pool[i]];
  }
  return pool.slice(0, Math.min(n, pool.length));
}

/* ---------------- SCREEN SWITCHING ---------------- */
function showScreen(id) {
  document.querySelectorAll(".screen").forEach(s => s.classList.remove("active"));
  document.getElementById(id).classList.add("active");
}

/* ---------------- QUIZ ---------------- */
let quizWords = [], quizIndex = 0, quizScore = 0, quizMisses = [], quizLastSet = [];

function startQuiz(words) {
  quizWords = words;
  quizIndex = 0;
  quizScore = 0;
  quizMisses = [];
  showScreen("screen-quiz");
  renderQuizQuestion();
}
document.getElementById("startQuiz").addEventListener("click", () => {
  const words = pickSessionWords(10);
  quizLastSet = words;
  startQuiz(words);
});
document.getElementById("quizBack").addEventListener("click", () => { renderHome(); showScreen("screen-home"); });

function makeOptions(correctWord) {
  const distractors = VOCAB.filter(v => v.en !== correctWord.en);
  for (let i = distractors.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [distractors[i], distractors[j]] = [distractors[j], distractors[i]];
  }
  const opts = [correctWord, ...distractors.slice(0, 3)];
  for (let i = opts.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [opts[i], opts[j]] = [opts[j], opts[i]];
  }
  return opts;
}

function renderQuizQuestion() {
  const w = quizWords[quizIndex];
  document.getElementById("quizCounter").textContent = `Question ${quizIndex + 1}/${quizWords.length}`;
  document.getElementById("quizProgress").style.width = `${(quizIndex / quizWords.length) * 100}%`;
  document.getElementById("quizWord").textContent = w.en;
  document.getElementById("quizTag").textContent = w.cat ? (w.cat === "pronoun" ? "pronom" : "connecteur") : `semaine ${w.week}`;
  const optsWrap = document.getElementById("quizOptions");
  optsWrap.innerHTML = "";
  const letters = ["a", "b", "c", "d"];
  const options = makeOptions(w);
  const nextBtn = document.getElementById("quizNext");
  nextBtn.disabled = true;
  nextBtn.textContent = quizIndex === quizWords.length - 1 ? "Voir le résultat" : "Suivant";

  options.forEach((opt, i) => {
    const b = document.createElement("button");
    b.className = "opt";
    b.innerHTML = `<span class="letter">${letters[i]}</span><span>${opt.fr}</span>`;
    b.addEventListener("click", () => {
      const isCorrect = opt.en === w.en;
      Array.from(optsWrap.children).forEach(c => c.disabled = true);
      if (isCorrect) {
        b.classList.add("correct");
        quizScore++;
      } else {
        b.classList.add("wrong");
        quizMisses.push(w);
        const correctBtn = Array.from(optsWrap.children).find((c, idx) => options[idx].en === w.en);
        if (correctBtn) correctBtn.classList.add("correct");
      }
      markResult(w.en, isCorrect);
      nextBtn.disabled = false;
    });
    optsWrap.appendChild(b);
  });
}
document.getElementById("quizNext").addEventListener("click", () => {
  quizIndex++;
  if (quizIndex >= quizWords.length) {
    document.getElementById("quizProgress").style.width = "100%";
    showQuizResults();
  } else {
    renderQuizQuestion();
  }
});

function showQuizResults() {
  showScreen("screen-results");
  document.getElementById("resScore").textContent = `${quizScore}/${quizWords.length}`;
  document.getElementById("resLabel").textContent = "bonnes réponses";
  const list = document.getElementById("resMissList");
  list.innerHTML = "";
  const uniqueMisses = [...new Map(quizMisses.map(w => [w.en, w])).values()];
  if (uniqueMisses.length === 0) {
    document.getElementById("resMissWrap").innerHTML = `<div class="empty-note">Aucune erreur — bien joué.</div>`;
  } else {
    uniqueMisses.forEach(w => {
      const li = document.createElement("li");
      li.innerHTML = `<span class="w">${w.en}</span><span class="t">${w.fr}</span>`;
      list.appendChild(li);
    });
  }
  document.getElementById("resRetry").onclick = () => startQuiz(quizLastSet);
}

/* ---------------- FLASHCARDS ---------------- */
let flashWords = [], flashIndex = 0, flashFlipped = false;

document.getElementById("startFlash").addEventListener("click", () => {
  flashWords = pickSessionWords(10);
  flashIndex = 0;
  showScreen("screen-flash");
  renderFlashCard();
});
document.getElementById("flashBack").addEventListener("click", () => { renderHome(); showScreen("screen-home"); });

function renderFlashCard() {
  flashFlipped = false;
  const w = flashWords[flashIndex];
  document.getElementById("flashCounter").textContent = `Carte ${flashIndex + 1}/${flashWords.length}`;
  document.getElementById("flashProgress").style.width = `${(flashIndex / flashWords.length) * 100}%`;
  document.getElementById("flashFront").textContent = w.en;
  document.getElementById("flashBackText").textContent = w.fr;
  document.getElementById("flashCard").classList.remove("flipped");
  document.getElementById("flashHint").textContent = "Touche la carte pour révéler la traduction";
  document.getElementById("flashYes").disabled = true;
  document.getElementById("flashNo").disabled = true;
}
document.getElementById("flashCard").addEventListener("click", () => {
  flashFlipped = !flashFlipped;
  document.getElementById("flashCard").classList.toggle("flipped", flashFlipped);
  if (flashFlipped) {
    document.getElementById("flashHint").textContent = "Comment tu t'en sortais ?";
    document.getElementById("flashYes").disabled = false;
    document.getElementById("flashNo").disabled = false;
  } else {
    document.getElementById("flashHint").textContent = "Touche la carte pour révéler la traduction";
    document.getElementById("flashYes").disabled = true;
    document.getElementById("flashNo").disabled = true;
  }
});
function advanceFlash(knew) {
  const w = flashWords[flashIndex];
  markResult(w.en, knew);
  flashIndex++;
  if (flashIndex >= flashWords.length) {
    document.getElementById("flashProgress").style.width = "100%";
    showFlashResults();
  } else {
    renderFlashCard();
  }
}
document.getElementById("flashYes").addEventListener("click", () => advanceFlash(true));
document.getElementById("flashNo").addEventListener("click", () => advanceFlash(false));

function showFlashResults() {
  showScreen("screen-results");
  const known = flashWords.filter(w => getEntry(w.en).correct > 0).length;
  document.getElementById("resScore").textContent = `${flashWords.length}`;
  document.getElementById("resLabel").textContent = "cartes vues";
  const list = document.getElementById("resMissList");
  list.innerHTML = "";
  document.getElementById("resMissWrap").innerHTML = `<fieldset><legend>À revoir</legend><ul class="miss-list" id="resMissList2"></ul></fieldset>`;
  const list2 = document.getElementById("resMissList2");
  const toReview = flashWords.filter(w => {
    const e = getEntry(w.en);
    return e.wrong > 0 && e.wrong >= e.correct;
  });
  if (toReview.length === 0) {
    document.getElementById("resMissWrap").innerHTML = `<div class="empty-note">Rien à signaler cette fois.</div>`;
  } else {
    toReview.forEach(w => {
      const li = document.createElement("li");
      li.innerHTML = `<span class="w">${w.en}</span><span class="t">${w.fr}</span>`;
      list2.appendChild(li);
    });
  }
  document.getElementById("resRetry").onclick = () => {
    flashWords = pickSessionWords(10);
    flashIndex = 0;
    showScreen("screen-flash");
    renderFlashCard();
  };
}

document.getElementById("resHome").addEventListener("click", () => { renderHome(); showScreen("screen-home"); });

/* ---------------- SENTENCE HISTORY / STREAK ---------------- */
const SENTENCES_KEY = "vocab-sentences-v1";
let sentences = [];
try {
  const raw = localStorage.getItem(SENTENCES_KEY);
  sentences = raw ? JSON.parse(raw) : [];
} catch (e) { sentences = []; }
function saveSentences() {
  try { localStorage.setItem(SENTENCES_KEY, JSON.stringify(sentences)); }
  catch (e) {}
}
function todayISO() {
  return new Date().toISOString().slice(0, 10);
}
function computeStreak() {
  if (sentences.length === 0) return 0;
  const days = [...new Set(sentences.map(s => s.date))].sort().reverse();
  let streak = 0;
  let cursor = new Date();
  for (let i = 0; i < days.length; i++) {
    const expected = cursor.toISOString().slice(0, 10);
    if (days[i] === expected) {
      streak++;
      cursor.setDate(cursor.getDate() - 1);
    } else if (i === 0 && days[i] !== expected) {
      // most recent entry isn't today or yesterday-chain start check
      const yest = new Date();
      yest.setDate(yest.getDate() - 1);
      if (days[i] === yest.toISOString().slice(0, 10)) {
        streak++;
        cursor = yest;
        cursor.setDate(cursor.getDate() - 1);
      } else {
        break;
      }
    } else {
      break;
    }
  }
  return streak;
}

/* ---------------- WRITE MODE (traduction FR -> EN) ---------------- */
let writeCurrentSentence = null;
let writeCorrected = false;
function sentencePoolForSelection() {
  if (selectedPool === "review") return SENTENCES.slice();
  const p = POOLS.find(x => x.id === selectedPool);
  const matched = SENTENCES.filter(p.filter);
  return matched.length ? matched : SENTENCES.slice();
}
function pickSentence() {
  const pool = sentencePoolForSelection();
  let choice;
  do {
    choice = pool[Math.floor(Math.random() * pool.length)];
  } while (pool.length > 1 && writeCurrentSentence && choice.fr === writeCurrentSentence.fr);
  return choice;
}
function renderWriteSentence() {
  writeCurrentSentence = pickSentence();
  writeCorrected = false;
  document.getElementById("writeFrSentence").textContent = writeCurrentSentence.fr;
  document.getElementById("writeArea").value = "";
  document.getElementById("writeArea").disabled = false;
  document.getElementById("writeCorrection").style.display = "none";
  document.getElementById("writeSave").textContent = "Voir la correction";
  document.getElementById("writeSave").disabled = true;
  renderWriteHistory();
}
document.getElementById("startWrite").addEventListener("click", () => {
  showScreen("screen-write");
  renderWriteSentence();
});
document.getElementById("writeBack").addEventListener("click", () => { renderHome(); showScreen("screen-home"); });
document.getElementById("writeShuffle").addEventListener("click", renderWriteSentence);
document.getElementById("writeArea").addEventListener("input", (e) => {
  if (!writeCorrected) document.getElementById("writeSave").disabled = e.target.value.trim().length < 2;
});
document.getElementById("writeSave").addEventListener("click", () => {
  if (writeCorrected) return;
  const text = document.getElementById("writeArea").value.trim();
  if (text.length < 2) return;
  writeCorrected = true;
  document.getElementById("writeRefText").textContent = writeCurrentSentence.en;
  document.getElementById("writeCorrection").style.display = "block";
  document.getElementById("writeArea").disabled = true;
  document.getElementById("writeSave").disabled = true;
  sentences.unshift({
    date: todayISO(),
    fr: writeCurrentSentence.fr,
    userEn: text,
    refEn: writeCurrentSentence.en,
  });
  saveSentences();
  renderWriteHistory();
});
function renderWriteHistory() {
  const wrap = document.getElementById("writeHistoryWrap");
  const list = document.getElementById("writeHistoryList");
  if (sentences.length === 0) {
    wrap.style.display = "none";
    return;
  }
  wrap.style.display = "block";
  list.innerHTML = "";
  sentences.slice(0, 5).forEach(s => {
    const li = document.createElement("li");
    li.style.flexDirection = "column";
    li.style.alignItems = "flex-start";
    li.style.gap = "3px";
    li.innerHTML = `<span class="t" style="font-size:12px;">${s.date} · ${s.fr}</span><span class="w" style="font-family:'IBM Plex Sans'; font-weight:400;">Toi : ${s.userEn}</span><span class="t" style="font-size:13px; color:var(--accent);">Correction : ${s.refEn}</span>`;
    list.appendChild(li);
  });
}

/* ---------------- WORD OF THE DAY ---------------- */
function renderWotd() {
  const dayIndex = Math.floor(Date.now() / 86400000);
  const w = VOCAB[dayIndex % VOCAB.length];
  document.getElementById("wotdEn").textContent = w.en;
  document.getElementById("wotdFr").textContent = w.fr;
}

/* ---------------- EXPLORER (browse & search) ---------------- */
document.getElementById("startBrowse").addEventListener("click", () => {
  showScreen("screen-browse");
  document.getElementById("browseSearch").value = "";
  renderBrowseList("");
  document.getElementById("browseSearch").focus();
});
document.getElementById("browseBack").addEventListener("click", () => { renderHome(); showScreen("screen-home"); });
document.getElementById("browseSearch").addEventListener("input", (e) => renderBrowseList(e.target.value));

function renderBrowseList(query) {
  const q = query.trim().toLowerCase();
  const results = VOCAB.filter(w => !q || w.en.toLowerCase().includes(q) || w.fr.toLowerCase().includes(q));
  document.getElementById("browseCount").textContent = `${results.length} mot${results.length > 1 ? "s" : ""}`;
  const list = document.getElementById("browseList");
  list.innerHTML = "";
  results.slice(0, 300).forEach(w => {
    const li = document.createElement("li");
    li.innerHTML = `<span class="en">${w.en}</span><span class="fr">${w.fr}</span>`;
    list.appendChild(li);
  });
  if (results.length === 0) {
    list.innerHTML = `<div class="empty-note">Aucun résultat.</div>`;
  }
}

/* ---------------- THEME ---------------- */
const themeToggle = document.getElementById("themeToggle");
function applyThemeLabel() {
  const t = document.documentElement.getAttribute("data-theme");
  themeToggle.textContent = t === "dark" ? "Mode clair" : "Mode sombre";
}
themeToggle.addEventListener("click", () => {
  const current = document.documentElement.getAttribute("data-theme");
  const next = current === "dark" ? "light" : "dark";
  document.documentElement.setAttribute("data-theme", next);
  try { localStorage.setItem("vocab-theme", next); } catch (e) {}
  applyThemeLabel();
});
try {
  const savedTheme = localStorage.getItem("vocab-theme");
  if (savedTheme) document.documentElement.setAttribute("data-theme", savedTheme);
} catch (e) {}
applyThemeLabel();

/* ---------------- INIT ---------------- */
renderHome();
</script>
</body>
</html>
