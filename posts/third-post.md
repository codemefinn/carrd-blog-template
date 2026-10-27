---
title: "Third Post: Testing the Blog Generator"
slug: "third-post"
date: "2026-10-27"
cover: "https://images.unsplash.com/photo-1499750310107-5fef28a66643"
excerpt: "This is the third test post to verify that the blog generator correctly processes Markdown files and updates the published post list."
---

# Third Post: Testing the Blog Generator

This is the **third test article** for the Carrd Blog template.

The purpose of this post is to verify that the GitHub Actions workflow can download the versioned post generator and update `posts.json` correctly.

## What We're Testing

- Markdown file detection
- Front matter parsing
- Title, slug, and date extraction
- Excerpt generation
- Post sorting by date

## A Simple Example

If everything works correctly, this article should appear in the generated `posts.json` file with the following information:

- **Title:** Third Post: Testing the Blog Generator
- **Slug:** `third-post`
- **Date:** 2026-10-27

Once the workflow finishes, check whether the new post appears in the generated list.

**Test result:** The third post has been submitted for testing.
