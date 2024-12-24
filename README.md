# Recipe Finder App 📱

A React Native mobile application that helps users discover, save, and manage recipes. Built with Expo and TypeScript, featuring a modern UI and seamless user experience.

## Features 🌟

- **Recipe Search**: Search for recipes using keywords
- **Categories**: Browse recipes by categories (Breakfast, Lunch, Dinner, etc.)
- **Recipe Details**: View detailed information including:
  - Ingredients
  - Cooking instructions
  - Preparation time
  - Serving size
- **Save Favorites**: Save recipes for offline access
- **Push Notifications**: Get notified about:
  - Daily recipe suggestions
  - Saved recipe updates
  - New features
- **User Profile**: Manage saved recipes and preferences

## Tech Stack 💻

- React Native with Expo
- TypeScript
- Expo Router for navigation
- Spoonacular API for recipe data
- AsyncStorage for local data persistence
- Expo Notifications for push notifications

## Prerequisites 📋

- Node.js (v14 or newer)
- npm or yarn
- Expo CLI
- iOS Simulator or Android Emulator (for development)

## Installation 🚀

1. Clone the repository:
   bash
  git clone https://github.com/Saee1005/recipe-finder.git
2. Install dependencies:
   bash
   cd recipe-finder
   npm install
3. Create a `.env` file in the root directory and add your Spoonacular API key:
   EXPO_PUBLIC_SPOONACULAR_API_KEY= '48295a8774674097a19e3586969c2efb'

4. Start the development server:
   bash
   npx expo start
5. ## Environment Setup 🔧

- Create an account on [Spoonacular](https://spoonacular.com/food-api) to get an API key
- Set up your Expo project ID in `app.config.js`
- Configure push notifications in `eas.json`

## Project Structure 📁
recipe-finder/
├── app/ # Main application screens
│ ├── (tabs)/ # Tab navigation screens
│ ├── recipe/ # Recipe-related screens
│ └── profile.tsx # User profile screen
├── components/ # Reusable components
├── services/ # API and notification services
├── types/ # TypeScript type definitions
└── config/ # Configuration files
## Features in Detail 🔍

### Recipe Search
- Real-time search with API integration
- Category-based filtering
- Grid view of search results

### Recipe Details
- Comprehensive recipe information
- Save to favorites functionality
- Cooking instructions and ingredients list

### Push Notifications
- Daily recipe suggestions
- Saved recipe notifications
- Customizable notification preferences

### User Profile
- View saved recipes
- Manage notification settings
- User preferences
## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments 👏

- [Spoonacular API](https://spoonacular.com/food-api) for recipe data
- [Expo](https://expo.dev/) for the development framework
- [React Native](https://reactnative.dev/) community for resources and support

## Contact 📧

Your Name - [@Saee1005](https://github.com/Saee1005)

Project Link: [https://github.com/Saee1005/recipe-finder](https://github.com/Saee1005/recipe-finder)
   
