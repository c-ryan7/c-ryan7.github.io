Built following https://jekyllrb.com/docs/step-by-step/01-setup/

Ideas:
- change your gemfile to include the github pages gem not jekyll? since you're sending it out to get built by github pages, not your local jekyll? see https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
- *jekyll new in a fake directory and copy formatting?*
- figure out a way to make the page.html layout in _layouts use the short_name from the author markdown files in _authors - right now all that's ever displayed is the long name, and the short_name is only used for filtering against the name written in each blog post's front matter in the author field
