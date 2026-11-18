# Customer Frontend - Multi-Vendor Retail Marketplace

A professional customer-facing frontend for a multi-vendor e-commerce marketplace built with React, Vite, Redux Toolkit, and React Router.

## Technology Stack

- **React 19.3** - UI library
- **Vite 8.3** - Build tool and dev server
- **Redux Toolkit 2.14** - State management
- **React Router DOM 7.18** - Client-side routing
- **Axios 1.21** - HTTP client
- **React Icons 5.7** - Icon library

## Project Structure

```
src/
├── assets/              # Images and static assets
├── components/          # Reusable React components
│   ├── common/         # Common UI components
│   ├── layout/         # Layout components (Navbar, Footer, Layout)
│   ├── products/       # Product-related components
│   └── cart/           # Cart-related components
├── pages/              # Page components
│   ├── Home.jsx
│   ├── Products.jsx
│   ├── ProductDetails.jsx
│   ├── Cart.jsx
│   ├── Wishlist.jsx
│   ├── Checkout.jsx
│   ├── OrderConfirmation.jsx
│   └── NotFound.jsx
├── redux/              # Redux state management
│   ├── store.js
│   └── slices/
│       ├── cartSlice.js
│       ├── wishlistSlice.js
│       └── productSlice.js
├── services/           # API service layer
│   └── api.js
├── data/               # Sample/mock data for development
│   └── sampleProducts.js
├── hooks/              # Custom React hooks
├── styles/             # Global styles and CSS variables
│   ├── variables.css   # Brand colors and design tokens
│   └── global.css      # Global styles and resets
├── App.jsx            # Main app component with routing
└── main.jsx           # App entry point with Redux Provider
```

## Brand Colors

The application uses a professional color palette:

- **Powder Blue** (#B8D8E8) - Selected backgrounds, hero sections
- **Pure White** (#FFFFFF) - Primary background
- **Orange** (#F07835) - Primary buttons and actions
- **Deep Charcoal** (#202A30) - Text and headings
- **Ice White** (#F4F8FA) - Subtle backgrounds

## Available Routes

- `/` - Home page
- `/products` - Product listing
- `/products/:id` - Product details
- `/cart` - Shopping cart
- `/wishlist` - User wishlist
- `/checkout` - Checkout page
- `/order-confirmation/:orderId` - Order confirmation
- `*` - 404 Not Found page

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The application will start on `http://localhost:5173`

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Environment Variables

Create a `.env` file in the root directory (use `.env.example` as template):

```
VITE_API_BASE_URL=http://localhost:5000/api
```

## Development Status

✅ Project foundation and structure  
⏳ Navigation and layout components  
⏳ Homepage design  
⏳ Product listing and filtering  
⏳ Shopping cart functionality  
⏳ Wishlist functionality  
⏳ Checkout process  
⏳ Backend API integration  

## Next Steps

1. Build responsive navigation bar
2. Create homepage with hero section and featured products
3. Implement product listing with filters
4. Build shopping cart with Redux
5. Add wishlist functionality
6. Create checkout flow
7. Integrate with backend API

---

Built with ❤️ for a professional multi-vendor marketplace experience
