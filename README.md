# EcoCycle™ | Circular Economy Logistics Platform

EcoCycle is a high-performance, full-stack waste management ecosystem designed to bridge the gap between urban households, field logistics agents (Riders), and administrative oversight. The platform leverages geo-spatial tracking, real-time data visualization, and a secure reward system to industrialize the recycling process.

## Live Demo
(Insert Demo Link Here)

---
## Local Development Setup

To run EcoCycle locally, follow the steps below:

### 1. Clone or Fork the Repository

bash
git clone https://github.com/<your-username>/<your-repo>.git

### 2. Install dependencies

bash
npm install

### 3. Start the Development Server
bash
npm run dev

After running the above command, open the local address displayed in the terminal (commonly [http://localhost:5173](http://localhost:5173)) in your browser.

### Requirements

- Node.js & npm installed
- Recommended editor: VS Code (React & Tailwind plugins suggested)
- LocalStorage is used as a mock backend for simulation

## System Architecture

EcoCycle is built on a Tri-Portal Architecture, with dedicated interfaces for three distinct user roles:

### 1. Recycler Portal (User Dashboard)
- Precision scheduling with GPS-validated coordinates
- Real-time Leaflet.js tracking with floating telemetry cards
- Eco-Wallet for transparent earnings based on material-specific rates
- Impact Ledger with complete contribution history

### 2. Field Ops Portal (Rider Dashboard)
- Tactical route mapping and deployment points
- Google Maps deep-linking for turn-by-turn navigation
- On-site verification via camera evidence and digital weight logging
- Dynamic valuation based on material type and verified weight

### 3. Command Center (Admin Dashboard)
- Logistics analytics using Recharts for material volume and growth metrics
- Cashfree Payout Simulator with realistic redirect-based settlement flow
- Real-time chain-of-custody monitoring for field operations

---

## Tech Stack

- Frontend: React 19 (ES6 Modules)
- Styling: Tailwind CSS (Custom Sage & Dark Teal branding)
- Mapping: Leaflet.js with CartoDB tiles
- Icons: Lucide-React
- Charts: Recharts
- Storage: Persistent LocalStorage-based mock backend (production-simulated data flow)

---

## Security & Design Principles

- Geo-verification for all collection requests
- Responsive UI for both mobile-first field operations and desktop administration
- Role-isolated interfaces for operational clarity and security

---

## Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Keerthi-naidu15">
        <img src="https://github.com/Keerthi-naidu15.png" width="100px;" alt="Keerthi Naidu"/>
        <br />
        <sub><b>Keerthi Naidu</b></sub>
      </a>
    </td>
        <td align="center">
      <a href="https://github.com/rishitha-1612">
        <img src="https://github.com/rishitha-1612.png" width="100px;" alt="Rishitha Rasineni"/>
        <br />
        <sub><b>Rishitha Rasineni</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/2406-Sowmya">
        <img src="https://github.com/2406-Sowmya.png" width="100px;" alt="Sowmya"/>
        <br />
        <sub><b>Sowmya PR</b></sub>
      </a>
    </td>
  </tr>
</table>

---
