# What does it all mean?

I have not written any of these problems manually. I have not tested any of them. I have not even attempted to solve any leetcode-style problem (like those used in this benchmark) in my life.
In fact, last time I ever wrote any code manually was years ago.
I literally do not have any skills (and time an patience) to produce such a benchmark.

Yet I did. I have successfully prompted GPT-5 High into generating a distribution of real-world coding challenges with predictable curve of difficulty for LLMs.
It was able to predict the problems' difficulty with reasonable accuracy (as a function of probability) and judge the tested model without even attempting to run the code.
The performance of LLaMa 4 drops predictably on increasingly rare problems, and since this behavior is uniform in all modern LLMs (see the 16 Questions article), this method can be used to evaluate and predict relative problem difficulty in ANY model!

This approach also solves benchmark hacking - since updating an eval becomes just as easy as prompting a strong model for a new probability distribution, updating contaminated evals costs virtually nothing.

My previous test that demonstrated this approach was written completely by hand. This one was created completely by a LLM with no human in the loop - except for prompting and compiling results into this repository, but I believe it can be automated too.
Sure, GPT 5 did not predict problem difficulty with 100% accuracy, but it was accurate *enough*, and I am sure that with some tweaks it is possible to achieve near perfect or perfect prediction of problem difficulty for LLMs.
I'm inviting more competent researchers to investigate the possibility of this.
