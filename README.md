# Pikzels API Documentation

[![API Version](https://img.shields.io/badge/API-v3.1.0-brightgreen)](https://api.pikzels.com)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289DA)](https://go.pikzels.com/discord)
[![Support](https://img.shields.io/badge/Support-api%40pikzels.com-blue)](mailto:api@pikzels.com)

Official documentation for the Pikzels API - **100X YOUR VIEWS** with viral content creation tools.

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

- **Image Generation** - Create eye-catching visuals from text prompts
- **Image Editing** - Transform existing images with smart edits
- **Face Swapping** - Seamlessly swap faces between images
- **Image Recreation** - Enhance and recreate images with your spin
- **Title Generation** - Generate engaging text content
- **Custom Training** - Train personalized AI models on your own content

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

All API endpoints require an API key. Get yours from the [Pikzels Dashboard](https://app.pikzels.com/platform).

## 📊 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/v1/thumbnail` | POST | Generate thumbnails from text |
| `/v1/edit` | POST | Edit existing images |
| `/v1/recreate` | POST | Recreate and enhance images |
| `/v1/faceswap` | POST | Swap faces between images |
| `/v1/title` | POST | Generate creative titles |
| `/v1/persona` | POST | Train custom persona models |
| `/v1/persona` | GET | Check persona training status |
| `/v1/style` | POST | Train custom style models |
| `/v1/style` | GET | Check style training status |

## 🎨 Supported Formats

16:9, 9:16, and 1:1 aspect ratios

## 🤖 Available Models

Three AI models: **pkz-1** (gaming), **pkz-2** (realistic), **pkz-3** (advanced)

## 💬 Community & Support

- **Discord**: [Join our community](https://go.pikzels.com/discord)
- **Email**: [api@pikzels.com](mailto:api@pikzels.com)
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