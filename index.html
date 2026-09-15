<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Verb Study Practice</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.577.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Fraunces:opsz,wght@9..144,700&display=swap" rel="stylesheet">
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
    .study-shell { width: 100%; min-height: 100vh; background: #f5f1e8; }
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
    @keyframes rise { from { opacity: 0; transform: translateY(7px); } to { opacity: 1; transform: translateY(0); } }
    button:focus-visible { outline: 3px solid var(--gold); outline-offset: 3px; }
    .verb-row:nth-child(even) { background: rgba(237,243,247,.72); }
  </style>
 </head>
 <body>
  <div class="study-shell">
   <header class="bg-[#245985] text-white border-b-4 border-[#f4bb45]">
    <div class="w-full max-w-6xl mx-auto px-5 py-7 sm:px-8">
     <div class="flex flex-col gap-3 sm:flex-row sm:items-end sm:justify-between">
      <div>
       <p class="text-sm font-semibold tracking-[0.13em] uppercase text-[#dcecf5]">English Grammar</p>
       <h1 class="title-font mt-1 text-3xl leading-tight">Verb Study Practice</h1>
      </div>
     </div>
    </div>
   </header>
   <main class="w-full max-w-6xl mx-auto px-5 py-7 sm:px-8 sm:py-10">
    <nav aria-label="Study sections" class="mb-6">
     <div class="grid grid-cols-3 rounded-xl overflow-hidden border border-[#d6e1e8] bg-white shadow-sm">
      <button class="tab-button active px-3 py-4 text-sm font-bold text-[#416078]" type="button" data-tab="table">Verb List</button> 
      <button class="tab-button px-3 py-4 text-sm font-bold text-[#416078]" type="button" data-tab="cards">Flashcards</button> 
      <button class="tab-button px-3 py-4 text-sm font-bold text-[#416078]" type="button" data-tab="quiz">Practice</button>
     </div>
    </nav>
    <section id="table-panel" class="tab-panel active">
     <div class="paper-grid rounded-2xl border border-[#d6e1e8] overflow-hidden shadow-sm">
      <div class="p-5 sm:p-7 border-b border-[#d6e1e8] bg-white/85">
       <h2 class="title-font text-2xl text-[#173f63]">Master Verb List</h2>
      </div>
      <div class="overflow-x-auto">
       <table class="w-full min-w-[680px] text-left">
        <thead class="bg-[#245985] text-white">
         <tr>
          <th class="px-5 py-4 text-sm font-bold">#</th>
          <th class="px-5 py-4 text-sm font-bold">Base Form</th>
          <th class="px-5 py-4 text-sm font-bold">Past Tense</th>
          <th class="px-5 py-4 text-sm font-bold">Past Participle</th>
          <th class="px-5 py-4 text-sm font-bold">Present Participle</th>
         </tr>
        </thead>
        <tbody id="verb-table-body"></tbody>
       </table>
      </div>
     </div>
    </section>
    <section id="cards-panel" class="tab-panel">
     <div class="paper-grid rounded-2xl border border-[#d6e1e8] p-5 sm:p-8 shadow-sm">
      <button id="flashcard" class="flashcard block w-full max-w-2xl mx-auto mt-7 text-center" type="button">
       <div class="flash-inner">
        <div class="flash-face bg-[#245985] text-white border-4 border-[#173f63] shadow-lg">
         <span class="text-xs font-bold uppercase tracking-[0.17em] text-[#dcecf5]">Base Form</span> 
         <strong id="flash-present" class="title-font mt-4 text-5xl sm:text-6xl"></strong> 
         <span class="mt-7 text-sm text-[#fff4cf]">Tap to reveal</span>
        </div>
        <div class="flash-face flash-back bg-[#fff8df] text-[#173f63] border-4 border-[#ecd184] shadow-lg">
         <div class="grid grid-cols-3 gap-4 w-full mt-6">
          <div><p class="text-xs font-bold uppercase text-[#587084]">Past</p><strong id="flash-past" class="block mt-1 text-xl"></strong></div>
          <div><p class="text-xs font-bold uppercase text-[#587084]">Participle</p><strong id="flash-participle" class="block mt-1 text-xl"></strong></div>
          <div><p class="text-xs font-bold uppercase text-[#587084]">Continuous</p><strong id="flash-ing" class="block mt-1 text-xl"></strong></div>
         </div>
        </div>
       </div>
      </button>
      <div class="flex items-center justify-center gap-4 mt-6">
       <button class="inline-flex items-center gap-2 rounded-lg bg-[#e6eef3] px-4 py-3 font-bold text-[#173f63] hover:bg-[#d6e1e8]" id="previous-card"><i data-lucide="arrow-left" width="18" height="18"></i> Previous</button>
       <p id="card-count" class="text-sm font-bold text-[#567085]"></p>
       <button class="inline-flex items-center gap-2 rounded-lg bg-[#245985] px-4 py-3 font-bold text-white hover:bg-[#173f63]" id="next-card">Next <i data-lucide="arrow-right" width="18" height="18"></i></button>
      </div>
     </div>
    </section>
    <section id="quiz-panel" class="tab-panel">
     <div class="paper-grid rounded-2xl border border-[#d6e1e8] p-5 sm:p-8 shadow-sm">
      <div class="max-w-2xl mx-auto mt-7">
       <div class="rounded-xl bg-[#173f63] text-white px-6 py-7 text-center shadow-md">
        <p id="quiz-prompt-type" class="text-xs font-bold uppercase tracking-[0.16em] text-[#dcecf5]"></p>
        <p id="quiz-question" class="title-font mt-3 text-3xl sm:text-4xl"></p>
       </div>
       <form id="typing-form" class="mt-5">
        <input id="typing-answer" class="mt-2 w-full rounded-xl border-2 border-[#d6e1e8] bg-white px-5 py-4 text-lg text-[#173f63] outline-none focus:border-[#245985]" type="text" autocomplete="off" spellcheck="false" placeholder="Type your answer here..."> 
        <button class="mt-3 w-full rounded-xl bg-[#245985] px-5 py-4 font-bold text-white hover:bg-[#173f63]" type="submit">Check Answer</button>
       </form>
       <div id="quiz-feedback" class="min-h-7 mt-5 text-center font-bold"></div>
       <div class="text-center mt-3">
        <button class="hidden rounded-lg bg-[#f4bb45] px-5 py-3 font-bold text-[#173f63] hover:bg-[#e8a92d]" id="next-question" type="button">Next Question</button>
       </div>
      </div>
     </div>
    </section>
   </main>
  </div>
  <script>
    /* I removed the local backend SDK script tags from your previous setup so this code can run smoothly on GitHub Pages without console errors! */
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

    let cardIndex = 0;
    let activeQuestion = null;

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
      document.getElementById("flash-present").textContent = item.verb;
      document.getElementById("flash-past").textContent = item.past;
      document.getElementById("flash-participle").textContent = item.participle;
      document.getElementById("flash-ing").textContent = item.ing;
      document.getElementById("card-count").textContent = (cardIndex + 1) + " / " + verbs.length;
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

    function answerQuestion(answer) {
      if (!activeQuestion || activeQuestion.answered) return;
      activeQuestion.answered = true;
      const isCorrect = answer.trim().toLowerCase() === activeQuestion.correctAnswer.toLowerCase();
      
      document.getElementById("typing-answer").disabled = true;
      document.querySelector("#typing-form button[type=submit]").disabled = true;

      const feedback = document.getElementById("quiz-feedback");
      feedback.textContent = isCorrect ? "Excellent — that is correct!" : "Not quite. The correct answer is “" + activeQuestion.correctAnswer + "”.";
      feedback.className = "min-h-7 mt-5 text-center font-bold " + (isCorrect ? "text-[#18735d]" : "text-[#b5443d]");
      document.getElementById("next-question").classList.remove("hidden");
    }

    document.querySelectorAll("[data-tab]").forEach(button => {
      button.addEventListener("click", () => {
        document.querySelectorAll("[data-tab]").forEach(tab => tab.classList.toggle("active", tab === button));
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
    });
  </script>
 </body>
</html>
