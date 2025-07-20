# SnapSell - Image Selling Platform

A modern image selling application built with Next.js, featuring secure authentication, seamless image uploads, and integrated payment processing.

## Features

- **User Authentication**: Secure login and registration with NextAuth
- **Image Management**: Upload and manage images with ImageKit integration
- **Payment Processing**: Secure payments powered by Razorpay
- **Product Management**: Full CRUD operations for products
- **Admin Dashboard**: Manage products and orders
- **User Dashboard**: Track orders and manage personal products

## Technologies

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS
- **Authentication**: NextAuth.js
- **Image Storage**: ImageKit
- **Payments**: Razorpay
- **Database**: MongoDB (with Mongoose)

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- MongoDB database
- ImageKit account
- Razorpay account

### Installation

1. Clone the repository
   ```bash
   git clone <repository-url>
   cd SnapSell
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables
   Create a `.env.local` file in the root directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   NEXTAUTH_SECRET=your_nextauth_secret
   NEXTAUTH_URL=http://localhost:3000
   IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
   IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
   IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
   RAZORPAY_KEY_ID=your_razorpay_key_id
   RAZORPAY_KEY_SECRET=your_razorpay_key_secret
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to [http://localhost:3000](http://localhost:3000)

## Usage

1. **Register/Login**: Create an account or sign in to access the platform
2. **Upload Images**: Use the admin panel to upload and manage your images
3. **Set Prices**: Configure pricing for your digital products
4. **Process Payments**: Customers can purchase images through secure Razorpay integration
5. **Track Orders**: Monitor sales and manage customer orders

## Project Structure

```
SnapSell/
├── app/                 # Next.js app directory
│   ├── admin/          # Admin dashboard
│   ├── api/            # API routes
│   ├── components/     # React components
│   └── ...
├── lib/                # Utility functions and configurations
├── models/             # Database models
└── public/             # Static assets
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
