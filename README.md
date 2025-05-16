# Order Management Dashboard

This is a full-stack Order Management Dashboard built as part of a job assessment. It displays a real-time order board where users can track, view, and manage customer orders efficiently.

---

## 🛠 Tech Stack

### Backend:
- **Node.js + Express** – for building a scalable RESTful API
- **TypeScript** – for safer, more maintainable backend logic
- **PostgreSQL** – as the relational database
- **Prisma ORM** – to simplify DB access with type-safety and schema modeling

### Frontend:
- **React** – for building a dynamic and component-based UI
- **Material UI** – for a consistent and clean visual design
- **@dnd-kit** – for drag-and-drop interaction (React Beautiful DnD wasn't compatible with my React version)

### Infrastructure:
- **Docker** – for creating a reproducible development and deployment environment across OS platforms

---

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/order-dashboard.git
   cd order-dashboard
2.**Run with Docker:

   ```bash
    docker-compose up --build
