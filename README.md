# 🐘 Elephant

**Never forget your citations.** A command-line tool to track, analyze, and boost your scientific citations across multiple platforms.

## Features

- 📊 Track citations across ORCID, Web of Science, arXiv, and more
- 📈 Monitor citation growth over time
- 💡 Get actionable recommendations to increase visibility
- 🎯 Identify under-cited papers needing promotion
- 🔍 Discover relevant communities and researchers
- 📅 Track submission and publication metrics

## Supported Platforms

- ORCID
- arXiv
- Google Scholar
- Semantic Scholar
- CrossRef
- MDPI, Elsevier, Nature (via CrossRef/DOI)
- Web of Science (requires institutional access)

## Installation

```bash
pip install -r requirements.txt
python setup.py install
```

## Quick Start

```bash
# Initialize your profile
elephant init

# Fetch latest metrics
elephant fetch --all

# View dashboard
elephant dashboard

# Get recommendations
elephant recommend

# Track specific paper
elephant track --doi "10.1234/example"
```

## Commands

- `init` - Set up your accounts and API keys
- `fetch` - Fetch latest data from platforms
- `dashboard` - View your citation metrics
- `recommend` - Get suggestions to boost citations
- `track` - Track specific papers
- `export` - Export data to CSV/JSON
- `alert` - Set up citation alerts
