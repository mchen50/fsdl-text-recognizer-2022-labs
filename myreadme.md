## Lab 5

[How to prefetch data when processing with GPU](https://discuss.pytorch.org/t/how-to-prefetch-data-when-processing-with-gpu/548/15)

For techniques in computer vision, see the [FFCV library](https://github.com/libffcv/ffcv) and for techniques in NLP, see e.g. [Hugging Face datasets with Arrow](https://huggingface.co/docs/datasets/about_arrow) and [Hugging Face FastTokenizers](https://huggingface.co/learn/nlp-course/chapter6/3).

But really,
the gold star is _decrease in loss per second_.
This metric connects model design choices
and hyperparameters with purely engineering concerns,
so it disrespects abstraction barriers
and doesn't generally lead to actionable recommendations,
but it is, in the end, the real goal:
make the loss go down faster so we get better models sooner.

For PyTorch internals abstractly,
see [Ed Yang's blog post](http://blog.ezyang.com/2019/05/pytorch-internals/).

For more on performance considerations in PyTorch,
see [Horace He's blog post](https://horace.io/brrr_intro.html).


[Choose the best data source for your Amazon SageMaker training job](https://aws.amazon.com/blogs/machine-learning/choose-the-best-data-source-for-your-amazon-sagemaker-training-job/)
