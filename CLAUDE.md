# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static educational website (northwesthillsatx.com) designed to inform Austin residents about their rights regarding illegal commercial event venues operating in residential neighborhoods. The site serves as both a specific resource for Northwest Hills residents and a general educational tool for residents throughout Austin.

## Architecture

### Site Structure
- **`index.html`** - Main Northwest Hills case study (~1,100 lines)
  - Detailed documentation of a specific illegal event venue case
  - Comprehensive FAQ section addressing common concerns
  - Legal framework, enforcement contacts, and action steps
  - Evidence gallery with examples of violations
- **`other-neighborhoods.html`** - City-wide resource (~650 lines)
  - Austin City Council directory with all 10 districts
  - Universal legal rights and enforcement mechanisms
  - Generic guidance applicable to any Austin neighborhood
- **`assets/`** - Visual evidence and documentation images
- **`CNAME`** - GitHub Pages custom domain configuration

### Design System
Both HTML files use **embedded CSS** with a consistent design system:
- **Color scheme**: Blue gradient headers (#2c5aa0 to #1e4080)
- **Layout**: Container-based responsive design (max-width: 1200px)
- **Components**: Contact cards, alert boxes, legal text blocks, evidence galleries
- **Navigation**: Internal anchor links with cross-page navigation
- **Mobile-first**: Responsive grid layouts with @media queries

### Content Strategy
- **Educational focus**: Legal rights, enforcement mechanisms, documentation guidance
- **Anonymous approach**: Authors remain anonymous for safety
- **Evidence-based**: Screenshots, legal citations, specific violation examples
- **Multi-track enforcement**: Government channels, legal options, community organizing

## Deployment

This is a **GitHub Pages site** with custom domain:
- Hosted at: `northwesthillsatx.com`
- Deployment: Automatic via GitHub Pages from main branch
- No build process - direct HTML/CSS/assets serving

## Development Guidelines

### Content Updates
- **Legal citations**: All laws referenced with direct links to Austin City Code
- **Contact information**: Keep representative contact details current
- **Cross-linking**: Maintain navigation between index.html and other-neighborhoods.html
- **Evidence**: Images in assets/ folder support content claims

### Design Consistency
- **CSS duplication**: Both files contain similar embedded styles - maintain consistency when updating
- **Component styling**: Contact cards, alert boxes, and grids follow established patterns
- **Navigation**: Update both files when adding new pages or sections

### Content Sensitivity
- **Anonymity**: Maintain author anonymity throughout all content
- **Legal accuracy**: Verify all legal citations and enforcement contact information
- **Evidence protection**: Ensure any identifying information is removed from images
- **Tone**: Educational and factual, avoiding confrontational language

## Key Features

### Interactive Elements
- **Anchor navigation**: Internal page linking with smooth scrolling
- **FAQ system**: Numbered questions with direct linking
- **Representative directory**: Searchable by district with contact cards
- **Evidence gallery**: Visual documentation with descriptive captions

### Content Sections
- **Legal framework**: Noise ordinances, zoning laws, deed restrictions
- **Enforcement channels**: City departments, representatives, community resources
- **Documentation guidance**: How to investigate and document violations
- **Action templates**: Sample emails and complaint procedures