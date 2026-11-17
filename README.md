# Rudelis

**AI-Powered Autonomous Trading Platform**

Rudelis is an AI-powered trading platform designed to automate intraday trading through intelligent AI agents. The platform aims to analyze market conditions, identify trading opportunities, make informed trading decisions, and execute trades automatically.

## 🚀 Features

- **AI Trading Agents** – Autonomous agents that analyze market data and make trading decisions.
- **Automated Trade Execution** – Execute trades based on predefined strategies and agent decisions.
- **Real-Time Market Data** – Monitor live market movements and price changes.
- **Strategy Management** – Configure and manage different trading strategies.
- **Portfolio Monitoring** – Track positions, balances, and trading performance.
- **Real-Time Updates** – Receive live trade notifications and execution updates.
- **Authentication & Security** – Secure user accounts and session management.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Frontend |
| Node.js | Backend |
| Better Auth | Authentication |
| PostgreSQL | Database |
| Redis | Caching and real-time communication |
| WebSockets | Real-time updates |
| AI Agents | Trading analysis and decision-making |

## 📁 Project Structure

```text
rudelis/
├── frontend/          # Next.js application
│   ├── app/
│   ├── components/
│   └── lib/
│
├── backend/           # Node.js backend
│   └── src/
│       ├── api/
│       ├── auth/
│       ├── websocket/
│       ├── agents/
│       ├── trading/
│       └── database/
│
├── README.md
└── .gitignore
```

## ⚙️ Getting Started

### Prerequisites

- Node.js
- PostgreSQL
- Redis (if enabled)
- npm or pnpm

### Installation

Clone the repository:

```bash
git clone <repository-url>
cd rudelis
```

Install frontend dependencies:

```bash
cd frontend
npm install
```

Install backend dependencies:

```bash
cd ../backend
npm install
```

### Environment Variables

Configure your environment variables in the frontend and backend `.env` files.

Example backend configuration:

```env
PORT=4000
DATABASE_URL=
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=
REDIS_URL=
```

Example frontend configuration:

```env
NEXT_PUBLIC_API_URL=http://localhost:4000
```

### Running the Project

Start the backend:

```bash
cd backend
npm run dev
```

Start the frontend in another terminal:

```bash
cd frontend
npm run dev
```

Frontend: `http://localhost:3000`

Backend: `http://localhost:4000`

## 🧠 AI Trading Architecture

The platform is designed around autonomous trading agents that can:

1. Collect and analyze market data.
2. Identify potential trading opportunities.
3. Evaluate market conditions and risk.
4. Generate trading signals.
5. Execute approved trading strategies.
6. Monitor open positions.
7. Track performance and trading outcomes.

## 🔐 Security

- Secure authentication and session management.
- Protected API endpoints.
- Encrypted communication over HTTPS.
- Secure handling of API credentials.
- Risk management and trade execution controls.

## ⚠️ Disclaimer

Rudelis is an automated trading software project. Financial markets involve substantial risk, and automated trading can result in significant losses.

AI-generated trading decisions are not guaranteed to be profitable. Always implement appropriate risk controls and thoroughly test strategies using historical data and paper trading before enabling live execution.

## 📌 Project Status

**Under Development**

More features and documentation will be added as the platform evolves.

## 📄 License

To be decided.
