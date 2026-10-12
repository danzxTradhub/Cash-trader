<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trading UI · realistic dashboard</title>
  <!-- Font Awesome for clean icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    /* ---------- GLOBAL RESET & VARIABLES ---------- */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    }

    body {
      background-color: #0b0e14;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 16px;
    }

    /* realistic dashboard container */
    .dashboard {
      max-width: 1400px;
      width: 100%;
      background-color: #0f1219;
      border-radius: 28px;
      box-shadow: 0 30px 50px rgba(0, 0, 0, 0.8), 0 0 0 1px rgba(255, 255, 255, 0.03);
      padding: 24px;
      display: flex;
      flex-direction: column;
      gap: 20px;
      transition: all 0.2s;
    }

    /* ---------- TYPOGRAPHY & COLORS ---------- */
    :root {
      --bg-card: #161b24;
      --bg-card-hover: #1c222e;
      --border-dim: #252b38;
      --text-primary: #e8edf5;
      --text-secondary: #8b95a9;
      --text-muted: #5e687c;
      --green: #0ecb81;
      --green-dim: rgba(14, 203, 129, 0.12);
      --red: #f6465d;
      --red-dim: rgba(246, 70, 93, 0.1);
      --accent: #f0b90b;
      --accent-dim: rgba(240, 185, 11, 0.1);
      --blue: #1e6bff;
      --blue-dim: rgba(30, 107, 255, 0.1);
      --radius-sm: 12px;
      --radius-md: 18px;
      --radius-lg: 24px;
    }

    /* ---------- HEADER (top bar) ---------- */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 4px 8px 4px;
      border-bottom: 1px solid var(--border-dim);
    }

    .logo-area {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo-icon {
      background: linear-gradient(145deg, #f0b90b, #d9a300);
      width: 38px;
      height: 38px;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #0b0e14;
      font-size: 22px;
      font-weight: 700;
      box-shadow: 0 6px 14px rgba(240, 185, 11, 0.25);
    }

    .logo-text {
      font-size: 20px;
      font-weight: 700;
      letter-spacing: -0.5px;
      color: var(--text-primary);
    }

    .logo-text span {
      color: var(--accent);
      font-weight: 800;
    }

    .header-actions {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .header-btn {
      background: var(--bg-card);
      border: 1px solid var(--border-dim);
      color: var(--text-secondary);
      padding: 10px 16px;
      border-radius: 40px;
      font-size: 14px;
      font-weight: 500;
      display: flex;
      align-items: center;
      gap: 8px;
      cursor: default;
      transition: all 0.2s;
      letter-spacing: 0.2px;
    }

    .header-btn i {
      font-size: 14px;
    }

    .header-btn:hover {
      background: var(--bg-card-hover);
      border-color: #333d4d;
      color: var(--text-primary);
    }

    .avatar {
      background: linear-gradient(145deg, #2a3242, #1a212e);
      border-radius: 40px;
      padding: 8px 16px 8px 12px;
      display: flex;
      align-items: center;
      gap: 10px;
      border: 1px solid var(--border-dim);
      color: var(--text-primary);
      font-size: 14px;
      font-weight: 500;
    }

    .avatar i {
      color: var(--accent);
      font-size: 16px;
    }

    /* ---------- MAIN GRID ---------- */
    .main-grid {
      display: grid;
      grid-template-columns: 1fr 360px;
      gap: 20px;
    }

    @media (max-width: 1000px) {
      .main-grid {
        grid-template-columns: 1fr;
      }
    }

    /* ---------- CHART SECTION (left) ---------- */
    .chart-section {
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .pair-selector {
      display: flex;
      align-items: center;
      gap: 20px;
      background: var(--bg-card);
      padding: 10px 18px;
      border-radius: 60px;
      border: 1px solid var(--border-dim);
      width: fit-content;
    }

    .pair {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: 600;
      font-size: 18px;
      color: var(--text-primary);
      letter-spacing: -0.2px;
    }

    .pair i {
      color: var(--accent);
      font-size: 22px;
    }

    .badge {
      background: var(--accent-dim);
      color: var(--accent);
      padding: 4px 12px;
      border-radius: 40px;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: 0.5px;
      border: 1px solid rgba(240, 185, 11, 0.25);
    }

    .price-big {
      display: flex;
      align-items: baseline;
      gap: 16px;
      margin-top: 4px;
    }

    .price-big h2 {
      font-size: 42px;
      font-weight: 700;
      color: var(--text-primary);
      letter-spacing: -1px;
    }

    .change-badge {
      background: var(--green-dim);
      color: var(--green);
      padding: 8px 14px;
      border-radius: 40px;
      font-size: 15px;
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .change-badge i {
      font-size: 14px;
    }

    /* chart placeholder with canvas */
    .chart-container {
      background: var(--bg-card);
      border: 1px solid var(--border-dim);
      border-radius: var(--radius-md);
      padding: 18px 12px 8px 12px;
      position: relative;
      height: 260px;
      width: 100%;
    }

    #chartCanvas {
      width: 100%;
      height: 200px;
      display: block;
    }

    .chart-toolbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 8px 8px 0 8px;
      color: var(--text-secondary);
      font-size: 12px;
    }

    .chart-toolbar i {
      cursor: default;
      transition: color 0.2s;
    }

    .chart-toolbar i:hover {
      color: var(--text-primary);
    }

    .timeframes {
      display: flex;
      gap: 14px;
      background: #10141c;
      padding: 6px 14px;
      border-radius: 40px;
      font-weight: 500;
      border: 1px solid var(--border-dim);
    }

    .timeframes span {
      cursor: default;
      transition: color 0.2s;
    }

    .timeframes span.active {
      color: var(--accent);
      font-weight: 600;
    }

    .timeframes span:hover {
      color: var(--text-primary);
    }

    /* order book small strip */
    .orderbook-strip {
      display: flex;
      gap: 18px;
      justify-content: space-between;
      background: var(--bg-card);
      border: 1px solid var(--border-dim);
      border-radius: var(--radius-sm);
      padding: 14px 18px;
    }

    .bid-ask {
      display: flex;
      gap: 40px;
    }

    .bid-ask-item {
      display: flex;
      flex-direction: column;
      gap: 4px;
    }

    .bid-ask-label {
      font-size: 12px;
      color: var(--text-muted);
      letter-spacing: 0.3px;
      text-transform: uppercase;
      font-weight: 500;
    }

    .bid-ask-value {
      font-weight: 700;
      font-size: 18px;
      color: var(--text-primary);
    }

    .bid-ask-value.green {
      color: var(--green);
    }

    .bid-ask-value.red {
      color: var(--red);
    }

    /* ---------- RIGHT PANEL (order form + trades) ---------- */
    .right-panel {
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .card {
      background: var(--bg-card);
      border: 1px solid var(--border-dim);
      border-radius: var(--radius-md);
      padding: 20px 18px;
      transition: border-color 0.2s;
    }

    .card-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }

    .card-header h4 {
      font-size: 16px;
      font-weight: 600;
      color: var(--text-primary);
      letter-spacing: -0.2px;
    }

    .card-header i {
      color: var(--text-muted);
      cursor: default;
    }

    /* order tabs */
    .order-tabs {
      display: flex;
      gap: 24px;
      margin-bottom: 18px;
      border-bottom: 1px solid var(--border-dim);
      padding-bottom: 10px;
    }

    .order-tab {
      font-size: 14px;
      font-weight: 600;
      color: var(--text-secondary);
      cursor: default;
      padding-bottom: 10px;
      margin-bottom: -11px;
      transition: all 0.2s;
    }

    .order-tab.active {
      color: var(--accent);
      border-bottom: 2px solid var(--accent);
    }

    .order-tab:hover {
      color: var(--text-primary);
    }

    /* order form */
    .form-group {
      margin-bottom: 18px;
    }

    .form-label {
      display: flex;
      justify-content: space-between;
      font-size: 13px;
      color: var(--text-secondary);
      margin-bottom: 6px;
      font-weight: 500;
    }

    .form-label span:last-child {
      color: var(--text-muted);
    }

    .input-wrapper {
      display: flex;
      align-items: center;
      background: #0d1119;
      border: 1px solid #232a36;
      border-radius: 14px;
      padding: 0 16px;
      transition: border-color 0.2s;
    }

    .input-wrapper:focus-within {
      border-color: var(--accent);
    }

    .input-wrapper input {
      background: transparent;
      border: none;
      padding: 14px 0;
      width: 100%;
      color: var(--text-primary);
      font-size: 16px;
      font-weight: 500;
      outline: none;
    }

    .input-wrapper input::placeholder {
      color: var(--text-muted);
      font-weight: 400;
    }

    .input-suffix {
      color: var(--text-secondary);
      font-size: 14px;
      font-weight: 600;
    }

    .percentage-buttons {
      display: flex;
      gap: 8px;
      margin: 8px 0 12px 0;
    }

    .percentage-buttons button {
      background: #1c222e;
      border: 1px solid #262e3c;
      color: var(--text-secondary);
      padding: 8px 0;
      border-radius: 30px;
      font-size: 12px;
      font-weight: 600;
      flex: 1;
      cursor: default;
      transition: all 0.15s;
    }

    .percentage-buttons button:hover {
      background: #2a3242;
      color: var(--text-primary);
    }

    .action-buttons {
      display: flex;
      gap: 12px;
      margin-top: 12px;
    }

    .btn-buy {
      background: var(--green);
      border: none;
      padding: 16px 0;
      border-radius: 40px;
      font-weight: 700;
      font-size: 16px;
      color: #0b0e14;
      flex: 1;
      cursor: default;
      transition: all 0.15s;
      box-shadow: 0 8px 16px rgba(14, 203, 129, 0.2);
      letter-spacing: 0.3px;
    }

    .btn-buy:hover {
      background: #0fdc8c;
      box-shadow: 0 8px 20px rgba(14, 203, 129, 0.35);
    }

    .btn-sell {
      background: var(--red);
      border: none;
      padding: 16px 0;
      border-radius: 40px;
      font-weight: 700;
      font-size: 16px;
      color: #0b0e14;
      flex: 1;
      cursor: default;
      transition: all 0.15s;
      box-shadow: 0 8px 16px rgba(246, 70, 93, 0.2);
      letter-spacing: 0.3px;
    }

    .btn-sell:hover {
      background: #ff5c70;
      box-shadow: 0 8px 20px rgba(246, 70, 93, 0.35);
    }

    /* recent trades list */
    .trades-list {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 4px;
    }

    .trade-row {
      display: flex;
      justify-content: space-between;
      font-size: 14px;
      padding: 8px 0;
      border-bottom: 1px solid #1e232e;
    }

    .trade-row:last-child {
      border-bottom: none;
    }

    .trade-price {
      font-weight: 600;
    }

    .trade-price.green {
      color: var(--green);
    }

    .trade-price.red {
      color: var(--red);
    }

    .trade-amount {
      color: var(--text-secondary);
    }

    .trade-time {
      color: var(--text-muted);
      font-size: 12px;
    }

    /* balance card */
    .balance-card {
      background: linear-gradient(145deg, #161e2a, #121824);
    }

    .balance-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .balance-label {
      color: var(--text-secondary);
      font-size: 14px;
    }

    .balance-value {
      font-size: 28px;
      font-weight: 700;
      color: var(--text-primary);
      letter-spacing: -0.5px;
    }

    .balance-sub {
      color: var(--text-muted);
      font-size: 13px;
      margin-top: 6px;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    /* ---------- FOOTER / BOTTOM BAR (extra realism) ---------- */
    .footer-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-top: 12px;
      border-top: 1px solid var(--border-dim);
      color: var(--text-muted);
      font-size: 13px;
    }

    .footer-left {
      display: flex;
      gap: 28px;
    }

    .footer-left span i {
      margin-right: 6px;
      font-size: 13px;
      color: var(--text-secondary);
    }

    .footer-right {
      display: flex;
      gap: 18px;
    }

    .status-dot {
      display: inline-block;
      width: 8px;
      height: 8px;
      background: var(--green);
      border-radius: 50%;
      margin-right: 6px;
      box-shadow: 0 0 10px var(--green);
    }

    /* misc */
    .fa-chevron-down {
      font-size: 12px;
      color: var(--text-secondary);
    }

    .text-glow {
      text-shadow: 0 0 10px rgba(14, 203, 129, 0.3);
    }

    /* custom scroll */
    ::-webkit-scrollbar {
      width: 4px;
    }

    ::-webkit-scrollbar-track {
      background: #0b0e14;
    }

    ::-webkit-scrollbar-thumb {
      background: #2a3242;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div class="dashboard">
    <!-- TOP BAR -->
    <div class="header">
      <div class="logo-area">
        <div class="logo-icon">T</div>
        <div class="logo-text">Trade<span>Flow</span></div>
      </div>
      <div class="header-actions">
        <div class="header-btn"><i class="fas fa-search"></i> Markets</div>
        <div class="header-btn"><i class="fas fa-bell"></i> Alerts</div>
        <div class="avatar"><i class="fas fa-user-circle"></i> Alex Trader <i class="fas fa-chevron-down"></i></div>
      </div>
    </div>

    <!-- MAIN GRID -->
    <div class="main-grid">
      <!-- LEFT: chart & market info -->
      <div class="chart-section">
        <div class="pair-selector">
          <div class="pair">
            <i class="fab fa-bitcoin"></i> BTC / USDT
            <i class="fas fa-chevron-down" style="font-size: 12px; margin-left: 6px; color: #8b95a9;"></i>
          </div>
          <div class="badge">Perpetual</div>
        </div>

        <div class="price-big">
          <h2>63,428.50</h2>
          <div class="change-badge"><i class="fas fa-caret-up"></i> +2.34%</div>
          <div style="color: var(--text-secondary); font-size: 14px; margin-left: auto;">24h Vol: 1.2B</div>
        </div>

        <!-- Chart container with canvas -->
        <div class="chart-container">
          <canvas id="chartCanvas" width="800" height="200"></canvas>
          <div class="chart-toolbar">
            <div><i class="far fa-clock"></i> 15m · Real-time</div>
            <div class="timeframes">
              <span>1m</span>
              <span>5m</span>
              <span class="active">15m</span>
              <span>1h</span>
              <span>4h</span>
              <span>1d</span>
            </div>
          </div>
        </div>

        <!-- Order book mini strip -->
        <div class="orderbook-strip">
          <div class="bid-ask">
            <div class="bid-ask-item">
              <div class="bid-ask-label">Bid</div>
              <div class="bid-ask-value green">63,425.20</div>
            </div>
            <div class="bid-ask-item">
              <div class="bid-ask-label">Ask</div>
              <div class="bid-ask-value red">63,430.80</div>
            </div>
            <div class="bid-ask-item">
              <div class="bid-ask-label">Spread</div>
              <div class="bid-ask-value" style="font-size: 16px;">5.60</div>
            </div>
          </div>
          <div style="color: var(--text-secondary); font-size: 13px; display: flex; align-items: center;">
            <i class="fas fa-chart-line" style="margin-right: 6px; color: var(--accent);"></i> Depth 0.2
          </div>
        </div>
      </div>

      <!-- RIGHT PANEL: order form + trades -->
      <div class="right-panel">
        <!-- ORDER FORM CARD -->
        <div class="card">
          <div class="card-header">
            <h4>Spot Order</h4>
            <i class="fas fa-sliders-h"></i>
          </div>
          <div class="order-tabs">
            <div class="order-tab active">Buy</div>
            <div class="order-tab">Sell</div>
            <div class="order-tab">Limit</div>
          </div>

          <div class="form-group">
            <div class="form-label"><span>Price</span><span>USDT</span></div>
            <div class="input-wrapper">
              <input type="text" value="63,428.50" readonly>
              <span class="input-suffix">USDT</span>
            </div>
          </div>

          <div class="form-group">
            <div class="form-label"><span>Amount</span><span>BTC</span></div>
            <div class="input-wrapper">
              <input type="text" placeholder="0.0000" value="0.0250">
              <span class="input-suffix">BTC</span>
            </div>
          </div>

          <div class="percentage-buttons">
            <button>25%</button>
            <button>50%</button>
            <button>75%</button>
            <button>100%</button>
          </div>

          <div class="action-buttons">
            <button class="btn-buy">Buy BTC</button>
            <button class="btn-sell">Sell BTC</button>
          </div>
        </div>

        <!-- RECENT TRADES CARD -->
        <div class="card">
          <div class="card-header">
            <h4>Recent Trades</h4>
            <i class="fas fa-history"></i>
          </div>
          <div class="trades-list">
            <div class="trade-row">
              <span class="trade-price green">63,428.50</span>
              <span class="trade-amount">0.0124 BTC</span>
              <span class="trade-time">12:42:18</span>
            </div>
            <div class="trade-row">
              <span class="trade-price red">63,425.20</span>
              <span class="trade-amount">0.0087 BTC</span>
              <span class="trade-time">12:41:55</span>
            </div>
            <div class="trade-row">
              <span class="trade-price green">63,430.80</span>
              <span class="trade-amount">0.0231 BTC</span>
              <span class="trade-time">12:41:22</span>
            </div>
            <div class="trade-row">
              <span class="trade-price green">63,427.10</span>
              <span class="trade-amount">0.0056 BTC</span>
              <span class="trade-time">12:40:47</span>
            </div>
            <div class="trade-row">
              <span class="trade-price red">63,422.30</span>
              <span class="trade-amount">0.0192 BTC</span>
              <span class="trade-time">12:40:10</span>
            </div>
          </div>
        </div>

        <!-- BALANCE CARD (small) -->
        <div class="card balance-card">
          <div class="balance-row">
            <span class="balance-label">Available Balance</span>
            <i class="fas fa-wallet" style="color: var(--accent);"></i>
          </div>
          <div class="balance-value">$12,845.32</div>
          <div class="balance-sub">
            <i class="fas fa-arrow-up" style="color: var(--green);"></i> +$342.10 (2.7%) today
          </div>
        </div>
      </div>
    </div>

    <!-- FOOTER -->
    <div class="footer-bar">
      <div class="footer-left">
        <sp
