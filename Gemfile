source "https://rubygems.org"

# 🔹 Jekyll Core
gem "jekyll", "~> 3.10.0"

# 🔹 GitHub Pages Plugin Group
group :jekyll_plugins do
  gem "jekyll-feed"           # Generates RSS/Atom feed
  gem "jekyll-seo-tag"        # Improves SEO metadata
  gem "jekyll-sitemap"        # Generates a sitemap.xml
  gem "jekyll-paginate"       # Enables pagination
  gem "jekyll-relative-links" # Resolves relative links
  gem "jekyll-github-metadata" # Fetches GitHub repository metadata
  gem "github-pages-health-check" # Checks repo health for GitHub Pages
end

# 🔹 Markdown & Parsing Enhancements
gem "kramdown"                # Markdown processor
gem "kramdown-parser-gfm"     # GitHub Flavored Markdown support
gem "html-pipeline"           # Enables advanced Markdown processing
gem "liquid", "~> 4.0"        # Templating engine for Jekyll

# 🔹 Theme (Minima + Skins)
gem "minima", "~> 2.5"

# 🔹 Syntax Highlighting
gem "rouge"  # Required for code highlighting

# 🔹 GitHub Pages (Optional: If deploying via GitHub Pages)
group :jekyll_pages do
  gem "github-pages", "~> 232" # Uses GitHub Pages compatible dependencies
end

# 🔹 Development Tools
group :development do
  gem "jekyll-admin" # Admin UI for Jekyll
  gem "webrick"      # Required for `bundle exec jekyll serve`
  gem "bundler"
end

# 🔹 Security & Performance
group :production do
  gem "nokogiri"  # Improves XML/HTML parsing
  gem "safe_yaml" # Protects YAML parsing
end
