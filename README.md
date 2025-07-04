# 🤖 DataSteward.ai

> The first AI-powered Requirements Steward that transforms business questions into perfect data contracts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Privacy First](https://img.shields.io/badge/Privacy-First-green.svg)](#privacy-first)
[![Open Source](https://img.shields.io/badge/Open-Source-blue.svg)](https://github.com/PowerUlf/datasteward-ai)

## 🎯 Vision

DataSteward.ai revolutionizes BI requirements engineering by combining the expertise of a requirements manager with a data steward - **without communication loss and 10x faster**.

**Input:** Natural business questions  
**Output:** Validated, transparent data contracts automatically integrated into your data catalog

## ✨ The "Holy Shit" Moment

```
Business User: "I need monthly sales by region for Q4 analysis"
↓
DataSteward.ai validates against your metadata
↓
Transparent business → technical mapping shown
↓
Perfect YAML/JSON data contract generated
↓
Automatically pushed to OpenMetadata
↓
User: "HOLY SHIT, that's exactly what I wanted!"
```

## 🏗️ Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Business      │    │  DataSteward.ai │    │  Data Catalog   │
│   Requirements  │───▶│   AI Engine     │───▶│  Integration    │
│                 │    │                 │    │ (OpenMetadata)  │
└─────────────────┘    └─────────────────┘    └─────────────────┘
                              │
                              ▼
                    ┌─────────────────┐
                    │  Transparency   │
                    │   Framework     │
                    └─────────────────┘
```

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- Python 3.9+
- Node.js 18+

### 5-Minute Setup

```bash
# Clone the repo
git clone https://github.com/PowerUlf/datasteward-ai.git
cd datasteward-ai

# Start with Docker (includes Adventure Works demo data)
docker-compose up -d

# Open browser
open http://localhost:3000
```

**That's it!** DataSteward.ai is running with Adventure Works sample data.

## 🔒 Privacy First

DataSteward.ai gives you **complete control** over your data privacy:

### 🏠 Local Processing
- **Default:** All processing happens on your infrastructure
- **Zero Cloud Dependency** for basic operations
- **On-Premises deployment** supported

### ☁️ Optional Cloud Enhancement
- **User Choice:** Enable cloud AI (Claude/GPT-4) for enhanced quality
- **Transparent Logging:** See exactly what data (if any) leaves your environment
- **Anonymization:** Sensitive data automatically scrubbed before cloud processing

### 🔍 Full Transparency
```yaml
transparency_mode: full_logging
data_processing:
  local_llm: "Enabled - 100% private"
  cloud_ai: "User choice - with consent dialog"
  anonymization: "Automatic for cloud requests"
  audit_trail: "Complete request/response logging"
```

## 🛠️ Technology Stack

- **Backend:** FastAPI + Python (AI engine, transparency framework)
- **Frontend:** React + Tailwind CSS (conversational UI)
- **AI Engine:** Local LLM + Optional Claude/GPT-4
- **Integration:** OpenMetadata REST APIs
- **Deployment:** Docker Compose, Kubernetes ready

## 📋 Features

### Core Features (Open Source)
- ✅ Conversational requirements gathering
- ✅ Adventure Works demo integration
- ✅ Basic data contract generation (YAML/JSON)
- ✅ OpenMetadata integration
- ✅ Privacy-first architecture
- ✅ Transparency framework

### Premium Features (Roadmap)
- 🔄 Advanced data catalog connectors (Databricks, Snowflake, etc.)
- 🧠 Enterprise knowledge graph
- 🤖 Business process automation recommendations
- 📊 Requirements analytics & insights
- 🔧 Custom fine-tuned models

## 🎮 Demo

Try the live demo with Adventure Works data:

1. **Start the application:** `docker-compose up`
2. **Ask a business question:** "Show me sales performance by product category"
3. **Watch the magic:** See requirements → validation → data contract generation
4. **Verify transparency:** Check the logs to see exactly what happened

## 🤝 Contributing

We're building the future of BI requirements engineering together!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Community Guidelines
- **Privacy First:** All contributions must respect our privacy-first principles
- **Transparency:** Code must be self-documenting and auditable
- **User Focus:** Features should solve real business user problems

## 📚 Documentation

- [Installation Guide](docs/installation.md)
- [API Documentation](docs/api.md)
- [Privacy & Security](docs/privacy.md)
- [Contributing Guide](docs/contributing.md)
- [Architecture Deep Dive](docs/architecture.md)

## 🌟 Roadmap

### Phase 1: Foundation (Current)
- [x] Core conversational AI engine
- [x] Adventure Works integration
- [x] Basic data contract generation
- [ ] OpenMetadata integration
- [ ] Docker deployment

### Phase 2: Community (Q2 2025)
- [ ] Multi-schema support
- [ ] Plugin architecture
- [ ] Community templates
- [ ] Advanced anonymization

### Phase 3: Enterprise (Q3 2025)
- [ ] Enterprise connectors
- [ ] Knowledge graph
- [ ] Business insights engine
- [ ] Custom model training

## 💬 Community

- **Discord:** [Join our community](https://discord.gg/datasteward-ai)
- **GitHub Discussions:** [Ask questions, share ideas](https://github.com/PowerUlf/datasteward-ai/discussions)
- **Twitter:** [@DataStewardAI](https://twitter.com/DataStewardAI)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **OpenMetadata** for the excellent data catalog foundation
- **Adventure Works** for the perfect demo dataset
- **The Open Source Community** for making this possible

---

**Built with ❤️ for the data community**

*"Finally, an AI that speaks business language and creates data contracts"*
