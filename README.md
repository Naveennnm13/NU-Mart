# NU-Mart

# NU Mart: Connecting Huskies through Buying and Selling


# Project Overview
NU Mart is a secure, web-based marketplace exclusively for Northeastern University students. It facilitates buying, selling, and exchanging essential items such as textbooks, electronics, furniture, and more. The platform ensures trust, safety, and ease of use by integrating NU authentication, secure messaging, and a student-only community.

# Why NU Mart?

- Secure & Exclusive – Only NU students can access it via NU credentials & two-factor authentication.
- Advanced Search & Filters – Quickly find items based on categories, price, and condition.
- Built-in Messaging – Direct communication between buyers and sellers.
- Safe Campus Exchanges – Suggested meet-up locations to minimize transaction risks.
- Fast & User-Friendly – Optimized UX/UI for seamless browsing and transactions.

# Key Features
*Feature	Description*
- NU Authentication	Ensures only NU students can access the platform using their NU credentials and two-factor authentication (2FA).
- Secure Transactions	Implements safety features such as fraud detection, user ratings, and admin moderation.
- In-App Messaging	Direct, secure communication without relying on third-party apps.
- Advanced Filtering	Easily search by category, price range, and condition.
- Safe Meet-Up Zones	Predefined campus locations for safe item exchanges.
- Admin Dashboard	Moderation tools for managing disputes and fraudulent listings.
- Future Enhancements	AI-based price suggestions, payment integration, and blockchain-based transaction verification.

# Tech Stack
*Technology	Purpose:*

- Frontend	React.js / Next.js + Tailwind CSS for a modern UI.
- Backend	Node.js with Express.js for API handling.
- Database	PostgreSQL for structured data storage and search optimization.
- Authentication	OAuth 2.0 via NU SSO + Duo 2FA for secure login.
- Hosting & Deployment	Hosted on AWS (EC2, RDS, S3) or Firebase for scalability.
- Messaging	WebSockets (Socket.io) for real-time chat.
- Security	Data encryption, fraud detection, and admin moderation.

# System Architecture

  ┌──────────────────────────────────────────────┐
  │                  NU Mart                     │
  ├──────────────────────────────────────────────┤
  │    🔐 NU Authentication (SSO + 2FA)          |
  │
  │    📦 Product Listings & Filters
  │
  │    💬 Secure In-App Messaging
  │
  │    🛠 Admin Moderation Tools
  │
  │    📍 Safe Meet-up Location Suggestions     │
  ├──────────────────────────────────────────────┤
  │   Frontend: React.js / Next.js              │
  │   Backend: Node.js + Express.js             │
  │   Database: PostgreSQL                      │
  │   Hosting: AWS / Firebase                   │
  │   Real-Time Chat: WebSockets (Socket.io)    │
  └──────────────────────────────────────────────┘
  
# How It Works

- Sign Up/Login – Authenticate using NU email & Duo 2FA.
- Browse Listings – Search for items using advanced filters.
- Post a Listing – Upload images, descriptions, and price.
- Chat Securely – Use in-app messaging for direct negotiations.
- Arrange a Meet-up – Suggested on-campus locations for safe transactions.
- Rate & Review – Build trust through seller ratings & fraud detection.

# Development Plan
The NU Mart project is structured into seven phases:

- 1️⃣ Requirement Analysis & Planning – Market research, feature analysis.
- 2️⃣ UI/UX Design & Prototyping – Wireframes, design review.
- 3️⃣ Core Development – Frontend, backend, and database integration.
- 4️⃣ Security & Transaction Features – Data encryption, fraud prevention.
- 5️⃣ Testing & Debugging – Beta testing, performance optimization.
- 6️⃣ Deployment & Launch – Hosting, domain setup, and go-live.
- 7️⃣ Maintenance & Future Enhancements – AI-based price suggestions, payments, and blockchain verification.

📅 Estimated Project Timeline: 10–12 months:

Estimated Budget: $191,663.48 (includes labor, hosting, security, and marketing costs).

# Future Enhancements
- ✅ AI-powered Price Suggestions – Automatically recommend competitive prices.
- ✅ Integrated Payments – Secure transactions via Stripe/PayPal.
- ✅ Blockchain Verification – Prevent fraudulent transactions.
- ✅ Mobile App – Extend platform availability.
- ✅ Community Forums – Discussion boards for buying/selling tips.

