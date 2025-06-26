# Fan Meet & Greet Manager

A web/mobile-responsive application for organizing and managing artist fan meet & greet events.

## Features
- Ticketing and registration system
- VIP access and management
- Artist-fan direct messaging
- Exclusive content sharing
- Live stream and Q&A integration
- Notifications
- Merchandise sales
- Fan community forums
- Analytics dashboard

## Technology Stack
- Front-end: React, Material-UI
- Back-end: Node.js (Express)
- Database: PostgreSQL
- Real-time: Socket.IO
- Storage: AWS S3 or Cloudinary
- Authentication: JWT + OAuth
- Deployment: Docker, GitHub Actions, Vercel/AWS

## Setup Instructions
1. Clone the repo and enter directory
2. npm install
3. Set up environment variables for database, auth, storage
4. npm run dev for development
5. See Dockerfile for containerized deployment

## Deployment
App is ready for Vercel or AWS deployment. Push to `main` triggers CI/CD if set up.

## Security
All personal and financial info is securely handled. Uses OAuth and JWTs.

---
For full plan and architecture details, see project Google Doc: https://docs.google.com/document/d/1WZAtMupJUgjgUT4Q_8Y3vzHyqCBMpoq9jK-eRTvCWj4