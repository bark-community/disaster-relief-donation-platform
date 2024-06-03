## BARK Foundation | Disaster Relief Donation Platform

Welcome to the BARK Foundation Disaster Relief Donation Platform repository. This platform aims to facilitate post-disaster relief efforts by providing a centralized hub for donations, donor testimonials, and relevant information. Together, we can rebuild homes, restore hope, and empower individuals and communities to overcome adversity and rebuild their lives with dignity and resilience.

## Project Overview

The BARK Foundation aims to empower families in poverty by enabling direct support through donations. This platform will ensure that those in need receive timely and efficient support through a user-friendly interface, secure transactions, and transparent tracking.

## Key Features

1. **Donation Management**: Secure and easy-to-use donation processing.
2. **User Authentication**: Secure login and registration for donors and administrators.
3. **Testimonial Submissions**: Enable donors to share their experiences.
4. **Disaster Information**: Up-to-date information on ongoing disaster relief efforts.
5. **Administrative Dashboard**: Tools for administrators to manage donations, users, and content.
6. **Blockchain Integration**: Transparent and immutable donation records using Solana Blockchain.
7. **Payment Processing**: Efficient and secure transactions with Circle USD and Solana Pay.
8. **Supply Chain Management**: Verifying and tracking supply chain data using Chainlink and logistics.

## Technology Stack

- **Next.js**: Server-side rendering and static site generation.
- **React**: User interface development.
- **Redux**: State management.
- **Postgres**: Database.
- **RTK Query**: Efficient data fetching.
- **React Router DOM**: Navigation.
- **Solana Blockchain**: Decentralized donation tracking.
- **Circle USD and Solana Pay**: Secure payment processing.
- **Chainlink**: Supply chain data, KYC/AML verification, Oracles, and logistics.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- Solana CLI and a wallet set up for blockchain integration.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/bark-community/disaster-relief-donation-platform.git
   cd disaster-relief-donation-platform
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Configure environment variables:**

   Create a `.env.local` file in the root directory and add necessary environment variables for Solana, Circle, and Chainlink integrations.

   ```plaintext
   NEXT_PUBLIC_SOLANA_NETWORK=devnet
   NEXT_PUBLIC_SOLANA_WALLET_ADDRESS=your-wallet-address
   CIRCLE_API_KEY=your-circle-api-key
   CHAINLINK_API_KEY=your-chainlink-api-key
   EVASV_API_KEY=your-evasv-api-key
   ```

### Running the Application

1. **Start the development server:**

   ```bash
   npm run dev
   ```

2. **Build for production:**

   ```bash
   npm run build
   npm start
   ```

### Directory Structure

```
disaster-relief-donation-platform/
├── public/                     # Static assets
├── src/
│   ├── components/             # Reusable UI components
│   ├── features/               # Redux slices and RTK Query setup
│   ├── pages/                  # Next.js pages
│   ├── services/               # API services and blockchain integration
│   ├── styles/                 # Styling files
│   ├── utils/                  # Utility functions
│   ├── App.js                  # Main application component
│   ├── store.js                # Redux store configuration
├── .env.local                  # Environment variables (not included in repo)
├── .gitignore                  # Git ignore file
├── package.json                # NPM dependencies and scripts
└── README.md                   # Project documentation
```

## Improvements

We continually seek to improve the platform. Here are some planned enhancements:

1. **Enhanced User Interface**: Improving the UI/UX for a more seamless user experience.
2. **Mobile Optimization**: Ensuring the platform is fully responsive and works well on all devices.
3. **Advanced Analytics**: Adding analytics features for better tracking and reporting of donations and user activity.
4. **Multi-language Support**: Providing support for multiple languages to reach a broader audience.
5. **AI Integration**: Implementing AI for personalized donor experiences and targeted relief efforts.

## Contributing

We welcome contributions to the BARK | Disaster Relief Donation Platform! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License

MIT License.
