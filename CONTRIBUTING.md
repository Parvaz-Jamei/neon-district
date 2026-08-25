# Contributing to Neon District

First of all, thank you for considering contributing!  
This project started as a solo experiment and grows better with community input.

## How to Contribute

### 1. Reporting Bugs
- Use GitHub Issues
- Include:
  - Browser + version
  - Device (desktop/mobile)
  - Steps to reproduce
  - Expected vs actual behavior
  - Screenshot or console output if possible

### 2. Suggesting Features
- Open an Issue with the `enhancement` label
- Explain the why (gameplay value) more than just the what

### 3. Code Contributions

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Test thoroughly (especially on mobile + different FPS)
5. Commit with clear messages
6. Push and open a Pull Request

### Code Style Guidelines

- Keep the single-file philosophy when possible
- Prefer readable, well-commented code over clever one-liners
- Performance matters — measure before optimizing
- Avoid introducing heavy external libraries
- Maintain the adaptive performance philosophy (FPS-aware systems)

### Areas We Especially Welcome Help

- Vehicle handling polish
- New districts / landmarks
- Additional side hustles / contracts
- Mobile touch UX improvements
- Accessibility
- Localization
- Documentation & examples

## Development Tips

- Open `index.html` directly or use a simple local server
- Use browser DevTools Performance tab
- Call `window.__DC95()` in console to inspect runtime state
- Keep particle and glow budgets under control

## Pull Request Process

1. Update documentation if needed
2. Make sure the game still loads and plays without console errors
3. Describe what you changed and why
4. Link related issues

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

---

Thank you for helping make Neon District bigger and better!  
— Parvaz Jamei
