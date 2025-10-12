# MENACOSE Digital Garden 🌱🔥

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://menacose.org)
[![Built with Quartz](https://img.shields.io/badge/Built%20with-Quartz-purple)](https://quartz.jzhao.xyz)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Welcome to the MENACOSE Digital Garden!

## 🔥 About MENACOSE


## 🚀 Getting Started

### Viewing the Digital Garden

Visit the published site: **[https://menacose.org](https://menacose.org)**

### Editing Content with Obsidian

The content lives in the `menacose/` folder as an Obsidian vault. You can edit it using [Obsidian](https://obsidian.md) for the best experience with wiki-style linking and live preview.

#### Setting Up Obsidian

1. **Download and Install Obsidian**
   - Visit [https://obsidian.md](https://obsidian.md)
   - Download and install for your platform (Windows, macOS, or Linux)

2. **Clone the Repository**
   ```bash
   git clone https://github.com/menacose/menacose.github.io.git
   cd menacose.github.io
   ```

3. **Open Vault in Obsidian**
   - Launch Obsidian
   - Click "Open folder as vault"
   - Navigate to and select the `menacose/` folder
   - Obsidian will now open your vault

4. **Start Editing**
   - Edit any `.md` file in Obsidian
   - Use `[[Page Name]]` syntax for wiki-style links
   - Add images to the `Assets/` folder
   - Changes are automatically saved

5. **Preview Changes Locally**
   ```bash
   # In the repository root
   npx quartz build --serve -d menacose
   ```
   - Visit `http://localhost:8080` to see your changes

6. **Commit and Push**
   ```bash
   git add .
   git commit -m "Update documentation"
   git push
   ```
   - GitHub Actions will automatically rebuild and deploy your site

#### Obsidian Tips

- **Command Palette**: Press `Ctrl/Cmd + P` for quick actions
- **Graph View**: Click the graph icon to visualize page connections
- **Quick Switcher**: Press `Ctrl/Cmd + O` to quickly jump between pages
- **Link Autocomplete**: Type `[[` to see a list of pages to link to
- **Backlinks**: See which pages link to the current page in the right sidebar

### Local Development

This digital garden is built with [Quartz 4](https://quartz.jzhao.xyz), a fast, batteries-included static site generator for publishing Obsidian vaults.

#### Prerequisites
- Node.js v22+
- npm v10.9.2+

#### Setup

```bash
# Clone the repository
git clone https://github.com/menacose/menacose.github.io.git
cd menacose.github.io

# Install dependencies
npm install

# Start local development server
npx quartz build --serve

# Or use the convenience script
./start.sh
```

The site will be available at `http://localhost:8080`

#### Building for Production

```bash
# Build the static site
npx quartz build

# Output will be in the /public directory
```

## ✨ Features

- **📝 Wiki-style linking** - Seamless navigation between related concepts
- **🔍 Full-text search** - Find information quickly across all documents
- **📊 Interactive diagrams** - Visual system architectures and flows
- **🎨 Syntax highlighting** - Code examples with beautiful formatting
- **📱 Responsive design** - Works on desktop, tablet, and mobile
- **🌙 Dark mode** - Easy on the eyes for extended reading
- **🔗 Backlinks** - Discover connections between topics
- **📈 Graph view** - Visualize the knowledge network

### Content Guidelines

- Use Markdown with wiki-style `[[links]]` for cross-references
- Place images in `menacose/Assets/` directory
- Place templates in `menacose/Templates/` directory
- Maintain technical accuracy and include citations where appropriate
- Use appropriate frontmatter metadata for SEO and organization

### Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-improvement`)
3. Make your changes to files in the `menacose/` directory
4. Test locally with `npx quartz build --serve`
5. Commit your changes (`git commit -m 'Add amazing improvement'`)
6. Push to the branch (`git push origin feature/amazing-improvement`)
7. Open a Pull Request

## 🙏 Acknowledgments

- Built with [Quartz](https://quartz.jzhao.xyz) by [jackyzha0](https://github.com/jackyzha0)

## 📬 Contact

For questions, suggestions, or technical discussions:

- **Issues**: [GitHub Issues](https://github.com/menacose/menacose.github.io/issues)
- **Discussions**: [GitHub Discussions](https://github.com/menacose/menacose.github.io/discussions)


