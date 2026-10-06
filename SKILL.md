---
name: skills-curator
description: Expert guide for evaluating, reviewing, and curating quality skills and resources. Includes submission assessment, quality standards, and contribution best practices.
---

# Skills Curator

Use this skill when reviewing skill submissions, evaluating resource quality, maintaining a curated skills list, or helping contributors meet repository standards.

## What this skill does

This skill provides:
- Framework for assessing skill and resource quality
- Contribution review guidelines and templates
- Safety and trust evaluation criteria
- Best practices for repository maintenance
- Decision-making guidance for submissions
- Feedback writing and contributor communication

## Core principles

When reviewing submissions, apply these principles:

1. **Value-first approach** - Contributions should provide genuine utility
2. **Anti-promotion** - No commercial funnels or SaaS wrappers disguised as community resources
3. **Quality over quantity** - Better to have fewer excellent entries than many mediocre ones
4. **Community trust** - Curate to maintain high signal-to-noise ratio
5. **Transparency** - Clear feedback and consistent standards

## Submission assessment framework

Evaluate submissions across four dimensions:

### 1. Relevance (25% weight)
**Questions to ask:**
- Does this fit the repository's scope?
- Is it clearly related to skills, resources, or best practices?
- Would the target audience find it useful?

**Red flags:**
- Off-topic or tangential content
- Unclear connection to the repository theme

### 2. Quality (30% weight)
**Questions to ask:**
- Is the title clear and descriptive?
- Is the description accurate and useful?
- Is documentation or content understandable?
- Do links work? Is the project active/maintained?

**Red flags:**
- Vague or misleading titles
- Poor grammar or formatting
- Broken links or inactive projects
- Lack of documentation

### 3. Safety & Trust (25% weight)
**Questions to ask:**
- Is this a commercial product disguised as a resource?
- Does it require paid subscriptions to function?
- Is it a thin wrapper around a vendor service?
- Does it look like spam or low-effort?

**Red flags:**
- Heavy sales language or marketing speak
- Mandatory SaaS dependency
- Primarily designed to upsell a product
- No original value added

### 4. Value & Fit (20% weight)
**Questions to ask:**
- Would community members actually use this?
- Is it general enough or too narrow/niche?
- Does it improve the repository?
- Is it better than similar existing entries?

**Red flags:**
- Extremely narrow use case
- Duplicates existing content
- Trivial or easily implemented by users
- Only valuable to the submitter

## Review decision guide

### ✅ Accept
Accept when:
- Clearly relevant and well-scoped
- Provides genuine, valuable utility
- Not a promotional funnel
- Well-described and properly formatted
- Properly categorized
- Quality comparable or better than existing entries

### 🔄 Request Changes
Request changes when:
- Concept is good but execution needs improvement
- Description is vague and needs clarification
- Category placement is incorrect
- Formatting doesn't match repository standards
- Missing key information (links, documentation)
- Minor issues that can be easily fixed

### ❌ Reject
Reject when:
- Primarily a commercial funnel or sales pitch
- Not meaningfully useful or low-quality
- Appears to be spam or low-effort
- Outside repository scope
- Violates repository principles
- Requires paid SaaS to function
- No independent value

## How to identify red flags

### SaaS Wrapper Warning Signs
- "Sign up for [platform] to use this"
- "Requires API key from [commercial service]"
- "This integrates with our paid product"
- Value only exists through paid platform
- No standalone functionality

### Low-Effort Red Flags
- Single file with minimal content
- Trivial functionality
- No documentation or examples
- Barely tested
- No clear use case
- Appears hastily created

### Spam Red Flags
- Poor grammar and formatting
- Generic marketing language
- Multiple submissions from same source
- Clearly AI-generated without substance
- Misleading or exaggerated claims

## Writing quality list entries

### Format
```markdown
- **[Name](link)** - Clear, concise description of what it does
```

### Description guidelines
- **Length:** 1-2 sentences, max 150 characters
- **Focus:** Lead with primary use case
- **Tone:** Neutral, factual, no hype
- **Content:** What it does, not why it's amazing

### ✅ Good examples
- "Automated PDF text extraction and form processing"
- "Browser automation for UI testing and verification"
- "Convert documentation sites into reusable skills"
- "iOS app testing through device simulator automation"

### ❌ Weak examples
- "Powerful tool for doing things"
- "Revolutionary system that changes everything"
- "A thing for PDFs"
- "Incredible solution for automation"

## Feedback template for contributors

When requesting changes:

```
**Title:** [What the submission is about]

**Feedback:**
[1-2 sentences explaining the overall assessment]

**Strengths:**
- [Positive aspect 1]
- [Positive aspect 2]

**Areas for improvement:**
- [Specific issue and how to fix it]
- [Specific issue and how to fix it]
- [Specific issue and how to fix it]

**Next steps:**
[Clear action items for the contributor]
```

### Example
```
**Title:** PDF Analysis Skill Submission

**Feedback:**
This submission describes a useful skill, but the description could be clearer about what makes it different from existing PDF tools.

**Strengths:**
- Addresses a real need in the community
- Well-documented GitHub repository
- Active maintenance and updates

**Areas for improvement:**
- Description is too generic ("PDF manipulation") - specify unique features like OCR support
- Links to documentation would strengthen the submission
- Could mention example use cases

**Next steps:**
Please revise the description to highlight what makes this skill unique, and add a link to your documentation. Once updated, we'll be happy to review again.
```

## Handling specific scenarios

### Scenario: Generic SaaS Integration
**Situation:** Skill primarily calls a commercial API
**Response:** "This submission primarily integrates with a paid platform. To be included, please demonstrate meaningful standalone value beyond the API wrapper."

### Scenario: Very Niche/Narrow
**Situation:** Skill only useful for specific industry/company
**Response:** "This is valuable for a narrow use case, but may not appeal to our general audience. Consider sharing this in industry-specific forums."

### Scenario: Low-Effort/Trivial
**Situation:** Simple prompt or barely functional code
**Response:** "This could be implemented by users in minutes. For inclusion, we look for more substantial, reusable components with clear documentation."

### Scenario: Weak Description
**Situation:** Unclear what the submission actually does
**Response:** "The description doesn't clearly explain what this does or why someone would use it. Please provide specific examples of use cases and capabilities."

## Reviewer communication style

**Be:**
- ✅ Constructive and helpful
- ✅ Specific about issues and suggestions
- ✅ Respectful of the contributor's effort
- ✅ Clear about decision criteria
- ✅ Encouraging about future submissions

**Avoid:**
- ❌ One-word rejections ("No.")
- ❌ Vague criticism ("Not good.")
- ❌ Discouraging language
- ❌ Inconsistent standards
- ❌ Personal criticism

## Category guidance

**Official Skills** - From Anthropic's official repository
**Community Skills** - Created by community members
**Tools & Utilities** - Development tools, CLI utilities, converters
**Tutorials & Guides** - Step-by-step how-to content
**Articles & Blog Posts** - Published articles and research
**Documentation** - Reference material and guides

## Quality scoring

Use this mental model when evaluating:

| Score | Meaning | Action |
|-------|---------|--------|
| 8-10 | Strong fit | Accept |
| 6-7 | Good but needs work | Request changes |
| 4-5 | Questionable | Likely reject |
| 0-3 | Poor fit | Reject |

## Final principle

**This repository should be a trusted, high-signal resource.** Every entry represents a recommendation to the community. Curate with care, maintain consistent standards, and prioritize quality and usefulness over quantity.
