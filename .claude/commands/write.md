# Write Command

Use this command to create comprehensive long-form articles.

## Usage
`/write [topic or research brief]`

## What This Command Does
1. Creates a complete, well-structured article
2. Ensures consistent voice and style throughout
3. Includes compelling introduction and conclusion
4. Integrates supporting examples and data
5. Optimizes for readability and engagement

## Process
- **Research Integration**: Weave in current trends, fresh data, and timely examples
- **Competitive Context**: Reference (and improve on) existing perspectives
- **Structure with Surprise**: Build article flow that challenges conventional wisdom
- **Evidence Integration**: Include recent studies, expert insights, real-world examples
- **Voice Authenticity**: Ensure your unique perspective comes through clearly
- **Future-Forward**: Connect current insights to emerging trends or implications

## References
Always check @context/writing-examples.md for voice and style consistency.

## Output
Provides a complete article ready for:
- Direct publication
- Repurposing by specialized agents
- Further editing and refinement

The article should serve as the master content from which all platform-specific versions are derived.

## File Management
After completing the article, automatically save the draft to:
- **File Location**: `drafts/article-[topic-slug]-[YYYY-MM-DD].md`
- **File Format**: Markdown with title, headers, and formatted content
- **Naming Convention**: Use lowercase, hyphenated topic slug and current date

Example: `drafts/article-remote-work-productivity-2024-01-15.md`

This ensures all article drafts are systematically organized and available for future reference, editing, or repurposing.

## Automatic Multi-Platform Repurposing
After saving the main article, immediately execute all platform-specific agents to create optimized versions:

### 1. LinkedIn Agent Execution
- **Agent**: `linkedin-repurposer`
- **Input**: Full article content
- **Output File**: `drafts/linkedin-[topic-slug]-[YYYY-MM-DD].md`
- **Purpose**: Professional networking post with engagement hooks

### 2. Newsletter Agent Execution
- **Agent**: `newsletter-repurposer` 
- **Input**: Full article content
- **Output File**: `drafts/newsletter-[topic-slug]-[YYYY-MM-DD].md`
- **Purpose**: Email-optimized content with compelling subject lines

### 3. Conversational Agent Execution
- **Agent**: `conversational-repurposer`
- **Input**: Full article content
- **Output File**: `drafts/social-[topic-slug]-[YYYY-MM-DD].md`
- **Purpose**: Social media posts and podcast Q&A scripts

### Workflow Automation
1. **Article Completion**: Main article saved to drafts folder
2. **Agent Cascade**: All three agents process the article simultaneously
3. **File Organization**: Each platform version saved with consistent naming
4. **Update Tracking**: Any changes to main article trigger regeneration of all platform versions

This creates a complete content suite from a single `/write` command, ensuring consistency across all platforms while optimizing for each platform's specific requirements.