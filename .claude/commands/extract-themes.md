# Extract Themes Command

Use this command to analyze raw notes and identify coherent themes, patterns, and content opportunities.

## Usage
`/extract-themes`

## What This Command Does
1. Analyzes all files in the `/rawnotes` folder
2. Identifies recurring themes and patterns across notes
3. Connects disparate ideas into coherent narratives
4. Surfaces the user's unique perspective and voice
5. Creates structured content briefs ready for development

## Process
- **Note Discovery**: Scan all files in `/rawnotes` for content and context
- **Pattern Recognition**: Identify recurring topics, themes, and interests
- **Connection Mapping**: Link related ideas across different notes and timeframes
- **Voice Analysis**: Extract the user's distinctive perspective and angle on topics
- **Narrative Threading**: Weave scattered thoughts into coherent storylines
- **Gap Identification**: Find missing pieces needed to complete ideas
- **Opportunity Spotting**: Identify which themes are ready for full development

## Output
Provides a structured theme analysis with:
- **Core Themes**: 3-5 main patterns identified across all notes
- **Unique Angles**: Your distinctive perspective on each theme
- **Content Opportunities**: Which themes are ready for article development
- **Supporting Evidence**: Quotes and insights from your raw notes
- **Missing Pieces**: What additional research or development each theme needs
- **Platform Potential**: How each theme could work across LinkedIn, newsletter, social
- **Next Actions**: Clear steps to develop themes into full content

## Integration Points
The output is designed to feed directly into:
- **LinkedIn Repurposing**: Use `linkedin-repurposer` agent on developed themes
- **Research Command**: Feed theme briefs into `/research` for deeper development
- **Writing Workflow**: Use themes as starting points for `/write` command

## File Management
After completing the analysis, automatically save results to:
- **File Location**: `research/theme-analysis-[YYYY-MM-DD].md`
- **File Format**: Markdown with clear theme sections and actionable next steps
- **Cross-Reference**: Include links back to original raw note files

Example: `research/theme-analysis-2024-01-15.md`

This ensures theme analyses are preserved alongside research briefs for comprehensive content planning.