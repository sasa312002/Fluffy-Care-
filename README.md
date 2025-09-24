Fluffy Care
Fluffy Care is a full‑stack platform that connects pet adopters, pet owners, and veterinary professionals. It streamlines the end‑to‑end adoption journey (from listing to home visits and forms), manages lost & found reports, enables appointment scheduling with professionals, and supports a small pet‑store workflow with products, orders, and reviews. A dedicated doctor/professional interface provides tools for availability management, appointments, and medical records/reporting.
Key features
Pet adoption: Manage adoptable pets, adoption forms, home visits, and adoption status.
Lost & found: Create and track lost/found pet reports to help reunite pets with owners.
Appointments: Book, confirm, and manage veterinary/professional appointments (with notifications).
Professional portal: Separate doctor interface for availability, appointments, pet profiles, and medical records.
Events & notifications: Community events with email/notification support.
Pet store flow: Products, cart, orders, and store reviews.
Media handling: Image upload and storage via Cloudinary.
Tech stack
Backend: Node.js, Express, MongoDB/Mongoose; modular controllers, models, and routes.
Frontend (Doctor interface): React (Vite), modern SPA for professionals.
Integrations: Cloudinary for media; email utilities for user communication.
Monorepo structure
backend/: Express API with controllers, models, routes, middleware, and scripts.
docterInterface/: Vite + React app for the professional/doctor dashboard.
uploads/: Local media assets (during development).
Root package.json: Workspace-level tooling.
