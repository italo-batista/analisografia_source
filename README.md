
Made with [Hugo](https://gohugo.io/) <3.

# Creating 

1. First, installed blogdown
<pre><code>
installe.packages("blogdown"")
</code></pre>

2. Then, installed hugo
<pre><code>
blogdown::install_hugo()
</code></pre>

3. Used nishanths/cocoa-hugo-theme for creating new site
<pre><code>
new_site(dir = 'blogdown_source', 
         theme = 'nishanths/cocoa-hugo-theme',
         format = 'toml')
</code></pre>

4. [More infos](https://tclavelle.github.io/blog/blogdown_github/). [About theme](https://themes.gohugo.io/cocoa/).

# Using

1. To server site locally
<pre><code>
blogdown::serve_site()
</code></pre>

2. To build site
<pre><code>
blogdown::serve_site()
</code></pre>

3. And to publish, go to your publish dir (this case, analisografia repo) and push commits.

