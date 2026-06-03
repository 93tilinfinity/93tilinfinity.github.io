source "https://rubygems.org"

# GitHub Pages builds this site remotely against a pinned set of gems.
# This Gemfile mirrors that toolchain so `bundle exec jekyll serve` previews
# locally exactly what GitHub Pages will publish.
# See: https://pages.github.com/versions/
gem "github-pages", group: :jekyll_plugins

# Plugins declared in _config.yml (also bundled by github-pages, listed here
# so they're available when running Jekyll directly).
group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jemoji"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem.
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
