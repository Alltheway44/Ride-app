# Ride App - Kenya Transport Booking Platform

A simplified Uber-like ride-booking platform for Kenya.

## Features

- **User Authentication**: Register and login for riders and drivers
- **Ride Booking**: Users can book rides from any location in Kenya
- **Real-time Tracking**: Live GPS tracking of rides
- **Driver Management**: Drivers can accept/reject ride requests
- **Payment Integration**: Basic payment processing
- **Rating System**: Users and drivers can rate each other
- **Ride History**: View past rides and transactions

## Tech Stack

### Frontend
- React.js with TypeScript
- Tailwind CSS for styling
- Google Maps API for location/mapping
- Socket.io for real-time updates

### Backend
- Node.js with Express.js
- MongoDB for database
- JWT for authentication
- Socket.io for real-time communication

### Infrastructure
- dotenv for environment variables
- bcryptjs for password hashing
- Axios for API calls

## Project Structure

```
ride-app/
├── frontend/              # React application
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/               # Node.js server
│   ├── src/
│   │   ├── models/       # MongoDB schemas
│   │   ├── routes/       # API endpoints
│   │   ├── controllers/  # Business logic
│   │   ├── middleware/   # Auth & validation
│   │   └── utils/        # Helper functions
│   ├── config/           # Configuration files
│   └── package.json
└── README.md
```

## Getting Started

See individual README files in `frontend/` and `backend/` directories for setup instructions.

## Environment Variables

Both frontend and backend require `.env` files. See `.env.example` files in each directory.

## Contributing

1. Create a feature branch from `dev`
2. Make your changes
3. Submit a pull request

## License

MIT
