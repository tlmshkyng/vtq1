# vtq1
Verb Table Quiz p.6-7
<!doctype html>
<html lang="en">
 <head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20260914-23-388855d","C":{"Abril Fatface":"YACgEZbkUVE,0","Alfa Slab One":"YACgEYS9sJU,0","Anton":"YACgEcYqQ-A,0","Archivo":"YAHO2-t-jNE,0","Arial":"YAGyDvJ_4Ts,0","Bebas Neue":"YACgESME5ew,0","Bricolage Grotesque":"YAFyMcdwzpc,0","Canva Sans":"YAFLd8sKbwc,2","Caveat":"YALBs2ploWQ,0","Comic Sans MS":"YAHO2VMiyZo,0","Cormorant Garamond":"YAFdJhX-538,0","Courier New":"YAGzXiGs0_8,0","DM Sans":"YAD1aU3sLnI,0","DM Serif Display":"YAD1aYG82rc,0","Forum":"YACgEcnnqB4,0","Fraunces":"YAEul-FRQw4,0","Georgia":"YAGzXkO0pEM,0","Helvetica Neue":"YAFcf6CtJfI,0","Impact":"YAFcfnjI7Vk,0","Inter":"YAFdJvSyp_k,3","Iowan Old Style":"YAGNIFa8j9o,0","Jacques Francois":"YAHO2a5g66Q,0","JetBrains Mono":"YAFdJksXcAk,0","Libre Baskerville":"YACgEUFdPdA,0","Manrope":"YAHO2b2feC4,0","Merriweather":"YACgEXvHxxs,0","Montserrat":"YADLjI9qxTA,0","Nunito":"YACgEX8C5Gg,0","Oleo Script":"YACgEQQ14jI,0","Phantom Sans":"YAHO2E8Pb88,0","Playfair Display":"YACgEYmuCJE,0","Poppins":"YAFdJjbTu24,1","Press Start 2P":"YAFyGr-8pmQ,0","Quicksand":"YADWjpfPmdk,0","Raleway":"YACgEVg3xZg,0","Segoe UI":"YAHNdRD1Klw,0","Source Sans 3":"YAG4lO1Mj10,0","Spectral":"YAHO2rVUHIM,0","Times New Roman":"YAGzXW3gftg,0","Times":"YAGzXW3gftg,0","Ubuntu":"YACgERDU--Q,0","Work Sans":"YAGXhLOKv44,0","Yellowtail":"YACgEYG4kG4,0","ui-monospace":"YADlN8CFZ8Q,0","ui-sans-serif":"YACkoN-xg4g,0"}}');</script><script src="/_sdk/c21197326e9a1154.telemetry_sdk.js" integrity="sha512-Aqwl+NmLtKBcMQM4HY+W9lmBHa+zP5MqSEuYfCjkzt4xeOSv2xNz81cCp7JyXBVrY+zojg5o94FHY/R31v2d3Q=="></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Verb Study Practice</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.577.0/dist/umd/lucide.min.js"></script>
  <script src="/_sdk/efe904fe8a212716.data_sdk.js" integrity="sha512-oiO0pmn5llS1uDeB2l690YywxqOe/a0U1kzY6RGaLZXtyh9YjTk1CUoK/bJUugc1QbUaJMJ3IE1MtpNY5NBZCw=="></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&amp;family=Fraunces:opsz,wght@9..144,700&amp;display=swap" rel="stylesheet">
  <style>
    :root {
      --ink: #17324d;
      --blue: #245985;
      --blue-deep: #173f63;
      --gold: #f4bb45;
      --paper: #fffdf7;
      --mist: #edf3f7;
      --line: #d6e1e8;
      --success: #18735d;
      --danger: #b5443d;
    }
    * { box-sizing: border-box; }
    body { font-family: "DM Sans", sans-serif; color: var(--ink); }
    .study-shell { width: 100%; min-height: calc(100 * min(var(--vh, 1vh), 1vh)); background: #f5f1e8; }
    .paper-grid {
      background-color: var(--paper);
      background-image: linear-gradient(rgba(36,89,133,.045) 1px, transparent 1px), linear-gradient(90deg, rgba(36,89,133,.045) 1px, transparent 1px);
      background-size: 28px 28px;
    }
    .title-font { font-family: "Fraunces", serif; }
    .tab-button { border-bottom: 3px solid transparent; transition: .2s ease; }
    .tab-button.active { color: var(--blue-deep); border-color: var(--gold); background: #fff8df; }
    .tab-panel { display: none; }
    .tab-panel.active { display: block; animation: rise .28s ease-out; }
    .flashcard { perspective: 1000px; min-height: 290px; cursor: pointer; }
    .flash-inner { position: relative; width: 100%; height: 100%; min-height: 290px; transform-style: preserve-3d; transition: transform .55s ease; }
    .flashcard.is-revealed .flash-inner { transform: rotateY(180deg); }
    .flash-face { position: absolute; inset: 0; backface-visibility: hidden; border-radius: 1.25rem; display: flex; flex-direction: column; justify-content: center; align-items: center; padding: 2rem; }
    .flash-back { transform: rotateY(180deg); }
    .option-button { transition: transform .16s ease, border-color .16s ease, background .16s ease; }
    .option-button:hover { transform: translateY(-2px); }
    .option-button.correct { border-color: #18735d; background: #e7f5ef; color: #125845; }
    .option-button.incorrect { border-color: #b5443d; background: #fbeceb; color: #8c302b; }
    .option-button:disabled { cursor: default; }
    @keyframes rise { from { opacity: 0; transform: translateY(7px); } to { opacity: 1; transform: translateY(0); } }
    button:focus-visible { outline: 3px solid var(--gold); outline-offset: 3px; }
    .verb-row:nth-child(even) { background: rgba(237,243,247,.72); }
  </style>
  <script src="/_sdk/516e6ea369c7bec3.resizing_sdk.js" type="text/javascript" integrity="sha512-Wkd7fz8smjKWLQKfGpbCeEd3vaTDgYMKS80NvRC3uLd35H5OX7WRPnw4yQS4rfT6pCk962a/QaOHPQl5a6q0DQ=="></script>
 </head>
 <body data-template-id="__page-root">
  <div class="study-shell">
   <header data-template-id="study-header" class="canva-header bg-[#245985] text-white border-b-4 border-[#f4bb45]">
    <div class="w-full max-w-6xl mx-auto px-5 py-7 sm:px-8">
     <div class="flex flex-col gap-3 sm:flex-row sm:items-end sm:justify-between">
      <div>
       <p data-template-id="school-label" class="canva-text text-sm font-semibold tracking-[0.13em] uppercase text-[#dcecf5]"></p>
       <h1 data-template-id="page-title" class="canva-text title-font mt-1 leading-tight"></h1>
      </div>
      <div class="flex items-center gap-2 text-[#fff4cf]">
       <i data-lucide="book-open" width="22" height="22" aria-hidden="true"></i>
       <p data-template-id="header-helper" class="canva-text text-sm font-medium"></p>
      </div>
     </div>
    </div>
   </header>
   <main class="w-full max-w-6xl mx-auto px-5 py-7 sm:px-8 sm:py-10">
    <section data-template-id="progress-panel" class="canva-panel rounded-2xl bg-[#fff8df] border border-[#ecd184] px-5 py-5 shadow-sm mb-7">
     <div class="flex flex-col gap-4 sm:flex-row sm:items-center sm:justify-between">
      <div>
       <h2 data-template-id="progress-heading" class="canva-text font-bold text-[#173f63]"></h2>
       <p data-template-id="progress-copy" class="canva-text mt-1 text-sm text-[#416078]"></p>
      </div>
      <div class="flex items-center gap-4">
       <div class="text-right">
        <p id="accuracy-value" class="title-font text-3xl font-bold text-[#173f63]" aria-live="polite">—</p>
        <p data-template-id="accuracy-label" class="canva-text text-xs font-bold uppercase tracking-wider text-[#587084]"></p>
       </div>
       <div class="h-12 w-12 rounded-full bg-[#f4bb45] flex items-center justify-center text-[#173f63]">
        <i data-lucide="award" width="25" height="25" aria-hidden="true"></i>
       </div>
      </div>
     </div>
     <div class="mt-4 h-2.5 rounded-full bg-[#f1dfaa] overflow-hidden" aria-label="Practice progress">
      <div id="progress-bar" class="h-full w-0 rounded-full bg-[#245985] transition-all duration-500"></div>
     </div>
    </section>
    <nav aria-label="Study sections" class="mb-6">
     <div class="grid grid-cols-3 rounded-xl overflow-hidden border border-[#d6e1e8] bg-white shadow-sm">
      <button data-template-id="table-tab" class="canva-button tab-button active px-3 py-4 text-sm font-bold text-[#416078]" type="button" data-tab="table" aria-selected="true"></button> <button data-template-id="cards-tab" class="canva-button tab-button px-3 py-4 text-sm font-bold text-[#416078]" type="button" data-tab="cards" aria-selected="false"></button> <button data-template-id="quiz-tab" class="canva-button tab-button px-3 py-4 text-sm font-bold text-[#416078]" type="button" data-tab="quiz" aria-selected="false"></button>
     </div>
    </nav>
    <section id="table-panel" class="tab-panel active" aria-label="Verb table">
     <div data-template-id="table-panel-card" class="canva-card paper-grid rounded-2xl border border-[#d6e1e8] overflow-hidden shadow-sm">
      <div class="p-5 sm:p-7 border-b border-[#d6e1e8] bg-white/85">
       <h2 data-template-id="table-heading" class="canva-text title-font text-[#173f63]"></h2>
       <p data-template-id="table-copy" class="canva-text mt-1 text-sm text-[#567085]"></p>
      </div>
      <div class="overflow-x-auto">
       <table class="w-full min-w-[680px] text-left">
        <thead class="bg-[#245985] text-white">
         <tr>
          <th data-template-id="number-header" class="canva-text px-5 py-4 text-sm font-bold"></th>
          <th data-template-id="present-header" class="canva-text px-5 py-4 text-sm font-bold"></th>
          <th data-template-id="past-header" class="canva-text px-5 py-4 text-sm font-bold"></th>
          <th data-template-id="participle-header" class="canva-text px-5 py-4 text-sm font-bold"></th>
          <th data-template-id="continuous-header" class="canva-text px-5 py-4 text-sm font-bold"></th>
         </tr>
        </thead>
        <tbody id="verb-table-body"></tbody>
       </table>
      </div>
     </div>
    </section>
    <section id="cards-panel" class="tab-panel" aria-label="Flashcards">
     <div data-template-id="cards-panel-card" class="canva-card paper-grid rounded-2xl border border-[#d6e1e8] p-5 sm:p-8 shadow-sm">
      <div class="text-center">
       <h2 data-template-id="cards-heading" class="canva-text title-font text-[#173f63]"></h2>
       <p data-template-id="cards-copy" class="canva-text mt-1 text-sm text-[#567085]"></p>
      </div><button id="flashcard" class="flashcard block w-full max-w-2xl mx-auto mt-7 text-center" type="button" aria-label="Reveal flashcard answer">
       <div class="flash-inner">
        <div class="flash-face bg-[#245985] text-white border-4 border-[#173f63] shadow-lg">
         <span data-template-id="flash-front-label" class="canva-text text-xs font-bold uppercase tracking-[0.17em] text-[#dcecf5]"></span> <strong id="flash-present" class="title-font mt-4 text-5xl sm:text-6xl"></strong> <span data-template-id="flash-tap-copy" class="canva-text mt-7 text-sm text-[#fff4cf]"></span>
        </div>
        <div class="flash-face flash-back bg-[#fff8df] text-[#173f63] border-4 border-[#ecd184] shadow-lg">
         <span data-template-id="flash-back-label" class="canva-text text-xs font-bold uppercase tracking-[0.17em] text-[#7a6332]"></span>
         <div class="grid grid-cols-3 gap-4 w-full mt-6">
          <div>
           <p data-template-id="flash-past-label" class="canva-text text-xs font-bold uppercase text-[#587084]"></p><strong id="flash-past" class="block mt-1 text-xl"></strong>
          </div>
          <div>
           <p data-template-id="flash-participle-label" class="canva-text text-xs font-bold uppercase text-[#587084]"></p><strong id="flash-participle" class="block mt-1 text-xl"></strong>
          </div>
          <div>
           <p data-template-id="flash-ing-label" class="canva-text text-xs font-bold uppercase text-[#587084]"></p><strong id="flash-ing" class="block mt-1 text-xl"></strong>
          </div>
         </div>
        </div>
       </div></button>
      <div class="flex items-center justify-center gap-4 mt-6">
       <button data-template-id="previous-card-button" class="canva-button inline-flex items-center gap-2 rounded-lg bg-[#e6eef3] px-4 py-3 font-bold text-[#173f63] hover:bg-[#d6e1e8]" type="button" id="previous-card"><i data-lucide="arrow-left" width="18" height="18" aria-hidden="true"></i><span data-template-id="previous-card-label"></span></button>
       <p id="card-count" class="text-sm font-bold text-[#567085]" aria-live="polite"></p><button data-template-id="next-card-button" class="canva-button inline-flex items-center gap-2 rounded-lg bg-[#245985] px-4 py-3 font-bold text-white hover:bg-[#173f63]" type="button" id="next-card"><span data-template-id="next-card-label"></span><i data-lucide="arrow-right" width="18" height="18" aria-hidden="true"></i></button>
      </div>
     </div>
    </section>
    <section id="quiz-panel" class="tab-panel" aria-label="Quick practice">
     <div data-template-id="quiz-panel-card" class="canva-card paper-grid rounded-2xl border border-[#d6e1e8] p-5 sm:p-8 shadow-sm">
      <div class="text-center">
       <h2 data-template-id="quiz-heading" class="canva-text title-font text-[#173f63]"></h2>
       <p data-template-id="quiz-copy" class="canva-text mt-1 text-sm text-[#567085]"></p>
      </div>
      <div class="max-w-2xl mx-auto mt-7">
       <div class="rounded-xl bg-[#173f63] text-white px-6 py-7 text-center shadow-md">
        <p id="quiz-prompt-type" class="text-xs font-bold uppercase tracking-[0.16em] text-[#dcecf5]"></p>
        <p id="quiz-question" class="title-font mt-3 text-3xl sm:text-4xl" aria-live="polite"></p>
       </div>
       <form id="typing-form" class="mt-5" novalidate><label data-template-id="typing-answer-label" class="canva-text block text-sm font-bold text-[#173f63]" for="typing-answer"></label> <input id="typing-answer" data-template-id="typing-answer-input" class="canva-input mt-2 w-full rounded-xl border-2 border-[#d6e1e8] bg-white px-5 py-4 text-lg text-[#173f63] outline-none focus:border-[#245985]" type="text" autocomplete="off" spellcheck="false"> <button data-template-id="check-answer-button" class="canva-button mt-3 w-full rounded-xl bg-[#245985] px-5 py-4 font-bold text-white hover:bg-[#173f63]" type="submit"></button>
       </form>
       <div id="quiz-feedback" class="min-h-7 mt-5 text-center font-bold" aria-live="polite"></div>
       <div class="text-center mt-3">
        <button data-template-id="next-question-button" class="canva-button hidden rounded-lg bg-[#f4bb45] px-5 py-3 font-bold text-[#173f63] hover:bg-[#e8a92d]" id="next-question" type="button"></button>
       </div>
      </div>
     </div>
    </section>
    <p id="status-message" class="mt-5 text-center text-sm font-medium text-[#567085]" aria-live="polite"></p>
   </main>
   <footer class="w-full px-5 py-6 text-center text-sm text-[#567085]">
    <p data-template-id="footer-note" class="canva-text"></p>
   </footer>
  </div>
  <script src="/_sdk/d3b1f5fdf3d3ed7d.editing_sdk.js" integrity="sha512-1kN2li6Bi1y+hyASeQrjX3T1ejbJuofO7QFHYwSxVmnYpAQy3WUUNCT5CEfq3aK+7Vbwgt8v89WSm0fddrQpfw=="></script>
  <script>
    const verbs = [
      { verb: "accept", past: "accepted", participle: "accepted", ing: "accepting" },
      { verb: "act", past: "acted", participle: "acted", ing: "acting" },
      { verb: "add", past: "added", participle: "added", ing: "adding" },
      { verb: "afford", past: "afforded", participle: "afforded", ing: "affording" },
      { verb: "agree", past: "agreed", participle: "agreed", ing: "agreeing" },
      { verb: "allow", past: "allowed", participle: "allowed", ing: "allowing" },
      { verb: "answer", past: "answered", participle: "answered", ing: "answering" },
      { verb: "appear", past: "appeared", participle: "appeared", ing: "appearing" },
      { verb: "arrive", past: "arrived", participle: "arrived", ing: "arriving" },
      { verb: "ask", past: "asked", participle: "asked", ing: "asking" },
      { verb: "bake", past: "baked", participle: "baked", ing: "baking" },
      { verb: "bang", past: "banged", participle: "banged", ing: "banging" },
      { verb: "bark", past: "barked", participle: "barked", ing: "barking" },
      { verb: "bathe", past: "bathed", participle: "bathed", ing: "bathing" },
      { verb: "be (is, am, are)", past: "was, were", participle: "been", ing: "being" },
      { verb: "bear", past: "bore", participle: "borne, born", ing: "bearing" },
      { verb: "beat", past: "beat", participle: "beaten", ing: "beating" },
      { verb: "become", past: "became", participle: "become", ing: "becoming" },
      { verb: "beg", past: "begged", participle: "begged", ing: "begging" },
      { verb: "begin", past: "began", participle: "begun", ing: "beginning" },
      { verb: "behave", past: "behaved", participle: "behaved", ing: "behaving" },
      { verb: "believe", past: "believed", participle: "believed", ing: "believing" },
      { verb: "belong", past: "belonged", participle: "belonged", ing: "belonging" },
      { verb: "bend", past: "bent", participle: "bent", ing: "bending" },
      { verb: "bite", past: "bit", participle: "bitten, bit", ing: "biting" },
      { verb: "bleed", past: "bled", participle: "bled", ing: "bleeding" },
      { verb: "block", past: "blocked", participle: "blocked", ing: "blocking" },
      { verb: "blow", past: "blew", participle: "blown", ing: "blowing" },
      { verb: "boil", past: "boiled", participle: "boiled", ing: "boiling" },
      { verb: "borrow", past: "borrowed", participle: "borrowed", ing: "borrowing" },
      { verb: "break", past: "broke", participle: "broken", ing: "breaking" },
      { verb: "breathe", past: "breathed", participle: "breathed", ing: "breathing" },
      { verb: "bring", past: "brought", participle: "brought", ing: "bringing" },
      { verb: "brush", past: "brushed", participle: "brushed", ing: "brushing" },
      { verb: "build", past: "built", participle: "built", ing: "building" },
      { verb: "burn", past: "burnt, burned", participle: "burnt, burned", ing: "burning" },
      { verb: "burst", past: "burst", participle: "burst", ing: "bursting" },
      { verb: "bury", past: "buried", participle: "buried", ing: "burying" },
      { verb: "buy", past: "bought", participle: "bought", ing: "buying" },
      { verb: "call", past: "called", participle: "called", ing: "calling" },
      { verb: "care", past: "cared", participle: "cared", ing: "caring" },
      { verb: "carry", past: "carried", participle: "carried", ing: "carrying" },
      { verb: "cast", past: "cast", participle: "cast", ing: "casting" },
      { verb: "catch", past: "caught", participle: "caught", ing: "catching" },
      { verb: "celebrate", past: "celebrated", participle: "celebrated", ing: "celebrating" },
      { verb: "change", past: "changed", participle: "changed", ing: "changing" },
      { verb: "check", past: "checked", participle: "checked", ing: "checking" },
      { verb: "choose", past: "chose", participle: "chosen", ing: "choosing" },
      { verb: "chop", past: "chopped", participle: "chopped", ing: "chopping" },
      { verb: "circle", past: "circled", participle: "circled", ing: "circling" },
      { verb: "clap", past: "clapped", participle: "clapped", ing: "clapping" },
      { verb: "clean", past: "cleaned", participle: "cleaned", ing: "cleaning" },
      { verb: "clear", past: "cleared", participle: "cleared", ing: "clearing" },
      { verb: "climb", past: "climbed", participle: "climbed", ing: "climbing" },
      { verb: "close", past: "closed", participle: "closed", ing: "closing" },
      { verb: "collect", past: "collected", participle: "collected", ing: "collecting" },
      { verb: "come", past: "came", participle: "come", ing: "coming" },
      { verb: "commit", past: "committed", participle: "committed", ing: "committing" },
      { verb: "complain", past: "complained", participle: "complained", ing: "complaining" },
      { verb: "complete", past: "completed", participle: "completed", ing: "completing" },
      { verb: "continue", past: "continued", participle: "continued", ing: "continuing" },
      { verb: "cook", past: "cooked", participle: "cooked", ing: "cooking" },
      { verb: "cool", past: "cooled", participle: "cooled", ing: "cooling" },
      { verb: "copy", past: "copied", participle: "copied", ing: "copying" },
      { verb: "correct", past: "corrected", participle: "corrected", ing: "correcting" },
      { verb: "cost", past: "cost", participle: "cost", ing: "costing" }
    ];

    let progressRecords = [];
    let cardIndex = 0;
    let activeQuestion = null;
    let sdkReady = false;

    const statusMessage = document.getElementById("status-message");

    function setStatus(message, tone = "normal") {
      statusMessage.textContent = message;
      statusMessage.className = "mt-5 text-center text-sm font-medium " + (tone === "error" ? "text-[#b5443d]" : tone === "success" ? "text-[#18735d]" : "text-[#567085]");
    }

    function renderTable() {
      const table = document.getElementById("verb-table-body");
      verbs.forEach((item, index) => {
        const row = document.createElement("tr");
        row.className = "verb-row border-b border-[#e2e9ed] last:border-0";
        row.innerHTML = `
          <td class="px-5 py-3.5 font-bold text-[#245985]">${index + 1}</td>
          <td class="px-5 py-3.5 font-semibold">${item.verb}</td>
          <td class="px-5 py-3.5">${item.past}</td>
          <td class="px-5 py-3.5">${item.participle}</td>
          <td class="px-5 py-3.5">${item.ing}</td>`;
        table.appendChild(row);
      });
    }

    function renderCard() {
      const item = verbs[cardIndex];
      const card = document.getElementById("flashcard");
      card.classList.remove("is-revealed");
      card.setAttribute("aria-label", "Reveal answer for " + item.verb);
      document.getElementById("flash-present").textContent = item.verb;
      document.getElementById("flash-past").textContent = item.past;
      document.getElementById("flash-participle").textContent = item.participle;
      document.getElementById("flash-ing").textContent = item.ing;
      document.getElementById("card-count").textContent = (cardIndex + 1) + " / " + verbs.length;
    }

    function updateProgress(data) {
      progressRecords = data;
      const total = data.reduce((sum, item) => sum + (Number(item.total_questions) || 0), 0);
      const correct = data.reduce((sum, item) => sum + (Number(item.correct_answers) || 0), 0);
      const accuracy = total ? Math.round((correct / total) * 100) : 0;
      document.getElementById("accuracy-value").textContent = total ? accuracy + "%" : "—";
      document.getElementById("progress-bar").style.width = total ? accuracy + "%" : "0%";
    }

    function makeQuestion() {
      const item = verbs[Math.floor(Math.random() * verbs.length)];
      const forms = [
        { key: "past", name: "Past tense" },
        { key: "participle", name: "Past participle" },
        { key: "ing", name: "Present participle" }
      ];
      const form = forms[Math.floor(Math.random() * forms.length)];
      const correctAnswer = item[form.key];
      const wrongs = [...new Set(verbs.map(v => v[form.key]).filter(value => value !== correctAnswer))]
        .sort(() => Math.random() - 0.5).slice(0, 3);
      const options = [correctAnswer, ...wrongs].sort(() => Math.random() - 0.5);

      activeQuestion = { item, form, correctAnswer, answered: false };
      document.getElementById("quiz-prompt-type").textContent = form.name;
      document.getElementById("quiz-question").textContent = "What is the " + form.name.toLowerCase() + " of “" + item.verb + "”?";
      document.getElementById("quiz-feedback").textContent = "";
      document.getElementById("next-question").classList.add("hidden");
      const answerInput = document.getElementById("typing-answer");
      answerInput.value = "";
      answerInput.disabled = false;
      document.querySelector("#typing-form button[type=submit]").disabled = false;
      setTimeout(() => answerInput.focus(), 0);
    }

    async function answerQuestion(answer) {
      if (!activeQuestion || activeQuestion.answered) return;
      activeQuestion.answered = true;
      const isCorrect = answer.trim().toLowerCase() === activeQuestion.correctAnswer.toLowerCase();
      document.getElementById("typing-answer").disabled = true;
      document.querySelector("#typing-form button[type=submit]").disabled = true;

      const feedback = document.getElementById("quiz-feedback");
      feedback.textContent = isCorrect ? "Excellent — that is correct!" : "Not quite. The correct answer is “" + activeQuestion.correctAnswer + "”.";
      feedback.className = "min-h-7 mt-5 text-center font-bold " + (isCorrect ? "text-[#18735d]" : "text-[#b5443d]");
      document.getElementById("next-question").classList.remove("hidden");

      await saveAttempt(activeQuestion.item.verb, isCorrect);
    }

    async function saveAttempt(verb, isCorrect) {
      if (!sdkReady) {
        setStatus("Your answer is ready, but study progress could not be saved.", "error");
        return;
      }
      const current = progressRecords.find(record => record.verb === verb);
      if (!current) {
        setStatus("Study progress is loading. Please try the next question.", "normal");
        return;
      }
      setStatus("Saving your practice result…");
      const updated = {
        ...current,
        correct_answers: Number(current.correct_answers || 0) + (isCorrect ? 1 : 0),
        total_questions: Number(current.total_questions || 0) + 1,
        last_studied: new Date().toISOString()
      };
      const result = await window.dataSdk.update(updated);
      if (result.isOk) {
        setStatus("Practice result saved.", "success");
      } else {
        setStatus("Your answer was checked, but it could not be saved. Please try another question.", "error");
      }
    }

    async function initialiseSheet() {
      const handler = {
        onDataChanged(data) {
          updateProgress(data);
          if (data.length) setStatus("");
        }
      };
      const result = await window.dataSdk.init(handler);
      if (result.isOk) {
        sdkReady = true;
      } else {
        setStatus("Study progress is unavailable at the moment.", "error");
      }
    }

    document.querySelectorAll("[data-tab]").forEach(button => {
      button.addEventListener("click", () => {
        document.querySelectorAll("[data-tab]").forEach(tab => {
          tab.classList.toggle("active", tab === button);
          tab.setAttribute("aria-selected", String(tab === button));
        });
        document.querySelectorAll(".tab-panel").forEach(panel => panel.classList.remove("active"));
        document.getElementById(button.dataset.tab + "-panel").classList.add("active");
      });
    });

    document.getElementById("flashcard").addEventListener("click", () => {
      document.getElementById("flashcard").classList.toggle("is-revealed");
    });
    document.getElementById("previous-card").addEventListener("click", () => {
      cardIndex = (cardIndex - 1 + verbs.length) % verbs.length;
      renderCard();
    });
    document.getElementById("next-card").addEventListener("click", () => {
      cardIndex = (cardIndex + 1) % verbs.length;
      renderCard();
    });
    document.getElementById("typing-form").addEventListener("submit", event => {
      event.preventDefault();
      answerQuestion(document.getElementById("typing-answer").value);
    });
    document.getElementById("next-question").addEventListener("click", makeQuestion);

    document.addEventListener("DOMContentLoaded", () => {
      renderTable();
      renderCard();
      makeQuestion();
      lucide.createIcons();
      initialiseSheet();
    });
  </script>
 </body>
</html>
