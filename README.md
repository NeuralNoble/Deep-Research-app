# 🔍 Deep Research Assistant

An AI-powered comprehensive research tool that automatically plans, executes, and synthesizes web and video searches to generate detailed research reports on any topic.

## 🌟 Features

- **Intelligent Search Planning**: AI agent creates strategic search plans with diverse query types
- **Multi-Modal Research**: Combines web search and video content analysis
- **Parallel Processing**: Executes multiple searches simultaneously for efficiency
- **Comprehensive Reports**: Generates detailed markdown reports (2500-3000+ words)
- **Video Curation**: Identifies high-quality educational videos with expert filtering
- **Interactive Interface**: Both Streamlit web app and Jupyter notebook interfaces


## 🎯 How It Works

### 1. Research Planning
The planner agent analyzes your query and creates a strategic search plan covering different dimensions:
- **Tutorial/How-to**: Implementation guides and tutorials
- **Technical/Academic**: Specifications and academic content
- **Comparison/Evaluation**: Comparative analyses
- **Practical/Application**: Real-world use cases
- **Expert Opinions**: Thought leader perspectives

### 2. Multi-Modal Search Execution
- **Web Search**: Searches multiple sources for comprehensive information
- **Video Search**: Finds high-quality educational videos (10+ minutes, expert channels)
- **Parallel Processing**: All searches run simultaneously for speed

### 3. Intelligent Synthesis
The writer agent creates comprehensive reports featuring:
- Executive summary and key insights
- Structured sections with proper markdown formatting
- Curated video recommendations
- Follow-up research questions
- 2500-3000+ word comprehensive analysis

## 🔧 Configuration

### Search Filtering
- Videos under 3 minutes are automatically filtered out
- Prioritizes content from reputable educational channels
- Recent content (last 3 months) gets highest priority
- Technical topics include code examples and implementation details

### Report Customization
Reports include:
- Executive summary
- Table of contents
- Detailed analysis sections
- Recommended videos with descriptions
- Key insights and takeaways
- Suggested follow-up questions

## 📋 Example Usage

```python
# Research any topic
query = "Latest AI Agent frameworks in 2025"

# The system will:
# 1. Plan 4-7 strategic searches
# 2. Execute web and video searches in parallel
# 3. Generate a comprehensive report
# 4. Save as markdown file

# Output: research_report.md with 2500+ words of analysis
```



### Agent Architecture

1. **Planner Agent**: Creates strategic search plans
2. **Web Search Agent**: Analyzes web content with source evaluation
3. **Video Search Agent**: Curates high-quality educational videos
4. **Writer Agent**: Synthesizes findings into comprehensive reports


## ⚠️ Notes

- Ensure you have sufficient API credits for OpenAI and Serper
- Large research topics may consume more API calls
- Video search prioritizes educational content over entertainment
- Reports are saved as `research_report.md` in the project directory


