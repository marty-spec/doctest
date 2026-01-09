Best practices for using AI to code
=

Goals
--
We would like to achieve 10x productivity while still maintaing target quality of performance and reliability.

We are in the early stage of figuring out what is right for us, some practices we will standardize on, others will be recomendations, and many others will be personal preferences when they largely only affect a single person.

People should experiment and share what is working for them and what is not, and then we can reflect them into the doc.

The goals
Key practices
--
1. **This is NOT vibe coding** — Understand every line of code. The output quality should be the same as manual development, just 10x faster.
1. **The development cycle is the bottleneck** — GenAI won’t help much if you’re still stuck in a 6-month deployment cycle. Fix testing, fix CI/CD, fix automation.
1. **Small tasks > big tasks** — Ask models to do things they’ll succeed at 99% of the time. Don’t ask for complex one-shot solutions.
1. **Single repo** - Putting all relevant files in a single mono repo increases the odds that the LLM will work correctly. 
1. **Text files** - Simple files are preferable to complex files e.g. .md vs .doc

1. **Context management is everything** — Think of context as a budget. Reset sessions frequently. Don’t overload with tools.
1. **Models learn best by mimicry** — Point to examples instead of writing complex rules.
1. **Invest in local testing** — If the model can’t test locally with high fidelity, you won’t see the benefits. This doesn't just mean unit tests but also being to test against local instance of dependent services running mocks, or using interface mocks in the code.
1. **Intuition requires time** — There’s no shortcut to learning how to work effectively with GenAI. Invest the hours.
1. **Automate** - When there is a good ROI, use AI to automate manual processes. If a process can't be automated can it be changed to be automated, or just entirely eliminated.
