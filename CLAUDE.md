# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# Content Creation System

## System Overview
This workspace transforms ideas into multi-format content:
1. Research → Long-form article → Platform-specific versions
2. All brand/voice guidelines live in @context/
3. Agents handle platform optimization

## Workflow Commands
- `/research [topic]` - Develop and refine ideas
- `/write` - Create comprehensive article
- Auto-generates: LinkedIn, Newsletter, Twitter/X, Podcast Q&A

## Context Architecture
Always reference these for consistency:
- @context/writing-examples.md - Real examples across platforms that demonstrate voice and style
- @context/research-sources.md - Priority newsletters and sources to check first during research

## Agent Specializations
- `linkedin-repurposer`: Professional networking optimization
- `newsletter-repurposer`: Email engagement specialist  
- `conversational-repurposer`: Social media posts and podcast Q&A scripts

## Development Guidelines
- Never duplicate context information - always reference source files
- Maintain consistency across all generated formats
- Each agent should specialize in their platform's unique requirements
- Content quality gates should validate against brand guidelines before output