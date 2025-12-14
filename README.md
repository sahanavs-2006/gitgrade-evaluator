# GitGrade - AI-Powered GitHub Repository Evaluator

**Hackathon**: GitGrade Hackathon by UnsaidTalks  
**Theme**: AI + Code Analysis + Developer Profiling

## 🎯 Project Overview

GitGrade is an intelligent system that evaluates GitHub repositories and provides:
1. A meaningful **SCORE/RATING** (0-100, Bronze/Silver/Gold)
2. A concise **WRITTEN SUMMARY** of strengths and weaknesses
3. A **PERSONALIZED IMPROVEMENT ROADMAP** with actionable steps

## 🚀 Live Demo

🔗 **Try it here**: [GitGrade Evaluator](https://sahanavs-2006.github.io/gitgrade-evaluator/)

## ✨ Features

### Multi-Dimensional Evaluation (100 Points)
- **README Quality** (15 points) - Documentation depth
- **Project Structure** (15 points) - Folder organization
- **Commit Consistency** (15 points) - Development activity
- **Commit Messages** (10 points) - Message quality
- **Test Coverage** (20 points) - Testing implementation
- **CI/CD Setup** (10 points) - Automation pipelines
- **Real-world Relevance** (15 points) - Project impact

### Intelligent Analysis
- Fetches data via GitHub API (no cloning needed)
- Analyzes file structure, commits, and documentation
- Provides transparent, explainable scoring
- Generates AI-powered summaries and roadmaps

### Beautiful Interface
- Modern gradient design
- Real-time analysis
- Visual score breakdowns
- Priority-based improvement suggestions

## 🛠️ Technology Stack

- **Frontend**: React (vanilla JavaScript)
- **Styling**: Custom CSS with modern gradients
- **API**: GitHub REST API
- **Deployment**: GitHub Pages

## 📊 How It Works

### 1. Input
User provides a public GitHub repository URL

### 2. Data Collection
System fetches via GitHub API:
- Repository metadata
- Commit history (last 100 commits)
- File structure (recursive tree)
- README content

### 3. Analysis & Scoring

**Transparent Rule-Based System:**

| Criteria | Points | What We Check |
|----------|--------|---------------|
| README | 15 | Length and quality |
| Structure | 15 | Folder organization, config files |
| Commits | 15 | Commit count and consistency |
| Messages | 10 | Meaningful commit messages |
| Tests | 20 | Test file detection |
| CI/CD | 10 | Pipeline configuration |
| Relevance | 15 | Description and community metrics |

### 4. Output Generation

**Score/Rating:**
- 0-59: Beginner (Bronze 🥉)
- 60-79: Intermediate (Silver 🥈)
- 80-100: Advanced (Gold 🥇)

**Summary:**
AI-generated honest feedback highlighting strengths and weaknesses

**Roadmap:**
Priority-based tasks (High/Medium/Low) with specific guidance

## 💡 Example

**Input:**
```
https://github.com/facebook/react
```

**Output:**
```
Score: 85/100 (Gold - Advanced)

Summary: Strong well-organized structure, consistent development 
activity, comprehensive testing; needs minor improvements in 
documentation structure.

Roadmap:
- [Low] Add advanced features
  Consider adding monitoring, logging, or performance optimizations
```

## 🚀 Usage

1. Open the [GitGrade Evaluator](https://sahanavs-2006.github.io/gitgrade-evaluator/)
2. Enter any public GitHub repository URL
3. Click "Evaluate"
4. View your score, summary, and personalized roadmap

## 🎓 Key Design Decisions

### 1. No Repository Cloning
- Uses GitHub API for all data
- Faster and more efficient
- No storage requirements

### 2. Transparent Scoring
- Every point is explained
- Clear breakdown shown to users
- Rule-based, not black-box AI

### 3. Honest Feedback
- No sugar-coating weaknesses
- Constructive mentor-like tone
- Focus on actionable improvements

### 4. Beginner-Friendly
- Single HTML file
- No build process required
- Easy to understand and modify

## 📦 Installation (For Local Development)

1. Clone the repository:
```bash
git clone https://github.com/sahanavs-2006/gitgrade-evaluator.git
```

2. Open `index.html` in your browser

That's it! No dependencies or build process needed.

## 🔒 API Rate Limits

GitHub API allows:
- **Unauthenticated**: 60 requests/hour
- **Authenticated**: 5,000 requests/hour

For production use with high traffic, consider adding GitHub OAuth.

## 🎯 Hackathon Requirements Met

✅ **Score/Rating System** - 0-100 with Bronze/Silver/Gold badges  
✅ **Written Summary** - AI-generated, honest, mentor-like feedback  
✅ **Personalized Roadmap** - Priority-based actionable steps  
✅ **Multi-dimensional Evaluation** - 7 key metrics analyzed  
✅ **Real Repository Data** - All analysis based on actual GitHub API data  
✅ **Transparent Scoring** - Every point explained with reasoning  
✅ **Working System** - Fully functional end-to-end solution  

## 👨‍💻 Author

**Sahanav S**  
Hackathon: GitGrade by UnsaidTalks  
Submission: December 2024

## 📝 License

MIT License - Free to use and modify

## 🙏 Acknowledgments

- GitHub API for repository data
- UnsaidTalks for organizing the hackathon
- React community for excellent documentation

---

**Live Demo**: https://sahanavs-2006.github.io/gitgrade-evaluator/  
**Repository**: https://github.com/sahanavs-2006/gitgrade-evaluator
