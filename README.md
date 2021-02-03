# NYC Python Meetup Blog

Welcome to the NYC Python Meetup Blog!

## Installation

1. Install hugo-extended on your platform by [following instructions here](https://gohugo.io/getting-started/installing/).
2. Run hugo:

```bash
hugo server
```

## How to create a new post?

1. Create new markdown:

```bash
hugo new post/my-new-post.md
```

This will create a markdown with a header:

```markdown
+++
title = "My New Post"
author = ""
date = 2021-02-03T14:12:09-05:00
tags = []
+++
```

2. Edit markdown file.

3. You can add images by placing them in `static/images` and referencing the image by:

```markdown
![NYC Python Logo](/blog/images/nyc_python_meetup_logo.png)
```

4. You can find an example of a [markdown file here](https://github.com/NYCPython/blog/blob/main/content/post/markdown-syntax-guide.md), which is rendered at [here](https://nycpython.github.io/blog/2021/02/03/markdown-syntax-guide/).

## License

This repo is under the [MIT License](LICENSE).
