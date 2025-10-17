# 🇮🇳 Bharat Warehouse Optimiser

A comprehensive Micro-Fulfillment Unit (MFU) Simulator for warehouse layout optimization, robot pathfinding, and performance analytics. Built to streamline operations in retail, logistics, and emergency scenarios.

---

## 🎯 Project Overview

The Bharat Warehouse Optimiser is a full-stack web application that simulates warehouse operations to:

- Optimize layout designs
- Simulate robot movement and pathfinding
- Analyze efficiency, cost, and environmental impact

Adaptable for:
- Disaster relief
- Festival rushes
- Emergency deployments

---

## 🏗️ Architecture

### Frontend (React + Vite)
- **Framework**: React 18 with hooks and context
- **UI**: Radix UI + Tailwind CSS
- **State**: TanStack Query + React hooks
- **Routing**: Wouter
- **Charts**: Recharts

### Backend (Node.js + Express)
- **Server**: Express.js with CORS and JSON middleware
- **Database**: PostgreSQL + Drizzle ORM (in-memory for dev)
- **API**: RESTful endpoints for layouts, simulations, and orders
- **Storage**: Modular (DB + in-memory)

---

## 🤖 Core Algorithms

| Algorithm        | Purpose                                |
|------------------|----------------------------------------|
| A* Pathfinding   | Optimal robot movement with obstacles  |
| TSP Solver       | Shelf visit order optimization         |
| Seasonal Logic   | Demand-based routing strategies        |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation


# Clone the repository
git clone https://github.com/your-username/bharat-warehouse-optimiser.git
cd bharat-warehouse-optimiser

# Install dependencies
npm install

# Start development servers
npm run dev
