# Contributing to Demic Africa

We welcome contributions to our open-source travel AI projects!

## 🚀 How to Contribute
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📏 Development Standards
- **Python**: PEP 8 style guide + type hints
- **JavaScript/TypeScript**: Prettier defaults + ESLint
- **Documentation**: Add JSDoc/Python docstrings
- **Testing**: Add tests for new features (Jest/Pytest)

## 🧪 Testing
```bash
# Frontend tests
npm run test

# Backend tests  
pytest tests/

🤝 Code of Conduct
Be respectful, inclusive, and professional. We're building the future of African travel together.
❓ Questions?
Open an issue or contact: dev@demicafrica.com


---

### Option B: Via Terminal (If You Prefer Local Setup)

```bash
# Clone your new repo
git clone https://github.com/demicafrica/travel-ai-web.git
cd travel-ai-web

# Create professional folder structure
mkdir -p src/app src/components src/lib src/hooks public docs .github/workflows

# Create essential files (copy-paste the content from above)
touch SECURITY.md CONTRIBUTING.md

# Initialize Next.js (optional but recommended)
npx create-next-app@latest . --typescript --tailwind --app --src-dir --import-alias "@/*"

# Add and commit
git add .
git commit -m "chore: initialize professional repo structure"
git push origin main
