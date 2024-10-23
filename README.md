# Promptopia

![Promptopia Banner](public/assets/images/logo.svg)

A modern open-source AI prompting tool that allows users to discover, create and share creative prompts. Create and manage your AI prompts in a user-friendly environment.

## Features

- 🔐 **Google Authentication** - Secure sign in with Google
- 💡 **Create & Share** - Post your AI prompts for others to see
- 🔍 **Search System** - Search by username, tag, or prompt content
- 🏷️ **Tag System** - Organize prompts with custom tags
- 📱 **Responsive Design** - Works on all devices
- ⚡ **Fast Performance** - Built with Next.js 13

## Demo

### Home Page

![Promptopia Demo](./public/assets/images/Promptopia%20Demo.png)

### Create Post Page

![Create Post](./public/assets/images/Create%20Post.png)

## Quick Start

### Prerequisites

Make sure you have:

- Node.js 16+ installed
- A MongoDB database
- A Google Cloud Console account

### Installation

1. Clone the repository

```bash
git clone https://github.com/Pekkawi/Next13-Promptopia.git
```

2. Install dependencies

```bash
cd Next13-Promptopia
npm ci
```

3. Set up your environment variables in `.env`

```env
MONGODB_URI=your_mongodb_connection_string
GOOGLE_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret
```

4. Run the development server

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Tech Stack

- [Next.js 13](https://nextjs.org/) - React framework
- [MongoDB](https://www.mongodb.com/) - Database
- [NextAuth.js](https://next-auth.js.org/) - Authentication
- [TailwindCSS](https://tailwindcss.com/) - Styling

## Project Structure

```
├── app/
│   ├── api/            # API routes
│   ├── create-prompt/  # Prompt creation page
│   ├── profile/        # User profile pages
│   ├── update-prompt/  # Prompt update page
│   └── page.jsx        # Home page
├── components/         # React components
├── models/            # MongoDB models
├── public/            # Static assets
├── styles/           # Global styles
└── utils/            # Helper functions
```

## Contributing

Contributions are always welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [Javascript Mastery](https://www.youtube.com/@javascriptmastery)

Made with ❤️ by Pekkawi
