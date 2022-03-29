---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-a
    variant: variant-b
    title: Parcerias Mais Recentes
    actions:
      - type: Link
        label: See all posts
        url: /blog
        showIcon: true
        icon: arrowRight
    posts:
      - /images/web3dev.png
      - content/pages/blog/post-three.md
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
          - pt-0
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: FeaturedPostsSection
    showDate: true
---
