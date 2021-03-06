# obits-by-molly-ivins

This is a GitHub Pages-hosted Jekyll site that lists citations for obituaries written by the late Molly Ivins. I want to list a citation for every obituary that Molly Ivins wrote.

## How to contribute
Thank you for being interested! I'm grateful for your help.

If you know of an obituary that Molly Ivins wrote that I haven't included already, would you please consider adding an [issue](https://github.com/hillaryfraley/obits-by-molly-ivins/issues) or submitting a [pull request](https://github.com/hillaryfraley/obits-by-molly-ivins/pulls)?

To submit a PR with a new post, please:
1. Follow the file naming and content format of [any post in the `_posts` folder](https://github.com/hillaryfraley/obits-by-molly-ivins/tree/gh-pages/_posts).
2. Write it in GitHub-flavored Markdown.

Include a clear log message for your commit---one line is enough.

`$ git commit -m "Brief summary of your commit, maybe including the name of the obituary subject and year published"`

## Post format explanation

Each post follows this format:

```markdown
---
layout: post
title: "First-name Last-name"
date: 20YY-MM-DD
tags: [tag1, tag2, tag3, ...]
---

"Favorite quote from the obituary."

Molly Ivins, "Obituary Title," *Publication Name* Month DD, YYYY.

#### Read Online
Citation and link for the obituary published online (if available).

#### Also Published In
Other sources where people can find the obituary. Mollly Ivins' books sometimes include obituaries she wrote.

#### Other Versions
Citations and links (if available) for other versions of the obituaries. Some of them were syndicated or republished.

```
If you don't have information for any of the main content sections (like **Also Published In**), just omit those sections. The only required content is the front matter, a quote from the obit, and a citation for the obit.

## Template attribution

The site template is based on a [Jekyll](https://jekyllrb.com/) template developed by [James Williamson](https://github.com/jameswillweb) for his [Lynda.com](https://www.lynda.com/) course [Jekyll for Web Designers](https://www.lynda.com/Jekyll-tutorials/Jekyll-Web-Designers/383124-2.html).

