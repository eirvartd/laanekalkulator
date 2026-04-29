<!DOCTYPE html>
<html lang="no">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lånekalkulator – Sparebanken Norge</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600&display=swap" rel="stylesheet">
<style>
:root {
  --navy: #0d1f3c;
  --navy-mid: #1a3458;
  --blue: #1e5799;
  --blue-light: #2e7bd6;
  --accent: #e8b84b;
  --accent-pale: #fdf4dc;
  --surface: #f4f7fb;
  --surface-2: #eef2f8;
  --border: #dae3ef;
  --text: #0d1f3c;
  --text-mid: #4a5d78;
  --text-light: #7a8fa8;
  --ok: #1a7a4a; --ok-bg: #e6f7ee;
  --warn: #8a5f00; --warn-bg: #fff8e1;
  --bad: #b82020; --bad-bg: #fdeaea;
  --radius: 12px;
  --radius-sm: 7px;
  --shadow: 0 1px 8px rgba(13,31,60,0.07);
  --shadow-md: 0 4px 24px rgba(13,31,60,0.12);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
body{font-family:'DM Sans',sans-serif;font-size:14px;background:var(--surface);color:var(--text);min-height:100vh}

/* ── HEADER ── */
.site-header{background:var(--navy);padding:0 40px;display:flex;align-items:stretch;position:sticky;top:0;z-index:100;box-shadow:0 2px 20px rgba(0,0,0,0.3)}
.header-brand{display:flex;align-items:center;gap:14px;padding:16px 28px 16px 0;border-right:1px solid rgba(255,255,255,0.1);margin-right:24px;flex-shrink:0}
.header-logo{width:38px;height:38px;background:var(--accent);border-radius:9px;display:flex;align-items:center;justify-content:center;font-family:'DM Serif Display',serif;font-size:20px;color:var(--navy);font-style:italic;flex-shrink:0}
.header-title{font-family:'DM Serif Display',serif;font-size:16px;color:#fff;line-height:1.15}
.header-subtitle{font-size:11px;color:rgba(255,255,255,0.4);margin-top:2px;font-weight:300;letter-spacing:0.05em}
.nav-tabs{display:flex;align-items:stretch;gap:0;overflow-x:auto}
.nav-tab{padding:0 20px;border:none;background:transparent;cursor:pointer;font-family:'DM Sans',sans-serif;font-size:13px;font-weight:500;color:rgba(255,255,255,0.5);position:relative;transition:color 0.2s;white-space:nowrap;letter-spacing:0.01em}
.nav-tab::after{content:'';position:absolute;bottom:0;left:20px;right:20px;height:3px;background:var(--accent);border-radius:3px 3px 0 0;opacity:0;transition:opacity 0.2s}
.nav-tab:hover{color:rgba(255,255,255,0.8)}
.nav-tab.active{color:#fff}
.nav-tab.active::after{opacity:1}

/* ── MAIN ── */
.main{max-width:1220px;margin:0 auto;padding:32px 40px 64px}
.panel{display:none;animation:fadeUp 0.22s ease}
.panel.active{display:block}
@keyframes fadeUp{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}

.section-heading{margin-bottom:24px}
.section-heading h2{font-family:'DM Serif Display',serif;font-size:24px;color:var(--navy);font-weight:400;margin-bottom:3px}
.section-heading p{font-size:13px;color:var(--text-light)}

/* ── GRIDS ── */
.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.grid-3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:20px}
.grid-ir{display:grid;grid-template-columns:360px 1fr;gap:24px}

/* ── CARDS ── */
.card{background:#fff;border:1px solid var(--border);border-radius:var(--radius);box-shadow:var(--shadow);overflow:hidden}
.card+.card{margin-top:16px}
.card-header{background:var(--navy-mid);padding:10px 18px;display:flex;align-items:center;gap:9px}
.card-icon{width:22px;height:22px;background:var(--accent);border-radius:5px;display:flex;align-items:center;justify-content:center;font-size:12px;flex-shrink:0}
.card-title{font-size:11px;font-weight:600;color:rgba(255,255,255,0.88);text-transform:uppercase;letter-spacing:0.08em}
.card-body{padding:18px}

/* ── FIELDS ── */
.field{margin-bottom:12px}
.field:last-child{margin-bottom:0}
.field label{display:block;font-size:12px;font-weight:500;color:var(--text-mid);margin-bottom:5px}
.field input,.field select{width:100%;padding:9px 12px;border:1.5px solid var(--border);border-radius:var(--radius-sm);font-family:'DM Sans',sans-serif;font-size:14px;font-weight:500;color:var(--navy);background:#fff;transition:border-color 0.15s,box-shadow 0.15s;-moz-appearance:textfield}
.field input::-webkit-outer-spin-button,.field input::-webkit-inner-spin-button{-webkit-appearance:none}
.field input:focus,.field select:focus{outline:none;border-color:var(--blue-light);box-shadow:0 0 0 3px rgba(46,123,214,0.12)}
.field-row{display:grid;grid-template-columns:1fr 1fr;gap:10px}

/* ── METRICS ── */
.metric-group{display:flex;flex-direction:column;gap:8px}
.metric{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-sm);padding:12px 14px}
.metric.dark{background:var(--navy);border-color:var(--navy)}
.metric.dark .metric-label{color:rgba(255,255,255,0.5)}
.metric.dark .metric-value{color:#fff}
.metric-label{font-size:11px;color:var(--text-light);margin-bottom:3px;font-weight:500;letter-spacing:0.02em}
.metric-value{font-family:'DM Serif Display',serif;font-size:23px;color:var(--navy);letter-spacing:-0.01em}
.metric-value.ok{color:var(--ok)}
.metric-value.warn{color:var(--warn)}
.metric-value.bad{color:var(--bad)}
.metric-sub{font-size:11px;margin-top:2px;font-weight:500}
.metric-sub.ok{color:var(--ok)}.metric-sub.warn{color:var(--warn)}.metric-sub.bad{color:var(--bad)}

/* ── BADGE ── */
.badge{display:inline-flex;align-items:center;gap:5px;padding:5px 12px;border-radius:20px;font-size:12px;font-weight:600;margin-top:6px}
.badge.ok{background:var(--ok-bg);color:var(--ok)}
.badge.warn{background:var(--warn-bg);color:var(--warn)}
.badge.bad{background:var(--bad-bg);color:var(--bad)}

/* ── TABLE ── */
.rtable{width:100%;border-collapse:collapse}
.rtable tr{border-bottom:1px solid var(--border)}
.rtable tr:last-child{border-bottom:none}
.rtable td{padding:9px 2px;font-size:13px;color:var(--text-mid)}
.rtable td:last-child{text-align:right;font-weight:600;color:var(--navy)}
.rtable .total td{font-weight:700;font-size:14px;color:var(--navy);padding-top:12px}
.rtable .total td:first-child{color:var(--text-mid)}

.divider{border:none;border-top:1px solid var(--border);margin:14px 0}
.note{font-size:12px;color:var(--text-mid);background:var(--surface);border-left:3px solid var(--blue-light);border-radius:0 var(--radius-sm) var(--radius-sm) 0;padding:10px 12px;margin-top:14px;line-height:1.6}

/* ── SUMMARY BAR ── */
.summary-bar{background:var(--navy);border-radius:var(--radius);padding:22px 32px;display:grid;grid-template-columns:1fr 1px 1fr 1px 1fr;gap:0;margin-top:20px;box-shadow:var(--shadow-md)}
.summary-sep{background:rgba(255,255,255,0.1)}
.summary-item{padding:0 28px}
.summary-item:first-child{padding-left:0}
.summary-item:last-child{padding-right:0}
.s-label{font-size:11px;color:rgba(255,255,255,0.45);text-transform:uppercase;letter-spacing:0.08em;margin-bottom:6px;font-weight:500}
.s-value{font-family:'DM Serif Display',serif;font-size:26px;color:#fff}
.s-value.gold{color:var(--accent)}

/* ── BIG RESULT ── */
.big-result{background:linear-gradient(135deg,var(--navy) 0%,var(--navy-mid) 100%);border-radius:var(--radius);padding:30px;text-align:center;margin-bottom:16px;box-shadow:var(--shadow-md)}
.br-label{font-size:11px;color:rgba(255,255,255,0.45);text-transform:uppercase;letter-spacing:0.1em;margin-bottom:8px}
.br-value{font-family:'DM Serif Display',serif;font-size:46px;color:var(--accent);letter-spacing:-0.02em;line-height:1}

@media(max-width:960px){
  .site-header{padding:0 16px}
  .main{padding:20px 16px 48px}
  .grid-2,.grid-3,.grid-ir{grid-template-columns:1fr}
  .summary-bar{grid-template-columns:1fr;gap:16px}
  .summary-sep{display:none}
  .summary-item{padding:0}
}
</style>
</head>
<body>

<header class="site-header">
  <div class="header-brand">
    <div class="header-logo">S</div>
    <div>
      <div class="header-title">Lånekalkulator</div>
      <div class="header-subtitle">Sparebanken Norge &mdash; internt verktøy</div>
    </div>
  </div>
  <nav class="nav-tabs">
    <button class="nav-tab active" onclick="showTab('mf',this)">Mellomfinansiering</button>
    <button class="nav-tab" onclick="showTab('blg',this)">Belåningsgrad</button>
    <button class="nav-tab" onclick="showTab('rk',this)">Realkausjon</button>
    <button class="nav-tab" onclick="showTab('lb',this)">Låneberegning</button>
    <button class="nav-tab" onclick="showTab('bolig',this)">Maks kjøpesum</button>
  </nav>
</header>

<main class="main">

<!-- ═══════════════════════════════════════════════
     MELLOMFINANSIERING
═══════════════════════════════════════════════ -->
<div id="tab-mf" class="panel active">
  <div class="section-heading">
    <h2>Mellomfinansiering</h2>
    <p>Beregn MF-lån, belåningsgrad og periodekostnad ved kjøp før salg</p>
  </div>
  <div class="grid-ir">
    <div>
      <div class="card">
        <div class="card-header"><div class="card-icon">🏠</div><span class="card-title">Ny bolig</span></div>
        <div class="card-body">
          <div class="field"><label>Kjøpesum (kr)</label><input type="number" id="mf_kjøp" value="4500000" oninput="calcMF()"></div>
          <div class="field-row">
            <div class="field"><label>EK – oppspart (kr)</label><input type="number" id="mf_ek_opp" value="0" oninput="calcMF()"></div>
            <div class="field"><label>EK – annen (kr)</label><input type="number" id="mf_ek_ann" value="0" oninput="calcMF()"></div>
          </div>
          <div class="field-row">
            <div class="field"><label>Rente nytt lån (%)</label><input type="number" id="mf_r_ny" value="4.8" step="0.1" oninput="calcMF()"></div>
            <div class="field"><label>Løpetid (år)</label><input type="number" id="mf_lop_ny" value="30" oninput="calcMF()"></div>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">🏡</div><span class="card-title">Gammel bolig</span></div>
        <div class="card-body">
          <div class="field"><label>Forventet salgssum (kr)</label><input type="number" id="mf_salg" value="4440000" oninput="calcMF()"></div>
          <div class="field-row">
            <div class="field"><label>Salgsomkostninger (kr)</label><input type="number" id="mf_salg_omk" value="130000" oninput="calcMF()"></div>
            <div class="field"><label>Boliglån innfris (kr)</label><input type="number" id="mf_gl_lån" value="3500000" oninput="calcMF()"></div>
          </div>
          <div class="field-row">
            <div class="field"><label>Buffer/margin (kr)</label><input type="number" id="mf_buf" value="0" oninput="calcMF()"></div>
            <div class="field"><label>Rente gl. lån (%)</label><input type="number" id="mf_r_gl" value="5.5" step="0.1" oninput="calcMF()"></div>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">⏱</div><span class="card-title">Mellomfinansiering</span></div>
        <div class="card-body">
          <div class="field-row">
            <div class="field"><label>Rente MF-lån (%)</label><input type="number" id="mf_r_mf" value="7.5" step="0.1" oninput="calcMF()"></div>
            <div class="field"><label>MF-periode (måneder)</label><input type="number" id="mf_mnd" value="6" min="1" max="24" oninput="calcMF()"></div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="card">
        <div class="card-header"><div class="card-icon">📊</div><span class="card-title">Finansieringsbehov</span></div>
        <div class="card-body">
          <div class="metric-group">
            <div class="metric"><div class="metric-label">Kjøpsomkostninger (2,5%)</div><div class="metric-value" id="mf_omk">–</div></div>
            <div class="metric"><div class="metric-label">Egenkapital fra salg</div><div class="metric-value" id="mf_ek_salg">–</div></div>
            <div class="metric"><div class="metric-label">Total egenkapital</div><div class="metric-value" id="mf_ek_tot">–</div></div>
            <div class="metric dark"><div class="metric-label">Nytt lån (langsiktig)</div><div class="metric-value" id="mf_nylån">–</div></div>
            <div class="metric"><div class="metric-label">MF-lån</div><div class="metric-value" id="mf_mflån">–</div></div>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">📐</div><span class="card-title">Belåningsgrad</span></div>
        <div class="card-body">
          <div class="metric">
            <div class="metric-label">Belåningsgrad (nytt lån / kjøpesum)</div>
            <div class="metric-value" id="mf_blg">–</div>
            <div class="metric-sub" id="mf_blg_sub"></div>
          </div>
          <div id="mf_blg_badge"></div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">💳</div><span class="card-title">Månedlige kostnader</span></div>
        <div class="card-body">
          <table class="rtable">
            <tr><td>Terminbeløp nytt lån</td><td id="mf_t_ny">–</td></tr>
            <tr><td>Terminbeløp gammelt lån</td><td id="mf_t_gl">–</td></tr>
            <tr><td>MF-rentekostnad per mnd</td><td id="mf_t_mf">–</td></tr>
            <tr class="total"><td>Sum per mnd (MF-perioden)</td><td id="mf_sum_mnd">–</td></tr>
          </table>
          <hr class="divider">
          <div class="metric dark">
            <div class="metric-label">Samlet rentekostnad MF-perioden</div>
            <div class="metric-value" id="mf_tot_kost">–</div>
          </div>
          <div class="note" id="mf_note"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════
     BELÅNINGSGRAD
═══════════════════════════════════════════════ -->
<div id="tab-blg" class="panel">
  <div class="section-heading">
    <h2>Belåningsgrad</h2>
    <p>Beregn belåningsgrad og makslån for selveier- og andel-/aksjebolig</p>
  </div>
  <div class="grid-2">
    <div class="card">
      <div class="card-header"><div class="card-icon">🏠</div><span class="card-title">Selveierbolig</span></div>
      <div class="card-body">
        <div class="field"><label>Markedsverdi (kr)</label><input type="number" id="blg_sv_v" value="3000000" oninput="calcBLG()"></div>
        <div class="field"><label>Boliglån (kr)</label><input type="number" id="blg_sv_l" value="2700000" oninput="calcBLG()"></div>
        <hr class="divider">
        <div class="metric"><div class="metric-label">Belåningsgrad</div><div class="metric-value" id="blg_sv_res">–</div></div>
        <div id="blg_sv_badge"></div>
        <hr class="divider">
        <table class="rtable">
          <tr><td>Maks lån (90%)</td><td id="blg_sv_90">–</td></tr>
          <tr><td>Maks lån avdr.utsettelse (60%)</td><td id="blg_sv_60">–</td></tr>
        </table>
      </div>
    </div>
    <div class="card">
      <div class="card-header"><div class="card-icon">🏢</div><span class="card-title">Andel-/aksjebolig</span></div>
      <div class="card-body">
        <div class="field"><label>Markedsverdi (kr)</label><input type="number" id="blg_ab_v" value="1700000" oninput="calcBLG()"></div>
        <div class="field-row">
          <div class="field"><label>Fellesgjeld (kr)</label><input type="number" id="blg_ab_fg" value="1150000" oninput="calcBLG()"></div>
          <div class="field"><label>Boliglån (kr)</label><input type="number" id="blg_ab_l" value="1600000" oninput="calcBLG()"></div>
        </div>
        <hr class="divider">
        <div class="metric"><div class="metric-label">Belåningsgrad (inkl. fellesgjeld)</div><div class="metric-value" id="blg_ab_res">–</div></div>
        <div id="blg_ab_badge"></div>
        <hr class="divider">
        <table class="rtable">
          <tr><td>Maks lån (85% av verdi – fg)</td><td id="blg_ab_85">–</td></tr>
          <tr><td>Maks lån avdr.utsettelse (60%)</td><td id="blg_ab_60">–</td></tr>
        </table>
        <div class="note">Belåningsgrad beregnes mot markedsverdi + fellesgjeld. Maks 85% av verdi fratrukket fellesgjeld.</div>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════
     REALKAUSJON
═══════════════════════════════════════════════ -->
<div id="tab-rk" class="panel">
  <div class="section-heading">
    <h2>Realkausjon</h2>
    <p>Beregn påkrevd og oppgitt kausjonsbeløp</p>
  </div>
  <div class="grid-ir">
    <div>
      <div class="card">
        <div class="card-header"><div class="card-icon">🔒</div><span class="card-title">Kausjonsobjekt</span></div>
        <div class="card-body">
          <div class="field"><label>Type objekt</label>
            <select id="rk_type" onchange="calcRK()">
              <option value="selveier">Selveierbolig</option>
              <option value="andel">Andel-/aksjebolig</option>
            </select>
          </div>
          <div class="field"><label>Markedsverdi (kr)</label><input type="number" id="rk_verdi" value="1700000" oninput="calcRK()"></div>
          <div class="field" id="rk_fg_felt"><label>Fellesgjeld (kr)</label><input type="number" id="rk_fg" value="1150000" oninput="calcRK()"></div>
          <div class="field"><label>Maks belåning (%)</label><input type="number" id="rk_mb" value="85" step="1" oninput="calcRK()"></div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">🏠</div><span class="card-title">Ny bolig</span></div>
        <div class="card-body">
          <div class="field"><label>Kjøpesum (kr)</label><input type="number" id="rk_kjøp" value="4500000" oninput="calcRK()"></div>
          <div class="field-row">
            <div class="field"><label>Kontant EK (kr)</label><input type="number" id="rk_ek_k" value="100000" oninput="calcRK()"></div>
            <div class="field"><label>Bunden EK (kr)</label><input type="number" id="rk_ek_b" value="0" oninput="calcRK()"></div>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">✍️</div><span class="card-title">Oppgitt kausjonsbeløp</span></div>
        <div class="card-body">
          <div class="field"><label>Realkausjonsbeløp (kr)</label><input type="number" id="rk_bel" value="200000" oninput="calcRK()"></div>
          <div class="note">Realkausjon gir 90% av beløpet som egenkapitalverdi mot ny bolig.</div>
        </div>
      </div>
    </div>
    <div>
      <div class="card">
        <div class="card-header"><div class="card-icon">🧮</div><span class="card-title">Beregnet realkausjon</span></div>
        <div class="card-body">
          <div class="metric-group">
            <div class="metric"><div class="metric-label">Frigjort sikkerhet i kausjonsobjekt</div><div class="metric-value" id="rk_frigjort">–</div></div>
            <div class="metric"><div class="metric-label">EK-krav (15% av kjøpesum)</div><div class="metric-value" id="rk_ek_krav">–</div></div>
            <div class="metric"><div class="metric-label">Manglende egenkapital</div><div class="metric-value" id="rk_mangel">–</div></div>
            <div class="metric dark"><div class="metric-label">Påkrevd realkausjonsbeløp</div><div class="metric-value" id="rk_påkrevd">–</div></div>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">✅</div><span class="card-title">Ved oppgitt kausjonsbeløp</span></div>
        <div class="card-body">
          <div class="metric-group">
            <div class="metric"><div class="metric-label">Tilsvarer egenkapital</div><div class="metric-value" id="rk_ek_verdi">–</div></div>
            <div class="metric"><div class="metric-label">Gir sikkerhet for lån</div><div class="metric-value" id="rk_sikkerhet">–</div></div>
          </div>
          <div id="rk_status" style="margin-top:10px"></div>
          <div class="note">Forutsetter at kjøpsomkostninger dekkes av kontant EK eller annen kilde.</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════
     LÅNEBEREGNING
═══════════════════════════════════════════════ -->
<div id="tab-lb" class="panel">
  <div class="section-heading">
    <h2>Låneberegning</h2>
    <p>Sammenlign terminbeløp og totalkostnad for alle tre lån</p>
  </div>
  <div class="grid-3">
    <div class="card">
      <div class="card-header"><div class="card-icon">🟢</div><span class="card-title">Nytt lån</span></div>
      <div class="card-body">
        <div class="field"><label>Lånebeløp (kr)</label><input type="number" id="lb_ny_b" value="3000000" oninput="calcLB()"></div>
        <div class="field-row">
          <div class="field"><label>Rente (%)</label><input type="number" id="lb_ny_r" value="4.8" step="0.1" oninput="calcLB()"></div>
          <div class="field"><label>Løpetid (år)</label><input type="number" id="lb_ny_å" value="30" oninput="calcLB()"></div>
        </div>
        <hr class="divider">
        <div class="metric dark"><div class="metric-label">Terminbeløp per mnd</div><div class="metric-value" id="lb_ny_term">–</div></div>
        <div class="metric" style="margin-top:8px"><div class="metric-label">Total rentekostnad</div><div class="metric-value" id="lb_ny_tot">–</div></div>
      </div>
    </div>
    <div class="card">
      <div class="card-header"><div class="card-icon">🟡</div><span class="card-title">Gammelt lån</span></div>
      <div class="card-body">
        <div class="field"><label>Lånebeløp (kr)</label><input type="number" id="lb_gl_b" value="3000000" oninput="calcLB()"></div>
        <div class="field-row">
          <div class="field"><label>Rente (%)</label><input type="number" id="lb_gl_r" value="5.5" step="0.1" oninput="calcLB()"></div>
          <div class="field"><label>Løpetid (år)</label><input type="number" id="lb_gl_å" value="30" oninput="calcLB()"></div>
        </div>
        <hr class="divider">
        <div class="metric dark"><div class="metric-label">Terminbeløp per mnd</div><div class="metric-value" id="lb_gl_term">–</div></div>
        <div class="metric" style="margin-top:8px"><div class="metric-label">Total rentekostnad</div><div class="metric-value" id="lb_gl_tot">–</div></div>
      </div>
    </div>
    <div class="card">
      <div class="card-header"><div class="card-icon">🟠</div><span class="card-title">Mellomfinansiering</span></div>
      <div class="card-body">
        <div class="field"><label>Lånebeløp (kr)</label><input type="number" id="lb_mf_b" value="500000" oninput="calcLB()"></div>
        <div class="field-row">
          <div class="field"><label>Rente (%)</label><input type="number" id="lb_mf_r" value="7.5" step="0.1" oninput="calcLB()"></div>
          <div class="field"><label>Periode (mnd)</label><input type="number" id="lb_mf_m" value="6" oninput="calcLB()"></div>
        </div>
        <hr class="divider">
        <div class="metric dark"><div class="metric-label">Rentekostnad per mnd</div><div class="metric-value" id="lb_mf_term">–</div></div>
        <div class="metric" style="margin-top:8px"><div class="metric-label">Total MF-kostnad</div><div class="metric-value" id="lb_mf_tot">–</div></div>
      </div>
    </div>
  </div>
  <div class="summary-bar">
    <div class="summary-item"><div class="s-label">Under MF-perioden</div><div class="s-value" id="lb_sum_mf">–</div></div>
    <div class="summary-sep"></div>
    <div class="summary-item"><div class="s-label">Etter salg av gammel bolig</div><div class="s-value" id="lb_sum_etter">–</div></div>
    <div class="summary-sep"></div>
    <div class="summary-item"><div class="s-label">Besparelse per mnd etter salg</div><div class="s-value gold" id="lb_diff">–</div></div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════
     MAKS KJØPESUM
═══════════════════════════════════════════════ -->
<div id="tab-bolig" class="panel">
  <div class="section-heading">
    <h2>Maks kjøpesum</h2>
    <p>Beregn maksimal kjøpesum basert på tilgjengelig egenkapital</p>
  </div>
  <div class="grid-ir">
    <div class="card">
      <div class="card-header"><div class="card-icon">🎯</div><span class="card-title">Forutsetninger</span></div>
      <div class="card-body">
        <div class="field"><label>Tilgjengelig egenkapital (kr)</label><input type="number" id="b_ek" value="500000" oninput="calcBolig()"></div>
        <div class="field-row">
          <div class="field"><label>Ønsket belåningsgrad (%)</label><input type="number" id="b_blg" value="85" min="1" max="100" step="1" oninput="calcBolig()"></div>
          <div class="field"><label>Kjøpsomkostninger (%)</label><input type="number" id="b_omk" value="2.5" step="0.1" oninput="calcBolig()"></div>
        </div>
        <div class="note">Brukt bolig: normalt 2,5% (dokumentavgift + gebyrer).<br>Ny bolig: normalt ca. 1,0%.</div>
      </div>
    </div>
    <div>
      <div class="big-result">
        <div class="br-label">Maks kjøpesum</div>
        <div class="br-value" id="b_kjøp">–</div>
      </div>
      <div class="card">
        <div class="card-header"><div class="card-icon">📊</div><span class="card-title">Fordeling</span></div>
        <div class="card-body">
          <div class="metric-group">
            <div class="metric"><div class="metric-label">Boliglån</div><div class="metric-value" id="b_lån">–</div></div>
            <div class="metric"><div class="metric-label">Kjøpsomkostninger</div><div class="metric-value" id="b_omk_kr">–</div></div>
            <div class="metric"><div class="metric-label">EK benyttet totalt</div><div class="metric-value" id="b_ek_bruk">–</div></div>
            <div class="metric"><div class="metric-label">Faktisk belåningsgrad</div><div class="metric-value" id="b_faktisk">–</div></div>
          </div>
          <div class="note">Formel: Kjøpesum = EK ÷ (1 &minus; BLG% + omk%)<br>Eks: 500 000 ÷ (0,15 + 0,025) = 2 857 143 kr</div>
        </div>
      </div>
    </div>
  </div>
</div>

</main>

<script>
function v(id){return parseFloat(document.getElementById(id).value)||0}
function set(id,val){var e=document.getElementById(id);if(e)e.textContent=val}
function setCls(id,cls){var e=document.getElementById(id);if(e){e.className='metric-value';if(cls)e.classList.add(cls)}}
function fmt(n){return Math.round(n).toLocaleString('nb-NO')+' kr'}
function fmtP(n){return (n*100).toFixed(1)+'%'}
function pmt(r,n,pv){if(r===0)return pv/n;return pv*(r*Math.pow(1+r,n))/(Math.pow(1+r,n)-1)}
function blgCls(b){return b>0.9?'bad':b>0.85?'warn':'ok'}
function blgBadge(b,max){
  max=max||0.9;
  if(b<=0)return '';
  if(b>max)return '<span class="badge bad">⚠ Over maks '+fmtP(max)+'</span>';
  if(b>0.85)return '<span class="badge warn">⚠ Over 85% – avdragsutsettelse ikke mulig</span>';
  return '<span class="badge ok">✓ Innenfor grense</span>';
}

function showTab(name,btn){
  document.querySelectorAll('.panel').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-tab').forEach(t=>t.classList.remove('active'));
  document.getElementById('tab-'+name).classList.add('active');
  btn.classList.add('active');
}

function calcMF(){
  var kjøp=v('mf_kjøp'),ekopp=v('mf_ek_opp'),ekann=v('mf_ek_ann');
  var salg=v('mf_salg'),somk=v('mf_salg_omk'),gllån=v('mf_gl_lån'),buf=v('mf_buf');
  var rny=v('mf_r_ny')/100,lop=v('mf_lop_ny'),rgl=v('mf_r_gl')/100;
  var rmf=v('mf_r_mf')/100,mnd=v('mf_mnd');
  var omk=kjøp*0.025;
  var eksalg=Math.max(0,salg-somk-gllån-buf);
  var ektot=eksalg+ekopp+ekann;
  var nylån=Math.max(0,kjøp+omk-ektot);
  var mflån=eksalg;
  var blg=kjøp>0?nylån/kjøp:0;
  var tny=pmt(rny/12,lop*12,nylån);
  var tgl=pmt(rgl/12,30*12,gllån);
  var tmf=mflån*rmf/12;
  set('mf_omk',fmt(omk)); set('mf_ek_salg',fmt(eksalg)); set('mf_ek_tot',fmt(ektot));
  set('mf_nylån',fmt(nylån)); set('mf_mflån',fmt(mflån));
  setCls('mf_blg',blgCls(blg)); set('mf_blg',fmtP(blg));
  var sub=document.getElementById('mf_blg_sub');
  sub.className='metric-sub '+blgCls(blg);
  sub.textContent=blg>0.9?'Over maks – tilleggssikkerhet påkrevd':blg>0.85?'Over 85% – ingen avdragsutsettelse':'Innenfor grense';
  document.getElementById('mf_blg_badge').innerHTML=blgBadge(blg);
  set('mf_t_ny',fmt(tny)+' /mnd'); set('mf_t_gl',fmt(tgl)+' /mnd');
  set('mf_t_mf',fmt(tmf)+' /mnd'); set('mf_sum_mnd',fmt(tny+tgl+tmf)+' /mnd');
  set('mf_tot_kost',fmt(tmf*mnd));
  document.getElementById('mf_note').textContent='MF-lån på '+fmt(mflån)+' dekkes ved salg av gammel bolig. Rentekostnad over '+mnd+' mnd: '+fmt(tmf*mnd)+'.';
}

function calcBLG(){
  var svv=v('blg_sv_v'),svl=v('blg_sv_l');
  var abv=v('blg_ab_v'),abfg=v('blg_ab_fg'),abl=v('blg_ab_l');
  var svblg=svv>0?svl/svv:0;
  var abblg=(abv+abfg)>0?(abl+abfg)/(abv+abfg):0;
  setCls('blg_sv_res',blgCls(svblg)); set('blg_sv_res',fmtP(svblg));
  document.getElementById('blg_sv_badge').innerHTML=blgBadge(svblg);
  set('blg_sv_90',fmt(svv*0.9)); set('blg_sv_60',fmt(svv*0.6));
  var abcls=abblg>0.85?'bad':abblg>0.80?'warn':'ok';
  setCls('blg_ab_res',abcls); set('blg_ab_res',fmtP(abblg));
  document.getElementById('blg_ab_badge').innerHTML=blgBadge(abblg,0.85);
  set('blg_ab_85',fmt(Math.max(0,abv*0.85-abfg)));
  set('blg_ab_60',fmt(Math.max(0,abv*0.6-abfg)));
}

function calcRK(){
  var type=document.getElementById('rk_type').value;
  document.getElementById('rk_fg_felt').style.display=type==='andel'?'block':'none';
  var verdi=v('rk_verdi'),fg=type==='andel'?v('rk_fg'):0,mb=v('rk_mb')/100;
  var kjøp=v('rk_kjøp'),ekk=v('rk_ek_k'),ekb=v('rk_ek_b'),bel=v('rk_bel');
  var frigjort=Math.max(0,verdi*mb-fg);
  var ekkrav=kjøp*0.15,mangel=Math.max(0,ekkrav-ekk-ekb);
  var påkrevd=mangel>0?mangel/0.9:0;
  var ekverdi=bel*0.9,sikkerhet=ekverdi>0?ekverdi/0.15:0;
  set('rk_frigjort',fmt(frigjort)); set('rk_ek_krav',fmt(ekkrav));
  set('rk_mangel',fmt(mangel)); set('rk_påkrevd',fmt(påkrevd));
  set('rk_ek_verdi',fmt(ekverdi)); set('rk_sikkerhet',fmt(sikkerhet));
  var ok=bel>=påkrevd&&påkrevd>0;
  document.getElementById('rk_status').innerHTML=påkrevd>0
    ?(ok?'<span class="badge ok">✓ Tilstrekkelig kausjon</span>'
        :'<span class="badge bad">⚠ Mangler '+fmt(Math.max(0,påkrevd-bel))+'</span>'):'';
}

function calcLB(){
  var nyb=v('lb_ny_b'),nyr=v('lb_ny_r')/100,nyå=v('lb_ny_å');
  var glb=v('lb_gl_b'),glr=v('lb_gl_r')/100,glå=v('lb_gl_å');
  var mfb=v('lb_mf_b'),mfr=v('lb_mf_r')/100,mfm=v('lb_mf_m');
  var tny=pmt(nyr/12,nyå*12,nyb);
  var tgl=pmt(glr/12,glå*12,glb);
  var tmf=mfb*mfr/12;
  set('lb_ny_term',fmt(tny)+' /mnd'); set('lb_ny_tot',fmt(tny*nyå*12-nyb));
  set('lb_gl_term',fmt(tgl)+' /mnd'); set('lb_gl_tot',fmt(tgl*glå*12-glb));
  set('lb_mf_term',fmt(tmf)+' /mnd'); set('lb_mf_tot',fmt(tmf*mfm));
  set('lb_sum_mf',fmt(tny+tgl+tmf)+' /mnd');
  set('lb_sum_etter',fmt(tny)+' /mnd');
  set('lb_diff',fmt(tgl+tmf)+' /mnd');
}

function calcBolig(){
  var ek=v('b_ek'),blg=v('b_blg')/100,omk=v('b_omk')/100;
  var kjøp=ek/(1-blg+omk);
  var lån=kjøp*blg,omkKr=kjøp*omk,ekbruk=kjøp-lån+omkKr;
  set('b_kjøp',fmt(kjøp)); set('b_lån',fmt(lån));
  set('b_omk_kr',fmt(omkKr)); set('b_ek_bruk',fmt(ekbruk));
  set('b_faktisk',fmtP(kjøp>0?lån/kjøp:0));
}

calcMF();calcBLG();calcRK();calcLB();calcBolig();
</script>
</body>
</html>
