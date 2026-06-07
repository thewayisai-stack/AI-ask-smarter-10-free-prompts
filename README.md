<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mary's 10 Bonus Prompts — Ask Smarter. Get More.</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,600;0,700;1,400;1,600&family=DM+Sans:ital,wght@0,300;0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">

<style>
/* ── Reset & base ─────────────────────────────────────────────── */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --blue:      #2E75B6;
  --blue-light:#D5E8F0;
  --blue-mid:  #4A90D4;
  --gold:      #F0A500;
  --gold-bg:   #FFF8E1;
  --green:     #1B7B3A;
  --green-bg:  #E8F5E9;
  --teal-bg:   #E1F5EE;
  --gray-bg:   #F7F8FA;
  --gray-line: #E2E6EC;
  --text:      #1A1D23;
  --text-mid:  #444C5C;
  --text-soft: #7A8494;
  --chatgpt:   #E8F5E9;
  --gemini:    #E3F2FD;
  --claude:    #F3E5F5;
  --red-soft:  #FDEDED;
  --font-head: 'Lora', Georgia, serif;
  --font-body: 'DM Sans', system-ui, sans-serif;
  --radius:    12px;
  --shadow:    0 2px 16px rgba(46,117,182,0.10);
}

html { scroll-behavior: smooth; }

body {
  font-family: var(--font-body);
  color: var(--text);
  background: #F4F7FB;
  font-size: 16px;
  line-height: 1.7;
}

/* ── Layout ───────────────────────────────────────────────────── */
.page-wrap {
  max-width: 820px;
  margin: 0 auto;
  padding: 0 20px 80px;
}

/* ── Hero ─────────────────────────────────────────────────────── */
.hero {
  background: linear-gradient(135deg, #1A3A5C 0%, #2E75B6 60%, #4A90D4 100%);
  color: #fff;
  text-align: center;
  padding: 64px 32px 56px;
  margin-bottom: 48px;
  border-radius: 0 0 32px 32px;
  position: relative;
  overflow: hidden;
}
.hero::before {
  content: '';
  position: absolute; inset: 0;
  background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.04'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
}
.hero-badge {
  display: inline-block;
  background: rgba(255,255,255,0.18);
  border: 1px solid rgba(255,255,255,0.35);
  border-radius: 20px;
  padding: 5px 18px;
  font-size: 13px;
  font-weight: 500;
  letter-spacing: .06em;
  text-transform: uppercase;
  margin-bottom: 20px;
  backdrop-filter: blur(4px);
}
.hero h1 {
  font-family: var(--font-head);
  font-size: clamp(28px, 5vw, 44px);
  font-weight: 700;
  line-height: 1.2;
  margin-bottom: 16px;
  text-shadow: 0 2px 12px rgba(0,0,0,0.2);
}
.hero h1 span { color: #FFD166; }
.hero p {
  font-size: 17px;
  opacity: .88;
  max-width: 540px;
  margin: 0 auto 28px;
  font-weight: 300;
}
.hero-sub {
  font-size: 13px !important;
  opacity: .65 !important;
  margin-top: 6px !important;
}

/* ── Download button ──────────────────────────────────────────── */
.btn-download {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #FFD166;
  color: #1A1D23;
  font-family: var(--font-body);
  font-weight: 600;
  font-size: 15px;
  padding: 14px 30px;
  border-radius: 50px;
  border: none;
  cursor: pointer;
  text-decoration: none;
  transition: transform .15s, box-shadow .15s;
  box-shadow: 0 4px 20px rgba(240,165,0,0.35);
}
.btn-download:hover { transform: translateY(-2px); box-shadow: 0 6px 28px rgba(240,165,0,0.45); }
.btn-download svg { flex-shrink: 0; }

/* ── Mary intro box ───────────────────────────────────────────── */
.mary-intro {
  background: var(--gold-bg);
  border-left: 4px solid var(--gold);
  border-radius: var(--radius);
  padding: 24px 28px;
  margin-bottom: 40px;
  font-style: italic;
  font-family: var(--font-head);
  font-size: 15.5px;
  color: var(--text-mid);
  line-height: 1.75;
}
.mary-intro strong { font-style: normal; color: var(--text); }
.mary-intro .attribution {
  margin-top: 12px;
  font-size: 13px;
  font-style: normal;
  color: var(--text-soft);
}

/* ── Section heading ──────────────────────────────────────────── */
.section-label {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 11px;
  font-weight: 600;
  letter-spacing: .12em;
  text-transform: uppercase;
  color: var(--blue);
  margin-bottom: 20px;
}
.section-label::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--blue-light);
}

/* ── Prompt cards ─────────────────────────────────────────────── */
.prompt-grid {
  display: grid;
  gap: 20px;
}

.prompt-card {
  background: #fff;
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  overflow: hidden;
  transition: transform .18s, box-shadow .18s;
  border: 1px solid var(--gray-line);
}
.prompt-card:hover { transform: translateY(-3px); box-shadow: 0 6px 28px rgba(46,117,182,0.14); }

.card-header {
  display: flex;
  align-items: flex-start;
  gap: 14px;
  padding: 20px 22px 16px;
  border-bottom: 1px solid var(--gray-line);
}
.card-num {
  width: 36px; height: 36px;
  border-radius: 50%;
  background: var(--blue);
  color: #fff;
  font-family: var(--font-head);
  font-weight: 700;
  font-size: 16px;
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0;
  margin-top: 2px;
}
.card-title-wrap { flex: 1; }
.card-emoji { font-size: 20px; margin-bottom: 4px; display: block; }
.card-title {
  font-family: var(--font-head);
  font-weight: 600;
  font-size: 17px;
  color: var(--text);
  line-height: 1.3;
}
.card-agent {
  display: inline-block;
  margin-top: 6px;
  font-size: 12px;
  font-weight: 500;
  padding: 3px 10px;
  border-radius: 12px;
}
.agent-chatgpt { background: var(--chatgpt); color: #1B7B3A; }
.agent-gemini  { background: var(--gemini);  color: #1558A0; }
.agent-claude  { background: var(--claude);  color: #6A1B9A; }
.agent-any     { background: #F5F5F5;        color: #555; }

.card-body { padding: 18px 22px; }

.mary-story {
  font-size: 14px;
  color: var(--text-mid);
  font-style: italic;
  font-family: var(--font-head);
  margin-bottom: 16px;
  padding-bottom: 16px;
  border-bottom: 1px dashed var(--gray-line);
  line-height: 1.7;
}

.prompt-label {
  font-size: 11px;
  font-weight: 600;
  letter-spacing: .1em;
  text-transform: uppercase;
  color: var(--blue);
  margin-bottom: 8px;
}

.prompt-box {
  background: var(--gray-bg);
  border: 1px solid var(--gray-line);
  border-radius: 8px;
  padding: 14px 16px;
  font-size: 14px;
  line-height: 1.8;
  position: relative;
}
.prompt-box p { margin-bottom: 4px; }
.prompt-box p:last-child { margin-bottom: 0; }
.fill { color: var(--blue); font-weight: 600; }

.copy-btn {
  position: absolute;
  top: 10px; right: 10px;
  background: var(--blue);
  color: #fff;
  border: none;
  border-radius: 6px;
  padding: 4px 10px;
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
  font-family: var(--font-body);
  transition: background .15s, transform .1s;
  letter-spacing: .04em;
}
.copy-btn:hover { background: #1A5A9C; }
.copy-btn.copied { background: var(--green); }

.why-box {
  margin-top: 14px;
  background: var(--blue-light);
  border-radius: 8px;
  padding: 12px 14px;
  font-size: 13.5px;
  color: var(--text-mid);
  line-height: 1.65;
}
.why-box strong { color: var(--blue); }

.mary-quote {
  margin-top: 12px;
  font-size: 13px;
  font-style: italic;
  color: var(--text-soft);
  font-family: var(--font-head);
  padding-left: 14px;
  border-left: 2px solid var(--gold);
}

/* ── Divider ──────────────────────────────────────────────────── */
.divider {
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--blue-light), transparent);
  margin: 8px 0;
}

/* ── Footer ───────────────────────────────────────────────────── */
.footer-cta {
  margin-top: 56px;
  background: linear-gradient(135deg, #1A3A5C, #2E75B6);
  border-radius: 20px;
  padding: 40px 36px;
  text-align: center;
  color: #fff;
}
.footer-cta h2 {
  font-family: var(--font-head);
  font-size: 24px;
  margin-bottom: 12px;
}
.footer-cta p { opacity: .85; font-size: 15px; margin-bottom: 24px; }
.btn-amazon {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #FFD166;
  color: #1A1D23;
  font-weight: 600;
  font-size: 15px;
  padding: 13px 28px;
  border-radius: 50px;
  text-decoration: none;
  transition: transform .15s;
}
.btn-amazon:hover { transform: translateY(-2px); }

.footer-note {
  text-align: center;
  margin-top: 32px;
  font-size: 12px;
  color: var(--text-soft);
}
.footer-note a { color: var(--blue); text-decoration: none; }

/* ── Print styles ─────────────────────────────────────────────── */
@media print {
  body { background: #fff; font-size: 12px; }
  .page-wrap { max-width: 100%; padding: 0 24px; }
  .hero { border-radius: 0; padding: 32px 24px; margin-bottom: 28px; print-color-adjust: exact; -webkit-print-color-adjust: exact; }
  .hero h1 { font-size: 28px; }
  .no-print { display: none !important; }
  .prompt-card { break-inside: avoid; box-shadow: none; border: 1px solid #ddd; margin-bottom: 16px; }
  .footer-cta { print-color-adjust: exact; -webkit-print-color-adjust: exact; }
  .copy-btn { display: none; }
}

/* ── Animations ───────────────────────────────────────────────── */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(20px); }
  to   { opacity: 1; transform: translateY(0); }
}
.prompt-card {
  animation: fadeUp .4s ease both;
}
.prompt-card:nth-child(1)  { animation-delay: .05s }
.prompt-card:nth-child(2)  { animation-delay: .10s }
.prompt-card:nth-child(3)  { animation-delay: .15s }
.prompt-card:nth-child(4)  { animation-delay: .20s }
.prompt-card:nth-child(5)  { animation-delay: .25s }
.prompt-card:nth-child(6)  { animation-delay: .30s }
.prompt-card:nth-child(7)  { animation-delay: .35s }
.prompt-card:nth-child(8)  { animation-delay: .40s }
.prompt-card:nth-child(9)  { animation-delay: .45s }
.prompt-card:nth-child(10) { animation-delay: .50s }
</style>
</head>
<body>

<!-- ── HERO ──────────────────────────────────────────────────────── -->
<header class="hero">
  <div class="hero-badge">Free Bonus · Ask Smarter. Get More.</div>
  <h1>Mary's <span>10 Bonus Prompts</span></h1>
  <p>Ten more ready-to-copy prompts that didn't fit in the book.<br>No email. No sign-up. Just the prompts.</p>
  <p class="hero-sub">From the book <em>Ask Smarter. Get More.</em> — the AI guide for people born before 2000.</p>
  <br>
  <button class="btn-download no-print" onclick="window.print()">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><polyline points="8 17 12 21 16 17"/><line x1="12" y1="12" x2="12" y2="21"/><path d="M20.88 18.09A5 5 0 0 0 18 9h-1.26A8 8 0 1 0 3 16.29"/></svg>
    Save as PDF
  </button>
</header>

<div class="page-wrap">

  <!-- Mary intro -->
  <div class="mary-intro">
    <strong>👩 A note from Mary:</strong><br>
    "The ten prompts in Chapter 11 are the ones I use every week. These ten are the ones I use when things get complicated — when the conversation is uncomfortable, when the fridge is empty, when I can't find the right words for something that matters. They're not harder. They're just for the other days."
    <div class="attribution">— Mary Richard, Accountant, Fremont Accounting Service Ltd., Fremont, CA</div>
  </div>

  <div class="section-label">10 Bonus Prompts — Ready to Copy</div>

  <div class="prompt-grid">

    <!-- PROMPT 1 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">1</div>
        <div class="card-title-wrap">
          <span class="card-emoji">💬</span>
          <div class="card-title">Planning a Hard Conversation with a Family Member</div>
          <span class="card-agent agent-claude">Best with: Claude</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Mary's brother hadn't spoken to their mother in two years. She needed to say something. She didn't know how to start. She typed for ninety seconds. <em>The conversation happened on Sunday. It went well.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are an experienced family mediator and communication coach.</p>
          <p>I need to have a conversation with <span class="fill">[relationship: my brother / my adult child / my parent]</span> about <span class="fill">[topic]</span>.</p>
          <p>The situation: <span class="fill">[2-3 sentences describing what happened and why it matters]</span>.</p>
          <p>My goal is not to win — it's to <span class="fill">[be heard / repair the relationship / set a boundary / ask for help]</span>.</p>
          <p>Write me an opening statement of 3-4 sentences. Calm, honest, not accusatory.</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> "Not accusatory" does more work than it looks like. It shifts the entire tone away from defensiveness before the conversation begins. This prompt doesn't replace the courage the conversation requires — but it helps you arrive with the right words.</div>
        <div class="mary-quote">"My brother said: 'I didn't expect you to say it like that.' I said: 'I had some help.' He assumed therapy. I didn't correct him." 😄</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 2 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">2</div>
        <div class="card-title-wrap">
          <span class="card-emoji">💼</span>
          <div class="card-title">Writing Your LinkedIn Summary — Without Sounding Like a Robot</div>
          <span class="card-agent agent-chatgpt">Best with: ChatGPT</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Mary's LinkedIn summary said: <em>"Experienced accounting professional with 20 years in the field."</em> ChatGPT read it and diplomatically said it could be stronger. <em>The new version got her three recruiter messages in two weeks.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are an experienced LinkedIn profile writer who specializes in mid-career professionals.</p>
          <p>Write a LinkedIn "About" section for me. Here are the facts:</p>
          <p>— Role: <span class="fill">[your job title and field]</span></p>
          <p>— Years of experience: <span class="fill">[number]</span></p>
          <p>— What I'm actually good at: <span class="fill">[2-3 specific things]</span></p>
          <p>— What I'm looking for: <span class="fill">[new role / clients / connections / nothing specific]</span></p>
          <p>Tone: warm, specific, first person. Sound like a real person, not a job posting. Maximum 5 sentences.</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> "Sound like a real person, not a job posting" is the instruction that changes everything. LinkedIn is full of people describing themselves in the third person with words like "passionate" and "results-driven." First person, specific facts, human tone stands out immediately.</div>
        <div class="mary-quote">"The recruiter said my profile was 'refreshingly direct.' I have never been called refreshingly direct in my life. I am keeping this." 😄</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 3 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">3</div>
        <div class="card-title-wrap">
          <span class="card-emoji">📄</span>
          <div class="card-title">Understand a Confusing Insurance or Legal Document</div>
          <span class="card-agent agent-claude">Best with: Claude</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Twelve pages. New health insurance renewal. Mary needed to know if her plan had changed before a 4 PM deadline. <em>She had the answer in eleven minutes.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are a patient advisor helping a non-specialist understand a complex document.</p>
          <p>I am <span class="fill">[brief description: a homeowner / an employee / a patient]</span> with no legal or insurance background.</p>
          <p>Read the text below and tell me:</p>
          <p>1. What is this document actually saying in plain words?</p>
          <p>2. What are the 3 most important things I need to know?</p>
          <p>3. Is there anything unusual, risky, or that I should ask a professional about?</p>
          <p>Format: numbered list, plain language, no jargon. If you use a technical term, define it immediately.</p>
          <p>---<br><span class="fill">[Paste document text here]</span></p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> Question 3 — "Is there anything unusual or risky?" — is the one most people forget to ask. It turns Claude from a summarizer into a first-pass reviewer. Always verify important details with the relevant professional. This prompt saves you time and helps you ask the right questions.</div>
        <div class="mary-quote">"The document had an auto-renewal clause on page 9 that Claude flagged. I called and canceled it. Saved $340." 😊</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 4 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">4</div>
        <div class="card-title-wrap">
          <span class="card-emoji">🥗</span>
          <div class="card-title">Dinner When the Fridge Is Almost Empty</div>
          <span class="card-agent agent-chatgpt">Best with: ChatGPT</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Tuesday, 6:15 PM. Half an onion, some eggs, leftover rice, a can of something. Dave asked what was for dinner. <em>Mary had an answer in forty seconds.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are a practical home cook who specializes in turning random ingredients into real meals.</p>
          <p>I have exactly these ingredients available: <span class="fill">[list everything in your fridge and pantry]</span>.</p>
          <p>Dietary needs or restrictions: <span class="fill">[none / vegetarian / low-carb / etc.]</span></p>
          <p>I have <span class="fill">[20 / 30 / 45]</span> minutes and <span class="fill">[beginner / intermediate]</span> cooking skills.</p>
          <p>Give me 2 options: one simple, one more interesting. For each: name, ingredients used, and steps in plain language.</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> Listing what you actually have — rather than asking for "a recipe with chicken" — prevents ChatGPT from suggesting things you'd need to buy. "One simple, one more interesting" gives you a real choice based on how much energy you have at 6 PM on a Tuesday.</div>
        <div class="mary-quote">"Dave said: 'This is really good. What is it?' I said: 'Improvised fried rice.' He said: 'You should improvise more often.' I agreed." 😄</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 5 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">5</div>
        <div class="card-title-wrap">
          <span class="card-emoji">👔</span>
          <div class="card-title">Prepare for a Job Interview After 45</div>
          <span class="card-agent agent-chatgpt">Best with: ChatGPT</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Her colleague Linda had been out of interviews for eleven years. The call came on a Wednesday. The interview was Friday. <em>Mary sent her this prompt Thursday morning. Linda got the job.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are an experienced career coach who specializes in mid-career professionals re-entering the job market.</p>
          <p>I am interviewing for: <span class="fill">[job title]</span> at <span class="fill">[type of company: a law firm / a hospital / a tech startup]</span>.</p>
          <p>My background: <span class="fill">[2-3 sentences about your experience]</span>.</p>
          <p>My concern: I've been in the same role for <span class="fill">[X]</span> years and I'm not sure how to present this positively.</p>
          <p>Give me: 5 likely interview questions for this role, a 60-second "tell me about yourself" answer, and one way to address my concern directly if asked.</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> Naming the concern directly — "I've been in the same role for X years" — lets ChatGPT help you reframe it rather than avoid it. Interviewers will ask. Having a prepared, honest answer is far better than a deflection.</div>
        <div class="mary-quote">"Linda called me after. 'They asked exactly one of those five questions.' I said: 'Which one?' She said: 'All of them.' 😄"</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 6 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">6</div>
        <div class="card-title-wrap">
          <span class="card-emoji">🥂</span>
          <div class="card-title">Write a Heartfelt Toast or Speech in Under 10 Minutes</div>
          <span class="card-agent agent-claude">Best with: Claude</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Her niece's wedding. Mary was asked to say something — three days before the event. She hadn't given a speech since her college graduation. <em>She wrote one that made three people cry. In a good way.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are a speechwriter who specializes in personal, warm, and memorable toasts for real occasions.</p>
          <p>Occasion: <span class="fill">[wedding / retirement / birthday / graduation]</span></p>
          <p>I am the <span class="fill">[relationship: aunt / colleague / oldest friend / parent]</span>.</p>
          <p>About this person: <span class="fill">[3-4 sentences: a specific memory, a quality you admire, something funny or touching]</span>.</p>
          <p>Tone: <span class="fill">[warm and funny / purely heartfelt / brief and sincere]</span>. Maximum 90 seconds when read aloud (about 200 words).</p>
          <p>Do not use clichés like "words cannot express" or "since the day you were born."</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> "Do not use clichés" sounds obvious, but without this instruction, AI defaults to exactly those phrases. The specific memory you provide in the context is what makes the speech genuinely personal — Claude builds around it, not around a template.</div>
        <div class="mary-quote">"My niece asked me afterward if I'd had help writing it. I said yes. She asked who. I said 'a very good listener.' That's technically accurate." 😄</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 7 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">7</div>
        <div class="card-title-wrap">
          <span class="card-emoji">🛒</span>
          <div class="card-title">A Second Opinion on a Purchase Decision</div>
          <span class="card-agent agent-chatgpt">Best with: ChatGPT or Gemini</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">A $1,200 laptop. Three options. All confusing. The salesperson was helpful but also trying to sell something. <em>Mary spent twelve minutes with ChatGPT before going back to the store. She knew exactly what she wanted.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are an honest, unbiased consumer advisor. You have no interest in selling me anything.</p>
          <p>I am considering buying: <span class="fill">[product name or description]</span>.</p>
          <p>My options are: <span class="fill">[list 2-3 options with prices if you have them]</span>.</p>
          <p>I will use it mainly for: <span class="fill">[what you actually do with it]</span>.</p>
          <p>I am not a tech expert. Budget: <span class="fill">$[amount]</span>.</p>
          <p>Tell me: which option fits my needs, what I'm paying extra for if I go higher, and what I'd be giving up if I go lower. One recommendation at the end.</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> "You have no interest in selling me anything" resets the frame. The request for what you're gaining and losing at each price point is what salespeople rarely tell you clearly — and what actually helps you decide.</div>
        <div class="mary-quote">"The salesperson said: 'You've really done your research.' I had. It took twelve minutes." 😄</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 8 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">8</div>
        <div class="card-title-wrap">
          <span class="card-emoji">💰</span>
          <div class="card-title">Understand a Bill, Invoice, or Financial Statement</div>
          <span class="card-agent agent-claude">Best with: Claude</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">The hospital bill arrived six weeks after the procedure. Four pages. Codes, adjustments, balances due. It said she owed $847. Her insurance said she owed $340. <em>Claude helped her figure out who was right. (It was the insurance.)</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are a patient financial advisor helping a non-specialist understand a confusing bill or statement.</p>
          <p>This is a <span class="fill">[hospital bill / utility bill / investment statement / credit card statement]</span>.</p>
          <p>I don't understand: <span class="fill">[specific thing: why the total is different from what I expected / what these codes mean / why there are two different amounts]</span>.</p>
          <p>Explain what each section means in plain language. Tell me what I actually owe and what to do next if something looks wrong.</p>
          <p>---<br><span class="fill">[Paste the bill text here]</span></p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> Naming the specific confusion — "why there are two different amounts" — focuses Claude immediately. This prompt is especially useful for medical bills, which are notoriously opaque. Always call the billing department if you find a discrepancy. Most errors are correctable.</div>
        <div class="mary-quote">"I called the hospital. They corrected it. The person on the phone said errors 'happen sometimes.' I said: 'I know. That's why I check.'" 😊</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 9 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">9</div>
        <div class="card-title-wrap">
          <span class="card-emoji">✈️</span>
          <div class="card-title">A Complete Packing List for Any Trip in 60 Seconds</div>
          <span class="card-agent agent-gemini">Best with: Gemini</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Three days in Chicago. January. Business meetings Monday, dinner Tuesday, free day Wednesday. Mary had packed in thirty minutes for the first time in twenty years. <em>She forgot nothing. Including the umbrella.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are a seasoned travel assistant who never forgets anything.</p>
          <p>I am traveling to <span class="fill">[destination]</span> for <span class="fill">[number]</span> days in <span class="fill">[month / season]</span>.</p>
          <p>The trip involves: <span class="fill">[business meetings / outdoor activities / a formal dinner / beach / sightseeing]</span>.</p>
          <p>I am: <span class="fill">[woman / man]</span>, traveling <span class="fill">[alone / with a partner / with kids]</span>.</p>
          <p>I take carry-on only. Give me a complete packing list organized by category (clothing, toiletries, documents, tech, other). Flag anything weather-specific for this destination in this season.</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> "Flag anything weather-specific" is the detail that prevents you from arriving in Chicago in January with a light jacket. Gemini's access to current data means the weather guidance is actually accurate for your dates.</div>
        <div class="mary-quote">"Gemini reminded me to bring a power adapter for the hotel hairdryer. I had not thought about the hotel hairdryer. Gemini had." 😄</div>
      </div>
    </div>

    <div class="divider"></div>

    <!-- PROMPT 10 -->
    <div class="prompt-card">
      <div class="card-header">
        <div class="card-num">10</div>
        <div class="card-title-wrap">
          <span class="card-emoji">👶</span>
          <div class="card-title">Ask AI to Explain Something Your Grandchild Said</div>
          <span class="card-agent agent-any">Any agent works</span>
        </div>
      </div>
      <div class="card-body">
        <div class="mary-story">Her grandson said dinner was "bussin." Her granddaughter said a movie was "lowkey mid." Dave thought "mid" was a compliment. <em>Mary looked it up that evening. Thanksgiving was much smoother after that.</em></div>
        <div class="prompt-label">📝 The Prompt</div>
        <div class="prompt-box">
          <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
          <p>You are a patient cultural translator helping someone over 50 understand modern slang and references.</p>
          <p>My <span class="fill">[grandchild / teenager / young colleague]</span> said: <span class="fill">"[exact phrase or word]"</span></p>
          <p>The context was: <span class="fill">[briefly describe the situation]</span>.</p>
          <p>Explain: what it means, whether it was positive or negative, and one natural way I could use it myself without sounding like I'm trying too hard.</p>
          <p>Also: should I be concerned, or is this completely normal? 😊</p>
        </div>
        <div class="why-box"><strong>Why it works:</strong> "Without sounding like I'm trying too hard" is the most important instruction in this prompt. It produces one specific example of appropriate use — rather than an explanation that makes you sound like you read it in a dictionary. Which you did. But they don't need to know that.</div>
        <div class="mary-quote">"I used 'bussin' once at Thanksgiving. My grandson stopped eating and stared at me. My granddaughter said: 'Okay, Grandma.' That is, I have been told, a compliment." 😄</div>
      </div>
    </div>

  </div><!-- /prompt-grid -->

  <!-- Footer CTA -->
  <div class="footer-cta no-print">
    <h2>Want 10 more prompts?</h2>
    <p>The full book contains Chapter 11 with Mary's 10 favorite everyday prompts,<br>plus nine chapters of guided practice with ChatGPT, Claude, and Gemini.</p>
    <a class="btn-amazon" href="https://www.amazon.com/s?k=Ask+Smarter+Get+More+Ivan" target="_blank">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 01-8 0"/></svg>
      Find on Amazon · $2.99
    </a>
  </div>

  <div class="footer-note no-print">
    © 2026 Ivan · <em>Ask Smarter. Get More.</em> · Free bonus for readers ·
    <a href="https://www.amazon.com/s?k=Ask+Smarter+Get+More+Ivan" target="_blank">amazon.com</a>
  </div>

</div><!-- /page-wrap -->

<script>
function copyPrompt(btn) {
  const box = btn.parentElement;
  const text = Array.from(box.querySelectorAll('p'))
    .map(p => p.innerText)
    .join('\n');
  navigator.clipboard.writeText(text).then(() => {
    btn.textContent = 'Copied!';
    btn.classList.add('copied');
    setTimeout(() => {
      btn.textContent = 'Copy';
      btn.classList.remove('copied');
    }, 2000);
  });
}
</script>
</body>
</html>
