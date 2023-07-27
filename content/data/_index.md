---
title: Data
summary: Here we describe how to add a page to your site.
date: "2018-06-28T00:00:00Z"

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---

## Source of Data:

- The data was collected by searching for relevant queries such as `male birth control` on Google, with the filter `site:reddit.com`.
- Around **74** posts over **12** years were identified, and the data was exported using [PRAW](https://praw.readthedocs.io/en/stable/_).
- The data consists of the submissions with the comments in it. Also, the user history of the commenters was downloaded.

## Data files

- submissions : **74** posts (in .pkl files)
- users: **21,627** user history of those who commented on the submissions (in .pkl files)
- Out of **41,792** comments read, **5179** comments had deleted user information.
- **22,099** unique users were found from all submissions.
