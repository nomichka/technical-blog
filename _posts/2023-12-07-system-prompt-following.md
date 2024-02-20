---
layout: distill
title: Examining Llama 2's Propensity for Following the System Prompt
description: Large Language Models seem to 'forget' their system prompt over the course of a long conversation. Can we measure this effect?
date: 2023-12-07
htmlwidgets: true

# Anonymize when submitting
# authors:
#   - name: Anonymous

authors:
  - name: Naomi Bashkansky*
    url: "https://www.linkedin.com/in/naomibas/"
    affiliations:
      name: Harvard
  - name: Kenneth Li
    url: "https://likenneth.github.io/"
    affiliations:
      name: Harvard
  - name: Martin Wattenberg
    url: "https://www.bewitched.com/"
    affiliations:
      name: Harvard

# must be the exact same name as your blogpost
bibliography: 2023-12-07_system_prompt_following.bib  

# Add a table of contents to your post.
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
toc:
  - name: Introduction
---

## Introduction

I'll write this blog post after the paper is accepted. For now, here is a benchmark for system prompts I created: [https://huggingface.co/datasets/Naomibas/llm-system-prompts-benchmark](https://huggingface.co/datasets/Naomibas/llm-system-prompts-benchmark).

Edit 2/19: Paper has been put on arXiv! See here: [https://arxiv.org/abs/2402.10962](https://arxiv.org/abs/2402.10962).
