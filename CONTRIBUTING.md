# Contributing to Axie Infinity Offline

🎮 **Thank you for your interest in contributing to Axie Infinity Offline!** 

We're excited to welcome contributors from the gaming community, developers, designers, and Axie Infinity enthusiasts. This guide will help you get started.

## 🌟 Ways to Contribute

### 🐛 Bug Reports
Found a bug in the battle system or team builder? Help us fix it!
- Use the [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md)
- Include steps to reproduce the issue
- Provide screenshots or videos if possible
- Mention your operating system and app version

### 💡 Feature Requests
Have ideas for new features or improvements?
- Use the [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.md)
- Explain the use case and benefits
- Include mockups or examples if available
- Consider how it fits with the offline nature of the app

### 🎨 Art & Design Contributions
- **Custom Axie Designs**: Create new Axie skins or visual variations
- **UI/UX Improvements**: Enhance the user interface and experience
- **Icons & Graphics**: Design new icons, badges, or promotional materials
- **Animations**: Create smooth battle animations or transitions

### 🔧 Code Contributions
- **Bug Fixes**: Fix issues in the battle engine or UI
- **New Features**: Implement requested features or your own ideas
- **Performance**: Optimize battle calculations or rendering
- **Testing**: Add unit tests or integration tests

### 📝 Documentation
- **Tutorials**: Write guides for using advanced features
- **Strategy Guides**: Create battle strategy documentation
- **Translation**: Help localize the app for different languages
- **API Docs**: Document internal APIs for modders

## 🚀 Getting Started

### Development Setup

#### Prerequisites
- **Node.js** 18+ and npm
- **Git** for version control
- **Code Editor** (VS Code recommended)
- **Gaming Knowledge** of Axie Infinity mechanics (helpful but not required)

#### Local Development
```bash
# Clone the repository
git clone https://github.com/Axie-lnfinity/axie-infinity.git
cd axie-infinity

# Install dependencies
npm install

# Start development server
npm run dev

# Run tests
npm run test

# Build for production
npm run build
```

#### Project Structure
```
src/
├── components/          # React components
│   ├── battle/         # Battle system components  
│   ├── team-builder/   # Team building interface
│   └── ui/             # Shared UI components
├── game-engine/        # Core battle mechanics
│   ├── axies/          # Axie stats and abilities
│   ├── cards/          # Card database and effects
│   └── battle/         # Battle calculation logic
├── data/               # Game data and assets
├── utils/              # Helper functions
└── styles/             # CSS/SCSS styles
```

### 📋 Contribution Workflow

1. **Fork** the repository to your GitHub account
2. **Create** a new branch for your feature/fix:
   ```bash
   git checkout -b feature/awesome-new-feature
   # or
   git checkout -b fix/battle-bug-fix
   ```
3. **Make** your changes following our coding standards
4. **Test** your changes thoroughly
5. **Commit** with descriptive messages:
   ```bash
   git commit -m "feat: add custom tournament mode

   - Implement tournament bracket system
   - Add single/double elimination options  
   - Include tournament save/load functionality
   - Update UI for tournament management"
   ```
6. **Push** to your fork and **create a Pull Request**

### 📏 Code Standards

#### Code Style
- **TypeScript/JavaScript**: Use Prettier and ESLint configurations
- **React**: Functional components with hooks preferred
- **CSS**: Use CSS modules or styled-components
- **Naming**: Use descriptive, camelCase variable names

#### Battle System Guidelines
- **Accuracy**: Keep battle mechanics true to original Axie Infinity
- **Performance**: Optimize for smooth 60fps battles
- **Modularity**: Make systems extensible for future content
- **Testing**: Include unit tests for battle calculations

#### Commit Messages
Follow [Conventional Commits](https://conventionalcommits.org/) format:
- `feat:` for new features
- `fix:` for bug fixes  
- `docs:` for documentation
- `style:` for formatting changes
- `refactor:` for code restructuring
- `test:` for adding tests
- `chore:` for maintenance tasks

## 🎯 Specific Contribution Areas

### 🏆 Battle System
**Skills Needed**: Game logic, mathematics, JavaScript/TypeScript
- Implement new card effects and abilities
- Optimize damage calculation algorithms
- Add new battle modes (tournaments, custom rules)
- Create AI opponent behaviors

### 🎨 User Interface  
**Skills Needed**: React, CSS, UX design
- Design intuitive team building interface
- Create responsive layouts for different screen sizes
- Implement accessibility features
- Add smooth animations and transitions

### 📊 Analytics & Statistics
**Skills Needed**: Data analysis, visualization
- Build win rate tracking systems
- Create performance analytics dashboards
- Implement matchup analysis tools
- Design statistical charts and graphs

### 🤖 AI Development
**Skills Needed**: Machine learning, game AI
- Improve AI decision-making algorithms
- Create difficulty scaling systems
- Implement learning AI that adapts to player strategies
- Add personality-based AI behaviors

## 📞 Community & Communication

### Discord Community
Join our [Discord server](https://discord.gg/axie-offline) for:
- Real-time development discussions
- Community feedback and testing
- Collaboration on larger features
- Getting help with contributions

### Discussion Guidelines
- **Be Respectful**: Treat everyone with kindness and respect
- **Stay On Topic**: Keep discussions relevant to the project
- **Help Others**: Share knowledge and assist new contributors
- **Be Patient**: Remember we're all volunteers with different schedules

## 🏅 Recognition

### Contributor Benefits
- **Credits**: Your name in the contributors section
- **Discord Role**: Special contributor role in our Discord
- **Early Access**: Beta testing access to new features
- **Influence**: Voice in major project decisions

### Major Contributions
Significant contributions may receive:
- **Feature Naming**: Name a feature after yourself
- **Special Thanks**: Highlighted recognition in release notes
- **Maintainer Status**: Invitation to join the core team

## ⚡ Quick Start Checklist

- [ ] Read this contributing guide
- [ ] Set up development environment
- [ ] Join Discord community
- [ ] Look at [Good First Issues](https://github.com/Axie-lnfinity/axie-infinity/labels/good%20first%20issue)
- [ ] Fork repository and create feature branch
- [ ] Make your first contribution!

## 🆘 Getting Help

### Common Issues
- **Build Errors**: Check Node.js version and clean node_modules
- **Game Mechanics**: Reference official Axie Infinity documentation
- **UI Problems**: Test on multiple browsers and screen sizes
- **Git Issues**: Use GitHub's built-in tools or ask for help

### Where to Ask
1. **GitHub Issues**: For bugs and feature requests
2. **Discord**: For development questions and real-time help
3. **Discussions**: For broader project discussions
4. **Email**: For sensitive or private matters

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We're committed to making this a welcoming and inclusive community for everyone.

---

**Ready to contribute?** Start by exploring our [open issues](https://github.com/Axie-lnfinity/axie-infinity/issues) or join the conversation on [Discord](https://discord.gg/axie-offline)!

🎮 **Let's build the best offline Axie Infinity experience together!** 