# Claude Code Writing System

## What This Template Does for Claude Code Users

**This template turns Claude Code into your personal content creation system** - a smart writing assistant that learns your unique voice and automatically adapts your ideas for every platform you use.

Think of it as having a team of specialized writers who all know exactly how you write and what your audience expects. You provide the idea, and the system handles everything from research to platform-specific optimization.

## How It Enables You to Build a Writing System

The template provides a complete, ready-to-use architecture that works immediately:

1. **Voice Learning**: Add a few examples of your existing writing, and Claude learns your style
2. **Smart Research**: Tell it your favorite sources, and it checks them first for relevant insights
3. **Automated Workflow**: Simple commands like `/research` and `/write` handle the entire process
4. **Platform Specialists**: Built-in agents that know exactly how to optimize for LinkedIn, newsletters, and social media

No coding required. No complex setup. Just add your examples and start writing.

## The Magic Workflow

1. **Research Once**: `/research [your topic]` finds trends, data, and unique angles from your trusted sources
2. **Write Once**: `/write` creates a comprehensive article in your voice
3. **Publish Everywhere**: Specialized agents automatically transform your article into:
   - LinkedIn posts with professional hooks and engagement drivers
   - Newsletter sections with compelling subject lines and personal touches
   - Twitter threads that maximize shares and conversations
   - Podcast Q&A scripts that sound naturally conversational

**Why This Matters:**
- **Time Savings**: What used to take hours (adapting content for each platform) now takes seconds
- **Consistency**: Your voice stays authentic across all platforms
- **Quality**: Each piece is optimized for its specific platform's best practices
- **Learning System**: The more you use it, the better it understands your style

**Perfect For:** Content creators, professionals building thought leadership, newsletter writers, or anyone tired of manually reformatting content for different audiences.

## Quick Start

### 1. Get This Template
1. Go to this repository on GitHub
2. Click the green "Use this template" button (or fork the repository)
3. Name your new repository (e.g. "my-writing-workspace")
4. Clone it to your computer:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   ```

### 2. Install Claude Code

**Mac:**
```bash
# Install via Homebrew
brew install anthropics/claude/claude-code

# Or download directly
curl -fsSL https://claude.ai/install.sh | sh
```

**Windows:**
1. Download the installer from [claude.ai/code](https://claude.ai/code)
2. Run the installer and follow the prompts
3. Open Command Prompt or PowerShell

**Setup:**
```bash
# Login to your Anthropic account
claude auth login

# Navigate to your writing workspace
cd path/to/your/writing-workspace

# Start Claude Code
claude
```

### 3. Customize Your Workspace

**Add Your Writing Examples** (Most Important!)
1. Open `context/writing-examples.md`
2. Add 2-3 examples of your actual posts from each platform
3. This teaches Claude your voice and style

**Add Your Research Sources**
1. Open `context/research-sources.md` 
2. Add your favorite newsletters and news sources
3. Claude will check these first during research

### 4. Ready to Write!

The system is now ready. No additional setup needed - the commands and agents are built-in.

## Writing Workflow

### Step 1: Research Your Topic
```
/research sustainable fashion trends
```

Claude will:
- Check your priority sources first
- Find current trends and data
- Identify gaps in existing coverage
- Suggest unique angles
- Provide a research brief

### Step 2: Write Your Article
```
/write [paste the research brief or topic]
```

Claude will:
- Create a comprehensive 800-1500 word article
- Use current data and trends
- Match your voice from examples
- Structure for readability

### Step 3: Repurpose for Each Platform

**LinkedIn Post:**
```
Use the linkedin-repurposer agent on this article: [paste article]
```

**Newsletter Section:**
```
Use the newsletter-repurposer agent on this article: [paste article]
```

**Social Media + Podcast Q&A:**
```
Use the conversational-repurposer agent for Twitter posts: [paste article]
```

## Complete Example Walkthrough

Let's say you want to write about "remote work productivity":

### 1. Research Phase
**You:** `/research remote work productivity tips for 2024`

**Claude responds with:**
- Current trends (hybrid work, AI tools, async communication)
- Gap analysis (missing: mental health aspect)
- Unique angle (productivity isn't about time management anymore)
- Supporting data from recent studies
- Platform-specific hooks

### 2. Writing Phase
**You:** `/write` *[paste the research brief]*

**Claude creates:**
A 1,200-word article titled "Why Productivity Advice is Failing Remote Workers (And What Actually Works)" with:
- Hook: Traditional productivity advice assumes office environment
- 3 main sections: Environment design, Energy management, Social connection
- Current data and examples
- Your authentic voice and perspective

### 3. Repurposing Phase

**LinkedIn Version:**
**You:** Use the `linkedin-repurposer` agent on this article

**Claude creates:**
```
Most productivity advice for remote workers is still stuck in 2019.

Here's what actually works:

❌ Time blocking (ignores energy rhythms)
✅ Energy blocking (work with your natural peaks)

❌ Separate home office (not realistic for many)  
✅ Transition rituals (same psychological effect)

❌ More meetings for connection
✅ Async check-ins with intention

The biggest shift: Productivity isn't about managing time anymore.
It's about managing energy and attention in a distributed world.

What's your best remote productivity hack that no one talks about?

#RemoteWork #Productivity #WorkFromHome #FutureOfWork
```

**Newsletter Version:**
**You:** Use the `newsletter-repurposer` agent on this article

**Claude creates:**
```
Subject: The productivity advice that's failing you
Preview: Most remote work tips assume we're still in offices...

Hey [Name],

I've been thinking about why so much productivity advice feels useless these days.

Most of it assumes we're still working in offices with predictable schedules and endless coffee refills.

But remote work changed everything...

[Full newsletter section with personal tone, scannable format, clear CTA]
```

**Social Media Version:**
**You:** Use the `conversational-repurposer` agent for social media on this article

**Claude creates:**
```
Platform: Twitter/X

Hot take: "Time blocking" doesn't work for remote workers.

Try "energy blocking" instead.

Schedule deep work when YOU naturally focus best, not when your calendar says you should.

Game changer.
```

## Tips for Success

1. **Start with examples**: The better your writing examples, the better Claude matches your voice
2. **Be specific in research**: "social media marketing" vs "TikTok marketing for B2B SaaS"  
3. **Iterate on repurposing**: Ask Claude to make posts shorter, longer, or adjust tone
4. **Save good outputs**: Copy successful posts back to your examples file

## File Structure

```
writing-workspace/
├── README.md                   # This guide
├── CLAUDE.md                  # Instructions for Claude
├── .claude/
│   ├── agents/               # Platform specialists
│   └── commands/            # Research & writing workflows
├── context/
│   ├── writing-examples.md  # Your voice samples
│   └── research-sources.md  # Priority sources
└── drafts/                  # Your work in progress
```

## Troubleshooting

**"Claude doesn't sound like me"**
→ Add more diverse writing examples to `context/writing-examples.md`

**"Research feels generic"**  
→ Add specific sources to `context/research-sources.md`

**"Posts are too long/short"**
→ Give Claude specific feedback: "Make this 50% shorter" or "Add more detail"

**Need help?**
→ Type `/help` in Claude Code for assistance

## What's Next?

Once you're comfortable with the basic workflow:
- Experiment with different research angles
- Try combining multiple articles into series
- Use Claude to analyze what content performs best
- Adapt the agents for other platforms you use

Happy writing! 🚀

## Contributing

We welcome contributions that improve the writing quality and research capabilities of this template! See our [Contributing Guidelines](CONTRIBUTING.md) for details on:

- How to improve agent prompts and workflows
- Testing requirements and submission process  
- What kinds of contributions we're looking for

Help make this system better for content creators everywhere!