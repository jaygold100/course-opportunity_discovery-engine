# Course Opportunity Discovery Engine

## Overview

Course Opportunity Discovery Engine is a personal research platform designed to identify emerging educational topics, recurring questions, and learning opportunities across multiple public data sources.

The platform aggregates signals from Reddit, Google Trends, and YouTube to help identify subjects that people are actively interested in learning about. These insights are used to support the creation of educational content, courses, tutorials, and learning resources.

## Purpose

### The primary purpose of this application is to:

- Discover emerging topics and trends.
- Identify recurring questions and educational needs.
- Analyze public discussions across multiple platforms.
- Evaluate demand for potential educational content.
- Support data-driven course topic research.

# How Reddit Data Is Used

The application uses the Reddit API to access publicly available posts and comments from selected subreddits.

## Reddit data is used to:

- Identify frequently asked questions.
- Detect recurring problems and discussion themes.
- Measure discussion activity around specific topics.
- Discover educational knowledge gaps.
- Contribute to opportunity scoring and trend analysis.

Reddit data is analyzed alongside information from Google Trends and YouTube to provide broader research insights.

### What the Application Does Not Do

### The application does not:

- Post content to Reddit.
- Vote on posts or comments.
- Send messages to users.
- Moderate communities.
- Scrape private information.
- Collect personally identifiable information.
- Republish Reddit content.
- Store user account credentials.

The application is intended solely for research and analytics purposes.

## Architecture

The system uses a provider-based architecture.

## Current Providers:

- Google Trends
- Reddit API
- YouTube Data API

## Future Providers:

- DataForSEO
- SerpAPI
- Ahrefs
- SEMrush

Each provider operates independently and can be enabled or disabled without affecting the rest of the application.

## Data Processing

Data collection follows a cost-efficient workflow:

1. Collect public discussion signals.
2. Normalize data across providers.
3. Deduplicate similar signals.
4. Calculate opportunity metrics.
5. Generate ranked research opportunities.

All provider requests are cached to minimize API usage and reduce operational costs.

## Privacy and Compliance

This application only accesses publicly available information made available through official APIs.

## The project is designed to:

- Respect platform terms of service.
- Minimize API usage.
- Avoid collection of personal information.
- Support responsible use of public discussion data.

## Current Status

Development Status: In Progress

## Current Scope:

- Authentication
- Provider Management
- Opportunity Discovery
- Trend Analysis
- Opportunity Scoring

## Planned Future Features:

- AI-assisted topic analysis
- Course outline generation
- Educational content planning
- Marketing content generation

## Contact

This project is currently under active development as a personal research and educational opportunity discovery platform.
