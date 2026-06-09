# Setting up your site

1. Create a new PUBLIC repo named exactly: AsheswariSwain.github.io
2. Copy everything in this folder into the repo root (keep folder structure).
3. Add your photo as: assets/images/profile.jpg  (square crop, ~600x600px works well)
4. Commit and push. GitHub Pages builds Jekyll automatically.
5. Visit https://asheswariswain.github.io — first build takes 1-2 minutes.

To write a new blog post:
- Add a file to _posts/ named YYYY-MM-DD-your-title.md
- Start it with:
  ---
  layout: post
  title: "Your title"
  ---
- Write in Markdown below. Push, and it appears on /blog/ automatically.

To preview locally (optional):
  gem install bundler jekyll
  jekyll serve
