---
title: "How to Use RLMs in Deep Agents"
url: "https://www.langchain.com/blog/how-to-use-rlms-in-deep-agents"
date: "2026-07-01"
author: ""
feed_url: "https://www.langchain.com/blog/rss.xml"
---
Recursive language models (RLMs) fix context rot by having agents write code that dispatches subagents over context chunks instead of pumping everything in one context window. Deep Agents now implements this through dynamic subagents and a lightweight code interpreter, letting agents programmatically fan out work like grep, map, and reduce over large inputs. We benchmark the approach on OOLONG, a...
