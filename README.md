# ENS App

Vercel Build: https://ens-app-six.vercel.app/

## Description
ENS App is a Next.js application designed to work with Ethereum Name Service (ENS). The app leverages modern web technologies to interact with ENS domains and related services.

## Features
- Next.js framework for server-side rendering and optimized performance.
- Tailwind CSS for modern and responsive UI design.
- Integration with Ethereum Name Service for domain interactions.

## Project Structure
```plaintext
|-- public/        # Static assets (images, etc.)
|-- src/
|   |-- app/       # Main application logic
|   |-- pages/     # Page components for routing
|   |-- styles/    # Global and component-level styles
|-- .gitignore     # Git ignored files and folders
|-- package.json   # Node.js dependencies and scripts
|-- tailwind.config.mjs # Tailwind CSS configuration
|-- next.config.js # Next.js configuration
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/jepherycyril/ens-app.git
   cd ens-app
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Application
To start the development server:
```bash
npm run dev
# or
yarn dev
```
The application will be available at `http://localhost:3000`.

### Building for Production
To build the app for production:
```bash
npm run build
```
The output will be in the `.next` directory.

### Exporting as Static Files
To export the app as static files:
```bash
npx next export
```

### Deploying
1. Ensure the app is built using `npm run build`.
2. Deploy the `.next` folder or exported files to your hosting provider.


You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
