---
layout: post
title: Jekyll Blogging with Obsidian
date: 2023-10-22
image: /posts/images/2023-10-22.jpg
author: luis mata
tags:
  - Tech
  - Coding
  - Creative
  - Blogging
---
**I usually write all my blog posts in visual studio code (It is the only editor that I'm comfortable enough with to use daily). I just recently switched over to obsidian and so far the experience is much better.**

## My Writing Process before Obsidian

Before using Obsidian, I wrote my blog posts in markdown in VS Code. Then, I would locally serve the website to ensure that the markdown formatting and links were correct. Once I was satisfied with the content, I committed it to my Git repository. From there, GitHub Pages' CI/CD Pipeline automatically built and published my site. While publishing the site after finishing a post was straightforward, ensuring that everything looked good and functioned correctly was a somewhat involved process. In an ideal scenario, I'd like to write blog posts, including adding images and media, and have them automatically committed to the repository. Editing in plain markdown lacked the visual cues to catch errors as I wrote. Obsidian solves these issues.

## Discovering Obsidian

I discovered Obsidian while searching for an alternative to [Notion](https://notion.so/). Notion is a great tool for those who prefer a task-oriented approach with to-do lists and structured hierarchies. However, this top-down approach doesn't suit my style. I find it more effective to freely express my ideas and thoughts and then organize them into a structure that makes sense to me. Notion relies on a parent-child note system, which is helpful, but I desired a different kind of connectivity that allows all notes to exist on the same level and be interconnected. Obsidian perfectly caters to this need.

## Using Obsidian with Jekyll

Jekyll's site structure is refreshingly straightforward, making it one of the most user-friendly static site generators I've encountered. Despite its simplicity, it offers some remarkable features that streamline the creation of a blog-oriented site. My site, in particular, follows a straightforward layout, consisting of several key folders, such as "data," "includes," "layouts," "pages," "posts" (which serves as my Obsidian vault), and "assets." Additionally, there are essential files like "index.html" and other configuration files. However, the real magic happens within the "posts" directory.

Inside the "posts" directory, you'll find the "```_posts```" subdirectory, which houses all the Markdown posts. There's also an "images" directory for storing images related to your content and a "templates" directory specifically tailored for Obsidian templates. The remarkable part is how it seamlessly integrates with Jekyll.

Every time I open this Obsidian vault, my "daily note" opens inside the "```_posts```" directory, automatically populating it with a template that contains all the necessary data for Jekyll. This setup simplifies the process of creating new posts, ensuring that each one adheres to the desired structure and format, while still allowing for creative flexibility.

In this simple yet effective system, I've found the perfect blend of ease and functionality. Jekyll, with its minimalistic approach, combines harmoniously with Obsidian's intuitive note-taking capabilities, allowing me to effortlessly craft and structure my blog content. This synergy empowers me to focus on what truly matters: the ideas and stories I want to share with the world. As I continue to explore this unique pairing, my digital journey is marked by creativity, organization, and a sense of control over my digital space. It's a dynamic duo that has reshaped how I approach content creation and curation, making my digital workspace a true reflection of my thoughts and ideas.

Until next time,
Luis