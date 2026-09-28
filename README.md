# Online Farmers Market Platform

A web-based system for buying and selling agricultural products directly between farmers and consumers.

## Features

- **User Authentication**: Secure login for farmers and buyers
- **Product Listing**: Farmers can list their agricultural products with images and descriptions
- **Shopping Cart**: Buyers can add products to cart and checkout
- **Payment Integration**: Secure payment processing
- **Order Management**: Track orders and delivery status
- **Rating & Reviews**: Community feedback system
- **Real-time Notifications**: Updates on orders and new products
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Tech Stack

### Frontend
- React.js / Vue.js
- Tailwind CSS or Bootstrap
- Redux (state management)
- Axios (HTTP client)

### Backend
- Node.js / Express.js or Python / Django
- MongoDB / PostgreSQL (Database)
- JWT (Authentication)
- Stripe/PayPal (Payment Gateway)

### Tools & Services
- Git & GitHub
- Docker (Containerization)
- Postman (API Testing)
- Figma (UI/UX Design)

## Project Structure

```
online-farmers-market/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   │   └── App.js
│   └── package.json
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── server.js
├── docs/
│   ├── API_DOCUMENTATION.md
│   └── SETUP_GUIDE.md
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB or PostgreSQL
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/abhiajy/online-farmers-market.git
cd online-farmers-market
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

4. Set up environment variables:
```bash
# Backend .env
DATABASE_URL=your_database_url
JWT_SECRET=your_secret_key
PAYMENT_API_KEY=your_payment_key
```

5. Start the application:
```bash
# Terminal 1 - Backend
cd backend
npm start

# Terminal 2 - Frontend
cd frontend
npm start
```

## API Endpoints

### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout

### Products
- `GET /api/products` - Get all products
- `POST /api/products` - Create new product (farmers only)
- `GET /api/products/:id` - Get product details
- `PUT /api/products/:id` - Update product
- `DELETE /api/products/:id` - Delete product

### Orders
- `POST /api/orders` - Create order
- `GET /api/orders/:id` - Get order details
- `GET /api/orders` - Get user orders

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Roadmap

- [ ] Phase 1: Basic setup and authentication
- [ ] Phase 2: Product listing and search
- [ ] Phase 3: Shopping cart and checkout
- [ ] Phase 4: Payment integration
- [ ] Phase 5: Order tracking
- [ ] Phase 6: Rating and reviews system
- [ ] Phase 7: Admin dashboard
- [ ] Phase 8: Mobile app (React Native)

## License

This project is licensed under the MIT License - see LICENSE file for details.

## Contact

For questions or suggestions, please open an issue or contact the maintainer.

---
**Happy Farming! 🌾**
