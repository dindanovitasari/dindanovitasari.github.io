# dindanovitasari.github.io

This repository is a simple Jekyll site (resume + blog).

Run locally (Windows)

1. Install Ruby (RubyInstaller recommended): https://rubyinstaller.org/
2. Open a new Command Prompt or PowerShell and install bundler & jekyll:

```powershell
gem install bundler jekyll
```

3. Install gems from the included Gemfile:

```powershell
bundle install
```

4. Serve the site locally:

```powershell
bundle exec jekyll serve --livereload
```

Open http://127.0.0.1:4000 in your browser.

If you prefer, GitHub Pages will build the site automatically when you push the `jekyll-site` branch (or `master`) depending on your Pages settings.
