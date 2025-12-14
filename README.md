# GitGrade - AI-Powered GitHub Repository Evaluator

**Hackathon**: GitGrade Hackathon by UnsaidTalks  
**Theme**: AI + Code Analysis + Developer Profiling

## 🎯 Project Overview

GitGrade is an intelligent system that evaluates GitHub repositories and converts them into:
1. A meaningful **SCORE/RATING** (0-100, Bronze/Silver/Gold)
2. A concise **WRITTEN SUMMARY** of strengths and weaknesses
3. A **PERSONALIZED IMPROVEMENT ROADMAP** with actionable steps

## 🚀 Live Demo

[Deploy the application and add link here]

## ✨ Features

### Multi-Dimensional Evaluation
- **Code Quality & Structure** (15 points)
- **Documentation Quality** (15 points)
- **Development Consistency** (15 points)
- **Commit Message Quality** (10 points)
- **Test Coverage** (20 points)
- **CI/CD Implementation** (10 points)
- **Real-world Relevance** (15 points)

### Intelligent Analysis
- Fetches repository data via GitHub API (no cloning)
- Analyzes file structure, commit history, and documentation
- Detects test files, CI/CD configs, and best practices
- Provides transparent, explainable scoring

### AI-Generated Outputs
- Honest, constructive summary (mentor-like tone)
- Personalized roadmap with priority-based tasks
- Actionable improvement steps

## 🛠️ Technology Stack

- **Frontend**: React with Tailwind CSS
- **API**: GitHub REST API
- **Deployment**: [Vercel/Netlify/Your choice]
- **Styling**: Modern gradient UI with dark theme

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gitgrade-evaluator.git
cd gitgrade-evaluator
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Open browser to `http://localhost:3000`

## 🎯 How It Works

### 1. Input
User provides a public GitHub repository URL:
```
https://github.com/username/repository-name
```

### 2. Data Collection
System fetches via GitHub API:
- Repository metadata (stars, forks, description)
- Commit history (last 100 commits)
- File structure (recursive tree)
- README content

### 3. Analysis & Scoring

**Transparent Rule-Based System:**

| Criteria | Max Points | Evaluation Method |
|----------|-----------|-------------------|
| README | 15 | Length and quality check |
| Structure | 15 | Folder organization, config files |
| Commits | 15 | Commit count and consistency |
| Messages | 10 | Meaningful commit message ratio |
| Tests | 20 | Test file detection |
| CI/CD | 10 | Pipeline configuration detection |
| Relevance | 15 | Description and community metrics |

### 4. Output Generation

**Score/Rating:**
- 0-59: Beginner (Bronze)
- 60-79: Intermediate (Silver)
- 80-100: Advanced (Gold)

**Summary:**
Generated based on score breakdown, highlighting top strengths and key weaknesses.

**Roadmap:**
Prioritized tasks (High/Medium/Low) with specific, actionable guidance.

## 📊 Example Output

**Input:**
```
https://github.com/example/todo-app
```

**Output:**
```
Score: 78/100 (Silver - Intermediate)

Summary: Strong well-organized structure, consistent development 
activity; needs improvement in testing, CI/CD setup.

Roadmap:
• [High] Implement comprehensive testing
  Add unit tests, integration tests, aim for >70% coverage

• [High] Enhance README documentation
  Add installation steps, usage examples, contribution guidelines

• [Medium] Set up CI/CD pipeline
  Configure GitHub Actions for automated testing and deployment

• [Medium] Improve commit message quality
  Use conventional commits format (feat:, fix:, docs:)
```

## 🎨 Key Design Decisions

### 1. No Repository Cloning
- Uses GitHub API for all data
- Faster analysis
- No storage requirements
- Respects rate limits

### 2. Transparent Scoring
- Every point explained
- Clear breakdown shown to users
- Rule-based, not black-box

### 3. Honest Feedback
- No sugar-coating weaknesses
- Constructive mentor tone
- Focuses on improvement

### 4. Actionable Roadmap
- Specific, implementable tasks
- Priority-based organization
- Detailed guidance for each step

## 🚀 Deployment

### Option 1: Vercel (Recommended)
```bash
npm install -g vercel
vercel
```

### Option 2: Netlify
```bash
npm run build
# Deploy dist folder via Netlify UI
```

### Option 3: GitHub Pages
```bash
npm run build
# Push dist folder to gh-pages branch
```

## 🔒 API Rate Limits

GitHub API allows:
- **Unauthenticated**: 60 requests/hour
- **Authenticated**: 5,000 requests/hour

For production, consider adding GitHub OAuth token.

## 🎓 Educational Value

This tool helps developers:
- Understand repository quality metrics
- Learn best practices in software development
- Get actionable feedback for improvement
- Build better portfolios

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 📝 License

MIT License - feel free to use for your projects!

## 👨‍💻 Author

[Your Name]  
Hackathon: GitGrade by UnsaidTalks

## 🙏 Acknowledgments

- GitHub API for repository data
- UnsaidTalks for organizing the hackathon
- React and Tailwind CSS communities

---


