---
layout: post
title:  "How to Create a Post"
date:   2016-1-20
categories: staq
---
Creating posts on the blog is easy. If you go under the `_posts` directory, you'll see posts set up by date and title. The newest post created will always be the one on the bottom. To create a new post, you click `new file`. the title must be structured with the date then the title of the page, like `YYYY-MM-DD-name-of-post.ext`. There is some started code that has to be included at the top of every page: 
`---
layout: post
title: "example"
date:0000-0-00
categories: staq
---
`
After this is complete, you can begin typing your post. Jekyll can highlight snippets of code by adding `{% highlight ruby %}`insert code `{% end highlight %}`
