# 🍽️ Sewanee Food Share

A community-driven food sharing platform that connects people to reduce food waste and build stronger neighborhoods.

## 📱 About

**Sewanee Food Share** is a mobile-first web application currently used by 500+ users to share surplus food across campus, reducing food waste by 40% and fostering community connections.

## 🚀 Getting Started

### Prerequisites

- Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

### Installation

```sh
# Clone the repository
git clone https://github.com/ankii08/Hungry-Tiger-Food-App.git

# Navigate to the project directory
cd login-layout-lover

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Environment Variables

Create a `.env` file in the root directory with the following variables:

```
VITE_SUPABASE_PROJECT_ID=your_project_id
VITE_SUPABASE_PUBLISHABLE_KEY=your_publishable_key
VITE_SUPABASE_URL=your_supabase_url
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

## 🛠️ Tech Stack

This project is built with:

- **Frontend**: React + TypeScript + Vite
- **UI Library**: Shadcn-ui + Tailwind CSS
- **Backend**: Supabase (PostgreSQL + Authentication + Storage)
- **Maps**: Google Maps JavaScript API
- **Real-time**: Supabase Subscriptions

## ⭐ Key Features

### 📍 Interactive Food Map
- Custom food image markers showing actual food photos
- Real-time location-based food discovery
- Color-coded status indicators (active, almost finished, expired)
- Detailed info windows with food descriptions
- Toggle between active and expired posts

### 🍕 Smart Food Posts
- Photo-based food listings with descriptions
- Expiration tracking with visual status indicators
- Serving size information and pickup instructions
- Automatic expiration handling

### 👥 Community Engagement
- "Going" feature to indicate pickup interest
- Real-time notifications for food updates
- User profiles with avatars
- Notification badges

### 📊 Post Management
- Personal dashboard for managing posts
- "Mark as Finished" functionality for owners
- Expired posts archive
- Secure row-level security policies

## 🗺️ How to Use the Food Map

1. Click "Find Food" in the main dashboard
2. Browse the interactive map to find food near you
3. Click markers to see detailed information about available food
4. Toggle between active and expired food posts
5. Use the "Going" button to indicate your interest in picking up food

See [MAPS_README.md](./MAPS_README.md) for detailed map documentation.

## 🚢 Deployment

### Build for Production

```sh
npm run build
```

### Preview Production Build

```sh
npm run preview
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

Built by Ankit Das

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ankii08/Hungry-Tiger-Food-App/issues).

---

**Made with ❤️ to reduce food waste and build community**
