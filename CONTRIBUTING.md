# Contributing to RentItOut & TravelBuddy

Thank you for your interest in contributing! We welcome all contributions.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/RentItOut-Web-Engineering-Project.git`
3. Create a feature branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Push to your fork: `git push origin feature/your-feature-name`
6. Open a Pull Request

## Development Setup

### Prerequisites
- Node.js v16 or higher
- npm or yarn
- Git

### Installation

```bash
# Install dependencies for RentItOut
cd rentitout
npm install

# Install dependencies for TravelBuddy
cd ../travelbuddy
npm install
```

## Code Standards

- Use meaningful variable and function names
- Write comments for complex logic
- Follow consistent formatting
- Keep files focused on single responsibility
- Use ES6+ features

## Git Workflow

### Commit Messages
Use clear, descriptive commit messages:
```
✨ Add new feature
🐛 Fix bug description
📝 Update documentation
🔧 Configure tool
```

### Branch Naming
- Feature: `feature/description`
- Bug fix: `bugfix/description`
- Hotfix: `hotfix/description`
- Documentation: `docs/description`

## Pull Request Process

1. Update documentation with any new features
2. Add tests for new functionality
3. Ensure all tests pass: `npm test`
4. Update the README if needed
5. Provide a clear description of changes in PR

## Testing

Before submitting a PR, run:
```bash
npm run lint
npm test
npm run build
```

## Reporting Issues

When reporting bugs, please include:
- Description of the issue
- Steps to reproduce
- Expected behavior
- Actual behavior
- Your environment (OS, Node version, etc.)

## Questions?

Feel free to open an issue or contact the maintainers.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
