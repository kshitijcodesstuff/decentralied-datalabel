# Image Selection and Rewards Project

This project is a Next.js application that allows users to upload images and have them evaluated by workers. Upon successful completion of a task, the user receives a reward in the form of Solana tokens, which are securely transferred to their wallet using Solana wallet libraries. The application utilizes AWS S3 for image storage and Prisma ORM with PostgreSQL as the database.

## Features

- **Image Upload**: Users can upload images to be evaluated by workers.
- **Worker Image Selection**: Workers can select the best image from a set of uploaded images for a particular task.
- **Solana Rewards**: Upon successful completion of a task, the user receives a reward in Solana tokens, which is securely transferred to their wallet using Solana wallet libraries.
- **AWS S3 Storage**: Uploaded images are stored in AWS S3 for efficient and scalable storage.
- **CDN Integration**: Images stored in S3 are accessed through a Content Delivery Network (CDN) for optimal performance and reliability.
- **PostgreSQL Database**: The application uses a PostgreSQL database for data storage and management.
- **Prisma ORM**: Prisma ORM is used as an abstraction layer for interacting with the PostgreSQL database, providing type-safe and efficient database operations.

## Technologies Used

- Next.js
- React
- AWS S3
- PostgreSQL
- Prisma ORM
- Solana Wallet Libraries
- Tailwind CSS (or any other CSS framework/library)

## Getting Started

1. Clone the repository:
```sh
git clone https://github.com/your-repo/image-selection-rewards.git

Install dependencies:
cd image-selection-rewards
npm install
```


Set up the required environment variables:

DATABASE_URL: PostgreSQL database connection URL
AWS_ACCESS_KEY_ID: AWS access key ID for S3 access
AWS_SECRET_ACCESS_KEY: AWS secret access key for S3 access
SOLANA_WALLET_PRIVATE_KEY: Private key for the Solana wallet used for reward transfers


Start the development server:

```sh
codenpm run dev
```

Open http://localhost:3000 in your browser to see the application.

# Deployment
This application is production-ready and can be deployed to a hosting platform like Vercel, Netlify, or AWS Amplify. Before deploying, make sure to set the required environment variables on the hosting platform.
# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.