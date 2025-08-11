# FusionForge PCs - Custom PC Building Platform

A professional, full-stack PC building platform that enables customers to browse pre-configured builds, customize specifications, and complete purchases with integrated payment processing.

## 🚀 Features

### E-commerce Functionality
- **Product Catalog**: Organized PC builds by category and price range
- **Shopping Cart**: Persistent cart with quantity management
- **Checkout System**: Multi-step checkout with address management
- **Payment Processing**: Razorpay integration with multiple payment options
- **Order Management**: Complete order tracking and status updates

### User Experience
- **Authentication**: Firebase Auth with email/password and Google OAuth
- **User Dashboard**: Profile management, order history, saved builds
- **Build Configurator**: Interactive PC customization tool
- **Mobile Responsive**: Optimized for all devices

### Admin Panel
- **Order Management**: Real-time order processing and customer service
- **Inventory Control**: Stock tracking with low stock alerts
- **Analytics Dashboard**: Revenue tracking and performance metrics
- **Content Management**: PC build catalog management

### Technical Excellence
- **Modern Stack**: React 18, TypeScript, Express.js, Firebase
- **Database**: Firebase Realtime Database for real-time data sync
- **Security**: Input validation, authentication, payment security
- **Performance**: Optimized builds, caching, lazy loading
- **Email System**: Automated notifications via Brevo SMTP

## 🛠️ Tech Stack

### Frontend
- **React 18** with TypeScript
- **Wouter** for routing
- **TanStack Query** for data management
- **Tailwind CSS** with shadcn/ui components
- **Framer Motion** for animations

### Backend
- **Express.js** with TypeScript
- **Firebase Realtime Database**
- **Razorpay** payment gateway
- **NodeMailer** with Brevo SMTP
- **bcrypt** for password security

### Development
- **Vite** for fast development and builds
- **ESLint** for code quality
- **TypeScript** for type safety
- **Hot reload** development server

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fusionforge-pcs.git
   cd fusionforge-pcs
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file with:
   ```bash
   # Firebase Configuration
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_firebase_app_id
   VITE_FIREBASE_MEASUREMENT_ID=your_firebase_measurement_id

   # Payment Gateway
   RAZORPAY_KEY_ID=your_razorpay_key_id
   RAZORPAY_KEY_SECRET=your_razorpay_key_secret

   # Admin Configuration
   ADMIN_EMAIL=your_admin_email
   ADMIN_USERNAME=admin
   ADMIN_PASSWORD_HASH=your_bcrypt_hash

   # Email Service
   BREVO_SMTP_HOST=smtp-relay.brevo.com
   BREVO_SMTP_PORT=587
   BREVO_SMTP_USER=your_brevo_user
   BREVO_SMTP_PASS=your_brevo_password
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5000`

## 🚀 Deployment

### Render Deployment
1. **Push to GitHub**
2. **Connect to Render** at https://render.com
3. **Create Web Service** from your repository
4. **Configure build settings**:
   - Build Command: `npm install && npm run build`
   - Start Command: `npm start`
5. **Add environment variables** from your `.env` file
6. **Deploy!**

Detailed deployment instructions are in `RENDER_DEPLOYMENT_GUIDE.md`.

## 🏗️ Project Structure

```
fusionforge-pcs/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── contexts/       # React contexts (Auth, etc.)
│   │   ├── lib/            # Utilities and configurations
│   │   └── index.css       # Global styles
│   └── index.html
├── server/                 # Backend Express application
│   ├── middleware/         # Custom middleware
│   ├── services/           # Email, payment services
│   ├── payment/            # Payment processing
│   ├── webhooks/           # Payment webhooks
│   └── routes.ts           # API routes
├── shared/                 # Shared types and schemas
│   └── schema.ts           # Database schemas
└── package.json
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run check` - TypeScript type checking

## 🎯 Key Features

### Customer Experience
- Browse PC builds by category and budget
- Interactive build configurator
- Secure user authentication
- Shopping cart and checkout
- Multiple payment options
- Order tracking and history

### Business Management
- Admin dashboard with analytics
- Order processing and management
- Inventory tracking and alerts
- Customer inquiry system
- Automated email notifications

## 🔒 Security

- Input validation with Zod schemas
- Password hashing with bcrypt
- Secure payment processing
- Protected admin routes
- Environment variable management

## 📱 Mobile Support

Fully responsive design optimized for:
- Mobile phones
- Tablets
- Desktop computers
- Touch interfaces

## 🎨 UI/UX

- Modern, clean design
- Consistent brand identity
- Smooth animations and transitions
- Accessible components
- Professional color scheme

## 📧 Email System

Automated email notifications for:
- Order confirmations
- Payment receipts
- Inquiry responses
- Status updates

## 💳 Payment Integration

Secure payment processing with:
- Razorpay payment gateway
- Multiple payment methods (UPI, cards, net banking)
- Payment verification
- Transaction logging

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support or questions:
- Email: fusionforgepc@gmail.com
- Check the documentation files
- Review the deployment guides

## 🔄 Version History

See `replit.md` for detailed changelog and recent updates.

---

**FusionForge PCs** - Building the perfect PC for every need and budget."# Fusion_Forge_PCs" 
"# Fusion_Forge_PCs" 
