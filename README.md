# Keepers Framework

An open-source AI agent framework for building intelligent keepers into Base and any Omni Chain dApps. Powered by Next.js, React and OpenAI.

## Overview

Keepers allows you to easily integrate keepers in your AI assistant into your dApp that can:

- Collaboration with TAO subnets
- Perform AI Tasks
- Training machine learning models
- Running inference operations
- Run as Sidecar to secure & monitor the agents

## Getting Started

1. Set up environment variables by creating a `.env` file in the root directory:

```bash
# Required: OpenAI API key for the AI functionality
OPENAI_API_KEY=your_openai_api_key

# Required: OpenAI model to use (e.g., gpt-4, gpt-3.5-turbo)
NEXT_PUBLIC_AI_MODEL=gpt-4o

# Optional: MongoDB connection for token mappings (if you want to use token mappings, and save addresses = tickers)
MONGODB_URI=your_mongodb_uri
MONGODB_DB=your_database_name

# Required: Your app's URL
NEXT_PUBLIC_APP_URL=http://localhost:3000

# Optional: Helius endpoint for DAS APIs
NEXT_PUBLIC_HELIUS_API_KEY=your_helius_api_key
```

2. Install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) to see the demo app.

## Integration Guide

### 1. Configure Custom Functions

```

```

### 2. Embed the Component

```

```

### 3. Customize the Look

The component is built with CSS and is fully customizable. Override styles through:

- Custom className props
- Tailwind CSS classes
- CSS modules
- Styled-components

## Features

- 🤖 AI-powered chat interface
- ⚙️ Configurable function framework
- 🎨 Customizable UI/UX
- 📱 Responsive design
- ⚡️ Real-time updates

## Learn More

- [Project Documentation](docs/README.md)
- [Configuration Guide](docs/configuration.md)
- [API Reference](docs/api-reference.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
