# Contributing to Claude Code Writing System

We welcome contributions that improve the writing quality and research capabilities of this template! This project helps content creators build personalized AI writing systems, and your expertise can make it work better for everyone.

## 🎯 Current Priority Areas

We're currently focused on improvements in these key areas:

### 1. **Agent Prompt Improvements**
- LinkedIn agent optimization (hooks, engagement, professional tone)
- Newsletter agent refinement (subject lines, personal voice, structure)
- Conversational agent enhancement (social media posts, podcast Q&A scripts)

### 2. **Research & Writing Workflow**
- Improving the `/research` command effectiveness
- Enhancing the `/write` command output quality
- Suggesting high-quality default research sources
- Streamlining the research-to-publication pipeline

## 📋 Contribution Requirements

### Before You Submit
All contributions must include:

1. **Before/After Comparison**: Test your changes against real content
2. **Output Examples**: Show actual generated content with your improvements
3. **Brief Explanation**: 2-3 sentences on why the "after" version is better
4. **Testing Evidence**: Demonstrate the improvement works consistently

### Example Contribution Format
```
## Improvement: LinkedIn Agent Hook Generation

**Before**: Generic opening lines that don't engage
**After**: Compelling hooks that drive comments and shares

**Test Results**:
- Original prompt generated: "Here's an interesting trend in remote work..."
- Improved prompt generated: "Most productivity advice for remote workers is still stuck in 2019."

**Why Better**: The improved version uses a contrarian hook that immediately challenges assumptions, leading to higher engagement rates.
```

## 🚀 How to Contribute

### Small Improvements (Preferred)
Focus on specific, targeted enhancements:
- Better LinkedIn post hooks
- More engaging newsletter subject lines
- Improved research source prioritization
- Enhanced voice consistency in outputs

### Larger Changes
If you have ideas for significant workflow redesigns or major new features:
1. **Discuss first**: Email info@womendefiningai.com before implementing
2. **Get approval**: Wait for green light before spending time on large changes
3. **Break it down**: Consider splitting large ideas into smaller contributions

## 🔄 Contribution Process

### 1. Set Up Your Environment
```bash
# Fork this repository on GitHub
# Clone your fork
git clone https://github.com/YOUR-USERNAME/claudecode-writertemplate.git
cd claudecode-writertemplate

# Install Claude Code if you haven't already
# Follow the README instructions for setup
```

### 2. Make Your Improvements
- **For Agent Prompts**: Edit files in `.claude/agents/`
- **For Commands**: Modify files in `.claude/commands/`
- **For Research Sources**: Update `context/research-sources.md`

### 3. Test Thoroughly
- Run your improved agents/commands on real content
- Document the before/after results
- Verify improvements are consistent across different topics

### 4. Submit Your Contribution
```bash
# Create a new branch
git checkout -b improve-linkedin-agent

# Make your changes and commit
git add .
git commit -m "Improve LinkedIn agent hook generation"

# Push and create pull request
git push origin improve-linkedin-agent
```

### 5. Pull Request Requirements
Your PR description must include:
- **What you changed** (specific agent/command/workflow)
- **Why you changed it** (what problem it solves)
- **Before/after examples** (real output comparisons)
- **Testing details** (how you verified the improvement)

## 🎨 Quality Standards

### Good Contributions
✅ Solve specific, real problems users face  
✅ Include concrete before/after examples  
✅ Improve output quality measurably  
✅ Maintain consistency with the overall system  
✅ Are thoroughly tested on multiple topics  

### What We Don't Need
❌ Generic writing examples (users should customize with their own)  
❌ Untested prompt changes  
❌ Major architectural changes without prior discussion  
❌ Platform agents for niche platforms (focus on major ones first)  
❌ Changes that make the system more complex without clear benefit  

## 📝 Review Process

1. **Submit**: Create pull request with all required documentation
2. **Review**: Maintainer will test your changes and provide feedback
3. **Iterate**: Address any requested changes
4. **Merge**: Approved changes get merged and acknowledged

**Review Timeline**: Expect feedback within 1 week of submission.

## 🏆 Recognition

Contributors will be acknowledged in our **Contributors** section of the README with:
- GitHub username
- Brief description of their contribution
- Link to their profile or project (optional)

## 💡 Contribution Ideas

Not sure where to start? Here are specific areas that need attention:

### Agent Improvements
- LinkedIn: Better engagement questions, industry-specific hooks
- Newsletter: More compelling subject line formulas, better CTAs
- Social Media: Platform-specific optimization, trending format adoption

### Research Enhancements
- Industry-specific source recommendations
- Better trend identification in research phase
- More actionable research summaries

### Workflow Optimizations
- Faster research-to-writing pipeline
- Better voice consistency across outputs
- More intuitive command interfaces

## 🤝 Getting Help

- **Questions about contributing?** Email info@womendefiningai.com
- **Technical issues?** Create a GitHub issue
- **Want to discuss ideas?** Start a discussion in the repository

## 📜 Code of Conduct

- Be respectful and constructive in all interactions
- Focus on improving the system for all users
- Provide helpful, actionable feedback
- Keep discussions focused on content quality and user experience

---

Thank you for helping make the Claude Code Writing System better for content creators everywhere! 🚀