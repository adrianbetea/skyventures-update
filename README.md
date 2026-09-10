# Skyventures

**Skyventures** is a mobile app, built by a two-person team, that gives users personalized recommendations for points of interest based on their **current location** and **weather conditions**, and lets them plan, save, and share full trip itineraries.

## Core Features

### 1. Location-based recommendations
Suggests nearby points of interest (restaurants, parks, theaters, etc.) based on the user's current location.

### 2. Weather-based recommendations
Adapts suggestions to current weather conditions — indoor activities (restaurants, theaters) on rainy days, outdoor activities on sunny days.

### 3. Favorites
Users can save points of interest to a favorites list.

### 4. Itineraries
- Build a custom itinerary manually, or
- Generate one automatically with an AI agent (Gemini 2.5 Flash) that plans the itinerary for the user.
- Attach photos to itinerary entries, stored in an AWS S3 bucket.
- Share itineraries with the community for other users to browse.

### 5. Authentication
Google OAuth sign-in.

## Tech Stack

- **Frontend:** React Native
- **Backend:** Node.js
- **Database:** Firebase / Firestore
- **File storage:** AWS S3
- **AI agent:** Gemini 2.5 Flash (automatic itinerary generation)
- **Authentication:** Google OAuth
- **Weather API:** WeatherAPI
- **Places/location API:** Google Places API
