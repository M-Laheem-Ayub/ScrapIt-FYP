# ScrapIt — Digital Scrap Marketplace

BS Software Engineering Final Year Project (University of Central Punjab — Group F26SE066).

ScrapIt is a three-sided mobile marketplace connecting households and offices (Sellers), freelance transporters (Riders), and local scrap yards (Dealers). The platform includes AI-based scrap photo verification, on-site dual-weight confirmation, live GPS tracking, and escrow payment settlement.

## Project Structure

- `mobile/` — React Native mobile application (Seller, Dealer, and Rider interfaces)
- `backend/` — Node.js and Express REST API, authentication, order state engine, and escrow ledger (MongoDB)
- `ai-service/` — Python and TensorFlow service for scrap image classification and CNIC OCR

## Team Members

- **Laheem Ayub** (L1F23BSSE0176) — Scrum Master, Mobile Frontend, UI/UX & Maps
- **Muhammad Saad** (L1F23BSSE0177) — Backend APIs, Security/RBAC & Escrow Engine
- **Muhammad Owais** (L1F23BSSE0145) — AI Computer Vision, OCR & Cloud Deployment

## Git Workflow

- `main` holds stable, reviewed code.
- All work is done on feature branches (`feature/US-XX-short-name`) linked to GitHub Issues and merged into `main` via Pull Requests after peer review.