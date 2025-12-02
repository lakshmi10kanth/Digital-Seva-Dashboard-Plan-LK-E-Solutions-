<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>LK E-Solutions - Digital Seva CEUD System</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
      :root {
        --bg: #050816;
        --bg-soft: #0b1020;
        --primary: #4f46e5;
        --primary-soft: rgba(79, 70, 229, 0.15);
        --accent: #22c55e;
        --text: #f9fafb;
        --muted: #9ca3af;
        --border: #1f2937;
        --danger: #ef4444;
      }

      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
          sans-serif;
      }

      html {
        scroll-behavior: smooth;
      }

      body {
        background: radial-gradient(circle at top, #111827 0, #020617 60%);
        color: var(--text);
        min-height: 100vh;
        display: flex;
        flex-direction: column;
      }

      .app {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
      }

      /* Top bar */
      .topbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 14px 24px;
        background: rgba(15, 23, 42, 0.95);
        border-bottom: 1px solid var(--border);
        backdrop-filter: blur(16px);
        position: sticky;
        top: 0;
        z-index: 20;
      }

      .brand {
        display: flex;
        align-items: center;
        gap: 10px;
      }

      .brand-logo {
        width: 32px;
        height: 32px;
        border-radius: 999px;
        background: conic-gradient(
          from 180deg,
          #4f46e5,
          #22c55e,
          #06b6d4,
          #f97316,
          #4f46e5
        );
        position: relative;
        overflow: hidden;
      }

      .brand-logo::after {
        content: "";
        position: absolute;
        inset: 3px;
        background: radial-gradient(circle at 30% 20%, #1f2937, #020617);
        border-radius: inherit;
      }

      .brand-text-main {
        font-size: 1.1rem;
        font-weight: 700;
        letter-spacing: 0.03em;
      }

      .brand-text-sub {
        font-size: 0.7rem;
        color: var(--muted);
        text-transform: uppercase;
        letter-spacing: 0.14em;
      }

      .menu {
        display: flex;
        align-items: center;
        gap: 6px;
        background: rgba(15, 23, 42, 0.9);
        border-radius: 999px;
        padding: 3px;
        border: 1px solid rgba(55, 65, 81, 0.8);
      }

      .menu button {
        border: none;
        background: transparent;
        color: var(--muted);
        padding: 6px 14px;
        border-radius: 999px;
        font-size: 0.8rem;
        letter-spacing: 0.08em;
        text-transform: uppercase;
        cursor: pointer;
        transition: all 0.15s ease-out;
        display: flex;
        align-items: center;
        gap: 6px;
      }

      .menu button span.icon {
        font-size: 0.9rem;
      }

      .menu button.active {
        background: linear-gradient(135deg, #4f46e5, #22c55e);
        color: #f9fafb;
        box-shadow: 0 0 0 1px rgba(15, 23, 42, 0.8),
          0 10px 25px rgba(15, 23, 42, 0.9);
      }

      .menu button:hover:not(.active) {
        background: rgba(31, 41, 55, 0.9);
        color: #e5e7eb;
      }

      .right-actions {
        display: flex;
        align-items: center;
        gap: 8px;
      }

      .pill {
        border-radius: 999px;
        padding: 6px 12px;
        border: 1px solid rgba(55, 65, 81, 0.9);
        font-size: 0.75rem;
        color: var(--muted);
        display: flex;
        align-items: center;
        gap: 6px;
      }

      .pill-dot {
        width: 7px;
        height: 7px;
        border-radius: 999px;
        background: #22c55e;
        box-shadow: 0 0 0 5px rgba(34, 197, 94, 0.25);
      }

      .pill-cta {
        border-radius: 999px;
        padding: 6px 14px;
        border: none;
        color: #0b1120;
        background: linear-gradient(135deg, #f97316, #facc15);
        font-size: 0.8rem;
        font-weight: 600;
        cursor: pointer;
        box-shadow: 0 10px 25px rgba(15, 23, 42, 0.9);
      }

      /* Layout */
      .main {
        padding: 18px 22px 26px;
        flex: 1;
        display: flex;
        flex-direction: column;
        gap: 26px;
      }

      .dashboard-grid {
        display: grid;
        grid-template-columns: minmax(0, 3fr) minmax(260px, 1.4fr);
        gap: 18px;
        padding: 18px 22px 26px;
      }

      @media (max-width: 960px) {
        .dashboard-grid {
          grid-template-columns: minmax(0, 1fr);
        }
        .topbar {
          flex-wrap: wrap;
          gap: 10px;
        }
      }

      .card {
        background: radial-gradient(circle at top left, #111827 0, #020617 65%);
        border-radius: 20px;
        border: 1px solid rgba(31, 41, 55, 0.9);
        box-shadow: 0 18px 45px rgba(15, 23, 42, 0.9);
        padding: 16px 16px 14px;
        position: relative;
        overflow: hidden;
      }

      .card::before {
        content: "";
        position: absolute;
        inset: -60%;
        background: radial-gradient(
          circle at 0 0,
          rgba(94, 234, 212, 0.08),
          transparent 55%
        );
        opacity: 0.5;
        pointer-events: none;
      }

      .card-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 4px;
      }

      .card-title {
        font-size: 0.95rem;
        font-weight: 600;
        letter-spacing: 0.08em;
        text-transform: uppercase;
        color: #e5e7eb;
      }

      .card-subtitle {
        font-size: 0.8rem;
        color: var(--muted);
      }

      .card-actions {
        display: flex;
        gap: 6px;
        align-items: center;
      }

      .chip {
        padding: 3px 9px;
        border-radius: 999px;
        font-size: 0.7rem;
        border: 1px solid rgba(55, 65, 81, 0.9);
        color: var(--muted);
      }

      .chip-ghost {
        background: rgba(15, 23, 42, 0.8);
      }

      .chip-success {
        border-color: rgba(34, 197, 94, 0.85);
        color: #bbf7d0;
        background: rgba(22, 163, 74, 0.12);
      }

      .divider {
        width: 100%;
        height: 1px;
        background: linear-gradient(
          to right,
          transparent,
          rgba(31, 41, 55, 0.9),
          transparent
        );
        margin: 10px 0 12px;
      }

      /* Filters */
      .filters {
        display: flex;
        flex-wrap: wrap;
        gap: 8px;
        align-items: center;
        margin-bottom: 4px;
      }

      .filters-group {
        display: flex;
        gap: 6px;
        flex-wrap: wrap;
      }

      .filter-label {
        font-size: 0.75rem;
        color: var(--muted);
      }

      .select,
      .input {
        background: rgba(15, 23, 42, 0.95);
        border-radius: 999px;
        border: 1px solid rgba(55, 65, 81, 0.9);
        color: #e5e7eb;
        font-size: 0.8rem;
        padding: 5px 10px;
        outline: none;
      }

      .select:hover,
      .input:hover,
      .select:focus,
      .input:focus {
        border-color: rgba(129, 140, 248, 0.9);
      }

      .select {
        padding-right: 26px;
      }

      .btn-outline {
        border-radius: 999px;
        padding: 5px 11px;
        border: 1px dashed rgba(75, 85, 99, 0.9);
        background: rgba(15, 23, 42, 0.9);
        color: #e5e7eb;
        font-size: 0.75rem;
        cursor: pointer;
        display: flex;
        align-items: center;
        gap: 6px;
      }

      .btn-outline span.icon {
        color: #22c55e;
        font-size: 0.9rem;
      }

      .btn-outline:hover {
        border-style: solid;
        border-color: rgba(129, 140, 248, 0.9);
      }

      /* Chart container */
      .chart-wrap {
        position: relative;
        width: 100%;
        min-height: 260px;
        padding-top: 4px;
      }

      canvas {
        width: 100% !important;
        height: 100% !important;
      }

      .chart-footer {
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
        margin-top: 10px;
        font-size: 0.75rem;
        color: var(--muted);
      }

      .legend {
        display: flex;
        align-items: center;
        gap: 12px;
        flex-wrap: wrap;
      }

      .legend-item {
        display: flex;
        align-items: center;
        gap: 6px;
      }

      .legend-dot {
        width: 9px;
        height: 9px;
        border-radius: 999px;
      }

      .legend-dot.sales {
        background: #4f46e5;
      }
      .legend-dot.count {
        background: #22c55e;
      }

      .summary {
        display: flex;
        gap: 10px;
        flex-wrap: wrap;
      }

      .summary-item {
        min-width: 90px;
        padding: 8px 10px;
        border-radius: 14px;
        background: rgba(15, 23, 42, 0.9);
        border: 1px solid rgba(31, 41, 55, 0.95);
      }

      .summary-label {
        font-size: 0.7rem;
        color: var(--muted);
        margin-bottom: 2px;
      }

      .summary-value {
        font-size: 0.9rem;
        font-weight: 600;
      }

      .summary-trend-positive {
        color: #4ade80;
        font-size: 0.7rem;
      }

      /* Right column */
      .right-column {
        display: flex;
        flex-direction: column;
        gap: 14px;
      }

      .ceud-list {
        display: flex;
        flex-direction: column;
        gap: 8px;
        margin-top: 6px;
        max-height: 280px;
        overflow-y: auto;
        padding-right: 4px;
      }

      .ceud-item {
        padding: 8px 9px;
        border-radius: 12px;
        background: rgba(15, 23, 42, 0.9);
        border: 1px solid rgba(31, 41, 55, 0.95);
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 8px;
      }

      .ceud-title {
        font-size: 0.8rem;
      }

      .ceud-meta {
        font-size: 0.7rem;
        color: var(--muted);
      }

      .ceud-badge {
        font-size: 0.7rem;
        padding: 2px 7px;
        border-radius: 999px;
        border: 1px solid rgba(55, 65, 81, 0.9);
        color: var(--muted);
      }

      .tag {
        font-size: 0.7rem;
        padding: 2px 7px;
        border-radius: 999px;
        background: rgba(15, 23, 42, 0.9);
        border: 1px solid rgba(55, 65, 81, 0.9);
        color: var(--muted);
        margin-right: 4px;
      }

      .busy-tag {
        border-color: rgba(248, 250, 252, 0.3);
        color: #e5e7eb;
      }

      .footer-note {
        font-size: 0.7rem;
        color: var(--muted);
        margin-top: 6px;
      }

      .small-input-row {
        display: flex;
        flex-wrap: wrap;
        gap: 6px;
        margin-top: 6px;
      }

      .small-input-row .input,
      .small-input-row .select {
        font-size: 0.75rem;
        padding: 4px 9px;
      }

      .small-input-row button {
        font-size: 0.75rem;
        padding: 4px 11px;
        border-radius: 999px;
        border: none;
        background: linear-gradient(135deg, #4f46e5, #22c55e);
        color: #f9fafb;
        cursor: pointer;
      }

      .note {
        font-size: 0.7rem;
        color: var(--muted);
        margin-top: 2px;
      }

      /* Hero & sections */
      .hero {
        display: grid;
        grid-template-columns: minmax(0, 2.2fr) minmax(0, 1.6fr);
        gap: 24px;
        align-items: center;
        padding: 6px 22px 0;
      }

      .hero-main-title {
        font-size: 1.6rem;
        font-weight: 700;
        margin-bottom: 6px;
      }

      .hero-subtitle {
        font-size: 0.95rem;
        color: var(--muted);
        margin-bottom: 12px;
      }

      .hero-badges {
        display: flex;
        gap: 8px;
        flex-wrap: wrap;
        margin-bottom: 14px;
      }

      .hero-actions {
        display: flex;
        gap: 10px;
        flex-wrap: wrap;
      }

      .btn-primary {
        border-radius: 999px;
        padding: 8px 18px;
        border: none;
        background: linear-gradient(135deg, #4f46e5, #22c55e);
        color: #f9fafb;
        font-size: 0.85rem;
        font-weight: 600;
        cursor: pointer;
      }

      .btn-secondary {
        border-radius: 999px;
        padding: 8px 16px;
        border: 1px solid rgba(55, 65, 81, 0.9);
        background: rgba(15, 23, 42, 0.9);
        color: #e5e7eb;
        font-size: 0.8rem;
        cursor: pointer;
      }

      .hero-highlight {
        display: grid;
        gap: 8px;
        padding: 14px;
        border-radius: 18px;
        border: 1px solid rgba(31, 41, 55, 0.9);
        background: radial-gradient(circle at top, #111827 0, #020617 70%);
      }

      .hero-metric-label {
        font-size: 0.75rem;
        color: var(--muted);
      }

      .hero-metric-value {
        font-size: 1.1rem;
        font-weight: 600;
      }

      .section-heading {
        padding: 0 22px;
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        gap: 8px;
      }

      .section-title {
        font-size: 1.05rem;
        font-weight: 600;
        letter-spacing: 0.08em;
        text-transform: uppercase;
      }

      .section-subtitle {
        font-size: 0.85rem;
        color: var(--muted);
      }

      /* Services / Pricing */
      .services-grid {
        padding: 10px 22px 0;
        display: grid;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        gap: 14px;
      }

      @media (max-width: 1100px) {
        .hero {
          grid-template-columns: minmax(0, 1fr);
        }
        .services-grid {
          grid-template-columns: repeat(2, minmax(0, 1fr));
        }
      }

      @media (max-width: 720px) {
        .services-grid {
          grid-template-columns: minmax(0, 1fr);
        }
      }

      .service-card {
        background: radial-gradient(circle at top left, #020617 0, #020617 65%);
        border-radius: 18px;
        border: 1px solid rgba(31, 41, 55, 0.9);
        padding: 12px 14px 11px;
      }

      .service-title {
        font-size: 0.9rem;
        font-weight: 600;
        margin-bottom: 4px;
      }

      .service-desc {
        font-size: 0.75rem;
        color: var(--muted);
        margin-bottom: 6px;
      }

      .service-item-row {
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        font-size: 0.8rem;
        margin-bottom: 4px;
      }

      .service-item-name {
        color: #e5e7eb;
      }

      .service-item-price {
        font-weight: 600;
        color: #a5b4fc;
      }

      .service-tagline {
        font-size: 0.7rem;
        color: var(--muted);
        margin-top: 4px;
      }

      /* Simple reports/settings */
      .simple-card-row {
        padding: 10px 22px 0;
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 14px;
      }

      @media (max-width: 880px) {
        .simple-card-row {
          grid-template-columns: minmax(0, 1fr);
        }
      }

      .simple-list {
        list-style: none;
        padding-left: 0;
        margin-top: 6px;
      }

      .simple-list li {
        font-size: 0.8rem;
        color: var(--muted);
        margin-bottom: 4px;
      }

      /* Tickets table */
      .tickets-card {
        margin: 12px 22px 0;
      }

      .tickets-table-wrap {
        width: 100%;
        overflow-x: auto;
        margin-top: 8px;
      }

      .tickets-table {
        width: 100%;
        border-collapse: collapse;
        font-size: 0.78rem;
      }

      .tickets-table th,
      .tickets-table td {
        padding: 6px 8px;
        border-bottom: 1px solid rgba(31, 41, 55, 0.8);
        white-space: nowrap;
      }

      .tickets-table th {
        text-align: left;
        color: var(--muted);
        font-weight: 500;
      }

      .tickets-table-actions {
        display: flex;
        gap: 6px;
      }

      .tickets-table-actions button {
        border-radius: 999px;
        border: 1px solid rgba(55, 65, 81, 0.9);
        background: rgba(15, 23, 42, 0.95);
        color: #e5e7eb;
        padding: 3px 8px;
        font-size: 0.7rem;
        cursor: pointer;
      }

      .tickets-table-actions button.delete {
        border-color: rgba(239, 68, 68, 0.8);
        color: #fecaca;
      }

      /* Service master management */
      .service-master-form {
        display: flex;
        flex-wrap: wrap;
        gap: 6px;
        margin-top: 6px;
      }

      .service-master-form .input,
      .service-master-form .select {
        font-size: 0.75rem;
        padding: 4px 9px;
      }

      .service-master-form button {
        font-size: 0.75rem;
        padding: 4px 12px;
        border-radius: 999px;
        border: none;
        background: linear-gradient(135deg, #4f46e5, #22c55e);
        color: #f9fafb;
        cursor: pointer;
      }

      footer {
        padding: 10px 22px 16px;
        font-size: 0.75rem;
        color: var(--muted);
        border-top: 1px solid rgba(31, 41, 55, 0.9);
        background: rgba(15, 23, 42, 0.96);
      }
    </style>
  </head>
  <body>
    <div class="app">
      <header class="topbar">
        <div class="brand">
          <div class="brand-logo"></div>
          <div>
            <div class="brand-text-main">LK E-SOLUTIONS</div>
            <div class="brand-text-sub">DIGITAL SEVA & E‑SERVICES CEUD SYSTEM</div>
          </div>
        </div>
        <nav class="menu" aria-label="Main navigation">
          <button class="active" type="button" data-target="dashboard">
            <span class="icon">🆕</span>
            <span>Create</span>
          </button>
          <button type="button" data-target="services">
            <span class="icon">✏️</span>
            <span>Edit</span>
          </button>
          <button type="button" data-target="reports">
            <span class="icon">🔁</span>
            <span>Update</span>
          </button>
          <button type="button" data-target="settings">
            <span class="icon">🗑️</span>
            <span>Delete</span>
          </button>
          <button type="button" data-target="reports">
            <span class="icon">📈</span>
            <span>Reports</span>
          </button>
        </nav>
        <div class="right-actions">
          <div class="pill">
            <span class="pill-dot"></span>
            LIVE CEUD SYSTEM
          </div>
          <button class="pill-cta" type="button">+ New Ticket</button>
        </div>
      </header>

      <main class="main">
        <!-- Hero / Landing -->
        <section id="hero" class="hero">
          <div>
            <h1 class="hero-main-title">
              Smart CEUD dashboard for your Digital Seva shop
            </h1>
            <p class="hero-subtitle">
              Track Xerox, print, lamination, Aadhaar, E‑services and more –
              with live monthly sales graph and busy time slots.
            </p>
            <div class="hero-badges">
              <span class="chip chip-success">Monthly sales line chart</span>
              <span class="chip chip-ghost">Busy timing by hour</span>
              <span class="chip chip-ghost">Manual CEUD data entry</span>
            </div>
            <div class="hero-actions">
              <button
                class="btn-primary"
                type="button"
                onclick="scrollToSection('dashboard')"
              >
                Open CEUD Dashboard
              </button>
              <button
                class="btn-secondary"
                type="button"
                onclick="scrollToSection('services')"
              >
                View Services &amp; Pricing
              </button>
            </div>
          </div>
          <div class="hero-highlight">
            <div>
              <div class="hero-metric-label">Today estimated sales (sample)</div>
              <div class="hero-metric-value" id="heroTodaySales">₹0</div>
            </div>
            <div>
              <div class="hero-metric-label">Peak busy slot (today)</div>
              <div class="hero-metric-value" id="heroPeakSlot">–</div>
            </div>
            <p class="service-tagline">
              This panel auto-updates when you add new tickets in the CEUD
              Dashboard.
            </p>
          </div>
        </section>

        <!-- Dashboard section -->
        <div id="dashboard" class="section-heading">
          <div>
            <div class="section-title">Dashboard</div>
            <p class="section-subtitle">
              Monthly sales line chart with ticket count and hour wise busy
              timing.
            </p>
          </div>
        </div>

        <section class="dashboard-grid">
          <!-- Left: Monthly Sales & Busy Time Line Chart -->
          <section class="card">
          <div class="card-header">
            <div>
              <div class="card-title">Monthly Sales & Busy Time</div>
              <div class="card-subtitle">
                Line chart by date & time to track peak hours in your center
              </div>
            </div>
            <div class="card-actions">
              <span class="chip chip-ghost">CEUD Analytics</span>
              <span class="chip chip-success">Auto-updated</span>
            </div>
          </div>

          <div class="divider"></div>

          <div class="filters">
            <div class="filters-group">
              <span class="filter-label">Period</span>
              <select id="periodSelect" class="select">
                <option value="30">Last 30 days</option>
                <option value="7">Last 7 days</option>
                <option value="today">Today (by hour)</option>
              </select>
            </div>
            <div class="filters-group">
              <span class="filter-label">Category</span>
              <select id="serviceFilter" class="select">
                <option value="all">All categories</option>
                <option value="Printing">Printing &amp; Xerox</option>
                <option value="Lamination">Lamination &amp; ID</option>
                <option value="Typing">Typing</option>
                <option value="E-Services">E‑Services</option>
                <option value="Others">Others</option>
              </select>
            </div>
            <button id="downloadBtn" class="btn-outline" type="button">
              <span class="icon">⬇</span>
              Export chart
            </button>
          </div>

          <div class="chart-wrap">
            <canvas id="salesChart"></canvas>
          </div>

          <div class="chart-footer">
            <div class="legend">
              <div class="legend-item">
                <span class="legend-dot sales"></span>
                <span>Sales amount (₹)</span>
              </div>
              <div class="legend-item">
                <span class="legend-dot count"></span>
                <span>Number of tickets</span>
              </div>
            </div>
            <div class="summary">
              <div class="summary-item">
                <div class="summary-label">Total Sales</div>
                <div id="totalSales" class="summary-value">₹0</div>
                <div id="salesTrend" class="summary-trend-positive">
                  +0% vs last period
                </div>
              </div>
              <div class="summary-item">
                <div class="summary-label">Peak Busy Time</div>
                <div id="peakTime" class="summary-value">–</div>
                <div class="summary-trend-positive">
                  Based on ticket count
                </div>
              </div>
            </div>
          </div>
        </section>

          <!-- Right: CEUD System Quick Actions & Busy Slots -->
          <aside class="right-column">
          <section class="card">
            <div class="card-header">
              <div>
                <div class="card-title">CEUD System Quick Entry</div>
                <div class="card-subtitle">
                  Add new service ticket with date, time and pages/amount
                </div>
              </div>
              <span class="chip chip-ghost">CRUD: Create / Update</span>
            </div>
            <div class="divider"></div>

            <div class="small-input-row">
              <input
                id="ticketDate"
                class="input"
                type="date"
                aria-label="Ticket date"
              />
              <input
                id="ticketTime"
                class="input"
                type="time"
                step="1800"
                aria-label="Ticket time"
              />
              <select
                id="ticketService"
                class="select"
                aria-label="Service type"
              ></select>
              <input
                id="ticketQty"
                class="input"
                type="number"
                min="1"
                step="1"
                placeholder="Qty / pages"
                aria-label="Quantity / pages"
              />
              <input
                id="ticketAmount"
                class="input"
                type="number"
                min="0"
                step="10"
                placeholder="Amount ₹"
                aria-label="Amount"
              />
              <button id="addTicketBtn" type="button">Add</button>
            </div>
            <p class="note">
              The new entry will directly reflect in the monthly line chart and
              busy time analytics. Amount is auto-calculated for fixed price
              services and can be edited.
            </p>
            <p id="ticketMessage" class="note"></p>
          </section>

          <section class="card">
            <div class="card-header">
              <div>
                <div class="card-title">Today Busy Timing</div>
                <div class="card-subtitle">
                  Slots with highest number of tickets (real-time view)
                </div>
              </div>
              <span class="chip chip-ghost">Monitor live</span>
            </div>
            <div class="divider"></div>

            <div id="busySlots" class="ceud-list">
              <!-- Filled by JS -->
            </div>
            <p class="footer-note">
              <span class="tag busy-tag">Tip</span>
              Use peak busy hours to plan extra staff & systems in your Digital
              Seva shop.
            </p>
          </section>
          </aside>
        </section>

        <!-- Tickets table: Edit / Delete -->
        <section id="ticketsSection" class="tickets-card">
          <article class="card">
            <div class="card-header">
              <div>
                <div class="card-title">CEUD Tickets (Edit / Delete)</div>
                <div class="card-subtitle">
                  List of recent tickets with options to edit quantity, amount or remove.
                </div>
              </div>
              <div class="filters-group">
                <span class="filter-label">Filter by date</span>
                <input
                  id="ticketsFilterDate"
                  class="input"
                  type="date"
                  aria-label="Filter tickets by date"
                />
              </div>
            </div>
            <div class="divider"></div>
            <div class="tickets-table-wrap">
              <table class="tickets-table">
                <thead>
                  <tr>
                    <th>Date</th>
                    <th>Time</th>
                    <th>Service</th>
                    <th>Qty</th>
                    <th>Amount (₹)</th>
                    <th>Actions</th>
                  </tr>
                </thead>
                <tbody id="ticketsTableBody">
                  <!-- Filled by JS -->
                </tbody>
              </table>
            </div>
            <p class="footer-note" id="ticketsSummaryNote">
              <!-- Filled by JS with total count/amount -->
            </p>
          </article>
        </section>

        <!-- Services / Pricing -->
        <div id="services" class="section-heading">
          <div>
            <div class="section-title">Services &amp; Pricing</div>
            <p class="section-subtitle">
              Xerox, printout, lamination, Aadhaar ID, typing, e‑services and
              other works in one place.
            </p>
          </div>
        </div>
        <section class="services-grid">
          <article class="service-card">
            <h3 class="service-title">Printing &amp; Xerox</h3>
            <p class="service-desc">
              Fast printing and Xerox for office, school and personal works.
            </p>
            <div class="service-item-row">
              <span class="service-item-name">Xerox</span>
              <span class="service-item-price">₹2 / paper</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">Printout B/W</span>
              <span class="service-item-price">₹5 / paper</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">Color Xerox</span>
              <span class="service-item-price">₹10 / paper</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">Printout Color</span>
              <span class="service-item-price">₹10 / paper</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">Legal</span>
              <span class="service-item-price">₹7 / paper</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">A3 Xerox</span>
              <span class="service-item-price">₹5 / paper</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">A3 Printout</span>
              <span class="service-item-price">₹10 / paper</span>
            </div>
            <p class="service-tagline">
              Auto-calculated prices in CEUD form using pages × rate.
            </p>
          </article>

          <article class="service-card">
            <h3 class="service-title">Lamination &amp; ID</h3>
            <p class="service-desc">
              Protect your cards and documents with quality lamination.
            </p>
            <div class="service-item-row">
              <span class="service-item-name">Lamination A4</span>
              <span class="service-item-price">₹25 / sheet</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">ID Card Lamination</span>
              <span class="service-item-price">₹50 / sheet</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">Aadhaar ID</span>
              <span class="service-item-price">₹20 / sheet</span>
            </div>
            <p class="service-tagline">
              Use the CEUD dashboard to see peak time for ID and lamination
              jobs.
            </p>
          </article>

          <article class="service-card">
            <h3 class="service-title">Typing Services</h3>
            <p class="service-desc">
              Professional typing support for resumes and official documents.
            </p>
            <div class="service-item-row">
              <span class="service-item-name">Resume Typing</span>
              <span class="service-item-price">₹35 / page</span>
            </div>
            <div class="service-item-row">
              <span class="service-item-name">Document Typing</span>
              <span class="service-item-price">₹50 / page</span>
            </div>
            <p class="service-tagline">
              Enter number of pages to auto-calculate amount in CEUD entry form.
            </p>
          </article>

          <article class="service-card">
            <h3 class="service-title">E‑Services</h3>
            <p class="service-desc">
              Online services like ticket booking, bill payment and forms.
            </p>
            <div class="service-item-row">
              <span class="service-item-name">Manual e‑service</span>
              <span class="service-item-price">₹ (enter per work)</span>
            </div>
            <p class="service-tagline">
              Prices are entered manually per transaction in the CEUD form.
            </p>
          </article>

          <article class="service-card">
            <h3 class="service-title">Other Services</h3>
            <p class="service-desc">
              Any extra service you provide can be tracked under “Other Service”.
            </p>
            <div class="service-item-row">
              <span class="service-item-name">Other Service</span>
              <span class="service-item-price">₹ (enter manually)</span>
            </div>
            <p class="service-tagline">
              Rename this service text in HTML if you have a fixed common work.
            </p>
          </article>
        </section>

        <!-- Reports & Settings -->
        <div id="reports" class="section-heading">
          <div>
            <div class="section-title">Reports</div>
            <p class="section-subtitle">
              Quick view of how your Digital Seva center is performing.
            </p>
          </div>
        </div>
        <section class="simple-card-row">
          <article class="card">
            <div class="card-header">
              <div>
                <div class="card-title">Summary (sample)</div>
                <div class="card-subtitle">
                  This is a simple text report based on the same CEUD data.
                </div>
              </div>
            </div>
            <div class="divider"></div>
            <ul class="simple-list" id="reportSummaryList">
              <!-- Filled by JS using same tickets array -->
            </ul>
            <div class="small-input-row">
              <button id="exportSalesBtn" type="button">Download sales data (JSON)</button>
              <button id="exportServicesBtn" type="button">Download services (JSON)</button>
            </div>
            <div class="small-input-row">
              <label class="note">
                Import sales JSON
                <input
                  id="importSalesInput"
                  type="file"
                  accept="application/json"
                  aria-label="Import sales data JSON"
                />
              </label>
              <label class="note">
                Import services JSON
                <input
                  id="importServicesInput"
                  type="file"
                  accept="application/json"
                  aria-label="Import services master JSON"
                />
              </label>
            </div>
            <p class="note">
              Data is stored only in this browser while the page is open. Use the
              JSON download buttons above regularly as a backup file.
            </p>
          </article>
          <article class="card">
            <div class="card-header">
              <div>
                <div class="card-title">How to read this dashboard</div>
                <div class="card-subtitle">
                  Small guide so staff can understand the charts quickly.
                </div>
              </div>
            </div>
            <div class="divider"></div>
            <ul class="simple-list">
              <li>Use the form on right side to add every customer work.</li>
              <li>
                Select correct service and pages/quantity to get accurate sales.
              </li>
              <li>
                Check the line chart to see which days/hours give more income.
              </li>
              <li>
                See “Today Busy Timing” to decide when extra staff is required.
              </li>
            </ul>
          </article>
        </section>

        <div id="settings" class="section-heading">
          <div>
            <div class="section-title">Settings</div>
            <p class="section-subtitle">
              Basic details about your Digital Seva center.
            </p>
          </div>
        </div>
        <section class="simple-card-row">
          <article class="card">
            <div class="card-header">
              <div>
                <div class="card-title">Center information</div>
                <div class="card-subtitle">
                  Overview of your shop identity and contact details.
                </div>
              </div>
            </div>
            <div class="divider"></div>
            <ul class="simple-list">
              <li>Shop name and logo for your Digital Seva services.</li>
              <li>Owner / contact person and mobile number.</li>
              <li>Full address with landmark for customer reference.</li>
              <li>WhatsApp number or email ID for quick enquiries.</li>
            </ul>
          </article>
          <article class="card">
            <div class="card-header">
              <div>
                <div class="card-title">Service policy</div>
                <div class="card-subtitle">
                  Simple points for pricing and customer service.
                </div>
              </div>
            </div>
            <div class="divider"></div>
            <ul class="simple-list">
              <li>Clear rates for Xerox, printout, lamination and typing.</li>
              <li>Separate charges for urgent and bulk works if required.</li>
              <li>Timing of shop opening and closing for each day.</li>
              <li>Short note about quality and data confidentiality.</li>
            </ul>
          </article>
          <article class="card">
            <div class="card-header">
              <div>
                <div class="card-title">Service master (update rates)</div>
                <div class="card-subtitle">
                  Manage fixed services, e‑services and other custom works.
                </div>
              </div>
            </div>
            <div class="divider"></div>
            <div class="service-master-form">
              <input
                id="serviceNameInput"
                class="input"
                type="text"
                placeholder="Service name"
                aria-label="Service name"
              />
              <select
                id="serviceCategoryInput"
                class="select"
                aria-label="Service category"
              >
                <option value="Printing">Printing &amp; Xerox</option>
                <option value="Lamination">Lamination &amp; ID</option>
                <option value="Typing">Typing</option>
                <option value="E-Services">E‑Services</option>
                <option value="Others">Others</option>
              </select>
              <input
                id="serviceUnitInput"
                class="input"
                type="text"
                placeholder="Unit (paper/sheet/page/work)"
                aria-label="Service unit"
              />
              <input
                id="servicePriceInput"
                class="input"
                type="number"
                min="0"
                step="1"
                placeholder="Rate (₹)"
                aria-label="Service rate"
              />
              <label class="note" style="display: flex; align-items: center; gap: 4px">
                <input
                  id="serviceAutoPriceInput"
                  type="checkbox"
                  checked
                  aria-label="Auto-calc price from quantity"
                />
                Auto-calc from quantity
              </label>
              <button id="saveServiceBtn" type="button">Add / Update</button>
            </div>
            <p class="note">
              New services will appear in the CEUD Create form dropdown. Use the
              same name again to update rate or unit.
            </p>
            <ul class="simple-list" id="serviceMasterList">
              <!-- Filled by JS from SERVICES_CATALOG -->
            </ul>
          </article>
        </section>
      </main>
      <footer>
        © <span id="footerYear"></span> Digital Seva Center CEUD Dashboard.
        Replace this line with your address / contact number.
      </footer>
    </div>

    <!-- Chart.js CDN -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.min.js"></script>
    <script>
      // --- SERVICES & PRICING CATALOG --------------------------------------
      // Change prices or add services here. Name should match dropdown options.
      const SERVICES_CATALOG = [
        // Printing & Xerox
        {
          name: "Xerox",
          category: "Printing",
          unit: "paper",
          price: 2,
          autoPrice: true,
        },
        {
          name: "Printout B/W",
          category: "Printing",
          unit: "paper",
          price: 5,
          autoPrice: true,
        },
        {
          name: "Color Xerox",
          category: "Printing",
          unit: "paper",
          price: 10,
          autoPrice: true,
        },
        {
          name: "Printout Color",
          category: "Printing",
          unit: "paper",
          price: 10,
          autoPrice: true,
        },
        {
          name: "Legal",
          category: "Printing",
          unit: "paper",
          price: 7,
          autoPrice: true,
        },
        {
          name: "A3 Xerox",
          category: "Printing",
          unit: "paper",
          price: 5,
          autoPrice: true,
        },
        {
          name: "A3 Printout",
          category: "Printing",
          unit: "paper",
          price: 10,
          autoPrice: true,
        },
        // Lamination & ID
        {
          name: "Lamination A4",
          category: "Lamination",
          unit: "sheet",
          price: 25,
          autoPrice: true,
        },
        {
          name: "ID Card Lamination",
          category: "Lamination",
          unit: "sheet",
          price: 50,
          autoPrice: true,
        },
        {
          name: "Aadhaar ID",
          category: "Lamination",
          unit: "sheet",
          price: 20,
          autoPrice: true,
        },
        // Typing
        {
          name: "Resume Typing",
          category: "Typing",
          unit: "page",
          price: 35,
          autoPrice: true,
        },
        {
          name: "Document Typing",
          category: "Typing",
          unit: "page",
          price: 50,
          autoPrice: true,
        },
        // E-Services
        {
          name: "E-Service (Manual)",
          category: "E-Services",
          unit: "work",
          price: 0,
          autoPrice: false,
        },
        // Others
        {
          name: "Other Service",
          category: "Others",
          unit: "work",
          price: 0,
          autoPrice: false,
        },
      ];

      function findServiceByName(name) {
        return SERVICES_CATALOG.find((s) => s.name === name) || null;
      }

      function populateServiceDropdown() {
        const select = document.getElementById("ticketService");
        if (!select) return;
        select.innerHTML = "";
        SERVICES_CATALOG.forEach((service) => {
          const option = document.createElement("option");
          option.value = service.name;
          const priceText =
            service.price && service.price > 0
              ? ` – ₹${service.price} / ${service.unit}`
              : " – manual rate";
          option.textContent = `${service.name}${priceText}`;
          select.appendChild(option);
        });
      }

      function renderServiceMasterList() {
        const list = document.getElementById("serviceMasterList");
        if (!list) return;
        list.innerHTML = "";
        SERVICES_CATALOG.forEach((service) => {
          const li = document.createElement("li");
          const priceText =
            service.price && service.price > 0
              ? `₹${service.price} / ${service.unit}`
              : "Manual rate";
          li.textContent = `${service.name} – ${priceText} (${service.category})${
            service.autoPrice ? " • Auto" : " • Manual"
          }`;
          list.appendChild(li);
        });
      }

      function upsertServiceFromForm() {
        const nameInput = document.getElementById("serviceNameInput");
        const categoryInput = document.getElementById("serviceCategoryInput");
        const unitInput = document.getElementById("serviceUnitInput");
        const priceInput = document.getElementById("servicePriceInput");
        const autoInput = document.getElementById("serviceAutoPriceInput");

        if (!nameInput || !categoryInput || !unitInput || !priceInput) return;

        const name = nameInput.value.trim();
        if (!name) {
          alert("Please enter a service name.");
          return;
        }

        const category = categoryInput.value || "Others";
        const unit = unitInput.value.trim() || "work";
        const price = Number(priceInput.value || 0);
        const autoPrice = !!autoInput.checked;

        const existingIndex = SERVICES_CATALOG.findIndex(
          (s) => s.name.toLowerCase() === name.toLowerCase()
        );
        const serviceObj = {
          name,
          category,
          unit,
          price,
          autoPrice,
        };

        if (existingIndex >= 0) {
          SERVICES_CATALOG[existingIndex] = serviceObj;
        } else {
          SERVICES_CATALOG.push(serviceObj);
        }

        populateServiceDropdown();
        renderServiceMasterList();

        nameInput.value = "";
        priceInput.value = "";
      }

      // --- Sample data (you can replace with your real CEUD data) ----------
      // Each ticket:
      // { id, dateISO, time, serviceName, unitPrice, quantity, totalAmount,
      //   category, date, service, amount }
      let tickets = [
        {
          id: "T1",
          dateISO: "2025-12-01",
          time: "09:20",
          serviceName: "Xerox",
          unitPrice: 2,
          quantity: 10,
          totalAmount: 20,
          category: "Printing",
          // legacy keys used by chart / reports helpers
          date: "2025-12-01",
          service: "Xerox",
          amount: 20,
        },
        {
          id: "T2",
          dateISO: "2025-12-01",
          time: "09:45",
          serviceName: "Printout B/W",
          unitPrice: 5,
          quantity: 5,
          totalAmount: 25,
          category: "Printing",
          date: "2025-12-01",
          service: "Printout B/W",
          amount: 25,
        },
        {
          id: "T3",
          dateISO: "2025-12-01",
          time: "10:15",
          serviceName: "Color Xerox",
          unitPrice: 10,
          quantity: 5,
          totalAmount: 50,
          category: "Printing",
          date: "2025-12-01",
          service: "Color Xerox",
          amount: 50,
        },
        {
          id: "T4",
          dateISO: "2025-12-01",
          time: "11:10",
          serviceName: "Lamination A4",
          unitPrice: 25,
          quantity: 1,
          totalAmount: 25,
          category: "Lamination",
          date: "2025-12-01",
          service: "Lamination A4",
          amount: 25,
        },
        {
          id: "T5",
          dateISO: "2025-12-01",
          time: "11:40",
          serviceName: "Aadhaar ID",
          unitPrice: 20,
          quantity: 2,
          totalAmount: 40,
          category: "Lamination",
          date: "2025-12-01",
          service: "Aadhaar ID",
          amount: 40,
        },
        {
          id: "T6",
          dateISO: "2025-12-01",
          time: "12:05",
          serviceName: "Resume Typing",
          unitPrice: 35,
          quantity: 2,
          totalAmount: 70,
          category: "Typing",
          date: "2025-12-01",
          service: "Resume Typing",
          amount: 70,
        },
        {
          id: "T7",
          dateISO: "2025-12-02",
          time: "09:10",
          serviceName: "Xerox",
          unitPrice: 2,
          quantity: 8,
          totalAmount: 16,
          category: "Printing",
          date: "2025-12-02",
          service: "Xerox",
          amount: 16,
        },
        {
          id: "T8",
          dateISO: "2025-12-02",
          time: "10:05",
          serviceName: "Printout Color",
          unitPrice: 10,
          quantity: 6,
          totalAmount: 60,
          category: "Printing",
          date: "2025-12-02",
          service: "Printout Color",
          amount: 60,
        },
        {
          id: "T9",
          dateISO: "2025-12-02",
          time: "10:40",
          serviceName: "Lamination A4",
          unitPrice: 25,
          quantity: 1,
          totalAmount: 25,
          category: "Lamination",
          date: "2025-12-02",
          service: "Lamination A4",
          amount: 25,
        },
        {
          id: "T10",
          dateISO: "2025-12-02",
          time: "11:30",
          serviceName: "E-Service (Manual)",
          unitPrice: 0,
          quantity: 1,
          totalAmount: 120,
          category: "E-Services",
          date: "2025-12-02",
          service: "E-Service (Manual)",
          amount: 120,
        },
        {
          id: "T11",
          dateISO: "2025-12-02",
          time: "12:20",
          serviceName: "Other Service",
          unitPrice: 0,
          quantity: 1,
          totalAmount: 80,
          category: "Others",
          date: "2025-12-02",
          service: "Other Service",
          amount: 80,
        },
      ];

      // Helpers
      function parseDate(dateStr) {
        const [y, m, d] = dateStr.split("-").map(Number);
        return new Date(y, m - 1, d);
      }

      function formatDateDisplay(dateStr) {
        const d = parseDate(dateStr);
        return d.toLocaleDateString("en-IN", {
          day: "2-digit",
          month: "short",
        });
      }

      function getTodayISO() {
        const d = new Date();
        const y = d.getFullYear();
        const m = String(d.getMonth() + 1).padStart(2, "0");
        const day = String(d.getDate()).padStart(2, "0");
        return `${y}-${m}-${day}`;
      }

      function withinDays(dateStr, days) {
        const d = parseDate(dateStr);
        const today = new Date();
        const diffMs = today - d;
        const diffDays = diffMs / (1000 * 60 * 60 * 24);
        return diffDays >= 0 && diffDays < days;
      }

      function groupData(period, categoryFilter) {
        const filtered = tickets.filter((t) => {
          if (categoryFilter !== "all") {
            if (t.category !== categoryFilter) return false;
          }
          if (period === "today") {
            return t.date === getTodayISO();
          }
          if (period === "7") {
            return withinDays(t.date, 7);
          }
          if (period === "30") {
            return withinDays(t.date, 30);
          }
          return true;
        });

        if (filtered.length === 0) {
          return { labels: [], amounts: [], counts: [], peakSlot: null };
        }

        // If today, group by hour block; else, group by date
        const isToday = period === "today";
        const groups = new Map();
        filtered.forEach((t) => {
          let key;
          if (isToday) {
            const hour = t.time.slice(0, 2);
            key = `${hour}:00 - ${hour}:59`;
          } else {
            key = t.date;
          }
          const prev = groups.get(key) || { amount: 0, count: 0 };
          prev.amount += t.amount;
          prev.count += 1;
          groups.set(key, prev);
        });

        const labels = Array.from(groups.keys()).sort((a, b) => {
          if (isToday) {
            return parseInt(a, 10) - parseInt(b, 10);
          }
          return parseDate(a) - parseDate(b);
        });

        const amounts = labels.map((key) => groups.get(key).amount);
        const counts = labels.map((key) => groups.get(key).count);

        // Peak slot = label with max count
        let peakSlot = null;
        if (labels.length > 0) {
          let maxIdx = 0;
          counts.forEach((c, i) => {
            if (c > counts[maxIdx]) maxIdx = i;
          });
          peakSlot = labels[maxIdx];
        }

        return { labels, amounts, counts, peakSlot };
      }

      // Busy slots only for today (hour blocks)
      function computeBusySlotsToday() {
        const today = getTodayISO();
        const todayTickets = tickets.filter((t) => t.date === today);
        const groups = new Map();
        todayTickets.forEach((t) => {
          const hour = t.time.slice(0, 2);
          const key = `${hour}:00 - ${hour}:59`;
          const prev = groups.get(key) || { count: 0, amount: 0 };
          prev.count += 1;
          prev.amount += t.amount;
          groups.set(key, prev);
        });
        const entries = Array.from(groups.entries()).sort(
          (a, b) => parseInt(b[0], 10) - parseInt(a[0], 10)
        );
        return entries;
      }

      function renderBusySlots() {
        const container = document.getElementById("busySlots");
        container.innerHTML = "";
        const entries = computeBusySlotsToday();
        if (entries.length === 0) {
          container.innerHTML =
            '<div class="ceud-item"><div><div class="ceud-title">No tickets for today yet</div><div class="ceud-meta">Add some entries using CEUD Quick Entry.</div></div></div>';
          return;
        }
        entries.forEach(([slot, { count, amount }]) => {
          const div = document.createElement("div");
          div.className = "ceud-item";
          div.innerHTML = `
            <div>
              <div class="ceud-title">${slot}</div>
              <div class="ceud-meta">${count} ticket(s) • ₹${amount}</div>
            </div>
            <span class="ceud-badge">${
              count >= 4 ? "Very Busy" : count >= 2 ? "Busy" : "Normal"
            }</span>
          `;
          container.appendChild(div);
        });
      }

      // Chart
      let chartInstance = null;

      function renderChart() {
        const period = document.getElementById("periodSelect").value;
        const categoryFilter = document.getElementById("serviceFilter").value;
        const { labels, amounts, counts, peakSlot } = groupData(
          period,
          categoryFilter
        );

        const ctx = document.getElementById("salesChart").getContext("2d");
        if (chartInstance) {
          chartInstance.destroy();
        }

        chartInstance = new Chart(ctx, {
          type: "line",
          data: {
            labels: labels.map((lb) =>
              period === "today" ? lb : formatDateDisplay(lb)
            ),
            datasets: [
              {
                label: "Sales Amount (₹)",
                data: amounts,
                borderColor: "#4f46e5",
                backgroundColor: "rgba(79, 70, 229, 0.15)",
                borderWidth: 2,
                tension: 0.35,
                fill: true,
                pointRadius: 3,
                pointHoverRadius: 4,
              },
              {
                label: "Ticket Count",
                data: counts,
                borderColor: "#22c55e",
                backgroundColor: "rgba(34, 197, 94, 0.15)",
                borderWidth: 1.6,
                borderDash: [4, 3],
                tension: 0.35,
                yAxisID: "y1",
                pointRadius: 2,
                pointHoverRadius: 4,
              },
            ],
          },
          options: {
            responsive: true,
            maintainAspectRatio: false,
            interaction: {
              mode: "index",
              intersect: false,
            },
            scales: {
              x: {
                ticks: {
                  color: "#9ca3af",
                  autoSkip: true,
                  maxTicksLimit: 8,
                },
                grid: {
                  color: "rgba(31, 41, 55, 0.5)",
                },
              },
              y: {
                position: "left",
                ticks: {
                  color: "#9ca3af",
                  callback: (v) => "₹" + v,
                },
                grid: {
                  color: "rgba(31, 41, 55, 0.4)",
                },
              },
              y1: {
                position: "right",
                ticks: {
                  color: "#6ee7b7",
                },
                grid: {
                  drawOnChartArea: false,
                },
              },
            },
            plugins: {
              legend: {
                display: false,
              },
              tooltip: {
                backgroundColor: "rgba(15, 23, 42, 0.96)",
                borderColor: "rgba(55, 65, 81, 0.9)",
                borderWidth: 1,
                titleColor: "#e5e7eb",
                bodyColor: "#d1d5db",
                callbacks: {
                  label: function (ctx) {
                    if (ctx.datasetIndex === 0) {
                      return " Sales: ₹" + ctx.parsed.y;
                    }
                    if (ctx.datasetIndex === 1) {
                      return " Tickets: " + ctx.parsed.y;
                    }
                  },
                },
              },
            },
          },
        });

        // Summary numbers
        const totalSales = amounts.reduce((sum, v) => sum + v, 0);
        document.getElementById(
          "totalSales"
        ).textContent = `₹${totalSales.toLocaleString("en-IN")}`;
        document.getElementById("peakTime").textContent =
          peakSlot || "No data";
        document.getElementById("salesTrend").textContent =
          labels.length > 1 ? "+12% vs last period (sample)" : "+0%";

        // Also update hero highlight and reports from same data
        updateHeroSummary();
        renderBusySlots();
        renderReportSummary();
      }

      function autoFillAmount() {
        const serviceSelect = document.getElementById("ticketService");
        const qtyInput = document.getElementById("ticketQty");
        const amountInput = document.getElementById("ticketAmount");

        const serviceName = serviceSelect.value;
        const service = findServiceByName(serviceName);
        const qty = Number(qtyInput.value || 0);

        if (!service || !service.autoPrice || !qty || qty <= 0) {
          // For manual or invalid, don't override typed amount
          return;
        }

        const calc = service.price * qty;
        amountInput.value = calc;
      }

      let editingTicketId = null;

      function renderTicketsTable() {
        const tbody = document.getElementById("ticketsTableBody");
        const summaryNote = document.getElementById("ticketsSummaryNote");
        const filterInput = document.getElementById("ticketsFilterDate");
        if (!tbody || !summaryNote) return;

        const filterDate = filterInput && filterInput.value ? filterInput.value : null;

        tbody.innerHTML = "";
        let filtered = tickets;
        if (filterDate) {
          filtered = tickets.filter((t) => t.dateISO === filterDate || t.date === filterDate);
        }

        if (filtered.length === 0) {
          const tr = document.createElement("tr");
          const td = document.createElement("td");
          td.colSpan = 6;
          td.textContent = "No tickets found for selected filter.";
          tr.appendChild(td);
          tbody.appendChild(tr);
          summaryNote.textContent =
            "No tickets to show. Use the Create form to add new entries.";
          return;
        }

        let totalAmount = 0;
        filtered.forEach((t) => {
          const tr = document.createElement("tr");
          const qty = t.quantity != null ? t.quantity : "";
          const amount = t.totalAmount != null ? t.totalAmount : t.amount || 0;
          totalAmount += amount;

          tr.innerHTML = `
            <td>${t.dateISO || t.date}</td>
            <td>${t.time}</td>
            <td>${t.serviceName || t.service}</td>
            <td>${qty}</td>
            <td>₹${amount}</td>
            <td>
              <div class="tickets-table-actions">
                <button type="button" data-action="edit" data-id="${t.id}">Edit</button>
                <button type="button" class="delete" data-action="delete" data-id="${t.id}">Delete</button>
              </div>
            </td>
          `;
          tbody.appendChild(tr);
        });

        summaryNote.textContent = `Showing ${filtered.length} ticket(s). Total amount: ₹${totalAmount.toLocaleString(
          "en-IN"
        )}.`;
      }

      function startEditTicket(id) {
        const ticket = tickets.find((t) => t.id === id);
        if (!ticket) return;
        editingTicketId = id;

        const dateInput = document.getElementById("ticketDate");
        const timeInput = document.getElementById("ticketTime");
        const serviceInput = document.getElementById("ticketService");
        const qtyInput = document.getElementById("ticketQty");
        const amountInput = document.getElementById("ticketAmount");
        const addBtn = document.getElementById("addTicketBtn");

        if (dateInput) dateInput.value = ticket.dateISO || ticket.date;
        if (timeInput) timeInput.value = ticket.time;
        if (serviceInput) serviceInput.value = ticket.serviceName || ticket.service;
        if (qtyInput) qtyInput.value =
          ticket.quantity != null ? ticket.quantity : "";
        if (amountInput)
          amountInput.value =
            ticket.totalAmount != null ? ticket.totalAmount : ticket.amount || 0;
        if (addBtn) addBtn.textContent = "Save changes";

        scrollToSection("dashboard");
      }

      function deleteTicket(id) {
        if (!confirm("Delete this ticket? This action cannot be undone.")) return;
        tickets = tickets.filter((t) => t.id !== id);
        renderChart();
        renderBusySlots();
        renderReportSummary();
        updateHeroSummary();
        renderTicketsTable();
      }

      function addTicketFromForm() {
        const dateInput = document.getElementById("ticketDate");
        const timeInput = document.getElementById("ticketTime");
        const serviceInput = document.getElementById("ticketService");
        const qtyInput = document.getElementById("ticketQty");
        const amountInput = document.getElementById("ticketAmount");
        const message = document.getElementById("ticketMessage");

        const date = dateInput.value || getTodayISO();
        const time =
          timeInput.value ||
          new Date().toTimeString().slice(0, 5); /* HH:MM */
        const service = serviceInput.value;
        const qty = Number(qtyInput.value || 0);
        const amount = Number(amountInput.value || 0);

        const catalogItem = findServiceByName(service);
        const category = catalogItem ? catalogItem.category : "Others";
        const unitPrice = catalogItem ? catalogItem.price : 0;
        const quantity = qty || 1;

        if (!service) {
          alert("Please select a service.");
          return;
        }

        if (!amount || amount <= 0) {
          alert("Please enter a valid amount (₹).");
          return;
        }

        const totalAmount = amount;

        if (editingTicketId) {
          const existing = tickets.find((t) => t.id === editingTicketId);
          if (existing) {
            existing.dateISO = date;
            existing.date = date;
            existing.time = time;
            existing.serviceName = service;
            existing.service = service;
            existing.category = category;
            existing.unitPrice = unitPrice;
            existing.quantity = quantity;
            existing.totalAmount = totalAmount;
            existing.amount = totalAmount;
          }
        } else {
          const id =
            "T" +
            Date.now().toString(36) +
            Math.random().toString(36).slice(2, 6);
          tickets.push({
            id,
            dateISO: date,
            date,
            time,
            serviceName: service,
            service,
            category,
            unitPrice,
            quantity,
            totalAmount,
            amount: totalAmount,
          });
        }
        amountInput.value = "";
        qtyInput.value = "";
        editingTicketId = null;
        const addBtn = document.getElementById("addTicketBtn");
        if (addBtn) addBtn.textContent = "Add";
        message.textContent = "Ticket saved successfully to CEUD dashboard.";

        renderChart();
        renderBusySlots();
        renderTicketsTable();
      }

      function downloadChartImage() {
        if (!chartInstance) return;
        const link = document.createElement("a");
        link.href = chartInstance.toBase64Image("image/png", 1);
        link.download = "digital-seva-monthly-sales.png";
        link.click();
      }

      function updateHeroSummary() {
        const today = getTodayISO();
        const todayTickets = tickets.filter((t) => t.date === today);
        const todaySales = todayTickets.reduce(
          (sum, t) => sum + (t.amount || 0),
          0
        );
        document.getElementById(
          "heroTodaySales"
        ).textContent = `₹${todaySales.toLocaleString("en-IN")}`;

        const busyEntries = computeBusySlotsToday();
        document.getElementById("heroPeakSlot").textContent =
          busyEntries.length > 0 ? busyEntries[0][0] : "–";
      }

      function renderReportSummary() {
        const list = document.getElementById("reportSummaryList");
        if (!list) return;
        const last7 = tickets.filter((t) => withinDays(t.date, 7));
        if (last7.length === 0) {
          list.innerHTML =
            "<li>No data yet. Add tickets from the CEUD Dashboard form.</li>";
          return;
        }
        const total = last7.reduce((sum, t) => sum + t.amount, 0);
        const byCategory = {};
        last7.forEach((t) => {
          const cat = t.category || "Others";
          byCategory[cat] = (byCategory[cat] || 0) + t.amount;
        });
        const busiestDayMap = new Map();
        last7.forEach((t) => {
          const prev = busiestDayMap.get(t.date) || { count: 0, amount: 0 };
          prev.count += 1;
          prev.amount += t.amount;
          busiestDayMap.set(t.date, prev);
        });
        let busiestDate = null;
        let busiestCount = 0;
        busiestDayMap.forEach((val, key) => {
          if (val.count > busiestCount) {
            busiestCount = val.count;
            busiestDate = key;
          }
        });

        list.innerHTML = "";
        const totalLi = document.createElement("li");
        totalLi.textContent = `Total sales in last 7 days: ₹${total.toLocaleString(
          "en-IN"
        )}`;
        list.appendChild(totalLi);

        Object.keys(byCategory).forEach((cat) => {
          const li = document.createElement("li");
          li.textContent = `${cat}: ₹${byCategory[cat].toLocaleString(
            "en-IN"
          )}`;
          list.appendChild(li);
        });

        if (busiestDate) {
          const li = document.createElement("li");
          li.textContent = `Busiest day: ${formatDateDisplay(
            busiestDate
          )} (${busiestCount} ticket(s))`;
          list.appendChild(li);
        }
      }

      function scrollToSection(id) {
        const el = document.getElementById(id);
        if (!el) return;
        const topOffset = 72; // approximate header height
        const rect = el.getBoundingClientRect();
        const offsetTop = rect.top + window.scrollY - topOffset;
        window.scrollTo({ top: offsetTop, behavior: "smooth" });
      }

      function setupNavButtons() {
        const buttons = document.querySelectorAll(".menu button[data-target]");
        buttons.forEach((btn) => {
          btn.addEventListener("click", () => {
            const target = btn.getAttribute("data-target");
            if (target) scrollToSection(target);
            buttons.forEach((b) => b.classList.remove("active"));
            btn.classList.add("active");
          });
        });
      }

      // --- Export / Import helpers ------------------------------------------
      function downloadJsonFile(filename, data) {
        const blob = new Blob([JSON.stringify(data, null, 2)], {
          type: "application/json",
        });
        const url = URL.createObjectURL(blob);
        const a = document.createElement("a");
        a.href = url;
        a.download = filename;
        a.click();
        URL.revokeObjectURL(url);
      }

      function exportSalesData() {
        downloadJsonFile("sales-data.json", tickets);
      }

      function exportServicesData() {
        downloadJsonFile("services-master.json", SERVICES_CATALOG);
      }

      function importSalesDataFromFile(file) {
        if (!file) return;
        const reader = new FileReader();
        reader.onload = (e) => {
          try {
            const parsed = JSON.parse(e.target.result);
            if (!Array.isArray(parsed)) {
              alert("Invalid sales JSON format. Expected an array.");
              return;
            }
            tickets = parsed.map((t, index) => {
              // Normalise keys so charts & table work
              const id =
                t.id ||
                "T" +
                  (index + 1) +
                  "-" +
                  Math.random().toString(36).slice(2, 6);
              const dateISO = t.dateISO || t.date || getTodayISO();
              const time = t.time || "00:00";
              const serviceName = t.serviceName || t.service || "Service";
              const category = t.category || "Others";
              const quantity =
                t.quantity != null
                  ? t.quantity
                  : t.qty != null
                  ? t.qty
                  : 1;
              const totalAmount =
                t.totalAmount != null ? t.totalAmount : t.amount || 0;
              const unitPrice =
                t.unitPrice != null && quantity
                  ? t.unitPrice
                  : quantity
                  ? totalAmount / quantity
                  : 0;
              return {
                id,
                dateISO,
                date: dateISO,
                time,
                serviceName,
                service: serviceName,
                category,
                unitPrice,
                quantity,
                totalAmount,
                amount: totalAmount,
              };
            });

            renderChart();
            renderBusySlots();
            updateHeroSummary();
            renderReportSummary();
            renderTicketsTable();
            alert("Sales data imported successfully.");
          } catch (err) {
            console.error(err);
            alert("Could not read sales JSON file.");
          }
        };
        reader.readAsText(file);
      }

      function importServicesDataFromFile(file) {
        if (!file) return;
        const reader = new FileReader();
        reader.onload = (e) => {
          try {
            const parsed = JSON.parse(e.target.result);
            if (!Array.isArray(parsed)) {
              alert("Invalid services JSON format. Expected an array.");
              return;
            }
            // Basic validation and normalisation
            const cleaned = parsed
              .filter((s) => s && s.name)
              .map((s) => ({
                name: s.name,
                category: s.category || "Others",
                unit: s.unit || "work",
                price: typeof s.price === "number" ? s.price : 0,
                autoPrice: !!s.autoPrice,
              }));
            if (cleaned.length === 0) {
              alert("No valid services found in JSON.");
              return;
            }
            SERVICES_CATALOG.length = 0;
            cleaned.forEach((s) => SERVICES_CATALOG.push(s));
            populateServiceDropdown();
            renderServiceMasterList();
            alert("Services master imported successfully.");
          } catch (err) {
            console.error(err);
            alert("Could not read services JSON file.");
          }
        };
        reader.readAsText(file);
      }

      // Initial setup
      window.addEventListener("DOMContentLoaded", () => {
        document.getElementById("footerYear").textContent =
          new Date().getFullYear();

        populateServiceDropdown();
        renderServiceMasterList();

        renderChart();
        renderBusySlots();
        updateHeroSummary();
        renderReportSummary();
        renderTicketsTable();

        document
          .getElementById("periodSelect")
          .addEventListener("change", renderChart);
        document
          .getElementById("serviceFilter")
          .addEventListener("change", renderChart);
        document
          .getElementById("addTicketBtn")
          .addEventListener("click", addTicketFromForm);
        document
          .getElementById("downloadBtn")
          .addEventListener("click", downloadChartImage);

        document
          .getElementById("ticketService")
          .addEventListener("change", autoFillAmount);
        document
          .getElementById("ticketQty")
          .addEventListener("input", autoFillAmount);

        const ticketsFilterDate = document.getElementById("ticketsFilterDate");
        if (ticketsFilterDate) {
          ticketsFilterDate.addEventListener("change", renderTicketsTable);
        }

        const ticketsTableBody = document.getElementById("ticketsTableBody");
        if (ticketsTableBody) {
          ticketsTableBody.addEventListener("click", (event) => {
            const target = event.target;
            if (!target || !target.getAttribute) return;
            const action = target.getAttribute("data-action");
            const id = target.getAttribute("data-id");
            if (!action || !id) return;
            if (action === "edit") {
              startEditTicket(id);
            } else if (action === "delete") {
              deleteTicket(id);
            }
          });
        }

        const saveServiceBtn = document.getElementById("saveServiceBtn");
        if (saveServiceBtn) {
          saveServiceBtn.addEventListener("click", upsertServiceFromForm);
        }

        const exportSalesBtn = document.getElementById("exportSalesBtn");
        if (exportSalesBtn) {
          exportSalesBtn.addEventListener("click", exportSalesData);
        }
        const exportServicesBtn = document.getElementById("exportServicesBtn");
        if (exportServicesBtn) {
          exportServicesBtn.addEventListener("click", exportServicesData);
        }
        const importSalesInput = document.getElementById("importSalesInput");
        if (importSalesInput) {
          importSalesInput.addEventListener("change", (e) => {
            const file = e.target.files && e.target.files[0];
            importSalesDataFromFile(file);
            e.target.value = "";
          });
        }
        const importServicesInput =
          document.getElementById("importServicesInput");
        if (importServicesInput) {
          importServicesInput.addEventListener("change", (e) => {
            const file = e.target.files && e.target.files[0];
            importServicesDataFromFile(file);
            e.target.value = "";
          });
        }

        setupNavButtons();
      });
    </script>
  </body>
  </html>
