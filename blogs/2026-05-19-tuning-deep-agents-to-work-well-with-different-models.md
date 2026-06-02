---
title: Tuning Deep Agents to Work Well with Different Models
url: https://www.langchain.com/blog/tuning-deep-agents-different-models
date: '2026-05-19'
author: ''
feed_url: https://langchain.com/blog/rss.xml
---
Deep Agents was previously designed in a generic way to work well across model families. Today we’re adding model-specific profiles to adjust prompts, tools, and middleware. We ship profiles for OpenAI, Anthropic, and Google models out of the box, which we see leads to a 10–20 point jump on a subset of tau2-bench over the default harness.
