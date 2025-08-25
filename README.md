# Modern Seaside Stay - Hotel Booking Application

A modern, responsive hotel booking application built with React, TypeScript, and Vite. This application provides a seamless booking experience for a seaside hotel with features like apartment listings, booking management, gallery, and contact forms.

## 🌟 Features

- **Responsive Design**: Modern, mobile-first design that works on all devices
- **Multi-language Support**: Internationalization support for multiple languages
- **Apartment Listings**: Browse available apartments with detailed information
- **Booking System**: Complete booking flow with date selection and form validation
- **Gallery**: Photo gallery showcasing the hotel and surroundings
- **Contact Form**: Easy communication with the hotel
- **Amenities Page**: Detailed information about hotel facilities
- **Modern UI**: Built with shadcn/ui components and Tailwind CSS
- **Type Safety**: Full TypeScript support for better development experience

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with shadcn/ui components
- **Routing**: React Router DOM
- **State Management**: React Query (TanStack Query)
- **Form Handling**: React Hook Form with Zod validation
- **UI Components**: Radix UI primitives
- **Icons**: Lucide React
- **Date Handling**: date-fns
- **Charts**: Recharts
- **Notifications**: Sonner toast notifications

## 📁 Project Structure

```
src/
├── components/     # Reusable UI components
├── contexts/       # React contexts (Language, etc.)
├── hooks/          # Custom React hooks
├── lib/           # Utility functions and configurations
├── locales/       # Internationalization files
├── pages/         # Page components
│   ├── Index.tsx           # Home page
│   ├── Apartments.tsx      # Apartment listings
│   ├── BookingPage.tsx     # Booking form
│   ├── Gallery.tsx         # Photo gallery
│   ├── Contact.tsx         # Contact form
│   ├── Amenities.tsx       # Hotel amenities
│   └── NotFound.tsx        # 404 page
├── App.tsx        # Main application component
└── main.tsx       # Application entry point
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm, yarn, or bun package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/CavingSeeder/modern-seaside-stay-5005.git
   cd modern-seaside-stay-5005
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   bun install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   bun dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application.

## 📜 Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the application for production
- `npm run build:dev` - Build the application in development mode
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## 🎨 Customization

### Styling
The application uses Tailwind CSS for styling. You can customize the design by modifying:
- `tailwind.config.ts` - Tailwind configuration
- `src/index.css` - Global styles
- Component-specific styles in individual files

### Components
All UI components are built using shadcn/ui. You can add new components using:
```bash
npx shadcn@latest add [component-name]
```

### Internationalization
The app supports multiple languages. Add new translations in the `src/locales/` directory.

## 🏗️ Building for Production

1. **Build the application**
   ```bash
   npm run build
   ```

2. **Preview the production build**
   ```bash
   npm run preview
   ```

3. **Deploy**
   The built files will be in the `dist/` directory, ready for deployment to any static hosting service like:
   - Netlify
   - Vercel
   - GitHub Pages
   - AWS S3

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory for any environment-specific configurations:

```env
VITE_API_URL=your_api_url_here
VITE_APP_TITLE=Modern Seaside Stay
```

### Vite Configuration
Modify `vite.config.ts` for build optimizations, aliases, or plugins.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/CavingSeeder/modern-seaside-stay-5005/issues) page
2. Create a new issue with detailed information
3. Contact the development team

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) for the beautiful UI components
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Vite](https://vitejs.dev/) for the fast build tool
- [React](https://reactjs.org/) for the amazing frontend framework

---

**Modern Seaside Stay** - Where luxury meets the ocean 🌊
