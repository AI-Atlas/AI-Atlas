---

title: Jekyll Garden Features

---

###### Wiki links are auto-converted to Hyperlinks
The theme will automatically convert wiki links to inline links. Similarly, `[text](url)` will be converted to external links. 

###### Markdown support
The theme supports all standard markdowns. Have a look at [[Markdown Rendered]] to see preview.

###### External Links are indicated
With link icon next to external links, it's easier to identify internal links and external links 

###### Easy Front-Matter
Using frontmatter, it's easy to configure notes. The capability includes - feed order based on date, option to hide notes from feed, list layout and more.

###### Introducing List layout for Notes
With simple front matter configuration, you can build a list layout (Check [[Credits]] for demo). This is helpful for building manual MoC :) 

###### Static Homepage
Want to have a seperate home page instead of the feed? (Like [my personal website](https://hiran.in/)) - You can configure that at `_config.yml` by change homepage enabled to true. 

###### Support Subpath
You can install Jekyll garden to a URL path, or a sub path (example.com/digitalgarden). To do that, just configure baseurl at  `_config.yml`

###### Private files using .gitignore
Not a theme feature, but if you want to publish part of your obsidian, it's easy. Just create two folders inside `_notes` (Say Public and Private), and use Gitignore to stop syncing your pirvate files with Github! 
