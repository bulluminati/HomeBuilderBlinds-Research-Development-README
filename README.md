# # CrossRef Tech Signals Dashboard  
Part of the Internal Intelligence Suite by [@bulluminati](https://github.com/bulluminati)

This real-time dashboard is part of the **Intelligence Sector** of a larger vertically integrated business suite that supports:

- General Contracting & Construction
- Real Estate Development & Asset Management
- Subcontractor Trade Monitoring (Window Treatments, Electrical, Plumbing, HVAC, etc.)
- Automation in Smart Homes & Multifamily Projects
- Materials Innovation & Procurement Strategy

---

## Mission

The goal of this tool is to track **emerging technology**, **materials**, and **business signals** in construction and real estate—especially where automation, patents, or academic research signals the next wave of disruption.

---

## Why It Matters

This dashboard is built to answer questions like:

- _What patents are being filed around smart home energy systems, blind motors, or self-healing surfaces?_
- _Which startups are receiving funding to digitize inspections, automate drywalling, or embed sensors in flooring?_
- _Are academic labs quietly prototyping construction robotics or AI-based HVAC load prediction?_

When a topic shows up in **multiple signals (patents + papers + funding + open-source code)**, it’s a sign the market is about to shift.

---

## Business Suite Integration

This project represents the **Intelligence Sector** of a broader business suite comprised of:

| Sector        | Function                                                                 |
|---------------|--------------------------------------------------------------------------|
| **Operations**   | General contracting, subcontractor scheduling, material installation   |
| **Marketing**    | Direct mail, inbound funnels, builder/PM outreach, brand building      |
| **Data Mining**  | Public record scrapers, renovation flags, lead intelligence            |
| **Intelligence** | Technical research, patent tracking, innovation alerts                 |

Currently focused on **window treatments**, but designed to scale across all trades.

---

## Supported Trade Areas

| Trade / Sector          | Signal Examples                                                |
|--------------------------|----------------------------------------------------------------|
| Window Treatments        | Cordless tilt patents, blackout fabrics, voice-controlled shades |
| Electrical & Lighting    | Smart switches, embedded dimmers, LED cooling systems          |
| Plumbing                 | Leak detection AI, patented pipe snap fittings, tankless upgrades |
| HVAC                     | AI thermostats, low-voltage zoning, energy-efficient motors     |
| Drywall / Paint          | Self-healing compounds, spray automation arms                   |
| Roofing / Insulation     | Fire-retardant membranes, solar-shingle integration             |
| Real Estate Technology   | Auto-valuation models, smart contracts, generative layouts      |
| Warehouse Logistics      | Robotic picking, inventory automation, real-time scheduling     |

---

## Dashboard Features

- **Cross-Referenced Trend Matching**: Papers + Patents + Funding Events
- **Sector-Based Signal Scoring**: Custom weights by relevance
- **Chart.js Visualizations**: Track trends over time
- **Live External Linking**: Google Patents, arXiv, startup profiles
- **Searchable Table**: Browse by topic, inventor, signal type, match confidence
- **Responsive Tailwind UI**: Clean UX across all devices

---

## Example Use Cases

| User                        | Use Case                                                                   |
|-----------------------------|----------------------------------------------------------------------------|
| GC or Developer             | Monitor what smart home integrations are gaining market heat              |
| Product Installer / Vendor  | Prepare to offer newer blind motors, fast-fit plumbing kits, or IoT thermostats |
| Real Estate Investor        | See where PropTech is changing market comps or demand                     |
| Automation Engineer         | Watch for funding in robotics across homebuilding and renovation tech     |
| Window Treatment Fabricator | Track patent activity around cordless, motorized, or snap-fit hardware    |

---

## Tech Stack

- **Node.js** + Express for backend - seriously idk tho and that goes for |
- **EJS** templating                                                      |
- **Tailwind CSS** UI                                                     | 
- **Chart.js** for graphing                                               |
- **Pluggable data sources**: arXiv, Google Patents, Crunchbase, etc.     v-- all this
- Optional: DynamoDB and python/LLM for scraping maybe idk

---

## Installation

```bash
git clone https://github.com/bulluminati/crossref-dashboard.git
cd crossref-dashboard
npm install
npm start
