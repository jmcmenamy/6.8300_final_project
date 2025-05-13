# 6.8300 Final Project: Spectral Diffusion with Sine Activations

The code for this project can be found in the .ipynb files

We did training in Google Cloud with $100 in compute provided by the course staff

The final models are around 200MB, so they are not added to this repo

The deliverable for this project is the blog_post/ directory. Open blog.html in the browser to view it.

The html file is based of this gist: https://gist.github.com/liuyang12/2bb234092c0f409239963b070b82d6f9

The [directions](https://drive.google.com/file/d/18ilI716Sxeo481YriD2eHn3mutFcHtWq/view) required the blog post to be viewable without an internet connection. The script tags in the template have web links for their .js source code, so this required downloading that .js and the dependencies the .js has.

- The latest MathJax release was downloaded from: https://github.com/mathjax/MathJax/releases/tag/3.2.2
- strapdown.js and strapdown.css were downloaded from:
    - https://ndossougbe.github.io/strapdown/dist/strapdown.js
    - https://ndossougbe.github.io/strapdown/dist/strapdown.css
- The css file uses google fonts, which were downloaded with this tool: https://gwfh.mranftl.com/fonts/source-sans-3?subsets=cyrillic,cyrillic-ext,greek,greek-ext,latin,latin-ext,vietnamese
- A default polyfill was downloaded with: `curl "https://cdnjs.cloudflare.com/polyfill/v3/polyfill.min.js?features=default" -o polyfill.min.js`


This setup became involved to locally host the html file. Perhaps submitting a latex pdf would have been better...