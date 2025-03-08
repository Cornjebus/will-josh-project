# Indy Pizza Heat Map

An interactive web application that heat maps the best places to get pizza in Indianapolis.

## Features

- Interactive map of Indianapolis
- Heat map visualization showing pizza quality density
- Filter options for different pizza styles, price ranges, and ratings
- User reviews and ratings integration
- Location-based search

## Tech Stack

- Frontend: React.js with TypeScript
- Map Integration: Leaflet.js or Google Maps API
- Styling: Tailwind CSS
- Data Storage: Firebase or MongoDB
- API: Node.js/Express

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Google Maps API key or Mapbox token (for map integration)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Cornjebus/will-josh-project.git
   cd will-josh-project
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory and add your API keys:
   ```
   REACT_APP_MAPS_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```
   npm start
   ```

## Project Structure

```
indy-pizza-heat-map/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── utils/
│   ├── data/
│   ├── App.tsx
│   └── index.tsx
├── .env
├── package.json
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Data sources for Indianapolis pizza establishments
- Map API providers