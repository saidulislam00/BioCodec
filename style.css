/* ========= CONFIG: edit these ========= */
const SOCIAL = { "Google Scholar": "", GitHub: "", LinkedIn: "", Kaggle: "https://www.kaggle.com/swandipsingha" }; // empty = hidden

/* ========= DATA ========= */
const PUBS = [
  { t: "J", title: "Adaptive Digital Filtering and TreeSHAP Feature Selection for Non-Invasive Diabetes Classification from Photoplethysmography Signals", authors: "S. Singha, A. Chowdhury", venue: "Discover Artificial Intelligence, 2026", link: "" /* add DOI */ },
  { t: "C", title: "1D-CNN-Based Denoising of PPG Signals for Preserving Heart Rate Variability Information", authors: "S. Singha, A. Chowdhury, R. C. C. Cheung, M. H. Chowdhury", venue: "IEEE ICEIC, 2026 (oral presentation, online)", link: "" /* add DOI */ },
  { t: "C", title: "MIT-BIH ECG Arrhythmia Multi-Class Classification Using AdamW-Optimized Deep Ensembles with SMOTE-Based Sampling", authors: "S. Singha, A. Saha, et al.", venue: "IEEE QPAIN, 2026 (oral presentation, online)", link: "" /* add DOI */ },
  { t: "P", title: "MoWaveQFormer: A Motion-Conditioned Quality-Gated Transformer for Smartphone-Based PPG Heart Rate Estimation", authors: "S. Singha, R. B. Reza, S. R. Sabuj", venue: "arXiv:2609.16248, 2026", link: "https://arxiv.org/abs/2609.16248" },
  { t: "U", title: "BAFF-ECG: SNR-Conditioned ECG Denoising via Dirichlet Filter Fusion and Residual Gating", authors: "S. Singha, A. Chowdhury", venue: "Under review at Measurement", link: "" },
  { t: "U", title: "Non-Invasive Blood Glucose Estimation from Multi-Wavelength Photoplethysmography Using Adaptive Signal Quality Assessment and Statistical Feature Selection", authors: "S. Singha, A. Chowdhury", venue: "Under review at Health Information Science and Systems", link: "" },
  { t: "U", title: "Lightweight Domain-Adaptive SNR Estimation for 5G NR Channels via Scenario-Embedded Transfer Learning", authors: "S. Singha, A. Chowdhury", venue: "Under review at Arabian Journal for Science and Engineering", link: "" }
];
const LABEL = { J: "Journal", C: "Conf.", P: "Preprint", U: "Review" };

const PROJECTS = [
  { s: "Preprint", ok: 1, stat: "7.85", unit: "bpm MAE", name: "MoWaveQFormer", blurb: "Smartphone PPG heart-rate estimation.", more: "A motion-conditioned, quality-gated Transformer evaluated on a subject-independent split of BUT PPG v2.0, with about 816K parameters and sub-3-ms inference latency.", tags: ["Transformer", "Wavelets", "Heart rate"] },
  { s: "Under review", stat: "11.71", unit: "dB output SNR", name: "BAFF-ECG", blurb: "SNR-aware ECG denoising.", more: "Dirichlet attention blends classical filters and a residual gate adapts to the noise level estimated from the noisy signal alone. Cross-correlation with clean ECG reaches 0.917.", tags: ["ECG", "Filter fusion", "Gating"] },
  { s: "Presented", ok: 1, stat: "27.88", unit: "dB SNR", name: "HRV-preserving PPG denoiser", blurb: "Clean signals that keep HRV intact.", more: "An attention-enhanced 1D-CNN encoder–decoder with an HRV-preserving loss, reaching 0.998 correlation on synthetic data. Presented at IEEE ICEIC 2026.", tags: ["1D-CNN", "PPG", "HRV"] },
  { s: "Published", ok: 1, stat: "90.91%", unit: "accuracy", name: "PPG diabetes screening", blurb: "Non-invasive screening from PPG.", more: "Adaptive filtering, signal-quality assessment and TreeSHAP feature selection give 0.915 ROC-AUC. A companion glucose-estimation study (under review) reaches R² = 0.410.", tags: ["TreeSHAP", "Glucose", "Screening"] },
  { s: "In preparation", stat: "150", unit: "studies", name: "ECG denoising review", blurb: "A PRISMA-guided systematic review.", more: "Finds a reconstruction–decision gap: 74% test only on synthetic noise, 79% use one lead and 73% never test clinical impact. Proposes a five-part reporting standard.", tags: ["PRISMA", "Review", "Reporting"] },
  { s: "Presented", ok: 1, stat: "0.86", unit: "macro F1", name: "Arrhythmia ensembles", blurb: "MIT-BIH multi-class classification.", more: "AdamW-optimized deep ensembles with SMOTE balancing lift macro F1 from 0.74 to 0.86 over the baseline. Presented at IEEE QPAIN 2026.", tags: ["Ensembles", "SMOTE", "ECG"] }
];

const TIMELINE = [
  { when: "Ongoing", role: "Sabuj Lab, BRAC University", org: "Dhaka, Bangladesh", pts: ["Development and evaluation of MoWaveQFormer for smartphone PPG heart-rate estimation."] },
  { when: "Ongoing", role: "ELITE Research Lab LLC", org: "New York, USA", pts: ["PRISMA-guided systematic review of 150 ECG denoising studies (2013–2026); manuscript in preparation."] },
  { when: "Since 2024", role: "Chittagong University of Engineering and Technology", org: "Department of Electrical and Electronic Engineering", pts: ["Where the lab began: PPG diabetes screening, ECG denoising, HRV-preserving PPG denoising and arrhythmia classification."] }
];

const HONORS = [
  { h: "Kaggle Master, 2025", m: "Peak global rank 73", links: [["Profile", "https://www.kaggle.com/swandipsingha"]] },
  { h: "Global AI Hackathon, 2025", m: "42nd place globally", links: [["Leaderboard", "https://www.kaggle.com/competitions/el-hackathon-2025/leaderboard"], ["Solution", "https://www.kaggle.com/code/swandipsingha/global-ai-hackathon-2025-end-to-end-solution"]] },
  { h: "KUET CSE Fest Datathon, 2025", m: "10th of 108 national teams", links: [["Leaderboard", "https://www.kaggle.com/competitions/bitfest-datathon-2025/leaderboard"], ["Solution", "https://www.kaggle.com/code/swandipsingha/tsukuyomi"]] }
];

// List a person only with their permission, and confirm the exact title and role wording with each of them.
const MENTORS = [
  { n: "Swandip Singha", r: "Founder and lead researcher", d: "Undergraduate in EEE at CUET. Kaggle Master. Leads MoWaveQFormer and the ECG denoising work.", u: "mailto:swandip.singha@gmail.com" },
  { n: "Aditta Chowdhury", r: "Advisor, CUET", d: "Assistant Professor, EEE. Advises the PPG and ECG work.", u: "https://cuet.ac.bd/profile/faculty-member/aditta-chowdhury" },
  { n: "Saifur Rahman Sabuj", r: "Advisor, BRAC University", d: "Sabuj Lab. Advises MoWaveQFormer.", u: "" },
  { n: "Md. Kishor Morol", r: "Collaborator, ELITE Research Lab", d: "Collaborates on the ECG denoising review.", u: "https://www.aiub.edu/faculty-list/faculty-profile?q=kishor" }
];

/* ========= HELPERS ========= */
const $ = (s, r = document) => r.querySelector(s);
const $$ = (s, r = document) => [...r.querySelectorAll(s)];
const esc = s => s.replace(/[&<>"]/g, c => ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;" }[c]));
const ini = n => n.split(" ").filter(w => /^[A-Z]/.test(w)).map(w => w[0]).slice(0, 2).join("");
const reduce = matchMedia("(prefers-reduced-motion: reduce)").matches;
$("#yr").textContent = new Date().getFullYear();

/* nav */
const burger = $(".burger"), links = $("#links");
burger.addEventListener("click", () => { const o = links.classList.toggle("open"); burger.setAttribute("aria-expanded", o); });
links.addEventListener("click", e => { if (e.target.closest("a")) { links.classList.remove("open"); burger.setAttribute("aria-expanded", false); } });
const spy = new IntersectionObserver(es => es.forEach(e => {
  if (e.isIntersecting) $$("#links a").forEach(a => a.classList.toggle("active", a.getAttribute("href") === "#" + e.target.id && !a.classList.contains("cta")));
}), { rootMargin: "-45% 0px -50% 0px" });
$$("main section").forEach(s => spy.observe(s));

/* render */
const pubs = $("#pubs");
function renderPubs(f = "all") {
  pubs.innerHTML = PUBS.filter(p => f === "all" || p.t === f).map(p =>
    `<li class="glass"><span class="tag ${p.t}">${LABEL[p.t]}</span><h3>${esc(p.title)}</h3><span class="m">${esc(p.authors)}</span><span class="m">${esc(p.venue)}${p.link ? ` · <a href="${p.link}" target="_blank" rel="noopener">Read</a>` : ""}</span></li>`).join("");
}
renderPubs();
$$(".chip").forEach(c => c.addEventListener("click", () => { $$(".chip").forEach(x => x.classList.remove("on")); c.classList.add("on"); renderPubs(c.dataset.f); }));

$("#projects-grid").innerHTML = PROJECTS.map((p, i) =>
  `<article class="card glass proj proj-wrap"><div class="top"><span class="status-tag ${p.ok ? "ok" : ""}">${p.s}</span><div class="stat">${p.stat}<small>${p.unit}</small></div><h3>${p.name}</h3><p>${p.blurb}</p></div><div class="more" id="pm${i}">${p.more}</div><button class="proj-btn" aria-expanded="false" aria-controls="pm${i}">Details</button><div class="tags">${p.tags.map(t => `<span>${t}</span>`).join("")}</div></article>`).join("");
$$(".proj-btn").forEach(b => b.addEventListener("click", () => {
  const card = b.closest(".proj"), o = b.getAttribute("aria-expanded") === "true";
  card.setAttribute("aria-expanded", !o); b.setAttribute("aria-expanded", !o); b.textContent = o ? "Details" : "Hide";
}));

$("#timeline").innerHTML = TIMELINE.map(t =>
  `<li class="glass"><span class="when">${t.when}</span><div><h3>${t.role}</h3><p class="org">${t.org}</p><ul>${t.pts.map(x => `<li>${x}</li>`).join("")}</ul></div></li>`).join("");
$("#honors").innerHTML = HONORS.map(h =>
  `<li class="glass"><span><b>${h.h}</b> <span class="m">· ${h.m}</span></span><span class="m">${h.links.map(([l, u]) => `<a href="${u}" target="_blank" rel="noopener">${l}</a>`).join(" · ")}</span></li>`).join("");
$("#mentors").innerHTML = MENTORS.map(m =>
  `<article class="card glass"><div class="avatar sm">${ini(m.n)}</div><h3>${m.u ? `<a href="${m.u}" target="_blank" rel="noopener">${m.n}</a>` : m.n}</h3><p class="role">${m.r}</p><p>${m.d}</p></article>`).join("");
$("#social").innerHTML = Object.entries(SOCIAL).filter(([, u]) => u).map(([l, u]) => `<a href="${u}" target="_blank" rel="noopener">${l}</a>`).join("");

/* gentle reveal, headings and grids only */
const rv = new IntersectionObserver(es => es.forEach(e => { if (e.isIntersecting) { e.target.classList.add("in"); rv.unobserve(e.target); } }), { threshold: .12 });
$$("section:not(.hero) h2, section:not(.hero) .sub, .grid, .pubs, .timeline, .honors, .stats").forEach(el => { el.classList.add("rv"); rv.observe(el); });

/* ========= SIGNAL SCOPE (synthetic illustration) ========= */
const cv = $("#wave"), ctx = cv.getContext("2d");
const noiseIn = $("#noise"), codecIn = $("#codec"), hrEl = $("#hr"), sqEl = $("#sq");
let W, H, DPR;
function size() { DPR = Math.min(devicePixelRatio || 1, 2); W = cv.clientWidth; H = cv.clientHeight; cv.width = W * DPR; cv.height = H * DPR; ctx.setTransform(DPR, 0, 0, DPR, 0, 0); }
size(); addEventListener("resize", size);
const BPM = 72, PERIOD = 60 / BPM, SPEED = 120;
const g = (x, m, s) => Math.exp(-((x - m) ** 2) / (2 * s * s));
const clean = t => { const p = ((t % PERIOD) + PERIOD) % PERIOD / PERIOD; return g(p, .2, .07) + .38 * g(p, .5, .09); };
const motion = t => Math.sin(t * 2.3) * .55 + Math.sin(t * 5.1 + 1) * .35 + Math.sin(t * .7) * .4 + (Math.sin(t * 1.3) > .6 ? Math.sin(t * 17) * .5 : 0);
const hash = x => { const s = Math.sin(x * 12.9898) * 43758.5453; return s - Math.floor(s); };
const jitter = t => hash(Math.floor(t * 90)) - .5;
const y = v => H * .72 - v * H * .5;
let T = 0, last = performance.now(), visible = true;
function trace(fn, color, width, alpha) {
  ctx.beginPath();
  for (let x = 0; x <= W; x += 2) { const v = fn(T + x / SPEED); x ? ctx.lineTo(x, y(v)) : ctx.moveTo(x, y(v)); }
  ctx.strokeStyle = color; ctx.lineWidth = width; ctx.globalAlpha = alpha; ctx.lineJoin = "round"; ctx.stroke(); ctx.globalAlpha = 1;
}
new IntersectionObserver(e => visible = e[0].isIntersecting).observe(cv);
function frame(now) {
  requestAnimationFrame(frame);
  if (!visible) { last = now; return; }
  T += reduce ? 0 : (now - last) / 1000; last = now;
  const n = noiseIn.value / 100, on = codecIn.checked;
  ctx.clearRect(0, 0, W, H);
  ctx.strokeStyle = "rgba(42,111,176,.08)"; ctx.lineWidth = 1;
  for (let x = 0; x < W; x += 40) { ctx.beginPath(); ctx.moveTo(x, 0); ctx.lineTo(x, H); ctx.stroke(); }
  for (let k = 1; k < 6; k++) { ctx.beginPath(); ctx.moveTo(0, k * H / 6); ctx.lineTo(W, k * H / 6); ctx.stroke(); }
  trace(t => clean(t) + n * (1.1 * motion(t) + .5 * jitter(t)), "#f08a5d", 2, on ? .5 : 1);
  if (on) { ctx.shadowColor = "rgba(23,184,162,.6)"; ctx.shadowBlur = 12; trace(t => clean(t) + n * .06 * motion(t) * (n > .85 ? 2.5 : 1), "#17b8a2", 3.5, 1); ctx.shadowBlur = 0; }
}
requestAnimationFrame(frame);
setInterval(() => {
  const n = noiseIn.value / 100, on = codecIn.checked, err = on ? n * 1.5 : n * 22;
  hrEl.textContent = Math.round(BPM + (Math.random() - .5) * 2 * err);
  sqEl.textContent = on && n > .85 ? "Low, segment gated" : n < .35 ? "High" : n < .7 ? "Medium" : "Low";
}, 600);
