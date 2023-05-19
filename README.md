Repository contains code to config a 28M param GPT-2 model to train it on tinystories dataset like the TinyStories paper. In the paper, they used several variations of **GPT-2** and **GPT-Neo** model, but **GPT-2** was the spotlight version. They tried to show you can create a SLM (Small Language Model) upto which small size params until it makes sense and compete against LLMs. 

I am only providing the code to config a 28M model as transformers currently having a problem to install my favourite version `transformers==4.2.2` and new transformers requires accelerate if you're using pytorch and requires `partial state` I am not sure how you resolve the partial state error at least now. But, I wanted the method to config a 28M model asap! Which is why, I am only providing the config code. Will later update the repo to add training code. 

Upcoming updates:
* Providing training script
* providing TinyStories dataset in `.txt` format

Please, star the repository if you find it helpful and help others to find it. [Paper Link](https://arxiv.org/abs/2305.07759)