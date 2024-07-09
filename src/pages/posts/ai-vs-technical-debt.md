---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Do LLMs increase technical debt?"
pubDate: 2023-08-30
---
Is it possible that relying on machine-generated code will decrease the amount of technical-debt in our systems overall? To what extent is “technical debt” another term for systems we no longer understand? If something is held together by digital duct-tape but works, and can be expanded upon effectively, is it really debt? Why so? 

I guess there’s a complexity ladder, and in some ways personally I think of technical debt as spandrils that we’ve built, that extend from our systems and are no longer expandable. Or code that in some other way limits the way the system can be expanded upon. In other words, technical debt limits the future possibilities, the future branching of systems in motion. This can either be an absolute degradation in the extreme, where the code can no longer be built upon, or just negative back pressure that prevents you from moving as fast as you know you could.

Now let’s return to generative artificial intelligence like GPT-4. Personally, I find them most useful when writing software as:

1. Sophisticated auto completion 
2. “Bicycle of the mind” like expansion of working memory as you build a system, allowing for more expansive system building
3. A “Souped up Rubber Duck” (i.e. forces me to describe what I'm
   trying to solve in text, and then spits back some code that sort of works)
4. A latent-space debugger
5. Paste problems in get prompted for ways to solve
   | In some ways you can think of this as reverse prompting. You get the AI to prompt potential solves for a problem,  and you the human explore those avenues with the AI. 

Generally speaking, I agree with [Simon Willison](https://simonwillison.net/2023/Aug/27/wordcamp-llms/) who talks about how these solutions allow for an expansion in ambition when undertaking new problems. 

How does all of this relate to technical debt? I guess it:

1. Makes branches that were previously closed for expansion and composability open again, LLMs can help you understand where the attachment points are so things that looked “set” and no longer maintainable all of a sudden become malleable
2. Give you super powers in the amount of context you can work with
3. Make problems more tractable, if you feel like you can always break them down with the help of a Language Model.

This isn't very conclusive but I think it's an interesting thing to think about in general. How do language models help or hurt us when trying to build greater, more complex and more ambitious projects?
