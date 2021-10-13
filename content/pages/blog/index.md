---
title: Blog
layout: PageLayout
sections:
  - type: FeaturedPostsSection
    variant: variant-a
    colors: colors-e
    bottomGap: none
    width: wide
    contentAlignHoriz: center
    title: Blog
    textAlign: center
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
  - elementId: ''
    colors: colors-f
    width: wide
    height: tall
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-a
    badge:
      elementId: ''
      label: lorem-ipsum
    title: This Is A Big Hero Headline
    subtitle: This Is Subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: /
        style: secondary
    feature:
      type: ImageBlock
      url: /images/hero.png
      altText: Hero section image
    backgroundImage:
      elementId: ''
      altText: lorem-ipsum
      caption: lorem-ipsum
      opacity: 100
      type: ImageBlock
    type: HeroSection
---
