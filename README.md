# VANTAGE - Graphics & Video Portfolio

A high-end, editorial portfolio for professional graphics designers and video editors featuring cinematic minimalism, bold typography, and immersive visual storytelling.

## Features

- **Cinematic Minimalism**: A clean, dark-themed design that puts the focus on visual content.
- **Bold Typography**: High-impact headings and editorial layouts.
- **Immersive Animations**: Smooth transitions and layout animations using `motion`.
- **Full-Stack Architecture**: Built with React, Vite, and Express.
- **Firebase Integration**: Real-time data and authentication support.
- **Responsive Design**: Optimized for all screen sizes.

## Tech Stack

- **Frontend**: React, Tailwind CSS, Motion
- **Backend**: Express (Node.js)
- **Build Tool**: Vite
- **Database/Auth**: Firebase
- **Icons**: Lucide React

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd vantage-portfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add your Gemini API key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

4. Configure Firebase:
   Ensure `firebase-applet-config.json` is present in the root directory with your Firebase project credentials.

### Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

### Production

Build the application for production:
```bash
npm run build
```

Start the production server:
```bash
npm start
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
