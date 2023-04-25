# Transformers seminar workshop

Initially created for [PhD Seminar on AI-Assisted Software Engineering](https://inforte.jyu.fi/events/phd-seminar-on-ai-assisted-software-engineering) workshop, Track 3:
 - Fine-tuning a transformer model based on a text corpus (Day 1)
 - Developing custom transformer architecture (Day 2)

## Local setup

 1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
 2. Create a `conda` environment:

        conda env create -f environment.yml

 3. Install [Pytorch](https://pytorch.org/) (prefer `pip` over `conda`):

        pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

 4. Use correct `conda` environment with notebooks.
 5. Download fine-tuned pre-trained BERT from [Google Drive](https://drive.google.com/drive/folders/1_4-H5pz2v5tgWp6xZLMnpS-gSomBQpRN?usp=sharing) (too big for Github)

## Additional resources for learning

Attention is all you need (2017)
 - [arXiv](https://arxiv.org/pdf/1706.03762.pdf)
 - [The Annotated Transformer: notebook of paper with code](http://nlp.seas.harvard.edu/annotated-transformer/)
 - [Stanford CS224N: NLP with Deep Learning | Winter 2019 | Lecture 14 – Transformers and Self-Attention](https://youtu.be/5vcj8kSwBCY)

HuggingFace Course
 - [YouTube playlist](https://www.youtube.com/playlist?list=PLo2EIpI_JMQvWfQndUesu0nPBAtZ9gP1o)

Jay Alammar's blog posts about core concepts
 - [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
 - [The Illustrated GPT-2 (Visualizing Transformer Language Models)](https://jalammar.github.io/illustrated-gpt2/)
 - [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)

Udemy course "Natural Language Processing: NLP With Transformers in Python"
 - [Github repo](https://github.com/jamescalam/transformers)

Peter Bloems blog "Transformers from scratch"
 - [Link](https://peterbloem.nl/blog/transformers)