# Workout App

A cross-platform mobile workout application with video content and subscription management.

## Project Structure
```
workout-app/
├── mobile/              # React Native mobile application
├── backend/             # Node.js/Express backend API
├── infrastructure/      # Infrastructure as Code (Terraform/CloudFormation)
├── docs/               # Documentation
└── scripts/            # Utility scripts
```

## Tech Stack

### Mobile
- React Native (Expo)
- TypeScript
- Redux Toolkit (State Management)
- React Navigation
- Expo AV (Video Playback)
- Stripe React Native SDK

### Backend
- Node.js
- Express/NestJS
- PostgreSQL
- Prisma ORM
- Stripe API
- AWS S3 (Video Storage)

### Infrastructure
- AWS (EC2/ECS, RDS, S3, CloudFront)
- Docker
- GitHub Actions (CI/CD)

## Features

- 🎥 Video-based workout library
- 📱 Cross-platform (iOS & Android)
- 💳 Subscription management via Stripe
- 👤 User authentication
- 📊 Analytics and tracking
- 🔄 Offline support
- 🚀 Production-ready deployment

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn
- Docker
- Expo CLI
- AWS CLI (for deployment)

### Development Setup

1. Clone the repository
```bash
git clone <repository-url>
cd workout-app
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables (see `.env.example` in each directory)

4. Start development servers
```bash
# Backend
cd backend && npm run dev

# Mobile
cd mobile && npm start
```

## Deployment

### Mobile
- iOS: TestFlight → App Store
- Android: Internal Testing → Google Play

### Backend
- Staging: Automatic deployment on `develop` branch
- Production: Automatic deployment on `main` branch

## Contributing

See [CONTRIBUTING.md](./docs/CONTRIBUTING.md) for development guidelines.

## License

MIT