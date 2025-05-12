# PRD Master - AI-Powered Product Requirements Document Generator

<div align="center">

![PRD Master Banner](https://img.shields.io/badge/PRD%20Master-AI%20Powered%20PRD%20Generator-blue?style=for-the-badge&logo=openai)

[![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![OpenRouter](https://img.shields.io/badge/Powered%20by-OpenRouter-orange.svg)](https://openrouter.ai/)
[![Cross Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20MacOS%20%7C%20Linux%20%7C%20Android-lightgrey.svg)](https://github.com/yourusername/prd-generator)

</div>

## 🚀 Overview

PRD Master is a powerful command-line tool that generates comprehensive Product Requirements Documents (PRDs) using AI. It leverages state-of-the-art language models through OpenRouter to create detailed, customizable product specifications with minimal effort.

Perfect for product managers, founders, engineers, and anyone needing to quickly draft professional product documentation.


## ✨ Features

- 🧠 **AI-Powered Generation** - Create detailed PRDs using the latest large language models
- 🌈 **Multiple AI Model Support** - Works with models from OpenAI, Anthropic, Google, Mistral, Meta, and others
- 📊 **Customizable Complexity** - Choose from standard, comprehensive, or advanced PRD templates
- 💻 **Code Examples** - Generate implementation code samples for technical features
- 🔧 **Tech Stack Integration** - Specify your preferred technologies for tailored implementation details
- 📱 **Cross-Platform** - Works on Windows, macOS, Linux, and even Android (via Termux)
- 🎨 **Elegant Interface** - Beautiful CLI with color formatting and interactive prompts
- 🔄 **Iterative Refinement** - Easily refine and regenerate to perfect your PRD
- 📁 **Automatic Organization** - Saves outputs in user-friendly locations by platform
- ⌨️ **Graceful Termination** - Handles Ctrl+C properly for a smooth user experience

## 🛠️ Installation

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sikandar-irfan/prd-generator.git
   ```

2. **Run the script**:

   **Windows**:
   ```powershell
   cd prd-generator
   python prd.py
   ```

   **Linux/macOS**:
   ```bash
   cd prd-generator
   python3 prd.py
   ```

   **Android (Termux)**:
   ```bash
   cd prd-generator
   python main.py
   ```

The script will automatically check for and install any required dependencies on first run.

## 🔑 API Key Setup

To use PRD Master, you'll need an OpenRouter API key:

1. Sign up at [OpenRouter](https://openrouter.ai/keys)
2. Create a new API key
3. The script will prompt you for the key on first run
4. Your key will be securely stored for future use

## 📖 Usage Guide

### Basic Usage

1. Run the script using the commands shown in the installation section
2. When prompted, select an AI model from the list
3. Enter your project details:
   - Project name
   - Short description
   - Key stakeholders
   - PRD complexity level
4. Review the generated PRD
5. Choose to save or refine the document

### PRD Complexity Levels

- **Standard**: Basic PRD structure with core sections
- **Comprehensive**: Detailed PRD with technical specifications
- **Advanced**: Full-scale PRD with code examples and deep technical details
- **Custom**: Define your own PRD structure with custom instructions

### Example Command

```powershell
python prd.py
```

## 📋 Example Output

PRD Master generates comprehensive documents that can include:

- Executive Summary & Vision
- Market Analysis & Opportunity
- Detailed User Personas
- Feature Breakdown (core, secondary, future)
- Technical Architecture & System Design
- API Specifications & Data Models
- Security Requirements
- Development Roadmap
- Risk Assessment
- Success Metrics & KPIs
- Implementation Code Examples
- Database Schema Designs
- UI/UX Specifications
- Testing Strategy
- And more...

## 📂 Output Locations

PRD Master automatically saves generated documents in platform-specific locations:

| Platform | Output Location |
|----------|----------------|
| Windows | `Desktop/PRD_Outputs/` |
| macOS/Linux | `~/PRD_Outputs/` |
| Android (Termux) | `/storage/shared/PRD_Outputs/` |

## 🔄 Advanced Features

### Custom Instructions

Choose the "Custom" complexity level to provide specific instructions about what you want included in your PRD.

### Technical Implementation

Enable "Include detailed technical implementation examples" to get code samples and specific technical guidance.

### Unrestricted Generation

For maximum creativity, enable "unrestricted generation mode" to remove standard content policies (use responsibly).

## 🛑 Terminating the Application

You can safely exit the application at any time by pressing `Ctrl+C`. The application will terminate gracefully without losing data.

## 📝 Logging

PRD Master keeps logs of generated documents in the output directory:

```
PRD_Outputs/prd_generator.log
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

For any queries, reach out to me at [sikandarirfan150162@gmail.com](mailto:sikandarirfan150162@gmail.com).
Project Link: [https://github.com/Sikandar-irfan/prd-generator](https://github.com/Sikandar-irfan/prd-generator)

---

<div align="center">
Made with ❤️ Sikandar Irfan to help build better products
</div>
