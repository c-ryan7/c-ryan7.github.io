Built following https://jekyllrb.com/docs/step-by-step/01-setup/

Ideas:
- change your gemfile to include the github pages gem not jekyll? since you're sending it out to get built by github pages, not your local jekyll? see https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
- *jekyll new in a fake directory and copy formatting?*
- figure out a way to make the page.html layout in _layouts use the short_name from the author markdown files in _authors - right now all that's ever displayed is the long name, and the short_name is only used for filtering against the name written in each blog post's front matter in the author field
- create explicit pages for "... oh shoot i forgot. hm. something about me hating websites that work like this and wanting more clear pages that contain material by topic so nothing's "hidden"...   
**note:** you followed the jekyll tutorial pretty much step by step except for pg10 Plugins (of which you tried jekyll-sitemap and it didn't work) and Environment (didn't try)
