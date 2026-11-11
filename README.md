# AI SaaS Application

An AI-powered SaaS application built with **Next.js**, featuring user authentication and AI-powered content generation using **Groq**.

## Live Demo

**[View Live Application](https://saas-olenrbi57-taha-0208.vercel.app/)**

## Features

- **User Authentication:** Secure authentication and user management with Clerk.
- **AI Integration:** Generate AI-powered business ideas using Groq.
- **Streaming Responses:** Receive AI-generated content in real time.
- **Protected API:** Authenticate requests and identify users through Clerk.
- **Modern Web Application:** Built with Next.js and React.

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Frontend framework |
| React | User interface |
| TypeScript | Type safety |
| Clerk | Authentication |
| Groq API | AI inference |
| OpenAI SDK | API integration |
| FastAPI | API backend |
| Vercel | Deployment |

## Getting Started

### Prerequisites

- Node.js 20 or later
- npm
- Clerk account
- Groq API key

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd saas
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

GROQ_API_KEY=your_groq_api_key
CLERK_JWKS_URL=your_clerk_jwks_url
```

Replace the placeholders with your actual credentials.

**Important:** Never commit API keys, secrets, or environment files to GitHub.

### 4. Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```text
saas/
├── api/
├── pages/
├── public/
├── styles/
├── .gitignore
├── package.json
├── package-lock.json
├── requirements.txt
└── README.md
```

## Deployment

The application is deployed using [Vercel](https://vercel.com/).

To deploy your own instance:

1. Import the repository into Vercel.
2. Configure the required environment variables.
3. Deploy the application.

## Security

- Keep API keys and credentials private.
- Protect API endpoints with authentication.
- Never expose secret environment variables in frontend code.
- Use environment variables to manage sensitive configuration.

## License

This project is licensed under the **Apache License 2.0**.

See the [LICENSE](LICENSE) file for the full license text.
