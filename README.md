# nfeldl.github.io

Source for [Nicole Feldl's academic website](http://nfeldl.github.io), built with Jekyll.

## Local preview

To view the site locally before pushing changes:

```bash
bundle exec jekyll serve
```

Then open `http://localhost:4000` in a browser. The site rebuilds automatically when files are saved.

### First-time setup

Requires Homebrew Ruby 3.3 (not the macOS system Ruby):

1. Install Ruby 3.3: `brew install ruby@3.3`
2. Add to `~/.zshrc`: `export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"`
3. Open a new terminal, then run:
   ```bash
   bundle config set build.eventmachine --with-cppflags=-I/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/usr/include/c++/v1
   bundle install
   ```

## Structure

- `_layouts/` — HTML templates
- `_includes/` — reusable HTML fragments (header, footer)
- `public/css/global.css` — all site styling
- `collections/` — research projects organized by theme
- `*.md` — top-level pages (index, papers, people, join)
