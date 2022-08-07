<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Patrick S. Roberts"
mintoclevel = 2

# Not sure if this will work or not
hasplotly = false


# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Deving The Ops"
website_descr = "Main Site Page for Deving The Ops Group"
website_url   = "https://www.devingtheops.com/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
