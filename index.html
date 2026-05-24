# pairspend[kh-wx-pairspend.html](https://github.com/user-attachments/files/28185706/kh-wx-pairspend.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>KH & WX · PairSpend</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
:root {
  --bg: #f7f5f0; --surface: #ffffff; --surface2: #f0ece4; --border: #e5dfd4;
  --kh: #2d5a3d; --wx: #8b3a3a; --kh-light: #e8f2eb; --wx-light: #f5e8e8;
  --income: #2d7a4f; --danger: #c0392b; --text: #1a1a1a; --muted: #8a8070;
  --card-r: 18px; --serif: 'Playfair Display', serif; --sans: 'Outfit', sans-serif;
}
* { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
body { font-family: var(--sans); background: var(--bg); color: var(--text); max-width: 430px; margin: 0 auto; min-height: 100vh; }

#setup-screen { min-height: 100vh; display: flex; flex-direction: column; justify-content: center; padding: 40px 24px; background: var(--surface); }
.setup-logo { font-family: var(--serif); font-size: 30px; color: var(--kh); margin-bottom: 6px; }
.setup-sub { font-size: 13px; color: var(--muted); margin-bottom: 32px; line-height: 1.6; }
.setup-step { margin-bottom: 24px; }
.step-num { width: 26px; height: 26px; border-radius: 50%; background: var(--kh); color: #fff; font-size: 12px; font-weight: 700; display: flex; align-items: center; justify-content: center; margin-bottom: 8px; }
.setup-step h3 { font-size: 14px; font-weight: 700; margin-bottom: 5px; }
.setup-step p { font-size: 12px; color: var(--muted); line-height: 1.6; margin-bottom: 8px; }
.setup-step a { color: var(--kh); font-weight: 600; }
.s-input { width: 100%; padding: 12px 14px; background: var(--surface2); border: 1.5px solid var(--border); border-radius: 11px; font-family: var(--sans); font-size: 13px; color: var(--text); outline: none; transition: border-color .2s; margin-bottom: 8px; word-break: break-all; }
.s-input:focus { border-color: var(--kh); }
.s-input::placeholder { color: var(--muted); }
.s-btn { width: 100%; padding: 15px; background: var(--kh); color: #fff; border: none; border-radius: 13px; font-family: var(--sans); font-size: 15px; font-weight: 700; cursor: pointer; }
.s-note { font-size: 11px; color: var(--muted); margin-top: 14px; line-height: 1.6; text-align: center; }
code { background: var(--surface2); padding: 1px 5px; border-radius: 4px; font-size: 11px; }

#app { display: none; }
.header { background: var(--surface); padding: 50px 16px 0; position: sticky; top: 0; z-index: 100; border-bottom: 1px solid var(--border); box-shadow: 0 2px 10px rgba(0,0,0,.05); }
.header-row { display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px; }
.brand { font-family: var(--serif); font-size: 20px; }
.brand .kh { color: var(--kh); } .brand .wx { color: var(--wx); }
.hdr-right { display: flex; align-items: center; gap: 7px; }
.period-btn { font-size: 11px; font-weight: 700; color: var(--kh); background: var(--kh-light); padding: 5px 10px; border-radius: 20px; cursor: pointer; border: 1px solid rgba(45,90,61,.2); }
.sync-pill { display: flex; align-items: center; gap: 5px; font-size: 11px; font-weight: 600; color: var(--muted); background: var(--surface2); padding: 5px 10px; border-radius: 20px; border: 1px solid var(--border); cursor: pointer; }
.sync-dot { width: 7px; height: 7px; border-radius: 50%; background: #ccc; transition: background .3s; flex-shrink: 0; }
.sync-dot.ok { background: #4caf50; } .sync-dot.busy { background: #ff9800; animation: blink .7s infinite; } .sync-dot.err { background: var(--danger); }
@keyframes blink { 0%,100%{opacity:1}50%{opacity:.3} }
.tabs { display: flex; }
.tab { flex: 1; text-align: center; padding: 11px 2px 9px; font-size: 10px; font-weight: 700; letter-spacing: .06em; text-transform: uppercase; color: var(--muted); cursor: pointer; border-bottom: 2.5px solid transparent; transition: all .2s; }
.tab.active { color: var(--kh); border-bottom-color: var(--kh); }

.page { display: none; padding: 16px 16px 140px; }
.page.active { display: block; animation: fadeUp .2s ease; }
@keyframes fadeUp { from{opacity:0;transform:translateY(5px)} to{opacity:1;transform:none} }

.s-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 14px; }
.s-card { background: var(--surface); border: 1px solid var(--border); border-radius: var(--card-r); padding: 15px; }
.s-card.full { grid-column: span 2; }
.s-lbl { font-size: 10px; font-weight: 700; letter-spacing: .07em; text-transform: uppercase; color: var(--muted); margin-bottom: 5px; }
.s-val { font-family: var(--serif); font-size: 25px; }
.s-val.green { color: var(--income); } .s-val.red { color: var(--danger); }
.s-sub { font-size: 11px; color: var(--muted); margin-top: 3px; }
.user-row { display: flex; gap: 8px; margin-top: 10px; }
.uc { flex: 1; border-radius: 11px; padding: 9px 11px; border-left: 3px solid; }
.uc.kh { background: var(--kh-light); border-color: var(--kh); } .uc.wx { background: var(--wx-light); border-color: var(--wx); }
.uc-name { font-size: 9px; font-weight: 700; letter-spacing: .06em; text-transform: uppercase; }
.kh .uc-name { color: var(--kh); } .wx .uc-name { color: var(--wx); }
.uc-val { font-family: var(--serif); font-size: 18px; margin-top: 2px; }

.cat-bar { display: flex; height: 7px; border-radius: 4px; overflow: hidden; gap: 2px; }
.cat-seg { border-radius: 2px; }
.cat-legend { display: flex; flex-wrap: wrap; gap: 5px 12px; margin-top: 9px; }
.cat-dot { display: flex; align-items: center; gap: 5px; font-size: 11px; color: var(--muted); }
.pip { width: 8px; height: 8px; border-radius: 2px; flex-shrink: 0; }

.sec-title { font-size: 10px; font-weight: 700; letter-spacing: .08em; text-transform: uppercase; color: var(--muted); margin: 16px 0 9px; display: flex; justify-content: space-between; align-items: center; }
.sec-link { color: var(--kh); cursor: pointer; }

.feed { display: flex; flex-direction: column; gap: 7px; }
.tx-card { background: var(--surface); border: 1px solid var(--border); border-radius: 13px; padding: 12px 13px; display: flex; align-items: center; gap: 11px; }
.tx-icon { width: 38px; height: 38px; border-radius: 11px; display: flex; align-items: center; justify-content: center; font-size: 17px; flex-shrink: 0; }
.tx-body { flex: 1; min-width: 0; }
.tx-name { font-size: 14px; font-weight: 500; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
.tx-meta { display: flex; flex-wrap: wrap; gap: 4px; align-items: center; margin-top: 3px; }
.tx-right { text-align: right; flex-shrink: 0; }
.tx-amt { font-family: var(--serif); font-size: 15px; }
.tx-amt.exp { color: var(--text); } .tx-amt.inc { color: var(--income); }
.tx-date { font-size: 10px; color: var(--muted); margin-top: 2px; }
.del-btn { background: none; border: none; color: #ccc; font-size: 15px; cursor: pointer; padding: 4px 5px; border-radius: 5px; flex-shrink: 0; }
.del-btn:active { color: var(--danger); }

.badge { display: inline-flex; align-items: center; font-size: 9px; font-weight: 700; letter-spacing: .04em; padding: 2px 6px; border-radius: 4px; text-transform: uppercase; white-space: nowrap; }
.b-kh { background: var(--kh-light); color: var(--kh); } .b-wx { background: var(--wx-light); color: var(--wx); }
.b-pl { background: #e6f4ea; color: #2d7a4f; } .b-ap { background: #f0f0f0; color: #555; }
.b-ca { background: #fef3e2; color: #b45309; } .b-cd { background: #ede9fe; color: #5b21b6; }
.b-rc { background: #fef9c3; color: #854d0e; }

.chart-card { background: var(--surface); border: 1px solid var(--border); border-radius: var(--card-r); padding: 17px; margin-bottom: 11px; }
.chart-title { font-size: 10px; font-weight: 700; letter-spacing: .07em; text-transform: uppercase; color: var(--muted); margin-bottom: 13px; }
.chart-wrap { position: relative; height: 185px; }

.insight-card { background: linear-gradient(135deg, var(--kh-light), #fff); border: 1px solid rgba(45,90,61,.15); border-radius: var(--card-r); padding: 15px; margin-bottom: 12px; }
.insight-lbl { font-size: 10px; font-weight: 700; letter-spacing: .07em; text-transform: uppercase; color: var(--kh); margin-bottom: 5px; }
.insight-txt { font-size: 13px; color: var(--text); line-height: 1.6; }

.fab { position: fixed; bottom: 26px; left: 50%; transform: translateX(-50%); background: var(--kh); color: #fff; border: none; border-radius: 50px; padding: 15px 28px; font-family: var(--sans); font-size: 14px; font-weight: 700; cursor: pointer; z-index: 200; box-shadow: 0 8px 26px rgba(45,90,61,.35); display: flex; align-items: center; gap: 7px; transition: transform .15s, box-shadow .15s; white-space: nowrap; }
.fab:active { transform: translateX(-50%) scale(.96); }

.overlay { position: fixed; inset: 0; background: rgba(0,0,0,.45); z-index: 300; display: flex; align-items: flex-end; opacity: 0; pointer-events: none; transition: opacity .2s; backdrop-filter: blur(3px); }
.overlay.open { opacity: 1; pointer-events: all; }
.modal { background: var(--surface); border-radius: 24px 24px 0 0; width: 100%; padding: 18px 18px 48px; transform: translateY(100%); transition: transform .3s cubic-bezier(.32,.72,0,1); max-height: 94vh; overflow-y: auto; }
.overlay.open .modal { transform: translateY(0); }
.modal-handle { width: 36px; height: 4px; background: var(--border); border-radius: 2px; margin: 0 auto 16px; }
.modal-title { font-family: var(--serif); font-size: 21px; margin-bottom: 14px; }
.f-lbl { font-size: 10px; font-weight: 700; letter-spacing: .07em; text-transform: uppercase; color: var(--muted); margin-bottom: 6px; display: block; }
.f-row { margin-bottom: 13px; }
.f-inp { width: 100%; padding: 12px 13px; background: var(--surface2); border: 1.5px solid var(--border); border-radius: 11px; font-family: var(--sans); font-size: 15px; color: var(--text); outline: none; transition: border-color .2s; }
.f-inp:focus { border-color: var(--kh); }
.f-inp.big { font-family: var(--serif); font-size: 25px; }
input[type=date].f-inp, input[type=number].f-inp { color-scheme: light; }
.type-bar { display: flex; background: var(--surface2); border-radius: 11px; padding: 4px; margin-bottom: 13px; gap: 3px; }
.type-btn { flex: 1; padding: 9px; text-align: center; border-radius: 8px; font-size: 13px; font-weight: 600; cursor: pointer; transition: all .2s; color: var(--muted); }
.type-btn.exp-active { background: var(--surface); color: var(--text); box-shadow: 0 2px 7px rgba(0,0,0,.08); }
.type-btn.inc-active { background: #e6f4ea; color: var(--income); box-shadow: 0 2px 7px rgba(0,0,0,.08); }
.pills { display: flex; flex-wrap: wrap; gap: 6px; }
.pill { padding: 7px 12px; border-radius: 20px; font-size: 12px; font-weight: 500; background: var(--surface2); border: 1.5px solid var(--border); cursor: pointer; transition: all .15s; color: var(--muted); }
.pill.sel { background: var(--kh); border-color: var(--kh); color: #fff; font-weight: 700; }
.pill.sel-inc { background: var(--income); border-color: var(--income); color: #fff; }
.toggle-row { display: flex; justify-content: space-between; align-items: center; padding: 11px 0; border-top: 1px solid var(--border); }
.toggle-title { font-size: 14px; font-weight: 500; }
.toggle-sub { font-size: 11px; color: var(--muted); margin-top: 1px; }
.sw { width: 44px; height: 26px; background: var(--border); border-radius: 13px; position: relative; cursor: pointer; transition: background .2s; flex-shrink: 0; }
.sw.on { background: var(--kh); }
.sw::after { content:''; position:absolute; width:20px; height:20px; background:#fff; border-radius:50%; top:3px; left:3px; transition:left .2s; }
.sw.on::after { left:21px; }
#rec-day-row { display: none; padding: 12px 0 0; border-top: 1px dashed var(--border); margin-top: 0; }
#rec-day-row.show { display: block; }
.day-hint { font-size: 11px; color: var(--muted); margin-top: 6px; }
.save-btn { width: 100%; padding: 16px; background: var(--kh); color: #fff; border: none; border-radius: 13px; font-family: var(--sans); font-size: 15px; font-weight: 700; cursor: pointer; margin-top: 16px; }
.save-btn:active { opacity: .85; }
.rec-card { background: var(--surface); border: 1px solid var(--border); border-radius: 13px; padding: 13px; margin-bottom: 7px; display: flex; align-items: center; gap: 11px; }
.edit-btn { background: var(--surface2); border: 1px solid var(--border); color: var(--muted); font-size: 11px; cursor: pointer; padding: 4px 9px; border-radius: 6px; flex-shrink: 0; font-weight: 600; }
.edit-btn:active { background: var(--kh-light); color: var(--kh); }
.empty { text-align: center; padding: 44px 20px; color: var(--muted); }
.empty-icon { font-size: 40px; margin-bottom: 9px; }
.loading { text-align: center; padding: 36px; color: var(--muted); font-size: 14px; }
.spinner { width: 26px; height: 26px; border: 3px solid var(--border); border-top-color: var(--kh); border-radius: 50%; animation: spin .8s linear infinite; margin: 0 auto 10px; }
@keyframes spin { to{transform:rotate(360deg)} }
.toast { position: fixed; bottom: 96px; left: 50%; transform: translateX(-50%) translateY(16px); background: #1a1a1a; color: #fff; padding: 9px 18px; border-radius: 20px; font-size: 13px; font-weight: 500; z-index: 500; opacity: 0; transition: all .3s; pointer-events: none; white-space: nowrap; }
.toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }
.reset-link { display: block; text-align: center; margin-top: 20px; font-size: 11px; color: var(--muted); text-decoration: underline; cursor: pointer; }
</style>
</head>
<body>

<!-- SETUP -->
<div id="setup-screen">
  <div class="setup-logo">KH & WX 💚<br>PairSpend</div>
  <div class="setup-sub">Your shared expense tracker — syncs live to Google Sheets via Apps Script. Full read/write, no API key needed.</div>

  <div class="setup-step">
    <div class="step-num">1</div>
    <h3>Open Apps Script in your Sheet</h3>
    <p>1. Open your <a href="https://docs.google.com/spreadsheets/d/159j4srEjvdSFHb_zP-d1QM7ukAC70d9gjGCs0Iw0EyI/edit" target="_blank">PairSpend Sheet</a><br>
    2. Click <strong>Extensions → Apps Script</strong><br>
    3. Delete any sample code shown in the editor</p>
  </div>

  <div class="setup-step">
    <div class="step-num">2</div>
    <h3>Paste the backend script</h3>
    <p>Open <code>apps-script-backend.gs</code> (downloaded with this app) → copy its entire contents → paste into the Apps Script editor → click Save (💾).</p>
  </div>

  <div class="setup-step">
    <div class="step-num">3</div>
    <h3>Deploy as Web App</h3>
    <p>1. Click <strong>Deploy → New deployment</strong><br>
    2. Click the gear ⚙ → choose <strong>Web app</strong><br>
    3. Execute as: <strong>Me</strong><br>
    4. Who has access: <strong>Anyone</strong><br>
    5. Click <strong>Deploy</strong> & authorize (Google warns it's unverified — click Advanced → Go to PairSpend Backend → Allow. This is your own script — safe.)<br>
    6. <strong>Copy the Web App URL</strong> at the end</p>
  </div>

  <div class="setup-step">
    <div class="step-num">4</div>
    <h3>Paste the URL & launch</h3>
    <input class="s-input" id="si-url" type="text" placeholder="https://script.google.com/macros/s/.../exec">
    <button class="s-btn" onclick="saveSetup()">Launch PairSpend →</button>
  </div>

  <div class="s-note">🔒 The URL is stored only on this device. WX uses the same URL on her phone — you both share one backend.</div>
</div>

<!-- APP -->
<div id="app">
  <div class="header">
    <div class="header-row">
      <div class="brand"><span class="kh">KH</span> <span style="color:var(--muted);font-size:15px">&</span> <span class="wx">WX</span></div>
      <div class="hdr-right">
        <div class="period-btn" id="period-btn" onclick="cyclePeriod()">This Month</div>
        <div class="sync-pill" onclick="syncNow()">
          <div class="sync-dot" id="sync-dot"></div>
          <span id="sync-lbl">Sync</span>
        </div>
      </div>
    </div>
    <div class="tabs">
      <div class="tab active" onclick="goPage('overview')">Overview</div>
      <div class="tab" onclick="goPage('feed')">Feed</div>
      <div class="tab" onclick="goPage('trends')">Trends</div>
      <div class="tab" onclick="goPage('recurring')">Recurring</div>
    </div>
  </div>

  <div class="page active" id="page-overview">
    <div id="ov-load" class="loading"><div class="spinner"></div>Loading your data…</div>
    <div id="ov-body" style="display:none">
      <div class="s-grid">
        <div class="s-card full">
          <div class="s-lbl">Total Spent</div>
          <div class="s-val" id="ov-total">S$0</div>
          <div class="user-row">
            <div class="uc kh"><div class="uc-name">KH</div><div class="uc-val" id="ov-kh">S$0</div></div>
            <div class="uc wx"><div class="uc-name">WX</div><div class="uc-val" id="ov-wx">S$0</div></div>
          </div>
        </div>
        <div class="s-card"><div class="s-lbl">Income</div><div class="s-val green" id="ov-income">S$0</div><div class="s-sub" id="ov-saved">Saved: S$0</div></div>
        <div class="s-card"><div class="s-lbl">Top Category</div><div class="s-val" id="ov-top" style="font-size:17px">—</div><div class="s-sub" id="ov-top-amt"></div></div>
      </div>
      <div class="sec-title">By Category</div>
      <div class="cat-bar" id="cat-bar" style="margin-bottom:9px"></div>
      <div class="cat-legend" id="cat-leg" style="margin-bottom:16px"></div>
      <div class="sec-title">Recent <span class="sec-link" onclick="goPage('feed')">See all →</span></div>
      <div class="feed" id="ov-feed"></div>
      <div class="reset-link" onclick="resetSetup()">Reset connection</div>
    </div>
  </div>

  <div class="page" id="page-feed">
    <div style="display:flex;gap:7px;margin-bottom:13px;margin-top:4px">
      <select class="f-inp" id="fil-u" onchange="renderFeed()" style="flex:1;font-size:12px;padding:9px 11px">
        <option value="all">KH + WX</option><option value="KH">KH only</option><option value="WX">WX only</option>
      </select>
      <select class="f-inp" id="fil-t" onchange="renderFeed()" style="flex:1;font-size:12px;padding:9px 11px">
        <option value="all">All types</option><option value="expense">Expenses</option><option value="income">Income</option>
      </select>
    </div>
    <div class="feed" id="main-feed"></div>
  </div>

  <div class="page" id="page-trends">
    <div style="margin-top:4px">
      <div class="insight-card"><div class="insight-lbl">📊 Smart Insight</div><div class="insight-txt" id="ins-txt">Loading…</div></div>
      <div class="chart-card"><div class="chart-title">Monthly Spending (6 months)</div><div class="chart-wrap"><canvas id="trendChart"></canvas></div></div>
      <div class="chart-card"><div class="chart-title">By Category · This Month</div><div class="chart-wrap"><canvas id="catChart"></canvas></div></div>
      <div class="chart-card"><div class="chart-title">By Payment Method · This Month</div><div class="chart-wrap"><canvas id="payChart"></canvas></div></div>
      <div class="chart-card"><div class="chart-title">KH vs WX · 6 Months</div><div class="chart-wrap"><canvas id="userChart"></canvas></div></div>
    </div>
  </div>

  <div class="page" id="page-recurring">
    <div style="margin-top:4px">
      <div class="insight-card"><div class="insight-lbl">🔁 How recurring works</div><div class="insight-txt">Each entry auto-logs on its chosen day every month. Tap <strong>Edit</strong> to change the day or amount, or stop the recurrence.</div></div>
      <div class="sec-title">Your Recurring Entries</div>
      <div id="rec-list"></div>
    </div>
  </div>

  <button class="fab" onclick="openModal()">＋ Add Entry</button>
</div>

<div class="overlay" id="overlay" onclick="closeOut(event)">
  <div class="modal">
    <div class="modal-handle"></div>
    <div class="modal-title" id="modal-title">New Entry</div>
    <div class="type-bar">
      <div class="type-btn exp-active" id="btn-exp" onclick="setType('expense')">💸 Expense</div>
      <div class="type-btn" id="btn-inc" onclick="setType('income')">💰 Income</div>
    </div>
    <div class="f-row"><label class="f-lbl">Amount (SGD)</label><input class="f-inp big" type="number" inputmode="decimal" id="f-amt" placeholder="0.00"></div>
    <div class="f-row"><label class="f-lbl">Description</label><input class="f-inp" type="text" id="f-desc" placeholder="e.g. Netflix"></div>
    <div class="f-row" id="cat-row"><label class="f-lbl">Category</label><div class="pills" id="cat-pills"></div></div>
    <div class="f-row" id="pay-row"><label class="f-lbl">Payment Method</label>
      <div class="pills">
        <div class="pill" data-v="PayLah" onclick="selPill(this,'pay')">🟢 PayLah</div>
        <div class="pill" data-v="Apple Pay" onclick="selPill(this,'pay')"> Apple Pay</div>
        <div class="pill" data-v="Cash" onclick="selPill(this,'pay')">💵 Cash</div>
        <div class="pill" data-v="Card" onclick="selPill(this,'pay')">💳 Card</div>
      </div>
    </div>
    <div class="f-row"><label class="f-lbl">Who</label>
      <div class="pills">
        <div class="pill" data-v="KH" onclick="selPill(this,'who')">KH</div>
        <div class="pill" data-v="WX" onclick="selPill(this,'who')">WX</div>
      </div>
    </div>
    <div class="f-row"><label class="f-lbl">Date</label><input class="f-inp" type="date" id="f-date"></div>
    <div class="toggle-row">
      <div><div class="toggle-title">Recurring Monthly</div><div class="toggle-sub">Auto-log this every month</div></div>
      <div class="sw" id="rec-sw" onclick="toggleRec()"></div>
    </div>
    <div id="rec-day-row">
      <label class="f-lbl">Day of Month (1-31)</label>
      <input class="f-inp" type="number" id="f-recday" min="1" max="31" placeholder="e.g. 10">
      <div class="day-hint">💡 The entry will auto-log on this day of each month. If the day doesn't exist (e.g. 31 in February), it logs on the last day of that month.</div>
    </div>
    <button class="save-btn" id="save-btn" onclick="submitEntry()">Save Entry</button>
  </div>
</div>

<div class="overlay" id="edit-overlay" onclick="closeEditOut(event)">
  <div class="modal" style="padding-bottom:36px">
    <div class="modal-handle"></div>
    <div class="modal-title">Edit Recurring</div>
    <div id="edit-summary" style="background:var(--surface2);border-radius:11px;padding:12px;margin-bottom:14px;font-size:13px"></div>
    <div class="f-row"><label class="f-lbl">Day of Month (1-31)</label>
      <input class="f-inp" type="number" id="edit-day" min="1" max="31">
      <div class="day-hint">💡 Future auto-logs will use this day.</div>
    </div>
    <div class="f-row"><label class="f-lbl">Amount (SGD)</label>
      <input class="f-inp" type="number" inputmode="decimal" id="edit-amt">
    </div>
    <button class="save-btn" onclick="saveEditRec()">Save Changes</button>
    <button class="save-btn" style="background:var(--danger);margin-top:10px" onclick="stopRecurring()">Stop Recurring</button>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
const CATS_EXP = [
  {id:'food',e:'🍜',l:'Food',c:'#e8735a'},{id:'transport',e:'🚌',l:'Transport',c:'#e8c547'},
  {id:'groceries',e:'🛒',l:'Groceries',c:'#4ecb8d'},{id:'utilities',e:'💡',l:'Utilities',c:'#7c6af7'},
  {id:'health',e:'🏥',l:'Health',c:'#f4a261'},{id:'entertainment',e:'🎬',l:'Entertainment',c:'#e76f51'},
  {id:'shopping',e:'🛍️',l:'Shopping',c:'#a8dadc'},{id:'education',e:'📚',l:'Education',c:'#457b9d'},
  {id:'travel',e:'✈️',l:'Travel',c:'#1d3557'},{id:'insurance',e:'🛡️',l:'Insurance',c:'#6d6875'},
  {id:'other',e:'📦',l:'Other',c:'#aaa'},
];
const CATS_INC = [
  {id:'salary',e:'💼',l:'Salary',c:'#4ecb8d'},{id:'freelance',e:'🧑‍💻',l:'Freelance',c:'#7c6af7'},
  {id:'bonus',e:'🎁',l:'Bonus',c:'#e8c547'},{id:'other',e:'📦',l:'Other',c:'#aaa'},
];
const ALL_CATS = [...CATS_EXP, ...CATS_INC.filter(c=>!CATS_EXP.find(x=>x.id===c.id))];
const PERIODS = ['month','3month','year','all'];
const P_LABELS = {month:'This Month','3month':'Last 3 Months',year:'This Year',all:'All Time'};
const PAY_COLORS = {PayLah:'#4ecb8d','Apple Pay':'#aaa',Cash:'#f4a261',Card:'#7c6af7',Other:'#bbb'};
const PAY_BADGE = {PayLah:'b-pl','Apple Pay':'b-ap',Cash:'b-ca',Card:'b-cd'};

let scriptUrl='', transactions=[], period='month', charts={}, editingTxId=null;
let formState={type:'expense',cat:null,pay:null,who:null,rec:false};

function saveSetup(){
  const url=document.getElementById('si-url').value.trim();
  if(!url||!url.startsWith('https://script.google.com/')){alert('Please paste your Apps Script Web App URL (should start with https://script.google.com/)');return;}
  localStorage.setItem('ps_url',url);
  scriptUrl=url; launchApp();
}
function tryAuto(){const u=localStorage.getItem('ps_url');if(u){scriptUrl=u;launchApp();}}
function launchApp(){
  document.getElementById('setup-screen').style.display='none';
  document.getElementById('app').style.display='block';
  syncNow();
}
function resetSetup(){
  if(!confirm('Reset connection? You\'ll need to paste your Apps Script URL again.'))return;
  localStorage.removeItem('ps_url');
  location.reload();
}

// API via Apps Script
async function apiCall(action, data){
  if(!scriptUrl)throw new Error('Not configured');
  let url=scriptUrl+'?action='+action;
  let opts={method:'GET'};
  if(data){
    // Use GET with parameters to avoid CORS preflight on POST
    if(action==='delete'){
      url+='&id='+encodeURIComponent(data.id);
    } else {
      url+='&tx='+encodeURIComponent(JSON.stringify(data));
    }
  }
  const r=await fetch(url,opts);
  if(!r.ok)throw new Error('HTTP '+r.status);
  const j=await r.json();
  if(!j.ok)throw new Error(j.error||'Unknown error');
  return j;
}

async function loadAll(){const j=await apiCall('list');return j.transactions||[];}
async function addRow(tx){await apiCall('add',tx);}
async function updateRow(tx){await apiCall('update',tx);}
async function deleteRow(id){await apiCall('delete',{id});}

// SYNC
function setSS(s){
  const dot=document.getElementById('sync-dot'),lbl=document.getElementById('sync-lbl');
  dot.className='sync-dot '+(s==='ok'?'ok':s==='busy'?'busy':'err');
  lbl.textContent=s==='ok'?'Synced':s==='busy'?'Syncing…':'Error';
}
async function syncNow(){
  if(!scriptUrl)return;setSS('busy');
  try{
    transactions=await loadAll();
    await autoLogRecurring();
    setSS('ok');renderAll();showToast('✓ Synced');
  }catch(e){setSS('err');showToast('⚠ '+e.message);console.error(e);}
}

async function autoLogRecurring(){
  const now=new Date(),today=now.getDate(),m=now.getMonth(),y=now.getFullYear();
  const seen={};const toAdd=[];
  const templates=transactions.filter(t=>t.recurring).filter(t=>{
    const k=t.desc+t.cat+t.user+t.type;if(seen[k])return false;seen[k]=true;return true;
  });
  for(const t of templates){
    const recDay = t.recDay || 1;
    const lastDay = new Date(y, m+1, 0).getDate();
    const logDay = Math.min(recDay, lastDay);
    if (today < logDay) continue;
    const already = transactions.some(x =>
      x.desc===t.desc && x.cat===t.cat && x.user===t.user && x.recurring &&
      (()=>{const d=new Date(x.date+'T00:00:00');return d.getMonth()===m && d.getFullYear()===y && d.getDate()===logDay;})()
    );
    if (!already) {
      toAdd.push({...t, id:uid(), date:`${y}-${String(m+1).padStart(2,'0')}-${String(logDay).padStart(2,'0')}`});
    }
  }
  for(const tx of toAdd){await addRow(tx);transactions.push(tx);}
}

function cyclePeriod(){
  period=PERIODS[(PERIODS.indexOf(period)+1)%PERIODS.length];
  document.getElementById('period-btn').textContent=P_LABELS[period];
  renderAll();
}
function filtered(){
  const now=new Date();
  return transactions.filter(t=>{
    const d=new Date(t.date+'T00:00:00');
    if(period==='month')return d.getMonth()===now.getMonth()&&d.getFullYear()===now.getFullYear();
    if(period==='3month')return d>=new Date(now.getFullYear(),now.getMonth()-2,1);
    if(period==='year')return d.getFullYear()===now.getFullYear();
    return true;
  }).sort((a,b)=>new Date(b.date)-new Date(a.date));
}

function renderAll(){
  renderOverview();renderFeed();renderRecurring();
  if(document.getElementById('page-trends').classList.contains('active'))renderTrends();
}
function renderOverview(){
  document.getElementById('ov-load').style.display='none';
  document.getElementById('ov-body').style.display='block';
  const txs=filtered(),exp=txs.filter(t=>t.type==='expense'),inc=txs.filter(t=>t.type==='income');
  const total=exp.reduce((s,t)=>s+t.amount,0),income=inc.reduce((s,t)=>s+t.amount,0);
  const kh=exp.filter(t=>t.user==='KH').reduce((s,t)=>s+t.amount,0);
  const wx=exp.filter(t=>t.user==='WX').reduce((s,t)=>s+t.amount,0);
  document.getElementById('ov-total').textContent=fmt(total);
  document.getElementById('ov-kh').textContent=fmt(kh);
  document.getElementById('ov-wx').textContent=fmt(wx);
  document.getElementById('ov-income').textContent=fmt(income);
  document.getElementById('ov-saved').textContent='Saved: '+fmt(income-total);
  const catT={};exp.forEach(t=>catT[t.cat]=(catT[t.cat]||0)+t.amount);
  const top=Object.entries(catT).sort((a,b)=>b[1]-a[1])[0];
  if(top){const co=ALL_CATS.find(c=>c.id===top[0]);document.getElementById('ov-top').textContent=(co?co.e+' '+co.l:top[0]);document.getElementById('ov-top-amt').textContent=fmt(top[1]);}
  else{document.getElementById('ov-top').textContent='—';document.getElementById('ov-top-amt').textContent='';}
  const bar=document.getElementById('cat-bar'),leg=document.getElementById('cat-leg');
  bar.innerHTML='';leg.innerHTML='';
  if(total>0)Object.entries(catT).sort((a,b)=>b[1]-a[1]).forEach(([cid,amt])=>{
    const co=ALL_CATS.find(c=>c.id===cid)||{c:'#aaa',l:cid,e:'📦'};
    const seg=document.createElement('div');seg.className='cat-seg';seg.style.cssText=`flex:${amt};background:${co.c}`;bar.appendChild(seg);
    leg.innerHTML+=`<div class="cat-dot"><div class="pip" style="background:${co.c}"></div>${co.e} ${co.l} ${(amt/total*100).toFixed(0)}%</div>`;
  });
  const feed=document.getElementById('ov-feed');feed.innerHTML='';
  if(!txs.length){feed.innerHTML='<div class="empty"><div class="empty-icon">📭</div><p style="font-size:13px">No entries yet. Tap + Add Entry!</p></div>';return;}
  txs.slice(0,5).forEach(t=>feed.appendChild(mkCard(t,false)));
}
function renderFeed(){
  const uf=document.getElementById('fil-u')?.value||'all',tf=document.getElementById('fil-t')?.value||'all';
  let txs=filtered();
  if(uf!=='all')txs=txs.filter(t=>t.user===uf);
  if(tf!=='all')txs=txs.filter(t=>t.type===tf);
  const feed=document.getElementById('main-feed');if(!feed)return;feed.innerHTML='';
  if(!txs.length){feed.innerHTML='<div class="empty"><div class="empty-icon">📭</div><p style="font-size:13px">No entries for this filter.</p></div>';return;}
  txs.forEach(t=>feed.appendChild(mkCard(t,true)));
}
function renderRecurring(){
  const el=document.getElementById('rec-list');if(!el)return;
  const seen={};
  const unique=transactions.filter(t=>t.recurring).filter(t=>{const k=t.desc+t.cat+t.user+t.type;if(seen[k])return false;seen[k]=true;return true;});
  el.innerHTML='';
  if(!unique.length){el.innerHTML='<div class="empty"><div class="empty-icon">🔁</div><p style="font-size:13px">No recurring entries yet. Toggle "Recurring Monthly" when adding an entry.</p></div>';return;}
  unique.forEach(t=>{
    const co=ALL_CATS.find(c=>c.id===t.cat)||{c:'#aaa',e:'📦'};
    const uc=t.user==='KH'?'var(--kh)':'var(--wx)';
    const day=t.recDay||1;
    const ord = day===1?'1st':day===2?'2nd':day===3?'3rd':day===21?'21st':day===22?'22nd':day===23?'23rd':day===31?'31st':day+'th';
    el.innerHTML+=`<div class="rec-card">
      <div class="tx-icon" style="background:${co.c}1a">${co.e}</div>
      <div class="tx-body"><div class="tx-name">${t.desc}</div>
      <div class="tx-meta"><span class="badge b-rc">Monthly · ${ord}</span> <span style="color:${uc};font-size:10px;font-weight:700">${t.user}</span></div></div>
      <div class="tx-right"><div class="tx-amt ${t.type==='income'?'inc':'exp'}">${t.type==='income'?'+':'−'}${fmt(t.amount)}</div></div>
      <button class="edit-btn" onclick="openEditRec('${t.id}')">Edit</button>
    </div>`;
  });
}
function mkCard(t,showDel){
  const co=ALL_CATS.find(c=>c.id===t.cat)||{c:'#aaa',e:'📦',l:'Other'};
  const uc=t.user==='KH'?'var(--kh)':'var(--wx)';
  const pb=PAY_BADGE[t.pay]||'b-cd';
  const div=document.createElement('div');div.className='tx-card';
  div.innerHTML=`<div class="tx-icon" style="background:${co.c}18">${co.e}</div>
    <div class="tx-body"><div class="tx-name">${t.desc}</div>
    <div class="tx-meta">${t.pay?`<span class="badge ${pb}">${t.pay}</span>`:''}${t.recurring?'<span class="badge b-rc">🔁</span>':''}<span style="color:${uc};font-size:10px;font-weight:700">${t.user}</span></div></div>
    <div class="tx-right"><div class="tx-amt ${t.type==='income'?'inc':'exp'}">${t.type==='income'?'+':'−'}${fmt(t.amount)}</div><div class="tx-date">${fmtD(t.date)}</div></div>
    ${showDel?`<button class="del-btn" onclick="delTx('${t.id}')">✕</button>`:''}`;
  return div;
}
async function delTx(id){
  if(!confirm('Delete this entry?'))return;setSS('busy');
  try{await deleteRow(id);transactions=transactions.filter(t=>t.id!==id);setSS('ok');renderAll();showToast('Entry deleted');}
  catch(e){setSS('err');showToast('Delete failed: '+e.message);}
}

function renderTrends(){
  const now=new Date();
  const months=Array.from({length:6},(_,i)=>{const d=new Date(now.getFullYear(),now.getMonth()-5+i,1);return{label:d.toLocaleString('en-SG',{month:'short'}),m:d.getMonth(),y:d.getFullYear()};});
  const exp=transactions.filter(t=>t.type==='expense');
  const mm=mo=>exp.filter(t=>matchM(t,mo));
  const khM=months.map(mo=>mm(mo).filter(t=>t.user==='KH').reduce((s,t)=>s+t.amount,0));
  const wxM=months.map(mo=>mm(mo).filter(t=>t.user==='WX').reduce((s,t)=>s+t.amount,0));
  const totM=months.map((_,i)=>khM[i]+wxM[i]);
  const cur=totM[5],prev=totM[4];
  let ins=cur>0&&prev>0?(cur>prev?`You spent ${fmt(cur)} together this month — ${Math.abs(((cur-prev)/prev*100)).toFixed(0)}% more than last month (${fmt(prev)}). Watch dining & shopping!`:`Great job! ${fmt(cur)} this month — ${Math.abs(((cur-prev)/prev*100)).toFixed(0)}% less than last month (${fmt(prev)}) 🎉`):cur>0?`You've logged ${fmt(cur)} in expenses this month. Keep tracking to unlock comparisons!`:'Add transactions to see smart insights here.';
  document.getElementById('ins-txt').textContent=ins;
  const mk=(id,type,data,opts)=>{if(charts[id])charts[id].destroy();charts[id]=new Chart(document.getElementById(id),{type,...data,...opts});};
  const go={responsive:true,maintainAspectRatio:false};
  mk('trendChart','line',{data:{labels:months.map(m=>m.label),datasets:[{label:'Combined',data:totM,borderColor:'#2d5a3d',backgroundColor:'rgba(45,90,61,.07)',tension:.4,fill:true,pointBackgroundColor:'#2d5a3d',pointRadius:4}]}},{options:{...go,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>'S$'+c.parsed.y.toFixed(2)}}},scales:{x:{grid:{color:'rgba(0,0,0,.04)'},ticks:{color:'#8a8070',font:{size:11}}},y:{grid:{color:'rgba(0,0,0,.04)'},ticks:{color:'#8a8070',callback:v=>'$'+v}}}}});
  const catT={};mm(months[5]).forEach(t=>catT[t.cat]=(catT[t.cat]||0)+t.amount);
  const catE=Object.entries(catT).sort((a,b)=>b[1]-a[1]);
  mk('catChart','doughnut',{data:{labels:catE.map(([k])=>{const co=ALL_CATS.find(c=>c.id===k);return(co?co.e+' '+co.l:k);}),datasets:[{data:catE.map(([,v])=>v),backgroundColor:catE.map(([k])=>ALL_CATS.find(c=>c.id===k)?.c||'#aaa'),borderWidth:0,hoverOffset:5}]}},{options:{...go,plugins:{legend:{position:'bottom',labels:{color:'#8a8070',font:{size:10},padding:8}},tooltip:{callbacks:{label:c=>'S$'+c.parsed.toFixed(2)}}}}});
  const payT={};mm(months[5]).forEach(t=>payT[t.pay||'Other']=(payT[t.pay||'Other']||0)+t.amount);
  const payE=Object.entries(payT).sort((a,b)=>b[1]-a[1]);
  mk('payChart','bar',{data:{labels:payE.map(([k])=>k),datasets:[{data:payE.map(([,v])=>v),backgroundColor:payE.map(([k])=>PAY_COLORS[k]||'#aaa'),borderRadius:7,borderWidth:0}]}},{options:{...go,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>'S$'+c.parsed.y.toFixed(2)}}},scales:{x:{grid:{display:false},ticks:{color:'#8a8070'}},y:{grid:{color:'rgba(0,0,0,.04)'},ticks:{color:'#8a8070',callback:v=>'$'+v}}}}});
  mk('userChart','bar',{data:{labels:months.map(m=>m.label),datasets:[{label:'KH',data:khM,backgroundColor:'rgba(45,90,61,.72)',borderRadius:5,borderWidth:0},{label:'WX',data:wxM,backgroundColor:'rgba(139,58,58,.72)',borderRadius:5,borderWidth:0}]}},{options:{...go,plugins:{legend:{position:'top',labels:{color:'#8a8070',font:{size:11},padding:10}},tooltip:{callbacks:{label:c=>'S$'+c.parsed.y.toFixed(2)}}},scales:{x:{grid:{display:false},ticks:{color:'#8a8070',font:{size:11}}},y:{grid:{color:'rgba(0,0,0,.04)'},ticks:{color:'#8a8070',callback:v=>'$'+v}}},barPercentage:.6}});
}
function matchM(t,mo){const d=new Date(t.date+'T00:00:00');return d.getMonth()===mo.m&&d.getFullYear()===mo.y;}

function openModal(){
  formState={type:'expense',cat:null,pay:null,who:null,rec:false};
  document.getElementById('modal-title').textContent='New Entry';
  document.getElementById('f-amt').value='';document.getElementById('f-desc').value='';
  document.getElementById('f-recday').value='';
  document.getElementById('f-date').value=new Date().toISOString().slice(0,10);
  document.getElementById('rec-sw').classList.remove('on');
  document.getElementById('rec-day-row').classList.remove('show');
  document.querySelectorAll('.pill').forEach(p=>p.classList.remove('sel','sel-inc'));
  setType('expense');document.getElementById('overlay').classList.add('open');
  setTimeout(()=>document.getElementById('f-amt').focus(),350);
}
function closeModal(){document.getElementById('overlay').classList.remove('open');}
function closeOut(e){if(e.target===document.getElementById('overlay'))closeModal();}
function setType(t){
  formState.type=t;
  document.getElementById('btn-exp').className='type-btn'+(t==='expense'?' exp-active':'');
  document.getElementById('btn-inc').className='type-btn'+(t==='income'?' inc-active':'');
  document.getElementById('pay-row').style.display=t==='expense'?'':'none';
  buildPills(t==='expense'?CATS_EXP:CATS_INC);formState.cat=null;
}
function buildPills(cats){
  const el=document.getElementById('cat-pills');el.innerHTML='';
  cats.forEach(c=>{const p=document.createElement('div');p.className='pill';p.dataset.v=c.id;p.textContent=c.e+' '+c.l;p.onclick=()=>selPill(p,'cat');el.appendChild(p);});
}
function selPill(el,group){
  const isInc=formState.type==='income';
  el.closest('.pills').querySelectorAll('.pill').forEach(p=>p.classList.remove('sel','sel-inc'));
  el.classList.add(isInc&&group==='cat'?'sel-inc':'sel');
  if(group==='cat')formState.cat=el.dataset.v;
  if(group==='pay')formState.pay=el.dataset.v;
  if(group==='who')formState.who=el.dataset.v;
}
function toggleRec(){
  formState.rec=!formState.rec;
  document.getElementById('rec-sw').classList.toggle('on',formState.rec);
  document.getElementById('rec-day-row').classList.toggle('show',formState.rec);
  if(formState.rec && !document.getElementById('f-recday').value){
    const date=document.getElementById('f-date').value;
    if(date) document.getElementById('f-recday').value=parseInt(date.slice(8,10));
  }
}
async function submitEntry(){
  const amt=parseFloat(document.getElementById('f-amt').value),desc=document.getElementById('f-desc').value.trim(),date=document.getElementById('f-date').value;
  if(!amt||amt<=0){alert('Enter a valid amount');return;}if(!desc){alert('Add a description');return;}
  if(!formState.cat){alert('Pick a category');return;}if(!formState.who){alert('Select KH or WX');return;}
  if(formState.type==='expense'&&!formState.pay){alert('Select payment method');return;}
  let recDay = null;
  if(formState.rec){
    const v = parseInt(document.getElementById('f-recday').value);
    if(!v||v<1||v>31){alert('Enter a day of month between 1 and 31');return;}
    recDay = v;
  }
  const tx={id:uid(),date,type:formState.type,desc,cat:formState.cat,amount:amt,pay:formState.pay||'',user:formState.who,recurring:formState.rec,recDay};
  const btn=document.getElementById('save-btn');btn.textContent='Saving…';btn.disabled=true;setSS('busy');
  try{await addRow(tx);transactions.push(tx);setSS('ok');closeModal();renderAll();showToast('✓ Saved');}
  catch(e){setSS('err');showToast('Save failed: '+e.message);}
  btn.textContent='Save Entry';btn.disabled=false;
}

function openEditRec(id){
  const t = transactions.find(x=>x.id===id);if(!t)return;
  editingTxId = id;
  document.getElementById('edit-summary').innerHTML = `<strong>${t.desc}</strong><br><span style="color:var(--muted);font-size:12px">${t.user} · ${t.type==='income'?'Income':'Expense'} · ${(ALL_CATS.find(c=>c.id===t.cat)?.l)||t.cat}</span>`;
  document.getElementById('edit-day').value = t.recDay||1;
  document.getElementById('edit-amt').value = t.amount.toFixed(2);
  document.getElementById('edit-overlay').classList.add('open');
}
function closeEditOut(e){if(e.target===document.getElementById('edit-overlay'))closeEditRec();}
function closeEditRec(){document.getElementById('edit-overlay').classList.remove('open');editingTxId=null;}
async function saveEditRec(){
  const t = transactions.find(x=>x.id===editingTxId);if(!t)return;
  const newDay = parseInt(document.getElementById('edit-day').value);
  const newAmt = parseFloat(document.getElementById('edit-amt').value);
  if(!newDay||newDay<1||newDay>31){alert('Day must be 1-31');return;}
  if(!newAmt||newAmt<=0){alert('Invalid amount');return;}
  setSS('busy');
  try{
    const matching = transactions.filter(x => x.recurring && x.desc===t.desc && x.cat===t.cat && x.user===t.user && x.type===t.type);
    for(const m of matching){
      m.recDay = newDay; m.amount = newAmt;
      await updateRow(m);
    }
    setSS('ok');closeEditRec();renderAll();showToast('✓ Recurring updated');
  }catch(e){setSS('err');showToast('Update failed: '+e.message);}
}
async function stopRecurring(){
  if(!confirm('Stop this recurring entry? Past logs stay, but no new ones will be added.'))return;
  const t = transactions.find(x=>x.id===editingTxId);if(!t)return;
  setSS('busy');
  try{
    const matching = transactions.filter(x => x.recurring && x.desc===t.desc && x.cat===t.cat && x.user===t.user && x.type===t.type);
    for(const m of matching){m.recurring=false;await updateRow(m);}
    setSS('ok');closeEditRec();renderAll();showToast('Recurring stopped');
  }catch(e){setSS('err');showToast('Stop failed: '+e.message);}
}

function goPage(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  ['overview','feed','trends','recurring'].forEach((n,i)=>{if(n===id)document.querySelectorAll('.tab')[i]?.classList.add('active');});
  if(id==='trends')renderTrends();if(id==='feed')renderFeed();if(id==='recurring')renderRecurring();
}

function fmt(n){return 'S$'+(n||0).toFixed(2);}
function fmtD(d){return new Date(d+'T00:00:00').toLocaleDateString('en-SG',{day:'numeric',month:'short'});}
function uid(){return Date.now().toString(36)+Math.random().toString(36).slice(2,6);}
function showToast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),2800);}

buildPills(CATS_EXP);
tryAuto();
setInterval(()=>{if(scriptUrl)syncNow();},60000);
</script>
</body>
</html>
