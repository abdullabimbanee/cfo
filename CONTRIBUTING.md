# Contributing to CFO Helper

Thank you for your interest in contributing to CFO Helper! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites
- Node.js 16.0 or higher
- npm or yarn
- Git
- Basic knowledge of React, TypeScript, and Tailwind CSS

### Development Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/CFO-Helper.git
   cd CFO-Helper
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create environment file:
   ```bash
   cp .env.example .env
   ```
   Add your Clerk publishable key to `.env`

5. Start development server:
   ```bash
   npm run dev
   ```

## 📝 Development Guidelines

### Code Style
- Use TypeScript for all new files
- Follow existing naming conventions
- Use Tailwind CSS for styling
- Keep components small and focused
- Add proper error handling

### Commit Messages
Use conventional commits:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `style:` for formatting changes
- `refactor:` for code refactoring
- `test:` for adding tests

Example: `feat: add circular slider component`

### Branch Naming
- `feature/description` for new features
- `fix/description` for bug fixes
- `docs/description` for documentation updates

## 🔧 Project Structure

```
src/
├── components/          # React components
├── types/              # TypeScript type definitions
├── utils/              # Utility functions
└── App.tsx             # Main application component
```

### Key Components
- `AdvancedInputPanel` - Modern input controls
- `OnboardingFlow` - User registration flow
- `ResultsPanel` - Charts and analytics
- `Header` - Navigation and user profile

## 🧪 Testing

```bash
# Run type checking
npm run type-check

# Build project
npm run build

# Preview build
npm run preview
```

## 📋 Contribution Process

1. **Choose an Issue**: Look at open issues or create a new one
2. **Create Branch**: `git checkout -b feature/your-feature`
3. **Make Changes**: Implement your feature/fix
4. **Test**: Ensure everything works correctly
5. **Commit**: Use conventional commit format
6. **Push**: `git push origin feature/your-feature`
7. **Pull Request**: Create PR with detailed description

## 🐛 Bug Reports

When reporting bugs, please include:
- Clear bug description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)
- Browser/OS information

## 💡 Feature Requests

For new features:
- Describe the feature clearly
- Explain the use case
- Consider implementation complexity
- Check if similar feature exists

## 📚 Resources

- [React Documentation](https://reactjs.org/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Clerk Documentation](https://clerk.com/docs)

## ❓ Questions

If you have questions:
- Check existing issues and discussions
- Create a new issue with the "question" label
- Join our community discussions

Thank you for contributing to CFO Helper! 🚀