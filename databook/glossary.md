<!-- GENERATED FILE — DO NOT EDIT BY HAND.
     Produced by scripts/build-glossary-page.mjs in this repository, from
     https://github.com/lappalainenj/allen-glossary
     Source commit: 1aa0c040189adc824959263bfd31e79e4d6bed84
     Edit the definitions in that repository's data/ directory; this page is
     regenerated from it and any change made here will be overwritten. -->

# Glossary

139 terms across 18 categories, from the
[Allen Glossary](https://lappalainenj.github.io/allen-glossary/). Search matches names, definitions, categories and dataset
names; the category legend doubles as a filter, so clicking one or more pills narrows the
list. Every term has a permalink you can paste into an email — click a term name to copy
the link to it.

:::::{raw} html
<style>
/* Allen Glossary — generated, do not edit here. Every rule is scoped to
   .acg-root so nothing leaks into the rest of the databook, and every class is
   prefixed acg- so the theme's own .card/.grid/.chip rules cannot reach in. */
.acg-root{
  --acg-sans: ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  --acg-mono: ui-monospace, SFMono-Regular, "SF Mono", Menlo, Consolas, "Liberation Mono", monospace;
  --card:#ffffff; --ink:#12161c; --muted:#55606d; --faint:#8b95a1;
  --line:#e0e5ea; --line-2:#cfd6de; --panel:#eef1f4;
  --accent:#0d7d88; --accent-ink:#0a5a63;
  --accent-soft:color-mix(in srgb, var(--accent) 10%, transparent);
  --scaffold:#7c8695; --neuron:#39424f; --dendrite:#3f6fa8; --axon:#b07a2b; --synapse:#c04a6e;
  --error:#c0392b; --ok:#2a8f57;
  --surface:var(--card); --surface-2:var(--panel);
  --border:var(--line); --border-strong:var(--line-2);
  --r:8px;
  --shadow:0 1px 2px rgba(20,24,29,.05), 0 6px 18px -12px rgba(20,24,29,.25);
  font-family:var(--acg-sans); color:var(--ink);
}
/* The databook theme stamps data-theme on <html>; honour it in both directions
   and fall back to the OS preference when it is left on auto. */
@media (prefers-color-scheme: dark){
  html:not([data-theme="light"]) .acg-root{
    --card:#141a21; --ink:#e7edf3; --muted:#97a1af; --faint:#67707e;
    --line:#232b35; --line-2:#303a46; --panel:#1a2129;
    --accent:#3cced9; --accent-ink:#86e4ec;
    --accent-soft:color-mix(in srgb, var(--accent) 14%, transparent);
    --scaffold:#8f99a8; --neuron:#c2cad6; --dendrite:#71a4dd; --axon:#d7a355; --synapse:#e2809c;
    --shadow:0 1px 2px rgba(0,0,0,.4), 0 8px 22px -14px rgba(0,0,0,.8);
  }
}
html[data-theme="dark"] .acg-root{
  --card:#141a21; --ink:#e7edf3; --muted:#97a1af; --faint:#67707e;
  --line:#232b35; --line-2:#303a46; --panel:#1a2129;
  --accent:#3cced9; --accent-ink:#86e4ec;
  --accent-soft:color-mix(in srgb, var(--accent) 14%, transparent);
  --scaffold:#8f99a8; --neuron:#c2cad6; --dendrite:#71a4dd; --axon:#d7a355; --synapse:#e2809c;
  --shadow:0 1px 2px rgba(0,0,0,.4), 0 8px 22px -14px rgba(0,0,0,.8);
}
html[data-theme="light"] .acg-root{
  --card:#ffffff; --ink:#12161c; --muted:#55606d; --faint:#8b95a1;
  --line:#e0e5ea; --line-2:#cfd6de; --panel:#eef1f4;
  --accent:#0d7d88; --accent-ink:#0a5a63;
  --scaffold:#7c8695; --neuron:#39424f; --dendrite:#3f6fa8; --axon:#b07a2b; --synapse:#c04a6e;
}

.acg-root *{box-sizing:border-box}
.acg-root [hidden]{display:none !important}
.acg-root .mono{font-family:var(--acg-mono)}

/* ── control bar ──────────────────────────────────────────────── */
.acg-bar{display:flex; align-items:center; gap:.6rem; flex-wrap:wrap; margin:0 0 .9rem}
.acg-search{flex:1 1 260px; display:flex; align-items:center; gap:.45rem; min-width:0;
  background:var(--card); border:1px solid var(--line-2); border-radius:99px; padding:.3rem .8rem}
.acg-search:focus-within{border-color:var(--accent); box-shadow:0 0 0 3px var(--accent-soft)}
.acg-search svg{width:15px; height:15px; flex:none; color:var(--faint)}
.acg-search input{flex:1; min-width:0; font:inherit; font-size:.85rem; color:var(--ink);
  background:none; border:0; outline:none; padding:0}
.acg-search input::-webkit-search-cancel-button{cursor:pointer}
.acg-count{font-family:var(--acg-mono); font-size:.68rem; color:var(--faint);
  white-space:nowrap; font-variant-numeric:tabular-nums}

/* ── legends ──────────────────────────────────────────────────── */
.acg-legends{display:flex; flex-direction:column; gap:.5rem; margin:0 0 1.1rem}
.acg-legend{font-size:.75rem; min-width:0}
.acg-legend > summary{cursor:pointer; color:var(--muted); font-family:var(--acg-mono);
  font-size:.63rem; letter-spacing:.1em; text-transform:uppercase; list-style:none}
.acg-legend > summary::-webkit-details-marker{display:none}
.acg-legend > summary::before{content:"\25B8 "; color:var(--faint)}
.acg-legend[open] > summary::before{content:"\25BE "}
.acg-legend .acg-hint{font-family:var(--acg-sans); text-transform:none; letter-spacing:0;
  font-size:.72rem; color:var(--faint)}
.acg-body{display:flex; flex-wrap:wrap; gap:.35rem; padding:.55rem 0 0 .9rem; align-items:center}
.acg-body.acg-anat{gap:.2rem .9rem}
.acg-body.acg-anat span{display:inline-flex; align-items:center; gap:.35rem;
  color:var(--muted); font-size:.72rem}
.acg-body.acg-anat i{width:9px; height:9px; border-radius:99px; flex:none}
.acg-caveat{margin:.55rem 0 0 .9rem; font-size:.72rem; line-height:1.45; color:var(--faint); max-width:70ch}

.acg-pillgroup{display:flex; flex-wrap:wrap; align-items:center; gap:.3rem; width:100%}
.acg-glabel{font-family:var(--acg-mono); font-size:.58rem; letter-spacing:.1em;
  text-transform:uppercase; color:var(--faint); width:6.2rem; flex:none}
@media (max-width:640px){ .acg-glabel{width:100%} }

/* the category legend doubles as the filter — clicking a pill narrows the grid */
.acg-pill{appearance:none; font:inherit; font-size:.72rem; cursor:pointer; color:var(--muted);
  background:var(--card); border:1px solid var(--line); border-radius:99px;
  padding:.16rem .6rem .16rem .45rem; display:inline-flex; align-items:center; gap:.35rem;
  line-height:1.35}
.acg-pill i{width:9px; height:9px; border-radius:2px; flex:none; background:var(--cc)}
.acg-pill:hover{border-color:var(--line-2); color:var(--ink)}
.acg-pill[aria-pressed="true"]{border-color:var(--cc); color:var(--ink);
  background:color-mix(in srgb, var(--cc) 12%, transparent); font-weight:600}
.acg-pill .acg-n{font-family:var(--acg-mono); font-size:.6rem; color:var(--faint);
  font-variant-numeric:tabular-nums}
.acg-pill.acg-zero{opacity:.4}
.acg-clear{appearance:none; font:inherit; font-size:.68rem; cursor:pointer; background:none;
  border:0; color:var(--accent-ink); text-decoration:underline; padding:.16rem .3rem}

/* ── the grid ─────────────────────────────────────────────────── */
/* A grid, not columns: entries read left to right along each row, the order
   people expect from an alphabetical list. */
.acg-grid{display:grid; grid-template-columns:repeat(auto-fill, minmax(250px, 1fr)); gap:12px}

.acg-card{display:flex; flex-direction:column; margin:0;
  background:var(--card); border:1px solid var(--line); border-left:3px solid var(--line-2);
  border-radius:var(--r); padding:.55rem .65rem .6rem; box-shadow:var(--shadow)}
.acg-card .acg-art{background:var(--panel); border:1px solid var(--line); border-radius:5px;
  padding:3px 4px; margin-bottom:.4rem}
.acg-card .acg-art svg{display:block; width:100%; height:auto; color:var(--neuron)}
.acg-card .acg-eb{margin-top:auto; font-family:var(--acg-mono); font-size:.56rem; font-weight:700;
  letter-spacing:.09em; margin-bottom:1px}
.acg-card .acg-h{margin:0; padding:0; border:0; font-size:.92rem; font-weight:700;
  line-height:1.2; letter-spacing:-.012em; color:var(--ink)}
.acg-card .acg-name{color:inherit; text-decoration:none}
.acg-card .acg-name::after{content:"#"; color:var(--faint); font-weight:400; margin-left:.3em;
  opacity:0; font-family:var(--acg-mono); font-size:.8em}
.acg-card:hover .acg-name::after,.acg-card .acg-name:focus-visible::after{opacity:1}
.acg-card:target{outline:2px solid var(--accent); outline-offset:3px}
.acg-card .acg-def{margin:.22rem 0 0; font-size:.79rem; color:var(--muted); line-height:1.38}
.acg-card .acg-def code{font-family:var(--acg-mono); font-size:.88em; background:var(--panel);
  color:var(--ink); padding:.05em .3em; border-radius:4px; word-break:break-word; border:0}
.acg-card .acg-meta{display:flex; flex-wrap:wrap; gap:.25rem; margin-top:.42rem}

.acg-chip{display:inline-flex; align-items:center; gap:.25rem; font-family:var(--acg-mono);
  font-size:.57rem; letter-spacing:.05em; text-transform:uppercase; line-height:1.6;
  border:1px solid var(--line-2); color:var(--muted); border-radius:99px; padding:.06rem .42rem}
.acg-chip.acg-ds{border-style:dashed}
.acg-chip.acg-warn{border-color:currentColor; color:var(--axon)}
.acg-chip.acg-ng{border-color:var(--accent); color:var(--accent-ink); text-decoration:none}
.acg-chip.acg-ng:hover{background:var(--accent-soft)}
.acg-chip.acg-aside{border-style:dotted; color:var(--faint)}
.acg-chip.acg-src{border-style:dotted; color:var(--faint); text-decoration:none}
.acg-chip.acg-src:hover{color:var(--accent-ink); border-color:var(--accent)}

.acg-root mark{background:var(--accent-soft); color:inherit; border-radius:2px; padding:0 .1em}
.acg-empty{text-align:center; color:var(--faint); padding:2.5rem 0; font-size:.85rem}
.acg-foot{margin-top:1.6rem; padding-top:.7rem; border-top:1px solid var(--line);
  font-size:.72rem; line-height:1.5; color:var(--faint)}
.acg-foot a{color:var(--accent-ink)}

/* The term index is a MyST {glossary} directive, so it renders outside
   .acg-root as the theme's own <dl>, inside a sphinx-design dropdown. Both are
   styled by stylesheets the deployed site already carries — jupyter-book ships
   sphinx-design's CSS on every page regardless of whether a page uses it, and
   the pinned toolchain guarantees the same bundle. Compacted here, since this
   <style> only loads on this page. */
dl.glossary{font-size:.82rem; columns:2; column-gap:2rem; margin-top:.6rem}
dl.glossary dt{font-weight:600; break-inside:avoid; margin-top:.5rem}
dl.glossary dd{margin:.1rem 0 0; padding:0; color:#55606d; break-inside:avoid}
html[data-theme="dark"] dl.glossary dd{color:#97a1af}
@media (max-width:800px){ dl.glossary{columns:1} }
</style>

<div class="acg-root" id="acg">

  <div class="acg-bar">
    <label class="acg-search">
      <svg viewBox="0 0 16 16" aria-hidden="true"><circle cx="7" cy="7" r="4.6" fill="none" stroke="currentColor" stroke-width="1.6"/><path d="M10.4 10.4 14 14" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg>
      <input class="acg-q" type="search" placeholder="Search terms and definitions&#8230;" aria-label="Search the glossary" autocomplete="off" spellcheck="false">
    </label>
    <span class="acg-count">139 terms</span>
  </div>

  <div class="acg-legends">
    <details class="acg-legend" open>
      <summary>Category <span class="acg-hint">&#8212; the colour on a card's edge. Click to filter.</span></summary>
      <div class="acg-body">
      <div class="acg-pillgroup">
        <span class="acg-glabel">Connectomics</span>
        <button type="button" class="acg-pill" data-cat="datasets" style="--cc:#0e7f8c" aria-pressed="false"><i></i>Datasets &amp; scope<span class="acg-n">8</span></button>
        <button type="button" class="acg-pill" data-cat="imaging" style="--cc:#8a6f4a" aria-pressed="false"><i></i>Imaging &amp; ultrastructure<span class="acg-n">6</span></button>
        <button type="button" class="acg-pill" data-cat="volume" style="--cc:#2f6fd0" aria-pressed="false"><i></i>Volume, voxels &amp; coordinates<span class="acg-n">7</span></button>
        <button type="button" class="acg-pill" data-cat="segmentation" style="--cc:#6d55e0" aria-pressed="false"><i></i>Segmentation &amp; reconstruction<span class="acg-n">8</span></button>
        <button type="button" class="acg-pill" data-cat="morphology" style="--cc:#2a8f57" aria-pressed="false"><i></i>Morphology — meshes &amp; skeletons<span class="acg-n">21</span></button>
        <button type="button" class="acg-pill" data-cat="proofreading" style="--cc:#b8791a" aria-pressed="false"><i></i>Proofreading &amp; data quality<span class="acg-n">4</span></button>
        <button type="button" class="acg-pill" data-cat="cave" style="--cc:#0f766e" aria-pressed="false"><i></i>CAVE — access &amp; versioning<span class="acg-n">5</span></button>
        <button type="button" class="acg-pill" data-cat="tables" style="--cc:#9333ea" aria-pressed="false"><i></i>Annotation tables, IDs &amp; queries<span class="acg-n">2</span></button>
        <button type="button" class="acg-pill" data-cat="connectivity" style="--cc:#d1462c" aria-pressed="false"><i></i>Connectivity &amp; synapses<span class="acg-n">3</span></button>
        <button type="button" class="acg-pill" data-cat="functional" style="--cc:#9a5b12" aria-pressed="false"><i></i>Functional data &amp; coregistration<span class="acg-n">8</span></button>
        <button type="button" class="acg-pill" data-cat="tools" style="--cc:#526278" aria-pressed="false"><i></i>Visualisation tools<span class="acg-n">3</span></button>
      </div>
      <div class="acg-pillgroup">
        <span class="acg-glabel">Physiology</span>
        <button type="button" class="acg-pill" data-cat="modalities" style="--cc:#c2410c" aria-pressed="false"><i></i>Recording modalities &amp; instruments<span class="acg-n">5</span></button>
        <button type="button" class="acg-pill" data-cat="signals" style="--cc:#0369a1" aria-pressed="false"><i></i>Signals &amp; preprocessing<span class="acg-n">3</span></button>
        <button type="button" class="acg-pill" data-cat="genetics" style="--cc:#15803d" aria-pressed="false"><i></i>Genetic &amp; optical tools<span class="acg-n">12</span></button>
        <button type="button" class="acg-pill" data-cat="stimuli" style="--cc:#a16207" aria-pressed="false"><i></i>Stimuli &amp; behavioural tasks<span class="acg-n">1</span></button>
        <button type="button" class="acg-pill" data-cat="responses" style="--cc:#9f1239" aria-pressed="false"><i></i>Response properties &amp; analysis<span class="acg-n">6</span></button>
        <button type="button" class="acg-pill" data-cat="dataorg" style="--cc:#3f3f46" aria-pressed="false"><i></i>Datasets, sessions &amp; files<span class="acg-n">8</span></button>
      </div>
      <div class="acg-pillgroup">
        <span class="acg-glabel">Both</span>
        <button type="button" class="acg-pill" data-cat="celltypes" style="--cc:#c9357f" aria-pressed="false"><i></i>Cell types &amp; cortical anatomy<span class="acg-n">29</span></button>
      </div>
        <button type="button" class="acg-clear" hidden>show all</button>
      </div>
    </details>
    <details class="acg-legend">
      <summary>Illustration <span class="acg-hint">&#8212; colour inside a drawing means anatomy, never category</span></summary>
      <div class="acg-body acg-anat">
        <span><i style="background:var(--scaffold)"></i>structure / volume</span>
        <span><i style="background:var(--dendrite)"></i>dendrite</span>
        <span><i style="background:var(--axon)"></i>axon</span>
        <span><i style="background:var(--synapse)"></i>synapse</span>
      </div>
      <p class="acg-caveat">The illustrations are generated rather than hand-drawn. They are being
      checked by the people who know the data, but errors cannot be ruled out at this stage &#8212;
      read them as sketches of the idea, and trust the definition over the picture.
      80 of 139 terms have one.</p>
    </details>
  </div>

  <div class="acg-grid">
    <article class="acg-card" id="term-3d-reconstruction" data-cat="segmentation" data-hay="3d reconstruction turning em imagery into 3d neuron objects (dense segmentation → meshes). segmentation &amp; reconstruction ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="rec3d"><title id="rec3d">3D reconstruction pipeline</title><rect x="16" y="58" width="76" height="74" fill="var(--scaffold)" fill-opacity=".12" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/><path d="M24,74 H84 M24,88 H84 M24,102 H84 M24,116 H84" stroke="currentColor" stroke-opacity=".28" stroke-width="2" stroke-linecap="round"/><text x="54" y="150" text-anchor="middle" font-size="11" fill="var(--muted)">EM tile</text><path d="M98,95 H113" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/><path d="M109,89 l7,6 -7,6" fill="none" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><polygon points="122,58 160,58 160,95 122,95" fill="var(--neuron)" fill-opacity=".6"/><polygon points="160,58 198,58 198,95 160,95" fill="var(--dendrite)" fill-opacity=".6"/><polygon points="122,95 160,95 160,132 122,132" fill="var(--axon)" fill-opacity=".6"/><polygon points="160,95 198,95 198,132 160,132" fill="var(--synapse)" fill-opacity=".6"/><path d="M160,58 V132 M122,95 H198" stroke="var(--surface)" stroke-width="1.5"/><rect x="122" y="58" width="76" height="74" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/><text x="160" y="150" text-anchor="middle" font-size="11" fill="var(--muted)">segmented</text><path d="M204,95 H219" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/><path d="M215,89 l7,6 -7,6" fill="none" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><rect x="228" y="58" width="76" height="74" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/><circle cx="266" cy="96" r="8" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2.2"/><path d="M266,88 C262,74 258,70 250,64 M266,88 C271,74 277,72 285,66 M266,104 C266,118 269,122 274,128 M259,93 C248,90 242,90 236,86" fill="none" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/><text x="266" y="150" text-anchor="middle" font-size="11" fill="var(--muted)">3D mesh</text></svg></div>
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-3d-reconstruction" title="Link to this term">3D reconstruction</a></h3>
    <p class="acg-def">Turning EM imagery into 3D neuron objects (dense segmentation → meshes).</p>
    </article>
    <article class="acg-card" id="term-action-potential" data-cat="celltypes" data-hay="action potential a characteristic signal that appears in excitable cell membranes, which takes the form of an electric potential difference waveform that propagates down the length of the cell membrane. in neurons, these indicate neuron activation. see spike. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ap-t"><title id="ap-t">Action potential — Hodgkin-Huxley simulation</title><g stroke="currentColor" stroke-opacity=".28" stroke-width="1" stroke-dasharray="3 3"><path d="M34,49.0 H306"/><path d="M34,88.0 H306"/></g><text x="31" y="52.0" text-anchor="end" font-size="7.5" class="mono" fill="var(--faint)">0</text><text x="31" y="91.0" text-anchor="end" font-size="7.5" class="mono" fill="var(--faint)">-65</text><text x="31" y="28.0" text-anchor="end" font-size="7.5" class="mono" fill="var(--faint)">+40</text><text x="12" y="60" font-size="8" fill="var(--muted)" transform="rotate(-90 12 60)" text-anchor="middle">mV</text><path d="M72.9,100 v6 h19.4 v-6" fill="none" stroke="var(--accent)" stroke-width="1.6"/><text x="82.6" y="116" text-anchor="middle" font-size="7.5" fill="var(--accent-ink)">stimulus</text><path d="M34.0,88.0 L72.9,88.0 L85.8,78.5 L89.5,73.5 L91.9,66.7 L93.9,56.2 L97.1,29.3 L98.1,25.7 L99.5,24.5 L102.6,26.6 L106.9,31.8 L135.2,73.8 L144.2,90.7 L148.2,94.1 L155.7,94.7 L196.6,94.0 L305.9,90.5" fill="none" stroke="var(--neuron)" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"/><circle cx="99.5" cy="24.5" r="2.4" fill="var(--neuron)"/><text x="104.5" y="25.5" font-size="8" fill="var(--muted)">peak +41 mV</text><text x="159.4" y="103.7" font-size="8" fill="var(--muted)">undershoot</text><g stroke-width="1.8" fill="none"><path d="M34.0,170.0 L82.2,169.9 L91.0,168.6 L93.0,166.8 L94.4,163.2 L98.7,137.4 L100.0,133.5 L101.5,132.1 L103.7,133.6 L113.3,146.9 L121.2,155.2 L131.5,162.8 L140.5,168.4 L144.1,169.7 L305.9,170.0" stroke="var(--accent)" stroke-opacity=".85"/><path d="M34.0,169.6 L94.5,169.1 L99.6,167.4 L117.1,158.2 L123.7,156.4 L130.6,155.8 L139.5,156.7 L167.5,163.5 L194.8,166.7 L237.1,168.7 L305.9,169.5" stroke="currentColor" stroke-opacity=".45"/></g><text x="306" y="129" text-anchor="end" font-size="7.5" class="mono" fill="var(--muted)">gK</text><text x="286" y="129" text-anchor="end" font-size="7.5" class="mono" fill="var(--accent-ink)">gNa</text><text x="12" y="152" font-size="8" fill="var(--muted)" transform="rotate(-90 12 152)" text-anchor="middle">mS/cm²</text><path d="M34,170 H306" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><g font-size="7.5" fill="var(--faint)" class="mono" text-anchor="middle"><text x="34.0" y="181">0</text><text x="131.1" y="181">5</text><text x="228.3" y="181">10</text><text x="308" y="181">ms</text></g><text x="160" y="194" text-anchor="middle" font-size="8" fill="var(--muted)">Na+ opens and closes; K+ follows and repolarises</text></svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-action-potential" title="Link to this term">Action potential</a></h3>
    <p class="acg-def">A characteristic signal that appears in excitable cell membranes, which takes the form of an electric potential difference waveform that propagates down the length of the cell membrane. In neurons, these indicate neuron activation. See Spike.</p>
    </article>
    <article class="acg-card" id="term-annotation" data-cat="tables" data-hay="annotation labeled data (points/tables) bound to locations or cells in the volume. annotation tables, ids &amp; queries ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="anno-t">
<title id="anno-t">Annotation</title>
<polygon points="30,78 84,78 84,138 30,138" fill="var(--scaffold)" fill-opacity=".12" stroke="currentColor" stroke-opacity=".55" stroke-width="1.5"/>
<polygon points="30,78 84,78 100,66 46,66" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.5"/>
<polygon points="84,78 100,66 100,126 84,138" fill="var(--scaffold)" fill-opacity=".06" stroke="currentColor" stroke-opacity=".55" stroke-width="1.5"/>
<line x1="57" y1="108" x2="57" y2="84" stroke="var(--synapse)" stroke-width="2" stroke-linecap="round"/>
<circle cx="57" cy="108" r="6" fill="var(--synapse)"/>
<circle cx="57" cy="84" r="3.6" fill="none" stroke="var(--synapse)" stroke-width="2"/>
<text x="57" y="156" text-anchor="middle" font-size="10" fill="var(--muted)">tagged point</text>
<path d="M104,102 C130,102 150,102 170,102" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/>
<path d="M165,97 l7,5 -7,5" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<rect x="178" y="72" width="118" height="62" rx="5" fill="var(--surface-2)" stroke="var(--border)" stroke-width="1.5"/>
<rect x="178" y="91" width="118" height="21" fill="var(--accent)" fill-opacity=".18"/>
<line x1="178" y1="91" x2="296" y2="91" stroke="var(--border)" stroke-width="1.4"/>
<line x1="178" y1="112" x2="296" y2="112" stroke="var(--border)" stroke-opacity=".6" stroke-width="1"/>
<text x="186" y="85" font-size="9.5" class="mono" fill="var(--muted)">id   pt_position</text>
<text x="186" y="105" font-size="9.5" class="mono" fill="var(--accent-ink)" font-weight="600">7   (x,y,z)</text>
<text x="186" y="126" font-size="9.5" class="mono" fill="var(--faint)">8   (x,y,z)</text>
<text x="237" y="156" text-anchor="middle" font-size="10" fill="var(--muted)">table row</text>
</svg></div>
    <div class="acg-eb" style="color:#9333ea">TABLES</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-annotation" title="Link to this term">Annotation</a></h3>
    <p class="acg-def">Labeled data (points/tables) bound to locations or cells in the volume.</p>
    </article>
    <article class="acg-card" id="term-astrocyte" data-cat="celltypes" data-hay="astrocyte a glial cell whose fine processes tile the neuropil and wrap capillaries with endfeet, supporting synapses metabolically and regulating the extracellular environment. its arbor is a dense thicket rather than a branching tree, which is why it is proofread to a different standard from a neuron. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-astrocyte" title="Link to this term">Astrocyte</a></h3>
    <p class="acg-def">A glial cell whose fine processes tile the neuropil and wrap capillaries with endfeet, supporting synapses metabolically and regulating the extracellular environment. Its arbor is a dense thicket rather than a branching tree, which is why it is proofread to a different standard from a neuron.</p>
    </article>
    <article class="acg-card" id="term-basket-cell" data-cat="celltypes" data-hay="basket cell (bc) a type of inhibitory neuron whose synaptic output targets the cell body and proximal dendrites of excitatory neurons. many basket cells express the molecular marker parvalbumin (pv), but not all basket cells are pv+: some express molecules such as cholecystokinin (cck). pv basket cells are typically fast spiking compared to other neurons and are thought to be important for gain control of network activity and setting the temporal precision of network activity. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d-basket-cell"><title id="d-basket-cell">Basket cell</title><defs><clipPath id="d-basket-cell-c" clipPathUnits="userSpaceOnUse"><rect x="12" y="26" width="76" height="118"/></clipPath></defs><g transform="translate(160,100) scale(1.55) translate(-50,-88)"><g clip-path="url(#d-basket-cell-c)"><g stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round">
<path d="M50,73 V54 M50,73 l-9,-12 M50,73 l9,-12"/>
<path d="M126,121 V132 M126,121 l-8,9 M126,121 l8,9"/>
<path d="M202,85 V54 M202,54 l-5,-6 M202,54 l5,-6 M202,95 V128 M202,128 l-5,6 M202,128 l5,6"/>
</g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M50,83 V95 M50,95 C44,98 40,104 42,112 M50,95 C56,98 60,104 58,112"/>
<path d="M126,111 V54 M112,54 H140 M116,54 v-6 M126,54 v-6 M136,54 v-6"/>
<path d="M278,88 l0,-16 M278,88 l14,-8 M278,88 l16,0 M278,88 l14,8 M278,88 l0,16 M278,88 l-14,8 M278,88 l-16,0 M278,88 l-14,-8"/>
</g>
<g fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.6"><circle cx="42" cy="110" r="5"/><circle cx="58" cy="110" r="5"/></g>
<g fill="var(--neuron)"><circle cx="50" cy="78" r="5"/><circle cx="126" cy="116" r="5"/><circle cx="202" cy="90" r="5"/><circle cx="278" cy="88" r="5"/></g></g></g></svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-basket-cell" title="Link to this term">Basket cell (BC)</a></h3>
    <p class="acg-def">A type of inhibitory neuron whose synaptic output targets the cell body and proximal dendrites of excitatory neurons. Many basket cells express the molecular marker parvalbumin (PV), but not all basket cells are PV+: some express molecules such as cholecystokinin (CCK). PV basket cells are typically fast spiking compared to other neurons and are thought to be important for gain control of network activity and setting the temporal precision of network activity.</p>
    </article>
    <article class="acg-card" id="term-bipolar-cell" data-cat="celltypes" data-hay="bipolar cell (bpc) a subset of vip cell with a bipolar dendritic arbor. see vip cell. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d-bipolar-cell"><title id="d-bipolar-cell">Bipolar cell</title><defs><clipPath id="d-bipolar-cell-c" clipPathUnits="userSpaceOnUse"><rect x="164" y="26" width="76" height="118"/></clipPath></defs><g transform="translate(160,100) scale(1.55) translate(-202,-88)"><g clip-path="url(#d-bipolar-cell-c)"><g stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round">
<path d="M50,73 V54 M50,73 l-9,-12 M50,73 l9,-12"/>
<path d="M126,121 V132 M126,121 l-8,9 M126,121 l8,9"/>
<path d="M202,85 V54 M202,54 l-5,-6 M202,54 l5,-6 M202,95 V128 M202,128 l-5,6 M202,128 l5,6"/>
</g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M50,83 V95 M50,95 C44,98 40,104 42,112 M50,95 C56,98 60,104 58,112"/>
<path d="M126,111 V54 M112,54 H140 M116,54 v-6 M126,54 v-6 M136,54 v-6"/>
<path d="M278,88 l0,-16 M278,88 l14,-8 M278,88 l16,0 M278,88 l14,8 M278,88 l0,16 M278,88 l-14,8 M278,88 l-16,0 M278,88 l-14,-8"/>
</g>
<g fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.6"><circle cx="42" cy="110" r="5"/><circle cx="58" cy="110" r="5"/></g>
<g fill="var(--neuron)"><circle cx="50" cy="78" r="5"/><circle cx="126" cy="116" r="5"/><circle cx="202" cy="90" r="5"/><circle cx="278" cy="88" r="5"/></g></g></g></svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-bipolar-cell" title="Link to this term">Bipolar cell (BPC)</a></h3>
    <p class="acg-def">A subset of VIP cell with a bipolar dendritic arbor. See VIP cell.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-bound-spatial-point" data-cat="tables" data-hay="bound spatial point binds an annotation to the cell at a location via the triad pt_position → pt_supervoxel_id → pt_root_id. annotation tables, ids &amp; queries ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="bsp-t">
<title id="bsp-t">Bound Spatial Point</title>
<circle cx="44" cy="100" r="9" fill="var(--accent)" fill-opacity=".18" stroke="var(--accent-ink)" stroke-width="2"/>
<line x1="44" y1="86" x2="44" y2="114" stroke="var(--accent-ink)" stroke-width="1.3" stroke-opacity=".7"/>
<line x1="30" y1="100" x2="58" y2="100" stroke="var(--accent-ink)" stroke-width="1.3" stroke-opacity=".7"/>
<circle cx="44" cy="100" r="2.6" fill="var(--accent-ink)"/>
<text x="44" y="132" text-anchor="middle" font-size="10" fill="var(--muted)">point</text>
<path d="M56,96 C100,80 118,57 148,57" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-linecap="round"/>
<path d="M58,100 L148,100" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-linecap="round"/>
<path d="M56,104 C100,120 118,143 148,143" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-linecap="round"/>
<rect x="150" y="42" width="146" height="30" rx="5" fill="var(--surface-2)" stroke="var(--border)" stroke-width="1.5"/>
<rect x="150" y="42" width="5" height="30" rx="2" fill="var(--accent)"/>
<text x="164" y="61" font-size="11" class="mono" fill="var(--muted)">pt_position</text>
<rect x="150" y="85" width="146" height="30" rx="5" fill="var(--surface-2)" stroke="var(--border)" stroke-width="1.5"/>
<rect x="150" y="85" width="5" height="30" rx="2" fill="var(--scaffold)"/>
<text x="164" y="104" font-size="11" class="mono" fill="var(--muted)">pt_supervoxel_id</text>
<rect x="150" y="128" width="146" height="30" rx="5" fill="var(--surface-2)" stroke="var(--border)" stroke-width="1.5"/>
<rect x="150" y="128" width="5" height="30" rx="2" fill="var(--neuron)"/>
<text x="164" y="147" font-size="11" class="mono" fill="var(--neuron)">pt_root_id</text>
</svg></div>
    <div class="acg-eb" style="color:#9333ea">TABLES</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-bound-spatial-point" title="Link to this term">Bound Spatial Point</a></h3>
    <p class="acg-def">Binds an annotation to the cell at a location via the triad <code>pt_position</code> → <code>pt_supervoxel_id</code> → <code>pt_root_id</code>.</p>
    </article>
    <article class="acg-card" id="term-bci" data-cat="stimuli" data-hay="brain computer interface (bci) a method of controlling a computer signal through the activity of a neuron. this can be extended to other types of devices (e.g. joysticks or robotic arms). this is also often referred to as &quot;brain machine interface&quot; stimuli &amp; behavioural tasks ">
    <div class="acg-eb" style="color:#a16207">STIMULUS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-bci" title="Link to this term">Brain Computer Interface (BCI)</a></h3>
    <p class="acg-def">A method of controlling a computer signal through the activity of a neuron. This can be extended to other types of devices (e.g. joysticks or robotic arms). This is also often referred to as "Brain Machine Interface"</p>
    </article>
    <article class="acg-card" id="term-branch-end-root-point" data-cat="morphology" data-hay="branch / end / root point named skeleton vertex types; the root is conventionally placed at the soma. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-brep"><title id="m-brep">Branch, end and root points on a skeleton</title><path d="M55,158 L82,120 M82,120 L64,88 L48,58 M64,88 L78,54 M82,120 L116,96 L104,60 M116,96 L140,66" fill="none" stroke="var(--neuron)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><circle cx="55" cy="158" r="11" fill="var(--neuron)" fill-opacity=".16" stroke="var(--neuron)" stroke-width="2"/><rect x="50" y="153" width="10" height="10" rx="1.5" fill="var(--neuron)" stroke="var(--surface)" stroke-width="1.5"/><g stroke="var(--surface)" stroke-width="1.5"><circle cx="82" cy="120" r="5" fill="var(--accent-ink)"/><circle cx="64" cy="88" r="5" fill="var(--accent-ink)"/><circle cx="116" cy="96" r="5" fill="var(--accent-ink)"/></g><g fill="none" stroke="currentColor" stroke-opacity=".8" stroke-width="2" stroke-linejoin="round"><path d="M48,53 L53,62 L43,62 Z"/><path d="M78,49 L83,58 L73,58 Z"/><path d="M104,55 L109,64 L99,64 Z"/><path d="M140,61 L145,70 L135,70 Z"/></g><text x="240" y="42" text-anchor="middle" font-size="9.5" class="mono" fill="var(--faint)">point type</text><rect x="207" y="54" width="10" height="10" rx="1.5" fill="var(--neuron)"/><text x="224" y="63" font-size="10" fill="var(--muted)">root (soma)</text><circle cx="212" cy="82" r="5" fill="var(--accent-ink)"/><text x="224" y="86" font-size="10" fill="var(--muted)">branch</text><path d="M212,100 L217,109 L207,109 Z" fill="none" stroke="currentColor" stroke-opacity=".8" stroke-width="2" stroke-linejoin="round"/><text x="224" y="108" font-size="10" fill="var(--muted)">end</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-branch-end-root-point" title="Link to this term">Branch / End / Root point</a></h3>
    <p class="acg-def">Named skeleton vertex types; the root is conventionally placed at the soma.</p>
    </article>
    <article class="acg-card" id="term-cave" data-cat="cave" data-hay="cave connectome annotation versioning engine — the suite managing large dynamic connectomics data. cave — access &amp; versioning ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="cave-hub"><title id="cave-hub">CAVE architecture hub</title>
<rect x="16" y="30" width="96" height="32" rx="6" fill="var(--scaffold)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".6" stroke-width="2"/>
<text x="64" y="50" text-anchor="middle" font-size="10" fill="var(--muted)">imagery</text>
<rect x="16" y="84" width="96" height="32" rx="6" fill="var(--neuron)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".6" stroke-width="2"/>
<text x="64" y="104" text-anchor="middle" font-size="10" fill="var(--muted)">segmentation</text>
<rect x="16" y="138" width="96" height="32" rx="6" fill="var(--synapse)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".6" stroke-width="2"/>
<text x="64" y="158" text-anchor="middle" font-size="10" fill="var(--muted)">annotation DB</text>
<path d="M112,46 C150,52 168,84 199,92" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/>
<path d="M112,100 L199,100" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/>
<path d="M112,154 C150,148 168,116 199,108" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/>
<polygon points="200,92 190,87 191,95" fill="currentColor" fill-opacity=".55"/>
<polygon points="200,100 190,95 190,105" fill="currentColor" fill-opacity=".55"/>
<polygon points="200,108 190,103 191,111" fill="currentColor" fill-opacity=".55"/>
<rect x="200" y="74" width="100" height="52" rx="10" fill="var(--surface-2)" stroke="var(--accent-ink)" stroke-width="2.6"/>
<text x="250" y="104" text-anchor="middle" font-size="13" class="mono" fill="var(--accent-ink)" font-weight="600">CAVEclient</text>
</svg></div>
    <div class="acg-eb" style="color:#0f766e">CAVE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-cave" title="Link to this term">CAVE</a></h3>
    <p class="acg-def">Connectome Annotation Versioning Engine — the suite managing large dynamic connectomics data.</p>
    </article>
    <article class="acg-card" id="term-cell-type" data-cat="celltypes" data-hay="cell type classification of a cell (e.g. 23p, bc) via several tables/methods, keyed on nucleus id. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ct-t"><title id="ct-t">Cell type dendrogram</title>
<text x="160" y="30" text-anchor="middle" font-size="11" fill="var(--muted)">all cells</text>
<path d="M160,36 V52 M60,52 H260 M60,52 V68 M160,52 V68 M260,52 V68" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<text x="60" y="84" text-anchor="middle" font-size="10.5" font-weight="600" fill="var(--neuron)">Excitatory</text>
<text x="160" y="84" text-anchor="middle" font-size="10.5" font-weight="600" fill="var(--dendrite)">Inhibitory</text>
<text x="260" y="84" text-anchor="middle" font-size="10.5" font-weight="600" fill="var(--scaffold)">Non-neuron</text>
<path d="M60,90 V110 M30,110 H90 M30,110 V122 M60,110 V122 M90,110 V122" fill="none" stroke="var(--neuron)" stroke-opacity=".85" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M160,90 V110 M135,110 H185 M135,110 V122 M160,110 V122 M185,110 V122" fill="none" stroke="var(--dendrite)" stroke-opacity=".85" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M260,90 V110 M230,110 H290 M230,110 V122 M260,110 V122 M290,110 V122" fill="none" stroke="var(--scaffold)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<g font-size="9.5" text-anchor="middle" class="mono" fill="var(--muted)">
<text x="30" y="136">IT</text><text x="60" y="136">ET</text><text x="90" y="136">CT</text>
<text x="135" y="136">Pv</text><text x="160" y="136">Sst</text><text x="185" y="136">Vip</text>
<text x="230" y="136">Ast</text><text x="260" y="136">Oli</text><text x="290" y="136">Mic</text>
</g>
</svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-cell-type" title="Link to this term">Cell type</a></h3>
    <p class="acg-def">Classification of a cell (e.g. 23P, BC) via several tables/methods, keyed on nucleus id.</p>
    </article>
    <article class="acg-card" id="term-chandelier-cell" data-cat="celltypes" data-hay="chandelier cell (chc) a parvalbumin interneuron that synapses exclusively onto the axon initial segments of pyramidal cells, placing it in unique control of whether they fire. its output forms vertical strings of boutons — the cartridges the cell is named for. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-chandelier-cell" title="Link to this term">Chandelier cell (ChC)</a></h3>
    <p class="acg-def">A parvalbumin interneuron that synapses exclusively onto the axon initial segments of pyramidal cells, placing it in unique control of whether they fire. Its output forms vertical strings of boutons — the cartridges the cell is named for.</p>
    </article>
    <article class="acg-card" id="term-channelrhodopsin" data-cat="genetics" data-hay="channelrhodopsin (chr2) a light-gated ion channel used in the field of optogenetics to control neuronal activity with light. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-channelrhodopsin" title="Link to this term">Channelrhodopsin (ChR2)</a></h3>
    <p class="acg-def">A light-gated ion channel used in the field of optogenetics to control neuronal activity with light.</p>
    </article>
    <article class="acg-card" id="term-column-microns" data-cat="datasets" data-hay="column (microns) a colloquial name for the 100 micron by 100 micron square column of cortex targeted for the census across layers. this column is a particularly well proofread collection of cells. datasets &amp; scope microns">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d1"><title id="d1">Column (MICrONS)</title><rect x="66" y="30" width="180" height="140" fill="var(--scaffold)" fill-opacity=".1" stroke="currentColor" stroke-opacity=".6" stroke-width="2"/><line x1="66" y1="48" x2="246" y2="48" stroke="currentColor" stroke-opacity=".35" stroke-width="1.3"/><line x1="66" y1="84" x2="246" y2="84" stroke="currentColor" stroke-opacity=".35" stroke-width="1.3"/><line x1="66" y1="106" x2="246" y2="106" stroke="currentColor" stroke-opacity=".35" stroke-width="1.3"/><line x1="66" y1="140" x2="246" y2="140" stroke="currentColor" stroke-opacity=".35" stroke-width="1.3"/><text x="60" y="42" text-anchor="end" font-size="9" fill="var(--faint)">L1</text><text x="60" y="69" text-anchor="end" font-size="9" fill="var(--faint)">L2/3</text><text x="60" y="99" text-anchor="end" font-size="9" fill="var(--faint)">L4</text><text x="60" y="126" text-anchor="end" font-size="9" fill="var(--faint)">L5</text><text x="60" y="158" text-anchor="end" font-size="9" fill="var(--faint)">L6</text><rect x="146" y="30" width="24" height="140" fill="var(--accent)" fill-opacity=".2" stroke="var(--accent-ink)" stroke-width="2"/><text x="70" y="24" text-anchor="start" font-size="9" fill="var(--muted)">pia</text><text x="70" y="184" text-anchor="start" font-size="9" fill="var(--muted)">white matter</text><line x1="158" y1="170" x2="158" y2="185" stroke="var(--accent-ink)" stroke-width="1.5"/><text x="155" y="196" text-anchor="end" font-size="9.5" class="mono" fill="var(--accent-ink)" font-weight="600">100 µm</text><text x="158" y="196" text-anchor="start" font-size="9.5" fill="var(--accent-ink)" font-weight="600"> census column</text></svg></div>
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-column-microns" title="Link to this term">Column (MICrONS)</a></h3>
    <p class="acg-def">A colloquial name for the 100 micron by 100 micron square column of cortex targeted for the census across layers. This column is a particularly well proofread collection of cells.</p>
    <div class="acg-meta"><span class="acg-chip acg-ds">MICrONS only</span><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-column-v1dd-field" data-cat="datasets" data-hay="column (v1dd field) a column field naming one of 5 stacked scan sub-volumes tiling the v1dd block — a different concept from the microns column. datasets &amp; scope v1dd">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d2"><title id="d2">Column (V1DD field)</title><text x="80" y="22" text-anchor="start" font-size="9" fill="var(--muted)">V1DD scan fields</text><polygon points="80,52 200,52 228,32 108,32" fill="var(--scaffold)" fill-opacity=".24" stroke="currentColor" stroke-opacity=".55" stroke-width="1.6"/><polygon points="200,52 228,32 228,158 200,178" fill="var(--scaffold)" fill-opacity=".08" stroke="currentColor" stroke-opacity=".55" stroke-width="1.6"/><rect x="80" y="52" width="120" height="25.2" fill="var(--accent)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.4"/><rect x="80" y="77.2" width="120" height="25.2" fill="var(--accent)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".5" stroke-width="1.4"/><rect x="80" y="102.4" width="120" height="25.2" fill="var(--accent)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.4"/><rect x="80" y="127.6" width="120" height="25.2" fill="var(--accent)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".5" stroke-width="1.4"/><rect x="80" y="152.8" width="120" height="25.2" fill="var(--accent)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.4"/><text x="140" y="68" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)" font-weight="600">1</text><text x="140" y="93.2" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)" font-weight="600">2</text><text x="140" y="118.4" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)" font-weight="600">3</text><text x="140" y="143.6" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)" font-weight="600">4</text><text x="140" y="168.8" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)" font-weight="600">5</text><text x="74" y="55" text-anchor="end" font-size="9" fill="var(--muted)">pia</text><text x="74" y="178" text-anchor="end" font-size="9" fill="var(--muted)">WM</text><text x="240" y="70" text-anchor="start" font-size="8.5" fill="var(--accent-ink)" font-weight="600">cf. MICrONS:</text><text x="240" y="82" text-anchor="start" font-size="8.5" fill="var(--muted)">samples one</text><text x="240" y="94" text-anchor="start" font-size="8.5" fill="var(--muted)">narrow 100 µm</text><text x="240" y="106" text-anchor="start" font-size="8.5" fill="var(--muted)">slab</text><text x="160" y="194" text-anchor="middle" font-size="9" fill="var(--muted)">5 sub-volumes tile the full depth</text></svg></div>
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-column-v1dd-field" title="Link to this term">Column (V1DD field)</a></h3>
    <p class="acg-def">A <code>column</code> field naming one of 5 stacked scan sub-volumes tiling the V1DD block — a different concept from the MICrONS column.</p>
    <div class="acg-meta"><span class="acg-chip acg-ds">V1DD only</span><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-ccf" data-cat="dataorg" data-hay="common coordinate framework (ccf) the ccf is a a standard 3d reference space for the mouse brain that enables spatial integration of data across modalities. datasets, sessions &amp; files ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ccf-t"><title id="ccf-t">Common Coordinate Framework: one reference space for every modality</title><clipPath id="clip-ccf"><path d="M126,52 C176,36 226,58 224,98 C222,138 178,158 148,146 C114,132 106,66 126,52"/></clipPath><path d="M126,52 C176,36 226,58 224,98 C222,138 178,158 148,146 C114,132 106,66 126,52" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".5" stroke-width="2"/><g clip-path="url(#clip-ccf)" stroke="currentColor" stroke-opacity=".22" stroke-width="1.1"><path d="M140,30 V160 M170,30 V160 M200,30 V160 M100,72 H240 M100,98 H240 M100,124 H240"/></g><path d="M30,58 h16 v52 l-8,10 l-8,-10 z" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".5" stroke-width="1.7" stroke-linejoin="round"/><path d="M33,68 h10 M33,80 h10 M33,92 h10" stroke="currentColor" stroke-opacity=".45" stroke-width="1.8"/><text x="38" y="140" text-anchor="middle" font-size="10" fill="var(--muted)">ephys</text><rect x="262" y="66" width="46" height="40" rx="4" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".5" stroke-width="1.7"/><g fill="var(--neuron)" fill-opacity=".5"><circle cx="275" cy="80" r="4"/><circle cx="292" cy="76" r="4"/><circle cx="286" cy="94" r="4"/></g><text x="285" y="140" text-anchor="middle" font-size="10" fill="var(--muted)">ophys</text><path d="M54,92 H96" stroke="currentColor" stroke-opacity=".5" stroke-width="1.8" stroke-linecap="round"/><polygon points="104,92 95,87 95,97" fill="currentColor" fill-opacity=".5"/><path d="M256,92 H236" stroke="currentColor" stroke-opacity=".5" stroke-width="1.8" stroke-linecap="round"/><polygon points="228,92 237,87 237,97" fill="currentColor" fill-opacity=".5"/><text x="166" y="176" text-anchor="middle" font-size="12" fill="var(--accent-ink)" font-weight="600">CCF</text><text x="166" y="192" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">[AP, DV, ML] µm</text></svg></div>
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-ccf" title="Link to this term">Common Coordinate Framework (CCF)</a></h3>
    <p class="acg-def">The CCF is a a standard 3D reference space for the mouse brain that enables spatial integration of data across modalities.</p>
    </article>
    <article class="acg-card" id="term-compartment-labels" data-cat="morphology" data-hay="compartment labels swc integer codes: 0 undefined, 1 soma, 2 axon, 3 basal dendrite, 4 apical dendrite. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-comp"><title id="m-comp">Skeleton colored by SWC compartment</title><path d="M90,101 C88,80 92,64 90,52 M90,60 C82,50 74,44 66,38 M90,58 C100,48 108,44 116,38" fill="none" stroke="var(--dendrite)" stroke-width="2.6" stroke-linecap="round"/><path d="M80,120 C64,130 56,140 46,152 M88,124 C86,142 78,150 68,160" fill="none" stroke="var(--dendrite)" stroke-width="2.2" stroke-linecap="round"/><path d="M101,120 C113,138 111,158 119,175 M108,150 C118,150 125,154 131,158" fill="none" stroke="var(--axon)" stroke-width="2.4" stroke-linecap="round"/><circle cx="90" cy="112" r="12" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2.2"/><text x="120" y="42" font-size="9" fill="var(--muted)">apical</text><text x="30" y="150" font-size="9" fill="var(--muted)">basal</text><circle cx="212" cy="66" r="5" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2"/><text x="226" y="70" font-size="10" fill="var(--muted)">soma</text><line x1="204" y1="92" x2="220" y2="92" stroke="var(--dendrite)" stroke-width="3.2" stroke-linecap="round"/><text x="226" y="96" font-size="10" fill="var(--muted)">dendrite</text><line x1="204" y1="116" x2="220" y2="116" stroke="var(--axon)" stroke-width="3.2" stroke-linecap="round"/><text x="226" y="120" font-size="10" fill="var(--muted)">axon</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-compartment-labels" title="Link to this term">Compartment labels</a></h3>
    <p class="acg-def">SWC integer codes: 0 undefined, 1 soma, 2 axon, 3 basal dendrite, 4 apical dendrite.</p>
    </article>
    <article class="acg-card" id="term-connectome" data-cat="datasets" data-hay="connectome a wiring map of neurons and the synaptic connections between them. datasets &amp; scope ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d3"><title id="d3">Connectome</title><g stroke="var(--axon)" stroke-width="2.2" stroke-linecap="round" fill="none"><line x1="93" y1="51.6" x2="192" y2="48.4"/><line x1="212.7" y1="58.5" x2="244.3" y2="101.5"/><line x1="240.8" y1="118.6" x2="179.2" y2="155.3"/><line x1="78.5" y1="135.7" x2="155.5" y2="158.3"/><line x1="77.8" y1="64.8" x2="68.2" y2="119.2"/><line x1="201" y1="60.4" x2="172" y2="149.6"/></g><g fill="var(--synapse)"><circle cx="192" cy="48.4" r="3.8"/><circle cx="244.3" cy="101.5" r="3.8"/><circle cx="179.2" cy="155.3" r="3.8"/><circle cx="155.5" cy="158.3" r="3.8"/><circle cx="68.2" cy="119.2" r="3.8"/><circle cx="172" cy="149.6" r="3.8"/></g><g fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.2"><circle cx="80" cy="52" r="13"/><circle cx="205" cy="48" r="13"/><circle cx="252" cy="112" r="13"/><circle cx="168" cy="162" r="13"/><circle cx="66" cy="132" r="13"/></g><circle cx="30" cy="180" r="3.8" fill="var(--synapse)"/><text x="39" y="183" font-size="9" fill="var(--muted)">synapse</text><line x1="96" y1="180" x2="118" y2="180" stroke="var(--axon)" stroke-width="2.2" stroke-linecap="round"/><text x="124" y="183" font-size="9" fill="var(--muted)">directed edge</text><circle cx="214" cy="180" r="6" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2"/><text x="224" y="183" font-size="9" fill="var(--muted)">neuron</text></svg></div>
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-connectome" title="Link to this term">Connectome</a></h3>
    <p class="acg-def">A wiring map of neurons and the synaptic connections between them.</p>
    </article>
    <article class="acg-card" id="term-container" data-cat="dataorg" data-hay="container there is no consistent use of this term most often this refers to the set of recording sessions for a single ophys imaging plane, but can also refer to the set of sessions for an animal. datasets, sessions &amp; files ">
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-container" title="Link to this term">Container</a></h3>
    <p class="acg-def"><i>There is no consistent use of this term</i> Most often this refers to the set of recording sessions for a single ophys imaging plane, but can also refer to the set of sessions for an animal.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-coordinate-frames" data-cat="volume" data-hay="coordinate frames three systems: voxel (annotations), nanometer (mesh/skeleton vertices), transformed (pia-flattened microns). volume, voxels &amp; coordinates ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="cf-t"><title id="cf-t">Coordinate frames: voxel, nanometer, pia-flattened</title><path d="M80,104 C102,74 128,74 148,104" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/><path d="M141,100 L148,104 L149,96" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><text x="114" y="68" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">x [4,4,40] nm</text><path d="M186,104 C208,74 234,74 256,104" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/><path d="M249,100 L256,104 L257,96" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><text x="221" y="68" text-anchor="middle" font-size="10.5" fill="var(--muted)">transform</text><g stroke="currentColor" stroke-opacity=".85" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"><path d="M52,118 H76"/><path d="M70,114 L76,118 L70,122"/><path d="M52,118 V142"/><path d="M48,136 L52,142 L56,136"/><path d="M52,118 L34,100"/><path d="M42,102 L34,100 L36,108"/></g><text x="80" y="122" font-size="10" class="mono" fill="var(--faint)">x</text><text x="44" y="153" font-size="10" class="mono" fill="var(--faint)">y</text><text x="26" y="98" font-size="10" class="mono" fill="var(--faint)">z</text><g stroke="currentColor" stroke-opacity=".85" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"><path d="M158,118 H182"/><path d="M176,114 L182,118 L176,122"/><path d="M158,118 V142"/><path d="M154,136 L158,142 L162,136"/><path d="M158,118 L140,100"/><path d="M148,102 L140,100 L142,108"/></g><text x="186" y="122" font-size="10" class="mono" fill="var(--faint)">x</text><text x="150" y="153" font-size="10" class="mono" fill="var(--faint)">y</text><text x="132" y="98" font-size="10" class="mono" fill="var(--faint)">z</text><g stroke="currentColor" stroke-opacity=".85" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"><path d="M262,118 H286"/><path d="M280,114 L286,118 L280,122"/><path d="M262,118 V94"/><path d="M258,100 L262,94 L266,100"/><path d="M262,118 L244,100"/><path d="M252,102 L244,100 L246,108"/></g><text x="290" y="122" font-size="10" class="mono" fill="var(--faint)">x</text><text x="250" y="90" font-size="10" class="mono" fill="var(--faint)">y</text><text x="236" y="98" font-size="10" class="mono" fill="var(--faint)">z</text><text x="52" y="168" text-anchor="middle" font-size="11" fill="var(--muted)">voxel</text><text x="158" y="168" text-anchor="middle" font-size="11" fill="var(--muted)">nm</text><text x="262" y="168" text-anchor="middle" font-size="11" fill="var(--accent-ink)" font-weight="600">pia-flat</text><text x="52" y="184" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">[i,j,k]</text><text x="158" y="184" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">[x,y,z]</text><text x="262" y="184" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">[u,v,d]</text></svg></div>
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-coordinate-frames" title="Link to this term">Coordinate frames</a></h3>
    <p class="acg-def">Three systems: voxel (annotations), nanometer (mesh/skeleton vertices), transformed (pia-flattened microns).</p>
    </article>
    <article class="acg-card" id="term-coregistration" data-cat="functional" data-hay="coregistration aligning functionally-imaged cells to the same cells in the em volume (manual + automatic). functional data &amp; coregistration ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="coreg-t"><title id="coreg-t">Coregistration</title><circle cx="70" cy="98" r="30" fill="var(--accent)" fill-opacity=".15" stroke="var(--accent)" stroke-width="2.4"/><path d="M50,100 h7 l4,-14 5,26 4,-16 3,6 h7" fill="none" stroke="var(--accent)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><text x="70" y="150" text-anchor="middle" font-size="10.5" fill="var(--muted)">calcium ROI</text><polygon points="272,74 294,90 286,116 258,116 250,90" fill="var(--neuron)" fill-opacity=".15" stroke="var(--neuron)" stroke-width="2.4" stroke-linejoin="round"/><path d="M272,74 L272,58" stroke="var(--dendrite)" stroke-width="2.2" stroke-linecap="round"/><circle cx="272" cy="97" r="4" fill="var(--neuron)"/><text x="272" y="150" text-anchor="middle" font-size="10.5" fill="var(--muted)">EM soma</text><line x1="102" y1="98" x2="242" y2="98" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-dasharray="6 5" stroke-linecap="round"/><text x="172" y="90" text-anchor="middle" font-size="10.5" class="mono" fill="var(--accent-ink)">match</text><circle cx="172" cy="116" r="13" fill="var(--surface)" stroke="var(--ok)" stroke-width="2.4"/><path d="M165,116 l5,5 8,-10" fill="none" stroke="var(--ok)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><text x="172" y="146" text-anchor="middle" font-size="9" fill="var(--ok)">agree</text></svg></div>
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-coregistration" title="Link to this term">Coregistration</a></h3>
    <p class="acg-def">Aligning functionally-imaged cells to the same cells in the EM volume (manual + automatic).</p>
    </article>
    <article class="acg-card" id="term-cover-paths" data-cat="morphology" data-hay="cover paths a decomposition of a skeleton into non-overlapping paths, each running from an end point toward the root until it meets a vertex already covered. every vertex belongs to exactly one, which makes them the right primitive for plotting or walking a neuron. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-cover-paths" title="Link to this term">Cover paths</a></h3>
    <p class="acg-def">A decomposition of a skeleton into non-overlapping paths, each running from an end point toward the root until it meets a vertex already covered. Every vertex belongs to exactly one, which makes them the right primitive for plotting or walking a neuron.</p>
    <div class="acg-meta"><a class="acg-chip acg-src" href="https://alleninstitute.github.io/microns_tutorial/" target="_blank" rel="noopener">MICrONS tutorial &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-cre-line" data-cat="genetics" data-hay="cre line the cre-lox system is a site-specific recombinase technology. cre-recombinase is a tyrosine site-specific recombinase that catalyzes the recombination of dna between specific sites known as loxp sequences. as used in these experiments, cre is used with loxp reporter line in order to drive recombinase of the loxp sites and drive the expression of the reporter. as cre is often expressed within a specific gene, this allows the reporter expression to be restricted to particular subset of cells. for specific lines used, see the section on transgenic tools. genetic &amp; optical tools ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="cre-t"><title id="cre-t">Cre line drives a loxP reporter</title> <g stroke="currentColor" stroke-opacity=".45" stroke-width="2" stroke-linecap="round"><path d="M20,58 H300"/><path d="M20,138 H300"/></g> <g fill="var(--accent)" fill-opacity=".35" stroke="var(--accent)" stroke-width="1.6" stroke-linejoin="round"> <polygon points="86,50 100,58 86,66"/><polygon points="176,50 190,58 176,66"/><polygon points="130,130 144,138 130,146"/></g> <g fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".5" stroke-width="1.8"> <rect x="106" y="46" width="64" height="24" rx="4"/><rect x="200" y="46" width="80" height="24" rx="4"/></g> <g text-anchor="middle" font-size="10" class="mono" fill="var(--muted)"> <text x="138" y="63">STOP</text><text x="240" y="63">reporter</text></g> <g text-anchor="middle" font-size="9" class="mono" fill="var(--faint)"> <text x="93" y="38">loxP</text><text x="183" y="38">loxP</text></g> <path d="M138,80 V104" stroke="var(--accent)" stroke-width="2" stroke-linecap="round"/> <polygon points="138,110 133,101 143,101" fill="var(--accent)"/> <text x="152" y="98" font-size="11" fill="var(--accent-ink)" font-weight="600">Cre</text> <rect x="200" y="126" width="80" height="24" rx="4" fill="var(--accent)" fill-opacity=".2" stroke="var(--accent)" stroke-width="2.2"/> <text x="240" y="143" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)" font-weight="600">reporter</text> <text x="88" y="143" text-anchor="middle" font-size="9" fill="var(--faint)">STOP excised</text> <text x="160" y="178" text-anchor="middle" font-size="9.5" fill="var(--muted)">only in Cre+ cells</text> </svg></div>
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-cre-line" title="Link to this term">Cre line</a></h3>
    <p class="acg-def">The Cre-lox system is a site-specific recombinase technology. Cre-recombinase is a tyrosine site-specific recombinase that catalyzes the recombination of DNA between specific sites known as <b>loxP</b> sequences. As used in these experiments, Cre is used with loxP Reporter line in order to drive recombinase of the loxP sites and drive the expression of the reporter. As Cre is often expressed within a specific gene, this allows the reporter expression to be restricted to particular subset of cells. For specific lines used, see the section on transgenic tools.</p>
    </article>
    <article class="acg-card" id="term-dataset" data-cat="dataorg" data-hay="dataset there is no consistent use of this term datasets, sessions &amp; files ">
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-dataset" title="Link to this term">Dataset</a></h3>
    <p class="acg-def"><i>There is no consistent use of this term</i></p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-datastack" data-cat="cave" data-hay="datastack a named bundle of imagery + segmentation + annotation db (minnie65_public, v1dd_public). cave — access &amp; versioning ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="cave-ds"><title id="cave-ds">Datastack</title>
<polygon points="62,58 182,58 208,44 88,44" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linejoin="round"/>
<polygon points="182,58 208,44 208,66 182,80" fill="var(--scaffold)" fill-opacity=".1" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linejoin="round"/>
<rect x="62" y="58" width="120" height="22" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<text x="122" y="73" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">imagery</text>
<polygon points="62,96 182,96 208,82 88,82" fill="var(--neuron)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linejoin="round"/>
<polygon points="182,96 208,82 208,104 182,118" fill="var(--neuron)" fill-opacity=".1" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linejoin="round"/>
<rect x="62" y="96" width="120" height="22" fill="var(--neuron)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<text x="122" y="111" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">segmentation</text>
<polygon points="62,134 182,134 208,120 88,120" fill="var(--synapse)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linejoin="round"/>
<polygon points="182,134 208,120 208,142 182,156" fill="var(--synapse)" fill-opacity=".1" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linejoin="round"/>
<rect x="62" y="134" width="120" height="22" fill="var(--synapse)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<text x="122" y="149" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">annotations</text>
<path d="M222,44 H234 V156 H222" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<text transform="translate(252,100) rotate(-90)" text-anchor="middle" font-size="12" class="mono" fill="var(--accent-ink)" font-weight="600">datastack</text>
</svg></div>
    <div class="acg-eb" style="color:#0f766e">CAVE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-datastack" title="Link to this term">Datastack</a></h3>
    <p class="acg-def">A named bundle of imagery + segmentation + annotation DB (<code>minnie65_public</code>, <code>v1dd_public</code>).</p>
    </article>
    <article class="acg-card" id="term-dendritic-spine" data-cat="morphology" data-hay="dendritic spine the small protrusion on a dendrite that receives most excitatory input, with a bulbous head on a thin neck. spine density separates excitatory from inhibitory dendrites, and spine heads are among the fragments most often left disconnected by automated segmentation. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-dendritic-spine" title="Link to this term">Dendritic spine</a></h3>
    <p class="acg-def">The small protrusion on a dendrite that receives most excitatory input, with a bulbous head on a thin neck. Spine density separates excitatory from inhibitory dendrites, and spine heads are among the fragments most often left disconnected by automated segmentation.</p>
    </article>
    <article class="acg-card" id="term-depth-pia-wm-axis" data-cat="volume" data-hay="depth / pia→wm axis y increases with cortical depth, so depth plots need ax.invert_yaxis(). volume, voxels &amp; coordinates ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="depth-t"><title id="depth-t">Depth axis: pia at top, white matter at bottom, y increases downward</title><rect x="118" y="32" width="46" height="140" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".6" stroke-width="2"/><g stroke="currentColor" stroke-opacity=".25" stroke-width="1.5"><path d="M118,62 H164"/><path d="M118,92 H164"/><path d="M118,122 H164"/><path d="M118,152 H164"/></g><text x="141" y="26" text-anchor="middle" font-size="11" fill="var(--muted)">pia</text><text x="141" y="186" text-anchor="middle" font-size="11" fill="var(--muted)">white matter</text><path d="M90,32 V170" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"/><path d="M84,162 L90,172 L96,162" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><text x="76" y="30" font-size="10" class="mono" fill="var(--muted)">0</text><text transform="translate(70,102) rotate(-90)" text-anchor="middle" font-size="12" class="mono" fill="var(--accent-ink)" font-weight="600">+y</text><text x="180" y="96" font-size="10.5" fill="var(--muted)">y increases</text><text x="180" y="110" font-size="10.5" fill="var(--muted)">downward</text><text x="180" y="130" font-size="10" class="mono" fill="var(--faint)">invert_yaxis</text></svg></div>
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-depth-pia-wm-axis" title="Link to this term">Depth / pia→WM axis</a></h3>
    <p class="acg-def">y increases with cortical depth, so depth plots need <code>ax.invert_yaxis()</code>.</p>
    </article>
    <article class="acg-card" id="term-digital-twin" data-cat="functional" data-hay="digital twin a dnn trained to predict a cell's response to arbitrary stimuli (source of derived functional properties). functional data &amp; coregistration ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="dtwin-t"><title id="dtwin-t">Digital twin</title><rect x="22" y="70" width="54" height="54" rx="6" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/><path d="M33,74 v46 M45,74 v46 M57,74 v46 M69,74 v46" stroke="currentColor" stroke-opacity=".45" stroke-width="4"/><text x="49" y="150" text-anchor="middle" font-size="10.5" fill="var(--muted)">stimulus</text><line x1="80" y1="97" x2="110" y2="97" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/><polygon points="116,97 108,93 108,101" fill="currentColor" fill-opacity=".6"/><rect x="120" y="62" width="82" height="70" rx="9" fill="var(--surface-2)" stroke="var(--accent)" stroke-width="2.4"/><rect x="132" y="76" width="12" height="42" rx="4" fill="var(--accent)" fill-opacity=".8"/><rect x="155" y="76" width="12" height="42" rx="4" fill="var(--accent)" fill-opacity=".5"/><rect x="178" y="76" width="12" height="42" rx="4" fill="var(--accent)" fill-opacity=".3"/><text x="161" y="150" text-anchor="middle" font-size="11" class="mono" fill="var(--accent-ink)" font-weight="600">DNN</text><line x1="206" y1="97" x2="234" y2="97" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/><polygon points="240,97 232,93 232,101" fill="currentColor" fill-opacity=".6"/><line x1="246" y1="118" x2="246" y2="72" stroke="currentColor" stroke-opacity=".35" stroke-width="1.6"/><line x1="246" y1="118" x2="302" y2="118" stroke="currentColor" stroke-opacity=".35" stroke-width="1.6"/><path d="M248,116 L262,116 C268,116 267,80 274,80 C281,80 280,116 288,116 L300,116" fill="none" stroke="var(--neuron)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><text x="274" y="150" text-anchor="middle" font-size="10" fill="var(--muted)">predicted</text><text x="274" y="163" text-anchor="middle" font-size="10" fill="var(--muted)">response</text></svg></div>
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-digital-twin" title="Link to this term">Digital twin</a></h3>
    <p class="acg-def">A DNN trained to predict a cell's response to arbitrary stimuli (source of derived functional properties).</p>
    </article>
    <article class="acg-card" id="term-driver-line" data-cat="genetics" data-hay="driver line a general term for transgenic mouse lines that are engineered to label a specific cell type or cell population by expressing a specific gene under the control of the promoter for the cell type or cell population of interest. a cre line is a common type of driver line that allows specific genes to be expressed when crossed with a reporter line. the driver line determines what cell population is targeted, and the reporter line determines what will be expressed in that specific cell population (for example, gfp, gcamp, or channelrhodopsin). genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-driver-line" title="Link to this term">Driver line</a></h3>
    <p class="acg-def">A general term for transgenic mouse lines that are engineered to label a specific cell type or cell population by expressing a specific gene under the control of the promoter for the cell type or cell population of interest. A Cre line is a common type of Driver line that allows specific genes to be expressed when crossed with a reporter line. The driver line determines what cell population is targeted, and the reporter line determines what will be expressed in that specific cell population (for example, GFP, GCaMP, or Channelrhodopsin).</p>
    </article>
    <article class="acg-card" id="term-dsi" data-cat="functional" data-hay="dsi direction selectivity index (0–1). functional data &amp; coregistration ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="dsi-t"><title id="dsi-t">DSI</title><circle cx="176" cy="100" r="70" fill="none" stroke="currentColor" stroke-opacity=".2" stroke-width="1.4"/><circle cx="176" cy="100" r="46" fill="none" stroke="currentColor" stroke-opacity=".2" stroke-width="1.4"/><circle cx="176" cy="100" r="22" fill="none" stroke="currentColor" stroke-opacity=".2" stroke-width="1.4"/><line x1="102" y1="100" x2="250" y2="100" stroke="currentColor" stroke-opacity=".28" stroke-width="1.4"/><line x1="176" y1="26" x2="176" y2="174" stroke="currentColor" stroke-opacity=".28" stroke-width="1.4"/><path d="M176,100 C186,62 232,60 238,100 C232,140 186,138 176,100 Z" fill="var(--accent)" fill-opacity=".2" stroke="var(--accent)" stroke-width="2.4" stroke-linejoin="round"/><path d="M176,100 C173,88 154,86 148,100 C154,114 173,112 176,100 Z" fill="var(--accent)" fill-opacity=".12" stroke="var(--accent)" stroke-width="2" stroke-linejoin="round"/><text x="20" y="30" font-size="14" class="mono" fill="var(--accent-ink)" font-weight="600">DSI</text><text x="176" y="192" text-anchor="middle" font-size="10" fill="var(--muted)">one dominant direction</text></svg></div>
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-dsi" title="Link to this term">DSI</a></h3>
    <p class="acg-def">Direction selectivity index (0–1).</p>
    </article>
    <article class="acg-card" id="term-edges" data-cat="morphology" data-hay="edges pairs of connected vertices (mesh.edges, skeleton edges). morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-edge"><title id="m-edge">One highlighted edge between adjacent vertices</title><g fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="1.8" stroke-linecap="round"><path d="M58,150 L100,122"/><path d="M100,122 L150,132"/><path d="M150,132 L188,96"/><path d="M188,96 L140,80"/><path d="M140,80 L96,70"/><path d="M96,70 L52,96"/><path d="M52,96 L58,150"/></g><line x1="100" y1="122" x2="96" y2="70" stroke="var(--accent)" stroke-width="3.4" stroke-linecap="round"/><g fill="currentColor" fill-opacity=".55"><circle cx="58" cy="150" r="3.6"/><circle cx="150" cy="132" r="3.6"/><circle cx="188" cy="96" r="3.6"/><circle cx="140" cy="80" r="3.6"/><circle cx="52" cy="96" r="3.6"/></g><circle cx="100" cy="122" r="5" fill="var(--accent)" stroke="var(--surface)" stroke-width="1.5"/><circle cx="96" cy="70" r="5" fill="var(--accent)" stroke="var(--surface)" stroke-width="1.5"/><line x1="98" y1="96" x2="128" y2="90" stroke="var(--accent-ink)" stroke-width="1.5"/><text x="132" y="94" font-size="11" fill="var(--accent-ink)" font-weight="600">edge</text><text x="156" y="140" font-size="9.5" fill="var(--muted)">vertex</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-edges" title="Link to this term">Edges</a></h3>
    <p class="acg-def">Pairs of connected vertices (<code>mesh.edges</code>, skeleton <code>edges</code>).</p>
    </article>
    <article class="acg-card" id="term-electron-microscopy-em" data-cat="imaging" data-hay="electron microscopy (em) imaging that reaches nanometer resolution to reveal tissue ultrastructure. imaging &amp; ultrastructure ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="em-t"><title id="em-t">Electron microscopy (EM)</title>
<rect x="58" y="20" width="40" height="15" rx="2" fill="var(--accent)" fill-opacity=".18" stroke="var(--accent-ink)" stroke-width="2" stroke-linejoin="round"/>
<text x="78" y="15" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)">e⁻ beam</text>
<path d="M62,35 L78,106 L94,35 Z" fill="var(--accent)" fill-opacity=".12"/>
<line x1="62" y1="35" x2="78" y2="107" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<line x1="94" y1="35" x2="78" y2="107" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<line x1="78" y1="38" x2="78" y2="100" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round" stroke-dasharray="3 4"/>
<polygon points="52,108 104,108 118,100 66,100" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="52,108 104,108 104,118 52,118" fill="var(--scaffold)" fill-opacity=".15" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8" stroke-linejoin="round"/>
<text x="72" y="136" text-anchor="middle" font-size="10" fill="var(--muted)">thin section</text>
<line x1="132" y1="112" x2="194" y2="112" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/>
<path d="M194,112 l-8,-4 M194,112 l-8,4" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/>
<rect x="204" y="66" width="90" height="84" rx="3" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".7" stroke-width="2"/>
<ellipse cx="232" cy="98" rx="18" ry="12" fill="var(--scaffold)" fill-opacity=".38"/>
<circle cx="268" cy="90" r="9" fill="var(--scaffold)" fill-opacity=".5"/>
<path d="M214,128 q20,-12 40,-2 t38,-2" fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="2" stroke-linecap="round"/>
<circle cx="256" cy="122" r="4" fill="var(--scaffold)" fill-opacity=".6"/>
<text x="249" y="164" text-anchor="middle" font-size="10" fill="var(--muted)">grayscale tile</text>
</svg></div>
    <div class="acg-eb" style="color:#8a6f4a">IMAGING</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-electron-microscopy-em" title="Link to this term">Electron microscopy (EM)</a></h3>
    <p class="acg-def">Imaging that reaches nanometer resolution to reveal tissue ultrastructure.</p>
    </article>
    <article class="acg-card" id="term-ephys" data-cat="modalities" data-hay="ephys shorthand for electrophysiology. recording modalities &amp; instruments ">
    <div class="acg-eb" style="color:#c2410c">MODALITY</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-ephys" title="Link to this term">Ephys</a></h3>
    <p class="acg-def">Shorthand for electrophysiology.</p>
    </article>
    <article class="acg-card" id="term-excitatory-v1-cell-types" data-cat="celltypes" data-hay="excitatory v1 cell types pyramidal subclasses by layer/projection: 23p, 4p, 5p-it/et/np, 6p-it/ct (+ mtype clusters l2a…l6wm). cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ev-t"><title id="ev-t">Excitatory V1 cell types by layer</title>
<g stroke="none">
<rect x="34" y="18" width="272" height="18" fill="currentColor" fill-opacity=".05"/>
<rect x="34" y="36" width="272" height="38" fill="currentColor" fill-opacity=".09"/>
<rect x="34" y="74" width="272" height="26" fill="currentColor" fill-opacity=".05"/>
<rect x="34" y="100" width="272" height="40" fill="currentColor" fill-opacity=".09"/>
<rect x="34" y="140" width="272" height="32" fill="currentColor" fill-opacity=".05"/>
<rect x="34" y="172" width="272" height="14" fill="currentColor" fill-opacity=".16"/>
</g>
<path d="M34,18 H306 M34,36 H306 M34,74 H306 M34,100 H306 M34,140 H306 M34,172 H306 M34,186 H306" stroke="currentColor" stroke-opacity=".28" stroke-width="1.2"/>
<g class="mono" font-size="8.5" fill="var(--muted)">
<text x="16" y="30">L1</text><text x="16" y="59">L2/3</text><text x="16" y="90">L4</text><text x="16" y="123">L5</text><text x="16" y="159">L6</text><text x="16" y="182">WM</text>
</g>
<g stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M95,55 V32 M95,32 l-7,-6 M95,32 l7,-6 M86,70 l-7,7 M104,70 l7,7"/>
<path d="M150,80 V32 M150,32 l-7,-6 M150,32 l7,-6 M141,95 l-7,7 M159,95 l7,7"/>
<path d="M205,110 V32 M205,32 l-8,-7 M205,32 l8,-7 M194,127 l-8,8 M216,127 l8,8"/>
<path d="M260,148 V80 M260,80 l-7,-6 M260,80 l7,-6 M251,162 l-7,7 M269,162 l7,7"/>
</g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round">
<path d="M95,70 V82"/><path d="M150,95 V108"/><path d="M205,127 V145"/><path d="M260,162 V176"/>
</g>
<g fill="var(--neuron)" stroke="var(--surface)" stroke-width="1.2" stroke-linejoin="round">
<polygon points="95,53 86,70 104,70"/>
<polygon points="150,78 141,95 159,95"/>
<polygon points="205,107 194,127 216,127"/>
<polygon points="260,146 251,162 269,162"/>
</g>
<g class="mono" font-size="10" font-weight="600" fill="var(--neuron)">
<text x="112" y="64">23P</text><text x="166" y="90">4P</text><text x="222" y="121">5P</text><text x="277" y="157">6P</text>
</g>
</svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-excitatory-v1-cell-types" title="Link to this term">Excitatory V1 cell types</a></h3>
    <p class="acg-def">Pyramidal subclasses by layer/projection: 23P, 4P, 5P-IT/ET/NP, 6P-IT/CT (+ mtype clusters L2a…L6wm).</p>
    </article>
    <article class="acg-card" id="term-experiment" data-cat="dataorg" data-hay="experiment there is no consistent use of this term it can refer to a stimulus protocol, an entire data collection campaign, or a single session. it is highly ambiguous. datasets, sessions &amp; files ">
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-experiment" title="Link to this term">Experiment</a></h3>
    <p class="acg-def"><i>There is no consistent use of this term</i> It can refer to a stimulus protocol, an entire data collection campaign, or a single session. It is highly ambiguous.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-faces" data-cat="morphology" data-hay="faces triangles of connected vertex indices that tile a mesh surface (mesh.faces). morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-face"><title id="m-face">One triangular face highlighted in a mesh patch</title><polygon points="130,50 190,58 120,105" fill="var(--accent)" fill-opacity=".28" stroke="var(--accent-ink)" stroke-width="2.4" stroke-linejoin="round"/><g fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M70,60 L130,50 L190,58 L245,52"/><path d="M60,110 L120,105 L180,108 L240,102"/><path d="M75,155 L135,150 L195,152 L250,148"/><path d="M70,60 L60,110 M130,50 L120,105 M190,58 L180,108 M245,52 L240,102"/><path d="M60,110 L75,155 M120,105 L135,150 M180,108 L195,152 M240,102 L250,148"/><path d="M130,50 L60,110 M190,58 L120,105 M245,52 L180,108"/><path d="M120,105 L75,155 M180,108 L135,150 M240,102 L195,152"/></g><line x1="150" y1="72" x2="175" y2="52" stroke="var(--accent-ink)" stroke-width="1.5"/><text x="178" y="50" font-size="10.5" fill="var(--accent-ink)" font-weight="600">1 face</text><text x="160" y="188" text-anchor="middle" font-size="9.5" fill="var(--muted)">triangle = 3 vertices + 3 edges</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-faces" title="Link to this term">Faces</a></h3>
    <p class="acg-def">Triangles of connected vertex indices that tile a mesh surface (<code>mesh.faces</code>).</p>
    </article>
    <article class="acg-card" id="term-fast-spiking-neuron" data-cat="celltypes" data-hay="fast spiking neuron (fsn) fast spiking neurons are so called because of their &quot;narrow,&quot; fast action potentials, specifically as seen in intracellular recordings of a cell in response to a prolonged step of current. additionally, with sufficient current injection fast spiking neurons exhibit fast spike rates, and do not show frequency adaptation, or slowing of spike rates, over time. in unlabeled extracellular recordings, units with narrow action potentials are also referred to as fast spiking neurons. this feature is sometimes used to putatively label neurons with narrow spikes as particular cell types, such as pv+ neurons, among others. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="fsn-t"><title id="fsn-t">Fast spiking narrow waveform versus broad waveform</title> <path d="M20,74 L46,74 L52,50 L60,108 L70,70 L86,74 L120,74" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/> <path d="M20,74 L46,74 L54,54 L66,110 L92,66 L110,74 L140,74" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/> <path d="M60,124 H92" stroke="currentColor" stroke-opacity=".35" stroke-width="1.4"/> <path d="M60,120 V128 M92,120 V128" stroke="currentColor" stroke-opacity=".35" stroke-width="1.4"/> <text x="76" y="140" text-anchor="middle" font-size="9" fill="var(--faint)">width</text> <text x="150" y="46" font-size="10.5" fill="var(--accent-ink)" font-weight="600">narrow</text> <text x="150" y="60" font-size="9" fill="var(--faint)">putative PV+</text> <text x="150" y="86" font-size="10.5" fill="var(--muted)">broad</text> <g stroke="var(--accent)" stroke-width="2" stroke-linecap="round"> <path d="M22,178 V152"/><path d="M34,178 V152"/><path d="M46,178 V152"/><path d="M58,178 V152"/><path d="M70,178 V152"/><path d="M82,178 V152"/><path d="M94,178 V152"/><path d="M106,178 V152"/><path d="M118,178 V152"/><path d="M130,178 V152"/></g> <text x="150" y="164" font-size="9.5" fill="var(--muted)">high rate</text> <text x="150" y="178" font-size="9.5" fill="var(--muted)">no adaptation</text> </svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-fast-spiking-neuron" title="Link to this term">Fast spiking neuron (FSN)</a></h3>
    <p class="acg-def">Fast spiking neurons are so called because of their "narrow," fast action potentials, specifically as seen in intracellular recordings of a cell in response to a prolonged step of current. Additionally, with sufficient current injection fast spiking neurons exhibit fast spike rates, and do not show frequency adaptation, or slowing of spike rates, over time. In unlabeled extracellular recordings, units with narrow action potentials are also referred to as fast spiking neurons. This feature is sometimes used to putatively label neurons with narrow spikes as particular cell types, such as PV+ neurons, among others.</p>
    </article>
    <article class="acg-card" id="term-fibsem" data-cat="imaging" data-hay="fibsem focused-ion-beam sem; block-face em that mills &amp; images, giving near-isotropic voxels. imaging &amp; ultrastructure ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="fib-t"><title id="fib-t">FIBSEM vs serial-section TEM</title>
<line x1="158" y1="36" x2="158" y2="158" stroke="currentColor" stroke-opacity=".3" stroke-width="1.5" stroke-dasharray="3 5"/>
<text x="78" y="28" text-anchor="middle" font-size="11" class="mono" fill="var(--accent-ink)" font-weight="600">FIB-SEM</text>
<polygon points="44,82 96,82 110,70 58,70" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="44,82 96,82 96,132 44,132" fill="var(--scaffold)" fill-opacity=".2" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="96,82 110,70 110,120 96,132" fill="var(--scaffold)" fill-opacity=".12" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="44,82 96,82 100,78 48,78" fill="var(--accent)" fill-opacity=".4" stroke="var(--accent-ink)" stroke-width="1.5" stroke-linejoin="round"/>
<line x1="138" y1="46" x2="82" y2="78" stroke="var(--accent-ink)" stroke-width="2.2" stroke-linecap="round"/>
<path d="M82,78 l10,-1 M82,78 l3,-9" fill="none" stroke="var(--accent-ink)" stroke-width="2.2" stroke-linecap="round"/>
<text x="138" y="42" text-anchor="middle" font-size="9.5" fill="var(--accent-ink)">ion beam</text>
<text x="78" y="152" text-anchor="middle" font-size="9.5" fill="var(--muted)">mill block face in situ</text>
<text x="234" y="28" text-anchor="middle" font-size="11" class="mono" fill="var(--accent-ink)" font-weight="600">ssTEM</text>
<polygon points="176,86 210,86 222,76 188,76" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="176,86 210,86 210,128 176,128" fill="var(--scaffold)" fill-opacity=".2" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="210,86 222,76 222,118 210,128" fill="var(--scaffold)" fill-opacity=".12" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<line x1="216" y1="104" x2="232" y2="104" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/>
<path d="M232,104 l-7,-3 M232,104 l-7,3" fill="none" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/>
<polygon points="236,92 280,92 288,86 244,86" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".5" stroke-width="1.5" stroke-linejoin="round"/>
<polygon points="236,92 280,92 280,99 236,99" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".5" stroke-width="1.5" stroke-linejoin="round"/>
<polygon points="236,106 280,106 288,100 244,100" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".5" stroke-width="1.5" stroke-linejoin="round"/>
<polygon points="236,106 280,106 280,113 236,113" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".5" stroke-width="1.5" stroke-linejoin="round"/>
<polygon points="236,120 280,120 288,114 244,114" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".5" stroke-width="1.5" stroke-linejoin="round"/>
<polygon points="236,120 280,120 280,127 236,127" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".5" stroke-width="1.5" stroke-linejoin="round"/>
<text x="234" y="152" text-anchor="middle" font-size="9.5" fill="var(--muted)">collect serial sections</text>
<text x="160" y="184" text-anchor="middle" font-size="9.5" fill="var(--faint)">context: FIB-SEM is destructive; sections stay archival</text>
</svg></div>
    <div class="acg-eb" style="color:#8a6f4a">IMAGING</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-fibsem" title="Link to this term">FIBSEM</a></h3>
    <p class="acg-def">Focused-ion-beam SEM; block-face EM that mills &amp; images, giving near-isotropic voxels.</p>
    <div class="acg-meta"><span class="acg-chip acg-aside" title="An adjacent method, not used to acquire these datasets">adjacent method</span></div>
    </article>
    <article class="acg-card" id="term-fluorophore" data-cat="genetics" data-hay="fluorophore a type of molecule which absorb light and re-emit it at a longer wavelength in a process called fluorescence. as a result, fluorophores fluoresce only while exposed to a light source. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-fluorophore" title="Link to this term">Fluorophore</a></h3>
    <p class="acg-def">A type of molecule which absorb light and re-emit it at a longer wavelength in a process called fluorescence. As a result, fluorophores fluoresce only while exposed to a light source.</p>
    </article>
    <article class="acg-card" id="term-functional-connectome" data-cat="datasets" data-hay="functional connectome a dataset linking synapse-resolution em connectivity to recorded neural function in the same neurons. datasets &amp; scope ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d4"><title id="d4">Functional connectome</title><rect x="16" y="40" width="132" height="140" rx="6" fill="var(--surface-2)" stroke="var(--border)" stroke-width="1.4"/><rect x="190" y="40" width="114" height="140" rx="6" fill="var(--surface-2)" stroke="var(--border)" stroke-width="1.4"/><text x="82" y="33" text-anchor="middle" font-size="9" fill="var(--muted)">calcium (function)</text><text x="247" y="33" text-anchor="middle" font-size="8.5" fill="var(--muted)">EM mesh (structure)</text><g fill="none" stroke="currentColor" stroke-opacity=".8" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M26,72 L46,72 C50,72 51,60 55,60 C60,60 60,72 70,72 L92,72 C96,72 97,55 102,55 C108,55 108,72 118,72 L138,72"/><path d="M26,112 L52,112 C56,112 57,98 62,98 C68,98 68,112 80,112 L104,112 C108,112 109,103 113,103 C118,103 118,112 138,112"/><path d="M26,152 L44,152 C48,152 49,140 54,140 C60,140 60,152 72,152 L96,152 C100,152 101,133 107,133 C114,133 114,152 138,152"/></g><g fill="none" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><ellipse cx="248" cy="72" rx="9" ry="7" fill="var(--neuron)" fill-opacity=".22"/><path d="M248,65 C246,54 253,52 251,42"/><path d="M242,77 C234,84 238,92 230,94"/><ellipse cx="252" cy="112" rx="9" ry="7" fill="var(--neuron)" fill-opacity=".22"/><path d="M252,105 C250,94 257,92 255,82"/><path d="M246,117 C238,124 242,132 234,134"/><ellipse cx="246" cy="152" rx="9" ry="7" fill="var(--neuron)" fill-opacity=".22"/><path d="M246,145 C244,134 251,132 249,122"/><path d="M240,157 C232,164 236,172 228,174"/></g><g stroke="currentColor" stroke-opacity=".5" stroke-width="1.8" stroke-linecap="round"><line x1="142" y1="72" x2="222" y2="72"/><line x1="142" y1="112" x2="224" y2="112"/><line x1="142" y1="152" x2="222" y2="152"/></g><g fill="currentColor" fill-opacity=".5"><polygon points="224,72 217,69 217,75"/><polygon points="226,112 219,109 219,115"/><polygon points="224,152 217,149 217,155"/></g><text x="160" y="194" text-anchor="middle" font-size="9" fill="var(--muted)">same cells</text></svg></div>
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-functional-connectome" title="Link to this term">Functional connectome</a></h3>
    <p class="acg-def">A dataset linking synapse-resolution EM connectivity to recorded neural function in the same neurons.</p>
    </article>
    <article class="acg-card" id="term-gaba" data-cat="celltypes" data-hay="gaba gamma-aminobutyric acid (gaba) is the main inhibitory neurotransmitter in the mammalian brain. in cortex, most gabaergic neurons are local interneurons. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-gaba" title="Link to this term">GABA</a></h3>
    <p class="acg-def">Gamma-aminobutyric acid (GABA) is the main inhibitory neurotransmitter in the mammalian brain. In cortex, most GABAergic neurons are local interneurons.</p>
    </article>
    <article class="acg-card" id="term-gcamp" data-cat="genetics" data-hay="gcamp a family of geci. gcamp was generated by a fusion of the calcium binding domain of the calmodulin protein with green fluorescent protein (gfp). in these data we use primarily gcamp6f as well as some gcamp6s, fast and slow variants respectively. these two variants differ in their sensitivity as well as their kinetics — primarily with regards to their decay. for more see {cite:t}`chen2013`. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-gcamp" title="Link to this term">GCaMP</a></h3>
    <p class="acg-def">A family of GECI. GCaMP was generated by a fusion of the calcium binding domain of the calmodulin protein with green fluorescent protein (GFP). In these data we use primarily GCaMP6f as well as some GCaMP6s, fast and slow variants respectively. These two variants differ in their sensitivity as well as their kinetics — primarily with regards to their decay. For more see {cite:t}`chen2013`.</p>
    </article>
    <article class="acg-card" id="term-geci" data-cat="genetics" data-hay="genetically-encoded calcium indicator (geci) a protein expressed by a cell that will change its fluorescence upon binding to a ca{sup}`2+` ion. used to visualize neural activity with fluorescence microscopy. genetic &amp; optical tools ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="gec-t"><title id="gec-t">GECI: fluorescence rises when the indicator binds calcium</title><g fill="none" stroke="var(--dendrite)" stroke-width="2" stroke-linecap="round"><path d="M62,72 C56,56 50,46 44,34"/><path d="M78,72 C84,56 90,48 98,38"/><path d="M70,112 C70,132 66,146 62,160"/><path d="M198,72 C192,56 186,46 180,34"/><path d="M214,72 C220,56 226,48 234,38"/><path d="M206,112 C206,132 202,146 198,160"/></g><circle cx="70" cy="92" r="20" fill="var(--neuron)" fill-opacity=".12" stroke="var(--neuron)" stroke-width="2.2"/><circle cx="206" cy="92" r="20" fill="var(--neuron)" fill-opacity=".8" stroke="var(--neuron)" stroke-width="2.6"/><circle cx="206" cy="92" r="27" fill="none" stroke="var(--accent)" stroke-width="2.2" stroke-opacity=".7"/><g fill="var(--accent)"><circle cx="150" cy="72" r="3"/><circle cx="164" cy="84" r="3"/><circle cx="152" cy="98" r="3"/><circle cx="168" cy="108" r="3"/></g><text x="159" y="58" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)">Ca²⁺</text><path d="M118,92 H140" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/><path d="M134,88 L140,92 L134,96" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><text x="70" y="184" text-anchor="middle" font-size="10.5" fill="var(--muted)">at rest, dim</text><text x="206" y="184" text-anchor="middle" font-size="10.5" fill="var(--accent-ink)" font-weight="600">active, bright</text><text x="272" y="40" text-anchor="middle" font-size="9.5" class="mono" fill="var(--faint)">ΔF/F</text><path d="M258,116 h6 c4,0 4,-44 10,-44 c7,0 5,44 12,44 h6" fill="none" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-geci" title="Link to this term">Genetically-encoded calcium indicator (GECI)</a></h3>
    <p class="acg-def">A protein expressed by a cell that will change its fluorescence upon binding to a Ca{sup}`2+` ion. Used to visualize neural activity with fluorescence microscopy.</p>
    </article>
    <article class="acg-card" id="term-geodesic-distance" data-cat="morphology" data-hay="geodesic distance distance between two points measured along the neuron itself — path length through the skeleton — rather than through the space between them. two points a micrometre apart in the volume can be hundreds of micrometres apart on the arbor, and the second number is the one a signal has to travel. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-geodesic-distance" title="Link to this term">Geodesic distance</a></h3>
    <p class="acg-def">Distance between two points measured along the neuron itself — path length through the skeleton — rather than through the space between them. Two points a micrometre apart in the volume can be hundreds of micrometres apart on the arbor, and the second number is the one a signal has to travel.</p>
    </article>
    <article class="acg-card" id="term-gfp" data-cat="genetics" data-hay="gfp green fluorescent protein. discovered at fhl. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-gfp" title="Link to this term">GFP</a></h3>
    <p class="acg-def">Green fluorescent protein. Discovered at FHL.</p>
    </article>
    <article class="acg-card" id="term-gosi-gdsi" data-cat="functional" data-hay="gosi / gdsi global orientation/direction selectivity indices (vector-sum variant). functional data &amp; coregistration ">
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-gosi-gdsi" title="Link to this term">gOSI / gDSI</a></h3>
    <p class="acg-def">Global orientation/direction selectivity indices (vector-sum variant).</p>
    </article>
    <article class="acg-card" id="term-graphene-graphene" data-cat="segmentation" data-hay="graphene (graphene://) url protocol for dynamic, cave-backed (editable) segmentation/meshes, vs static precomputed://. segmentation &amp; reconstruction ">
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-graphene-graphene" title="Link to this term">Graphene (graphene://)</a></h3>
    <p class="acg-def">URL protocol for dynamic, CAVE-backed (editable) segmentation/meshes, vs static <code>precomputed://</code>.</p>
    </article>
    <article class="acg-card" id="term-graphene-vs-precomputed" data-cat="cave" data-hay="graphene vs precomputed graphene:// = dynamic/editable; precomputed:// = static. cave — access &amp; versioning ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="cave-gp"><title id="cave-gp">Graphene vs Precomputed</title>
<rect x="28" y="44" width="264" height="52" rx="12" fill="var(--surface-2)" stroke="var(--ok)" stroke-width="2"/>
<circle cx="54" cy="70" r="11" fill="none" stroke="var(--ok)" stroke-opacity=".4" stroke-width="2"/>
<circle cx="54" cy="70" r="6" fill="var(--ok)"/>
<text x="76" y="75" font-size="14" class="mono" fill="var(--ok)" font-weight="600">graphene://</text>
<text x="282" y="75" text-anchor="end" font-size="10" fill="var(--ok)">editable / live</text>
<rect x="28" y="110" width="264" height="52" rx="12" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<rect x="46" y="130" width="16" height="14" rx="2" fill="var(--scaffold)" fill-opacity=".5" stroke="currentColor" stroke-opacity=".7" stroke-width="2"/>
<path d="M50,130 v-3 a4,4 0 0 1 8,0 v3" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/>
<text x="76" y="141" font-size="14" class="mono" fill="var(--muted)">precomputed://</text>
<text x="282" y="141" text-anchor="end" font-size="10" fill="var(--muted)">frozen / static</text>
</svg></div>
    <div class="acg-eb" style="color:#0f766e">CAVE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-graphene-vs-precomputed" title="Link to this term">Graphene vs Precomputed</a></h3>
    <p class="acg-def"><code>graphene://</code> = dynamic/editable; <code>precomputed://</code> = static.</p>
    </article>
    <article class="acg-card" id="term-grids-chunk" data-cat="volume" data-hay="grids / chunk the volume is partitioned into a 3d grid of chunks for the chunked-graph. volume, voxels &amp; coordinates ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="grid-t"><title id="grid-t">Volume diced into a grid of chunks, one chunk highlighted</title><polygon points="55,60 175,60 175,160 55,160" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linejoin="round"/><polygon points="55,60 175,60 205,42 85,42" fill="var(--scaffold)" fill-opacity=".26" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linejoin="round"/><polygon points="175,60 205,42 205,142 175,160" fill="var(--scaffold)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linejoin="round"/><polygon points="135,60 175,60 175,93 135,93" fill="var(--accent)" fill-opacity=".3"/><polygon points="135,60 175,60 205,42 165,42" fill="var(--accent)" fill-opacity=".42"/><polygon points="175,60 205,42 205,75 175,93" fill="var(--accent)" fill-opacity=".2"/><g stroke="currentColor" stroke-opacity=".5" stroke-width="1.5"><path d="M95,60 V160"/><path d="M135,60 V160"/><path d="M55,93 H175"/><path d="M55,127 H175"/><path d="M95,60 L125,42"/><path d="M135,60 L165,42"/><path d="M175,93 L205,75"/><path d="M175,127 L205,109"/></g><path d="M208,58 L232,55" fill="none" stroke="var(--accent-ink)" stroke-width="1.5" stroke-linecap="round"/><text x="236" y="59" font-size="11" fill="var(--accent-ink)" font-weight="600">chunk</text><text x="115" y="182" text-anchor="middle" font-size="11" fill="var(--muted)">chunked volume</text></svg></div>
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-grids-chunk" title="Link to this term">Grids / Chunk</a></h3>
    <p class="acg-def">The volume is partitioned into a 3D grid of chunks for the chunked-graph.</p>
    </article>
    <article class="acg-card" id="term-higher-visual-area" data-cat="responses" data-hay="higher visual area (hva) a **higher visual area** is a term for cortical visual areas that receive input from the primary visual cortex, thus considered to be &quot;higher&quot; in the visual hierarchy. in primates, higher visual areas include v2, v3, v4, v5, mt, etc. in the mouse, higher visual areas include: visl, visal, vispm, visam, visrl among others. for more, see {cite:t}`glickfeld_higher-order_2017`. response properties &amp; analysis ">
    <div class="acg-eb" style="color:#9f1239">RESPONSE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-higher-visual-area" title="Link to this term">Higher visual area (HVA)</a></h3>
    <p class="acg-def">A **higher visual area** is a term for cortical visual areas that receive input from the primary visual cortex, thus considered to be "higher" in the visual hierarchy. In primates, higher visual areas include V2, V3, V4, V5, MT, etc. In the mouse, higher visual areas include: VISl, VIsal, VISpm, VISam, VISrl among others. For more, see {cite:t}`glickfeld_higher-order_2017`.</p>
    </article>
    <article class="acg-card" id="term-hyperparameter" data-cat="responses" data-hay="hyperparameter a free parameter that controls behaviors in machine learning algorithms. these are distinct from parameters which control behaviors of the models developed by the algorithms; hyperparameters affect how the algorithm finds the models in the first place. response properties &amp; analysis ">
    <div class="acg-eb" style="color:#9f1239">RESPONSE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-hyperparameter" title="Link to this term">Hyperparameter</a></h3>
    <p class="acg-def">A free parameter that controls behaviors in machine learning algorithms. These are distinct from parameters which control behaviors of the models developed by the algorithms; hyperparameters affect how the algorithm finds the models in the first place.</p>
    </article>
    <article class="acg-card" id="term-imagery" data-cat="imaging" data-hay="imagery the 3d grayscale (0–255) array depicting em ultrastructure. imaging &amp; ultrastructure ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="img-t"><title id="img-t">Imagery: grayscale EM tile</title>
<rect x="28" y="26" width="196" height="124" rx="3" fill="var(--scaffold)" fill-opacity=".12" stroke="currentColor" stroke-opacity=".7" stroke-width="2"/>
<ellipse cx="90" cy="78" rx="40" ry="24" fill="var(--scaffold)" fill-opacity=".3"/>
<path d="M70,64 q6,14 0,28 M90,60 q6,18 0,34 M110,64 q6,14 0,28" fill="none" stroke="currentColor" stroke-opacity=".35" stroke-width="1.6" stroke-linecap="round"/>
<circle cx="170" cy="54" r="5" fill="var(--scaffold)" fill-opacity=".5"/>
<circle cx="182" cy="50" r="5" fill="var(--scaffold)" fill-opacity=".5"/>
<circle cx="178" cy="62" r="5" fill="var(--scaffold)" fill-opacity=".5"/>
<circle cx="192" cy="60" r="5" fill="var(--scaffold)" fill-opacity=".5"/>
<circle cx="184" cy="116" r="17" fill="var(--scaffold)" fill-opacity=".55"/>
<path d="M40,132 q28,-14 56,-2 t56,-4" fill="none" stroke="currentColor" stroke-opacity=".3" stroke-width="2" stroke-linecap="round"/>
<text x="126" y="166" text-anchor="middle" font-size="9.5" fill="var(--muted)">8-bit grayscale tile</text>
<rect x="244" y="30" width="22" height="15" fill="var(--scaffold)" fill-opacity=".08" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="45" width="22" height="15" fill="var(--scaffold)" fill-opacity=".19" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="60" width="22" height="15" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="75" width="22" height="15" fill="var(--scaffold)" fill-opacity=".41" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="90" width="22" height="15" fill="var(--scaffold)" fill-opacity=".52" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="105" width="22" height="15" fill="var(--scaffold)" fill-opacity=".62" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="120" width="22" height="15" fill="var(--scaffold)" fill-opacity=".72" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<rect x="244" y="135" width="22" height="15" fill="var(--scaffold)" fill-opacity=".82" stroke="currentColor" stroke-opacity=".25" stroke-width="1"/>
<text x="255" y="24" text-anchor="middle" font-size="9.5" class="mono" fill="var(--muted)">255</text>
<text x="255" y="164" text-anchor="middle" font-size="9.5" class="mono" fill="var(--muted)">0</text>
<text transform="translate(284,90) rotate(-90)" text-anchor="middle" font-size="9.5" fill="var(--faint)">intensity</text>
</svg></div>
    <div class="acg-eb" style="color:#8a6f4a">IMAGING</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-imagery" title="Link to this term">Imagery</a></h3>
    <p class="acg-def">The 3D grayscale (0–255) array depicting EM ultrastructure.</p>
    </article>
    <article class="acg-card" id="term-inhibitory-v1-cell-types" data-cat="celltypes" data-hay="inhibitory v1 cell types interneuron subclasses: bc, bpc, mc, ngc (manual) and ptc/dtc/stc/itc (targeting-based mtypes). cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="iv-t"><title id="iv-t">Inhibitory V1 cell types: manual vs targeting</title>
<text x="84" y="26" text-anchor="middle" font-size="12" font-weight="600" fill="var(--accent-ink)">manual</text>
<text x="84" y="38" text-anchor="middle" font-size="8" fill="var(--muted)">by morphology</text>
<text x="236" y="26" text-anchor="middle" font-size="12" font-weight="600" fill="var(--accent-ink)">targeting-based</text>
<text x="236" y="38" text-anchor="middle" font-size="8" fill="var(--muted)">by synaptic target</text>
<path d="M160,44 V172" stroke="currentColor" stroke-opacity=".3" stroke-width="1.6" stroke-dasharray="3 3"/>
<g stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round">
<path d="M52,62 V52"/>
<path d="M116,68 V54 M116,76 V92"/>
<path d="M52,140 l-6,7 M52,140 l6,7"/>
</g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M52,70 V80 M52,80 C47,82 44,86 46,93 M52,80 C57,82 60,86 58,93"/>
<path d="M52,132 V114 M44,114 H60"/>
<path d="M116,132 l0,-11 M116,132 l9,-6 M116,132 l11,0 M116,132 l9,6 M116,132 l0,11 M116,132 l-9,6 M116,132 l-11,0 M116,132 l-9,-6"/>
</g>
<g fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.6"><circle cx="45" cy="90" r="4"/><circle cx="59" cy="90" r="4"/></g>
<g fill="var(--neuron)"><circle cx="52" cy="66" r="4"/><circle cx="116" cy="72" r="4"/><circle cx="52" cy="136" r="4"/><circle cx="116" cy="132" r="4"/></g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M198,72 H210 M210,72 l-4,-3 M210,72 l-4,3"/>
<path d="M262,72 H274 M274,72 l-4,-3 M274,72 l-4,3"/>
<path d="M262,132 H272 M272,132 l-4,-3 M272,132 l-4,3"/>
</g>
<g stroke="var(--axon)" stroke-width="1.6" fill="none" stroke-linecap="round" stroke-dasharray="2 2">
<path d="M199,132 L212,124 M199,132 L214,132 M199,132 L212,140"/>
</g>
<polygon points="215,65 210,79 220,79" fill="var(--neuron)" fill-opacity=".18" stroke="var(--neuron)" stroke-width="2" stroke-linejoin="round"/>
<path d="M280,62 V82 M280,70 l6,-4" stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round"/>
<circle cx="280" cy="132" r="5" fill="none" stroke="var(--dendrite)" stroke-width="2"/>
<path d="M280,127 v-4 M280,137 v4" stroke="var(--dendrite)" stroke-width="1.6" stroke-linecap="round"/>
<g fill="var(--neuron)"><circle cx="194" cy="72" r="3.5"/><circle cx="258" cy="72" r="3.5"/><circle cx="194" cy="132" r="3.5"/><circle cx="258" cy="132" r="3.5"/></g>
<g class="mono" text-anchor="middle" font-size="9.5" fill="var(--muted)">
<text x="52" y="104">BC</text><text x="116" y="104">BPC</text><text x="52" y="164">MC</text><text x="116" y="164">NGC</text>
<text x="204" y="104">PTC</text><text x="268" y="104">DTC</text><text x="204" y="164">STC</text><text x="268" y="164">ITC</text>
</g>
</svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-inhibitory-v1-cell-types" title="Link to this term">Inhibitory V1 cell types</a></h3>
    <p class="acg-def">Interneuron subclasses: BC, BPC, MC, NGC (manual) and PTC/DTC/STC/ITC (targeting-based mtypes).</p>
    </article>
    <article class="acg-card" id="term-interneuron" data-cat="celltypes" data-hay="interneuron also known as a local interneuron: a neuron that has short axons and synapse exclusively with nearby neurons. in the cortex the term is often used to refer to inhibitory neurons. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-interneuron" title="Link to this term">Interneuron</a></h3>
    <p class="acg-def">Also known as a local interneuron: a neuron that has short axons and synapse exclusively with nearby neurons. In the cortex the term is often used to refer to inhibitory neurons.</p>
    </article>
    <article class="acg-card" id="term-intrinsic-signal-imaging" data-cat="modalities" data-hay="intrinsic signal imaging (isi) intrinsic signal imaging, also called isi, is a method to measure changes in blood flow associated with neural activity using reflectance of red light on the brain's surface, measured using a standard ccd camera. the amount of red light reflected by the brain tissue increases when oxygenated hemoglobin perfuses the local region. the timecourse of the isi signal is slow, and the magnitude of the reflectance changes are small. as a result, the use of periodic stimuli can aid in signal detection. a common use of isi is to map retinotopy across the brain surface by moving a slowly drifting bar across the visual field then measuring the signal in each pixel at the frequency of the periodic drifting bar. isi has also been used to identify orientation maps in species with organized orientation maps like cats and primates, as well as to map the location of the whisker barrels in somatosensory cortex of the mouse. for additional papers using isi to map the organization of the mouse visual cortex see {cite:t}`kalatsky2003` and {cite:t}`garrett2014`. recording modalities &amp; instruments ">
    <div class="acg-eb" style="color:#c2410c">MODALITY</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-intrinsic-signal-imaging" title="Link to this term">Intrinsic signal imaging (ISI)</a></h3>
    <p class="acg-def">Intrinsic signal imaging, also called ISI, is a method to measure changes in blood flow associated with neural activity using reflectance of red light on the brain's surface, measured using a standard CCD camera. The amount of red light reflected by the brain tissue increases when oxygenated hemoglobin perfuses the local region. The timecourse of the ISI signal is slow, and the magnitude of the reflectance changes are small. As a result, the use of periodic stimuli can aid in signal detection. A common use of ISI is to map retinotopy across the brain surface by moving a slowly drifting bar across the visual field then measuring the signal in each pixel at the frequency of the periodic drifting bar. ISI has also been used to identify orientation maps in species with organized orientation maps like cats and primates, as well as to map the location of the whisker barrels in somatosensory cortex of the mouse. For additional papers using ISI to map the organization of the mouse visual cortex see {cite:t}`kalatsky2003` and {cite:t}`garrett2014`.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-it-et-np-ct-sp" data-cat="celltypes" data-hay="it / et / np / ct / sp projection categories: intratelencephalic, extratelencephalic, near-projecting, corticothalamic, subplate. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ip-t"><title id="ip-t">Excitatory projection classes and their targets</title>
<rect x="34" y="22" width="50" height="158" fill="currentColor" fill-opacity=".04" stroke="currentColor" stroke-opacity=".3" stroke-width="1.4"/>
<path d="M34,36 H84 M34,70 H84 M34,92 H84 M34,128 H84 M34,168 H84" stroke="currentColor" stroke-opacity=".28" stroke-width="1.1"/>
<g class="mono" font-size="7.5" fill="var(--muted)">
<text x="13" y="31">L1</text><text x="13" y="55">L2/3</text><text x="13" y="83">L4</text><text x="13" y="112">L5</text><text x="13" y="150">L6</text><text x="12" y="176">L6b</text>
</g>
<g stroke="var(--axon)" stroke-width="2.2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M80,54 C140,42 185,44 224,46 M224,46 l-7,-3 M224,46 l-6,4"/>
<path d="M80,150 C140,150 185,150 224,150 M224,150 l-7,-4 M224,150 l-7,4"/>
<path d="M80,112 C150,138 195,166 224,176 M224,176 l-8,-2 M224,176 l-2,-7"/>
<path d="M80,122 C104,120 120,110 126,98 M126,98 l-4,7 M126,98 l6,3"/>
<path d="M80,172 C98,177 116,181 134,182 M134,182 l-7,-3 M134,182 l-6,4"/>
</g>
<g fill="var(--neuron)"><circle cx="80" cy="54" r="4"/><circle cx="80" cy="112" r="4"/><circle cx="80" cy="122" r="4"/><circle cx="80" cy="150" r="4"/><circle cx="80" cy="172" r="4"/></g>
<g font-size="10">
<text x="230" y="50"><tspan class="mono" font-weight="600" fill="var(--axon)">IT</tspan><tspan fill="var(--muted)"> cortex</tspan></text>
<text x="132" y="96"><tspan class="mono" font-weight="600" fill="var(--axon)">NP</tspan><tspan fill="var(--muted)"> local</tspan></text>
<text x="230" y="154"><tspan class="mono" font-weight="600" fill="var(--axon)">CT</tspan><tspan fill="var(--muted)"> thalamus</tspan></text>
<text x="230" y="180"><tspan class="mono" font-weight="600" fill="var(--axon)">ET</tspan><tspan fill="var(--muted)"> brainstem</tspan></text>
<text x="140" y="186"><tspan class="mono" font-weight="600" fill="var(--axon)">SP</tspan><tspan fill="var(--muted)"> subplate</tspan></text>
</g>
</svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-it-et-np-ct-sp" title="Link to this term">IT / ET / NP / CT / SP</a></h3>
    <p class="acg-def">Projection categories: intratelencephalic, extratelencephalic, near-projecting, corticothalamic, subplate.</p>
    </article>
    <article class="acg-card" id="term-layer-cortical" data-cat="celltypes" data-hay="layer (cortical) l1–l6 along the pia→wm axis; drives cell-type naming. not the neuroglancer layer. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="lc-t"><title id="lc-t">Cortical layers from pia to white matter</title>
<text x="150" y="18" text-anchor="middle" font-size="10" fill="var(--muted)">pia</text>
<g stroke="none">
<rect x="100" y="24" width="100" height="18" fill="currentColor" fill-opacity=".05"/>
<rect x="100" y="42" width="100" height="40" fill="currentColor" fill-opacity=".10"/>
<rect x="100" y="82" width="100" height="22" fill="currentColor" fill-opacity=".06"/>
<rect x="100" y="104" width="100" height="36" fill="currentColor" fill-opacity=".10"/>
<rect x="100" y="140" width="100" height="30" fill="currentColor" fill-opacity=".06"/>
<rect x="100" y="170" width="100" height="12" fill="currentColor" fill-opacity=".18"/>
</g>
<path d="M100,24 V182 M200,24 V182 M100,42 H200 M100,82 H200 M100,104 H200 M100,140 H200 M100,170 H200 M100,182 H200" stroke="currentColor" stroke-opacity=".3" stroke-width="1.2" fill="none"/>
<path d="M100,24 H200" stroke="var(--accent)" stroke-width="2.6" stroke-linecap="round"/>
<path d="M84,28 V174 M84,174 l-4,-6 M84,174 l4,-6" stroke="currentColor" stroke-opacity=".5" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
<text transform="translate(72,101) rotate(-90)" text-anchor="middle" class="mono" font-size="9" fill="var(--muted)">cortical depth</text>
<g class="mono" font-size="10" fill="var(--muted)">
<text x="210" y="36">L1</text><text x="210" y="65">L2/3</text><text x="210" y="96">L4</text><text x="210" y="125">L5</text><text x="210" y="157">L6</text><text x="210" y="178">white matter</text>
</g>
</svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-layer-cortical" title="Link to this term">Layer (cortical)</a></h3>
    <p class="acg-def">L1–L6 along the pia→WM axis; drives cell-type naming. NOT the Neuroglancer layer.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-level-of-detail-lod" data-cat="morphology" data-hay="level of detail (lod) static meshes are smaller, multi-lod, precomputed://; dynamic meshes are detailed, single-lod, graphene://. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-lod"><title id="m-lod">Same neuron at coarse versus fine triangle density</title><line x1="160" y1="24" x2="160" y2="176" stroke="currentColor" stroke-opacity=".25" stroke-width="1.5" stroke-dasharray="3 4"/><polygon points="75,68 108,88 112,120 88,145 55,142 40,112 48,82" fill="var(--neuron)" fill-opacity=".12" stroke="var(--neuron)" stroke-width="2" stroke-linejoin="round"/><g fill="none" stroke="var(--neuron)" stroke-opacity=".6" stroke-width="1.4"><path d="M74,105 L75,68 M74,105 L108,88 M74,105 L112,120 M74,105 L88,145 M74,105 L55,142 M74,105 L40,112 M74,105 L48,82"/></g><text x="75" y="170" text-anchor="middle" font-size="10.5" fill="var(--muted)">coarse</text><text x="75" y="184" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">~7 faces</text><polygon points="225,66 252,74 266,96 266,120 252,142 225,150 198,142 184,120 184,96 198,74" fill="var(--neuron)" fill-opacity=".12" stroke="var(--neuron)" stroke-width="2" stroke-linejoin="round"/><g fill="none" stroke="var(--neuron)" stroke-opacity=".55" stroke-width="1.2"><path d="M225,108 L225,66 M225,108 L252,74 M225,108 L266,96 M225,108 L266,120 M225,108 L252,142 M225,108 L225,150 M225,108 L198,142 M225,108 L184,120 M225,108 L184,96 M225,108 L198,74"/><path d="M225,66 L266,96 L252,142 L198,142 L184,96 L225,66 M252,74 L266,120 L225,150 L184,120 L198,74 L252,74"/></g><text x="225" y="170" text-anchor="middle" font-size="10.5" fill="var(--muted)">fine</text><text x="225" y="184" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">~40 faces</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-level-of-detail-lod" title="Link to this term">Level of detail (LOD)</a></h3>
    <p class="acg-def">Static meshes are smaller, multi-LOD, <code>precomputed://</code>; dynamic meshes are detailed, single-LOD, <code>graphene://</code>.</p>
    </article>
    <article class="acg-card" id="term-link-edges" data-cat="morphology" data-hay="link edges extra mesh edges inserted from the proofreading record to bridge gaps where segmentation was merged across a discontinuity. without them a mesh may be several disconnected pieces; mesh.add_link_edges() heals it, and mesh.graph_edges is the edges plus the link edges. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-link-edges" title="Link to this term">Link edges</a></h3>
    <p class="acg-def">Extra mesh edges inserted from the proofreading record to bridge gaps where segmentation was merged across a discontinuity. Without them a mesh may be several disconnected pieces; <code>mesh.add_link_edges()</code> heals it, and <code>mesh.graph_edges</code> is the edges plus the link edges.</p>
    <div class="acg-meta"><a class="acg-chip acg-src" href="https://alleninstitute.github.io/microns_tutorial/" target="_blank" rel="noopener">MICrONS tutorial &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-local-field-potential" data-cat="signals" data-hay="local field potential (lfp) transient electrical potential generated in nervous tissue by the summed activity of cells in that tissue. this is typically measured in a lower temporal-frequency band of less than 250 hz. signals &amp; preprocessing ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="lfp-t"><title id="lfp-t">Local field potential: summed activity of nearby cells</title><circle cx="74" cy="108" r="52" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".3" stroke-width="1.6" stroke-dasharray="4 4"/><path d="M66,26 V104 L74,118 L82,104 V26" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linejoin="round"/><g fill="var(--neuron)" fill-opacity=".45" stroke="var(--neuron)" stroke-width="1.6"><circle cx="38" cy="88" r="6"/><circle cx="46" cy="136" r="6"/><circle cx="98" cy="82" r="6"/><circle cx="106" cy="130" r="6"/><circle cx="72" cy="152" r="6"/><circle cx="34" cy="116" r="6"/></g><path d="M132,108 H164" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/><path d="M158,104 L164,108 L158,112" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M176,108 C188,80 200,80 212,108 C220,127 226,131 234,116 C242,101 248,98 256,110 C266,127 274,131 284,108 C291,91 300,92 306,104" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round"/><text x="74" y="180" text-anchor="middle" font-size="10.5" fill="var(--muted)">many cells, one electrode</text><text x="242" y="164" text-anchor="middle" font-size="11" fill="var(--accent-ink)" font-weight="600">summed potential</text><text x="242" y="180" text-anchor="middle" font-size="9.5" class="mono" fill="var(--faint)">below 250 Hz</text></svg></div>
    <div class="acg-eb" style="color:#0369a1">SIGNAL</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-local-field-potential" title="Link to this term">Local field potential (LFP)</a></h3>
    <p class="acg-def">Transient electrical potential generated in nervous tissue by the summed activity of cells in that tissue. This is typically measured in a lower temporal-frequency band of less than 250 Hz.</p>
    </article>
    <article class="acg-card" id="term-martinotti-cell" data-cat="celltypes" data-hay="martinotti cell (mc) a martinotti cell is a particular subtype of sst cell that targets the apical dendrites of pyramidal cells in layer 1. martinotti cells are found in layer 2/3 and layer 5. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d-martinotti-cell"><title id="d-martinotti-cell">Martinotti cell</title><defs><clipPath id="d-martinotti-cell-c" clipPathUnits="userSpaceOnUse"><rect x="88" y="26" width="76" height="118"/></clipPath></defs><g transform="translate(160,100) scale(1.55) translate(-126,-88)"><g clip-path="url(#d-martinotti-cell-c)"><g stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round">
<path d="M50,73 V54 M50,73 l-9,-12 M50,73 l9,-12"/>
<path d="M126,121 V132 M126,121 l-8,9 M126,121 l8,9"/>
<path d="M202,85 V54 M202,54 l-5,-6 M202,54 l5,-6 M202,95 V128 M202,128 l-5,6 M202,128 l5,6"/>
</g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M50,83 V95 M50,95 C44,98 40,104 42,112 M50,95 C56,98 60,104 58,112"/>
<path d="M126,111 V54 M112,54 H140 M116,54 v-6 M126,54 v-6 M136,54 v-6"/>
<path d="M278,88 l0,-16 M278,88 l14,-8 M278,88 l16,0 M278,88 l14,8 M278,88 l0,16 M278,88 l-14,8 M278,88 l-16,0 M278,88 l-14,-8"/>
</g>
<g fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.6"><circle cx="42" cy="110" r="5"/><circle cx="58" cy="110" r="5"/></g>
<g fill="var(--neuron)"><circle cx="50" cy="78" r="5"/><circle cx="126" cy="116" r="5"/><circle cx="202" cy="90" r="5"/><circle cx="278" cy="88" r="5"/></g></g></g></svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-martinotti-cell" title="Link to this term">Martinotti cell (MC)</a></h3>
    <p class="acg-def">A Martinotti cell is a particular subtype of SST cell that targets the apical dendrites of pyramidal cells in layer 1. Martinotti cells are found in layer 2/3 and layer 5.</p>
    </article>
    <article class="acg-card" id="term-materialization-versioning" data-cat="cave" data-hay="materialization &amp; versioning timestamped snapshots of the annotation db; each version = a fixed timestamp (microns v1507, v1dd v1196). cave — access &amp; versioning ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="cave-mv"><title id="cave-mv">Materialization and versioning</title>
<line x1="28" y1="132" x2="290" y2="132" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/>
<polygon points="296,132 287,128 287,136" fill="currentColor" fill-opacity=".55"/>
<text x="290" y="150" text-anchor="end" font-size="9.5" class="mono" fill="var(--muted)">time</text>
<line x1="64" y1="132" x2="64" y2="99" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<circle cx="64" cy="88" r="11" fill="var(--surface)" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<text x="64" y="92" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">v1</text>
<line x1="124" y1="132" x2="124" y2="99" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<circle cx="124" cy="88" r="11" fill="var(--surface)" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<text x="124" y="92" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">v2</text>
<line x1="184" y1="132" x2="184" y2="99" stroke="var(--ok)" stroke-width="2.6"/>
<circle cx="184" cy="88" r="11" fill="var(--ok)" fill-opacity=".18" stroke="var(--ok)" stroke-width="2.6"/>
<text x="184" y="92" text-anchor="middle" font-size="10" class="mono" fill="var(--ok)" font-weight="600">v3</text>
<line x1="244" y1="132" x2="244" y2="99" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<circle cx="244" cy="88" r="11" fill="var(--surface)" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/>
<text x="244" y="92" text-anchor="middle" font-size="10" class="mono" fill="var(--muted)">v4</text>
<text x="42" y="34" font-size="11" class="mono" fill="var(--accent-ink)" font-weight="600">query @ v3</text>
<path d="M60,42 C110,44 152,54 181,71" fill="none" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<polygon points="184,74 174,70 179,64" fill="var(--accent-ink)"/>
</svg></div>
    <div class="acg-eb" style="color:#0f766e">CAVE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-materialization-versioning" title="Link to this term">Materialization &amp; Versioning</a></h3>
    <p class="acg-def">Timestamped snapshots of the annotation DB; each version = a fixed timestamp (MICrONS v1507, V1DD v1196).</p>
    </article>
    <article class="acg-card" id="term-merge-errors" data-cat="proofreading" data-hay="merge errors two neurons' processes incorrectly joined; they add false connections. proofreading &amp; data quality ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="pm"><title id="pm">Merge errors — false merge</title>
<circle cx="34" cy="60" r="10" fill="var(--neuron)" fill-opacity=".22" stroke="var(--neuron)" stroke-width="2.4"/>
<path d="M40,66 C72,74 106,86 138,98" fill="none" stroke="var(--neuron)" stroke-width="2.6" stroke-linecap="round"/>
<path d="M30,52 C28,42 27,36 26,28" fill="none" stroke="var(--neuron)" stroke-width="2.6" stroke-linecap="round"/>
<circle cx="34" cy="150" r="10" fill="var(--dendrite)" fill-opacity=".22" stroke="var(--dendrite)" stroke-width="2.4"/>
<path d="M40,144 C72,136 106,112 138,100" fill="none" stroke="var(--dendrite)" stroke-width="2.6" stroke-linecap="round"/>
<path d="M30,160 C28,170 27,176 26,184" fill="none" stroke="var(--dendrite)" stroke-width="2.6" stroke-linecap="round"/>
<circle cx="140" cy="99" r="11" fill="none" stroke="var(--error)" stroke-width="2.4"/>
<path d="M135,94 l10,10 M145,94 l-10,10" stroke="var(--error)" stroke-width="2" stroke-linecap="round"/>
<text x="96" y="150" text-anchor="middle" font-size="9.5" fill="var(--error)">false merge — adds a connection</text>
</svg></div>
    <div class="acg-eb" style="color:#b8791a">PROOF</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-merge-errors" title="Link to this term">Merge errors</a></h3>
    <p class="acg-def">Two neurons' processes incorrectly joined; they add false connections.</p>
    </article>
    <article class="acg-card" id="term-meshes" data-cat="morphology" data-hay="meshes vertices + triangular faces defining a neuron's 3d outer surface. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-mesh"><title id="m-mesh">Neuron surface mesh with triangle-wireframe zoom</title><path d="M120,90 C150,70 165,64 180,58 M92,128 C86,150 80,160 72,172" fill="none" stroke="var(--neuron)" stroke-width="6" stroke-linecap="round"/><ellipse cx="100" cy="105" rx="28" ry="24" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.2"/><g fill="none" stroke="currentColor" stroke-opacity=".3" stroke-width="1"><path d="M80,92 L118,100 L96,124 Z M118,100 L124,116 L96,124 M80,92 L86,110 L96,124"/></g><rect x="142" y="58" width="16" height="16" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="1.5" stroke-dasharray="3 3"/><line x1="158" y1="60" x2="221" y2="118" stroke="currentColor" stroke-opacity=".4" stroke-width="1.2"/><line x1="152" y1="74" x2="217" y2="163" stroke="currentColor" stroke-opacity=".4" stroke-width="1.2"/><circle cx="250" cy="140" r="40" fill="var(--surface)" stroke="currentColor" stroke-opacity=".7" stroke-width="2.4"/><g fill="none" stroke="var(--neuron)" stroke-width="1.6" stroke-linejoin="round"><polygon points="250,112 274,126 274,154 250,168 226,154 226,126"/><path d="M250,140 L250,112 M250,140 L274,126 M250,140 L274,154 M250,140 L250,168 M250,140 L226,154 M250,140 L226,126"/></g><text x="100" y="188" text-anchor="middle" font-size="10" fill="var(--muted)">surface mesh</text><text x="250" y="190" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">triangles</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-meshes" title="Link to this term">Meshes</a></h3>
    <p class="acg-def">Vertices + triangular faces defining a neuron's 3D outer surface.</p>
    </article>
    <article class="acg-card" id="term-meshpoints" data-cat="morphology" data-hay="meshpoints informal usage for mesh vertices. not a formal term — say vertices, since “point” elsewhere means an annotation position. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-meshpoints" title="Link to this term">Meshpoints</a></h3>
    <p class="acg-def">Informal usage for mesh vertices. Not a formal term — say <em>vertices</em>, since “point” elsewhere means an annotation position.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-meshwork-mask" data-cat="morphology" data-hay="meshwork mask a boolean array over mesh vertices restricting a meshwork to part of a cell, applied with apply_mask or mask_context so mesh, skeleton and annotations stay in step. masking on anno.is_axon is how axonal and dendritic path length are measured separately. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-meshwork-mask" title="Link to this term">Meshwork mask</a></h3>
    <p class="acg-def">A boolean array over mesh vertices restricting a meshwork to part of a cell, applied with <code>apply_mask</code> or <code>mask_context</code> so mesh, skeleton and annotations stay in step. Masking on <code>anno.is_axon</code> is how axonal and dendritic path length are measured separately.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span><a class="acg-chip acg-src" href="https://alleninstitute.github.io/microns_tutorial/" target="_blank" rel="noopener">MICrONS tutorial &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-met-type" data-cat="celltypes" data-hay="met-type a cell type defined jointly by morphology, electrophysiology and transcriptomics, from patch-seq recordings where all three are measured in the same cell. it is a stricter claim than a type named from any one of them alone. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-met-type" title="Link to this term">MET-type</a></h3>
    <p class="acg-def">A cell type defined jointly by morphology, electrophysiology and transcriptomics, from patch-seq recordings where all three are measured in the same cell. It is a stricter claim than a type named from any one of them alone.</p>
    </article>
    <article class="acg-card" id="term-microglia" data-cat="celltypes" data-hay="microglia the resident immune cell of the brain. it surveys the neuropil with motile processes and contacts, prunes and engulfs synapses, so it appears in em wrapped around structures it is in the act of removing. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-microglia" title="Link to this term">Microglia</a></h3>
    <p class="acg-def">The resident immune cell of the brain. It surveys the neuropil with motile processes and contacts, prunes and engulfs synapses, so it appears in EM wrapped around structures it is in the act of removing.</p>
    </article>
    <article class="acg-card" id="term-microns" data-cat="datasets" data-hay="microns cubic-millimeter functional-connectomics em dataset of mouse visual cortex (visp/visal/visrl). datasets &amp; scope ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d5"><title id="d5">MICrONS</title><polygon points="90,80 230,80 268,50 128,50" fill="var(--scaffold)" fill-opacity=".26" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8"/><polygon points="230,80 268,50 268,145 230,175" fill="var(--scaffold)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8"/><polygon points="90,80 230,80 230,175 90,175" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8"/><line x1="136.7" y1="80" x2="174.7" y2="50" stroke="currentColor" stroke-opacity=".4" stroke-width="1.3"/><line x1="183.3" y1="80" x2="221.3" y2="50" stroke="currentColor" stroke-opacity=".4" stroke-width="1.3"/><text x="128" y="67" text-anchor="middle" font-size="8.5" fill="var(--accent-ink)" font-weight="600">VISp</text><text x="177" y="64" text-anchor="middle" font-size="8.5" fill="var(--accent-ink)" font-weight="600">VISal</text><text x="223" y="61" text-anchor="middle" font-size="8.5" fill="var(--accent-ink)" font-weight="600">VISrl</text><text x="160" y="97" text-anchor="middle" font-size="9" class="mono" fill="var(--muted)">1 mm</text><text transform="translate(257,58) rotate(-38)" text-anchor="middle" font-size="9" class="mono" fill="var(--muted)">0.5 mm</text><text x="85" y="84" text-anchor="end" font-size="9" fill="var(--muted)">pia</text><text x="85" y="172" text-anchor="end" font-size="9" fill="var(--muted)">WM</text><text x="160" y="194" text-anchor="middle" font-size="8.5" fill="var(--faint)">3 visual areas · mm-scale EM volume</text></svg></div>
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-microns" title="Link to this term">MICrONS</a></h3>
    <p class="acg-def">Cubic-millimeter functional-connectomics EM dataset of mouse visual cortex (VISp/VISal/VISrl).</p>
    </article>
    <article class="acg-card" id="term-minnie" data-cat="datasets" data-hay="minnie a colloquial name for the millimeter-scale microns electron microscopy dataset. datasets &amp; scope ">
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-minnie" title="Link to this term">Minnie</a></h3>
    <p class="acg-def">A colloquial name for the millimeter-scale MICrONs electron microscopy dataset.</p>
    </article>
    <article class="acg-card" id="term-mtypes" data-cat="celltypes" data-hay="mtypes morphology/connectivity-derived cell-type clusters (l2a…l6wm; ptc/dtc/stc/itc). cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-mtypes" title="Link to this term">mtypes</a></h3>
    <p class="acg-def">Morphology/connectivity-derived cell-type clusters (L2a…L6wm; PTC/DTC/STC/ITC).</p>
    </article>
    <article class="acg-card" id="term-multifeature-cell-types" data-cat="celltypes" data-hay="multifeature cell types a labelling scheme combining somatic, dendritic and spine features. excitatory labels are layer plus projection class (l2it…l6ct); inhibitory labels split more finely than the mtypes (nmc, chc, pv, altbasket, altdtc, itcperi, l1). cell types &amp; cortical anatomy microns">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-multifeature-cell-types" title="Link to this term">Multifeature cell types</a></h3>
    <p class="acg-def">A labelling scheme combining somatic, dendritic and spine features. Excitatory labels are layer plus projection class (<code>L2IT</code>…<code>L6CT</code>); inhibitory labels split more finely than the mtypes (<code>NMC</code>, <code>ChC</code>, <code>PV</code>, <code>AltBasket</code>, <code>AltDTC</code>, <code>ITCperi</code>, <code>L1</code>).</p>
    <div class="acg-meta"><span class="acg-chip acg-ds">MICrONS only</span><a class="acg-chip acg-src" href="https://alleninstitute.github.io/microns_tutorial/" target="_blank" rel="noopener">MICrONS tutorial &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-neuroglancer" data-cat="tools" data-hay="neuroglancer webgl browser viewer for very large volumetric connectomics data (imagery, segmentation, meshes, annotations). visualisation tools ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ng-t"><title id="ng-t">Neuroglancer</title><rect x="18" y="20" width="138" height="78" rx="4" fill="var(--surface-2)" fill-opacity=".5" stroke="currentColor" stroke-opacity=".35" stroke-width="1.8"/><rect x="164" y="20" width="138" height="78" rx="4" fill="var(--surface-2)" fill-opacity=".5" stroke="currentColor" stroke-opacity=".35" stroke-width="1.8"/><rect x="18" y="102" width="138" height="78" rx="4" fill="var(--surface-2)" fill-opacity=".5" stroke="currentColor" stroke-opacity=".35" stroke-width="1.8"/><rect x="164" y="102" width="138" height="78" rx="4" fill="var(--surface-2)" fill-opacity=".5" stroke="currentColor" stroke-opacity=".35" stroke-width="1.8"/><line x1="18" y1="59" x2="156" y2="59" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><line x1="87" y1="20" x2="87" y2="98" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><ellipse cx="87" cy="59" rx="24" ry="16" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2"/><circle cx="96" cy="54" r="3" fill="var(--synapse)"/><line x1="164" y1="59" x2="302" y2="59" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><line x1="233" y1="20" x2="233" y2="98" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><ellipse cx="233" cy="59" rx="18" ry="19" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2"/><line x1="18" y1="141" x2="156" y2="141" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><line x1="87" y1="102" x2="87" y2="180" stroke="currentColor" stroke-opacity=".3" stroke-width="1"/><ellipse cx="87" cy="141" rx="23" ry="14" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2"/><circle cx="233" cy="138" r="8" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2.2"/><path d="M233,131 C228,119 221,113 213,117" fill="none" stroke="var(--dendrite)" stroke-width="2.2" stroke-linecap="round"/><path d="M233,131 C239,120 247,115 254,121" fill="none" stroke="var(--dendrite)" stroke-width="2.2" stroke-linecap="round"/><path d="M233,146 C233,158 240,164 249,168" fill="none" stroke="var(--axon)" stroke-width="2.2" stroke-linecap="round"/><text x="26" y="34" font-size="9" class="mono" fill="var(--muted)">xy</text><text x="172" y="34" font-size="9" class="mono" fill="var(--muted)">xz</text><text x="26" y="116" font-size="9" class="mono" fill="var(--muted)">yz</text><text x="172" y="116" font-size="9" class="mono" fill="var(--muted)">3D</text></svg></div>
    <div class="acg-eb" style="color:#526278">TOOLS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neuroglancer" title="Link to this term">Neuroglancer</a></h3>
    <p class="acg-def">WebGL browser viewer for very large volumetric connectomics data (imagery, segmentation, meshes, annotations).</p>
    <div class="acg-meta"><a class="acg-chip acg-src" href="https://github.com/google/neuroglancer" target="_blank" rel="noopener">Neuroglancer &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-neuroglancer-layer-img-seg-ann" data-cat="tools" data-hay="neuroglancer layer (img/seg/ann) the data layers in a neuroglancer state. not the cortical layer. visualisation tools ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="nl-t"><title id="nl-t">Neuroglancer layers img seg ann</title><line x1="34" y1="80" x2="34" y2="164" stroke="currentColor" stroke-opacity=".25" stroke-width="1.4" stroke-dasharray="3 4"/><line x1="208" y1="80" x2="208" y2="164" stroke="currentColor" stroke-opacity=".25" stroke-width="1.4" stroke-dasharray="3 4"/><polygon points="62,132 236,132 208,164 34,164" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".5" stroke-width="1.8"/><line x1="70" y1="141" x2="200" y2="141" stroke="currentColor" stroke-opacity=".22" stroke-width="1.4"/><line x1="60" y1="152" x2="190" y2="152" stroke="currentColor" stroke-opacity=".22" stroke-width="1.4"/><polygon points="62,90 236,90 208,122 34,122" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2"/><path d="M110,98 C130,94 156,98 160,108 C162,116 140,118 120,116 C104,114 98,102 110,98 Z" fill="var(--neuron)" fill-opacity=".45" stroke="var(--neuron)" stroke-width="1.8"/><polygon points="62,48 236,48 208,80 34,80" fill="var(--synapse)" fill-opacity=".1" stroke="var(--synapse)" stroke-width="2"/><circle cx="120" cy="62" r="3.6" fill="var(--synapse)"/><circle cx="158" cy="68" r="3.6" fill="var(--synapse)"/><circle cx="90" cy="70" r="3.6" fill="var(--synapse)"/><text x="248" y="68" font-size="12" class="mono" fill="var(--synapse)">ann</text><text x="248" y="110" font-size="12" class="mono" fill="var(--neuron)">seg</text><text x="248" y="152" font-size="12" class="mono" fill="var(--muted)">img</text></svg></div>
    <div class="acg-eb" style="color:#526278">TOOLS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neuroglancer-layer-img-seg-ann" title="Link to this term">Neuroglancer Layer (img/seg/ann)</a></h3>
    <p class="acg-def">The data layers in a Neuroglancer state. NOT the cortical layer.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-neuroglancer-state" data-cat="tools" data-hay="neuroglancer state json object storing all layers/view/annotations, identified by a state id. visualisation tools ">
    <div class="acg-eb" style="color:#526278">TOOLS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neuroglancer-state" title="Link to this term">Neuroglancer State</a></h3>
    <p class="acg-def">JSON object storing all layers/view/annotations, identified by a state id.</p>
    </article>
    <article class="acg-card" id="term-neurogliaform-cell" data-cat="celltypes" data-hay="neurogliaform cell (ngc) a type of interneuron that makes a diffuse axonal arbor and is thought to release gaba through both synaptic release and volume transmission, non-selectively inhibiting neurons nearby. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d-neurogliaform-cell"><title id="d-neurogliaform-cell">Neurogliaform cell</title><defs><clipPath id="d-neurogliaform-cell-c" clipPathUnits="userSpaceOnUse"><rect x="240" y="26" width="76" height="118"/></clipPath></defs><g transform="translate(160,100) scale(1.55) translate(-278,-88)"><g clip-path="url(#d-neurogliaform-cell-c)"><g stroke="var(--dendrite)" stroke-width="2" fill="none" stroke-linecap="round">
<path d="M50,73 V54 M50,73 l-9,-12 M50,73 l9,-12"/>
<path d="M126,121 V132 M126,121 l-8,9 M126,121 l8,9"/>
<path d="M202,85 V54 M202,54 l-5,-6 M202,54 l5,-6 M202,95 V128 M202,128 l-5,6 M202,128 l5,6"/>
</g>
<g stroke="var(--axon)" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
<path d="M50,83 V95 M50,95 C44,98 40,104 42,112 M50,95 C56,98 60,104 58,112"/>
<path d="M126,111 V54 M112,54 H140 M116,54 v-6 M126,54 v-6 M136,54 v-6"/>
<path d="M278,88 l0,-16 M278,88 l14,-8 M278,88 l16,0 M278,88 l14,8 M278,88 l0,16 M278,88 l-14,8 M278,88 l-16,0 M278,88 l-14,-8"/>
</g>
<g fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.6"><circle cx="42" cy="110" r="5"/><circle cx="58" cy="110" r="5"/></g>
<g fill="var(--neuron)"><circle cx="50" cy="78" r="5"/><circle cx="126" cy="116" r="5"/><circle cx="202" cy="90" r="5"/><circle cx="278" cy="88" r="5"/></g></g></g></svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neurogliaform-cell" title="Link to this term">Neurogliaform cell (NGC)</a></h3>
    <p class="acg-def">A type of interneuron that makes a diffuse axonal arbor and is thought to release GABA through both synaptic release and volume transmission, non-selectively inhibiting neurons nearby.</p>
    </article>
    <article class="acg-card" id="term-neuromodulatory-axon" data-cat="celltypes" data-hay="neuromodulatory axon a long-range axon carrying a neuromodulator rather than a fast transmitter. in em it is recognised by boutons packed with large dense-core vesicles and by branching that ignores laminar boundaries, since it acts over a volume rather than at a single partner. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neuromodulatory-axon" title="Link to this term">Neuromodulatory axon</a></h3>
    <p class="acg-def">A long-range axon carrying a neuromodulator rather than a fast transmitter. In EM it is recognised by boutons packed with large dense-core vesicles and by branching that ignores laminar boundaries, since it acts over a volume rather than at a single partner.</p>
    </article>
    <article class="acg-card" id="term-neuronal-process" data-cat="segmentation" data-hay="neuronal process an axon or dendrite branch of a neuron (a process that splits at branch points). segmentation &amp; reconstruction ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="nproc"><title id="nproc">Neuronal process</title><path d="M137,93 C116,80 104,70 90,50 M104,70 C100,60 98,52 100,42 M116,80 C110,72 104,70 92,64" fill="none" stroke="var(--dendrite)" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/><path d="M167,106 C210,112 240,116 276,132" fill="none" stroke="var(--axon)" stroke-width="2.6" stroke-linecap="round"/><circle cx="276" cy="132" r="5" fill="var(--axon)" fill-opacity=".4" stroke="var(--axon)" stroke-width="2"/><circle cx="150" cy="104" r="17" fill="var(--neuron)" fill-opacity=".25" stroke="var(--neuron)" stroke-width="2.4"/><text x="86" y="34" text-anchor="middle" font-size="11.5" fill="var(--dendrite)" font-weight="600">dendrite</text><text x="150" y="150" text-anchor="middle" font-size="11.5" fill="var(--neuron)" font-weight="600">soma</text><text x="228" y="118" text-anchor="middle" font-size="11.5" fill="var(--axon)" font-weight="600">axon</text></svg></div>
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neuronal-process" title="Link to this term">Neuronal process</a></h3>
    <p class="acg-def">An axon or dendrite branch of a neuron (a process that splits at branch points).</p>
    </article>
    <article class="acg-card" id="term-neuropixels" data-cat="modalities" data-hay="neuropixels a family of devices for obtaining high channel count single unit extracellular recordings created through a collaborative open science project funded by howard hughes medical institute, gatsby charitable trust, the wellcome trust, and the allen institute. these devices utilize modern integrated circuit design to miniaturize aspects of electrophysiology, enabling recordings of hundred of single units from a single probe with minimal brain damage. {cite:t}`jun2017` describes these probes; a summary can also be found here. recording modalities &amp; instruments ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="npx-t"><title id="npx-t">Neuropixels: dense electrode sites along one silicon shank</title><rect x="52" y="22" width="30" height="138" rx="3" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".5" stroke-width="2"/><path d="M52,158 L82,158 L67,182 Z" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-linejoin="round"/><path d="M57,36 h8v6h-8zM69,44 h8v6h-8zM57,52 h8v6h-8zM69,60 h8v6h-8zM57,68 h8v6h-8zM69,76 h8v6h-8zM57,84 h8v6h-8zM69,92 h8v6h-8zM57,100 h8v6h-8zM69,108 h8v6h-8zM57,116 h8v6h-8zM69,124 h8v6h-8zM57,132 h8v6h-8zM69,140 h8v6h-8z" fill="currentColor" fill-opacity=".45"/><text x="67" y="14" text-anchor="middle" font-size="10" fill="var(--muted)">one shank</text><text x="67" y="196" text-anchor="middle" font-size="9.5" class="mono" fill="var(--faint)">384 sites</text><path d="M96,56H132 M96,100H132 M96,144H132" stroke="currentColor" stroke-opacity=".3" stroke-width="1.6" stroke-dasharray="3 4"/><g fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" stroke="currentColor" stroke-opacity=".45"><path d="M140,56 h8 l4,-5 l5,20 l5,-16 c3,-5 6,-2 8,-1 h12"/><path d="M140,144 h8 l4,-5 l5,20 l5,-16 c3,-5 6,-2 8,-1 h12"/></g><path d="M140,100 h8 l4,-5 l5,20 l5,-16 c3,-5 6,-2 8,-1 h12" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><text x="216" y="26" text-anchor="middle" font-size="10.5" fill="var(--accent-ink)" font-weight="600">sorted units</text><text x="216" y="180" text-anchor="middle" font-size="9.5" fill="var(--muted)">hundreds per probe</text></svg></div>
    <div class="acg-eb" style="color:#c2410c">MODALITY</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-neuropixels" title="Link to this term">Neuropixels</a></h3>
    <p class="acg-def">A family of devices for obtaining high channel count single unit extracellular recordings created through a collaborative open science project funded by Howard Hughes Medical Institute, Gatsby Charitable Trust, the Wellcome Trust, and the Allen Institute. These devices utilize modern integrated circuit design to miniaturize aspects of electrophysiology, enabling recordings of hundred of single units from a single probe with minimal brain damage. {cite:t}`jun2017` describes these probes; a summary can also be found here.</p>
    </article>
    <article class="acg-card" id="term-nodes" data-cat="morphology" data-hay="nodes vertices in the skeleton / l2 graph. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-nodes" title="Link to this term">Nodes</a></h3>
    <p class="acg-def">Vertices in the skeleton / L2 graph.</p>
    </article>
    <article class="acg-card" id="term-non-neuronal-cell-types" data-cat="celltypes" data-hay="non-neuronal cell types the glial and vascular labels the cell-type tables use: astrocyte, microglia, oligo, opc and pericyte, carried under a classification_system of aibs_coarse_nonneuronal or nonneuron. cell types &amp; cortical anatomy microns">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-non-neuronal-cell-types" title="Link to this term">Non-neuronal cell types</a></h3>
    <p class="acg-def">The glial and vascular labels the cell-type tables use: <code>astrocyte</code>, <code>microglia</code>, <code>oligo</code>, <code>OPC</code> and <code>pericyte</code>, carried under a <code>classification_system</code> of <code>aibs_coarse_nonneuronal</code> or <code>nonneuron</code>.</p>
    <div class="acg-meta"><span class="acg-chip acg-ds">MICrONS only</span><a class="acg-chip acg-src" href="https://alleninstitute.github.io/microns_tutorial/" target="_blank" rel="noopener">MICrONS tutorial &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-nwb" data-cat="dataorg" data-hay="nwb (neurodata without borders) a standardized file format for physiology and behavior data. all of our physiology and behavior data is stored in nwb files. the visual coding and visual behavior data are in nwb files with a hdf backend, while the newer data (v1dd, bci, dynamic foraging, np ultra &amp; psychedelics) have a zarr backend - which is optimized for cloud access. more info can be found here datasets, sessions &amp; files ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="nwb-t"><title id="nwb-t">NWB: one format, two storage backends</title><rect x="20" y="72" width="66" height="56" rx="9" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".5" stroke-width="2"/><text x="53" y="105" text-anchor="middle" font-size="12" class="mono" fill="var(--muted)">NWB</text><text x="53" y="150" text-anchor="middle" font-size="9.5" fill="var(--faint)">one schema</text><path d="M90,100 C112,100 118,66 138,66 M90,100 C112,100 118,136 138,136" fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.8" stroke-linecap="round"/><rect x="146" y="44" width="38" height="46" rx="6" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="1.8"/><path d="M154,58 h22 M154,68 h22 M154,78 h22" stroke="currentColor" stroke-opacity=".4" stroke-width="2" stroke-linecap="round"/><text x="196" y="62" font-size="11" class="mono" fill="var(--muted)">HDF5</text><text x="196" y="78" font-size="9.5" fill="var(--faint)">one file</text><g fill="var(--accent)" fill-opacity=".2" stroke="var(--accent)" stroke-width="1.8"><rect x="146" y="114" width="16" height="16" rx="3"/><rect x="166" y="114" width="16" height="16" rx="3"/><rect x="146" y="134" width="16" height="16" rx="3"/><rect x="166" y="134" width="16" height="16" rx="3"/><rect x="146" y="154" width="16" height="16" rx="3"/><rect x="166" y="154" width="16" height="16" rx="3"/></g><text x="196" y="134" font-size="11" class="mono" fill="var(--accent-ink)" font-weight="600">Zarr</text><text x="196" y="150" font-size="9.5" fill="var(--faint)">chunked, cloud-read</text></svg></div>
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-nwb" title="Link to this term">NWB (Neurodata Without Borders)</a></h3>
    <p class="acg-def">A standardized file format for physiology and behavior data. All of our physiology and behavior data is stored in NWB files. The Visual Coding and Visual Behavior data are in NWB files with a hdf backend, while the newer data (V1DD, BCI, Dynamic Foraging, NP Ultra & Psychedelics) have a Zarr backend - which is optimized for cloud access. More info can be found here</p>
    </article>
    <article class="acg-card" id="term-ophys" data-cat="modalities" data-hay="ophys shorthand for optical physiology, often in reference to two-photon calcium imaging, but can also include other methods such as fiber photometry. recording modalities &amp; instruments ">
    <div class="acg-eb" style="color:#c2410c">MODALITY</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-ophys" title="Link to this term">Ophys</a></h3>
    <p class="acg-def">Shorthand for optical physiology, often in reference to Two-photon calcium imaging, but can also include other methods such as fiber photometry.</p>
    </article>
    <article class="acg-card" id="term-optogenetics" data-cat="genetics" data-hay="optogenetics a method for controlling the activity of neurons by expressing light activated ion channels (using a reporter line ) in a specific subpopulation of cells (using a driver line) to enable temporally precise control of neural spiking. spiking can be suppressed or enhanced using different types of reporters. see {cite:t}`peron2011` for a review on optogenetics as a method. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-optogenetics" title="Link to this term">Optogenetics</a></h3>
    <p class="acg-def">A method for controlling the activity of neurons by expressing light activated ion channels (using a reporter line ) in a specific subpopulation of cells (using a Driver line) to enable temporally precise control of neural spiking. Spiking can be suppressed or enhanced using different types of reporters. See {cite:t}`peron2011` for a review on optogenetics as a method.</p>
    </article>
    <article class="acg-card" id="term-optotagging" data-cat="genetics" data-hay="optotagging a technique that uses optogenetics in order to identify neurons that belong to a specific subpopulation. see: optotagging. genetic &amp; optical tools ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="opto-t"><title id="opto-t">Optotagging: tagged units follow the laser pulse train</title><path d="M44,58 H58 V38 H70 V58 H104 V38 H116 V58 H150 V38 H162 V58 H196 V38 H208 V58 H242 V38 H254 V58 H288 V38 H300 V58" fill="none" stroke="var(--accent)" stroke-width="2.2" stroke-linejoin="round" stroke-linecap="round"/><text x="44" y="28" font-size="9.5" class="mono" fill="var(--faint)">10 ms pulses · 20 Hz</text><g stroke="var(--accent)" stroke-width="2.2" stroke-linecap="round"><path d="M62,80 V102 M67,80 V102 M108,80 V102 M114,80 V102 M154,80 V102 M160,80 V102 M200,80 V102 M206,80 V102 M246,80 V102 M252,80 V102 M292,80 V102"/></g><text x="44" y="120" font-size="11" fill="var(--accent-ink)" font-weight="600">tagged unit</text><g stroke="currentColor" stroke-opacity=".65" stroke-width="2.2" stroke-linecap="round"><path d="M52,138 V160 M78,138 V160 M96,138 V160 M132,138 V160 M148,138 V160 M186,138 V160 M212,138 V160 M228,138 V160 M266,138 V160 M290,138 V160"/></g><text x="44" y="178" font-size="11" fill="var(--muted)">untagged unit</text><text x="300" y="178" text-anchor="end" font-size="9.5" fill="var(--faint)">spikes locked to pulses</text></svg></div>
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-optotagging" title="Link to this term">Optotagging</a></h3>
    <p class="acg-def">A technique that uses optogenetics in order to identify neurons that belong to a specific subpopulation. See: Optotagging.</p>
    </article>
    <article class="acg-card" id="term-oracle-score" data-cat="functional" data-hay="oracle score visual-response reliability — signal correlation across repeated “oracle” movies. functional data &amp; coregistration ">
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-oracle-score" title="Link to this term">Oracle score</a></h3>
    <p class="acg-def">Visual-response reliability — signal correlation across repeated “oracle” movies.</p>
    </article>
    <article class="acg-card" id="term-osi" data-cat="functional" data-hay="osi orientation selectivity index (0–1). functional data &amp; coregistration ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="osi-t"><title id="osi-t">OSI</title><text x="160" y="24" text-anchor="middle" font-size="14" class="mono" fill="var(--accent-ink)" font-weight="600">OSI</text><circle cx="86" cy="96" r="42" fill="none" stroke="currentColor" stroke-opacity=".2" stroke-width="1.4"/><line x1="44" y1="96" x2="128" y2="96" stroke="currentColor" stroke-opacity=".22" stroke-width="1.3"/><line x1="86" y1="54" x2="86" y2="138" stroke="currentColor" stroke-opacity=".22" stroke-width="1.3"/><path d="M86,96 C95,79 95,64 86,58 C77,64 77,79 86,96 Z" fill="var(--accent)" fill-opacity=".22" stroke="var(--accent)" stroke-width="2.2" stroke-linejoin="round"/><path d="M86,96 C95,113 95,130 86,134 C77,130 77,113 86,96 Z" fill="var(--accent)" fill-opacity=".22" stroke="var(--accent)" stroke-width="2.2" stroke-linejoin="round"/><text x="86" y="162" text-anchor="middle" font-size="10.5" fill="var(--muted)">sharp</text><text x="86" y="176" text-anchor="middle" font-size="9.5" class="mono" fill="var(--accent-ink)">OSI ≈ 1</text><circle cx="232" cy="96" r="42" fill="none" stroke="currentColor" stroke-opacity=".2" stroke-width="1.4"/><line x1="190" y1="96" x2="274" y2="96" stroke="currentColor" stroke-opacity=".22" stroke-width="1.3"/><line x1="232" y1="54" x2="232" y2="138" stroke="currentColor" stroke-opacity=".22" stroke-width="1.3"/><path d="M232,96 C258,79 258,64 232,58 C206,64 206,79 232,96 Z" fill="var(--accent)" fill-opacity=".12" stroke="var(--accent)" stroke-width="2.2" stroke-linejoin="round"/><path d="M232,96 C258,113 258,130 232,134 C206,130 206,113 232,96 Z" fill="var(--accent)" fill-opacity=".12" stroke="var(--accent)" stroke-width="2.2" stroke-linejoin="round"/><text x="232" y="162" text-anchor="middle" font-size="10.5" fill="var(--muted)">broad</text><text x="232" y="176" text-anchor="middle" font-size="9.5" class="mono" fill="var(--accent-ink)">OSI ≈ 0</text></svg></div>
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-osi" title="Link to this term">OSI</a></h3>
    <p class="acg-def">Orientation selectivity index (0–1).</p>
    </article>
    <article class="acg-card" id="term-pv-neuron" data-cat="celltypes" data-hay="parvalbumin-positive (pv+) neuron fast spiking neurons, also known as fast spiking interneurons, is a short-hand for parvalbumin positive gaba-ergic inhibitory interneurons found in many brain regions that have strong inhibitory effects on neighboring cells. in experimental preparations where the genetic identity of neurons can be paired with electrophysiological recordings, pv+ neurons have short action potentials, occasionally less than 400 µs. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-pv-neuron" title="Link to this term">Parvalbumin-positive (PV+) neuron</a></h3>
    <p class="acg-def">Fast spiking neurons, also known as fast spiking interneurons, is a short-hand for parvalbumin positive GABA-ergic inhibitory interneurons found in many brain regions that have strong inhibitory effects on neighboring cells. In experimental preparations where the genetic identity of neurons can be paired with electrophysiological recordings, PV+ neurons have short action potentials, occasionally less than 400 µS.</p>
    </article>
    <article class="acg-card" id="term-physiology" data-cat="datasets" data-hay="physiology the activity side of a functional-connectomics dataset: the calcium-imaging responses recorded from the same neurons that were later reconstructed in em. datasets &amp; scope ">
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-physiology" title="Link to this term">Physiology</a></h3>
    <p class="acg-def">The activity side of a functional-connectomics dataset: the calcium-imaging responses recorded from the same neurons that were later reconstructed in EM.</p>
    </article>
    <article class="acg-card" id="term-position" data-cat="volume" data-hay="position the 3d coordinate of a bound spatial point (pt_position, stored in voxels by default). volume, voxels &amp; coordinates ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="pos-t"><title id="pos-t">A position: point marker inside a voxel grid with (x, y, z) label</title><g stroke="currentColor" stroke-opacity=".28" stroke-width="1.5"><path d="M50,45 V165"/><path d="M80,45 V165"/><path d="M110,45 V165"/><path d="M140,45 V165"/><path d="M170,45 V165"/><path d="M200,45 V165"/><path d="M230,45 V165"/><path d="M50,45 H230"/><path d="M50,75 H230"/><path d="M50,105 H230"/><path d="M50,135 H230"/><path d="M50,165 H230"/></g><path d="M140,88 V122 M123,105 H157" stroke="var(--accent)" stroke-width="1.5" stroke-opacity=".7" stroke-linecap="round"/><circle cx="140" cy="105" r="5.5" fill="var(--accent)" stroke="var(--surface)" stroke-width="1.5"/><text x="163" y="101" font-size="11.5" class="mono" fill="var(--accent-ink)" font-weight="600">(x, y, z)</text><text x="140" y="186" text-anchor="middle" font-size="10.5" fill="var(--muted)">voxel grid</text></svg></div>
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-position" title="Link to this term">Position</a></h3>
    <p class="acg-def">The 3D coordinate of a bound spatial point (<code>pt_position</code>, stored in voxels by default).</p>
    </article>
    <article class="acg-card" id="term-precomputed-format" data-cat="cave" data-hay="precomputed format storage representation for arbitrarily large images/meshes/skeletons. cave — access &amp; versioning ">
    <div class="acg-eb" style="color:#0f766e">CAVE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-precomputed-format" title="Link to this term">Precomputed format</a></h3>
    <p class="acg-def">Storage representation for arbitrarily large images/meshes/skeletons.</p>
    </article>
    <article class="acg-card" id="term-primary-visual-cortex" data-cat="celltypes" data-hay="primary visual cortex (v1 / visp) the largest visual area in cortex that receives inputs from the lateral geniculate nucleus of thalamus. often referred to as v1 or visp. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-primary-visual-cortex" title="Link to this term">Primary visual cortex (V1 / VISp)</a></h3>
    <p class="acg-def">The largest visual area in cortex that receives inputs from the Lateral geniculate nucleus of thalamus. Often referred to as <b>V1</b> or <b>VISp</b>.</p>
    </article>
    <article class="acg-card" id="term-proofreading" data-cat="proofreading" data-hay="proofreading manual correction of split/merge errors to make neurons biologically accurate/complete. proofreading &amp; data quality ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="pp"><title id="pp">Proofreading — before and after</title>
<circle cx="46" cy="104" r="9" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.4"/>
<g fill="none" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
<path d="M46,95 C44,84 43,76 42,66"/>
<path d="M40,56 C39,48 38,42 37,34"/>
<path d="M46,104 C64,100 78,96 94,92"/>
<path d="M46,113 C46,130 44,142 42,156"/>
</g>
<path d="M36,64 L47,58" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round"/>
<path d="M94,92 C104,90 112,92 122,96" fill="none" stroke="var(--dendrite)" stroke-width="2.2" stroke-linecap="round"/>
<circle cx="94" cy="92" r="8" fill="none" stroke="var(--error)" stroke-width="2"/>
<path d="M90,88 l8,8 M98,88 l-8,8" stroke="var(--error)" stroke-width="1.8" stroke-linecap="round"/>
<text x="70" y="178" text-anchor="middle" font-size="9.5" fill="var(--error)">merge + split</text>
<path d="M150,100 L180,100" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2.4" stroke-linecap="round"/>
<path d="M173,95 L181,100 L173,105" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/>
<text x="165" y="90" text-anchor="middle" font-size="9" fill="var(--muted)">proofread</text>
<circle cx="240" cy="104" r="9" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.4"/>
<g fill="none" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
<path d="M240,95 C236,82 234,72 232,58"/>
<path d="M232,58 C228,52 226,50 222,44"/>
<path d="M240,104 C258,100 272,96 288,92"/>
<path d="M272,96 C280,94 285,95 291,98"/>
<path d="M240,113 C240,130 238,142 236,156"/>
</g>
<path d="M256,52 l5,6 l11,-13" fill="none" stroke="var(--ok)" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/>
<text x="248" y="178" text-anchor="middle" font-size="9.5" fill="var(--ok)">one clean neuron</text>
</svg></div>
    <div class="acg-eb" style="color:#b8791a">PROOF</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-proofreading" title="Link to this term">Proofreading</a></h3>
    <p class="acg-def">Manual correction of split/merge errors to make neurons biologically accurate/complete.</p>
    </article>
    <article class="acg-card" id="term-pychunkedgraph-pcg-l2-graph" data-cat="segmentation" data-hay="pychunkedgraph (pcg) / l2 graph hierarchical representation: l0 = voxels, l1 = supervoxels, l2 = supervoxels grouped within a chunk. segmentation &amp; reconstruction ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="pcg"><title id="pcg">PyChunkedGraph L2 graph</title><g stroke="currentColor" stroke-opacity=".4" stroke-width="1.5"><rect x="60" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="78" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="96" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="114" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="132" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="150" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="168" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/><rect x="186" y="150" width="14" height="14" fill="var(--scaffold)" fill-opacity=".16"/></g><g stroke="currentColor" stroke-opacity=".55" stroke-width="2"><rect x="74" y="98" width="22" height="22" fill="var(--scaffold)" fill-opacity=".3"/><rect x="104" y="98" width="22" height="22" fill="var(--scaffold)" fill-opacity=".3"/><rect x="134" y="98" width="22" height="22" fill="var(--scaffold)" fill-opacity=".3"/><rect x="164" y="98" width="22" height="22" fill="var(--scaffold)" fill-opacity=".3"/></g><circle cx="116" cy="48" r="12" fill="var(--accent)" fill-opacity=".3" stroke="var(--accent-ink)" stroke-width="2.2"/><circle cx="144" cy="48" r="12" fill="var(--accent)" fill-opacity=".3" stroke="var(--accent-ink)" stroke-width="2.2"/><g fill="none" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M130,148 V124"/><path d="M124,130 l6,-6 6,6"/><path d="M130,96 V66"/><path d="M124,72 l6,-6 6,6"/></g><text x="210" y="52" font-size="10.5" fill="var(--accent-ink)">L2 nodes <tspan class="mono" fill="var(--faint)">~10</tspan></text><text x="210" y="113" font-size="10.5" fill="var(--muted)">supervoxels <tspan class="mono" fill="var(--faint)">1e3</tspan></text><text x="210" y="160" font-size="10.5" fill="var(--muted)">voxels <tspan class="mono" fill="var(--faint)">1e6</tspan></text></svg></div>
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-pychunkedgraph-pcg-l2-graph" title="Link to this term">PyChunkedGraph (PCG) / L2 graph</a></h3>
    <p class="acg-def">Hierarchical representation: L0 = voxels, L1 = supervoxels, L2 = supervoxels grouped within a chunk.</p>
    </article>
    <article class="acg-card" id="term-pyramidal-cell" data-cat="celltypes" data-hay="pyramidal cell a type of excitatory neuron with a characteristic cell body shape and apical dendrite. in visual cortex, pyramidal cells are by far the most common type of excitatory neuron. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-pyramidal-cell" title="Link to this term">Pyramidal cell</a></h3>
    <p class="acg-def">A type of excitatory neuron with a characteristic cell body shape and apical dendrite. In visual cortex, pyramidal cells are by far the most common type of excitatory neuron.</p>
    </article>
    <article class="acg-card" id="term-radial-distance" data-cat="morphology" data-hay="radial distance depth measured along the local pia-to-white-matter streamline rather than along a straight line. cortex curves, so two cells the same euclidean distance apart can sit in different layers; following the streamline is what makes depth comparable across a volume. standard_transform.radial_distance computes it. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-radial-distance" title="Link to this term">Radial distance</a></h3>
    <p class="acg-def">Depth measured along the local pia-to-white-matter streamline rather than along a straight line. Cortex curves, so two cells the same Euclidean distance apart can sit in different layers; following the streamline is what makes depth comparable across a volume. <code>standard_transform.radial_distance</code> computes it.</p>
    </article>
    <article class="acg-card" id="term-radius" data-cat="morphology" data-hay="radius half the cable thickness at a skeleton vertex (µm). morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-rad"><title id="m-rad">Skeleton segment as tapering tube with radius callout</title><path d="M50,82 C120,78 200,92 260,98 L260,122 C200,128 120,142 50,138 Z" fill="var(--neuron)" fill-opacity=".16" stroke="var(--neuron)" stroke-width="2.2" stroke-linejoin="round"/><line x1="50" y1="110" x2="260" y2="110" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-dasharray="6 5" stroke-linecap="round"/><g fill="currentColor" fill-opacity=".7"><circle cx="50" cy="110" r="3.2"/><circle cx="155" cy="110" r="3.2"/><circle cx="260" cy="110" r="3.2"/></g><line x1="120" y1="80" x2="120" y2="140" stroke="currentColor" stroke-opacity=".3" stroke-width="1.2" stroke-dasharray="3 3"/><path d="M120,110 L120,84 M116,90 L120,84 L124,90 M116,104 L120,110 L124,104" fill="none" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><text x="130" y="94" font-size="11" class="mono" fill="var(--accent-ink)" font-weight="600">r = 1.2 µm</text><text x="155" y="164" text-anchor="middle" font-size="9.5" fill="var(--muted)">radius per skeleton vertex</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-radius" title="Link to this term">Radius</a></h3>
    <p class="acg-def">Half the cable thickness at a skeleton vertex (µm).</p>
    </article>
    <article class="acg-card" id="term-receptive-field" data-cat="responses" data-hay="receptive field in a sensory context, the receptive field of a neuron is the region of the stimulus domain in which sensory stimulus needs to lie in order to evoke a response. for visual cortical cells, for example, the receptive field is the region of visual space in which stimuli can evoke neural responses. in a computational context, this notion is often generalized multiple dimensions (e.g. space, time, frequency, etc.) and thus equates to the necessary stimulus features that drive neural response (e.g. a localized grating of a specific orientation and frequency). response properties &amp; analysis ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="rfd-t"><title id="rfd-t">Receptive field: only stimuli inside the region drive the cell</title><rect x="24" y="34" width="96" height="60" rx="4" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".45" stroke-width="1.8"/><ellipse cx="72" cy="64" rx="26" ry="18" fill="var(--accent)" fill-opacity=".14" stroke="var(--accent)" stroke-width="2" stroke-dasharray="4 4"/><rect x="64" y="56" width="16" height="16" rx="2" fill="currentColor" fill-opacity=".6"/><path d="M150,56v14M155,56v14M162,56v14M165,56v14M167,56v14M176,56v14M184,56v14M185,56v14M186,56v14M191,56v14M194,56v14M198,56v14M205,56v14M207,56v14" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round"/><text x="292" y="46" text-anchor="end" font-size="10" fill="var(--accent-ink)" font-weight="600">response</text><rect x="24" y="112" width="96" height="60" rx="4" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".45" stroke-width="1.8"/><ellipse cx="72" cy="142" rx="26" ry="18" fill="none" stroke="currentColor" stroke-opacity=".3" stroke-width="2" stroke-dasharray="4 4"/><rect x="98" y="118" width="16" height="16" rx="2" fill="currentColor" fill-opacity=".6"/><path d="M190,134v14M194,134v14M207,134v14" stroke="currentColor" stroke-opacity=".45" stroke-width="2.2" stroke-linecap="round"/><text x="292" y="124" text-anchor="end" font-size="10" fill="var(--muted)">no response</text><text x="72" y="22" text-anchor="middle" font-size="10" fill="var(--muted)">stimulus inside</text><text x="72" y="190" text-anchor="middle" font-size="10" fill="var(--muted)">stimulus outside</text></svg></div>
    <div class="acg-eb" style="color:#9f1239">RESPONSE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-receptive-field" title="Link to this term">Receptive field</a></h3>
    <p class="acg-def">In a sensory context, the receptive field of a neuron is the region of the stimulus domain in which sensory stimulus needs to lie in order to evoke a response. For visual cortical cells, for example, the receptive field is the region of visual space in which stimuli can evoke neural responses. In a computational context, this notion is often generalized multiple dimensions (e.g. space, time, frequency, etc.) and thus equates to the necessary stimulus features that drive neural response (e.g. a localized grating of a specific orientation and frequency).</p>
    </article>
    <article class="acg-card" id="term-regular-spiking-neuron" data-cat="celltypes" data-hay="regular spiking neuron (rs) neurons that, when injected with a long step of current in the context of intracellular recordings, show spike frequency adaptation where the rate of spiking decreases over time. these neurons also have longer (or wider) action potentials, and lower spike rates even when injected with large currents due to hyperpolarization after each action potential. these are the most common type of neurons in the mammalian cortex, and are often associated excitatory neurons. in extracellular recordings, neurons with longer action potentials are also sometimes referred to as regular spiking neurons, a feature which is used to associate these units with specific cell types, such as excitatory pyramidal neurons among others. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-regular-spiking-neuron" title="Link to this term">Regular spiking neuron (RS)</a></h3>
    <p class="acg-def">Neurons that, when injected with a long step of current in the context of intracellular recordings, show spike frequency adaptation where the rate of spiking decreases over time. These neurons also have longer (or wider) action potentials, and lower spike rates even when injected with large currents due to hyperpolarization after each action potential. These are the most common type of neurons in the mammalian cortex, and are often associated excitatory neurons. In extracellular recordings, neurons with longer action potentials are also sometimes referred to as regular spiking neurons, a feature which is used to associate these units with specific cell types, such as excitatory pyramidal neurons among others.</p>
    </article>
    <article class="acg-card" id="term-reporter" data-cat="genetics" data-hay="reporter an exogenous coding region joined to a promoter sequence or element in an expression vector that is introduced into cells to provide the means for measuring the promoter activity source. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-reporter" title="Link to this term">Reporter</a></h3>
    <p class="acg-def">An exogenous coding region joined to a promoter sequence or element in an expression vector that is introduced into cells to provide the means for measuring the promoter activity <a href="https://www.promega.com/resources/guides/cell-biology/bioluminescent-reporters/#:~:text=What%20is%20a%20Reporter%20Gene,for%20measuring%20the%20promoter%20activity." target="_blank" rel="noopener">source</a>.</p>
    </article>
    <article class="acg-card" id="term-reporter-line" data-cat="genetics" data-hay="reporter line a reporter line is a transgenic mouse line that is engineered to express a specific protein that enables monitoring or manipulation of neural activity (such as gfp, gcamp, or channelrhodopsin) under the control of cre or flp recombinase, or a tetracycline transactivator system. the gene engineered into the reporter line will not be expressed unless the protein that controls reporter gene expression (such as cre or flp) is present, such as by breeding a mouse from the reporter line with a mouse from a specific driver line that expresses the control protein. injecting a virus that delivers cre or flp in a cell type specific manner can also trigger the expression of the reporter gene. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-reporter-line" title="Link to this term">Reporter line</a></h3>
    <p class="acg-def">A <b>reporter line</b> is a transgenic mouse line that is engineered to express a specific protein that enables monitoring or manipulation of neural activity (such as GFP, GCaMP, or Channelrhodopsin) under the control of cre or FLP recombinase, or a tetracycline transactivator system. The gene engineered into the reporter line will not be expressed unless the protein that controls reporter gene expression (such as cre or FLP) is present, such as by breeding a mouse from the reporter line with a mouse from a specific Driver line that expresses the control protein. Injecting a virus that delivers cre or FLP in a cell type specific manner can also trigger the expression of the reporter gene.</p>
    </article>
    <article class="acg-card" id="term-residual-separation-score" data-cat="functional" data-hay="residual / separation score the two coregistration-quality metrics. functional data &amp; coregistration ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="resid-t"><title id="resid-t">Residual and separation score</title><circle cx="128" cy="30" r="5" fill="var(--accent)"/><circle cx="192" cy="30" r="5" fill="var(--neuron)"/><line x1="133" y1="30" x2="187" y2="30" stroke="currentColor" stroke-opacity=".5" stroke-width="2" stroke-dasharray="5 4"/><text x="160" y="20" text-anchor="middle" font-size="9.5" class="mono" fill="var(--muted)">coreg match</text><path d="M46,128 A46 46 0 0 1 138,128" fill="none" stroke="currentColor" stroke-opacity=".3" stroke-width="6" stroke-linecap="round"/><path d="M46,128 A46 46 0 0 1 70,89" fill="none" stroke="var(--ok)" stroke-width="6" stroke-linecap="round"/><line x1="92" y1="128" x2="63" y2="104" stroke="var(--accent)" stroke-width="3" stroke-linecap="round"/><circle cx="92" cy="128" r="5" fill="var(--accent)"/><text x="92" y="150" text-anchor="middle" font-size="10.5" fill="var(--muted)">residual</text><text x="92" y="165" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)">2.1 µm</text><path d="M186,128 A46 46 0 0 1 278,128" fill="none" stroke="currentColor" stroke-opacity=".3" stroke-width="6" stroke-linecap="round"/><path d="M254,89 A46 46 0 0 1 278,128" fill="none" stroke="var(--ok)" stroke-width="6" stroke-linecap="round"/><line x1="232" y1="128" x2="261" y2="104" stroke="var(--accent)" stroke-width="3" stroke-linecap="round"/><circle cx="232" cy="128" r="5" fill="var(--accent)"/><text x="232" y="150" text-anchor="middle" font-size="10.5" fill="var(--muted)">separation</text><text x="232" y="165" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)">0.92</text></svg></div>
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-residual-separation-score" title="Link to this term">Residual / Separation score</a></h3>
    <p class="acg-def">The two coregistration-quality metrics.</p>
    </article>
    <article class="acg-card" id="term-resolution" data-cat="volume" data-hay="resolution physical voxel size in nm/voxel (microns 4×4×40; v1dd 9×9×45); set per query via desired_resolution. volume, voxels &amp; coordinates ">
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-resolution" title="Link to this term">Resolution</a></h3>
    <p class="acg-def">Physical voxel size in nm/voxel (MICrONS 4×4×40; V1DD 9×9×45); set per query via <code>desired_resolution</code>.</p>
    </article>
    <article class="acg-card" id="term-retinotopy" data-cat="responses" data-hay="retinotopy retinotopy refers to the mapping of visual space on to neural space. most visual areas of the brain contain an orderly map of visual space such that neighboring regions in space are represented by neighboring regions in the brain. retinotopic maps are typically measured in terms of altitude (aka vertical retinotopy), referring to the axis from upper to lower visual field, and and azimuth (aka horizontal retinotopy), referring to the axis from left to right in space. response properties &amp; analysis ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ret-t"><title id="ret-t">Retinotopy: neighbouring points in visual space map to neighbouring cortex</title><rect x="30" y="44" width="100" height="100" rx="3" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".4" stroke-width="1.6"/><path d="M63,44 V144 M97,44 V144 M30,77 H130 M30,111 H130" stroke="currentColor" stroke-opacity=".18" stroke-width="1.2"/><circle cx="50" cy="68" r="5" fill="var(--accent)" fill-opacity="1"/><circle cx="108" cy="72" r="5" fill="currentColor" fill-opacity=".7"/><circle cx="76" cy="124" r="5" fill="currentColor" fill-opacity=".35"/><path d="M206,52 C252,40 296,62 292,96 C288,132 244,152 212,140 C186,130 180,68 206,52" fill="var(--scaffold)" fill-opacity=".18" stroke="currentColor" stroke-opacity=".45" stroke-width="1.8"/><circle cx="224" cy="76" r="5" fill="var(--accent)" fill-opacity="1"/><circle cx="272" cy="88" r="5" fill="currentColor" fill-opacity=".7"/><circle cx="238" cy="124" r="5" fill="currentColor" fill-opacity=".35"/><path d="M140,94 H166" stroke="currentColor" stroke-opacity=".5" stroke-width="1.8" stroke-linecap="round"/><polygon points="174,94 165,89 165,99" fill="currentColor" fill-opacity=".5"/><text x="157" y="84" text-anchor="middle" font-size="9" fill="var(--faint)">maps to</text><path d="M30,156 H92" stroke="currentColor" stroke-opacity=".4" stroke-width="1.5"/><polygon points="98,156 90,152 90,160" fill="currentColor" fill-opacity=".4"/><text x="112" y="159" font-size="9" fill="var(--faint)">azimuth</text><path d="M20,144 V60" stroke="currentColor" stroke-opacity=".4" stroke-width="1.5"/><polygon points="20,52 16,60 24,60" fill="currentColor" fill-opacity=".4"/><text x="14" y="102" text-anchor="middle" font-size="9" fill="var(--faint)" transform="rotate(-90 14 102)">altitude</text><text x="80" y="184" text-anchor="middle" font-size="10.5" fill="var(--muted)">visual field</text><text x="244" y="184" text-anchor="middle" font-size="10.5" fill="var(--muted)">cortex</text></svg></div>
    <div class="acg-eb" style="color:#9f1239">RESPONSE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-retinotopy" title="Link to this term">Retinotopy</a></h3>
    <p class="acg-def"><b>retinotopy</b> refers to the mapping of visual space on to neural space. Most visual areas of the brain contain an orderly map of visual space such that neighboring regions in space are represented by neighboring regions in the brain. Retinotopic maps are typically measured in terms of altitude (aka vertical retinotopy), referring to the axis from upper to lower visual field, and and azimuth (aka horizontal retinotopy), referring to the axis from left to right in space.</p>
    </article>
    <article class="acg-card" id="term-roi-mask" data-cat="signals" data-hay="roi mask a region of interest is a general term that describes a subregion of an image. when used in reference to two photon calcium imaging, an roi is the mask containing pixels thought to belong to a single neuron. signals &amp; preprocessing ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="roi-t"><title id="roi-t">ROI mask: the pixels assigned to one segmented cell</title><path d="M124,88h16v16h-16zM124,104h16v16h-16zM140,72h16v16h-16zM140,88h16v16h-16zM140,104h16v16h-16zM156,72h16v16h-16zM156,88h16v16h-16zM156,104h16v16h-16zM172,72h16v16h-16zM172,88h16v16h-16zM172,104h16v16h-16zM188,88h16v16h-16zM188,104h16v16h-16z" fill="var(--accent)" fill-opacity=".3"/><path d="M92,40V152M108,40V152M124,40V152M140,40V152M156,40V152M172,40V152M188,40V152M204,40V152M220,40V152M236,40V152M252,40V152M92,40H252M92,56H252M92,72H252M92,88H252M92,104H252M92,120H252M92,136H252M92,152H252" stroke="currentColor" stroke-opacity=".22" stroke-width="1"/><rect x="92" y="40" width="160" height="112" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="2"/><ellipse cx="164" cy="98" rx="38" ry="30" fill="none" stroke="var(--neuron)" stroke-width="2.4"/><text x="172" y="26" text-anchor="middle" font-size="10.5" fill="var(--muted)">imaging plane, pixel grid</text><text x="60" y="96" text-anchor="middle" font-size="10.5" fill="var(--accent-ink)" font-weight="600">mask</text><path d="M62,104 V122 C62,130 74,132 96,124" fill="none" stroke="var(--accent)" stroke-width="2" stroke-linecap="round"/><text x="172" y="176" text-anchor="middle" font-size="10" fill="var(--muted)">one ROI = pixels of one cell</text></svg></div>
    <div class="acg-eb" style="color:#0369a1">SIGNAL</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-roi-mask" title="Link to this term">ROI mask</a></h3>
    <p class="acg-def">A <b>region of interest</b> is a general term that describes a subregion of an image. When used in reference to two photon calcium imaging, an ROI is the mask containing pixels thought to belong to a single neuron.</p>
    </article>
    <article class="acg-card" id="term-root-id-pt-root-id" data-cat="segmentation" data-hay="root_id (pt_root_id) unique integer for a specific segmentation = a specific version of a cell (a.k.a. segment / object id). segmentation &amp; reconstruction ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="rootid"><title id="rootid">Root ID (pt_root_id)</title><circle cx="74" cy="100" r="16" fill="var(--neuron)" fill-opacity=".28" stroke="var(--neuron)" stroke-width="2.4"/><path d="M74,84 C66,64 58,56 48,44 M74,84 C84,66 94,60 106,50 M74,116 C74,140 82,148 92,158 M60,98 C44,94 34,94 24,88 M86,110 C100,116 108,120 116,128" fill="none" stroke="var(--neuron)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><path d="M126,96 H172" stroke="currentColor" stroke-opacity=".3" stroke-width="1.5" stroke-dasharray="2 4"/><text x="232" y="58" text-anchor="middle" font-size="11" class="mono" fill="var(--muted)">pt_root_id</text><text x="232" y="94" text-anchor="middle" font-size="18" class="mono" font-weight="600" fill="var(--accent-ink)">864691135…</text><text x="232" y="120" text-anchor="middle" font-size="10.5" fill="var(--muted)">changes with every edit</text></svg></div>
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-root-id-pt-root-id" title="Link to this term">Root_id (pt_root_id)</a></h3>
    <p class="acg-def">Unique integer for a specific segmentation = a specific version of a cell (a.k.a. segment / object id).</p>
    </article>
    <article class="acg-card" id="term-saccade" data-cat="celltypes" data-hay="saccade a rapid and ballistic eye movement that shifts the visual field between two fixation points. mice are not foveal animals, and their eye movements are different from foveal animals (such as humans). cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-saccade" title="Link to this term">Saccade</a></h3>
    <p class="acg-def">A rapid and ballistic eye movement that shifts the visual field between two fixation points. Mice are not foveal animals, and their eye movements are different from foveal animals (such as humans).</p>
    </article>
    <article class="acg-card" id="term-scan" data-cat="functional" data-hay="scan the scan_idx from functional imaging; part of the roi's unique id. functional data &amp; coregistration ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="scan-t"><title id="scan-t">Scan</title><text x="72" y="30" text-anchor="middle" font-size="10" fill="var(--muted)">ROI identity</text><rect x="16" y="42" width="112" height="34" rx="8" fill="var(--accent)" fill-opacity=".16" stroke="var(--accent)" stroke-width="2.6"/><text x="72" y="63" text-anchor="middle" font-size="13" class="mono" fill="var(--accent-ink)" font-weight="600">scan_idx</text><rect x="16" y="88" width="112" height="34" rx="8" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".35" stroke-width="2"/><text x="72" y="109" text-anchor="middle" font-size="13" class="mono" fill="var(--muted)">session</text><rect x="16" y="134" width="112" height="34" rx="8" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".35" stroke-width="2"/><text x="72" y="155" text-anchor="middle" font-size="13" class="mono" fill="var(--muted)">unit_id</text><text x="72" y="86" text-anchor="middle" font-size="15" fill="currentColor" opacity=".5">+</text><text x="72" y="132" text-anchor="middle" font-size="15" fill="currentColor" opacity=".5">+</text><path d="M128,59 C152,59 152,105 172,105" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><path d="M128,105 H172" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><path d="M128,151 C152,151 152,105 172,105" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><circle cx="172" cy="105" r="3.5" fill="currentColor" fill-opacity=".55"/><line x1="176" y1="105" x2="212" y2="105" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/><polygon points="218,105 210,101 210,109" fill="currentColor" fill-opacity=".55"/><circle cx="250" cy="105" r="30" fill="var(--neuron)" fill-opacity=".15" stroke="var(--neuron)" stroke-width="2.4"/><circle cx="250" cy="105" r="6" fill="var(--neuron)"/><text x="250" y="152" text-anchor="middle" font-size="10.5" fill="var(--muted)">unique ROI</text></svg></div>
    <div class="acg-eb" style="color:#9a5b12">FUNCTION</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-scan" title="Link to this term">Scan</a></h3>
    <p class="acg-def">The <code>scan_idx</code> from functional imaging; part of the ROI's unique id.</p>
    </article>
    <article class="acg-card" id="term-segmentation" data-cat="segmentation" data-hay="segmentation a 3d array where each voxel stores the root_id of the object at that location. segmentation &amp; reconstruction ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="segm"><title id="segm">Segmentation</title><rect x="22" y="54" width="118" height="100" fill="var(--scaffold)" fill-opacity=".1" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/><path d="M28,68 H134 M28,82 H134 M28,96 H134 M28,118 H134 M28,132 H134 M28,146 H134" stroke="currentColor" stroke-opacity=".16" stroke-width="2" stroke-linecap="round"/><path d="M81,54 V154 M22,104 H140" stroke="currentColor" stroke-opacity=".4" stroke-width="2"/><text x="81" y="172" text-anchor="middle" font-size="11" fill="var(--muted)">EM tile</text><path d="M146,104 H171" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round"/><path d="M167,98 l7,6 -7,6" fill="none" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><polygon points="180,54 239,54 239,104 180,104" fill="var(--neuron)" fill-opacity=".65"/><polygon points="239,54 298,54 298,104 239,104" fill="var(--dendrite)" fill-opacity=".65"/><polygon points="180,104 239,104 239,154 180,154" fill="var(--axon)" fill-opacity=".65"/><polygon points="239,104 298,104 298,154 239,154" fill="var(--synapse)" fill-opacity=".65"/><path d="M239,54 V154 M180,104 H298" stroke="var(--surface)" stroke-width="1.5"/><rect x="180" y="54" width="118" height="100" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2"/><text x="239" y="172" text-anchor="middle" font-size="11" fill="var(--muted)">by object id</text></svg></div>
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-segmentation" title="Link to this term">Segmentation</a></h3>
    <p class="acg-def">A 3D array where each voxel stores the root_id of the object at that location.</p>
    </article>
    <article class="acg-card" id="term-segments-root-object-id" data-cat="segmentation" data-hay="segments (= root/object id) “segment id” used as a synonym for root id — collides with the skeleton sense of “segment”. segmentation &amp; reconstruction ">
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-segments-root-object-id" title="Link to this term">Segments (= root/object id)</a></h3>
    <p class="acg-def">“Segment id” used as a synonym for root id — collides with the skeleton sense of “segment”.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-segments-skeleton" data-cat="morphology" data-hay="segments (skeleton) an unbranched run of vertices between branch/end points. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-seg"><title id="m-seg">One unbranched skeleton segment highlighted</title><path d="M55,160 L85,120 M85,120 L65,88 L48,58 M65,88 L80,56 M85,120 L118,96 L108,62 M118,96 L142,66" fill="none" stroke="currentColor" stroke-opacity=".5" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/><line x1="85" y1="120" x2="118" y2="96" stroke="var(--accent)" stroke-width="4.5" stroke-linecap="round"/><circle cx="55" cy="160" r="10" fill="var(--neuron)" fill-opacity=".18" stroke="var(--neuron)" stroke-width="2"/><g fill="currentColor" fill-opacity=".75" stroke="var(--surface)" stroke-width="1.2"><circle cx="85" cy="120" r="4.5"/><circle cx="65" cy="88" r="4.5"/></g><circle cx="85" cy="120" r="5.5" fill="none" stroke="var(--accent-ink)" stroke-width="2"/><circle cx="118" cy="96" r="5.5" fill="none" stroke="var(--accent-ink)" stroke-width="2"/><line x1="102" y1="108" x2="150" y2="120" stroke="var(--accent-ink)" stroke-width="1.5"/><text x="154" y="116" font-size="11" fill="var(--accent-ink)" font-weight="600">segment</text><text x="154" y="132" font-size="9" fill="var(--muted)">unbranched path</text><text x="154" y="144" font-size="9" fill="var(--muted)">between nodes</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-segments-skeleton" title="Link to this term">Segments (skeleton)</a></h3>
    <p class="acg-def">An unbranched run of vertices between branch/end points.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-serial-section-em" data-cat="imaging" data-hay="serial-section em many ultrathin sections are cut from a block, imaged one by one, then re-aligned into a volume. resolution is fine in x/y and coarse in z, so voxels are strongly anisotropic. imaging &amp; ultrastructure ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="sse-t"><title id="sse-t">Serial-section EM</title>
<polygon points="30,88 78,88 94,74 46,74" fill="var(--scaffold)" fill-opacity=".3" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="30,88 78,88 78,142 30,142" fill="var(--scaffold)" fill-opacity=".2" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<polygon points="78,88 94,74 94,128 78,142" fill="var(--scaffold)" fill-opacity=".12" stroke="currentColor" stroke-opacity=".55" stroke-width="1.8" stroke-linejoin="round"/>
<rect x="60" y="46" width="52" height="9" rx="1.5" transform="rotate(-7 86 50)" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6"/>
<rect x="66" y="34" width="52" height="9" rx="1.5" transform="rotate(4 92 38)" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6"/>
<rect x="72" y="22" width="52" height="9" rx="1.5" transform="rotate(-3 98 26)" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6"/>
<text x="62" y="160" text-anchor="middle" font-size="9.5" fill="var(--muted)">sections peel off</text>
<line x1="120" y1="100" x2="158" y2="100" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/>
<path d="M158,100 l-8,-4 M158,100 l-8,4" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/>
<text x="139" y="92" text-anchor="middle" font-size="9.5" fill="var(--muted)">align</text>
<polygon points="172,126 236,126 250,117 186,117" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,126 236,126 236,136 172,136" fill="var(--scaffold)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,113 236,113 250,104 186,104" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,113 236,113 236,123 172,123" fill="var(--scaffold)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,100 236,100 250,91 186,91" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,100 236,100 236,110 172,110" fill="var(--scaffold)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,87 236,87 250,78 186,78" fill="var(--scaffold)" fill-opacity=".28" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<polygon points="172,87 236,87 236,97 172,97" fill="var(--scaffold)" fill-opacity=".16" stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linejoin="round"/>
<line x1="204" y1="70" x2="222" y2="70" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<path d="M222,70 l-6,-3 M222,70 l-6,3" fill="none" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<line x1="204" y1="70" x2="192" y2="62" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<path d="M192,62 l1,6 M192,62 l6,1" fill="none" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<text x="200" y="52" text-anchor="middle" font-size="9.5" fill="var(--accent-ink)">fine x/y</text>
<line x1="262" y1="80" x2="262" y2="134" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<path d="M262,80 l-4,7 M262,80 l4,7 M262,134 l-4,-7 M262,134 l4,-7" fill="none" stroke="var(--accent-ink)" stroke-width="2" stroke-linecap="round"/>
<text transform="translate(280,107) rotate(-90)" text-anchor="middle" font-size="9.5" fill="var(--accent-ink)">coarse z</text>
<text x="205" y="160" text-anchor="middle" font-size="9.5" fill="var(--muted)">re-aligned stack</text>
</svg></div>
    <div class="acg-eb" style="color:#8a6f4a">IMAGING</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-serial-section-em" title="Link to this term">Serial-section EM</a></h3>
    <p class="acg-def">Many ultrathin sections are cut from a block, imaged one by one, then re-aligned into a volume. Resolution is fine in x/y and coarse in z, so voxels are strongly anisotropic.</p>
    </article>
    <article class="acg-card" id="term-session" data-cat="dataorg" data-hay="session a physiological and/or behavioral recording that happens at one time. datasets, sessions &amp; files ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="sess-t"><title id="sess-t">Session</title><text x="72" y="30" text-anchor="middle" font-size="10" fill="var(--muted)">ROI identity</text><rect x="16" y="42" width="112" height="34" rx="8" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".35" stroke-width="2"/><text x="72" y="63" text-anchor="middle" font-size="13" class="mono" fill="var(--muted)">scan_idx</text><rect x="16" y="88" width="112" height="34" rx="8" fill="var(--accent)" fill-opacity=".16" stroke="var(--accent)" stroke-width="2.6"/><text x="72" y="109" text-anchor="middle" font-size="13" class="mono" fill="var(--accent-ink)" font-weight="600">session</text><rect x="16" y="134" width="112" height="34" rx="8" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".35" stroke-width="2"/><text x="72" y="155" text-anchor="middle" font-size="13" class="mono" fill="var(--muted)">unit_id</text><text x="72" y="86" text-anchor="middle" font-size="15" fill="currentColor" opacity=".5">+</text><text x="72" y="132" text-anchor="middle" font-size="15" fill="currentColor" opacity=".5">+</text><path d="M128,59 C152,59 152,105 172,105" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><path d="M128,105 H172" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><path d="M128,151 C152,151 152,105 172,105" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><circle cx="172" cy="105" r="3.5" fill="currentColor" fill-opacity=".55"/><line x1="176" y1="105" x2="212" y2="105" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/><polygon points="218,105 210,101 210,109" fill="currentColor" fill-opacity=".55"/><circle cx="250" cy="105" r="30" fill="var(--neuron)" fill-opacity=".15" stroke="var(--neuron)" stroke-width="2.4"/><circle cx="250" cy="105" r="6" fill="var(--neuron)"/><text x="250" y="152" text-anchor="middle" font-size="10.5" fill="var(--muted)">unique ROI</text></svg></div>
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-session" title="Link to this term">Session</a></h3>
    <p class="acg-def">A physiological and/or behavioral recording that happens at one time.</p>
    </article>
    <article class="acg-card" id="term-skeletons" data-cat="morphology" data-hay="skeletons tree-like linear representation of a neuron's branching (vertices + edges, radius, compartments). morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-skel"><title id="m-skel">Cartoon neuron reduced to a skeleton</title><path d="M72,93 C68,72 60,60 52,50 M62,100 C44,92 34,86 24,80 M84,98 C100,86 108,78 118,66 M66,122 C54,138 46,146 38,158 M80,122 C92,140 96,150 100,162" fill="none" stroke="var(--neuron)" stroke-width="4.5" stroke-linecap="round"/><circle cx="72" cy="108" r="15" fill="var(--neuron)" fill-opacity=".3" stroke="var(--neuron)" stroke-width="2.2"/><path d="M150,105 L176,105 M170,100 L176,105 L170,110" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><text x="163" y="98" text-anchor="middle" font-size="9" class="mono" fill="var(--faint)">skeletonize</text><path d="M232,102 C228,82 220,70 212,60 M224,104 C206,96 196,90 186,84 M244,102 C260,90 268,82 278,70 M228,120 C216,136 208,144 200,156 M240,120 C252,138 256,148 260,160" fill="none" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linecap="round"/><circle cx="232" cy="108" r="6" fill="var(--neuron)" stroke="var(--surface)" stroke-width="1.5"/><text x="72" y="184" text-anchor="middle" font-size="10.5" fill="var(--muted)">neuron</text><text x="235" y="184" text-anchor="middle" font-size="10.5" fill="var(--muted)">skeleton</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-skeletons" title="Link to this term">Skeletons</a></h3>
    <p class="acg-def">Tree-like linear representation of a neuron's branching (vertices + edges, radius, compartments).</p>
    </article>
    <article class="acg-card" id="term-somatostatin-sst-cell" data-cat="celltypes" data-hay="somatostatin (sst) cell a type of inhibitory interneuron expressing the molecular marker somatostatin (sst, or sometimes som). sst cells tend to target the distal dendrites of excitatory neurons, and have important roles in regulating the activity of excitatory neurons. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-somatostatin-sst-cell" title="Link to this term">Somatostatin (SST) cell</a></h3>
    <p class="acg-def">A type of inhibitory interneuron expressing the molecular marker somatostatin (SST, or sometimes SOM). SST cells tend to target the distal dendrites of excitatory neurons, and have important roles in regulating the activity of excitatory neurons.</p>
    </article>
    <article class="acg-card" id="term-source-presynaptic" data-cat="connectivity" data-hay="source (presynaptic) the presynaptic partner of a synapse (pre_pt_root_id). connectivity &amp; synapses ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="src-t"><title id="src-t">Source (presynaptic)</title><text x="252" y="34" text-anchor="middle" font-size="9.5" fill="var(--faint)">target</text><path d="M258,44 C252,92 252,116 258,160" fill="none" stroke="var(--dendrite)" stroke-width="2.6" stroke-linecap="round" stroke-opacity=".5"/><circle cx="56" cy="98" r="22" fill="var(--neuron)" fill-opacity=".18" stroke="var(--neuron)" stroke-width="2.6"/><path d="M78,98 C120,98 168,98 204,98" fill="none" stroke="var(--axon)" stroke-width="2.6" stroke-linecap="round"/><path d="M214,98 l-11,-5 M214,98 l-11,5" fill="none" stroke="var(--axon)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/><circle cx="240" cy="98" r="6.5" fill="var(--synapse)"/><text x="56" y="150" text-anchor="middle" font-size="13" class="mono" fill="var(--axon)" font-weight="600">pre</text><text x="56" y="166" text-anchor="middle" font-size="9.5" fill="var(--muted)">presynaptic source</text></svg></div>
    <div class="acg-eb" style="color:#d1462c">CONNECT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-source-presynaptic" title="Link to this term">Source (presynaptic)</a></h3>
    <p class="acg-def">The presynaptic partner of a synapse (<code>pre_pt_root_id</code>).</p>
    </article>
    <article class="acg-card" id="term-spatial-frequency" data-cat="responses" data-hay="spatial frequency how often sinusoidal components of as signal or structure repeat per unit of distance. when used in reference to drifting gratings, spatial frequency means the distance between the bars of the grating. typically measured as cycles per degree. response properties &amp; analysis ">
    <div class="acg-eb" style="color:#9f1239">RESPONSE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-spatial-frequency" title="Link to this term">Spatial frequency</a></h3>
    <p class="acg-def">How often sinusoidal components of as signal or structure repeat per unit of distance. When used in reference to drifting gratings, spatial frequency means the distance between the bars of the grating. Typically measured as cycles per degree.</p>
    </article>
    <article class="acg-card" id="term-spectral-shape-analysis" data-cat="morphology" data-hay="spectral shape analysis (hks) shape descriptors computed from the heat kernel on a mesh, invariant to how the surface is bent. a classifier on these features drives the spine, shaft and soma predictions attached to synapses. morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-spectral-shape-analysis" title="Link to this term">Spectral shape analysis (HKS)</a></h3>
    <p class="acg-def">Shape descriptors computed from the heat kernel on a mesh, invariant to how the surface is bent. A classifier on these features drives the spine, shaft and soma predictions attached to synapses.</p>
    <div class="acg-meta"><a class="acg-chip acg-src" href="https://alleninstitute.github.io/microns_tutorial/" target="_blank" rel="noopener">MICrONS tutorial &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-split-errors" data-cat="proofreading" data-hay="split errors a process incorrectly appears to stop; they remove true connections. proofreading &amp; data quality ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ps"><title id="ps">Split errors — false split</title>
<circle cx="44" cy="104" r="10" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.4"/>
<g fill="none" stroke="var(--neuron)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
<path d="M54,102 C90,98 118,96 146,94"/>
<path d="M44,95 C40,82 38,72 36,58"/>
<path d="M44,113 C42,130 40,142 38,156"/>
<path d="M46,100 C60,90 68,86 78,80"/>
<path d="M176,94 C196,92 210,90 226,84"/>
<path d="M226,84 C236,80 242,78 250,72"/>
<path d="M210,90 C216,98 220,104 226,112"/>
<path d="M196,92 C200,100 202,106 204,114"/>
</g>
<path d="M146,94 L176,94" fill="none" stroke="var(--accent)" stroke-width="2" stroke-dasharray="3 5" stroke-opacity=".8"/>
<path d="M146,86 L146,102" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round"/>
<path d="M176,86 L176,102" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round"/>
<path d="M156,89 L149,94 L156,99" fill="none" stroke="var(--accent)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M166,89 L173,94 L166,99" fill="none" stroke="var(--accent)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<text x="160" y="182" text-anchor="middle" font-size="9.5" fill="var(--accent)">false split — removes a connection</text>
</svg></div>
    <div class="acg-eb" style="color:#b8791a">PROOF</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-split-errors" title="Link to this term">Split errors</a></h3>
    <p class="acg-def">A process incorrectly appears to stop; they remove true connections.</p>
    </article>
    <article class="acg-card" id="term-supervoxel-pt-supervoxel-id" data-cat="segmentation" data-hay="supervoxel (pt_supervoxel_id) l1 grouping of voxels within a chunk; the stable internal id an annotation binds to. segmentation &amp; reconstruction ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="svox"><title id="svox">Supervoxel</title><rect x="40" y="46" width="224" height="112" fill="var(--scaffold)" fill-opacity=".08"/><g stroke="currentColor" stroke-opacity=".3" stroke-width="1.5"><path d="M68,46 V158 M96,46 V158 M124,46 V158 M152,46 V158 M180,46 V158 M208,46 V158 M236,46 V158"/><path d="M40,74 H264 M40,102 H264 M40,130 H264"/></g><rect x="40" y="46" width="224" height="112" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><rect x="45" y="51" width="46" height="46" rx="6" fill="var(--neuron)" fill-opacity=".28" stroke="var(--neuron)" stroke-width="2.4"/><polygon points="129,51 175,51 175,97 157,97 157,79 129,79" fill="var(--axon)" fill-opacity=".25" stroke="var(--axon)" stroke-width="2.4" stroke-linejoin="round"/><rect x="213" y="107" width="46" height="46" rx="6" fill="var(--dendrite)" fill-opacity=".28" stroke="var(--dendrite)" stroke-width="2.4"/><text x="68" y="78" text-anchor="middle" font-size="10" class="mono" fill="var(--surface)">sv1</text><text x="147" y="64" text-anchor="middle" font-size="10" class="mono" fill="var(--surface)">sv2</text><text x="236" y="134" text-anchor="middle" font-size="10" class="mono" fill="var(--surface)">sv3</text><text x="40" y="38" font-size="10" class="mono" fill="var(--muted)">voxel grid</text><text x="152" y="180" text-anchor="middle" font-size="10.5" fill="var(--muted)">voxels merged into supervoxels</text></svg></div>
    <div class="acg-eb" style="color:#6d55e0">SEGMENT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-supervoxel-pt-supervoxel-id" title="Link to this term">Supervoxel (pt_supervoxel_id)</a></h3>
    <p class="acg-def">L1 grouping of voxels within a chunk; the stable internal id an annotation binds to.</p>
    </article>
    <article class="acg-card" id="term-swc-format" data-cat="morphology" data-hay="swc format standard skeleton file format (one of three: swc, meshwork-h5, precomputed). morphology — meshes &amp; skeletons ">
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-swc-format" title="Link to this term">SWC format</a></h3>
    <p class="acg-def">Standard skeleton file format (one of three: SWC, meshwork-h5, precomputed).</p>
    <div class="acg-meta"><a class="acg-chip acg-src" href="https://swc-specification.readthedocs.io/en/latest/" target="_blank" rel="noopener">SWC specification &#8599;</a></div>
    </article>
    <article class="acg-card" id="term-synapse-size" data-cat="connectivity" data-hay="synapse size synapse size in voxels; correlates with surface area / strength. connectivity &amp; synapses ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ss-t"><title id="ss-t">Synapse size — small vs large cleft</title><path d="M50,58 C70,54 92,54 112,58" fill="none" stroke="var(--axon)" stroke-width="2.4" stroke-linecap="round"/><path d="M50,104 C70,108 92,108 112,104" fill="none" stroke="var(--dendrite)" stroke-width="2.4" stroke-linecap="round"/><ellipse cx="81" cy="82" rx="9" ry="6" fill="var(--synapse)"/><rect x="65" y="118" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="77" y="118" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="89" y="118" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><text x="81" y="147" text-anchor="middle" font-size="10" fill="var(--muted)">small</text><text x="81" y="162" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)">3 vox</text><path d="M160,54 C192,48 250,48 282,54" fill="none" stroke="var(--axon)" stroke-width="2.4" stroke-linecap="round"/><path d="M160,108 C192,114 250,114 282,108" fill="none" stroke="var(--dendrite)" stroke-width="2.4" stroke-linecap="round"/><ellipse cx="221" cy="82" rx="30" ry="9" fill="var(--synapse)"/><rect x="180" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="192" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="204" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="216" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="228" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="240" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><rect x="252" y="120" width="10" height="10" rx="1.5" fill="var(--scaffold)" fill-opacity=".22" stroke="currentColor" stroke-opacity=".55" stroke-width="1.4"/><text x="221" y="149" text-anchor="middle" font-size="10" fill="var(--muted)">large</text><text x="221" y="164" text-anchor="middle" font-size="10" class="mono" fill="var(--accent-ink)">7 vox</text></svg></div>
    <div class="acg-eb" style="color:#d1462c">CONNECT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-synapse-size" title="Link to this term">Synapse size</a></h3>
    <p class="acg-def">Synapse size in voxels; correlates with surface area / strength.</p>
    </article>
    <article class="acg-card" id="term-target-postsynaptic" data-cat="connectivity" data-hay="target (postsynaptic) the postsynaptic partner of a synapse (post_pt_root_id). connectivity &amp; synapses ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="tgt-t"><title id="tgt-t">Target (postsynaptic)</title><text x="66" y="82" text-anchor="middle" font-size="9.5" fill="var(--faint)">pre</text><path d="M32,96 C82,96 128,96 168,96" fill="none" stroke="var(--axon)" stroke-width="2.6" stroke-linecap="round" stroke-opacity=".5"/><path d="M176,96 l-11,-5 M176,96 l-11,5" fill="none" stroke="var(--axon)" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" stroke-opacity=".5"/><circle cx="190" cy="96" r="6.5" fill="var(--synapse)"/><path d="M228,96 C214,96 206,96 200,96" fill="none" stroke="var(--dendrite)" stroke-width="2.6" stroke-linecap="round"/><path d="M250,76 C246,60 250,50 262,42" fill="none" stroke="var(--dendrite)" stroke-width="2.2" stroke-linecap="round"/><circle cx="250" cy="96" r="22" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.8"/><text x="250" y="150" text-anchor="middle" font-size="13" class="mono" fill="var(--neuron)" font-weight="600">post</text><text x="250" y="166" text-anchor="middle" font-size="9.5" fill="var(--muted)">postsynaptic target</text></svg></div>
    <div class="acg-eb" style="color:#d1462c">CONNECT</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-target-postsynaptic" title="Link to this term">Target (postsynaptic)</a></h3>
    <p class="acg-def">The postsynaptic partner of a synapse (<code>post_pt_root_id</code>).</p>
    </article>
    <article class="acg-card" id="term-targeted-structure" data-cat="dataorg" data-hay="targeted structure the brain region where data was collected from. datasets, sessions &amp; files ">
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-targeted-structure" title="Link to this term">Targeted structure</a></h3>
    <p class="acg-def">The brain region where data was collected from.</p>
    </article>
    <article class="acg-card" id="term-tem" data-cat="imaging" data-hay="tem transmission em; microns/v1dd are serial-section tem-style (thin sections, anisotropic z). imaging &amp; ultrastructure ">
    <div class="acg-eb" style="color:#8a6f4a">IMAGING</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-tem" title="Link to this term">TEM</a></h3>
    <p class="acg-def">Transmission EM; MICrONS/V1DD are serial-section TEM-style (thin sections, anisotropic z).</p>
    <div class="acg-meta"><span class="acg-chip acg-aside" title="An adjacent method, not used to acquire these datasets">adjacent method</span></div>
    </article>
    <article class="acg-card" id="term-temporal-frequency" data-cat="responses" data-hay="temporal frequency how many complete periods the signal goes through for a given unit of time. typically measured in hertz. response properties &amp; analysis ">
    <div class="acg-eb" style="color:#9f1239">RESPONSE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-temporal-frequency" title="Link to this term">Temporal frequency</a></h3>
    <p class="acg-def">How many complete periods the signal goes through for a given unit of time. Typically measured in Hertz.</p>
    </article>
    <article class="acg-card" id="term-transgenic-line" data-cat="genetics" data-hay="transgenic line a mouse line whose genome has been altered by the introduction of one or more foreign dna sequences. for these contexts, this typical involves using cre lines to drive the expression of a reporter line within a specific subset of cells. genetic &amp; optical tools ">
    <div class="acg-eb" style="color:#15803d">GENETIC</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-transgenic-line" title="Link to this term">Transgenic line</a></h3>
    <p class="acg-def">A mouse line whose genome has been altered by the introduction of one or more foreign DNA sequences. For these contexts, this typical involves using Cre lines to drive the expression of a Reporter line within a specific subset of cells.</p>
    </article>
    <article class="acg-card" id="term-two-photon-calcium-imaging" data-cat="modalities" data-hay="two-photon calcium imaging a term for techniques which measure neural activity of neurons by measuring a fluorescent calcium indicator. these indicators are usually a protein expressed in a cell, such as gcamp, often using a specific combination of driver line and reporter lines to express gcamp in a specific subset of neurons. fluorescent dyes can also be used to perform calcium imaging. at rest a neuron has low levels of calcium, and when the neuron spikes calcium flows into the neuron and raises the level of calcium, which binds to the calcium indicator and increases the emitted fluorescence in a specific wavelength. see {cite:t}`svoboda2006` for a review of two-photon calcium imaging. recording modalities &amp; instruments ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="tpci-t"><title id="tpci-t">Two-photon calcium imaging: a spike raises indicator fluorescence</title><path d="M22,104 H84" stroke="currentColor" stroke-opacity=".3" stroke-width="1.6" stroke-linecap="round"/><path d="M46,104 L53,58 L60,104" fill="none" stroke="currentColor" stroke-opacity=".8" stroke-width="2.2" stroke-linejoin="round"/><circle cx="152" cy="88" r="26" fill="var(--neuron)" fill-opacity=".2" stroke="var(--neuron)" stroke-width="2.4"/><g fill="none" stroke="currentColor" stroke-opacity=".6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M104,58 L124,72"/><path d="M117,70 L124,72 L122,65"/><path d="M104,118 L124,104"/><path d="M122,111 L124,104 L117,106"/></g><text x="96" y="94" text-anchor="middle" font-size="10" fill="var(--muted)">Ca²⁺</text><path d="M184,88 H206" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/><path d="M200,84 L206,88 L200,92" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M216,120 H306" stroke="currentColor" stroke-opacity=".3" stroke-width="1.6" stroke-linecap="round"/><path d="M216,116 L240,116 C246,116 248,60 256,60 C266,60 270,100 284,110 C292,115 298,116 306,116" fill="none" stroke="var(--accent)" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/><text x="53" y="174" text-anchor="middle" font-size="10.5" fill="var(--muted)">spike</text><text x="152" y="174" text-anchor="middle" font-size="10.5" fill="var(--muted)">calcium influx</text><text x="262" y="174" text-anchor="middle" font-size="10.5" fill="var(--accent-ink)" font-weight="600">fluorescence</text></svg></div>
    <div class="acg-eb" style="color:#c2410c">MODALITY</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-two-photon-calcium-imaging" title="Link to this term">Two-photon calcium imaging</a></h3>
    <p class="acg-def">A term for techniques which measure neural activity of neurons by measuring a fluorescent calcium indicator. These indicators are usually a protein expressed in a cell, such as GCaMP, often using a specific combination of Driver line and reporter lines to express GCaMP in a specific subset of neurons. Fluorescent dyes can also be used to perform calcium imaging. At rest a neuron has low levels of calcium, and when the neuron spikes calcium flows into the neuron and raises the level of calcium, which binds to the calcium indicator and increases the emitted fluorescence in a specific wavelength. See {cite:t}`svoboda2006` for a review of two-photon calcium imaging.</p>
    </article>
    <article class="acg-card" id="term-ultrastructure" data-cat="imaging" data-hay="ultrastructure fine sub-cellular em features: organelles, mitochondria, synapses, myelin. imaging &amp; ultrastructure ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="ult-t"><title id="ult-t">Ultrastructure</title>
<rect x="20" y="24" width="280" height="132" rx="4" fill="var(--scaffold)" fill-opacity=".1" stroke="currentColor" stroke-opacity=".6" stroke-width="2"/>
<ellipse cx="76" cy="74" rx="34" ry="20" fill="var(--scaffold)" fill-opacity=".32" stroke="currentColor" stroke-opacity=".5" stroke-width="2"/>
<path d="M60,60 q6,14 0,28 M76,58 q6,16 0,32 M92,60 q6,14 0,28" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="1.6" stroke-linecap="round"/>
<line x1="76" y1="46" x2="76" y2="54" stroke="currentColor" stroke-opacity=".4" stroke-width="1.4"/>
<text x="76" y="42" text-anchor="middle" font-size="9.5" fill="var(--muted)">mitochondrion</text>
<circle cx="205" cy="54" r="4.5" fill="var(--synapse)" fill-opacity=".35" stroke="var(--synapse)" stroke-width="1.5"/>
<circle cx="216" cy="50" r="4.5" fill="var(--synapse)" fill-opacity=".35" stroke="var(--synapse)" stroke-width="1.5"/>
<circle cx="226" cy="56" r="4.5" fill="var(--synapse)" fill-opacity=".35" stroke="var(--synapse)" stroke-width="1.5"/>
<circle cx="208" cy="64" r="4.5" fill="var(--synapse)" fill-opacity=".35" stroke="var(--synapse)" stroke-width="1.5"/>
<circle cx="219" cy="64" r="4.5" fill="var(--synapse)" fill-opacity=".35" stroke="var(--synapse)" stroke-width="1.5"/>
<circle cx="215" cy="59" r="4.5" fill="var(--synapse)" fill-opacity=".35" stroke="var(--synapse)" stroke-width="1.5"/>
<line x1="215" y1="45" x2="215" y2="39" stroke="var(--synapse)" stroke-opacity=".55" stroke-width="1.4"/>
<text x="215" y="35" text-anchor="middle" font-size="9.5" fill="var(--synapse)">synaptic vesicles</text>
<circle cx="252" cy="108" r="24" fill="none" stroke="var(--axon)" stroke-width="2" stroke-opacity=".9"/>
<circle cx="252" cy="108" r="18" fill="none" stroke="var(--axon)" stroke-width="2" stroke-opacity=".6"/>
<circle cx="252" cy="108" r="12" fill="none" stroke="var(--axon)" stroke-width="2" stroke-opacity=".9"/>
<circle cx="252" cy="108" r="6" fill="var(--scaffold)" fill-opacity=".4"/>
<line x1="252" y1="132" x2="258" y2="142" stroke="var(--axon)" stroke-opacity=".6" stroke-width="1.4"/>
<text x="264" y="152" text-anchor="middle" font-size="9.5" fill="var(--axon)">myelin</text>
<path d="M40,124 H150" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/>
<path d="M40,129 H150" fill="none" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/>
<line x1="95" y1="131" x2="95" y2="140" stroke="currentColor" stroke-opacity=".4" stroke-width="1.4"/>
<text x="95" y="151" text-anchor="middle" font-size="9.5" fill="var(--muted)">membrane</text>
</svg></div>
    <div class="acg-eb" style="color:#8a6f4a">IMAGING</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-ultrastructure" title="Link to this term">Ultrastructure</a></h3>
    <p class="acg-def">Fine sub-cellular EM features: organelles, mitochondria, synapses, myelin.</p>
    </article>
    <article class="acg-card" id="term-unit" data-cat="dataorg" data-hay="unit a putative neuron in extracellular electrophysiology, with varying degrees of confidence assigned to it. in extracellular electrophysiology, neurons are referred to as units, because we cannot guarantee that all the spikes assigned to one unit actually originate from a single cell. unlike in two-photon imaging, where you can visualize each neuron throughout the entire experiment, with electrophysiology we can only “see” a neuron when it fires a spike. if a neuron moves relative to the probe, or if it’s far away from the probe, some of its spikes may get mixed together with those from other neurons. because of this inherent ambiguity, quality metrics allow you to find the right units for your analysis. even highly contaminated units can contain potentially valuable information about brain states, but certain types of analysis require more stringent quality thresholds to ensure that all of the included units are well isolated from their neighbors. datasets, sessions &amp; files ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="unit-t"><title id="unit-t">Unit</title><text x="72" y="30" text-anchor="middle" font-size="10" fill="var(--muted)">ROI identity</text><rect x="16" y="42" width="112" height="34" rx="8" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".35" stroke-width="2"/><text x="72" y="63" text-anchor="middle" font-size="13" class="mono" fill="var(--muted)">scan_idx</text><rect x="16" y="88" width="112" height="34" rx="8" fill="var(--surface-2)" stroke="currentColor" stroke-opacity=".35" stroke-width="2"/><text x="72" y="109" text-anchor="middle" font-size="13" class="mono" fill="var(--muted)">session</text><rect x="16" y="134" width="112" height="34" rx="8" fill="var(--accent)" fill-opacity=".16" stroke="var(--accent)" stroke-width="2.6"/><text x="72" y="155" text-anchor="middle" font-size="13" class="mono" fill="var(--accent-ink)" font-weight="600">unit_id</text><text x="72" y="86" text-anchor="middle" font-size="15" fill="currentColor" opacity=".5">+</text><text x="72" y="132" text-anchor="middle" font-size="15" fill="currentColor" opacity=".5">+</text><path d="M128,59 C152,59 152,105 172,105" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><path d="M128,105 H172" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><path d="M128,151 C152,151 152,105 172,105" fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="2"/><circle cx="172" cy="105" r="3.5" fill="currentColor" fill-opacity=".55"/><line x1="176" y1="105" x2="212" y2="105" stroke="currentColor" stroke-opacity=".55" stroke-width="2" stroke-linecap="round"/><polygon points="218,105 210,101 210,109" fill="currentColor" fill-opacity=".55"/><circle cx="250" cy="105" r="30" fill="var(--neuron)" fill-opacity=".15" stroke="var(--neuron)" stroke-width="2.4"/><circle cx="250" cy="105" r="6" fill="var(--neuron)"/><text x="250" y="152" text-anchor="middle" font-size="10.5" fill="var(--muted)">unique ROI</text></svg></div>
    <div class="acg-eb" style="color:#3f3f46">DATA</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-unit" title="Link to this term">Unit</a></h3>
    <p class="acg-def">A putative neuron in extracellular electrophysiology, with varying degrees of confidence assigned to it. In extracellular electrophysiology, neurons are referred to as <i>units</i>, because we cannot guarantee that all the spikes assigned to one unit actually originate from a single cell. Unlike in two-photon imaging, where you can visualize each neuron throughout the entire experiment, with electrophysiology we can only “see” a neuron when it fires a spike. If a neuron moves relative to the probe, or if it’s far away from the probe, some of its spikes may get mixed together with those from other neurons. Because of this inherent ambiguity, quality metrics allow you to find the right units for your analysis. Even highly contaminated units can contain potentially valuable information about brain states, but certain types of analysis require more stringent quality thresholds to ensure that all of the included units are well isolated from their neighbors.</p>
    <div class="acg-meta"><span class="acg-chip acg-warn" title="This word means different things in different places">&#9888; ambiguous</span></div>
    </article>
    <article class="acg-card" id="term-v1dd-v1-deep-dive" data-cat="datasets" data-hay="v1dd (v1 deep-dive) functional (2p/3p calcium) + em dataset of v1 across all layers in 4 mice (~50k neurons/mouse). datasets &amp; scope v1dd">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="d6"><title id="d6">V1DD (V1 Deep-Dive)</title><polygon points="95,55 215,55 250,32 130,32" fill="var(--scaffold)" fill-opacity=".26" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8"/><polygon points="215,55 250,32 250,155 215,178" fill="var(--scaffold)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8"/><polygon points="95,55 215,55 215,178 95,178" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".6" stroke-width="1.8"/><text x="155" y="50" text-anchor="middle" font-size="9" class="mono" fill="var(--muted)">800 µm</text><text transform="translate(240,40) rotate(-33)" text-anchor="middle" font-size="9" class="mono" fill="var(--muted)">800 µm</text><g stroke="currentColor" stroke-opacity=".5" stroke-width="1.6" stroke-linecap="round"><line x1="88" y1="62" x2="88" y2="170"/></g><g fill="currentColor" fill-opacity=".5"><polygon points="88,58 85,64 91,64"/><polygon points="88,174 85,168 91,168"/></g><text x="88" y="50" text-anchor="middle" font-size="9" fill="var(--muted)">pia</text><text x="88" y="184" text-anchor="middle" font-size="9" fill="var(--muted)">WM</text><text transform="translate(76,116) rotate(-90)" text-anchor="middle" font-size="8.5" fill="var(--faint)">cortical depth</text><rect x="236" y="163" width="72" height="26" rx="6" fill="var(--accent)" fill-opacity=".18" stroke="var(--accent-ink)" stroke-width="1.8"/><text x="272" y="180" text-anchor="middle" font-size="12" fill="var(--accent-ink)" font-weight="700">×4 mice</text></svg></div>
    <div class="acg-eb" style="color:#0e7f8c">DATASETS</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-v1dd-v1-deep-dive" title="Link to this term">V1DD (V1 Deep-Dive)</a></h3>
    <p class="acg-def">Functional (2p/3p calcium) + EM dataset of V1 across all layers in 4 mice (~50k neurons/mouse).</p>
    <div class="acg-meta"><span class="acg-chip acg-ds">V1DD only</span></div>
    </article>
    <article class="acg-card" id="term-vertex-vertices" data-cat="morphology" data-hay="vertex / vertices points in 3d (n×3, nanometers) that, connected, build meshes and skeletons. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-vert"><title id="m-vert">Vertices tracing a neuron outline</title><g fill="none" stroke="currentColor" stroke-opacity=".4" stroke-width="1.8" stroke-linecap="round"><path d="M55,120 L70,100 L88,112 M88,112 L105,100 L140,88 L180,80 L220,72 L255,66"/><path d="M255,66 L258,96"/><path d="M258,96 L226,104 L188,112 L148,120 L112,132 L78,138"/><path d="M78,138 L58,142 L55,120"/></g><g fill="var(--neuron)"><circle cx="55" cy="120" r="3.6"/><circle cx="70" cy="100" r="3.6"/><circle cx="88" cy="112" r="3.6"/><circle cx="105" cy="100" r="3.6"/><circle cx="180" cy="80" r="3.6"/><circle cx="220" cy="72" r="3.6"/><circle cx="255" cy="66" r="3.6"/><circle cx="258" cy="96" r="3.6"/><circle cx="226" cy="104" r="3.6"/><circle cx="188" cy="112" r="3.6"/><circle cx="148" cy="120" r="3.6"/><circle cx="112" cy="132" r="3.6"/><circle cx="78" cy="138" r="3.6"/><circle cx="58" cy="142" r="3.6"/></g><g fill="var(--neuron)" fill-opacity=".45"><circle cx="130" cy="58" r="3.2"/><circle cx="205" cy="145" r="3.2"/></g><circle cx="140" cy="88" r="6" fill="var(--neuron)" stroke="var(--accent-ink)" stroke-width="2"/><line x1="140" y1="80" x2="150" y2="60" stroke="var(--accent-ink)" stroke-width="1.5"/><text x="152" y="58" font-size="11" fill="var(--accent-ink)" font-weight="600">vertex</text><text x="150" y="184" text-anchor="middle" font-size="9.5" fill="var(--muted)">3D points sampling the surface</text></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-vertex-vertices" title="Link to this term">Vertex / Vertices</a></h3>
    <p class="acg-def">Points in 3D (N×3, nanometers) that, connected, build meshes and skeletons.</p>
    </article>
    <article class="acg-card" id="term-vip-cell" data-cat="celltypes" data-hay="vip cell a type of inhibitory interneuron expressing the molecular marker vasoactive intestinal protein. vip cells tend to target somatostatin cells rather than excitatory neurons. this role as a &quot;disinhibitory specialist&quot; is thought to be important for context-dependent modulation of cortical activity. many vip cells have a characteristic bipolar axon that points along the axis of the cortical column and are thus often called &quot;bipolar cells&quot;. cell types &amp; cortical anatomy ">
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-vip-cell" title="Link to this term">VIP cell</a></h3>
    <p class="acg-def">A type of inhibitory interneuron expressing the molecular marker Vasoactive Intestinal Protein. VIP cells tend to target Somatostatin cells rather than excitatory neurons. This role as a "disinhibitory specialist" is thought to be important for context-dependent modulation of cortical activity. Many VIP cells have a characteristic bipolar axon that points along the axis of the cortical column and are thus often called "bipolar cells".</p>
    </article>
    <article class="acg-card" id="term-visp-visal-visrl" data-cat="celltypes" data-hay="visp / visal / visrl the visual cortical areas (v1 / al / rl / lm) the volume spans and assigns. cell types &amp; cortical anatomy ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="vp-t"><title id="vp-t">Mouse visual area flat-map patch</title>
<rect x="40" y="34" width="240" height="140" rx="28" fill="currentColor" fill-opacity=".04" stroke="currentColor" stroke-opacity=".25" stroke-width="1.6"/>
<ellipse cx="180" cy="112" rx="62" ry="48" fill="var(--accent)" fill-opacity=".18" stroke="var(--accent)" stroke-width="2.4"/>
<g fill="currentColor" fill-opacity=".05" stroke="currentColor" stroke-opacity=".6" stroke-width="2">
<ellipse cx="150" cy="52" rx="24" ry="18"/>
<ellipse cx="104" cy="68" rx="24" ry="20"/>
<ellipse cx="106" cy="120" rx="26" ry="24"/>
</g>
<text x="180" y="110" text-anchor="middle" font-size="16" font-weight="700" fill="var(--accent-ink)">V1</text>
<text x="180" y="126" text-anchor="middle" class="mono" font-size="9" fill="var(--accent-ink)">VISp</text>
<text x="150" y="50" text-anchor="middle" font-size="11" font-weight="600" fill="var(--muted)">RL</text>
<text x="150" y="61" text-anchor="middle" class="mono" font-size="7.5" fill="var(--faint)">VISrl</text>
<text x="104" y="66" text-anchor="middle" font-size="11" font-weight="600" fill="var(--muted)">AL</text>
<text x="104" y="77" text-anchor="middle" class="mono" font-size="7.5" fill="var(--faint)">VISal</text>
<text x="106" y="119" text-anchor="middle" font-size="11" font-weight="600" fill="var(--muted)">LM</text>
<text x="106" y="131" text-anchor="middle" class="mono" font-size="7.5" fill="var(--faint)">VISl</text>
<path d="M66,170 V154 M66,154 l-3,5 M66,154 l3,5 M66,170 H50 M50,170 l5,-3 M50,170 l5,3" stroke="currentColor" stroke-opacity=".55" stroke-width="1.6" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
<text x="66" y="150" text-anchor="middle" class="mono" font-size="8" fill="var(--muted)">A</text>
<text x="44" y="173" text-anchor="middle" class="mono" font-size="8" fill="var(--muted)">L</text>
</svg></div>
    <div class="acg-eb" style="color:#c9357f">CELLTYPE</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-visp-visal-visrl" title="Link to this term">VISp / VISal / VISrl</a></h3>
    <p class="acg-def">The visual cortical areas (V1 / AL / RL / LM) the volume spans and assigns.</p>
    </article>
    <article class="acg-card" id="term-volume" data-cat="volume" data-hay="volume a cubic-mm 3d em image dataset spanning a cortical region. volume, voxels &amp; coordinates ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="vol-t"><title id="vol-t">Cortical EM volume with a zoom-in to a single voxel</title><polygon points="40,70 120,70 120,165 40,165" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linejoin="round"/><polygon points="40,70 120,70 150,50 70,50" fill="var(--scaffold)" fill-opacity=".26" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linejoin="round"/><polygon points="120,70 150,50 150,145 120,165" fill="var(--scaffold)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".7" stroke-width="2" stroke-linejoin="round"/><rect x="104" y="74" width="9" height="9" fill="var(--accent)" fill-opacity=".28" stroke="var(--accent)" stroke-width="1.5"/><text x="95" y="184" text-anchor="middle" font-size="11" fill="var(--muted)">EM volume</text><path d="M113,74 L235,78 M113,83 L235,132" fill="none" stroke="var(--accent)" stroke-opacity=".8" stroke-width="1.5" stroke-dasharray="4 3"/><polygon points="235,78 258,78 258,138 235,138" fill="var(--scaffold)" fill-opacity=".14" stroke="var(--accent)" stroke-width="2" stroke-linejoin="round"/><polygon points="235,78 258,78 272,66 249,66" fill="var(--scaffold)" fill-opacity=".26" stroke="var(--accent)" stroke-width="2" stroke-linejoin="round"/><polygon points="258,78 272,66 272,126 258,138" fill="var(--scaffold)" fill-opacity=".07" stroke="var(--accent)" stroke-width="2" stroke-linejoin="round"/><text x="253" y="158" text-anchor="middle" font-size="11" fill="var(--accent-ink)" font-weight="600">1 voxel</text></svg></div>
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-volume" title="Link to this term">Volume</a></h3>
    <p class="acg-def">A cubic-mm 3D EM image dataset spanning a cortical region.</p>
    </article>
    <article class="acg-card" id="term-vortex" data-cat="proofreading" data-hay="vortex nih program (virtual observatory of the cortex) funding continued proofreading; source of the vortex_* tables. proofreading &amp; data quality ">
    <div class="acg-eb" style="color:#b8791a">PROOF</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-vortex" title="Link to this term">VORTEX</a></h3>
    <p class="acg-def">NIH program (Virtual Observatory of the Cortex) funding continued proofreading; source of the <code>vortex_*</code> tables.</p>
    </article>
    <article class="acg-card" id="term-voxel" data-cat="volume" data-hay="voxel the smallest 3d image unit; anisotropic 4×4×40 nm (microns) / 9×9×45 nm (v1dd). volume, voxels &amp; coordinates ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="voxel-t"><title id="voxel-t">Voxel: anisotropic, z ~10x coarser than x and y</title><polygon points="110,55 150,55 150,165 110,165" fill="var(--scaffold)" fill-opacity=".14" stroke="currentColor" stroke-opacity=".65" stroke-width="2" stroke-linejoin="round"/><polygon points="110,55 150,55 184,35 144,35" fill="var(--scaffold)" fill-opacity=".26" stroke="currentColor" stroke-opacity=".65" stroke-width="2" stroke-linejoin="round"/><polygon points="150,55 184,35 184,145 150,165" fill="var(--scaffold)" fill-opacity=".07" stroke="currentColor" stroke-opacity=".65" stroke-width="2" stroke-linejoin="round"/><text x="130" y="182" text-anchor="middle" font-size="11" class="mono" fill="var(--muted)">4 nm</text><text x="170" y="30" text-anchor="middle" font-size="11" class="mono" fill="var(--muted)">4 nm</text><text transform="translate(96,110) rotate(-90)" text-anchor="middle" font-size="12" class="mono" fill="var(--accent-ink)" font-weight="600">40 nm</text></svg></div>
    <div class="acg-eb" style="color:#2f6fd0">VOLUME</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-voxel" title="Link to this term">Voxel</a></h3>
    <p class="acg-def">The smallest 3D image unit; anisotropic 4×4×40 nm (MICrONS) / 9×9×45 nm (V1DD).</p>
    </article>
    <article class="acg-card" id="term-watertight" data-cat="morphology" data-hay="watertight em meshes are not watertight, so trimesh .volume/.center_mass are invalid. morphology — meshes &amp; skeletons ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="m-water"><title id="m-water">Mesh hole flagged as not watertight</title><polygon points="58,40 118,34 178,40 238,36 244,116 184,120 124,118 64,122" fill="var(--scaffold)" fill-opacity=".12"/><g fill="none" stroke="currentColor" stroke-opacity=".45" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M58,40 L118,34 L178,40 L238,36"/><path d="M50,82 L110,78 L170,80 L230,76"/><path d="M64,122 L124,118 L184,120 L244,116"/><path d="M58,40 L50,82 M118,34 L110,78 M178,40 L170,80 M238,36 L230,76"/><path d="M50,82 L64,122 M110,78 L124,118 M170,80 L184,120 M230,76 L244,116"/><path d="M118,34 L50,82 M238,36 L170,80"/><path d="M110,78 L64,122 M170,80 L124,118 M230,76 L184,120"/></g><polygon points="110,78 170,80 124,118" fill="var(--surface)" stroke="var(--error)" stroke-width="2.6" stroke-dasharray="5 4" stroke-linejoin="round"/><line x1="140" y1="98" x2="140" y2="62" stroke="var(--error)" stroke-width="1.5"/><text x="140" y="58" text-anchor="middle" font-size="10.5" fill="var(--error)" font-weight="600">hole</text><g transform="rotate(-5 227 172)"><rect x="150" y="159" width="155" height="26" rx="5" fill="none" stroke="var(--error)" stroke-width="2" stroke-dasharray="4 3"/><text x="227" y="177" text-anchor="middle" font-size="12" fill="var(--error)" font-weight="700">⚠ not watertight</text></g></svg></div>
    <div class="acg-eb" style="color:#2a8f57">MORPH</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-watertight" title="Link to this term">Watertight</a></h3>
    <p class="acg-def">EM meshes are NOT watertight, so Trimesh <code>.volume</code>/<code>.center_mass</code> are invalid.</p>
    </article>
    <article class="acg-card" id="term-waveform" data-cat="signals" data-hay="waveform in a system neuroscience setting, this often refers to the voltage over time measured with an electrode when an individual neuron produces an action potential. signals &amp; preprocessing ">
    <div class="acg-art"><svg viewBox="0 0 320 200" role="img" aria-labelledby="wfm-t"><title id="wfm-t">Spike waveform: trough and repolarisation peak of the mean spike</title><path d="M36,96 H284" stroke="currentColor" stroke-opacity=".25" stroke-width="1.6"/><g fill="none" stroke="currentColor" stroke-opacity=".22" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M36,96 H98 C106,96 110,90 114,86 L122,150 L142,66 C150,50 158,52 166,68 C174,84 184,94 200,96 H284" transform="translate(-3,-7)"/><path d="M36,96 H98 C106,96 110,90 114,86 L122,150 L142,66 C150,50 158,52 166,68 C174,84 184,94 200,96 H284" transform="translate(3,8)"/></g><path d="M36,96 H98 C106,96 110,90 114,86 L122,150 L142,66 C150,50 158,52 166,68 C174,84 184,94 200,96 H284" fill="none" stroke="var(--accent)" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/><circle cx="122" cy="150" r="3.4" fill="var(--accent-ink)"/><circle cx="159" cy="60" r="3.4" fill="var(--accent-ink)"/><text x="122" y="172" text-anchor="middle" font-size="10" fill="var(--muted)">trough</text><text x="176" y="52" font-size="10" fill="var(--muted)">peak</text><text x="30" y="70" font-size="9.5" class="mono" fill="var(--faint)">µV</text><text x="284" y="112" text-anchor="end" font-size="9.5" class="mono" fill="var(--faint)">~3 ms</text><text x="60" y="188" font-size="10" fill="var(--muted)">single spikes</text><line x1="140" y1="184" x2="164" y2="184" stroke="var(--accent)" stroke-width="2.6" stroke-linecap="round"/><text x="170" y="188" font-size="10" fill="var(--accent-ink)" font-weight="600">mean waveform</text></svg></div>
    <div class="acg-eb" style="color:#0369a1">SIGNAL</div>
    <h3 class="acg-h"><a class="acg-name" href="#term-waveform" title="Link to this term">Waveform</a></h3>
    <p class="acg-def">In a system neuroscience setting, this often refers to the voltage over time measured with an electrode when an individual neuron produces an action potential.</p>
    </article>
  </div>

  <p class="acg-empty" hidden>Nothing matches that search.</p>

  <p class="acg-foot">
    Generated from the <a href="https://lappalainenj.github.io/allen-glossary/" target="_blank" rel="noopener">Allen Glossary</a>
    (revision 2026-08 · v0.2.0-beta), which is the source of truth for these definitions &#8212;
    corrections and new terms belong there, not on this page.<br>Further reading: <a href="https://www.microns-explorer.org/" target="_blank" rel="noopener">MICrONS Explorer</a> &middot; <a href="https://caveconnectome.github.io/CAVEclient/" target="_blank" rel="noopener">CAVEclient documentation</a> &middot; <a href="https://nwb.org/" target="_blank" rel="noopener">NWB</a> &middot; <a href="https://registry.opendata.aws/allen-nd-open-data/" target="_blank" rel="noopener">AIND open data on S3</a>
  </p>

</div>

<script>
(function(){
  "use strict";
  var root = document.getElementById("acg");
  if (!root) return;

  var cards = Array.prototype.slice.call(root.querySelectorAll(".acg-card"));
  var pills = Array.prototype.slice.call(root.querySelectorAll(".acg-pill"));
  var input = root.querySelector(".acg-q");
  var count = root.querySelector(".acg-count");
  var empty = root.querySelector(".acg-empty");
  var clear = root.querySelector(".acg-clear");
  var total = cards.length;
  var cats  = Object.create(null);

  // cache the original markup once, so highlighting can be re-applied from
  // scratch on every keystroke instead of nesting <mark> inside <mark>
  cards.forEach(function(c){
    c._name = c.querySelector(".acg-name");
    c._def  = c.querySelector(".acg-def");
    c._nameHTML = c._name ? c._name.innerHTML : "";
    c._defHTML  = c._def ? c._def.innerHTML : "";
    c._hay = c.getAttribute("data-hay") || "";
    c._cat = c.getAttribute("data-cat") || "";
  });

  function escapeRx(s){ return s.replace(/[.*+?^${}()|[\]\\]/g, "\\$&"); }

  // highlight matches in markup, touching only the text between tags
  function hl(html, q){
    if (!q) return html;
    var rx = new RegExp("(" + escapeRx(q) + ")", "ig");
    return String(html).split(/(<[^>]+>)/).map(function(part){
      return part.charAt(0) === "<" ? part : part.replace(rx, "<mark>$1</mark>");
    }).join("");
  }

  function activeCats(){
    var on = [];
    for (var k in cats) if (cats[k]) on.push(k);
    return on;
  }

  function apply(){
    var q = (input && input.value ? input.value : "").trim().toLowerCase();
    var on = activeCats();
    var set = on.length ? on : null;
    var shown = 0;
    // counts ignore the category filter itself, so pill numbers do not collapse
    // to zero the moment you narrow to one category
    var per = Object.create(null);

    cards.forEach(function(c){
      var hit = !q || c._hay.indexOf(q) !== -1;
      if (hit) per[c._cat] = (per[c._cat] || 0) + 1;
      var vis = hit && (!set || set.indexOf(c._cat) !== -1);
      c.hidden = !vis;
      if (vis){
        shown++;
        if (c._name) c._name.innerHTML = hl(c._nameHTML, q);
        if (c._def)  c._def.innerHTML  = hl(c._defHTML, q);
      }
    });

    pills.forEach(function(p){
      var n = per[p.getAttribute("data-cat")] || 0;
      var slot = p.querySelector(".acg-n");
      if (slot) slot.textContent = String(n);
      p.classList.toggle("acg-zero", n === 0);
    });

    if (count) count.textContent = (q || set) ? shown + " of " + total + " terms"
                                              : total + " terms";
    if (empty) empty.hidden = shown !== 0;
    if (clear) clear.hidden = !set;
  }

  if (input){
    var t = null;
    input.addEventListener("input", function(){
      clearTimeout(t);
      t = setTimeout(apply, 110);
    });
  }

  pills.forEach(function(p){
    p.addEventListener("click", function(){
      var id = p.getAttribute("data-cat");
      cats[id] = !cats[id];
      p.setAttribute("aria-pressed", cats[id] ? "true" : "false");
      apply();
    });
  });

  if (clear){
    clear.addEventListener("click", function(){
      pills.forEach(function(p){ cats[p.getAttribute("data-cat")] = false;
                                 p.setAttribute("aria-pressed", "false"); });
      apply();
    });
  }

  // "/" focuses the box, Escape empties it — but only while the page has focus,
  // never stealing keys from the databook's own search
  document.addEventListener("keydown", function(e){
    if (!input) return;
    if (e.key === "/" && document.activeElement !== input){
      var tag = (document.activeElement && document.activeElement.tagName) || "";
      if (tag === "INPUT" || tag === "TEXTAREA" || tag === "SELECT") return;
      e.preventDefault();
      input.focus();
    } else if (e.key === "Escape" && document.activeElement === input){
      input.value = "";
      apply();
    }
  });

  // a card linked to directly should survive an active filter
  window.addEventListener("hashchange", function(){
    var h = location.hash.replace(/^#/, "");
    if (h.indexOf("term-") !== 0) return;
    var el = document.getElementById(h);
    if (el && el.hidden){
      pills.forEach(function(p){ cats[p.getAttribute("data-cat")] = false;
                                 p.setAttribute("aria-pressed", "false"); });
      if (input) input.value = "";
      apply();
      el.scrollIntoView({ block: "center" });
    }
  });

  apply();
})();
</script>
:::::

## Term index

The same 139 terms as a plain list, A to Z. This is what the databook's own
search box and any `{term}` cross-reference elsewhere in the book resolve against,
so it is folded away rather than left out.

::::::{dropdown} Every term, A to Z
:::::{glossary}
3D reconstruction
  Turning EM imagery into 3D neuron objects (dense segmentation → meshes). <a href="#term-3d-reconstruction">Go to the card</a>.

Action potential
Spike
  A characteristic signal that appears in excitable cell membranes, which takes the form of an electric potential difference waveform that propagates down the length of the cell membrane. In neurons, these indicate neuron activation. See Spike. <a href="#term-action-potential">Go to the card</a>.

Annotation
  Labeled data (points/tables) bound to locations or cells in the volume. <a href="#term-annotation">Go to the card</a>.

Astrocyte
  A glial cell whose fine processes tile the neuropil and wrap capillaries with endfeet, supporting synapses metabolically and regulating the extracellular environment. Its arbor is a dense thicket rather than a branching tree, which is why it is proofread to a different standard from a neuron. <a href="#term-astrocyte">Go to the card</a>.

Basket cell (BC)
Basket cell
  A type of inhibitory neuron whose synaptic output targets the cell body and proximal dendrites of excitatory neurons. Many basket cells express the molecular marker parvalbumin (PV), but not all basket cells are PV+: some express molecules such as cholecystokinin (CCK). PV basket cells are typically fast spiking compared to other neurons and are thought to be important for gain control of network activity and setting the temporal precision of network activity. <a href="#term-basket-cell">Go to the card</a>.

Bipolar cell (BPC)
Bipolar cell
  A subset of VIP cell with a bipolar dendritic arbor. See VIP cell. <a href="#term-bipolar-cell">Go to the card</a>.

Bound Spatial Point
  Binds an annotation to the cell at a location via the triad pt_position → pt_supervoxel_id → pt_root_id. <a href="#term-bound-spatial-point">Go to the card</a>.

Brain Computer Interface (BCI)
  A method of controlling a computer signal through the activity of a neuron. This can be extended to other types of devices (e.g. joysticks or robotic arms). This is also often referred to as "Brain Machine Interface" <a href="#term-bci">Go to the card</a>.

Branch / End / Root point
  Named skeleton vertex types; the root is conventionally placed at the soma. <a href="#term-branch-end-root-point">Go to the card</a>.

CAVE
  Connectome Annotation Versioning Engine — the suite managing large dynamic connectomics data. <a href="#term-cave">Go to the card</a>.

Cell type
  Classification of a cell (e.g. 23P, BC) via several tables/methods, keyed on nucleus id. <a href="#term-cell-type">Go to the card</a>.

Chandelier cell (ChC)
  A parvalbumin interneuron that synapses exclusively onto the axon initial segments of pyramidal cells, placing it in unique control of whether they fire. Its output forms vertical strings of boutons — the cartridges the cell is named for. <a href="#term-chandelier-cell">Go to the card</a>.

Channelrhodopsin (ChR2)
  A light-gated ion channel used in the field of optogenetics to control neuronal activity with light. <a href="#term-channelrhodopsin">Go to the card</a>.

Column (MICrONS)
Minnie column
  A colloquial name for the 100 micron by 100 micron square column of cortex targeted for the census across layers. This column is a particularly well proofread collection of cells. <a href="#term-column-microns">Go to the card</a>.

Column (V1DD field)
  A column field naming one of 5 stacked scan sub-volumes tiling the V1DD block — a different concept from the MICrONS column. <a href="#term-column-v1dd-field">Go to the card</a>.

Common Coordinate Framework (CCF)
CCF
  The CCF is a a standard 3D reference space for the mouse brain that enables spatial integration of data across modalities. <a href="#term-ccf">Go to the card</a>.

Compartment labels
  SWC integer codes: 0 undefined, 1 soma, 2 axon, 3 basal dendrite, 4 apical dendrite. <a href="#term-compartment-labels">Go to the card</a>.

Connectome
  A wiring map of neurons and the synaptic connections between them. <a href="#term-connectome">Go to the card</a>.

Container
  There is no consistent use of this term Most often this refers to the set of recording sessions for a single ophys imaging plane, but can also refer to the set of sessions for an animal. <a href="#term-container">Go to the card</a>.

Coordinate frames
  Three systems: voxel (annotations), nanometer (mesh/skeleton vertices), transformed (pia-flattened microns). <a href="#term-coordinate-frames">Go to the card</a>.

Coregistration
  Aligning functionally-imaged cells to the same cells in the EM volume (manual + automatic). <a href="#term-coregistration">Go to the card</a>.

Cover paths
  A decomposition of a skeleton into non-overlapping paths, each running from an end point toward the root until it meets a vertex already covered. Every vertex belongs to exactly one, which makes them the right primitive for plotting or walking a neuron. <a href="#term-cover-paths">Go to the card</a>.

Cre line
  The Cre-lox system is a site-specific recombinase technology. Cre-recombinase is a tyrosine site-specific recombinase that catalyzes the recombination of DNA between specific sites known as loxP sequences. As used in these experiments, Cre is used with loxP Reporter line in order to drive recombinase of the loxP sites and drive the expression of the reporter. As Cre is often expressed within a specific gene, this allows the reporter expression to be restricted to particular subset of cells. For specific lines used, see the section on transgenic tools. <a href="#term-cre-line">Go to the card</a>.

Dataset
  There is no consistent use of this term <a href="#term-dataset">Go to the card</a>.

Datastack
  A named bundle of imagery + segmentation + annotation DB (minnie65_public, v1dd_public). <a href="#term-datastack">Go to the card</a>.

Dendritic spine
  The small protrusion on a dendrite that receives most excitatory input, with a bulbous head on a thin neck. Spine density separates excitatory from inhibitory dendrites, and spine heads are among the fragments most often left disconnected by automated segmentation. <a href="#term-dendritic-spine">Go to the card</a>.

Depth / pia→WM axis
  y increases with cortical depth, so depth plots need ax.invert_yaxis(). <a href="#term-depth-pia-wm-axis">Go to the card</a>.

Digital twin
  A DNN trained to predict a cell's response to arbitrary stimuli (source of derived functional properties). <a href="#term-digital-twin">Go to the card</a>.

Driver line
  A general term for transgenic mouse lines that are engineered to label a specific cell type or cell population by expressing a specific gene under the control of the promoter for the cell type or cell population of interest. A Cre line is a common type of Driver line that allows specific genes to be expressed when crossed with a reporter line. The driver line determines what cell population is targeted, and the reporter line determines what will be expressed in that specific cell population (for example, GFP, GCaMP, or Channelrhodopsin). <a href="#term-driver-line">Go to the card</a>.

DSI
  Direction selectivity index (0–1). <a href="#term-dsi">Go to the card</a>.

Edges
  Pairs of connected vertices (mesh.edges, skeleton edges). <a href="#term-edges">Go to the card</a>.

Electron microscopy (EM)
  Imaging that reaches nanometer resolution to reveal tissue ultrastructure. <a href="#term-electron-microscopy-em">Go to the card</a>.

Ephys
  Shorthand for electrophysiology. <a href="#term-ephys">Go to the card</a>.

Excitatory V1 cell types
  Pyramidal subclasses by layer/projection: 23P, 4P, 5P-IT/ET/NP, 6P-IT/CT (+ mtype clusters L2a…L6wm). <a href="#term-excitatory-v1-cell-types">Go to the card</a>.

Experiment
  There is no consistent use of this term It can refer to a stimulus protocol, an entire data collection campaign, or a single session. It is highly ambiguous. <a href="#term-experiment">Go to the card</a>.

Faces
  Triangles of connected vertex indices that tile a mesh surface (mesh.faces). <a href="#term-faces">Go to the card</a>.

Fast spiking neuron (FSN)
  Fast spiking neurons are so called because of their "narrow," fast action potentials, specifically as seen in intracellular recordings of a cell in response to a prolonged step of current. Additionally, with sufficient current injection fast spiking neurons exhibit fast spike rates, and do not show frequency adaptation, or slowing of spike rates, over time. In unlabeled extracellular recordings, units with narrow action potentials are also referred to as fast spiking neurons. This feature is sometimes used to putatively label neurons with narrow spikes as particular cell types, such as PV+ neurons, among others. <a href="#term-fast-spiking-neuron">Go to the card</a>.

FIBSEM
  Focused-ion-beam SEM; block-face EM that mills & images, giving near-isotropic voxels. <a href="#term-fibsem">Go to the card</a>.

Fluorophore
  A type of molecule which absorb light and re-emit it at a longer wavelength in a process called fluorescence. As a result, fluorophores fluoresce only while exposed to a light source. <a href="#term-fluorophore">Go to the card</a>.

Functional connectome
  A dataset linking synapse-resolution EM connectivity to recorded neural function in the same neurons. <a href="#term-functional-connectome">Go to the card</a>.

GABA
  Gamma-aminobutyric acid (GABA) is the main inhibitory neurotransmitter in the mammalian brain. In cortex, most GABAergic neurons are local interneurons. <a href="#term-gaba">Go to the card</a>.

GCaMP
  A family of GECI. GCaMP was generated by a fusion of the calcium binding domain of the calmodulin protein with green fluorescent protein (GFP). In these data we use primarily GCaMP6f as well as some GCaMP6s, fast and slow variants respectively. These two variants differ in their sensitivity as well as their kinetics — primarily with regards to their decay. For more see {cite:t}`chen2013`. <a href="#term-gcamp">Go to the card</a>.

Genetically-encoded calcium indicator (GECI)
GECI
  A protein expressed by a cell that will change its fluorescence upon binding to a Ca{sup}`2+` ion. Used to visualize neural activity with fluorescence microscopy. <a href="#term-geci">Go to the card</a>.

Geodesic distance
  Distance between two points measured along the neuron itself — path length through the skeleton — rather than through the space between them. Two points a micrometre apart in the volume can be hundreds of micrometres apart on the arbor, and the second number is the one a signal has to travel. <a href="#term-geodesic-distance">Go to the card</a>.

GFP
  Green fluorescent protein. Discovered at FHL. <a href="#term-gfp">Go to the card</a>.

gOSI / gDSI
  Global orientation/direction selectivity indices (vector-sum variant). <a href="#term-gosi-gdsi">Go to the card</a>.

Graphene (graphene://)
  URL protocol for dynamic, CAVE-backed (editable) segmentation/meshes, vs static precomputed://. <a href="#term-graphene-graphene">Go to the card</a>.

Graphene vs Precomputed
  graphene:// = dynamic/editable; precomputed:// = static. <a href="#term-graphene-vs-precomputed">Go to the card</a>.

Grids / Chunk
  The volume is partitioned into a 3D grid of chunks for the chunked-graph. <a href="#term-grids-chunk">Go to the card</a>.

Higher visual area (HVA)
HVA
  A **higher visual area** is a term for cortical visual areas that receive input from the primary visual cortex, thus considered to be "higher" in the visual hierarchy. In primates, higher visual areas include V2, V3, V4, V5, MT, etc. In the mouse, higher visual areas include: VISl, VIsal, VISpm, VISam, VISrl among others. For more, see {cite:t}`glickfeld_higher-order_2017`. <a href="#term-higher-visual-area">Go to the card</a>.

Hyperparameter
  A free parameter that controls behaviors in machine learning algorithms. These are distinct from parameters which control behaviors of the models developed by the algorithms; hyperparameters affect how the algorithm finds the models in the first place. <a href="#term-hyperparameter">Go to the card</a>.

Imagery
  The 3D grayscale (0–255) array depicting EM ultrastructure. <a href="#term-imagery">Go to the card</a>.

Inhibitory V1 cell types
  Interneuron subclasses: BC, BPC, MC, NGC (manual) and PTC/DTC/STC/ITC (targeting-based mtypes). <a href="#term-inhibitory-v1-cell-types">Go to the card</a>.

Interneuron
  Also known as a local interneuron: a neuron that has short axons and synapse exclusively with nearby neurons. In the cortex the term is often used to refer to inhibitory neurons. <a href="#term-interneuron">Go to the card</a>.

Intrinsic signal imaging (ISI)
ISI
  Intrinsic signal imaging, also called ISI, is a method to measure changes in blood flow associated with neural activity using reflectance of red light on the brain's surface, measured using a standard CCD camera. The amount of red light reflected by the brain tissue increases when oxygenated hemoglobin perfuses the local region. The timecourse of the ISI signal is slow, and the magnitude of the reflectance changes are small. As a result, the use of periodic stimuli can aid in signal detection. A common use of ISI is to map retinotopy across the brain surface by moving a slowly drifting bar across the visual field then measuring the signal in each pixel at the frequency of the periodic drifting bar. ISI has also been used to identify orientation maps in species with organized orientation maps like cats and primates, as well as to map the location of the whisker barrels in somatosensory cortex of the mouse. For additional papers using ISI to map the organization of the mouse visual cortex see {cite:t}`kalatsky2003` and {cite:t}`garrett2014`. <a href="#term-intrinsic-signal-imaging">Go to the card</a>.

IT / ET / NP / CT / SP
  Projection categories: intratelencephalic, extratelencephalic, near-projecting, corticothalamic, subplate. <a href="#term-it-et-np-ct-sp">Go to the card</a>.

Layer (cortical)
  L1–L6 along the pia→WM axis; drives cell-type naming. NOT the Neuroglancer layer. <a href="#term-layer-cortical">Go to the card</a>.

Level of detail (LOD)
  Static meshes are smaller, multi-LOD, precomputed://; dynamic meshes are detailed, single-LOD, graphene://. <a href="#term-level-of-detail-lod">Go to the card</a>.

Link edges
  Extra mesh edges inserted from the proofreading record to bridge gaps where segmentation was merged across a discontinuity. Without them a mesh may be several disconnected pieces; mesh.add_link_edges() heals it, and mesh.graph_edges is the edges plus the link edges. <a href="#term-link-edges">Go to the card</a>.

Local field potential (LFP)
LFP
Local field potential
  Transient electrical potential generated in nervous tissue by the summed activity of cells in that tissue. This is typically measured in a lower temporal-frequency band of less than 250 Hz. <a href="#term-local-field-potential">Go to the card</a>.

Martinotti cell (MC)
Martinotti cell
  A Martinotti cell is a particular subtype of SST cell that targets the apical dendrites of pyramidal cells in layer 1. Martinotti cells are found in layer 2/3 and layer 5. <a href="#term-martinotti-cell">Go to the card</a>.

Materialization & Versioning
  Timestamped snapshots of the annotation DB; each version = a fixed timestamp (MICrONS v1507, V1DD v1196). <a href="#term-materialization-versioning">Go to the card</a>.

Merge errors
  Two neurons' processes incorrectly joined; they add false connections. <a href="#term-merge-errors">Go to the card</a>.

Meshes
  Vertices + triangular faces defining a neuron's 3D outer surface. <a href="#term-meshes">Go to the card</a>.

Meshpoints
  Informal usage for mesh vertices. Not a formal term — say vertices, since “point” elsewhere means an annotation position. <a href="#term-meshpoints">Go to the card</a>.

Meshwork mask
  A boolean array over mesh vertices restricting a meshwork to part of a cell, applied with apply_mask or mask_context so mesh, skeleton and annotations stay in step. Masking on anno.is_axon is how axonal and dendritic path length are measured separately. <a href="#term-meshwork-mask">Go to the card</a>.

MET-type
  A cell type defined jointly by morphology, electrophysiology and transcriptomics, from patch-seq recordings where all three are measured in the same cell. It is a stricter claim than a type named from any one of them alone. <a href="#term-met-type">Go to the card</a>.

Microglia
  The resident immune cell of the brain. It surveys the neuropil with motile processes and contacts, prunes and engulfs synapses, so it appears in EM wrapped around structures it is in the act of removing. <a href="#term-microglia">Go to the card</a>.

MICrONS
  Cubic-millimeter functional-connectomics EM dataset of mouse visual cortex (VISp/VISal/VISrl). <a href="#term-microns">Go to the card</a>.

Minnie
  A colloquial name for the millimeter-scale MICrONs electron microscopy dataset. <a href="#term-minnie">Go to the card</a>.

mtypes
  Morphology/connectivity-derived cell-type clusters (L2a…L6wm; PTC/DTC/STC/ITC). <a href="#term-mtypes">Go to the card</a>.

Multifeature cell types
  A labelling scheme combining somatic, dendritic and spine features. Excitatory labels are layer plus projection class (L2IT…L6CT); inhibitory labels split more finely than the mtypes (NMC, ChC, PV, AltBasket, AltDTC, ITCperi, L1). <a href="#term-multifeature-cell-types">Go to the card</a>.

Neuroglancer
  WebGL browser viewer for very large volumetric connectomics data (imagery, segmentation, meshes, annotations). <a href="#term-neuroglancer">Go to the card</a>.

Neuroglancer Layer (img/seg/ann)
  The data layers in a Neuroglancer state. NOT the cortical layer. <a href="#term-neuroglancer-layer-img-seg-ann">Go to the card</a>.

Neuroglancer State
  JSON object storing all layers/view/annotations, identified by a state id. <a href="#term-neuroglancer-state">Go to the card</a>.

Neurogliaform cell (NGC)
  A type of interneuron that makes a diffuse axonal arbor and is thought to release GABA through both synaptic release and volume transmission, non-selectively inhibiting neurons nearby. <a href="#term-neurogliaform-cell">Go to the card</a>.

Neuromodulatory axon
  A long-range axon carrying a neuromodulator rather than a fast transmitter. In EM it is recognised by boutons packed with large dense-core vesicles and by branching that ignores laminar boundaries, since it acts over a volume rather than at a single partner. <a href="#term-neuromodulatory-axon">Go to the card</a>.

Neuronal process
  An axon or dendrite branch of a neuron (a process that splits at branch points). <a href="#term-neuronal-process">Go to the card</a>.

Neuropixels
  A family of devices for obtaining high channel count single unit extracellular recordings created through a collaborative open science project funded by Howard Hughes Medical Institute, Gatsby Charitable Trust, the Wellcome Trust, and the Allen Institute. These devices utilize modern integrated circuit design to miniaturize aspects of electrophysiology, enabling recordings of hundred of single units from a single probe with minimal brain damage. {cite:t}`jun2017` describes these probes; a summary can also be found here. <a href="#term-neuropixels">Go to the card</a>.

Nodes
  Vertices in the skeleton / L2 graph. <a href="#term-nodes">Go to the card</a>.

Non-neuronal cell types
  The glial and vascular labels the cell-type tables use: astrocyte, microglia, oligo, OPC and pericyte, carried under a classification_system of aibs_coarse_nonneuronal or nonneuron. <a href="#term-non-neuronal-cell-types">Go to the card</a>.

NWB (Neurodata Without Borders)
  A standardized file format for physiology and behavior data. All of our physiology and behavior data is stored in NWB files. The Visual Coding and Visual Behavior data are in NWB files with a hdf backend, while the newer data (V1DD, BCI, Dynamic Foraging, NP Ultra & Psychedelics) have a Zarr backend - which is optimized for cloud access. More info can be found here <a href="#term-nwb">Go to the card</a>.

Ophys
  Shorthand for optical physiology, often in reference to Two-photon calcium imaging, but can also include other methods such as fiber photometry. <a href="#term-ophys">Go to the card</a>.

Optogenetics
  A method for controlling the activity of neurons by expressing light activated ion channels (using a reporter line ) in a specific subpopulation of cells (using a Driver line) to enable temporally precise control of neural spiking. Spiking can be suppressed or enhanced using different types of reporters. See {cite:t}`peron2011` for a review on optogenetics as a method. <a href="#term-optogenetics">Go to the card</a>.

Optotagging
  A technique that uses optogenetics in order to identify neurons that belong to a specific subpopulation. See: Optotagging. <a href="#term-optotagging">Go to the card</a>.

Oracle score
  Visual-response reliability — signal correlation across repeated “oracle” movies. <a href="#term-oracle-score">Go to the card</a>.

OSI
  Orientation selectivity index (0–1). <a href="#term-osi">Go to the card</a>.

Parvalbumin-positive (PV+) neuron
Parvalbumin-positive interneuron
  Fast spiking neurons, also known as fast spiking interneurons, is a short-hand for parvalbumin positive GABA-ergic inhibitory interneurons found in many brain regions that have strong inhibitory effects on neighboring cells. In experimental preparations where the genetic identity of neurons can be paired with electrophysiological recordings, PV+ neurons have short action potentials, occasionally less than 400 µS. <a href="#term-pv-neuron">Go to the card</a>.

Physiology
  The activity side of a functional-connectomics dataset: the calcium-imaging responses recorded from the same neurons that were later reconstructed in EM. <a href="#term-physiology">Go to the card</a>.

Position
  The 3D coordinate of a bound spatial point (pt_position, stored in voxels by default). <a href="#term-position">Go to the card</a>.

Precomputed format
  Storage representation for arbitrarily large images/meshes/skeletons. <a href="#term-precomputed-format">Go to the card</a>.

Primary visual cortex (V1 / VISp)
  The largest visual area in cortex that receives inputs from the Lateral geniculate nucleus of thalamus. Often referred to as V1 or VISp. <a href="#term-primary-visual-cortex">Go to the card</a>.

Proofreading
  Manual correction of split/merge errors to make neurons biologically accurate/complete. <a href="#term-proofreading">Go to the card</a>.

PyChunkedGraph (PCG) / L2 graph
  Hierarchical representation: L0 = voxels, L1 = supervoxels, L2 = supervoxels grouped within a chunk. <a href="#term-pychunkedgraph-pcg-l2-graph">Go to the card</a>.

Pyramidal cell
  A type of excitatory neuron with a characteristic cell body shape and apical dendrite. In visual cortex, pyramidal cells are by far the most common type of excitatory neuron. <a href="#term-pyramidal-cell">Go to the card</a>.

Radial distance
  Depth measured along the local pia-to-white-matter streamline rather than along a straight line. Cortex curves, so two cells the same Euclidean distance apart can sit in different layers; following the streamline is what makes depth comparable across a volume. standard_transform.radial_distance computes it. <a href="#term-radial-distance">Go to the card</a>.

Radius
  Half the cable thickness at a skeleton vertex (µm). <a href="#term-radius">Go to the card</a>.

Receptive field
  In a sensory context, the receptive field of a neuron is the region of the stimulus domain in which sensory stimulus needs to lie in order to evoke a response. For visual cortical cells, for example, the receptive field is the region of visual space in which stimuli can evoke neural responses. In a computational context, this notion is often generalized multiple dimensions (e.g. space, time, frequency, etc.) and thus equates to the necessary stimulus features that drive neural response (e.g. a localized grating of a specific orientation and frequency). <a href="#term-receptive-field">Go to the card</a>.

Regular spiking neuron (RS)
  Neurons that, when injected with a long step of current in the context of intracellular recordings, show spike frequency adaptation where the rate of spiking decreases over time. These neurons also have longer (or wider) action potentials, and lower spike rates even when injected with large currents due to hyperpolarization after each action potential. These are the most common type of neurons in the mammalian cortex, and are often associated excitatory neurons. In extracellular recordings, neurons with longer action potentials are also sometimes referred to as regular spiking neurons, a feature which is used to associate these units with specific cell types, such as excitatory pyramidal neurons among others. <a href="#term-regular-spiking-neuron">Go to the card</a>.

Reporter
  An exogenous coding region joined to a promoter sequence or element in an expression vector that is introduced into cells to provide the means for measuring the promoter activity source. <a href="#term-reporter">Go to the card</a>.

Reporter line
  A reporter line is a transgenic mouse line that is engineered to express a specific protein that enables monitoring or manipulation of neural activity (such as GFP, GCaMP, or Channelrhodopsin) under the control of cre or FLP recombinase, or a tetracycline transactivator system. The gene engineered into the reporter line will not be expressed unless the protein that controls reporter gene expression (such as cre or FLP) is present, such as by breeding a mouse from the reporter line with a mouse from a specific Driver line that expresses the control protein. Injecting a virus that delivers cre or FLP in a cell type specific manner can also trigger the expression of the reporter gene. <a href="#term-reporter-line">Go to the card</a>.

Residual / Separation score
  The two coregistration-quality metrics. <a href="#term-residual-separation-score">Go to the card</a>.

Resolution
  Physical voxel size in nm/voxel (MICrONS 4×4×40; V1DD 9×9×45); set per query via desired_resolution. <a href="#term-resolution">Go to the card</a>.

Retinotopy
retinotopic map
  retinotopy refers to the mapping of visual space on to neural space. Most visual areas of the brain contain an orderly map of visual space such that neighboring regions in space are represented by neighboring regions in the brain. Retinotopic maps are typically measured in terms of altitude (aka vertical retinotopy), referring to the axis from upper to lower visual field, and and azimuth (aka horizontal retinotopy), referring to the axis from left to right in space. <a href="#term-retinotopy">Go to the card</a>.

ROI mask
ROI
  A region of interest is a general term that describes a subregion of an image. When used in reference to two photon calcium imaging, an ROI is the mask containing pixels thought to belong to a single neuron. <a href="#term-roi-mask">Go to the card</a>.

Root_id (pt_root_id)
  Unique integer for a specific segmentation = a specific version of a cell (a.k.a. segment / object id). <a href="#term-root-id-pt-root-id">Go to the card</a>.

Saccade
  A rapid and ballistic eye movement that shifts the visual field between two fixation points. Mice are not foveal animals, and their eye movements are different from foveal animals (such as humans). <a href="#term-saccade">Go to the card</a>.

Scan
  The scan_idx from functional imaging; part of the ROI's unique id. <a href="#term-scan">Go to the card</a>.

Segmentation
  A 3D array where each voxel stores the root_id of the object at that location. <a href="#term-segmentation">Go to the card</a>.

Segments (= root/object id)
  “Segment id” used as a synonym for root id — collides with the skeleton sense of “segment”. <a href="#term-segments-root-object-id">Go to the card</a>.

Segments (skeleton)
  An unbranched run of vertices between branch/end points. <a href="#term-segments-skeleton">Go to the card</a>.

Serial-section EM
  Many ultrathin sections are cut from a block, imaged one by one, then re-aligned into a volume. Resolution is fine in x/y and coarse in z, so voxels are strongly anisotropic. <a href="#term-serial-section-em">Go to the card</a>.

Session
  A physiological and/or behavioral recording that happens at one time. <a href="#term-session">Go to the card</a>.

Skeletons
  Tree-like linear representation of a neuron's branching (vertices + edges, radius, compartments). <a href="#term-skeletons">Go to the card</a>.

Somatostatin (SST) cell
Somatostatin cell
  A type of inhibitory interneuron expressing the molecular marker somatostatin (SST, or sometimes SOM). SST cells tend to target the distal dendrites of excitatory neurons, and have important roles in regulating the activity of excitatory neurons. <a href="#term-somatostatin-sst-cell">Go to the card</a>.

Source (presynaptic)
  The presynaptic partner of a synapse (pre_pt_root_id). <a href="#term-source-presynaptic">Go to the card</a>.

Spatial frequency
  How often sinusoidal components of as signal or structure repeat per unit of distance. When used in reference to drifting gratings, spatial frequency means the distance between the bars of the grating. Typically measured as cycles per degree. <a href="#term-spatial-frequency">Go to the card</a>.

Spectral shape analysis (HKS)
  Shape descriptors computed from the heat kernel on a mesh, invariant to how the surface is bent. A classifier on these features drives the spine, shaft and soma predictions attached to synapses. <a href="#term-spectral-shape-analysis">Go to the card</a>.

Split errors
  A process incorrectly appears to stop; they remove true connections. <a href="#term-split-errors">Go to the card</a>.

Supervoxel (pt_supervoxel_id)
  L1 grouping of voxels within a chunk; the stable internal id an annotation binds to. <a href="#term-supervoxel-pt-supervoxel-id">Go to the card</a>.

SWC format
  Standard skeleton file format (one of three: SWC, meshwork-h5, precomputed). <a href="#term-swc-format">Go to the card</a>.

Synapse size
  Synapse size in voxels; correlates with surface area / strength. <a href="#term-synapse-size">Go to the card</a>.

Target (postsynaptic)
  The postsynaptic partner of a synapse (post_pt_root_id). <a href="#term-target-postsynaptic">Go to the card</a>.

Targeted structure
  The brain region where data was collected from. <a href="#term-targeted-structure">Go to the card</a>.

TEM
  Transmission EM; MICrONS/V1DD are serial-section TEM-style (thin sections, anisotropic z). <a href="#term-tem">Go to the card</a>.

Temporal frequency
  How many complete periods the signal goes through for a given unit of time. Typically measured in Hertz. <a href="#term-temporal-frequency">Go to the card</a>.

Transgenic line
  A mouse line whose genome has been altered by the introduction of one or more foreign DNA sequences. For these contexts, this typical involves using Cre lines to drive the expression of a Reporter line within a specific subset of cells. <a href="#term-transgenic-line">Go to the card</a>.

Two-photon calcium imaging
  A term for techniques which measure neural activity of neurons by measuring a fluorescent calcium indicator. These indicators are usually a protein expressed in a cell, such as GCaMP, often using a specific combination of Driver line and reporter lines to express GCaMP in a specific subset of neurons. Fluorescent dyes can also be used to perform calcium imaging. At rest a neuron has low levels of calcium, and when the neuron spikes calcium flows into the neuron and raises the level of calcium, which binds to the calcium indicator and increases the emitted fluorescence in a specific wavelength. See {cite:t}`svoboda2006` for a review of two-photon calcium imaging. <a href="#term-two-photon-calcium-imaging">Go to the card</a>.

Ultrastructure
  Fine sub-cellular EM features: organelles, mitochondria, synapses, myelin. <a href="#term-ultrastructure">Go to the card</a>.

Unit
  A putative neuron in extracellular electrophysiology, with varying degrees of confidence assigned to it. In extracellular electrophysiology, neurons are referred to as units, because we cannot guarantee that all the spikes assigned to one unit actually originate from a single cell. Unlike in two-photon imaging, where you can visualize each neuron throughout the entire experiment, with electrophysiology we can only “see” a neuron when it fires a spike. If a neuron moves relative to the probe, or if it’s far away from the probe, some of its spikes may get mixed together with those from other neurons. Because of this inherent ambiguity, quality metrics allow you to find the right units for your analysis. Even highly contaminated units can contain potentially valuable information about brain states, but certain types of analysis require more stringent quality thresholds to ensure that all of the included units are well isolated from their neighbors. <a href="#term-unit">Go to the card</a>.

V1DD (V1 Deep-Dive)
  Functional (2p/3p calcium) + EM dataset of V1 across all layers in 4 mice (~50k neurons/mouse). <a href="#term-v1dd-v1-deep-dive">Go to the card</a>.

Vertex / Vertices
  Points in 3D (N×3, nanometers) that, connected, build meshes and skeletons. <a href="#term-vertex-vertices">Go to the card</a>.

VIP cell
  A type of inhibitory interneuron expressing the molecular marker Vasoactive Intestinal Protein. VIP cells tend to target Somatostatin cells rather than excitatory neurons. This role as a "disinhibitory specialist" is thought to be important for context-dependent modulation of cortical activity. Many VIP cells have a characteristic bipolar axon that points along the axis of the cortical column and are thus often called "bipolar cells". <a href="#term-vip-cell">Go to the card</a>.

VISp / VISal / VISrl
Primary visual cortex
V1
VISp
  The visual cortical areas (V1 / AL / RL / LM) the volume spans and assigns. <a href="#term-visp-visal-visrl">Go to the card</a>.

Volume
  A cubic-mm 3D EM image dataset spanning a cortical region. <a href="#term-volume">Go to the card</a>.

VORTEX
  NIH program (Virtual Observatory of the Cortex) funding continued proofreading; source of the vortex_* tables. <a href="#term-vortex">Go to the card</a>.

Voxel
  The smallest 3D image unit; anisotropic 4×4×40 nm (MICrONS) / 9×9×45 nm (V1DD). <a href="#term-voxel">Go to the card</a>.

Watertight
  EM meshes are NOT watertight, so Trimesh .volume/.center_mass are invalid. <a href="#term-watertight">Go to the card</a>.

Waveform
  In a system neuroscience setting, this often refers to the voltage over time measured with an electrode when an individual neuron produces an action potential. <a href="#term-waveform">Go to the card</a>.
:::::
::::::

:::{note}
This page is generated from [`1aa0c04`](https://github.com/lappalainenj/allen-glossary/commit/1aa0c040189adc824959263bfd31e79e4d6bed84) of the
[Allen Glossary](https://github.com/lappalainenj/allen-glossary) repository.
Do not edit it directly &mdash; edits are overwritten the next time it is regenerated.
To fix a definition or add a term, open a pull request against that repository.
:::
