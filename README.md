burglr
===================================

With `burglr()` you can convienently source R scripts from the web. For a more specific
motivation you can visit our [blog](https://www.statworx.com/de/blog/burglr-stealing-code-from-the-web/)

Feel free to [contact](mailto:andre.bleier@statworx.com) me with input, ideas or some dank memes.


# Usage

<pre><code># install burglr
devtools::install_github("andrebleier/burglr")
# steal code
burglr::burglr("https://github.com/andrebleier/dive/blob/master/dive.R")
</code></pre>
