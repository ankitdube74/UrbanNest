# Urban Nest

A modern property booking site built with React, TypeScript, and Tailwind CSS.

## Features

- Browse property listings
- Filter properties by price range, property type, and amenities
- View detailed property information
- Book properties with date selection and guest count
- Responsive design for desktop and mobile

## Technology Stack

- **Frontend Framework**: React with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Heroicons
- **Components**: Headless UI
- **Build Tool**: Vite

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd urban-nest
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and visit `http://localhost:5173`

## Project Structure

```
urban-nest/
├── public/              # Static assets
├── src/
│   ├── components/      # React components
│   │   ├── Navbar.tsx   # Top navigation bar
│   │   ├── Filters.tsx  # Property filters
│   │   ├── PropertyGrid.tsx  # Grid of property cards
│   │   ├── PropertyCard.tsx  # Individual property card
│   │   ├── PropertyDetail.tsx  # Detailed property view
│   │   └── BookingForm.tsx  # Property booking form
│   ├── services/        # Service functions
│   │   └── propertyService.ts  # Property data and filter functions
│   ├── types/           # TypeScript type definitions
│   │   └── index.ts     # Shared type interfaces
│   ├── App.tsx          # Main app component
│   ├── main.tsx         # App entry point
│   └── index.css        # Global styles
├── tailwind.config.js   # Tailwind CSS configuration
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

## Features Implemented

1. **Property Browsing**
   - Grid layout of available properties
   - Property cards showing key information

2. **Filtering**
   - Price range filters
   - Property type filters (entire place, private room, shared room)
   - Amenity filters (WiFi, kitchen, pool, etc.)

3. **Property Details**
   - Image gallery
   - Property description
   - Host information
   - Amenity list
   - Reviews and ratings

4. **Booking System**
   - Date selection
   - Guest count selection
   - Price calculation including fees
   - Booking confirmation

5. **Responsive Design**
   - Mobile-friendly interface
   - Responsive grid layouts
   - Mobile filter drawer

## Planned Features

- User authentication
- Property search by location
- Map view of properties
- Review system
- Favoriting properties
- Host dashboard

## Credits
## Credits
- Project developed by Ankit Dubey
- Images from Unsplash
- Design inspired by modern booking platforms

## License

MIT
