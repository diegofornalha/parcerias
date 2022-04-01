---
title: Home
layout: PageLayout
sections:
  - type: FeaturedPostsSection
    elementId: ''
    showDate: true
    showAuthor: true
    showExcerpt: true
    variant: variant-c
    actions:
      - type: Button
        label: View All
        altText: View All Posts
        url: /blog
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    title: Featured
    subtitle: Featured blog posts section example
    colors: colors-h
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
  - type: FeaturedItemsSection
    colors: colors-f
    elementId: ''
    title: Key value propositions
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Faster
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage: null
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Smarter
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage: null
        styles:
          self:
            textAlign: center
      - type: FeaturedItem
        title: Focused
        text: >-
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage: null
        styles:
          self:
            textAlign: center
    actions: []
    columns: 3
    enableHover: false
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
---
