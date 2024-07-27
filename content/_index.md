# Leave the homepage title empty to use the site title
---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Computational and Statistical Science Laboratory
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Computational and Statistical Science Laboratory** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
   
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        Our laboratory is dedicated to advancing the field of Artificial Intelligence through cutting-edge research and practical applications. We focus on:
        - Asymptotic Statistics
        - Data Analysis and Machine Learning
        - Functional Data Analysis

        We strive to foster a collaborative environment where researchers and students can innovate and excel in their respective areas of expertise.

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
