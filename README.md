# Hesham Eraqi's Personal Website

Personal website built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

**Live site:** [https://heshameraqi.github.io](https://heshameraqi.github.io)
**Other web blog** [Simply](simply.blogspot.com)

---

## Building and Viewing Locally

### Prerequisites

1. **Install Homebrew** (macOS package manager, if not already installed):
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
   After installation, add Homebrew to your PATH:
   ```bash
   echo >> /Users/heraqi/.zprofile
   echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/heraqi/.zprofile
   eval "$(/opt/homebrew/bin/brew shellenv zsh)"
   ```

2. **Install Ruby** (version 3.0+ required):
   ```bash
   brew install ruby
   ```
   Add Homebrew Ruby to your PATH:
   ```bash
   echo >> /Users/heraqi/.zprofile
   echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> /Users/heraqi/.zprofile
   export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
   ```

3. **Install Bundler:**
   ```bash
   gem install bundler
   ```

### Setup

```bash
# Navigate to the project directory
cd heshameraqi.github.io

# Install dependencies
bundle install
```

### Run Locally

```bash
bundle exec jekyll serve
```

This starts a local development server. Open your browser and navigate to:

```
http://localhost:4000
```

The site will auto-regenerate when you make changes to source files. Press `Ctrl+C` to stop the server.

#### Options

- **Live reload** (auto-refresh browser on changes):
  ```bash
  bundle exec jekyll serve --livereload
  ```

- **Include drafts** (show posts in `_drafts/`):
  ```bash
  bundle exec jekyll serve --drafts
  ```

- **Custom port:**
  ```bash
  bundle exec jekyll serve --port 4001
  ```

---

## Pushing Changes to Production

This site is deployed automatically via GitHub Pages. To publish updates:

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Description of changes"

# Push to the main branch
git push origin master
```

GitHub Pages will automatically rebuild and deploy the site within a few minutes. You can monitor the build status in the repository's **Actions** tab on GitHub.
