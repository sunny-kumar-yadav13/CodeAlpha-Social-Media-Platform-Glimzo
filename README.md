# Social Media Web Application

A modern, full-featured social media platform built with Next.js, React, and Redux Toolkit. This social media web application provides users with a comprehensive social networking experience including posts, stories, comments, friend requests, and real-time interactions.

## 🚀 Features

### Core Features
- **User Authentication** - Login, Register, and Logout functionality
- **Posts & Stories** - Create, edit, and share posts with multimedia support
- **Social Interactions** - Like, comment, and share content
- **Friend System** - Send, accept, and manage friend requests
- **User Profiles** - Customizable user profiles with stats and information
- **Real-time Notifications** - Stay updated with app activities
- **Search & Discovery** - Find users, posts, and trending content

### Advanced Features
- **Stories** - Temporary content sharing similar to Instagram/Snapchat stories
- **Hashtag System** - Organize and discover content through hashtags
- **Bookmarks** - Save posts for later viewing
- **Trending Content** - Discover popular posts and topics
- **Poll Creation** - Interactive polls in posts
- **Media Support** - Image uploads and GIF integration
- **Mood & Background Options** - Customize post appearance
- **Profile Verification** - Profile picture verification system

## 🛠️ Tech Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **React 18** - UI library
- **Redux Toolkit** - State management
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **React Icons** - Icon library
- **React Toastify** - Toast notifications

### Additional Libraries
- **Axios** - HTTP client for API requests
- **Moment.js** - Date/time manipulation
- **clsx** - Dynamic class name utility

## 📁 Project Structure

```
src/
├── api/                    # API configurations
│   └── axiosInstance.js   # Axios configuration
├── app/                   # Next.js App Router pages
│   ├── (auth)/           # Authentication pages
│   ├── bookmarks/        # Bookmarks page
│   ├── profile/          # User profiles
│   ├── posts/            # Post details
│   ├── stories/          # Stories section
│   └── ...              # Other app pages
├── components/           # Reusable components
│   ├── common/          # Shared components
│   ├── feed/            # Feed-related components
│   ├── layout/          # Layout components
│   └── userProfile/     # Profile components
├── contexts/            # React contexts
├── redux/               # Redux store and slices
│   ├── auth/           # Authentication state
│   ├── posts/          # Posts state
│   ├── users/          # Users state
│   └── ...            # Other slices
└── utility/            # Utility functions
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sunny-kumar-yadav13/CodeAlpha-Social-Media-Platform-Glimzo.git
   cd frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   - Copy `envsample.txt` to `.env.local`
   - Update environment variables as needed

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open the application**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🎨 Key Components

### Authentication System
- Login, register, and logout pages
- Protected routes with authentication guards
- JWT token management

### Post System
- Rich text posting with formatting options
- Image and GIF support
- Poll creation functionality
- Background themes and mood selection
- Hashtag integration

### Story System
- Temporary content sharing
- Story creation and viewing
- Auto-expiring content

### Social Features
- Friend request system
- Following/followers management
- User search and discovery
- Profile customization

### Interaction System
- Like and comment functionality
- Real-time notifications
- Bookmark system
- Content sharing

## 🔧 Configuration Files

- `next.config.mjs` - Next.js configuration
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.mjs` - PostCSS configuration
- `jsconfig.json` - JavaScript configuration

## 🔐 Environment Variables

Create a `.env.local` file based on `envsample.txt` and configure:
- API endpoints
- Authentication secrets
- Third-party service keys
- Database connection strings

## 📱 Responsive Design

SApp is fully responsive and optimized for:
- Desktop browsers
- Tablet devices  
- Mobile phones
- Progressive Web App (PWA) capabilities

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📸 Screenshorts

![image alt](https://github.com/sunny-kumar-yadav13/CodeAlpha-Social-Media-Platform-Glimzo/blob/b6211a53a33448cbf3ea387403cd27ac5e2aedee/Screenshot.png)

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Built with Next.js and React
- Styled with Tailwind CSS
- State management by Redux Toolkit
- Icons provided by React Icons
- Animations powered by Framer Motion

---

**Made with ❤️ by Sunny**
