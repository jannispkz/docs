# Pikzels API Documentation

[![API Version](https://img.shields.io/badge/API-v3.1.0-brightgreen)](https://api.pikzels.com)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289DA)](https://go.pikzels.com/discord)
[![Support](https://img.shields.io/badge/Support-support%40pikzels.com-blue)](mailto:support@pikzels.com)

Official documentation for the Pikzels API - AI-powered image generation and manipulation services.

## 🚀 Quick Start

Get started with the Pikzels API in minutes:

```bash
curl -X POST https://api.pikzels.com/v1/thumbnail \
  -H "X-Api-Key: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"prompt": "beautiful landscape", "format": "16:9", "model": "pkz-2"}'
```

## 📚 Documentation

Visit our full documentation at [docs.pikzels.com](https://docs.pikzels.com) to learn about:

- **Image Generation** - Create thumbnails from text prompts
- **Image Editing** - Modify existing images with AI
- **Face Swapping** - Seamlessly swap faces between images
- **Image Recreation** - Enhance and recreate images
- **Title Generation** - Generate engaging text content

## 🛠️ Local Development

To run the documentation locally:

```bash
# Install Mintlify CLI
npm i -g mintlify

# Navigate to the docs folder
cd pikzels-api-documentation

# Start the development server
mintlify dev
```

View your local documentation at `http://localhost:3000`

## 🔑 Authentication

All API endpoints require authentication using an API key:

```
X-Api-Key: pkz_your_api_key_here
```

Get your API key from the [Pikzels Dashboard](https://google.com).

## 📊 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/v1/thumbnail` | POST | Generate thumbnails from text |
| `/v1/edit` | POST | Edit existing images |
| `/v1/recreate` | POST | Recreate and enhance images |
| `/v1/faceswap` | POST | Swap faces between images |
| `/v1/title` | POST | Generate creative titles |

## 🎨 Supported Formats

- **16:9** - Landscape (YouTube thumbnails)
- **9:16** - Portrait (Instagram Stories)
- **1:1** - Square (Instagram posts)

## 🤖 Available Models

- **pkz-1** - Legacy model for gaming content (Roblox, Fortnite, Minecraft, etc.)
- **pkz-2** - Go-to model for realistic images and detailed content
- **pkz-3** - Most advanced model, preferred choice for highest quality

## 💬 Community & Support

- **Discord**: [Join our community](https://go.pikzels.com/discord)
- **Email**: [support@pikzels.com](mailto:support@pikzels.com)
- **GitHub**: [@Pikzels](https://github.com/Pikzels)
- **Twitter**: [@Pikzels](https://x.com/Pikzels)

## 📝 Contributing

To contribute to the documentation:

1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

Copyright © 2024 Pikzels. All rights reserved.