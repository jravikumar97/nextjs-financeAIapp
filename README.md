# MarketMind - AI-Powered Stock Market Assistant

A modern web application that combines financial market data with AI capabilities to provide an interactive and intelligent stock market assistant. Built with Next.js and powered by OpenAI's GPT models.

![Project Screenshot](app/assets/screenshot.png)

## 🚀 Features

- **AI-Powered Market Analysis**: Get instant insights and analysis of stocks, market trends, and financial data
- **Real-time Market Data**: Access up-to-date stock prices, market indices, and financial news
- **Modern UI/UX**: Clean, responsive design with a focus on user experience
- **Type-Safe Development**: Built with TypeScript for robust code quality
- **Database Integration**: Efficient data storage and retrieval using Astra DB

## 🛠️ Tech Stack

### Frontend
- **Next.js 15**: React framework for server-side rendering and static site generation
- **React 19**: Latest version of React for building user interfaces
- **TypeScript**: For type-safe development
- **Tailwind CSS**: For modern, responsive styling

### Backend
- **Next.js API Routes**: Serverless API endpoints
- **OpenAI API**: Integration with GPT models for AI capabilities
- **Astra DB**: NoSQL database for data storage
- **LangChain**: Framework for building AI applications

### Development Tools
- **ESLint**: For code linting and quality control
- **TypeScript**: For type checking and better development experience
- **Puppeteer**: For web scraping and data collection
- **Dotenv**: For environment variable management

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nextjs-marketmind.git
cd nextjs-marketmind
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:
```env
OPENAI_API_KEY=your_openai_api_key
ASTRA_DB_API_ENDPOINT=your_astra_db_endpoint
ASTRA_DB_APPLICATION_TOKEN=your_astra_db_token
```

4. Run the development server:
```bash
npm run dev
```

5. Seed the database (optional):
```bash
npm run seed
```

## 🏗️ Project Structure

```
nextjs-marketmind/
├── app/
│   ├── api/           # API routes
│   ├── assets/        # Static assets
│   ├── components/    # React components
│   ├── global.css     # Global styles
│   ├── layout.tsx     # Root layout
│   └── page.tsx       # Home page
├── scripts/           # Utility scripts
├── .env              # Environment variables
├── next.config.ts    # Next.js configuration
└── package.json      # Project dependencies
```

## 🚀 Deployment

The application can be deployed on any platform that supports Next.js applications, such as:
- Vercel (recommended)
- Netlify
- AWS Amplify
- DigitalOcean App Platform
