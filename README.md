# Morent 🚗 Car Rental Web Application

![PRs Welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=shields)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://morent-zeta.vercel.app/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📝 Project Overview

Morent is a modern, full-featured car rental web application designed to simplify the car rental experience. Built with cutting-edge web technologies, the platform allows users to browse, search, and rent cars with ease.

### Key Features
- 🏠 Dynamic homepage with featured vehicles
- 🚗 Comprehensive car listing with advanced search and filtering
- 📋 Detailed car information and image galleries
- 💳 Integrated Stripe payment processing
- 👤 User profiles with rental history and favorites
- 🌟 Car review and rating system

## 🌐 Live Demo

- **Website**: [https://morent-zeta.vercel.app/](https://morent-zeta.vercel.app/)
- **Demo Video**: [Loom Walkthrough](https://www.loom.com/share/64be3ad8506e4540a4f61fa83008ad29)

## 🛠️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) (included with Node.js)
- [Git](https://git-scm.com/)

### Installation Steps

1. Clone the repository
```bash
git clone https://github.com/DevTaehong/Morent.git
cd Morent
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
Create a `.env` file in the project root with the following variables:
```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

# Database Configuration
DATABASE_URL=<your_mongodb_connection_string>

# Uploadthing
UPLOADTHING_SECRET=<your_uploadthing_secret>
UPLOADTHING_APP_ID=<your_uploadthing_app_id>

# Stripe Integration
STRIPE_SECRET_KEY=<your_stripe_secret_key>
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=<your_stripe_publishable_key>
```

4. Run the development server
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🚀 Deployment

### Vercel Deployment
1. Fork the repository
2. Connect your Vercel account to the GitHub repository
3. Set the environment variables in the Vercel project settings
4. Vercel will automatically deploy the main branch

### Docker Deployment
```bash
# Build Docker image
docker build -t morent .

# Run Docker container
docker run -p 3000:3000 morent
```

## 📂 Project Structure

- `app/`: Next.js app directory with routes and pages
- `components/`: Reusable React components
- `lib/`: Server actions, models, and utility functions
- `public/`: Static assets like images and icons
- `utils/`: Utility functions and helpers

## 🧰 Technologies Used

- **Frontend**: 
  - Next.js 13
  - React
  - TypeScript
  - Tailwind CSS

- **Backend**:
  - MongoDB
  - Mongoose
  - Clerk (Authentication)
  - Stripe (Payments)

- **Additional Tools**:
  - Uploadthing (File uploads)
  - React Hook Form
  - Zod (Validation)

## ✨ Feature Highlights

- User Authentication with Clerk
- Car Listing and Search
- Detailed Car Information
- Stripe Payment Integration
- Favorite Cars
- User Profile Management
- Car Rental and Review System

## 🔧 Configuration

- Tailwind CSS configuration in `tailwind.config.js`
- TypeScript configuration in `tsconfig.json`
- Environment variables managed via `.env`

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👥 Credits

- Tye Stanley
- Glen McCallum
- Alexander Mc Lachlan

## 📞 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-taehong-blue?style=flat&logo=linkedin&logoColor=b0c0c0&labelColor=363D44)](https://www.linkedin.com/in/taehong/)

---

**Happy Car Renting with Morent! 🚗✨**