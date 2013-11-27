recipe-site
===========
Generic recipe site built in jekyll

jekyll version 1.2.1
http://jekyllrb.com

# Install and Run
- gem install jekyll
- jekyll serve
- go to http://localhost:4000

# Making changes
When editing any template file (e.g. markdown .md files) you need to restart jekyll server to see updates.

## Adding recipes
- For each new recipe, you need to create a new folder (e.g. Butter-Cream) and an index.md file inside it.
- Syntax to link to another recipe is not ideal (maybe there is a better way to do it). To link to another recipe (e.g. Butter-Cream) within another recipe, you would do:
```
[Butter Cream](../Butter-Cream)
```

## Adding blog posts
- Jekyll is much better for adding blog posts as it seems that is what it is designed for.  [The wiki](http://jekyllrb.com/docs/posts/) explains it well.

## Writing Markdown
- There are good docs online for markdown.  You can use [Markable Editor](http://markable.in/editor) test it out.
