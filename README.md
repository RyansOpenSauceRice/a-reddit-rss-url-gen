# Reddit RSS Feed URL Generator

![Reddit RSS Generator Interface](images/reddit_rss_generator.png)

A lightweight, single-file tool that runs locally in your browser to generate RSS feed URLs for Reddit subreddits. No containers, no server setup, no dependencies - just open the HTML file and start generating URLs.

## 🔍 Use Case

This tool solves the problem of manually constructing Reddit RSS feed URLs with the correct parameters. Instead of remembering the URL structure and parameters, users can:

1. Enter a subreddit name
2. Select sorting options (Top, Hot, New)
3. Choose a time period (Day, Week, Month, Year, All)
4. Set a post limit
5. Get an instantly generated URL ready to use in any RSS reader

Perfect for users who want to follow specific subreddits in their preferred RSS reader without dealing with the Reddit interface.

## ⚡ Features

- **Simple & Lightweight**: Single HTML file, runs entirely in your browser
- **No Installation**: No dependencies, containers, or server setup required
- **Customizable Parameters**:
  - Sort type (Top, Hot, New)
  - Time period (Day, Week, Month, Year, All)
  - Post limit
- **Live Preview**: See the generated URL update in real-time
- **One-Click Copy**: Copy the URL or label with a single click

## 🚀 Usage

1. Download the HTML file
2. Open it in any modern web browser
3. Enter the subreddit name
4. Select your preferred options
5. Copy the generated URL to your RSS reader

## 💻 Technical Details

- Pure HTML, CSS, and JavaScript
- No external dependencies
- No data collection or tracking
- Runs entirely client-side

## 🔄 Similar Projects

There are several excellent projects in the Reddit RSS ecosystem, each with different approaches and strengths:

### Reddit RSS Tools Ecosystem

| Project | Approach | Tech Stack | Features |
|---------|----------|------------|----------|
| **This Project** | Browser-based URL generator | HTML, CSS, JavaScript | Single file, client-side only, customizable parameters, live preview |
| [trashhalo/reddit-rss](https://github.com/trashhalo/reddit-rss) | Server-based feed enhancer | Go, Docker | Content extraction, NSFW filtering, score limits, OAuth support |
| [johnwarne/reddit-top-rss](https://github.com/johnwarne/reddit-top-rss) | Web application with filtering | PHP, Bootstrap | Score thresholds, content parsing, caching system, Docker deployment |
| [lalitpagaria/reddit-rss-reader](https://github.com/lalitpagaria/reddit-rss-reader) | Python library | Python, PyPI package | Programmatic access, content extraction, datetime filtering |

### Project Characteristics

Each project offers unique capabilities for working with Reddit RSS:

- **This generator** provides a dependency-free solution for quickly creating Reddit RSS URLs
- **trashhalo/reddit-rss** enhances feed content with additional filtering and extraction capabilities
- **johnwarne/reddit-top-rss** offers popularity-based filtering with a preview interface
- **lalitpagaria/reddit-rss-reader** enables programmatic Reddit feed processing in Python applications

The diversity of approaches demonstrates the rich ecosystem of tools available for Reddit RSS integration, each with different technical implementations and feature sets.
