# Datastore.News

Weekly intelligence on databases and data infrastructure—featuring dedicated columns on DynamoDB, PostgreSQL, ValKey, and other modern data technologies, plus a sharp editorial perspective on emerging trends and architecture.

Visit [https://datastore.news](https://datastore.news) for the best reading experience.

## About

This site is built with [Hugo](https://gohugo.io/) and uses the [Rusty Typewriter](https://github.com/math-queiroz/rusty-typewriter) theme, optimized for reading long-form technical articles.


## Local Development

### Prerequisites
- Hugo Extended v0.152.2 or later

### Running Locally

```bash
# Clone the repository with submodules
git clone --recurse-submodules https://github.com/fogfish/datastore.news

# Or if already cloned, initialize submodules
git submodule update --init --recursive

# Start the Hugo development server
hugo server --buildDrafts

# Visit http://localhost:1313
```

### Building for Production

```bash
hugo --minify
```

The site will be generated in the `public/` directory.

## Deployment

The site automatically deploys to GitHub Pages via GitHub Actions when changes are pushed to the main branch.

## License

Copyright © 2026 Dmitry Kolesnikov, All Rights Reserved.

All materials contained in this repository are copyrighted and may be used for educational purposes only. The usage of material in other contexts requires written permission.

No material may be modified, edited, or taken out of context.

The author holds rights to publish any materials contained in this document to public domain or use them in commercial environments without any prior notice.

